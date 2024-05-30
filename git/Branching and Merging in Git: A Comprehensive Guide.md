# Branching and Merging in Git

## Branching in Git

### What is Branching?
Branching allows you to create a separate version of your project to work on new features, fixes, or experiments without affecting the main codebase.

### Creating a Branch

#### Using Git Command Line
1. **Check Current Branch**:
   ```sh
   git branch
   ```
2. **Create a New Branch**:
   ```sh
   git checkout -b <new-branch-name>
   ```
   Replace `<new-branch-name>` with your desired branch name.

#### Using GitHub Interface
1. **Open GitHub Desktop**:
   - Click on the "Current branch" dropdown.
   - Type the new branch name in the "New branch" field.
   - Click "Create branch".

### Switching Between Branches

#### Using Git Command Line
1. **Switch to an Existing Branch**:
   ```sh
   git checkout <branch-name>
   ```
   Replace `<branch-name>` with the name of the branch you want to switch to.

#### Using GitHub Interface
1. **Open GitHub Desktop**:
   - Click on the "Current branch" dropdown.
   - Select the branch you want to switch to from the list.

## Merging in Git

### What is Merging?
Merging is the process of integrating changes from one branch into another. Usually, you merge a feature branch into the main branch after completing the work.

### Steps to Merge a Branch

#### Using Git Command Line
1. **Switch to the Main Branch**:
   ```sh
   git checkout main
   ```
2. **Merge the Feature Branch**:
   ```sh
   git merge <feature-branch>
   ```
   Replace `<feature-branch>` with the name of the branch you want to merge.

#### Using GitHub Interface
1. **Open GitHub Desktop**:
   - Switch to the main branch using the "Current branch" dropdown.
   - Click on "Branch" > "Merge into current branch".
   - Select the feature branch to merge and click "Merge <branch-name> into main".

## Handling Merge Conflicts

### What are Merge Conflicts?
Merge conflicts occur when changes in different branches conflict and Git cannot automatically merge them.

### Steps to Handle Merge Conflicts

#### Using Git Command Line
1. **Identify Conflicted Files**:
   ```sh
   git status
   ```
2. **Open Conflicted Files**: Manually open the files and look for conflict markers (`<<<<<<<`, `=======`, `>>>>>>>`).
3. **Resolve Conflicts**: Edit the file to resolve the conflicts.
4. **Add Resolved Files to Staging**:
   ```sh
   git add <file-name>
   ```
5. **Commit the Merge**:
   ```sh
   git commit
   ```

#### Using GitHub Interface
1. **Open GitHub Desktop**: After attempting a merge, conflicts will be indicated.
2. **View Conflicts**: Click on "View Conflicts" to open the conflict editor.
3. **Resolve Conflicts**: Use the editor to resolve conflicts by choosing the changes to keep.
4. **Mark as Resolved**: Once resolved, mark the conflicts as resolved.
5. **Commit the Merge**: Click "Commit merge".

### Additional Resources
- [GitHub Documentation](https://docs.github.com/)
- [Pro Git Book](https://git-scm.com/book/en/v2)
