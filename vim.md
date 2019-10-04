## Movement keys

**hjkl** - left down up right

## Quitting

**:q!** - quit and dont save the file  
**:q** - quit and save the file  
**:wq** - quit and write  
**:w** - save change and not quit

## Modes

**i** - insert mode  
**v, V** - visual mode, where we can see what we are doing!

- in visual mode we can use the movement commands such as } to jump to the end of multiple now selected blocks
- once we have made our selections we can use commands such as d to delete it

**esc** - command mode

## Commands

**dd** - delete a line / 'grab'  
**u** - undo  
**⌃ r** - redo  
**yy** - copy line  
**p** - paste below  
**P** - paste above  
**o, O** - newline below or above and then jump into insert mode

### Vertical

**G** - end of file  
**gg** - start of file  
**}** - end of block  
**{** - start of block  
**: + 30** - line 30

### Horizontal

**w** - next space / punctuation  
**W** - ignores punctuation  
**b** - prev space / puntuation  
**B** - ignores punctuation  
**0** - start of line  
**^** - first char in line

### Search

**t + !** - one char before char "!"  
**f + !** - atop of char "!"

> We can link commands together

**number + }** - number of code blocks down  
**number + dd** - delete / 'grab' number of lines down  
**number + hjkl** - number lines/chars in direction  
**d + }** - delete entire block  
**15 + dd** - delete 15 lines of code
