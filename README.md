Basic app for Rachel to mess around with keyboard navigation.

State as of April 23:
- The workspace and blocks are from running `npx @blockly/create-package app`
- renderer: zelos
- cursor: line cursor

Controls:
- Basic keyboard nav controls, but with WASD key behaviour moved to the arrow keys.
- `a`: Calls the `announce` shortcut, which prints the type of the currently selected node to the `Announcer Text` area on the left side.
- `r`: Moves the cursor to the root of the current stack.
- `/`: Prints all currently registered keyboard shortcuts to the announcer region.
- `n`: Goes to the next sibling stack (if on a stack) or block (if on a block, input, or field).
- `p`: Goes to the previous sibling stack (if on a stack) or block (if on a block, input, or field).
- `shift-i`: Goes *in* a level of context.
- `shift-o`: Goes *out* a level of context.

To use:
- Download or clone the repository
- `cd keyboard-experiment`
- `npm install`
- `npm start`
