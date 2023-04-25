# mark
Simple way to mark and get to common directories using dmenu

use the `mark add` command to add the current working directory to 
the `stored_directories.txt` folder, which does what you'd expect.
Use `mark remove` to remove said directory from the file, and use 
`mark list` to cat the contents of `stored_directories.txt` to stdout. 

Finally, just calling `mark` will open a rofi dmenu with all of the contents of
`stored_directories.txt`. Selecting one of the directories will open a new 
terminal emulator at the chosen spot. Works great with keybinds like if you use
a basic window manager. 

Very unfinished! Currently only works with alacritty and rofi's dmenu emulation! 
Planning on adding universality to the script as well as the ability to 
add multiple different lists, and the ability to simply change the current working
directory if called within a terminal instead of opening a new window! 
