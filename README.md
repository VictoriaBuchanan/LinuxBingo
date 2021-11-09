# LinuxBingo
LinuxBingo is a bash shell program that takes a file (containing a seed number for the random number generator and a bingo card) as input and runs a bingo game using that card.The bingo card is a 5x5 matrix with the following properties:
* Column L = 5 unique integers from 1 to 15
* Column I = 5 unique integers from 16 to 30
* Column N = 5 unique integers from 31 to 45
* Column U = 5 unique integers from 46 to 60
* Column X = 5 unique integers from 61 to 75

To ensure that program can read the file, the input must start with a seed number, contain 5 rows of numbers with no extranuous white space at the end. Any deviation from this format will trigger various error messages depending on the formatting issue. There are several files under the testfiles folder that can be used to run this program. All files named badInput will trigger various error messages when one while any file called goodInput will let you run the game.

To run the program type the following command in the command line:

```
./LINUX fileName
```
