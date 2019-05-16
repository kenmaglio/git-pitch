---?image=template/img/vscode.png
@title[Customizing VSCode]

## @color[white](Customizing<br>VSCode)

@fa[arrow-down text-white]

@snap[south docslink span-50 text-white]
Customizing VS Code
@snapend

+++?image=template/img/bg/black.jpg&position=left&size=70% 100%
@title[Heading + List Body]

@snap[east text-17 text-bold text-black span-50]
Make<br>It<br>Your<br>Own
@snapend

@snap[west text-white span-35]
@ul[split-screen-list text-08](false)
- Extensions
  - Must have extensions
- Themes
- Settings.json

@ulend
@snapend

Note:
- Must have extensions
  - Settings Sync
  - Alignment
  - GitLens
  - Markdown All in One
  - Markdown Preview Github
  - Auto-Open Markdown Preview
  - ToDo Tree
  - Spell Right
- Settings

```json
  "workbench.settings.editor": "json",

  "editor.cursorSmoothCaretAnimation": true,
  "editor.renderIndentGuides": true,
  "editor.renderWhitespace":"boundary",
  "editor.minimap.enabled": false,
  "editor.fontLigatures": true,
  "editor.fontFamily": "Fira Code",
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.copyWithSyntaxHighlighting": false,
  "editor.mouseWheelZoom": true,
  "editor.suggestSelection": "recentlyUsed",
  "editor.tabSize": 2,
  "editor.find.autoFindInSelection": true,

  "terminal.integrated.fontFamily": "Fira Code",

  "files.autoSave": "onFocusChange",

  "git.autofetch": true,
  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "git.defaultCloneDirectory": "C:\\_git",

```
