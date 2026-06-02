
# git-hub-1
None selected

Skip to content
Using Gmail with screen readers
1 of 859
(no subject)
Inbox

Ancy Michael
13:18 (0 minutes ago)
to me

Here are your notes in a clean format with a short description of each stage in VS Code and GitHub:

Git and GitHub Notes (VS Code)
Step 1: Add Git Account to VS Code
Install Git on your computer.

Open VS Code.

Open Terminal → Select Git Bash.

Configure your GitHub account:

git config --global user.name "username"
git config --global user.email "emailid"
These commands connect your Git commits with your GitHub account.

Basic Git Commands
1. git status
Checks the current state of files in the repository.

git status
2. git init
Creates a new local Git repository.

git init
3. git add filename
Adds a file to the staging area.

git add filename
Example:

git add index.html
4. git commit -m "message"
Saves staged changes as a commit.

git commit -m "added file"
5. git checkout commitid
Moves to a specific commit.

git checkout commitid
6. git switch - / git checkout master
Returns to the previous branch or switches to the master/main branch.

git switch -
or

git checkout master
Branch Management
7. git branch
Displays all available branches.

git branch
8. git branch dev
Creates a new branch named dev.

git branch dev
9. git checkout dev
Switches to the dev branch.

git checkout dev
GitHub Commands
10. git clone URL
Downloads a GitHub repository to your local computer.

git clone URL
11. git push
Uploads local commits to GitHub.

git push origin main
GitHub Concepts
12. Fork
Creates a personal copy of another user's GitHub repository.

13. Pull Request (PR)
A request to merge your changes into another branch or repository after review.

Git Workflow Stages
Working Directory
↓
git add
↓
Staging Area
↓
git commit
↓
Local Repository
↓
git push
↓
GitHub Remote Repository

Description:

• Working Directory – Files you edit in VS Code.
• Staging Area – Files selected for the next commit.
• Local Repository – Commits stored on your computer.
• Remote Repository (GitHub) – Online copy of your project.
• Push – Sends local commits to GitHub.
• Pull – Downloads updates from GitHub.

These notes are suitable for quick revision before a Git/GitHub lab or interview.

