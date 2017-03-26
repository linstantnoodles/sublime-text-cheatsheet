# Cheatsheet Contents

The contents are organized such that the more basic and/or more frequently used commands are at the beginning. What this means is that you can use this sheet as both a reference and a tutorial because mastering the earlier commands will enable you to master the later ones.

I will also be making use of vertical distance within each topic to improve readability.

## Topic 1: Navigating cursor around

**Move cursor to the ...**
---

    * beginning of a character
    * end of a character

    ---
    * beginning of a word
    * end of a word

    ---
    * beginning of the line
    * end of the line
    * next line
    * previous line

    ---
    * beginning of a file (before first line)
    * end of file (end of last line)

    ---
    * closing parenthesis

**Jump cursor to the ...**
---

    * specific line

    ---
    * previous cursor position
    * next cursor position

Next section will be on ...

## Topic 2: Selecting text to manipulate

### Normal selection (using cursor movement)
---
*Combine the `SHIFT` key with cursor **moving** (not **jumping**) commands to form a selection of text between the cursor beginning and ending positions.*

**Select ...**

    * beginning of a character
    * end of a character

    ---
    * beginning of a word
    * end of a word

    ---
    * beginning of the line
    * end of the line
    * next line
    * previous line

    ---
    * beginning of a file (before first line)
    * end of file (end of last line)

    ---
    * closing parenthesis


### Special selection (not based on cursor movement)
---

**Select ...**

#### Expanding selection
*Select a range of characters at once*

    * whole word
    * whole line
    * whole paragraph
    * everything in scope
    * everything in same level of indentation
    * everything in the file

#### Multiple selection
*Select multiple occurrences of an existing selection*

    * next match of an existing selection
    * every match of an existing selection

## Topic 3: Editing

    * inserting
        * inserting a new line after current line
        * inserting a new line before current line
    * duplicating
        * duplicating a line
        * duplicating the selection
    * transposing (changing places)
        * transposing line up (swap current line with previous line)
        * transposing line down (swap current line with next line)
        * transposing selection up / down (swap current selection with next / prev line)
    * deleting
        * to end of the line
        * to start of the lne
        * current line
    * commenting
