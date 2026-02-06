#Git Commands Cheat Sheet (DevOps)
1. Git Setup & Configuration

git config --global user.name "Your Name"

git config --global user.email "your@email.com"

git config --list

2. Repository Initialization

git init

git clone <repository-url>

3. Repository Status

git status

git status -s

4. Adding Files to Staging Area

git add <file>

git add .

git add -A

5. Removing Files

git rm <file>

git rm --cached <file>

6. Commit Changes

git commit -m "commit message"

git commit -am "add & commit tracked files"

7. View Commit History

git log

git log --oneline

git log --graph --oneline --all

8. Branch Management

git branch

git branch <branch-name>

git branch -d <branch-name>

9. Switching Branches

git checkout <branch-name>

git checkout -b <branch-name>

10. Merging Branches

git checkout master

git merge dev

11. Undo & Restore

git restore <file>

git restore --staged <file>

git reset HEAD <file>

git reset --hard <commit-id>

12. Stashing Changes

git stash

git stash list

git stash apply

git stash pop

13. Remote Repository

git remote -v

git remote add origin <repo-url>

git push origin master

git push -u origin <branch-name>

git pull origin master

14. Tags

git tag

git tag v1.0

git tag -a v1.0 -m "version 1.0"

git push origin --tags

15. Cleanup & Maintenance

git clean -f

git clean -fd

16. Git Help

git help

git <command> --help

git --version

17. Common DevOps Git Workflow

git clone <repo>

git checkout -b feature-branch

git add .

git commit -m "feature added"

git push origin feature-branch
