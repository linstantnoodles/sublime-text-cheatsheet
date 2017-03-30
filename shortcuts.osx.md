# Cheatsheet

The contents are organized such that the more basic and/or more frequently used commands are at the beginning. What this means is that you can use this sheet as both a reference and a tutorial because mastering the earlier commands will enable you to master the later ones.

# Navigating cursor

## Move cursor to .. ##

**beginning / end of a word**
option + left / right

**beginning / end of the line**
command + left / right

**beginning / end of a file**
command + up / down

**closing parenthesis**
control + M

## Jump cursor to …

**specific line**
control + G

**previous cursor position**
control + shift + minus

**next cursor position**
control + minus

# Folding code

**fold / unfold current indent level**
option + command + [ / ]

**fold all indented N levels**
[ command + K ] + [ command + N ]

**fold / unfold all**
[ command + K ] + [ command + 1 / command + J ]


# Selecting text

## Select (by cursor motion) …

**beginning / end of a word**
shift + [ option + left / right ]

**beginning / end of the line**
shift + [ command + left / right ]

**beginning / end of a file**
shift + [ command + up / down ]

**closing parenthesis**
shift + [ control + M ]

## Select (special) ...

**whole word**
command + D

**whole line**
command + L

**everything in current scope**
shift + command + space

**everything in current indentation**
shift + command + J

**everything in file**
command + A

## Select (multiple)  ...

**next match of an existing selection**
command + D (repeat)

**all matches of an existing selection**
control + command + G

# Changing text

## Insert …

**new line before current line**
shift + command + enter

**new line after current line**
command + enter

## Duplicate …

**line / selection**
command + shift + D

## Swap …

**line / selection with previous / next line**
control + command + [ up / down ]

## Delete …

**to end / start of the line**
command + K + [ K / DELETE ]

**current line**
control + shift + K

**current line and copy**
command + X

## Comment …

**line / selection**
command + /

## Undoing / Redoing …

**undo** - command + Z
**redo** - command + shift + Z
