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
        "editor.colorDecorators": false,
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
        /* New settings ------------------------------------------------------------- */
    }
    ```

## ➕ Shortcuts

- `alt+$` : Template String: insert argument
- `alt+x` : View: focus into Panel
- `alt+j` : Terminal: PLit Terminal
- `alt+k` : Terminal: Focus Next Pane

## 🕹 Enjoy