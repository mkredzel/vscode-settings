# VS Code Settings

# Font

* Consolas

# Extensions

```
abusaidm.html-snippets
ajshortt.tokyo-hack
anseki.vscode-color
bceskavich.theme-dracula-at-night
benawad.VSinder
bierner.color-info
CoenraadS.bracket-pair-colorizer
dbaeumer.vscode-eslint
DiemasMichiels.emulate
dracula-theme.theme-dracula
ecmel.vscode-html-css
esbenp.prettier-vscode
evan-buss.font-switcher
FallenMax.mithril-emmet
formulahendry.auto-rename-tag
fosshaas.fontsize-shortcuts
GitHub.github-vscode-theme
immament.vscode-ngrx-uml
iocave.monkey-patch
marqu3s.aurora-x
max-SS.Cyberpunk
ms-python.python
ms-toolsai.jupyter
ms-vsliveshare.vsliveshare
NativeScript.nativescript
Nur.just-black
octref.vetur
PKief.material-icon-theme
pkosta2006.tns-cli
redhat.java
ritwickdey.LiveServer
sdras.night-owl
SonarSource.sonarlint-vscode
syler.sass-indented
tinkertrain.theme-panda
VisualStudioExptTeam.vscodeintellicode
vscjava.vscode-java-debug
vscjava.vscode-java-dependency
vscjava.vscode-java-pack
vscjava.vscode-java-test
vscjava.vscode-maven
vscode-icons-team.vscode-icons
wesbos.theme-cobalt2
whizkydee.material-palenight-theme
Wscats.eno
xabikos.JavaScriptSnippets
```

## Themes/Color

* Current theme:
  * [Just Black](https://marketplace.visualstudio.com/items?itemName=nur.just-black)
* Previous theme:
  * [Cobalt2](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2)
* [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=coenraads.bracket-pair-colorizer)
  * Matching parenthesis and curly brackets to with colors

## Workflow

* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
  * Automatically add HTML/XML close tag
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * Automatically rename paired HTML/XML tag
* [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
  * Change the font size with keyboard shortcuts.

## Style/Formatting

* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * Automatically format JavaScript, JSON, CSS, Sass, and HTML files.

## Useful/Extra

* [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Collaborative editing, debugging, and more inside VS Code

# Settings

```json
{
  "explorer.openEditors.visible": 0,
  "editor.snippetSuggestions": "top",
  "emmet.showAbbreviationSuggestions": false,
  "editor.formatOnPaste": false,
  "window.zoomLevel": 0,
  "editor.fontLigatures": true,
  "terminal.integrated.fontSize": 15,
  "files.autoSave": "off",
  "markdown.preview.fontSize": 15,
  "editor.detectIndentation": true,
  "eslint.enable": true,
  // "files.exclude": { "**/.*": true },
  "eslint.validate": [
    {
      "language": "vue",
      "autoFix": true
    },
    {
        "language": "typescript",
        "autoFix": true
      },
    {
      "language": "html",
      "autoFix": true
    },
    {
      "language": "javascript",
      "autoFix": true
    }
  ],
  "workbench.startupEditor": "newUntitledFile",
  "editor.suggestSelection": "first",
  "[javascript]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[json]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[html]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "[css]": {
    "editor.defaultFormatter": "HookyQR.beautify"
  },
  "liveshare.featureSet": "insiders",
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "diffEditor.ignoreTrimWhitespace": false,
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "liveshare.anonymousGuestApproval": "accept",
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.colorCustomizations": {},
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "comment.block"
        ],
        "settings": {
          "fontStyle": "italic"
        }
      },
      {
        "scope": [
          "keyword.operator.logical",
          "keyword.operator.arithmetic",
          "keyword.operator.assignment",
          "keyword.operator.bitwise"
        ],
        "settings": {
          "fontStyle": ""
        }
      },
    ],
  },
  "todo-tree.tree.showScanModeButton": false,
  "cSpell.userWords": [
    "deno",
    "feathersjs",
    "middlewares",
    "socketio",
    "upsert",
    "upvote"
  ],
  "editor.lineHeight": 0,
  "editor.fontSize": 14,
  "workbench.iconTheme": "material-icon-theme",
  "terminal.integrated.fontFamily": "Consolas, 'Courier New', monospace",
  "editor.fontFamily": "Consolas, 'Courier New', monospace",

  "terminal.integrated.shell.windows": "C:\\WINDOWS\\System32\\cmd.exe",
  "workbench.colorTheme": "Just Black",
  "sonarlint.rules": {
    "Web:TableWithoutCaptionCheck": {
      "level": "off"
    },
    "Web:TableHeaderHasIdOrScopeCheck": {
      "level": "off"
    },
    "Web:S1827": {
      "level": "off"
    },
    "Web:ImgWithoutAltCheck": {
      "level": "off"
    }
  },
  "python.languageServer": "Microsoft",
  "liveServer.settings.donotShowInfoMsg": true
}
```
