# My Development Environment

### Apps

CleanMyMac -- utility tool
Euclid -- measurement tool
Fork -- git tool
Grammarly -- spellchecker
iTerm2 -- terminal
Mosaic -- window manager
Postmap -- API manager
RecordIt -- screen grab tool
Sip -- color tool
Visual Studio Code -- editor

### Visual Studio Code

#### Settings

```
{
  // Editor
  "editor.fontFamily": "Fira Code",
  "editor.fontSize": 12,
  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "editor.formatOnType": true,
  "editor.minimap.enabled": false,
  "editor.rulers": [72, 80],
  "editor.snippetSuggestions": "top",
  // Searching
  "search.exclude": {
    ".git/**": true,
    "node_modules/**": true,
    "coverage/**": true,
    "dist/**": true
  },
  // Formatting
  "files.autoSave": "onFocusChange",
  "html.format.wrapAttributes": "force-aligned",
  // Terminal
  "terminal.integrated.shell.osx": "zsh",
  // TSLint
  "tslint.autoFixOnSave": true,
  "tslint.rulesDirectory": "./node_modules/codelyzer",
  // IDE
  "window.restoreWindows": "none",
  "workbench.statusBar.feedback.visible": false,
  "workbench.iconTheme": "file-icons",
  "workbench.colorTheme": "ƒ - AYU - Operator Mono/Italic",
  "workbench.editor.enablePreview": false,
  // Pretier Config
  "prettier.singleQuote": true,
  "prettier.trailingComma": "all",
  "prettier.printWidth": 80,
  // Custom Extensions
  "auto-close-tag.activationOnLanguage": [
    "xml",
    "php",
    "blade",
    "ejs",
    "jinja",
    "javascriptreact",
    "typescriptreact",
    "plaintext",
    "markdown",
    "vue",
    "liquid",
    "erb",
    "lang-cfml",
    "cfml",
    "HTML (Eex)"
  ],
  "gitlens.advanced.messages": {
    "suppressShowKeyBindingsNotice": true,
    "suprpessShowKeyBindingsNotice": true
  },
  "gitlens.historyExplorer.enabled": true,
  "typescript.updateImportsOnFileMove.enabled": "always"
}
```

#### Extensions

```
alefragnani.bookmarks-9.1.0
mrmlnc.vscode-scss-0.6.2
alefragnani.project-manager-9.0.1
msjsdiag.debugger-for-chrome-4.10.2
andys8.jest-snippets-1.6.1
naumovs.color-highlight-2.3.0
christian-kohler.path-intellisense-1.4.2
peterjausovec.vscode-docker-0.3.1
donjayamanne.githistory-0.4.3
simontest.simontest-0.19.0
eamodio.gitlens-8.5.6
editorconfig.editorconfig-0.12.5
stkb.rewrap-1.9.1
eg2.tslint-1.0.40
esbenp.prettier-vscode-1.6.1
file-icons.file-icons-1.0.16
formulahendry.auto-close-tag-0.5.6
vscjava.vscode-maven-0.11.1
formulahendry.auto-rename-tag-0.0.15
wayou.vscode-todo-highlight-1.0.4
gregorbiswanger.json2ts-0.0.6
```

### Terminal Setup

ZSH with PURE

#### Alias

```
alias fresh="rm -rf node_modules package-lock.json && npm install"
alias clean="rm -rf node_modules package-lock.json"
```
