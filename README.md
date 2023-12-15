## jvalc's build of dmenu

## Usage
Get more information about the usage of my build, including useful keybindings
by executing `man dmenu` in your terminal.

## Used patches from suckless project
- border:                               Add border around dmenu window
- caseinsensitive:                      Set case-insentative to default behaviour
- grid:                                 Allows dmenu to render entries in grid mode
- gridnav:                              Adds ability navigate dmenu up/right/left/down
- highlight:                            Highlights matched text for each dmenu entry
- mousesupport:                         Allows dmenu to have mouse funcionality

## Installation 
- `git clone https://github.com/jvalc82/dmenu.git`
- `cd dmenu`
- `make`
- `sudo make install`

## Future steps
All the code can be expanded from source. Also, to change some of the configurations
you need edit the "config.h", do not edit "config.def.h".

