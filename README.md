# Sudoko
A simple HTML + JS implementation of the game.

It's still under development which means it's barely playable.

Just open the [index.html](index.html) file on any browser to play the game.

## TODO
In no particular order:
### Must-Have Features
- [x] Game generator
- [x] Save game progress in sessionStorage
- [ ] Mark wrong cells
  - [ ] Absolute error (test against solution)
  - [ ] Relative error (collision with row/col/box)
- [ ] Restart the same puzzle
- [ ] Undo button
  - [ ] Redo button
### Nice to Have Features
- [x] Game timer
  - [ ] Continued over sessions
- [ ] Manual board input
  - [ ] Validity test for manual board
- [ ] Game solver
- [ ] Save statistics for all games in localStorage
- [ ] Automatic pencil marks
- [ ] Modify color scheme
- [ ] Game completed animation
- [ ] Link to specific board states in a query string?
### Known Bugs
- [ ] Board state is incompletely restored
  - [ ] Pencil marks aren't saved
  - [ ] All digits on the board change to hardcoded after load
- [ ] Timer does not continue from previous value when loading data
- [ ] Some borders appear to not overlap