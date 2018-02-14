# bash

## Shortcuts

### Display existing shortcuts

    bind -P

### Terminal shortcuts

    Ctrl + L : clear screen
    Ctrl + D : close terminal
    Ctrl + C : abort
    Ctrl + Z : suspend


    Ctrl + Shift + C : copy
    Ctrl + Shift + V : paste


    Ctrl + A : move to begining of line
    Ctrl + E : move to end of line
    Alt + B : move one word backward
    Alt + F : move one word forward

    Ctrl + U : Cut from start of line
    Ctrl + K : Cut to end of line

    Alt + backspace : erase word to the left
    Alt + D : erase word to the right

    Alt + '.' or Alt + '_': retrieve last argument of the previous command
    Ctrl + Y : Paste the text that was cut after the cursor

    Ctrl + Shift + ':' : undo change made by previous command
    Alt + '#' : insert comment on the current line (bash)

    Alt + C : capitalize starting at cursor to end of word
    Alt + U : make uppercase from cursor to end of word

    Alt + Ctrl + E : extend alias definition

    Crtl + R : Reverse search in history
    Ctrl + S : Forward Search in history
    Ctrl + G : escape from history searching mode


### man 

    enter or j or <down arrow> : Forward  one line
    y or k or <up arrow> : Backward one line 
    f or space : Forward  one window
    b : Backward one window
    g  : Go to first line in file (or line N).
    G  : Go to last line in file (or line N).

    /word: search forward word occurence
    ?word : search backward word occurences
    n : next occurence
    N: previous occurence 
    &word : display only lines containing word

    = : Prints some information about the file being viewed,
    ! shell command : Invokes a shell to run the shell-command given

    q : quit