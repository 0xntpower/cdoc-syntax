![VSCode](https://img.shields.io/badge/VSCode-1.74%2B-007ACC?logo=visual-studio-code&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

<img width="128" height="128" alt="icon-128" src="https://github.com/user-attachments/assets/f01fe201-63c0-4559-abfc-1f2643afa6f4" />

# CDoc Pseudocode Syntax

C syntax highlighting for `.cdoc` pseudocode files without the noise. Built for documenting reverse engineered code where the standard C/C++ extension complains about missing headers, undefined types, and incomplete code.

## Features

- Full C syntax highlighting with bracket matching and smart indentation
- No error squiggles or IntelliSense interference
- Disassembler name recognition (`sub_140001000`, `loc_`, `dword_`, etc.)
- Windows API and NT kernel type support (`NTSTATUS`, `UNICODE_STRING`, `PEPROCESS`)
- Calling conventions (`__fastcall`, `WINAPI`, `NTAPI`)
- RE-specific code snippets (type `func`, `struct`, `virtmem`, `apihash` and press Tab)
- TODO/FIXME/NOTE/RESEARCH comment highlighting

## Usage

Create files with the `.cdoc` extension and start documenting your reverse engineering work in pseudocode.

## Installation

### From Source
1. Copy to VSCode extensions directory:
   - Windows: `%USERPROFILE%\.vscode\extensions\cdoc-syntax`
   - macOS/Linux: `~/.vscode/extensions/cdoc-syntax`
2. Restart VSCode

### From VSIX
1. Download the `.vsix` file
2. Run: `code --install-extension cdoc-syntax-1.0.0.vsix`

## License

MIT
