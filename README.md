## Stockfish 9 on Android

Before trying to introduce StockFish engine into an Android application, I wanted to see if it runs well on the phone or tablet.

There are two repositories by "chess24", but I was not lucky enough to get them compiled and run using fresh version of Android Studio:
 
 * https://github.com/chess24com/StockfishService
 * https://github.com/chess24com/StockfishServiceTest
 
So I have decided to bring the fresh app, and copy-paste the necessary pieces of the code together, without separation into several different projects, and, surprisingly, it worked!
 
Most of the Java source code taken from the original projects, so I kept the copyright notice and the license.
 
Stockfish code originally used in this project originated from checkout 3ab3e55bb5faf57aec864f3bb7268601c11d72be of the official repository, somewhere between sf_8 and sf_9.
 
I've bumped up the code to Stockfish 9, since I don't expect a lot of improvements from 10-11-12, but some complications because of variants and optimizations.
 
I might replace the Stockfish with a more recent version in the future, and probably archive the project, because there's not much work to be done here.
 
Here's a sample output for "uci" command (you have to send one before starting to use the engine) :
 
![Sample output](device-2020-12-27-011523.png?raw=true "Enjoy!")