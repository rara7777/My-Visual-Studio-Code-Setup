# My Visual Studio Code Setup

### Extensions
- ESLint
- Laravel 5 Snippets
- Laravel Blade Snippets
- phpfmt - PHP formatter
- Project Manager
- Vetur

### Settings

```
{
    "[blade]": {
        "editor.tabSize": 2
    },
    "[javascript]": {
        "editor.tabSize": 2
    },
    "[php]": {
        "editor.tabSize": 4,
        "editor.formatOnSave": true
    },
    "[vue]": {
        "editor.tabSize": 2
    },
    "[python]": {
        "editor.tabSize": 4
    },
    "editor.tabSize": 2,
    "editor.fontSize": 16,
    "window.zoomLevel": -1,
    "workbench.startupEditor": "newUntitledFile",
    "search.exclude": {
        "**/bower_components": true,
        "**/dist": true,
        "**/node_modules": true,
        "**/vendor": true
    },
    "editor.renderWhitespace": "boundary",
    "editor.codeLens": true,
    "editor.snippetSuggestions": "top",
    "git.ignoreMissingGitWarning": true,
    "explorer.confirmDragAndDrop": false,
    "editor.quickSuggestions": {
        "other": false,
        "comments": false,
        "strings": false
    },
    "emmet.includeLanguages": {
        "blade": "html"
    },
    "emmet.triggerExpansionOnTab": true, // enable tab to expanse emmet tags
    "telemetry.enableTelemetry": false,
    // "files.autoSave": "onFocusChange",
    "workbench.colorCustomizations": {
        "statusBar.background": "#333333",
        "statusBar.noFolderBackground": "#333333",
        "statusBar.debuggingBackground": "#263238"
    },
    "css.validate": false,
    "scss.validate": false,
    "less.validate": false,
    "editor.wordWrap": "on",
    "blade.format.enable": true,
    "vetur.validation.template": false,
    "extensions.ignoreRecommendations": true,
    "files.eol": "\n"
}
```
