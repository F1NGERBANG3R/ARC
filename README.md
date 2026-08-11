cd /path/to/your/ARC-project

git add README.md
git commit -m "Add ARC project manifest README"

git remote set-url origin https://github.com/F1NGERBANG3R/ARC.git
git push -u origin main

git status
git remote -v
git log -1 --oneline
git ls-remote --heads origin main
