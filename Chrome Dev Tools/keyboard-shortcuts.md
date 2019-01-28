- [Keyboard shortcuts for opening DevTools](#keyboard-shortcuts-for-opening-devtools)
  - [Global keyboard shortcuts](#global-keyboard-shortcuts)
  - [Elements panel keyboard shortcuts](#elements-panel-keyboard-shortcuts)
  - [Styles panel keyboard shortcuts](#styles-panel-keyboard-shortcuts)
  - [Sources panel keyboard shortcuts](#sources-panel-keyboard-shortcuts)
  - [Code Editor keyboard shortcuts](#code-editor-keyboard-shortcuts)
  - [Performance panel keyboard shortcuts](#performance-panel-keyboard-shortcuts)
  - [Memory panel keyboard shortcuts](#memory-panel-keyboard-shortcuts)
  - [Console panel keyboard shortcuts](#console-panel-keyboard-shortcuts)

<style>
  table {
    width: 100%;
  }
  td:nth-child(1){
    width: 40%;
  }
</style>

# Keyboard shortcuts for opening DevTools

> To open DevTools, press the following keyboard shortcuts while your cursor is focused on the browser viewport:

| Action        | Mac           | Windows / Linux  |
| ------------- | ------------- | ---------------  |
| Open whatever panel you used last | Command+Option+I | F12 or Control+Shift+I |
| Open the Console panel            | Command+Option+J | Control+Shift+J        |
| Open the Elements panel           | Command+Option+C | Control+Shift+C        |


## Global keyboard shortcuts
  The following keyboard shortcuts are available in most, if not all, DevTools panels.

| Action        | Mac           | Windows / Linux  |
| ------------- | ------------- | ---------------  |
| Show Settings	| ? or Function+F1 | ? or F1 |
| Focus the next panel | Command+] | Control+] |
| Focus the previous panel | Command+[ | Control+[ |
| Switch back to whatever docking position you last used. If DevTools has been in its default position for the entire session, then this shortcut undocks DevTools into a separate window | Command+Shift+D | Control+Shift+D |
| Toggle Device Mode | Command+Shift+M | Control+Shift+M |
| Toggle Inspect Element Mode |	Command+Shift+C	| Control+Shift+C |
| Open the Command Menu |	Command+Shift+P |	Control+Shift+P |
| Toggle the Drawer |	Escape | Escape |
| Normal reload	| Command+R |	F5 or Control+R |
| Hard reload	| Command+Shift+R	| Control+F5 or Control+Shift+R |
| Search for text within the current panel. Not supported in the Audits, Application, and Security panels	| Command+F	| Control+F |
| Opens the Search tab in the Drawer, which lets you search for text across all loaded resources	| Command+Option+F	| Control+Shift+F |
| Open a file in the Sources panel	| Command+O or Command+P	| Control+O or Control+P |
| Zoom in	| Command+Shift++	| Control+Shift++ |
| Zoom out	| Command+-	| Control+- |
| Restore default zoom level | Command+0 | Control+0 |
| Run snippet	| Press Command+O to open the Command Menu, type ! followed by the name of the script, then press Enter	| Press Control+O to open the Command Menu, type ! followed by the name of the script, then press Enter |

## Elements panel keyboard shortcuts

| Action        | Mac           | Windows / Linux  |
| ------------- | ------------- | ---------------  |
| Undo change	| Command+Z	| Control+Z |
| Redo change	| Command+Shift+Z	| Control+Y |
| Select the element above / below the currently-selected element	| Up Arrow / Down |Arrow	Up Arrow / Down Arrow |
| Expand the currently-selected node. If the node is already expanded, this shortcut selects the element below it	| Right Arrow	| Right Arrow
| Collapse the currently-selected node. If the node is already collapsed, this shortcut selects the element above it	| Left Arrow	| Left Arrow |
| Expand or collapse the currently-selected node and all of its children | Hold Option then click the arrow icon next to the element's name	| Hold Control+Alt then click the arrow icon next to the element's name |
| Toggle Edit Attributes mode on the currently-selected element	| Enter	| Enter
| Select the next / previous attribute after entering Edit Attributes mode	| Tab / Shift+Tab	| Tab / Shift+Tab |
| Hide the currently-selected element	| H	| H |
| Toggle Edit as HTML mode on the currently-selected element	| Function+F2	| F2


## Styles panel keyboard shortcuts

| Action        | Mac           | Windows / Linux  |
| ------------- | ------------- | ---------------  |
| Go to the line where a property value is declared	| Hold Command then click the property value	| Hold Control then click the property value
| Cycle through the RBGA, HSLA, and Hex representations of a color value	| Hold Shift then click the Color Preview box next to the value	| Hold Shift then click the Color Preview box next to the value |
| Select the next / previous property or value	| Click a property name or value then press Tab / Shift+Tab	| Click a property name or value then press Tab / Shift+Tab |
| Increment / decrement a property value by 0.1	| Click a value then press Option+Up Arrow / Option+Down Arrow	| Click a value then press Alt+Up Arrow / Alt+Down Arrow |
| Increment / decrement a property value by 1	| Click a value then press Up Arrow / Down Arrow	| Click a value then press Up Arrow / Down Arrow |
| Increment / decrement a property value by 10	| Click a value then press Shift+Up Arrow / Shift+Down Arrow	| Click a value then press Shift+Up Arrow / Shift+Down Arrow |
| Increment / decrement a property value by 100	| Click a value then press Command+Up Arrow / Command+Down Arrow	| Click a value then press Control+Up Arrow / Control+Down Arrow |

## Sources panel keyboard shortcuts

| Action        | Mac           | Windows / Linux  |
| ------------- | ------------- | ---------------  |
| Pause script execution (if currently running) or resume (if currently paused)	| F8 or Command+\	| F8 or Control+\ |
| Step over next function call | F10 or Command+'	| F10 or Control+' |
| Step into next function call | F11 or Command+; |	F11 or Control+; |
| Step out of current function | Shift+F11 or Command+Shift+; |	Shift+F11 or Control+Shift+; |
| Select the call frame below / above the currently-selected frame | Control+. / Control+, | Control+. / Control+, |
| Save changes to local modifications	| Command+S	| Control+S |
| Save all changes | Command+Option+S	| Control+Alt+S |
| Go to line | Control+G	| Control+G |
| Jump to a line number of the currently-open file	| Press Command+O to open the Command Menu, type : followed by the line number, then press Enter	| Press Control+O to open the Command Menu, type : followed the line number, then press Enter |
| Jump to a column of the currently-open file (for example line 5, column 9)	| Press Command+O to open the Command Menu, type :, then the line number, then another :, then the column number, then press Enter	| Press Control+O to open the Command Menu, type :, then the line number, then another :, then the column number, then press Enter |
| Go to a function declaration (if currently-open file is HTML or a script), or a rule set (if currently-open file is a stylesheet)	| Press Command+Shift+O, then type in the name of the declaration / rule set, or select it from the list of options	| Press Control+Shift+O, then type in the name of the declaration / rule set, or select it from the list of options |
| Close the active tab | Option+W	| Alt+W |


## Code Editor keyboard shortcuts

| Action        | Mac           | Windows / Linux  |
| ------------- | ------------- | ---------------  |
| Delete all characters in the last word, up to the cursor	| Option+Delete	| Control+Delete |
| Add or remove a line-of-code breakpoint	| Focus your cursor on the line and then press Command+B	| Focus your cursor on the line and then press Control+B |
| Go to matching bracket	| Control+M	| Control+M |
| Toggle single-line comment. If multiple lines are selected, DevTools adds a comment to the start of each line	| Command+/	| Control+/ |
| Select / de-select the next occurrence of whatever word the cursor is on. Each occurrence is highlighted simultaneously	| Command+D / Command+U	| Control+D / Control+U |


## Performance panel keyboard shortcuts

| Action        | Mac           | Windows / Linux  |
| ------------- | ------------- | ---------------  |
| Start / stop recording | Command+E	| Control+E |
| Save recording	| Command+S	| Control+S |
| Load recording	| Command+O	| Control+O |

## Memory panel keyboard shortcuts

| Action        | Mac           | Windows / Linux  |
| ------------- | ------------- | ---------------  |
| Start / stop recording | Command+E	| Control+E |

## Console panel keyboard shortcuts

| Action        | Mac           | Windows / Linux  |
| ------------- | ------------- | ---------------  |
| Accept autocomplete suggestion	| Right Arrow or Tab	| Right Arrow or Tab |
| Reject autocomplete suggestion	| Escape	| Escape |
| Get previous statement	| Up Arrow	| Up Arrow |
| Get next statement	| Down Arrow	| Down Arrow |
| Focus the Console	| Control+\` | Control+` |
| Clear the Console	| Command+K or Option+L |	Control+L |
| Force a multi-line entry. Note that DevTools should detect multi-line scenarios by default, so this shortcut is now usually unnecessary | Command+Return	| Shift+Enter
| Execute	| Return	| Enter |
| Expand all sub-properties of an object that's been logged to the Console	| Hold Alt then click Expand | Hold Alt then click Expand |