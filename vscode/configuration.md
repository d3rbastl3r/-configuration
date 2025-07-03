# Configurations in VSCode

This file describes configurations i am using in VSCode.

## Show open files only on the right side

1. `OPEN EDITORS` tab
   - Move the tab to the right side
   - In `Command Pallete` (F1 **OR** Ctrl + Shift + P) search for `Preferences: Open Settings (UI)`
   - In the `Search Settings` bar type `explorer.openEditors.visible`
   - Set `Min Visible` and `Visible` to 16

    > [!IMPORTANT]
    > If you set `Min Visible` to `0`, the `Open Editors` window will cloase after restarting the VSCode

2. Disable file tabs on the top
   - In `Command Pallete` (F1 **OR** Ctrl + Shift + P) search for `Preferences: Open Settings (UI)`
   - In the `Search Settings` bar type `workbench.editor.showTabs`
   - Set `Show Tabs` to `single` or `none`
