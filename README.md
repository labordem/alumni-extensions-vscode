# Alumni Pack

## ⌨️ Install
- Open the extensions sidebar on Visual Studio Code
- Search for `Alumni Pack` and install it.

## 🔧 Personal settings (optional)

- Open VSCode settings.json with `ctrl+maj+P` > `Preferences: Open Settings (JSON)`
- Copy/Paste this settings:

```typescript
{
    // Window & layout
    "window.menuBarVisibility": "toggle",
    "window.zoomLevel": 0.5,
    "workbench.editor.highlightModifiedTabs": true,
    "explorer.sortOrder": "type",
    // Editor
    "editor.autoIndent": true,
    "editor.tabSize": 2,
    "editor.fontSize": 17,
    "editor.minimap.renderCharacters": false,
    "editor.minimap.enabled": false,
    "editor.renderWhitespace": "all",
    "editor.insertSpaces": true,
    "editor.cursorWidth": 5,
    "editor.cursorBlinking": "solid",
    // Action on save / paste
    "files.trimTrailingWhitespace": true,
    "files.trimFinalNewlines": true,
    "editor.formatOnPaste": true,
    "editor.formatOnSave": true,
    // Terminal
    // "workbench.colorCustomizations": {
    //     "terminal.ansiBlack": "#0a1d29",
    // },
    // "terminal.integrated.fontSize": 17,
    /* ZSH & Fira Code ---------------------------------------------------------- */
    // "terminal.integrated.shell.osx": "/usr/local/bin/zsh",
    // "terminal.integrated.shell.linux": "/usr/bin/zsh",
    // "editor.fontFamily": "FuraCode Nerd Font, monospace, Noto Color Emoji",
    // "editor.fontLigatures": true,
    /* VSCode extensions settings ----------------------------------------------- */
    // TSLint
    "editor.codeActionsOnSave": {
        "source.fixAll.tslint": true,
        "source.organizeImports": true,
    },
    // Code Spell Checker
    "cSpell.language": "en,fr",
    "cSpell.diagnosticLevel": "Hint",
    "cSpell.userWords": [],
    // Material icon theme
    "workbench.iconTheme": "material-icon-theme",
    "material-icon-theme.showWelcomeMessage": false,
    "material-icon-theme.showReloadMessage": false,
    "material-icon-theme.folders.color": "#608eb9",
    "material-icon-theme.folders.associations": {
        "_services": "controller",
        "_helpers": "helper",
        "_shared": "shared",
        "_components": "components",
        "_models": "class",
        "_core": "core",
        "_guards": "guard",
        "_utils": "utils",
        "_pipes": "pipe"
    },
    // Bracket Pair Colorizer 2
    "editor.matchBrackets": false,
    "bracket-pair-colorizer-2.colors": [
        "#dfeeff",
    ],
    "bracket-pair-colorizer-2.excludedLanguages": [
        "html",
    ],
    "bracket-pair-colorizer-2.highlightActiveScope": true,
    // Comment Divider
    "comment-divider.subheaderAlign": "left",
    // Highlight Matching Tags
    "highlight-matching-tag.styles": {
        "opening": {
            "name": {
                "underline": "#ffd900"
            }
        }
    }
    /* New settings ------------------------------------------------------------- */
}
```

## ➕ Shortcuts
- Open VSCode settings.json with `ctrl+maj+P` > `Preferences: Open Keyboard Shortcuts (JSON)`
- Copy/Paste this settings:

```typescript
// Place your key bindings in this file to override the defaultsauto[]
[
    {
        "key": "alt+j",
        "command": "workbench.action.terminal.splitInActiveWorkspace"
    },
    {
        "key": "alt+[BracketRight]",
        "command": "template-strings.insertArg",
        "when": "editorTextFocus"
    },
    {
        "key": "alt+x",
        "command": "workbench.action.focusPanel"
    },
    {
        "key": "alt+f",
        "command": "workbench.action.toggleMaximizedPanel"
    },
    {
        "key": "alt+w",
        "command": "extension.htmlTagWrap",
        "when": "editorTextFocus"
    },
    {
        "key": "shift+cmd+l",
        "command": "extension.insertLogStatement",
        "when": "editorTextFocus"
    },
]
```

## 🕹 Enjoy