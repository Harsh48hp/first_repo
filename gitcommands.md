⭐ Git Essentials (Daily Use)
🔧 Configure Git
git config --global user.name "Your Name"
git config --global user.email "your@email.com"

📥 Clone a repo
git clone <repo-url>

🔍 Check repo status
git status

➕ Add files
git add <file>
git add .        # add everything

💾 Commit changes
git commit -m "your message"

⬆️ Push to remote
git push
git push origin <branch>

⬇️ Pull latest changes
git pull
git pull origin <branch>

🌿 List branches
git branch
git branch -a        # include remote branches

🌱 Create a branch
git branch <branch-name>

🔀 Switch branch
git checkout <branch-name>

↔️ Create + Switch (Shortcut)
git checkout -b <branch-name>

🔁 Merge a branch
git merge <branch>

🛑 Abort merge
git merge --abort

📜 View history
git log
git log --oneline

🗑 Undo last commit (keep changes)
git reset --soft HEAD~1

❌ Undo last commit (delete changes)
git reset --hard HEAD~1

🌐 Show remote URLs
git remote -v

🗃 Stash changes
git stash
git stash list
git stash apply
git stash pop
