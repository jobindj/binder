# VSCode


## Tips,Tricks, and Shortcuts


### Compare files

Select the files to compare on the Explorer pane (on the left), right click and chose `Compare Selected` ([stackoverflow](https://stackoverflow.com/questions/30139597/visual-studio-code-is-there-a-compare-feature-like-that-plugin-for-notepad))

### Cursor

- Vertical select : `Alt + Shift`
- Multiple cursors
	- `Alt + click`
	- Vertically add more cursors `Ctrl + Alt + Up/Down`
	- Add cursor at the next occurrence of the word : `Ctrl+D`
	- Add cursor at every occurrence of the word : `Ctrl+Shift+L`


### File Explorer

- Open in Explorer : `Alt + Shft + R`

### Git

- Move to the next/previous diff : `Alt + F5` / `Alt + Shift + F5`

### Search

- in whole workspace:  `Ctrl + Shft + F`
- in a sub-folder within whole workspace:  `Alt + Shft + F`

## Snippets

- To include, a snippet within a snippet (nested snippet)
	- Add the prefix of nested snippet as label
	- Use `Ctrl + Space` at the tab stop
		- Caveat: This breaks the snippet flow. If using this, have the nested snippet as the last tab stop
	- Hat tip : [Stackoverflow](https://stackoverflow.com/questions/58566363/vscode-nested-snippets-or-include-a-snippet-inside-another-snippet)