# VIM

Link of video tutorial: https://www.youtube.com/watch?v=ggSyF1SVFr4

## Basics

Open a file using vim just enter the name of the file

```
vim myWonderfulFile.md
```

By default, you ar in `normal` mode, it mean that you can only move through the file and make some command.
If you want to update the file, you have to switch to `insetion` mode using the `ì` command.
To coma back to normal mode, just use `Esc`

Command:
- `:set number` will add number for each line of file
- `dd` will delete a entire line
- `u` will undo your last change
- `^r` will redo your last undo
- `/<string>` will search for matching string
- `n` will go to the begenning of the next searched match string
- `N or shift + n`  will go to the previous searched match string 
To coma back to normal mode, just use `Esc`
