# Git + CSS Links

## Handy Links

- [Flexbox Froggy](https://flexboxfroggy.com/)
- [Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [Bootstrap](https://getbootstrap.com/)
- [Markdown CheatSheet](https://5pence.net/markdown-cheat-sheet/)

## Git IS NOT GitHub

    - git is a local repository
    - gitHub is a remote one
    
## Git Commands

- `git clone gitUrl`
  - Using the URL from Github/remote repository (repo) clones the project to folder you are currently in
- `git status`
  - Shows the current status of your working directory and staging area, indicating any changes (untracked, modified, or staged files) in red or green.
- `git add .`
  - Adds all files in your current directory and subdirectories to the staging area, preparing them to be committed.
- `git add filename`
  - Adds a single file (replace filename with the actual name) to the staging area. You can specify multiple filenames separated by spaces.
- `git commit -m 'sensible commit message'`
  - Commits the staged changes with a message. The -m flag allows you to provide a commit message in-line.
- `git branch branchName`
  - Creates a new branch with the specified branchName without switching to it.
- `git checkout branchName`
  - Switches to the specified branch. If the branch doesn't exist, it will throw an error.
- `git checkout -b newBranchName`
  - Creates a new branch and switches to it in one command.
- `git merge branchname`
  - Merges the specified branchName into your current branch. If there are conflicts, Git will notify you and require manual resolution.
- `git pull`
  - Fetches the latest changes from the remote repository and merges them into your current branch.
- `git push`
  - Pushes your committed changes to the remote repository, syncing your local commits.
- `git push --force`
  - This command force-pushes your local changes to the remote repository, potentially overwriting commits that already exist on the remote branch.  
  - Using --force can be risky because it rewrites history. If someone else has pulled the branch you're force-pushing to and made changes, your force-push can overwrite their commits. So, it’s usually good practice to use it carefully, particularly in collaborative projects.

## Diagram

![git branching](https://raw.githubusercontent.com/5pence/gitIntro/refs/heads/main/assets/images/git2.png)
