# git-cheat-sheet
A cheat sheet for `git` commands (+ `gh-md-toc` command)

## Table of Contents
   * [git-cheat-sheet](#git-cheat-sheet)
      * [git commands](#git-commands)
         * [Creating a new repository](#creating-a-new-repository)
         * [Pushing an existing repository](#pushing-an-existing-repository)
      * [gh-md-toc command](#gh-md-toc-command)
         * [Creating a table of contets](#creating-a-table-of-contets)

## `git` commands
### Creating a new repository
```bash
echo "# {REPOSITORY_NAME}" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:{USER_ID}/{REPOSITORY_NAME}.git
git push -u origin main
```

### Pushing an existing repository
```bash
git remote add origin git@github.com:{USER_ID}/{REPOSITORY_NAME}.git
git branch -M main
git push -u origin main
```

## `gh-md-toc` command
### Creating a table of contets
```bash
{INSTALLED_PATH}/gh-md-toc README.md
# Output example
#---------------------------------------
# Table of Contents
# =================
#   * [git-cheat-sheet](#git-cheat-sheet)
#      * [Creating a new repository](#creating-a-new-repository)
#      * [Pushing an existing repository](#pushing-an-existing-repository)
```


