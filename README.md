solarized-osx-terminal-colors
=============================

The correct colors for Terminal.app to run Solarized (fixes editor colorscheme)

I've only tested this on Mountain Lion, but the configuration works now.

Installation:
-------------
Put the following in your .vimrc, and remove any colour hacks (`let g:solarized_termcolors=256`, etc.)

    set background=<either dark or light>
    colorscheme solarized
  
####For Mountain Lion and above:
use xterm-256color


####For anyone that doesn't work for:
use xterm-ansi
