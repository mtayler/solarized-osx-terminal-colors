solarized-osx-terminal-colors
=============================

The correct colors for Terminal.app to run Solarized (fixes editor colorscheme)

I've only tested this on Mountain Lion and Mavericks, and cannot guarantee success using any other version.

Installation:
-------------
Put the following in your .vimrc, and remove any colour hacks (`let g:solarized_termcolors=256`, etc.)

    set background=<either dark or light>
    colorscheme solarized
  
####For Mountain Lion and above:
Use the xterm-256color configurations

####For anyone that doesn't work for:
Use the xterm-ansi configurations
