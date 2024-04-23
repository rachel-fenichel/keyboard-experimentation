Basic app for Rachel to mess around with keyboard navigation.

State as of April 23:
- The workspace and blocks are from running `npx @blockly/create-package app`
- renderer: zelos
- cursor: line cursor,
- Controls:
  - Basic keyboard nav controls, but with WASD key behaviour moved to the arrow keys
  - Pressing `a` calls the `announce` shortcut, which prints the type of the currently selected node to the `Announcer Text` area on the left side.


Possible next steps:
- Make the announcer more interesting
- Add the ability to jump between groups/jump to siblings
