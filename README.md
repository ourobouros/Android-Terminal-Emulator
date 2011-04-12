#Android Terminal Emulator (Acer E130 Mod)

This is my quick 30 minutes hack to add some keymapping to make the terminal more usable for my Acer BeTouch E130. I didn't use any configuration, everything is hardcoded for my own need.

I added the 'Sym' button as new modifier, with the following bindings:


  * Sym + t = '{' (in the keyboard Fn + 't' is '(', so it is easy to remember)
  * Sym + y = '}' (in the keyboard Fn + 'y' is ')', so it is easy to remember)
  * Sym + / = '\' (mnemonic: reverse /)
  * Sym + i = '|' (mnemonic: looks like an 'i')
  * Sym + q = ESC (mnemonic: escape is on top left)
  * Sym + . =  '<' (mnemonic: like in standard qwerty keyboard, but inverted the position)
  * Sym + , =  '>' (mnemonic: like in standard qwerty keyboard, but inverted the position)
  * Sym + v =  '^' (mnemonic: v is inverted '^') 
  * Sym + 'o'  = '[' (mnemonic: the position of [ in standard keyboard is on top right)
  * Sym + 'p'  = ']' (mnemonic: the position of ] in standard keyboard is on top right)
  * Sym + 'w'  = '~' (mnemonic: the position ~ is almost on top left on standard qwerty)  
  * Sym + 'k' = "`" (mnemonic: backtikc looks like inverted single quote)  
  

##Android Terminal Emulator (original readme)

Android Terminal Emulator is a terminal emulator for communicating with the built-in Android shell. Emulates a reasonably large subset of Digital Equipment Corporation VT-100 terminal codes, so that programs like "vi", "Emacs" and "NetHack" will display properly.

This code is based on the "Term" application which is included in the Android source code release. It's provided as a separate project for the convenience of developers who do not want to deal with installing and building the whole Android source tree.

Although this program does not include a built-in ssh client, it can be used with command-line-based ssh tools such as dropbear.

Got questions? Please check out the [FAQ](http://github.com/jackpal/Android-Terminal-Emulator/wiki/Frequently-Asked-Questions) before emailing or adding an issue. Thanks!

Please see the [Recent Updates](http://github.com/jackpal/Android-Terminal-Emulator/wiki/Recent-Updates)
page for recent updates.
