## 9150 Unstage a File


Further Reading [Git Reset Demystified](http://git-scm.com/2011/07/11/reset.html)


Unstaging will remove file(s) from staging after they have been added using `git add`, so that the files are not included in the next commit. Unstaging will keep your local changes to the files you are unstaging.

In Sublime Text:

`Ctrl-Shift-P` or `⌘-Shift-P` then type: `git unstage`

Then select

**Git: Reset (unstage) All**

or

**Git: Reset (unstage) Current File**

Side Note:

Doing a Reset (hard), instead of unstage as above, will revert your repository to match what is currently on the **remote** repository and lose ALL **local** uncommitted changes.

### Next Section

[Back to Index](https://github.com/sleepepi/howto/blob/master/README.md)
