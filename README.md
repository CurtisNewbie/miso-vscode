# miso-vscode

```sh
npm install -g @vscode/vsce
vsce package
```

In vscode settings.json:

```json
"editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "scope": "keywords.misoapi",
            "settings": {
                "fontStyle": "italic bold"
            }
        }
    ]
}
```
