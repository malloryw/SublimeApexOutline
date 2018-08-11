## SublimeApexOutline for Sublime Text 3

### Overview

Original code repo [SublimeOutline](https://github.com/warmdev/SublimeOutline), this package shows the outline of your document or class/function name list of your code in a sidebar-style tab.

This repo is the custom solution for making SublimeOutline work for Apex files (from the Sublime MavensMate plugin).
Since Apex symbols are virtually identical to Java's, the 'hacky' solution is to switch the current file's syntax from Apex -> Java, run the 'Outline' logic code, then switch the syntax back from Java -> Apex.

### Manual installation instructions + usage

1. Clone or download this repository to your hard drive using the green `Clone or download` button
2. Rename the cloned or extracted folder to `Outline`. Make sure `outline.py` is at the root of the `Outline` folder.
3. Move the `Outline` folder to your Sublime Text's `Packages` folder. To find the `Packages` folder, click menu `Preferences` > `Browse Packages`.
4. Restart Sublime Text, and press `Cmd + Shift + P` to select your preferred layout (`Browse Mode`)

### Default layout

The outline tab can be set as a sidebar on the left or right. Press `Cmd + Shift + P` and select either `Browse Mode: Outline (Left)` or `Browse Mode: Outline (Right)` to set your preferred layout.

Outline is updated when you save a file or switch between files.

Since the Mavensmate doesn't have the extensive list of Apex symbols (`.tmPreferences` files), we are pulling from the Java syntax symbols to render the outline.

See [SublimeOutline](https://github.com/warmdev/SublimeOutline) for details about other features.

