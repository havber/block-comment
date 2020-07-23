# DEPRECATED comment

Atom provides this functionality by default in the last versions it seems, so this package is not needed anymore.

# Comment package for atom [![Build Status](https://travis-ci.org/javaguirre/comment.svg?branch=master)](https://travis-ci.org/javaguirre/comment)

Atom package for inserting block- or single line comments via keyboard shortcut

![alt tag](https://raw.github.com/havber/comment/master/example.gif)

## Usage
Select the text you want to comment, and hit ```shift-cmd-m```.
If selection is empty, an empty comment block will be inserted.

Both block comments and single line comments are toggled on/off on ```shift-cmd-m```
by default. if you want to add It to your own keymap, you can do so using:

```comment:toggle```

## Language support
...is based on file extensions and will be added incrementally.
Latest version supports
* .class
* .coffee
* .cs
* .css
* .html/.htm
* .js
* .less
* .md
* .rb
* .yml
* .php
* .py
* .lisp

and more!
