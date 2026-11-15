# Mission 2 — Become Comfortable with the Terminal

## 1. Task / objective

Use the command-line interface to inspect folders, create and manage practice files, understand command options and pipes, and explain package managers.

## 2. Work completed

- Explored basic Terminal operations and directory navigation.
- Practised creating, copying, moving, renaming and displaying files.
- Understood replacing file contents and appending new content.
- Studied command flags and options.
- Learned how pipes connect commands and pass output between them.
- Explored Homebrew, a package manager for macOS.
- Checked the installed Homebrew package list.
- Reviewed Formulae and Casks managed by Homebrew.

## 3. Commands / tools used

| Command | Purpose |
|---|---|
| `pwd` | Displays the current working directory. |
| `ls` | Lists files and folders. |
| `ls -l` | Displays a detailed directory listing. |
| `ls -a` | Includes hidden files in the listing. |
| `ls -h` | Displays file sizes in human-readable format when used with suitable listing options. |
| `cd ..` | Moves to the parent directory. |
| `mkdir` | Creates a new directory. |
| `touch` | Creates an empty file. |
| `echo` | Prints text or sends text to a file. |
| `cat` | Displays file contents. |
| `cp` | Copies files. |
| `mv` | Moves or renames files. |
| `rm` | Removes files. |
| `>` | Redirects output and replaces existing file contents. |
| `>>` | Appends output to a file. |
| `|` | Passes one command's output to another command. |
| `head` | Displays the first few lines of input. |
| `brew --version` | Checks the installed Homebrew version. |
| `brew list` | Lists packages managed by Homebrew. |

## 4. My understanding

The Terminal is an application that provides access to the command-line interface. A shell, such as zsh on macOS, interprets commands and executes the requested operations.

The `pwd` command displays the current working directory, while `ls` helps inspect files and folders. File-management commands such as `mkdir`, `touch`, `cp`, `mv` and `cat` make it possible to organise and manage files efficiently.

The `>` operator replaces existing file contents, while `>>` appends new content without removing previous text. Flags modify command behaviour. For example, `ls -la` displays detailed information, including hidden files.

A pipe (`|`) connects commands by passing the output of one command as input to another. For example, `ls -la | head` passes a directory listing to `head`, which displays its first few lines.

A package manager helps install, update and remove software while managing dependencies. Homebrew is a commonly used package manager on macOS. Formulae generally manage command-line tools and libraries, while Casks manage applications and other packaged software.

## 5. Difficulties faced

No major difficulties.

## 6. How I resolved them

Reviewed command behaviour, practised Terminal operations and inspected the Homebrew package list.

## 7. Evidence / files

- `mission-02-terminal/README.md`
- Terminal practice activities.
- Homebrew package-list observation.

## 8. Commit details

- **Commit ID:** `c881b37`
- **Commit message:** `Complete Terminal and file management mission`
- **Branch:** `main`
- **Remote:** `origin`
- **Status:** Successfully pushed to GitHub.
- **Verification:** Working tree clean; local branch is up to date with `origin/main`.