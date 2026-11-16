# P3 – Feature-branch Git workflow

## Aim
Create a separate feature branch, make a change, commit it, and merge it into the main branch.

## Commands
```bash
git switch -c feature/about-section
git status
git add .
git commit -m "Add about section"
git switch main
git merge feature/about-section
git push
```

## Result
The feature branch is merged into `main`, and the updated repository is pushed to GitHub.
