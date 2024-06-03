# Pull Requests and Code Reviews on GitHub

This guide provides a step-by-step tutorial on how to create pull requests and perform code reviews on GitHub.

## Table of Contents
- [Introduction](#introduction)
- [Creating a Pull Request](#creating-a-pull-request)
- [Reviewing a Pull Request](#reviewing-a-pull-request)
- [Merging a Pull Request](#merging-a-pull-request)
- [Best Practices](#best-practices)
- [Additional Resources](#additional-resources)

## Introduction
Pull requests (PRs) are a way to propose changes to a repository on GitHub. They are essential for collaboration, allowing team members to review and discuss changes before merging them into the main branch.

## Creating a Pull Request
To create a pull request, follow these steps:

1. **Fork the Repository:**
   If you don't have write access to the repository, fork it first.

2. **Create a Branch:**
   Make sure you are working on a separate branch for your changes.
   ```bash
   git checkout -b feature-xyz
   ```

3. **Commit Your Changes:**
   Make your changes and commit them with a meaningful message.
   ```bash
   git add .
   git commit -m "Add feature XYZ"
   ```

4. **Push Your Changes:**
   Push your branch to your fork or the main repository.
   ```bash
   git push origin feature-xyz
   ```

5. **Open a Pull Request:**
   - Go to the repository on GitHub.
   - Click on the "Pull requests" tab.
   - Click the "New pull request" button.
   - Select the branch you want to merge into, usually `main` or `master`, and the branch you are merging from.
   - Add a title and description for your pull request, explaining the changes you made.
   - Click "Create pull request."

## Reviewing a Pull Request
To review a pull request:

1. **Navigate to the Pull Requests Tab:**
   - Go to the repository on GitHub.
   - Click on the "Pull requests" tab.

2. **Select a Pull Request:**
   - Click on the pull request you want to review.

3. **Review the Changes:**
   - Click on the "Files changed" tab to see the changes made.
   - Add comments by clicking the "+" icon next to the line number.
   - You can also add general comments on the "Conversation" tab.

4. **Approve or Request Changes:**
   - After reviewing, you can either approve the changes, request changes, or comment without approval.
   - Select the appropriate option and submit your review.

## Merging a Pull Request
Once the pull request has been reviewed and approved, you can merge it:

1. **Open the Pull Request:**
   - Go to the pull request on GitHub.

2. **Merge the Pull Request:**
   - Click the "Merge pull request" button.
   - Confirm the merge by clicking "Confirm merge."
   - Optionally, delete the branch by clicking "Delete branch."

## Best Practices
- **Use Descriptive Branch Names:** Clearly describe the purpose of the branch.
- **Write Clear Commit Messages:** Provide meaningful commit messages.
- **Review Thoroughly:** Ensure code is reviewed for functionality, readability, and adherence to coding standards.
- **Communicate:** Use comments to explain the rationale behind significant changes.

## Additional Resources
- [GitHub Pull Requests Documentation](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests)
- [GitHub Code Review Guidelines](https://github.com/features/code-review/)
