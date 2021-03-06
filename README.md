# vscode-settings

My VsCode settings

#### Useful shortcut (by default):

```
Balance outward
[editor.action.smartSelect.grow]
`Shift + alt + right`
```

```
Balance inward
[editor.action.smartSelect.shrink]
`Shift + alt + left`
```

```
Split Selection Into Lines
[editor.action.insertCursorAtEndOfEachLineSelected]
`Shift + alt + i`
```

```
Multiple-Line Comment/Toggle Block Comment
[editor.action.blockComment]
`Shift + alt + A`
```

Good reading from VS Code website:

https://code.visualstudio.com/docs/getstarted/tips-and-tricks

#### Additional useful shorcut to add:

```
{
"key": "ctrl+k ctrl+l",
"command": "editor.action.transformToLowercase"
}

{
"key": "ctrl+k ctrl+u",
"command": "editor.action.transformToUppercase"
}

{
  "key": "ctrl+alt+n",
  "command": "workbench.action.duplicateWorkspaceInNewWindow"
}
```

# npm setting

```bash
npm list -g --depth=0
/usr/local/lib
├── @aws-amplify/cli@1.6.1
├── babel-cli@6.26.0
├── create-react-app@2.1.5
├── loopback-cli@5.0.0
├── node-jq@1.5.0
├── nodemon@1.18.6
├── npm@6.4.1
└── umi@2.6.2
```

## On npm install: Unhandled rejection Error: EACCES: permission denied

Give ownership to npm like this:

```
sudo chown -R $USER:$GROUP ~/.npm
sudo chown -R $USER:$GROUP ~/.config
```
