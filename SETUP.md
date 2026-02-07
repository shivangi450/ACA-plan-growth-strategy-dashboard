# GitHub Upload Steps (Quick)

1. Create a new GitHub repository (public or private).
2. On your computer, place this folder as the repository root.
3. Initialize git and push:

```bash
git init
git add .
git commit -m "Initial commit: Tableau dashboard project"
git branch -M main
git remote add origin <YOUR_REPO_URL>
git push -u origin main
```

Tips:
- Keep `.twbx` files in the repo so recruiters can open them easily.
- If exports become large, store them in Releases or Git LFS.
