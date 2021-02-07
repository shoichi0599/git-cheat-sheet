# git-cheat-sheet

## Creating a new repository
echo "# {REPOSITORY_NAME}" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:{USER_ID}/{REPOSITORY_NAME}.git
git push -u origin main

## Pushing an existing repository
git remote add origin git@github.com:{USER_ID}/{REPOSITORY_NAME}.git
git branch -M main
git push -u origin main


