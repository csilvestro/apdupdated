# :old_key: GitHub Key terms
1. Copy your repo to your desktop, in terminal type: **git clone yoururl**
2. Create a new branch, in terminal type: **git checkout -b dev**
3. Switch branches, in terminal type: **git checkout branchname**
4. Fetch provides a safe way to review the information before committing to your local branch, in terminal type: **git fetch**
6. Create an upstream -  push changes to github:  **git push --set-upstream origin my-branch**
7. Push changes to remote repo: **git push origin my-branch**
8. Pull changes from a branch: **git pull  origin my-branch**
9. Delete branch Local: **git branch -d my-branch**
10. Check Branches: **git branch**

**Merge changes - make sure you are on new branch**
```
git merge my-branch
Or
git push <branch with new changes>:<branch you are pushing to>

git push origin dev:master
git push origin branch:master
```

![Git Cheat Sheet](/images/gitcheatsheet.JPG)