# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project overview

This is a VSCode language extension for Pseudocode. It provides syntax highlighting, code snippets, and a custom color theme for `.dscode` files.

## Development commands

### Run/debug the extension

Press `F5` in VSCode to launch a new Extension Development Host window with the extension loaded.

### Reload after changes

Use `Cmd+R` (Mac) or `Ctrl+R` (Windows/Linux) in the Extension Development Host window to reload the extension.

### Install locally

Copy the entire extension folder to `~/.vscode/extensions/` and restart VSCode.

## Architecture

This is a declarative VSCode language extension (no TypeScript/JavaScript code). All functionality is defined in JSON configuration files:

- [package.json](package.json) - Extension manifest defining language ID (`dscode`), file extension (`.dscode`), and contribution points
- [syntaxes/.tmLanguage.json](syntaxes/.tmLanguage.json) - TextMate grammar for syntax highlighting (keywords, strings, comments)
- [language-configuration.json](language-configuration.json) - Bracket pairs, auto-closing, comment symbols, and indentation rules
- [snippets/snippets.json](snippets/snippets.json) - Code snippets for common constructs (WHILE, FOR, IF, FUNCTION, etc.)

## Supported keywords

Control flow: `BEGIN`, `END`, `IF`, `THEN`, `ELSEIF`, `ELSE`, `ENDIF`, `FOR`, `TO`, `STEP`, `NEXT`, `ENDFOR`, `WHILE`, `ENDWHILE`, `REPEAT`, `UNTIL`

Functions: `FUNCTION`, `RETURN`, `END FUNCTION`, `CALL`, `EXIT`

I/O: `INPUT`, `OUTPUT`, `PRINT`, `DISPLAY`, `READ`, `WRITE`

Operations: `SET`, `GET`, `POST`, `FETCH`, `QUERY`, `CALCULATE`, `SQL`, `CLASS`

Logical: `AND`, `OR`, `NOT`

## Comment syntax

- Single line: `//`
- Block comments: `/* */`
