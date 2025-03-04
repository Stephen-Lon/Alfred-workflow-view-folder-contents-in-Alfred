# Alfred-workflow-view-folder-contents

# Introduction and use

This workflow enables you to:
- view in Alfred the contents of a default folder (set in the workflow configuration) simply by typing your chosen keyword and pressing <kbd>↩︎</kbd> (but see also "Immediate trigger of keyword to view default folder" below);
- alternatively, view in Alfred the contents of a folder you choose by either:
	- starting to type the name of the folder after the relevant keyword; or
	- selecting a folder in Finder, using your Universal Actions hotkey and choosing `View folder contents`.

By default the folder contents are displayed by most recently added but you can change that to alphabetical order by clicking on the dropdown in the workflow configuration.

If you wish to include the content of sub-folders check `Show contents of sub-folders` in the workflow configuration.  
**Warning**: That may fail with an error message, though no fault of Alfred, on a folder containing many sub-folders.

# Acting on the results displayed in Alfred

When the folder contents are displayed in Alfred you can:
- press <kbd>↩︎</kbd> to open the selected item in its default app;
- press <kbd>→</kbd> to see the actions offered by Alfred for that item;
- use <kbd>⇧</kbd> or <kbd>⌘Y</kbd> to preview any selected item in the list of files (check your settings under `Alfred Preferences → Features → Previews`).

# The keywords

I chose `vfd` (for `view folder default`) and `vfs` (for `view folder selected`). That has the advantage that you see both options in Alfred when you type merely `vf`.

# Immediate trigger of keyword to view default folder

In the workflow configuration you can check the box `Trigger keyword immediately` which will dispense with the need to press  <kbd>↩︎</kbd> following the keyword you use to open the default folder. If you check that the default folder will open immediately after you have typed the relevant keyword.

## Important warnings when using `Trigger keyword immediately`

1. In Alfred Preferences → Advanced, under `History:`, you should ensure `Show latest query if within 5 minutes` is *not* checked. If you don’t do that you could end up in a loop of repeatedly triggering the workflow.

2. If you want to check the option to trigger the keyword immediately *and* change the keyword for viewing the default folder be *very* careful about the keyword you choose for viewing the default folder. Remember that as soon as you type the keyword the workflow will trigger—so you’ll never have the chance to type more characters after you’ve typed the keyword…which may hinder future searches in Alfred. You need to choose a unique keyword that is also not the start of any other term for which you may wish to search.
