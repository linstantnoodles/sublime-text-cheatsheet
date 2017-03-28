# Cheatsheet Contents

The contents are organized such that the more basic and/or more frequently used commands are at the beginning. What this means is that you can use this sheet as both a reference and a tutorial because mastering the earlier commands will enable you to master the later ones.

I will also be making use of vertical distance within each topic to improve readability.

## Topi 1: Navigating cursor around

**Move cursor to the ...**
---

    * beginning of a character - left
    * end of a character - right

    ---
    * beginning of a word - option + left
    * end of a word - option + right

    ---
    * beginning of the line - command + left
    * end of the line - command + right
    * next line - down
    * previous line - up

    ---
    * beginning of a file (before first line) - command + up
    * end of file (end of last line) - command + down

    ---
    * closing parenthesis - control + M

**Jump cursor to the ...**
---

    * specific line - control + g

    ---
    * previous cursor position - control + shift + -
    * next cursor position - control + -

Next section will be on ...

## Topic 2: Selecting text to manipulate

### Normal selection (using cursor movement)
---
*Combine the `SHIFT` key with cursor **moving** (not **jumping**) commands to form a selection of text between the cursor beginning and ending positions.*

**Select ...**

    * beginning of a character - shift + left
    * end of a character - right

    ---
    * beginning of a word - shift + option + left
    * end of a word - option + right

    ---
    * beginning of the line - shift + command + left
    * end of the line - shift + command + right
    * next line - shift + down
    * previous line - shift + up

    ---
    * beginning of a file (before first line) - shift + command + up
    * end of file (end of last line) - shift + command + down

    ---
    * closing parenthesis - shift + control + M


### Special selection (not based on cursor movement)
---

**Select ...**

#### Expanding selection
*Select a range of characters at once*

    * whole word - command + D
    * whole line - command + L
    * everything in current scope - shift + command + space
    * everything in current indentation - shift + command + J
    * everything in the file - command + A

#### Multiple selection
*Select multiple occurrences of an existing selection*

    * next match of an existing selection - command + D (repeat)
    * every match of an existing selection - control + command + G

## Topic 3: Editing

    * inserting
        * inserting a new line after current line - shift + command + enter
        * inserting a new line before current line - command + enter
    * duplicating
        * duplicating a line - command + shift + D
        * duplicating the selection - command + shift + D
    * transposing (changing places)
        * transposing line up (swap current line with previous line) - control + command + up
        * transposing line down (swap current line with next line) - control + command + down
        * transposing selection up / down (swap current selection with next / prev line)
    * deleting
        * to end of the line - command + K + K
        * to start of the line - command + K + DELETE
        * current line - control + shift + K
    * comment toggling - command + /
    * undo / redo -

## Topic 4: Text visibility control

    * Code folding
        * fold current indent level - option + command + [
        * unfold current indent level - option + command + ]
        * fold all indented N levels - [command + K] + [command + N]
        * fold all - command + K + command + 1
        * unfold all - command + K + command + J
