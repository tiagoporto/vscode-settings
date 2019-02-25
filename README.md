# vscode-settings

## Extensions

### Export
```
code --list-extensions > extensions.list
```
or

```
code-insiders --list-extensions > extensions.list
```


### Import
```
cat extensions.list |% { code --install-extension $_}
```

or

```
cat extensions.list |% { code-insiders --install-extension $_}
```
