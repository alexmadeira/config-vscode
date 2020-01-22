# VSCode

### Setings

```json
{
  "workbench.colorTheme": "Dracula",
  "editor.fontSize": 16,
  "editor.lineHeight": 24,
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  "editor.rulers": [
    80,
    120
  ],
  "editor.renderLineHighlight": "gutter",
  "editor.formatOnSave": true,
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.shell.osx": "/bin/zsh",
  "workbench.iconTheme": "material-icon-theme",
  "explorer.confirmDelete": false,
  "editor.minimap.enabled": false,
  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "window.zoomLevel": -1,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "liveServer.settings.donotShowInfoMsg": true
}
```

### Extensions 

- Color Highlight
- DotENV
- Dracula Official
- EditorConfig for VS Code
- ESLint
- Import Cost
- Live Server
- Material Icon Theme
- Prettier - Code formatter
- Rocketseat React Native
- Rocketseat ReactJS
- vscode-styled-components

### GitConfig

[alias]

> ci = commit

> co = checkout

> cm = checkout master

> cb = checkout -b

> st = status -sb

> sf = show --name-only

> lg = log --pretty=format:'%Cred%h%Creset %C(bold)%cr%Creset %Cgreen<%an>%Creset %s' --max-count=30
 
> incoming = !(git fetch --quiet && git log --pretty=format:'%C(yellow)%h %C(white)- %C(red)%an %C(white)- %C(cyan)%d%Creset %s %C(white)- %ar%Creset' ..@{u})

> outgoing = !(git fetch --quiet && git log --pretty=format:'%C(yellow)%h %C(white)- %C(red)%an %C(white)- %C(cyan)%d%Creset %s %C(white)- %ar%Creset' @{u}..)
 
> unstage = reset HEAD --

> undo = checkout --

> rollback = reset --soft HEAD~1

