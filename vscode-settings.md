{
  "workbench.iconTheme": "material-icon-theme",
  "files.autoSave": "afterDelay",
  "editor.stickyScroll.enabled": false,
  "background.fullscreen": {
    "images": ["file:///C:/Users/znnn/Pictures/_wal/_05.png"],
    "opacity": 0.1,
    "size": "cover",
    "position": "center",
    "interval": 0,
  },
  "background.editor": {
    "background-position": "100% 100%",
    "background-size": "auto",
    "opacity": 1,
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "editor.fontSize": 13,
  "editor.fontFamily": "'JetBrains Mono', Consolas, 'Courier New', monospace",
  "[blade]": {
    "editor.defaultFormatter": "DEVSENSE.phptools-vscode",
  },
  "git.autofetch": true,
  "git.enableSmartCommit": true,
  "git.confirmSync": false,
  "[html]": {
    "editor.defaultFormatter": "vscode.html-language-features",
  },

  "editor.foldingStrategy": "indentation",
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "explorer.compactFolders": false,
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "comment",
        "settings": {
          "foreground": "#03af00",
          "fontStyle": "italic",
        },
      },

      {
        "scope": "string",
        "settings": {
          "foreground": "#de7d7d",
        },
      },

      {
        "scope": [
          "entity.name.function",
          "support.function",
          "meta.function-call",
        ],
        "settings": {
          "foreground": "#76c7f6",
        },
      },

      {
        "scope": "entity.name.variable.parameter.php",
        "settings": {
          "foreground": "#de7d7d",
        },
      },

      {
        "scope": ["constant.language.json", "constant.language.json.comments"],
        "settings": {
          "foreground": "#4FD6BE",
        },
      },

      {
        "scope": ["constant.numeric.json.comments", "source.json.comments"],
        "settings": {
          "foreground": "#4FD6BE",
        },
      },

      {
        "scope": ["entity.other.attribute-name.html", "text.html.php.blade"],
        "settings": {
          "foreground": "#8fbaf6",
        },
      },

      {
        "scope": ["source.css", "text.html.php.blade"],
        "settings": {
          "foreground": "#4FD6BE",
        },
      },

      {
        "scope": ["meta.object-literal.key.js", "text.html.php.blade"],
        "settings": {
          "foreground": "#4FD6BE",
        },
      },

      {
        "scope": ["variable.other.property.js", "text.html.php.blade"],
        "settings": {
          "foreground": "#4FD6BE",
        },
      },

      {
        "scope": ["constant.other.php", "text.html.php.blade"],
        "settings": {
          "foreground": "#4FD6BE",
        },
      },

      {
        "scope": ["string.quoted.single.html", "text.html.php.blade"],
        "settings": {
          "foreground": "#ffffff",
        },
      },

      {
        "scope": ["entity.other.alias.php", "text.html.php"],
        "settings": {
          "foreground": "#A277FF",
        },
      },

      {
        "scope": ["variable.other.property.php", "text.html.php"],
        "settings": {
          "foreground": "#76c7f6",
        },
      },

      {
        "scope": [
          "invalid.illegal.character-not-allowed-here.html",
          "text.html.php.blade",
        ],
        "settings": {
          "foreground": "#4FD6BE",
        },
      },

      {
        "scope": ["text.html.php.blade", "text.html.php.blade"],
        "settings": {
          "foreground": "#f3f3f3",
        },
      },

      {
        "scope": ["variable.named.arm", "source.arm"],
        "settings": {
          "foreground": "#A277FF",
        },
      },
    ],
  },
  "workbench.colorTheme": "Aura Soft Dark",
  "workbench.tree.indent": 25,
  "editor.semanticTokenColorCustomizations": {
    "enabled": true,
  },

  "vim.easymotion": true,
  "vim.incsearch": true,
  "vim.hlsearch": true,
  "vim.useSystemClipboard": true,
  "vim.useCtrlKeys": true,

  "vim.leader": "\\",

  "vim.smartRelativeLine": true,
  "vim.camelCaseMotion.enable": true,

  "editor.lineNumbers": "relative",

  "vim.insertModeKeyBindings": [
    {
      "before": ["<C-Space>"],
      "after": ["<Esc>"],
    },
    {
      "before": ["<A-h>"],
      "after": ["<Esc>", "b", "i"],
    },
    {
      "before": ["<A-l>"],
      "after": ["<Esc>", "e", "a"],
    },
    {
        "before": ["j", "k"],
        "after": ["<Esc>"]
    }
  ],

  "vim.normalModeKeyBindingsNonRecursive": [
    {
      "before": [";", ";"],
      "commands": ["workbench.action.files.save"],
    },
    {
      "before": ["<leader>", "d"],
      "after": ["d", "d"],
    },
    {
      "before": ["<C-n>"],
      "commands": [":nohl"],
    },
    {
      "before": ["<C-j>"],
      "after": ["5", "j"],
    },
    {
      "before": ["<C-k>"],
      "after": ["5", "k"],
    },
    {
      "before": ["L"],
      "after": [],
    },
    {
      "before": ["K"],
      "commands": ["editor.action.insertLineAfter"],
    },
  ],

  "vim.handleKeys": {
    "<C-a>": false,
    "<C-f>": false,
    "<C-p>": false,
  },

  "extensions.experimental.affinity": {
    "vscodevim.vim": 1,
  },
"editor.inlineSuggest.enabled": false,
}
