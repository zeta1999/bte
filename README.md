
<p align="center"><img src="https://imgur.com/8gdhpmv.png" width="200px"></p>
<h1 align="center">bash text editor</h1> <p
align="center">A text editor written in bash.
Cos why the fuck not</p>

<p align="center"><img src="https://imgur.com/0NXQVJw.png"></p>


## Requirements
```
bash 4+
```

## Progress

- [X] Loading file
- [X] Basic text navigation
- [ ] Complex text navigation
  - [X] `PGUP` and `PGDWN` nav
  - [X] `HOME` , `END` nav
  - [ ] `Ctrl+[arrow keys]` nav / Word based nav
- [X] Inserting characters
- [X] Removing characters
- [ ] Text manipulation
  - [ ] Selecting text
  - [ ] Copying selected text
  - [ ] Pasting selected text
  - [ ] Searching text
  - [ ] Replacing text
- [X] Undo & Redo immplemented
- [X] Saving File
- [ ] Opening a file from an empty buffer
- [ ] Syntax Highlighting

## Keybindings
```
Arrow Keys  : For cursor movement
Pg Up       : To move up a page
Pg Dwn      : To move down a page

Meta+G      : Goto line/coord

Back Space  : To delete the character before the cursor
Delete      : To delete the character under the cursor

Meta+U      : Undo the most recent action
Meta+R      : Redo an undone action

Ctrl+O      : Write to file
Ctrl+X      : Exit
```

## Why i made it?
This is just a passion I chose to do after being inspired by [fff](https://github.com/dylanaraps/fff). Thank you @dylanaraps ^u^
