# My-Mac-Apps
A list of apps I use (brew, brew cask, app store)

## Mac App Store

### [Line](https://itunes.apple.com/us/app/line/id539883307?mt=12&ign-mpt=uo%3D4)
- Chatting, video calls, etc with friends (mainly in Japan)

### [Trello Desktop App](https://itunes.apple.com/ca/app/trello/id461504587?mt=8)
- Project tracking

### [Be Focused](https://itunes.apple.com/us/app/be-focused-focus-timer-goal-tracker-for-work/id973134470?mt=12) 
- Pomodoro timer with basic todo tasks in the Mac menu bar

---

## Brew
- install from: https://brew.sh/
- install the below apps by running `brew install {APP NAME}`
 - `{APP NAME}` is exactly like the apps below in this section


### cask
- For installing useful apps through commandline

### git
- version controll...

### git-flow
- commandline tool for following a good version control process for projects: https://jeffkreeftmeijer.com/git-flow/

### git-lfs
- git lfs

### python3
- python3 development

### python
- for installing a seperate python2.7 other than the one that comes with the OS

### sqlite		
- Simple browser for sqlite db files

### wget
- Useful since a lot of scripts use wget to download data

### node
- Node.js and npm

### nginx
- http server

### tree
- a CLI command `tree` that shows a tree view of the current directory

---

## Brew Cask
- install by running `brew install cask`
- install the below apps by running `brew cask install {APP NAME}`
 - `{APP NAME}` is exactly like the apps below in this section

### caffeine
- App that lives on the toolbar that can prevent your Mac from sleeping with a button click

### google-chrome
- web browser

### slack
- Team communication

### steam 
- Gaming platform... way better on PC, useful for messaging gaming friends

### flycut
- Clipboard manager that lives on the toolbar

### postman
- testing and developing out APIs and sharing API docs

### spotify
- music

### visual-studio-code
- best code editor <3

### launchrocket
- a Mac PrefPane to manage all your Homebrew-installed services (e.g. mongodb, nginx, etc...)

### ngrok
- Secure tunnels to localhost, usefull for opening up API access to an external connection from localhost

---

## Other

### [npm install gtop -g](https://github.com/aksakalli/gtop)
- for visualizaiton system performance (RAM, CPU, etc...)

### [npm install -g fkill-cli](https://github.com/sindresorhus/fkill-cli)
- fabulously kill process with a nice CLI tool

### VS Code Settings
```json
{
    "workbench.iconTheme": "vscode-icons",
    "vsicons.projectDetection.autoReload": true,
    "editor.rulers": [
        80,
        120
    ],
    "editor.multiCursorModifier": "alt",

    "python.pythonPath": "/usr/local/bin/python3",
    "python.linting.enabled": true,
    "python.linting.pylintArgs": [
        "--max-line-length=120"
    ],
    "python.linting.pydocstyleEnabled": true,
    "autoDocstring.docstringFormat": "google",
    "python.linting.pydocstyleArgs": ["--ignore=D413,D406,D407,D213,D203"],

    "trailing-spaces.trimOnSave": true,
    "window.zoomLevel": 0,
    "gitlens.keymap": "chorded",
    "gitlens.advanced.messages": {
        "suppressCommitHasNoPreviousCommitWarning": false,
        "suppressCommitNotFoundWarning": false,
        "suppressFileNotUnderSourceControlWarning": false,
        "suppressGitVersionWarning": false,
        "suppressLineUncommittedWarning": false,
        "suppressNoRepositoryWarning": false,
        "suppressResultsExplorerNotice": true,
        "suppressShowKeyBindingsNotice": true
    },
    "workbench.statusBar.feedback.visible": false,
    "gitlens.historyExplorer.enabled": false,
    "gitlens.codeLens.enabled": false,

    "markdownlint.config": {
        "MD013": false,
        "MD007": false
    },
}
```
