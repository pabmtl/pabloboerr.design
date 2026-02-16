# Deploy from the project folder (not from ~)

Run these commands **from inside this folder** (`pabloboerr-design`).

In Terminal:

```bash
cd /Users/pabloboerr/pabloboerr-design

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/pabmtl/pabloboerr.design.git
git push -u origin main
```

For the **work** site, use the work folder and its repo:

```bash
cd /Users/pabloboerr/work-pabloboerr-design

git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/pabmtl/WORK_REPO_NAME.git
git push -u origin main
```

(Replace `WORK_REPO_NAME` with the actual work repo name on GitHub.)
