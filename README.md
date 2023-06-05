# 🧰 .config

Setup, tooling and other bits & pieces that I use.

- [Visual Studio Code](https://code.visualstudio.com/)
  - Extensions:
    - [Activitus Bar](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.activitusbar)
    - [Atom Keymap](https://marketplace.visualstudio.com/items?itemName=ms-vscode.atom-keybindings)
    - [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
    - [GitHub Actions](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-github-actions)
    - [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
    - [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
    - [Jest](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-jest)
    - [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
    - [npm IntelliSense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
    - [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    - [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
    - [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
    - [vscode-twoslash-queries](https://marketplace.visualstudio.com/items?itemName=Orta.vscode-twoslash-queries)
  - Misc.
    - [Sidebar on the right](https://tinytip.co/tips/vscode-sidebar-position/)
- [iTerm2](https://iterm2.com/)
  - [Oh My Zsh](https://ohmyz.sh/)
    - [powerlevel10k](https://github.com/romkatv/powerlevel10k)
  - [_Tomorrow Night Burns_ color scheme](https://github.com/mbadolato/iTerm2-Color-Schemes/blob/master/schemes/Tomorrow%20Night%20Burns.itermcolors) 
- [FiraCode font](https://github.com/tonsky/FiraCode)
- [Google Chrome](https://www.google.com/chrome/)
  - Extensions:
    - [AdBlock](https://chrome.google.com/webstore/detail/adblock-%E2%80%94-best-ad-blocker/gighmmpiobklfepjocnamgkkbiglidom)
    - [JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa)
    - [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
    - [Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd)
    - [Screen Reader](https://chrome.google.com/webstore/detail/screen-reader/kgejglhpjiefppelpmljglcjbhoiplfn)


## Visual Studio Code configuration

```json
{
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.fontFamily": "Fira Code, Menlo, Monaco, 'Courier New', monospace",
  "editor.fontLigatures": true,
  "editor.minimap.autohide": true,
  "editor.tabSize": 2,

  "emmet.triggerExpansionOnTab": true,

  "window.zoomLevel": 1,

  "workbench.activityBar.visible": false,
  "workbench.iconTheme": "vscode-icons",
  "workbench.sideBar.location": "right",

  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  }
}
```
