## Common Git Commands

| Purpose | Command | Notes |
|----------|----------|-------|
| **Initialize a new repo** | `git init` | Turns current folder into a new Git repo |
| **Clone a repository** | `git clone https://github.com/username/repository-name.git` | Creates a local copy of a remote repo |
| **Clone via SSH** | `git clone git@github.com:username/repository-name.git` | Requires SSH key setup |

| --- | --- | --- |
| **Check repo status** | `git status` | Shows branch and uncommitted changes |
| **Create placeholder file** | `touch data/.gitkeep` | Common way to keep empty folders in Git |
| **Add files to staging** | `git add data/.gitkeep` | Prepares file(s) for commit |
| **Commit changes** | `git commit -m "add empty data folder"` | Records staged changes with message |
| **Push changes to GitHub** | `git push` | Pushes committed changes to remote branch |

| --- | --- | --- |
| **List branches** | `git branch` | Shows all local branches |
| **Create a new branch** | `git branch feature-branch` | Makes a new branch without switching to it |
| **Switch branches** | `git switch feature-branch` | Switches to an existing branch |
| **Create and switch** | `git switch -c new-branch` | Creates and immediately switches to a new branch |
| **Merge branches** | `git merge feature-branch` | Combines changes from another branch into current branch |

| --- | --- | --- |
| **Verify current remotes** | `git remote -v` | Lists connected remote URLs |
| **List all remote names** | `git remote` | Shows remote names like `origin`, `upstream`, etc. |
| **Add a new remote** | `git remote add origin https://github.com/username/repo.git` | Connects local repo to GitHub |
| **Remove a remote** | `git remote remove origin` | Unlinks GitHub connection (no longer pushes/fetches) |

| --- | --- | --- |
| **Remove Git tracking** | `rm -rf .git` | Deletes `.git` directory (makes folder non-repo) |
