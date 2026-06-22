# A Great Vim Cheat Sheet

## Movement

* `w` / `b` - jump forward/back by word
* `0` - start of line
* `$` - end of line
* `Ctrl+d` / `Ctrl+u` - half page down/up
* `gg` / `G` - top/bottom of file
* `:[num][enter]` - go to line
* `f[char]` - jump to next char on line

## Insert/Edit

* `i` / `a` - insert before / append after cursor
* `o` / `O` - new line below / above
* `cc` - change entire line
* `c[movement]` - change to move-to point (e.g. `ce`)
* `Esc` - exit insert mode
* `dd` - delete line
* `d[movement]` - delete to move-to point

## Visual Mode

* `v` - visual mode
* `V` - linewise visual mode
* `y` - yank (selection or `yy` for line)
* `d` - delete (selection or `dd` for line)

## Cut and Paste

* `p` - paste after cursor
* `x` - delete (cut) char

## Exiting

* `:w` - save
* `:wq` - save and quit
* `:q` - quit (no unsaved changes)
* `:q!` - quit, discard changes

## Search/Replace

* `/pattern` - search forward
* `n` / `N` - repeat search same/opposite direction
* `:%s/old/new/g` - replace all in file

## General

* `u` - undo
* `Ctrl+r` - redo
* `.` - repeat last command
