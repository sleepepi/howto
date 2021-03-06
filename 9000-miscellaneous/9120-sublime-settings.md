## 9120 Sublime Settings

We use [Sublime Text](http://www.sublimetext.com/) to edit most changes on our GitHub repositories.

The following conventions should be added to the `Preferences: Settings - User` settings file.

Type `Ctrl-Shift-P` or `⌘-Shift-P` then type `Preferences: Settings - User`.

At the bottom of this file add the following four lines and make sure you use correct JSON syntax.

```json
{
  ...,
  "ensure_newline_at_eof_on_save": true,
  "tab_size": 2,
  "translate_tabs_to_spaces": true,
  "trim_trailing_white_space_on_save": true,
  "default_line_ending": "unix"
}
```

- **ensure_newline_at_eof_on_save**: This adds a standard newline to the end of files on when the file is saved.
- **tab_size** and **translate_tabs_to_spaces**: We indent using spaces, and this specifies that our standard indent is two spaces.
- **trim_trailing_white_space_on_save**: This removes whitespace from the end of each line when the file is saved.


### Next Section

[9121 - Sublime Package Control](https://github.com/sleepepi/howto/blob/master/9000-miscellaneous/9121-sublime-package-control.md)
