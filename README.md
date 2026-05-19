# McBopomofo Data Editor for VS Code

This extension provides syntax highlighting for McBopomofo `data.txt` and `excluded-phrases.txt` files.

## Features

- Syntax highlighting for comments (starting with `#`).
- Validation for data lines (`Phrase Bopomofo-Sequence`).
- Marking invalid lines.

## Syntax Rules

- **Comments**: Lines starting with `#`.
- **Valid Data**: `Phrase` followed by a space and a `Bopomofo-Sequence` (syllables connected by `-`) or an English macro (starting with `_`).
- **Invalid Lines**: Any line that doesn't follow the above rules.

## Development and Testing

1. Open this repository in Visual Studio Code.
2. Press `F5` to open a new window with the extension loaded ("Extension Development Host").
3. In the new window, open the provided `test_data.txt` file (or create a file named `data.txt` or `excluded-phrases.txt`).
4. You should immediately see the syntax highlighting applied.
5. **Making Changes:** If you modify the `syntaxes/mcbopomofo-data.tmLanguage.json` file, you need to reload the Extension Development Host window to see the changes. You can do this by opening the Command Palette (`Cmd+Shift+P` on macOS, `Ctrl+Shift+P` on Windows/Linux) in the test window and selecting **Developer: Reload Window**, or simply by pressing `Cmd+R` (`Ctrl+R`).
