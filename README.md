# .srushti Version Control System

## Overview
**.srushti** is a command-line version control system (VCS) built to efficiently manage file changes in a given directory. It provides a lightweight, intuitive interface for developers and users to track file versions, manage commits, and handle user identities — all within a terminal environment.

---

## Features
- **Easy Initialization**: Instantly set up version control in any directory.
- **File Tracking**: Add, commit, and monitor file changes with simple commands.
- **User Management**: Configure and view usernames tied to commits.
- **Commit Logging**: Track commit history and messages.
- **Robust Error Handling**: Clear guidance for incorrect usage or missing steps.
- **Cross-Platform Support**: Compatible with Windows, macOS, and Linux.

---

## Installation
1. Download the `.exe` file from the [repository](#).
2. Run the file (no extra setup or dependencies required).
3. On launch, you'll be prompted to select a directory for version tracking.

---

## Usage

### 🔧 Initial Setup
- Launch `.srushti` and enter the path of the directory where you want to initialize version control.
- This creates a `.srushti` folder for internal tracking.

### Key Commands

| Command | Description |
|--------|-------------|
| `help` | Displays all supported commands. |
| `location` | Shows the directory currently under version control. |
| `init` | Initializes the VCS in the specified directory. |
| `status` | Shows current tracked/untracked files. |
| `add <file>` | Adds a file to the staging area. |
| `commit -m "<message>"` | Commits staged changes with a message. |
| `rmcommit` | Removes the most recent commit. |
| `rmadd` | Clears all files from the staging area. |
| `push "<dest>"` | Pushes committed changes to a given destination directory. |
| `user show` | Displays the current username. |
| `user set <name>` | Sets your username for future commits. |
| `log` | Lists all previous commits and metadata. |
| `clear` | Clears the terminal screen. |
| `checkout <hash>` | Rolls back to a specific commit using its hash. |
