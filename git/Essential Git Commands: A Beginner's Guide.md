# Understanding Git Commands: `init`, `add`, `commit`, `status`, and `log`

Git is a powerful version control system that helps developers manage changes to their codebase over time. In this document, we will explore and demonstrate the use of five essential Git commands: `init`, `add`, `commit`, `status`, and `log`. Additionally, we'll cover how to configure your global username and email for Git.

## Configuring Global Username and Email

Before starting with Git commands, it's important to set your global username and email. This information will be associated with your commits and is essential for collaboration.

### Demo:

1. Open your terminal or command prompt.
2. Run the following commands to set your global username and email:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### Example:

```bash
$ git config --global user.name "John Doe"
$ git config --global user.email "john.doe@example.com"
```

## 1. `git init`

The `git init` command initializes a new Git repository. This command creates a new subdirectory named `.git` that contains all of the necessary metadata for the repository.

### Demo:

1. Open your terminal or command prompt.
2. Navigate to the directory where you want to initialize the Git repository.
3. Run the following command:

```bash
git init
```

### Example:

```bash
$ mkdir my_project
$ cd my_project
$ git init
Initialized empty Git repository in /path/to/my_project/.git/
```

## 2. `git add`

The `git add` command adds changes in the working directory to the staging area. This is the first step in the process of committing changes to the repository.

### Demo:

1. Create or modify a file in your project directory.
2. Run the following command to add the file to the staging area:

```bash
git add <file_name>
```

### Example:

```bash
$ echo "Hello, Git!" > hello.txt
$ git add hello.txt
```

To add all changes in the directory:

```bash
$ git add .
```

## 3. `git commit`

The `git commit` command records the changes in the staging area to the repository's history. Each commit has a unique identifier and contains a message describing the changes.

### Demo:

1. After adding changes to the staging area, run the following command to commit them:

```bash
git commit -m "Your commit message"
```

### Example:

```bash
$ git commit -m "Initial commit with hello.txt"
[master (root-commit) d1e8d16] Initial commit with hello.txt
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt
```

## 4. `git status`

The `git status` command shows the state of the working directory and the staging area. It displays which changes have been staged, which haven't, and which files aren't being tracked by Git.

### Demo:

1. Run the following command to check the status of your repository:

```bash
git status
```

### Example:

```bash
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   hello.txt
```

## 5. `git log`

The `git log` command shows the commit history for the repository. It displays a list of commits along with their messages, authors, and dates.

### Demo:

1. Run the following command to view the commit history:

```bash
git log
```

### Example:

```bash
$ git log
commit d1e8d16b784a5c5a5f65f5e5e0e0e5e5e5e5e5e5 (HEAD -> master)
Author: John Doe <john.doe@example.com>
Date:   Thu May 23 12:34:56 2024 +0000

    Initial commit with hello.txt
```

## Summary

- **`git init`**: Initializes a new Git repository.
- **`git add`**: Adds changes to the staging area.
- **`git commit`**: Records changes to the repository.
- **`git status`**: Displays the state of the working directory and staging area.
- **`git log`**: Shows the commit history.

These commands form the foundation of using Git for version control. By mastering them, you'll be well on your way to managing your codebase effectively.
