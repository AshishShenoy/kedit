Kedit
===

Kedit is a small text editor, forked from the popular learning project Kilo
by antirez. This is my first intermediate project in C, and it is a change 
from the usual short script-like programs I've written till now.

This project was made with the help of 
[this interactive tutorial](https://viewsourcecode.org/snaptoken/kilo/)

Source: [Kilo Text Editor on GitHub](https://github.com/antirez/kilo)

Usage: 

    kedit `<filename>`

Shortcuts:

    CTRL-S: Save
    CTRL-Q: Quit
    CTRL-F: Search in file (ESC to exit search, arrows to navigate)

Kedit is written entirely from scratch and does not depend on any external 
C libraries (not even curses). It uses fairly standard escape sequences. 

People are encouraged to use it as a starting point to write other editors
or command line interfaces that are more advanced than the usual REPL
style CLI. 

I highly encourage you to look at the original project by antirez as well.

Kedit is released under the GNU General Public License v3.0 in 2019.
Any suggestions in the form of Pull Requests are welcome.
