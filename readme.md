git log
git reset --hard <commit_hash>
git push origin main --force
git reflog expire --expire=now --all
git gc --prune=now --aggressive

