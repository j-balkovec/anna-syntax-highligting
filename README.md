[![VSCode](https://img.shields.io/badge/VS%20Code-Extension-blue)](https://code.visualstudio.com/)
[![Version](https://img.shields.io/badge/version-0.0.1-brightgreen)](https://github.com/j-balkovec/anna-syntax-highligting)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Build](https://img.shields.io/badge/build-passing-success)](https://github.com/j-balkovec/anna-syntax-highligting)

# ANNA Syntax Highlighting

This Visual Studio Code extension provides syntax highlighting and basic autocompletion for the ANNA assembly language used in CPSC 2500 at Seattle University. It supports `.ac` and `.anna` files and is designed to make ANNA code easier to read and maintain.

## Features

- Syntax highlighting for all ANNA instructions, directives, registers, and labels
- Comment and label recognition
- Snippet-based autocompletion for common instruction patterns
- Support for `.ac` and `.anna` file extensions

## Installation

### Option 1: Local installation

If you have the packaged file (`anna-syntax-0.0.1.vsix`):

```bash
code --install-extension anna-syntax-0.0.1.vsix
```

### Option 2: From source

Clone the repo and build in manually:

```bash
git clone https://github.com/j-balkovec/anna-syntax-highligting.git
cd anna-syntax-highligting
npm install -g vsce
vsce package
code --install-extension anna-syntax-0.0.1.vsix
```

## Usage

1. Open a `.ac` or `.anna` file in VS Code.
2. The syntax highlighting and snippets load automatically.
3. Snippets can be triggered by typing an instruction and pressing Tab.

## Contributing

Contributions are welcome. Open an issue or submit a pull request with improvements to grammar, snippets, or formatting.

## License

This project is licensed under the MIT License. See `LICENSE` file for details.
