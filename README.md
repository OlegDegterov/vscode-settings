# vscode-settings

1. Откройте терминал и создайте файл vs-extension.txt:
   `touch vs-extension.txt`.
   В файл vs-extension.txt скопируйте ваши vscode расширения: >- alex-pattison.theme-cobalt3 >- fosshaas.fontsize-shortcuts >- vscode-icons-team.vscode-icons >- dbaeumer.vscode-eslint >- esbenp.prettier-vscode >- vunguyentuan.vscode-postcss >- streetsidesoftware.code-spell-checker >-yoavbls.pretty-ts-errors >- adpyke.codesnap >- rangav.vscode-thunder-client >- dsznajder.es7-react-js-snippets >- Prisma.prisma >- bierner.markdown-mermaid

2. Запустите скрипт для установки расширений:

`cat vs-extension.txt | xargs -L1 code --install-extension`

3. Откройте в vscode файл settings.json (command+shift+P) и скопируйте в него настройки:

```
{
    "codesnap.backgroundColor": "#000000",
    "codesnap.containerPadding": "0px",
    "codesnap.showWindowControls": false,
    "codesnap.transparentBackground": true,
    "cSpell.enabled": true,
    "cSpell.enableFiletypes": [
      "mdx"
    ],
    "diffEditor.ignoreTrimWhitespace": false,
    "editor.detectIndentation": true,
    "editor.fontFamily": "Anonymous Pro",
    "editor.fontLigatures": true,
    "editor.fontSize": 9,
    "editor.formatOnPaste": false,
    "editor.inlineSuggest.enabled": true,
    "editor.lineHeight": 0,
    "editor.linkedEditing": true,
    "editor.minimap.enabled": false,
    "editor.multiCursorModifier": "ctrlCmd",
    "editor.snippetSuggestions": "top",
    "editor.suggestSelection": "first",
    "editor.tabSize": 2,
    "editor.tokenColorCustomizations": {
      "textMateRules": [
        {
          "scope": [
            "keyword.operator",
            "punctuation.separator"
          ],
          "settings": {
            "fontStyle": ""
          }
        },
        {
          "scope": [
            "comment",
            "comment.block"
          ],
          "settings": {
            "fontStyle": "italic",
            "foreground": "#F5F"
          }
        },
        {
          "name": "envKeys",
          "scope": "string.quoted.double.env,source.env,constant.numeric.env",
          "settings": {
            "foreground": "#19354900"
          }
        }
      ]
    },
    "editor.unicodeHighlight.invisibleCharacters": false,
    "emmet.showAbbreviationSuggestions": false,
    "eslint.enable": true,
    "eslint.validate": [
      "react",
      "typescript",
      "html",
      "javascript"
    ],
    "explorer.openEditors.visible": 1,
    "extensions.ignoreRecommendations": true,
    "files.autoSave": "onWindowChange",
    "git.autofetch": true,
    "git.openRepositoryInParentFolders": "never",
    "markdown.preview.fontSize": 36,
    "screencastMode.keyboardOptions": {
      "showCommandGroups": false,
      "showCommands": false,
      "showKeybindings": true,
      "showKeys": false,
      "showSingleEditorCursorMoves": true
    },
    "search.exclude": {
      "**/*.code-search": true,
      "**/bower_components": true,
      "**/node_modules": true
    },
    "search.useIgnoreFiles": false,
    "terminal.integrated.fontSize": 10,
    "vsicons.dontShowNewVersionMessage": true,
    "window.zoomLevel": 4,
    "workbench.colorTheme": "Cobalt3",
    "workbench.editor.labelFormat": "medium",
    "workbench.editor.showTabs": "none",
    "workbench.iconTheme": "vscode-icons",
    "workbench.sideBar.location": "right",
    "workbench.startupEditor": "newUntitledFile",
    "workbench.statusBar.visible": false,
    "[css]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[handlebars]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[html]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascript]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[javascriptreact]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[json]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[jsonc]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[markdown]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[scss]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescript]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "[typescriptreact]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "editor.formatOnSave": true,
  }
```

Приятного кодинга)

![App Platorm](https://cs14.pikabu.ru/post_img/big/2023/07/03/1/1688339687161032319.jpg)
