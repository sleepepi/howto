## 9121 Sublime Package Control

We will be using the Sublime Text 3 instructions located here: [wbond.net/sublime_packages/package_control/installation#ST3](http://wbond.net/sublime_packages/package_control/installation#ST3)

Open Sublime and Click `Preferences > Browse Packages`, or `Sublime Text > Preferences > Browse Packages` on Mac OS X.


**BrowsePackagesDir**

Windows `C:\Users\<username>\AppData\Roaming\Sublime Text 3\Packages`
OSX: `/Users/<username>/Library/Application Support/Sublime Text 3/Packages/`


You will want to navigate to this folder in the Command Prompt/Terminal.

```
cd <BrowsePackagesDir>
git clone https://github.com/wbond/sublime_package_control.git "Package Control"
cd "Package Control"
git checkout python3
```

### Next Section

[9122 - Setup Sublime Git](https://github.com/sleepepi/howto/blob/master/9000-miscellaneous/9122-setup-sublime-git.md)
