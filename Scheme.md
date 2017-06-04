# Shortcuts for Edwin

## types of commands

`C-<chr>`
means hold the CONTROL key while typing the character <chr>. Thus, C-f would be: hold the CONTROL key and type f.

`M-<chr>`
means hold the META or EDIT key down while typing <chr>. If there is no META or EDIT key, type <ESC>, release it,      then type the character <chr>.  "<ESC>" stands for the key labelled "ALT" or "ESC".

## stopping Edwin

`ctrl + g` stop command
`ctrl + g -> ctrl + g` cancel scheme evaluation.
You can tell if Scheme is evaluating something by looking at the run-light for the word Eval instead of Listen.

## move through the screen

`ctrl + v` moving forward
`Esc + v` moving backwards
`ctrl + l` center cursor, sort of clear screen
`Esc + <` move beguinning of a file
`Esc + >` move to the end of a file
`Ctr + u -> number -> other command` repeat a command number times

## editing text

`Esc + d` delete word after the cursor
`ctrl + k` delete row after the cursor
`ctrl+ y` undo the delete. Scheme saves the deleted text, so it can be palced on another line
`Esc + y` undo prevous delete texts (like undo several times)

## Evaluating scheme expressions

`Ctrl + x -> Ctrl e` evaluate the expression - last expression between the last ( and the cursor
`Ctrl + x -> u` o `ctrl + _` undo the last commands

## Files













