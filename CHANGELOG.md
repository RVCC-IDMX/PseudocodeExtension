# Changelog

All notable changes to the Pseudocode extension will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## [0.0.2] - 2025-12-17

### Added

- Semantic keyword categories (control flow, functions, I/O, logical operators, other)
- Number highlighting for integers and floats
- Operator highlighting for comparison and arithmetic operators
- Single-quoted string support
- Code folding for block structures (BEGIN/END, IF/ENDIF, FOR/NEXT, etc.)
- Auto-indentation rules for pseudocode constructs
- New snippets: ELSEIF, ELSE, IF-ELSE, CLASS, INPUT, OUTPUT, DISPLAY, SET, CALL, SQL

### Fixed

- Block comment highlighting now works correctly
- Typo in package.json description ("Psuedocode" to "Pseudocode")
- Added missing RUN and EXECUTE keywords
- Corrected snippet descriptions (WHILE POST, IF)
- Fixed FOR loop snippet structure
- Fixed RETURN snippet placeholder

## [0.0.1] - Initial release

### Added

- Basic syntax highlighting for pseudocode keywords
- Code snippets for WHILE, FOR, REPEAT, IF, BEGIN, FUNCTION, RETURN
- Comment support (single-line and block)
- Auto-closing brackets and quotes
