# Mission 6 — Git and GitHub

## 1. Mission Objective

To understand version control, practise Git commands, create and use branches, publish changes to GitHub, and create a Pull Request.

## 2. Basic Git Workflow

| Git operation | Command | Explanation |
|---|---|---|
| Check status | `git status` | Shows the current branch and file changes. |
| Stage changes | `git add README.md` | Selects changes for the next commit. |
| Create commit | `git commit -m "message"` | Records staged changes in local Git history. |
| View history | `git log --oneline` | Displays recent commits. |

### Difference between staging and committing

Staging selects the changes that should be included in the next commit. Committing records those staged changes as a snapshot in the local Git repository.

## 3. Branch Creation and Usage

Created a new branch named `update-about` using:

`git switch -c update-about`

Verified branches using:

`git branch`

Updated the root `README.md` by adding a section titled **My Learning**.

Staged and committed the change:

`git add README.md`

`git commit -m "Add personal learning summary to README"`

Commit ID: `f87d0bc`

Published the branch:

`git push -u origin update-about`

## 4. Pull Request

Created Pull Request #1 on GitHub.

- Title: Add personal learning summary to README
- Source branch: `update-about`
- Target branch: `main`
- Commit: `f87d0bc`
- Status: Open and not merged
- Merge conflicts: None reported

The Pull Request requests a review of the README changes before merging them into the main branch.

## 5. Git Command Glossary

| Operation | Command | Meaning |
|---|---|---|
| Initialise a repository | `git init` | Starts Git version control in a folder. |
| Check status | `git status` | Displays repository status. |
| Stage changes | `git add` | Selects changes for committing. |
| Commit changes | `git commit` | Records staged changes. |
| View history | `git log` | Displays commit history. |
| Create or list branches | `git branch` | Creates or lists branches. |
| Switch branches | `git switch` | Changes the current branch. |
| Publish changes | `git push` | Publishes commits to a remote repository. |
| Retrieve remote changes | `git pull` | Fetches and integrates remote changes. |

## 6. My Understanding

- Git is a version control system that tracks changes in a project.
- GitHub hosts Git repositories online and supports collaboration.
- A branch provides a separate line of development.
- A Pull Request allows changes to be reviewed before merging.
- Staging and committing are different steps in the Git workflow.
- Pushing publishes local commits to GitHub.

## 7. Difficulties Faced and Solutions

I learned that changes must be staged before creating a normal Git commit. I also understood that commands such as `git push` publish commits to a remote repository, while `git commit` only records them locally.

## 8. Evidence and Files

- Root `README.md` — contains the My Learning section.
- Git branch `update-about` — published to GitHub.
- Pull Request #1 — open and not merged.
- This README — Git explanations and command glossary.

## 9. Commit Details

- Commit ID: `1b186be`
- Commit Message: `Complete Git and GitHub collaboration mission`
- Branch: `update-about`
- Remote: `origin`
- Status: Successfully pushed to GitHub.