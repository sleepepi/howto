## 9140 Amend a Commit Message

Based on [Stack Overflow: How do I edit an incorrect commit message in Git](http://stackoverflow.com/questions/179123/how-do-i-edit-an-incorrect-commit-message-in-git)

If you want to change your latest commit message (of a commit that has not yet been pushed!), you can type:

```
git commit --amend -m "New commit message"
```

Note that you should NOT attempt to change the commit message if the commit has already been pushed.

### Next Section

[9150 - Unstage a File](https://github.com/sleepepi/howto/blob/master/9000-miscellaneous/9150-unstage-a-file.md)
