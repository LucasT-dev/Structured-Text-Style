# Sublime Structured Text Syntax Highlighting

**[Idea created from this repository](https://github.com/mszubart/IEC_ST.sublimePackage)**

This repository contains the files needed to add **Structured Text (ST)** syntax highlighting to **Sublime Text**. Structured Text is a programming language used in industrial programmable logic controllers (PLCs) according to the IEC 61131-3 standard.

---

## Features

- **Keywords**: `IF`, `THEN`, `ELSE`, `FOR`, `WHILE`, etc.
- **Data Types**: `INT`, `REAL`, `BOOL`, `STRING`, etc.
- **Comments**: Supports both inline (`//`) and block (`(* ... *)`) comments.
- **Strings**: Text enclosed in apostrophes (`'text'`).
- **Variable Addresses**: Addresses starting with `%` (e.g., `%IW6.2`, `%MW6`).
- **Time and Date Values**: `T#5s`, `DATE#2024-12-06`, `TOD#12:30:15`, `DT#2024-12-06-12:30:15`.
- **Operators**: `+`, `-`, `*`, `/`, `=`, `<`, `>`, `<=`, `>=`, `AND`, `OR`, `NOT`, etc.

---

## Installation

1. **Clone the repository** or download the files.
2. Copy the `.tmLanguage`, `.sublime-color-scheme`, `.sublime-completions` and `.sublime-settings` files to the `Packages/User` folder in Sublime Text.
   - To access this folder, go to `Preferences > Browse Packages...`.

3. **Restart Sublime Text**.

4. Open a file with the `.st` extension and select the `IEC_ST` syntax highlighting theme:
   - Go to `Preferences > Color Scheme...` and select `IEC_ST`.

---
## Example

Syntax highlighting for Structured Text (ST) in Sublime Text.
Colors can be customized by editing the .sublime-color-scheme file.

<img width="825" height="750" alt="image" src="https://github.com/user-attachments/assets/f5792da9-fa78-422e-bddc-715c80dfd5c3" />
<img width="612" height="228" alt="image" src="https://github.com/user-attachments/assets/d95f9ff8-f711-4b85-8184-838d3ef7f3e6" />

