# Alfred-workflow-view-folder-contents-in-Alfred

# Introduction

This workflow enables you to:
- view in Alfred the contents of a default folder (set in the workflow configuration) simply by typing your chosen keyword and pressing <kbd>↩︎</kbd>;
- alternatively, view in Alfred the contents of a folder you choose by eiher:
	- starting to type the name of the folder after the relevant keyword; or
	- selecting a folder in Finder, using your Universal Actions hotkey and choosing `View folder contents in Alfred`.

By default the folder contents are displayed by most recently added but you can change that to alphabetical order by clicking on the dropdown in the workflow configuration.

If you wish to include the content of sub-folders check `Show contents of sub-folders` in the workflow configuration.  
**Warning**: That may fail with an error message, though no fault of Alfred, on a folder containing many sub-folders.

# The keywords

The keywords will be stripped when you import the workflow (to avoid any conflict with existing keywords you may use) so you will need to set them. I chose `vf`—for "View folder"—for the default and `vfs`—for "View folder (selected)"—for viewing an alternative, selected folder. They are deliberately similar so that both will appear, and can be easily accessed, when I type `vf`.

# Acting on the results displayed in Alfred

When the folder contents are displayed in Alfred you can:
- press <kbd>↩︎</kbd> to open the selected item in its default app;
- press <kbd>→</kbd> to see the actions offered by Alfred for that item;
- use <kbd>⇧</kbd> or <kbd>⌘Y</kbd> to preview any selected item in the list of files (check your settings under `Alfred Preferences → Features → Previews`).
