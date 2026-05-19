# McBopomofo Data Editor for VS Code

This extension provides syntax highlighting for McBopomofo `data.txt` and `excluded-phrases.txt` files.

## Features

- Syntax highlighting for comments (starting with `#`).
- Validation for data lines (`Phrase Bopomofo-Sequence`).
- Marking invalid lines.

## Syntax Rules

- **Comments**: Lines starting with `#`.
- **Valid Data**: `Phrase` followed by a space and a `Bopomofo-Sequence` (syllables connected by `-`).
- **Invalid Lines**: Any line that doesn't follow the above rules.
