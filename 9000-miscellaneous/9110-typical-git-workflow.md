## 9110 Typical Git Workflow

For help setting up Git on your machine: [Setting up Git](https://help.github.com/articles/set-up-git)

Git is a distributed version control software. This means that when you do `git clone ...` you receive the entire repository along with all past changes onto your local computer.

Git commands make **local** changes and can also make **remote** changes to an upstream or origin repository.

For our purposes, the **remote** Git repository will be the one hosted on GitHub, while the **local** one will be the working copy on your computer.

A common workflow may look like:

- `git pull`
- `git add newfile.txt`
- `git commit -m "Added Newfile"`
- `git push`


### Local Git Commands

`git add` adds a non-tracked file and marks it as staged, or adds an existing tracked file that has been modified and marks it as staged

To unstage a file see: [9150 - Unstage a File](https://github.com/sleepepi/howto/blob/master/9000-miscellaneous/9150-unstage-a-file.md)

`git commit` takes all staged files and bundles them with a message as a change to the repository. This modifies the **local** repository.

To modify a commit message see: [9140 - Amend a Commit Message](https://github.com/sleepepi/howto/blob/master/9000-miscellaneous/9140-amend-a-commit-message.md)

### Remote Git Commands

`git pull` checks the **remote** repository and attempts to merge changes there into your **local** repository.

`git push` takes all commits to the **local** repository and moves them to the **remote** repository.

### Other Git Commands

`git clone` lets you create a copy of a remote repository. All GitHub repositories will provide the SSH and HTTPS urls for repositories.

NOTE: In order to push changes back to the **remote** repository, you will need to use the SSH url, and also have an SSH Key: [9130 - Setup SSH Key](https://github.com/sleepepi/howto/blob/master/9000-miscellaneous/9130-setup-ssh-key.md)

### Next Section

[9120 - Sublime Settings](https://github.com/sleepepi/howto/blob/master/9000-miscellaneous/9120-sublime-settings.md)
