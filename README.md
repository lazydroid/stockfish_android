## Stockfish test

Before trying to introduce StockFish engine into the Android application, I wanted to see if it runs well on the phone or tablet.

There are two repositories by "chess24", but I was not lucky enough to get them compiled and run using fresh version of Android Studio:
 
 * https://github.com/chess24com/StockfishService
 * https://github.com/chess24com/StockfishServiceTest
 
 So I have decided to bring the fresh app, and copy-paste the necessary pieces of the code together, without separation into several different projects, and, surprisingly, it worked.
 
 Most of the source code taken from the original projects, so I kept the copyright notice and the license.
 
 I'm planning to replace the Stockfish with a more recent version and probably archive the project, because there's not much work to be done here.
 
 Here's a sample output for "uci" command (you have to send one before starting using the engine) :
 
 ![Sample output](device-2020-12-27-011523.png?raw=true "Enjoy!")