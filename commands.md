#Git Commands Cheat Sheet (DevOps Friendly)
1. Git Setup & Configuration
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
git config --list

2. Repository Initialization
git init
git clone <repository-url>

3. Checking Repository Status
git status
git status -s

4. File Management (Working Directory)
git add <file>
git add .
git add -A
git rm <file>
git rm --cached <file>

5. Committing Changes
git commit -m "commit message"
git commit -am "add & commit tracked files"

6. Viewing Commit History
git log
git log --oneline
git log --graph --oneline --all

7. Branch Management
git branch
git branch <branch-name>
git checkout <branch-name>
git checkout -b <branch-name>
git branch -d <branch-name>

8. Switching Between Branches
git checkout master
git checkout dev

9. Merging Branches
git checkout master
git merge dev

10. Undo & Restore
git restore <file>
git restore --staged <file>
git reset HEAD <file>
git reset --hard <commit-id>

11. Stashing Changes
git stash
git stash list
git stash apply
git stash pop

12. Remote Repository Management
git remote -v
git remote add origin <repo-url>
git push origin master
git push -u origin <branch-name>
git pull origin master

13. Deleting Files & Cleanup
rm <file>
git clean -f
git clean -fd

14. Tagging
git tag
git tag v1.0
git tag -a v1.0 -m "version 1.0"
git push origin --tags

15. Git Help
git help
git <command> --help
git --version

16. Common DevOps Git Workflow
git clone <repo>
git checkout -b feature-branch
git add .
git commit -m "feature added"
git push origin feature-branch
