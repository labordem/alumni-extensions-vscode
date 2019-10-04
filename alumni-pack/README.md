# Alumni Pack

## 📦 Install

- Open the extensions sidebar on Visual Studio Code
- Search for `Alumni Pack` and install it.

## 👌 Personal settings

- Open VSCode settings.json with `ctrl+maj+P` > `Preferences: Open Settings (JSON)`
- Copy/Paste this settings:

```typescript
{
  // Window & layout
  "window.menuBarVisibility": "toggle",
  "workbench.editor.highlightModifiedTabs": true,
  "explorer.sortOrder": "type",
  // Editor
  "editor.autoIndent": true,
  "editor.tabSize": 2,
  "editor.fontSize": 16,
  "editor.minimap.renderCharacters": false,
  "editor.minimap.enabled": false,
  "editor.insertSpaces": true,
  "editor.cursorWidth": 5,
  "editor.cursorBlinking": "solid",
  // Action on save / paste
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  // Terminal
  "terminal.integrated.fontSize": 16,
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
  },
  // Error Lens
  "errorLens.enabledDiagnosticLevels": [
      "error",
      "warning",
      "info"
  ],
  "errorLens.errorBackground": "#0000000",
  "errorLens.infoBackground": "#0000000",
  "errorLens.hintBackground": "0000000",
  "errorLens.warningBackground": "0000000",
  // Disable markdown all in one linting for Prettier
  "[markdown]": {
      "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  /* ZSH & Fira Code ---------------------------------------------------------- */
  // "terminal.integrated.shell.linux": "/usr/bin/zsh",
  // "terminal.integrated.shell.osx": "/usr/local/bin/zsh",
  // "editor.fontFamily": "FuraCode Nerd Font, monospace, Noto Color Emoji",
  // "workbench.colorCustomizations": {
  //     "terminal.ansiBlack": "#0a1d29",
  // },
  // "editor.fontLigatures": true,
}
```

## ⌨️ Personal shortcuts

- Open VSCode settings.json with `ctrl+maj+P` > `Preferences: Open Keyboard Shortcuts (JSON)`
- Copy/Paste this settings:

```typescript
// Place your key bindings in this file to override the defaultsauto[]
[
  {
    // Terminal split
    key: "alt+j",
    command: "workbench.action.terminal.splitInActiveWorkspace"
  },
  {
    // Insert ES6 template string `${}` in simple "" string
    key: "alt+[BracketRight]",
    command: "template-strings.insertArg",
    when: "editorTextFocus"
  },
  {
    // Toggle terminal panel
    key: "alt+x",
    command: "workbench.action.togglePanel"
  },
  {
    // Toggle terminal fullscreen
    key: "alt+f",
    command: "workbench.action.toggleMaximizedPanel"
  },
  {
    // Wrap the current selected elements with html tags
    key: "alt+w",
    command: "extension.htmlTagWrap",
    when: "editorTextFocus"
  },
  {
    // Insert "console.log('selectedElements: ' + selectedElements)"
    key: "shift+cmd+l",
    command: "extension.insertLogStatement",
    when: "editorTextFocus"
  },
  {
    // (Angular Pack) Jump between  Angular component files, switch back and forth to associated template.
    key: "alt+q",
    command: "extension.ngQuickSwitchToggle",
    when: "editorTextFocus"
  }
];
```

## 👇 More cool stuffs

- A [theme](https://marketplace.visualstudio.com/items?itemName=milab.pikachu-theme-vscode) for Visual Studio Code
- A [guide](https://github.com/mIaborde/my-zsh) to install **ZSH** & **Fura Code fonts** (a NerdFonts patched Fira Code fonts), uncomment the **ZSH & Fira Code** section in **settings.json** to enable ZSH, Fura Code and emoji support for Linux
- An **Anguar** complementary [extension](https://marketplace.visualstudio.com/items?itemName=milab.alumni-pack-angular)

## 🕹 Enjoy
