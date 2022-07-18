# save-playlist
This script saves your current playlist to the working directory of the mpv process and works well along with [autoload.lua](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autoload.lua).

Disclaimer: This is not my script. I took it from a [reddit thread](https://www.reddit.com/r/mpv/comments/ax925a/comment/emhpie3/?utm_source=share&utm_medium=web2x&context=3) and added it here since I couldnt find a script that saves the playlist and works with [autoload.lua](https://github.com/mpv-player/mpv/blob/master/TOOLS/lua/autoload.lua).

Thanks to [@Goroto](https://github.com/garoto) (the deleted one) and [@jonniek](https://github.com/jonniek) (his muse) for the script! All credits go to both of them. Without their help, this wouldn't have existed. Thank you again!

# Installation
Place this script inside your `/scripts` folder.

# How to use the script?
To activate the script press `Alt + s`. This keybind can be changed also via your `input.conf`.

Instructions to do that is given below.

# How to change keybind
The keybinds for this script can be changed by placing the following lines in your ``input.conf``:  
```
KEY script-binding save-playlist
```
