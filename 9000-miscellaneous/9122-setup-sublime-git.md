## 9122 Setup Sublime Git

Based on instructions here: [https://github.com/kemayo/sublime-text-2-git/wiki](github.com/kemayo/sublime-text-2-git/wiki)


Open Sublime and Click `Preferences > Browse Packages`, or `Sublime Text > Preferences > Browse Packages` on Mac OS X.


**BrowsePackagesDir**

Windows `C:\Users\<username>\AppData\Roaming\Sublime Text 3\Packages`
OSX: `/Users/<username>/Library/Application Support/Sublime Text 3/Packages/`

You will want to navigate to this folder in the Command Prompt/Terminal.

```
cd <BrowsePackagesDir>
git clone git://github.com/kemayo/sublime-text-2-git.git Git
cd Git
git checkout python3
```

### Next Section

[9130 - Setup SSH Key](https://github.com/sleepepi/howto/blob/master/9000-miscellaneous/9130-setup-ssh-key.md)
