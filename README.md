haskell-tetris
=====
Project for Programming Languages for Saint Louis University 2015, by Matthew Meyer.

####To Do
 - make a score display
 - enable rotation when a piece is at the very top of the board
 - display the next piece to be added
 - define level speeds and the ascension of levels after so many blocks
 - figure out a monad or something for instant getChar

####Cabal Dependencies
- ghc base
- System.Console.ANSI
- System.Random
```sh
$ sudo cabal install ansi-terminal random
```


####Build and Run
Have ghc and cabal installed.
```sh
$ runhaskell Main.hs
```
