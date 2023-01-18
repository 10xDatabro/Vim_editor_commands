This is a list of most of the vim commands I use alot
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

Use `:e .` to open directory explorer in Vim

Use `:q` to close the current window and the buffer as well

### Vim command sources
[Vim buffers](https://linuxhandbook.com/vim-buffers/)
[Xiaoqiang
Zhen](https://www.quora.com/How-do-I-switch-between-panes-in-split-mode-in-Vim)
[Complete Guide to Buffers in Vim](https://linuxhandbook.com/vim-buffers/)

