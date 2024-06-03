# Using the Integrated Terminal, Debugging, and Integrating Git and GitHub with Visual Studio Code

This guide provides instructions on using the integrated terminal in VS Code, basic debugging, and integrating Git and GitHub with VS Code.

## Table of Contents
- [Using the Integrated Terminal in VS Code](#using-the-integrated-terminal-in-vs-code)
- [Basic Debugging in VS Code](#basic-debugging-in-vs-code)
- [Integrating Git and GitHub with VS Code](#integrating-git-and-github-with-vs-code)

## Using the Integrated Terminal in VS Code

The integrated terminal in VS Code allows you to run command-line tools without leaving the editor.

### Opening the Terminal
- **Open the Terminal:**
  - Press `Ctrl+` ` (backtick) or `Cmd+` ` (backtick) on macOS.
  - Or go to `View > Terminal` from the top menu.

### Terminal Features
- **Multiple Terminals:**
  - You can open multiple terminal instances by clicking the `+` icon in the terminal tab.
- **Split Terminals:**
  - Click the split terminal icon to open terminals side by side.
- **Terminal Selector:**
  - Use the dropdown menu in the terminal tab to switch between terminal instances.

### Using the Terminal
- **Run Commands:**
  - Execute any command as you would in a standalone terminal, e.g., `git status`, `npm install`, `python script.py`.
- **Configure Shell:**
  - Configure the default shell by going to `Settings > Terminal > Integrated > Shell` and specifying the path to your preferred shell (e.g., Bash, PowerShell, Zsh).

## Basic Debugging in VS Code

VS Code offers a powerful debugging toolset that can be used for various programming languages.

### Setting Up Debugging
1. **Open a File to Debug:**
   - Open the file you want to debug.

2. **Set Breakpoints:**
   - Click in the gutter next to the line numbers to set breakpoints.

3. **Launch Debugger:**
   - Open the Debug view by clicking the Debug icon in the Activity Bar or pressing `Ctrl+Shift+D` (Windows/Linux) or `Cmd+Shift+D` (macOS).
   - Click the green play button or press `F5` to start debugging.

### Debugging Features
- **Step Through Code:**
  - Use the toolbar buttons to step over, step into, or step out of functions.
- **Watch Variables:**
  - Add variables to the watch list to monitor their values.
- **Evaluate Expressions:**
  - Use the debug console to evaluate expressions at runtime.
- **Inspect Call Stack:**
  - View the call stack to understand the sequence of function calls.

### Configuring Debugging
- **Launch Configuration:**
  - Create or edit `launch.json` in the `.vscode` folder to customize debugging configurations for different environments and scenarios.

## Integrating Git and GitHub with VS Code

VS Code provides seamless integration with Git and GitHub, allowing you to manage version control and collaboration directly within the editor.

### Setting Up Git Integration
1. **Initialize a Git Repository:**
   - Open the command palette (`Ctrl+Shift+P` or `Cmd+Shift+P`) and type `Git: Initialize Repository`.

2. **Clone a Repository:**
   - In the command palette, type `Git: Clone` and enter the repository URL.

3. **Open Source Control View:**
   - Click the Source Control icon in the Activity Bar or press `Ctrl+Shift+G` (Windows/Linux) or `Cmd+Shift+G` (macOS).

### Basic Git Commands
- **Stage Changes:**
  - Use the `+` icon next to files to stage changes.
- **Commit Changes:**
  - Enter a commit message in the message box and click the checkmark icon to commit.
- **Push/Pull Changes:**
  - Use the `...` menu for push, pull, and other Git commands.

### GitHub Integration
1. **Install GitHub Extension:**
   - In the Extensions view, search for and install the "GitHub Pull Requests and Issues" extension.

2. **Sign In to GitHub:**
   - Follow the prompts to sign in to your GitHub account.

3. **Managing Pull Requests:**
   - View and manage pull requests directly in the Source Control view.
   - Click on the GitHub icon in the Activity Bar to access GitHub-specific features.

### Additional GitHub Features
- **Create and Review Pull Requests:**
  - Use the GitHub extension to create, review, and merge pull requests.
- **Browse Issues:**
  - View and manage GitHub issues within VS Code.

## Additional Resources
- [VS Code Integrated Terminal Documentation](https://code.visualstudio.com/docs/editor/integrated-terminal)
- [VS Code Debugging Documentation](https://code.visualstudio.com/docs/editor/debugging)
- [VS Code GitHub Integration Documentation](https://code.visualstudio.com/docs/editor/github)
