# vscode-settings

## Extensions

> Mac users need to add command to PATH

Open the Command Palette `⇧⌘P` and type **shell command** to find the Shell Command: Install `code` or `code-insiders` command in PATH command.


### VSCode

#### Export
```
code --list-extensions > extensions.list
```

#### Import
```
cat extensions.list |% { code --install-extension $_}
```

### VSCode - Insiders


#### Export

```
code-insiders --list-extensions > extensions.list
```

#### Import

```
cat extensions.list |% { code-insiders --install-extension $_}
```
