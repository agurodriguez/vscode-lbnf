# vscode-lbnf

[![Version](https://vsmarketplacebadge.apphb.com/version/agurodriguez.vscode-lbnf.svg)](https://marketplace.visualstudio.com/items?itemName=agurodriguez.vscode-lbnf) [![Installs](https://vsmarketplacebadge.apphb.com/installs-short/agurodriguez.vscode-lbnf.svg)](https://marketplace.visualstudio.com/items?itemName=agurodriguez.vscode-lbnf) 

An extension for VS Code which provides support for the [LBNF language](https://github.com/BNFC/bnfc/blob/master/docs/lbnf.rst#appendix-lbnf-specification).

LBNF is acronym for *Labelled BNF*, which is the language used in the compiler construction tool [BNF Converter](https://github.com/BNFC/bnfc).

![](docs/screenshot.png)

## Features

* Syntax highlighting

## Release Notes

### 1.0.5

- Fix issue with strings containing a semicolon in rules starting with a keyword

### 1.0.4

- Fix issue with word `nonempty` not being detected when placed next to another keyword

### 1.0.3

- Fix issue detecting single line comments after rules starting with a keyword

### 1.0.2

- Fixed issues detecting categories inside squared brackets
- Fixed issues parsing multiline rules

### 1.0.1

Added keywords for vscode marketplace

### 1.0.0

Initial release
