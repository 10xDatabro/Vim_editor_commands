This is a list of most of the vim commands I use alot

Vim editor has three major modes

- Normal mode
- Insert mode
- Visual mode


The following commands will work in Normal mode. To enter the Normal mode in
Vim  press `Esc`

#### VIM editor command tip
A buffer in context of VIM is any file that you have open


Press `CTRL + w + w` to switch buffer panes in split mode.

Press `CTRL + w` followed by the letter `l` to navigate to the right pane


Press `CTRL + w` followed by the letter `h` to navigate to the left pane 

Use `:edit <filename>` or `:e <filename>` to open a file in the active buffer

Use `:vertical resize N` to change the width of the current buffer window.
Where `N` is the number of columns you specify

Use `:vsplit <filename>` to open the file `<filename>` in a vertical split
buffer. you can use `:vs <filename>` to perform the same command.

[Click here for more split mode
commands](https://www.tecmint.com/split-vim-screen/) 

Use `:ls` or `:buffers` to get a list of all open buffers.

In the output of running the `:ls` command, the file with `%a` in front of it
is the active buffer, a file with `#h` indicates the previous active buffer, a
file with `h` indicats the buffer that was opened before the previous active
buffer (the file with `#h` in front of it).
front of it.

### Navigation keys 

Press `h` to move the cursor to the left

Press `l` to move the cursor to the right

Press `k` to move the cursor up one line

Press `j` to move the cursor down one line

Press `w` to move the cursor to the start of the next word (punctuation are
considered as words)

Press `W` to mover the cursor to the start of the next word 
(spaces separate words)


Press `e` to move the cursor to the end of the next word (punctuation are
considered as words)

Press `b` to move the cursor to the previous word (punctuation are considered
words)

### Editing commands

Press `u` in normal mode to undo your last change to the file (press as many times as you
need to undo). (You use this command to revert the changes made by other
command, such as the delete, paste, search and so on.

> Make sure you're typing lowercase `u` command, not the uppercase `U` command
> Uppercase `U` command undoes all latest changes on one line. If you
> accidentally type `U` you can undo the change with `u`

Hold `CTRL` and press `r` to redo whatever you last change to the file (While holding `CTRL`, press
`r` as many times as you want to redo)

### Saving and directory exploring commands

Use `:e .` to open directory explorer in Vim

Use `:q` to close the current window and the buffer as well

Use `:wq` to save and close the current window and buffer as well

### Copy, Cut and Paste in Visual Mode
To copy, cut or paste switch to visual mode from Normal mode by pressing `v`

Press `y` to copy (use the navigation keys to highlight as much content as you
want to copy)

Press `d` to cut the selection

Move the cursor to the location where you want to paste the contents

Press `P` to paste the contents before the cursor, or `p` to paste it after
the cursor



### Vim command sources
[Vim buffers](https://linuxhandbook.com/vim-buffers/)


[Xiaoqiang
Zhen](https://www.quora.com/How-do-I-switch-between-panes-in-split-mode-in-Vim)


[Complete Guide to Buffers in Vim](https://linuxhandbook.com/vim-buffers/)

