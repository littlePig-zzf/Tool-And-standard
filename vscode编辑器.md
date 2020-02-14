**vscode编辑器的插件安装，配置参考：**

- 主题颜色：Monokai
- 图标主题：Material Icon Theme
- Auto Rename Tag    自动修改一堆标签
- cssrem   css转换rem
- ESLint   代码风格
- GitLens   代码中显示git的历史版本控制
- Javascript (ES6) code snippets
- Javascript Standard Format
- Output Colorizer    语法高亮显示
- Path Intellisense   路径的提示与自动获取
- Prettier - Code formatter   代码规范
- TurboJavascript   输入代码快捷键提高代码速度
- vetur   vue的工具
- Setting Sync vscode的配置文件上传或下载到github
- Simple React Snippets react的代码提示
- https://github.com/tonsky/FiraCode vscode字体的引用，看起来更加友好

settings.json 用户配置文件内容如下：
```javascript
{
    "workbench.iconTheme": "material-icon-theme",
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "emmet.includeLanguages": {
        "javascript": "javascriptreact"
    },
    "css.fileExtensions": [
        "css",
        "scss"
    ],
    "git.suggestSmartCommit": false,
    "editor.tabSize": 2,
    "window.zoomLevel": 0,
    "javascript.implicitProjectConfig.experimentalDecorators": true,
    "emmet.showSuggestionsAsSnippets": true,
    "editor.suggest.snippetsPreventQuickSuggestions": false,
    "emmet.syntaxProfiles": {
        "javascript": "javascriptreact",
    },
    "typescript.validate.enable": false,
    "update.mode": "none",
    "extensions.autoUpdate": false,
    "sync.gist": "c34290d414d0de57d9a7639cfe720d27",
    "workbench.colorTheme": "Monokai",
}
```
