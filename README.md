# QBE extension for Zed

This extension provides comprehensive support for the [QBE](https://c9x.me/qbe/) Intermediate Language in the [Zed editor](https://zed.dev).

## Features

- **Syntax Highlighting**: Complete highlighting for functions, types, instructions, sigils (`%`, `$`, `@`, `:`), constants, and comments using [Tree-sitter](https://github.com/WinAndronuX/tree-sitter-qbe).
- **Code Outline**: Symbol navigation for functions, data, aggregate types, and block labels (`@start`, `@loop`, etc.).
- **Auto-indentation & Bracket Matching**: Smart indentation inside function bodies and structures, and automatic bracket pair handling.
- **Snippets**: Quick expansion for functions (`func`, `export`), data definitions (`data`), aggregate types (`type`), phi nodes (`phi`), memory instructions (`alloc`, `load`, `store`), calls (`call`), jumps (`jnz`, `jmp`), and returns (`ret`).
- **Supported file extensions**: `.ssa`, `.qbe`.

## Installation (Local Dev Extension)

1. Open Zed.
2. Open the Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`).
3. Select `zed: install dev extension`.
4. Choose the `qbe-zed` folder.

## License

MIT
