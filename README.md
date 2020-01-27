# VSCode

### Setings

```json
{
  "workbench.colorTheme": "Dracula",
  "editor.fontSize": 14,
  "editor.lineHeight": 22,
  "editor.fontFamily": "Fira Code",
  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  
  "editor.rulers": [
    80,
    120
  ],

  "editor.renderLineHighlight": "gutter",

  "terminal.integrated.fontSize": 12,

  "workbench.iconTheme": "material-icon-theme",
  "editor.minimap.enabled": false,
  "javascript.updateImportsOnFileMove.enabled": "never",
  "git.confirmSync": false,
  "git.autofetch": true,
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,
  "git.enableSmartCommit": true,
  "workbench.statusBar.visible": true,
  "eslint.format.enable": true,
 
  "importCost.smallPackageSize": 50,
  "importCost.mediumPackageSize": 100,
  "importCost.smallPackageColor": "#7cc36e",
  "importCost.mediumPackageColor": "#7cc36e",
  "importCost.largePackageColor": "#d44e40",
  "importCost.typescriptExtensions": [
    "\\.tsx?$"
  ],
  "importCost.javascriptExtensions": [
    "\\.jsx?$"
  ],
  "importCost.bundleSizeDecoration": "gzipped",
  "importCost.showCalculatingDecoration": true,
  "importCost.debug": true,
  "liveServer.settings.donotShowInfoMsg": true,
  "color-highlight.markerType": "underline",
  "indentRainbow.colors": [
    "rgba(16,16,16,0.1)",
    "rgba(16,16,16,0.3)",
    "rgba(16,16,16,0.6)",
    "rgba(16,16,16,0.4)",
    "rgba(16,16,16,0.2)",
  ]
}
```

### Extensions 
- Better Comments
- Rainbow Brackets
- Color Highlight
- DotENV
- Dracula Official
- EditorConfig for VS Code
- ESLint
- Import Cost
- indent-rainbow
- Live Server
- Material Icon Theme
- Prettier - Code formatter
- Rocketseat React Native
- Rocketseat ReactJS
- vscode-styled-components

### Snippets

```json

{
	"Create Storybook Story": {
		"scope": "javascript, javascriptreact",
		"prefix": "story",
		"body": [
			"import React from 'react'",
			"import { storiesOf } from '@storybook/react'",
			"import $1 from './$2'",
			" ",
			"storiesOf('$3|$1', module)",
			".add('$1', () => <$1 />)",
			" ",
		],
		"description": "Create Story"
	}
}

```
____

# GIT 

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

