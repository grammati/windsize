## windsize.el

Easy resizing of emacs windows.

### Usage

    (require 'windsize)
    (windsize-default-keybindings)

Then use `C-S-<left>`, `C-S-<right>`, `C-S-<up>`, and `C-S-<down>` to
move window edges.

Resizes by 8 columns or 4 rows by default. Change that by setting
`windsize-cols` and/or `windsize-rows`.

### License

GPL, of course.
