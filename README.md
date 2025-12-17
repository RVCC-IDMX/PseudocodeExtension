# Pseudocode Extension

A VSCode language extension for Pseudocode that provides syntax highlighting, code snippets, and language support for `.dscode` files.

## Attribution

This project is a fork of [DigitalSolutionsPseudocodeExtension](https://github.com/andrewtacon/DigitalSolutionsPseudocodeExtension) by [Andrew Tacon](https://github.com/andrewtacon). Thank you to Andrew for creating the original extension.

## Features

- Syntax highlighting for pseudocode keywords
- Code snippets for common constructs (IF, FOR, WHILE, FUNCTION, etc.)
- Auto-closing brackets and quotes
- Comment support (single-line `//` and block `/* */`)

## Usage

Files must have the `.dscode` extension to activate syntax highlighting.

## Supported keywords

### Control flow

`BEGIN`, `END`, `IF`, `THEN`, `ELSEIF`, `ELSE`, `ENDIF`

### Loops

`FOR`, `TO`, `STEP`, `NEXT`, `ENDFOR`, `WHILE`, `ENDWHILE`, `REPEAT`, `UNTIL`

### Functions

`FUNCTION`, `RETURN`, `END FUNCTION`, `CALL`, `EXIT`

### Input/Output

`INPUT`, `OUTPUT`, `PRINT`, `DISPLAY`, `READ`, `WRITE`

### Operations

`SET`, `RUN`, `EXECUTE`, `GET`, `POST`, `FETCH`, `QUERY`, `CALCULATE`, `SQL`, `CLASS`

### Logical operators

`AND`, `OR`, `NOT`

## Code snippets

Type the following prefixes and press Tab to insert snippets:

| Prefix | Snippet |
|--------|---------|
| `WHILE` or `WHI` | WHILE loop |
| `FOR` | FOR loop |
| `REPEAT` or `REP` | REPEAT-UNTIL loop |
| `IF` | IF statement |
| `BEGIN` or `BEG` | BEGIN-END block |
| `FUNCTION` or `FUN` | Function definition |
| `RETURN` or `RET` | Return statement |

## Examples

The `examples/` folder contains tutorial files organized by topic:

- `01-basics/` - Hello world, comments, variables, operators
- `02-control-flow/` - IF, ELSE, ELSEIF, nested conditions
- `03-loops/` - WHILE, FOR, REPEAT-UNTIL, nested loops
- `04-functions/` - Function basics, parameters, return values
- `05-io-operations/` - Input, output, read, write
- `06-data-operations/` - SET, CALCULATE, arrays, SQL
- `07-web-operations/` - GET, POST, FETCH
- `08-classes/` - Object-oriented pseudocode
- `09-complete-programs/` - Full program examples

## Installation

### From source

1. Clone this repository
2. Copy the folder to `~/.vscode/extensions/`
3. Restart VSCode

### Development

Press `F5` in VSCode to launch an Extension Development Host with the extension loaded.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

See [LICENSE](LICENSE) file for details.
