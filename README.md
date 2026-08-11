cd /path/to/your/project

git add README.md
git commit -m "Add ARC project manifest README"
git branch -M main
git remote set-url origin https://github.com/F1NGERBANG3R/REPOSITORY_NAME.git
git push -u origin main

If the repository has no remote yet, use:
git remote add origin https://github.com/F1NGERBANG3R/REPOSITORY_NAME.git
git push -u origin main

git status
git remote -v
git log -1 --oneline

git ls-remote --heads origin main
