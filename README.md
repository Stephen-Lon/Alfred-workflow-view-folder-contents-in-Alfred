# Alfred-workflow-view-folder-contents-in-Alfred

# Introduction

This workflow enables you to:
- view in Alfred the contents of a default folder (set in the workflow configuration) simply by typing your chosen keyword and pressing <kbd>↩︎</kbd>;
- alternatively, view in Alfred the contents of a folder you choose by eiher:
	- starting to type the name of the folder after the relevant keyword; or
	- selecting a folder in Finder, using your Universal Actions hotkey and choosing `View folder contents in Alfred`.

By default the folder contents are displayed by most recently added but you can change that to alphabetical order if you wish (see below).

# The keywords

The keywords will be stripped when you import the workflow (to avoid any conflict with existing keywords you may use) so you will need to set them. I chose `vf`—for "View folder"—for the default and `vfs`—for "View folder (selected)"—for viewing an alternative, selected folder. They are deliberately similar so that both will appear, and can be easily accessed, when I type `vf`.

# Changing how the folder contents are displayed

If you double click on the `Folder Contents` Automation Task you can click on `By Most Recently Added`, under `Sort:`, to change the order of the displayed folder contents to alphabetical.

# Including the content of sub-folders

If you wish to include the content of sub-folders double click on the `Folder Contents` Automation Task and check `Recursive:` `Act on directory contents`.  

**Warning**: That may fail with an error message, though no fault of Alfred, on a folder containing many sub-folders.

# Acting on the results displayed in Alfred

When the folder contents are displayed in Alfred you can:
- press <kbd>↩︎</kbd> to open the selected item in its default app;
- press <kbd>→</kbd> to see the actions offered by Alfred for that item.
