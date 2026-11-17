# Support for Theme-D Programming Language

This package provides support for the Theme-D programming language in Visual Studio Code. Support includes semantic highlighting. Note that Theme-D source file indentation is not provided by this package.

## Useful VSCode Configuration Variables

If you don't want the brackets in your source code to be colourized switch off the configuration variable editor.bracketPairColorization.enabled.

## Release Notes

## 1.0.9

Added keywords define-enum and define-new-goops-class and procedure raise-rte-exception.

### 1.0.8

Updated README.md.

### 1.0.7

Set the notIn attributes for brackets.

Detect character constants.

Updated keywords.

### 1.0.6

Removed keyword match-type-strong and added keyword match-type-weak.

Added keywords create, static-type-of0 and type-of.

### 1.0.5

Added some keywords.

### 1.0.4

Changed line comment to ;; in language-configuration.json.

### 1.0.3

Added publisher to package.json.

### 1.0.2

Fixed colouring of type names.

Added special forms iterate-2-lists, iterate-2-lists-pure,
iterate-2-lists-with-break, iterate-2-lists-with-break-pure,
receive, and fluid-let.

### 1.0.1

Added special forms iterate-list, iterate-list-pure, iterate-list-with-break, and iterate-list-with-break-pure.

### 1.0.0

Initial release of the Theme-D language support in VSCode.
