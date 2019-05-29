# mastermind
Uni project for the Advanced Programming course.

## History
Mastermind is a code-breaking game for two player that is based on an older, paper based game called Bulls and Cows. The modern game with pegs was invented in 1970 by Mordecai Meirowitz, an Israeli postmaster and telecommunications expert. A computer adaptation of it was run on Cambridge University’s Titan computer system, where it was called 'MOO'.

### How to play
In the original version the code is composed of 4 digits and the coder has all 10 decimal digits (0,1,2,3,4,5,6,7,8,9). There are numerous other versions, but the most popular is the one which uses 6 differents colors.

Once the coder has composed his/her code, the guesser makes a first attempt trying to predict the word. Then, the coder provides hints to his/her opponent with the following rules:
- The number of digits in the right position with black pegs;
- The number of digits that are present in the actual code, but they were guessed in the wrong position, with white pegs;
- No hint about which digits are right or wrong is allowed: only about how many.

If the guesser can guess right within the number of trys predetermined (usually 9) he/she win the game. Otherwise, the victory goes to the coder.
