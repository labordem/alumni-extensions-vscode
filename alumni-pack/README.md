# Alumni Pack

## 📦 Install

- Open the extensions sidebar on Visual Studio Code
- Search for `Alumni Pack` and install it.

## 👌 Personal settings

- Open VSCode settings.json with `ctrl+maj+P` > `Preferences: Open Settings (JSON)`
- Copy/Paste this settings:

```json
{
  /* BASE settings ------------------------------------------------------------ */
  // Window & layout
  "window.menuBarVisibility": "toggle",
  "window.title": "${activeEditorMedium}${separator}${rootName}",
  "workbench.editor.highlightModifiedTabs": true,
  "explorer.sortOrder": "type",
  "explorer.openEditors.visible": 0,
  "explorer.compactFolders": false,
  "workbench.panel.defaultLocation": "right",
  // Editor
  "editor.lineHeight": 22,
  "editor.minimap.enabled": false,
  "editor.cursorWidth": 5,
  "editor.cursorBlinking": "solid",
  "editor.cursorSmoothCaretAnimation": true,
  "editor.rulers": [80 /* default Prettier maxWidth */],
  // Custom fonts
  "editor.fontFamily": "Operator Mono SSm Lig, Fira Code, Noto Color Emoji, OperatorMonoSSmLig Nerd Font, FiraCode Nerd Font",
  "terminal.integrated.fontFamily": "OperatorMonoSSmLig Nerd Font, FiraCode Nerd Font, Noto Color Emoji",
  "debug.console.fontFamily": "Operator Mono SSm Lig, Fira Code, Noto Color Emoji, OperatorMonoSSmLig Nerd Font, FiraCode Nerd Font",
  "markdown.preview.fontFamily": "-apple-system, BlinkMacSystemFont, 'Segoe WPC', 'Segoe UI', 'Ubuntu', 'Droid Sans', sans-serif, Noto Color Emoji",
  "editor.fontLigatures": true,
  "editor.fontSize": 17,
  "terminal.integrated.fontSize": 15,
  "editor.fontWeight": "500",
  "terminal.integrated.fontWeight": "500",
  // Code format
  "files.trimTrailingWhitespace": true,
  "files.trimFinalNewlines": true,
  "files.insertFinalNewline": true,
  "editor.tabSize": 2,
  "editor.insertSpaces": true,
  "editor.autoIndent": true,
  "editor.formatOnSave": true,
  /* TELEMETRY & UPDATES settings --------------------------------------------- */
  "telemetry.enableCrashReporter": false,
  "telemetry.enableTelemetry": false,
  "update.mode": "manual",
  "extensions.autoUpdate": false,
  "workbench.settings.enableNaturalLanguageSearch": false,
  "workbench.enableExperiments": false,
  "extensions.autoCheckUpdates": false,
  /* EXCLUSION settings ------------------------------------------------------- */
  "files.watcherExclude": {
    "**/.git/objects/**": true,
    "**/.git/subtree-cache/**": true,
    "**/node_modules/**": true,
    "**/tmp/**": true,
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true,
    "**/node_modules": true,
    "**/bower_components": true,
    "**/dist/**": true,
    "**/log/**": true,
    "**/logs/**": true,
    "**/.fdk/**": true
  },
  "search.exclude": {
    "**/.git/objects/**": true,
    "**/.git/subtree-cache/**": true,
    "**/node_modules/**": true,
    "**/tmp/**": true,
    "**/.git": true,
    "**/.svn": true,
    "**/.hg": true,
    "**/CVS": true,
    "**/.DS_Store": true,
    "**/node_modules": true,
    "**/bower_components": true,
    "**/dist/**": true,
    "**/log/**": true
  },
  /* EXTENSIONS settings ------------------------------------------------------ */
  // TSLint
  "editor.codeActionsOnSave": {
    "source.fixAll.tslint": true,
    "source.organizeImports": true
  },
  // Code Spell Checker
  "cSpell.language": "en,fr",
  "cSpell.diagnosticLevel": "Hint",
  "cSpell.userWords": ["signin", "signup", "aujourd'hui", "sidenav", "navbar"],
  // Material icon theme
  "workbench.iconTheme": "material-icon-theme",
  "material-icon-theme.showWelcomeMessage": false,
  "material-icon-theme.showReloadMessage": false,
  "material-icon-theme.folders.color": "#608eb9",
  "material-icon-theme.folders.associations": {
    "App_Resources": "resource",
    "platforms": "other",
    "features": "content",
    "common": "shared"
  },
  "material-icon-theme.files.associations": {
    "*.controller.ts": "nest-controller",
    "*.middleware.ts": "nest-middleware",
    "*.filter.ts": "nest-filter",
    "*.gateway.ts": "nest-gateway",
    "*.decorator.ts": "nest-decorator"
  },
  // Comment Divider
  "comment-divider.subheaderAlign": "left",
  // Prettier
  "[markdown]": {
    "files.trimTrailingWhitespace": false,
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```

## ⌨️ Personal shortcuts

- Open VSCode settings.json with `ctrl+maj+P` > `Preferences: Open Keyboard Shortcuts (JSON)`
- Copy/Paste this settings:

```json
[
  // Terminal split
  {
    "key": "alt+j",
    "command": "workbench.action.terminal.splitInActiveWorkspace"
  },
  // Insert ES6 template string `${}` in simple string
  {
    "key": "alt+[BracketRight]",
    "command": "template-strings.insertArg",
    "when": "editorTextFocus"
  },
  // Toggle terminal panel
  { "key": "alt+x", "command": "workbench.action.togglePanel" },
  // Toggle terminal fullscreen
  { "key": "alt+f", "command": "workbench.action.toggleMaximizedPanel" },
  // Wrap the current selected elements with html tags
  {
    "key": "alt+w",
    "command": "editor.emmet.action.wrapWithAbbreviation",
    "when": "editorHasSelection"
  },
  // Insert console.log('selectedElement: ' + selectedElement)
  {
    "key": "shift+cmd+l",
    "command": "extension.insertLogStatement",
    "when": "editorTextFocus"
  },
  // Select all the block content or block & content...
  {
    "key": "cmd+shift+a",
    "command": "editor.action.smartSelect.grow",
    "when": "editorTextFocus"
  },
  // (Angular Pack) Jump between  Angular component files, switch back and forth to associated template
  { "key": "alt+q", "command": "extension.ngQuickSwitchToggle" }
]
```

## 👇 More cool stuff

- A [theme](https://marketplace.visualstudio.com/items?itemName=milab.pikachu-theme-vscode) for Visual Studio Code
- A [guide](https://github.com/mIaborde/my-zsh) to install **ZSH** & **Fura Code fonts** (a NerdFonts patched Fira Code fonts), uncomment the **ZSH** section in **settings.json** to enable ZSH in VSCode
- An [Angular](https://marketplace.visualstudio.com/items?itemName=milab.alumni-pack-angular) complementary extension

## 🕹 Enjoy
