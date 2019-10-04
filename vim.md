## Movement keys

**hjkl** - left down up right

## Quitting

**:q!** - quit and dont save the file  
**:q** - quit and save the file  
**:wq** - quit and write  
**:w** - save change and not quit

## Modes

i - insert mode  
V - visual mode, where we can see what we are doing!

- in visual mode we can use the movement commands such as } to jump to the end of multiple now selected blocks
- once we have made our selections we can use commands such as d to delete it

**i** - insert mode  
**esc** - command mode

## Commands

**dd** - delete a line / 'grab'  
**u** - undo  
**⌃ r** - redo  
**G** - end of file  
**gg** - start of file  
**}** - end of block  
**{** - start of block  
**number + hjkl** - number lines/chars in direction

> Alot of the commands in vim follows this convention for example

**number + }** - number of code blocks down  
**number + dd** - delete / 'grab' number of lines down  
**yy** - copy line  
**p** - paste below  
**P** - paste above  
**o** / **O** - newline below or above and then jump into insert mode

> We can link commands together

**d + }** - delete entire block
