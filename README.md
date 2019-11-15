# remember: list of commands to REMEMBER

# open dev menu in device
```bash
adb shell input keyevent KEYCODE_MENU
```

# reload app from terminal
```bash
adb shell input text "RR"
```

# set keyboard to SPANISH
```bash
setxkbmap -layout "es"
```

# reset Linux UI
```bash
sudo service lightdm restart
```

# yarn equivalent to npm commands
|npm   |yarn   |
|---|---|
|npm install   |yarn install   |	
|npm install --no-package-lock	|yarn install --no-lockfile   |
|npm install [package] --save   |yarn add [package]   |
|npm install [package] --save-dev  |yarn add [package] --dev   |
|npm install [package] --save-optional   |yarn add [package] --optional   |
|npm install [package] --save-exact   |yarn add [package] --exact   |
|npm install [package] --global   |yarn global add [package]   |
|npm update --global   |yarn global upgrade   |
|npm rebuild   |yarn add --force   |
|npm uninstall [package]  |yarn remove [package]   |
|npm cache clean   |yarn cache clean [package]   |
|rm -rf node_modules && npm install   |yarn upgrade   |
|npm version major   |yarn version --major   |
|npm version minor   |yarn version --minor   |
|npm version patch   |yarn version --patch   |

#
