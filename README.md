solarized-osx-terminal-colors
=============================

Terminal colours for the Solarized coloscheme

I've only tested this on Mountain Lion and Mavericks, and cannot guarantee success using any other version.

I suggest using iTerm2, with using the main solarized repo's iTerm2 preset. iTerm2 (with about 5 minutes of customization) is much more powerful and easier to use than Terminal.app. However, if you are deadset on using Terminal.app, these colorschemes work great.

Installation:
-------------
####For Mountain Lion and above:
Use the xterm-256color configurations

####For anyone that doesn't work for:
Use the xterm-ansi configurations


#####For use with Vim:
Put the following in your .vimrc, and remove any colour hacks (`let g:solarized_termcolors=256`, etc.)

    set background=<either dark or light>
    colorscheme solarized

###Credit:
Ethan Schoonover for the awesome colorscheme – http://ethanschoonover.com/solarized
