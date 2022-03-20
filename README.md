# Frontend Extension Pack

This extension pack adds features for frontend development.

## Note

** Please read the [Recommended Settings](#Recommended-Settings) section to enable all features.**

## Recommended-Settings

### Setup VS Code

* TODO

## Extensions Included in this pack

### Linters
- Prettier - [https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- Eslint - [https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- Stylelint - [https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint](https://marketplace.visualstudio.com/items?itemName=stylelint.vscode-stylelint)
- EditorConfig - [https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

###  Git
- Git Graph - [https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph](https://marketplace.visualstudio.com/items?itemName=mhutchie.git-graph)
- Gitlens - [https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
- Git History Diff - [https://marketplace.visualstudio.com/items?itemName=huizhou.githd](https://marketplace.visualstudio.com/items?itemName=huizhou.githd)
### Vscode utils & them
- Material Icon Theme - [https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)
- Change Case - [https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case](https://marketplace.visualstudio.com/items?itemName=wmaurer.change-case)
- Pin Up - [https://marketplace.visualstudio.com/items?itemName=saekiraku.pin-up](https://marketplace.visualstudio.com/items?itemName=saekiraku.pin-up)
- Quit Control for VSCode - [https://marketplace.visualstudio.com/items?itemName=artdiniz.quitcontrol-vscode](https://marketplace.visualstudio.com/items?itemName=artdiniz.quitcontrol-vscode)

### Others
- Version Lens - [https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens](https://marketplace.visualstudio.com/items?itemName=pflannery.vscode-versionlens)


## Other Extensions recommended but not included
- Live Share [https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- GitLab Workflow [https://marketplace.visualstudio.com/items?itemName=GitLab.gitlab-workflow](https://marketplace.visualstudio.com/items?itemName=GitLab.gitlab-workflow)
- Github Pull request [https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github)
- Docker [https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-docker)

## Recomended settings for linters
You can use this `settings.json` file globally or in each workspace putting into a `.vscode` folder.
```
{
  "javascript.validate.enable": false,
  "css.validate": false,
  "less.validate": false,
  "scss.validate": false,
  "editor.formatOnSave": false,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.fixAll.stylelint": true
  },
  "eslint.validate": ["javascript", "javascriptreact"],
  "eslint.format.enable": true,
  "eslint.debug": true,
  "eslint.codeAction.showDocumentation": {
    "enable": true
  },
  "eslint.alwaysShowStatus": true,
  "stylelint.validate": ["css", "scss"]
}
```

## Recomended keyBindings for change-case

```
    // vscode-change-case https://github.com/wmaurer/vscode-change-case
    //upercase
   ,{ "key": "cmd+u",
      "command": "extension.changeCase.upper",
      "when": "editorTextFocus" 
    }
    //lowercase
    ,{ "key": "cmd+l",
      "command": "extension.changeCase.lower",
      "when": "editorTextFocus" 
   },
```
## Credits

All credits goes to original authors of the above mentioned extensions.

**Happy Coding!**
