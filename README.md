```{
  "editor.fontFamily": "'JetBrains Mono','Droid Sans Mono', 'monospace', monospace",
  "editor.fontLigatures": true,
  "files.autoSave": "afterDelay",
  "editor.formatOnSave": false,
  "editor.formatOnPaste": true,
  "editor.minimap.enabled": false,
  "editor.mouseWheelZoom": true,
  "editor.wordWrap": "on",
  "editor.fontSize": 12,

  // "terminal.integrate.setting
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorStyleInactive": "underline",
  "terminal.integrated.fontFamily": "MesloLGS NF",
  "terminal.integrated.defaultProfile.osx": "zsh",
  "terminal.integrated.gpuAcceleration": "canvas",
  "terminal.integrated.fontSize": 12,
  "terminal.integrated.lineHeight": 1.1,


  "workbench.colorCustomizations": {
    "terminal.background": "#1D2021",
    "terminal.foreground": "#A89984",
    "terminalCursor.background": "#A89984",
    "terminalCursor.foreground": "#A89984",
    "terminal.ansiBlack": "#1D2021",
    "terminal.ansiBlue": "#4e45a3",
    "terminal.ansiBrightBlack": "#665C54",
    "terminal.ansiBrightBlue": "#0D6678",
    "terminal.ansiBrightCyan": "#8BA59B",
    "terminal.ansiBrightGreen": "#95C085",
    "terminal.ansiBrightMagenta": "#8F4673",
    "terminal.ansiBrightRed": "#FB543F",
    "terminal.ansiBrightWhite": "#FDF4C1",
    "terminal.ansiBrightYellow": "#FAC03B",
    "terminal.ansiCyan": "#8BA59B",
    "terminal.ansiGreen": "#95C085",
    "terminal.ansiMagenta": "#8F4673",
    "terminal.ansiRed": "#FB543F",
    "terminal.ansiWhite": "#8c17c2",
    "terminal.ansiYellow": "#FAC03B"
  },

  //Formatting
  "prettier.endOfLine": "lf",
  // javascript/Typescript

  "javascript.preferences.quoteStyle": "single",
  "typescript.preferences.quoteStyle": "single",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "typescript.updateImportsOnFileMove.enabled": "always",
  "javascript.preferences.importModuleSpecifier": "relative",
  "typescript.preferences.importModuleSpecifier": "relative",

// For Javascript Formating 

  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
//  CSS
"tailwindCSS.emmetCompletions": true,
"tailwindCSS.includeLanguages": {
  "TypeScript":"typescript",
},
 
"[json]": {
  "editor.quickSuggestions": {
    "strings": true
  },
  "editor.suggest.insertMode": "replace",
  "editor.defaultFormatter": "esbenp.prettier-vscode"
},
"[jsonc]": {
  "editor.quickSuggestions": {
    "strings": true
  },
  "editor.suggest.insertMode": "replace",
  "editor.defaultFormatter": "esbenp.prettier-vscode"
},


  // For PHP Code Formating 

  "[php]": {
    "editor.defaultFormatter": "kokororin.vscode-phpfmt",
    "editor.formatOnSave": true
  },
  "phpfmt.psr2": false,
  "phpfmt.exclude": ["AllmanStyleBraces"],
  "phpfmt.passes": ["AlignDoubleArrow"],

  // blade format setting customize

   "blade.format.enable": true,
  
  "[blade]": {
    "editor.autoClosingBrackets": "always",
    "editor.defaultFormatter": "shufo.vscode-blade-formatter",
    "editor.formatOnSave": true,
  },


  "bladeFormatter.format.sortTailwindcssClasses": false,

  // vs code background theme customize
  "background.enabled": true,

  "background.fullscreen": {
    "images": [
      "https://i.ibb.co/P1h9s4S/Black-Futuristic-Technology-Desktop-Wallpaper.png"
    ],
    "opacity": 0.91,
    "size": "cover",
    "position": "center",
    "interval": 0
  },
  // Tailwind css unknown message
  
"css.lint.unknownAtRules": "ignore",


  // vs code them and icon 
  "workbench.colorTheme": "Andromeda Italic Bordered",
  "workbench.iconTheme": "material-icon-theme",
  "window.menuBarVisibility": "compact",


  "debug.javascript.defaultRuntimeExecutable": {
    "pwa-node": "node",
  },
  "emmet.includeLanguages": {
    "javascript": "javascriptreact",
    "blade": "html"
  }
}

```