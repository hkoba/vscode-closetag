# Close tag keyboard shortcut
Closes last opened HTML or XML tag with `Alt+.`

![Demo showing how close tag works](https://raw.githubusercontent.com/compulim/vscode-closetag/master/demo.gif)

## Usage
By default, close tag is bound to `Alt+.`. You can still run it thru Command Palette.
* Bring up Command Palette (`F1`, or `Ctrl+Shift+P` on Windows and Linux, or `Shift+CMD+P` on OSX)
* Type or select "Close Tag: Close last opened HTML/XML tag"

You can also modify keyboard shortcut with JSON below.
```
{
  "key": "alt+.",
  "command": "closeTag.closeHTMLTag",
  "when": "editorTextFocus"
}
```

## Contributions
* [Issues](https://github.com/compulim/vscode-closetag/issues/)