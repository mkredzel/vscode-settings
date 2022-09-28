# VS Code Settings

## Font

* Current font:
  * [Cascadia Code](https://github.com/microsoft/cascadia-code)
* Previous font:
  * Consolas

## Themes

* Current theme:
  * [Theme](https://marketplace.visualstudio.com/items?itemName=tal7aouy.theme)
* Previous themes:
  * [Just Black](https://marketplace.visualstudio.com/items?itemName=nur.just-black)
  * [Cobalt2](https://marketplace.visualstudio.com/items?itemName=wesbos.theme-cobalt2)

## Workflow

* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
  * Automatically add HTML/XML close tag
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * Automatically rename paired HTML/XML tag
* [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
  * Change the font size with keyboard shortcuts
* [Tabnine AI Autocomplete](https://marketplace.visualstudio.com/items?itemName=TabNine.tabnine-vscode)
  * AI-driven code auto-complete

## Style/Formatting

* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * Automatically format JavaScript, JSON, CSS, Sass, and HTML files.

## Useful/Extra

* [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Collaborative editing, debugging, and more inside VS Code

## Settings

```json
{
    "workbench.colorTheme": "Theme",
    "tabnine.experimentalAutoImports": true,
    "terminal.integrated.defaultProfile.windows": "Git Bash",
    "liveServer.settings.donotShowInfoMsg": true,
    "workbench.iconTheme": "material-icon-theme",
    "editor.lineHeight": 20,
    "editor.fontSize": 14,
    "editor.fontFamily": "Cascadia Code",
    "terminal.integrated.fontFamily": "Cascadia Code",
    "editor.fontLigatures": true,
    "editor.guides.bracketPairs": true,
    "[html]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[json]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[css]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[scss]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascriptreact]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[jsonc]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "terminal.integrated.windowsEnableConpty": false,
}
```
