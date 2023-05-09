# Slot Machine :slot_machine:

## Project Overview :clipboard:

So let’s dive into the project. 
Now, the first thing to mention here is:
:heavy_exclamation_mark: *I do not support gambling. I’m just doing this project because it’s really good one for beginners like me. And to really dive into code and kind of see to create a complete project. But please do not gamble. I don’t gamble myself and I would never encourage anyone to do that.* :heavy_exclamation_mark:

So we’re going to imagine here that we have three reels. Now in each of the reels we’re going to have three symbols, smth like:

![ABC](images/pic1.jpg)

Now, what we're going to have here for our slot machine is three lines. Now, whenever you play a slot machine, there's a certain number of lines that you can win on. Usually it's like 80 lines or 60 lines... In our case, we're just going to do three, and they're just going to be each row. Okay, so these are the three possible lines that you could win on. Now you only win when you have three symbols that match in a row. So in this case, we would have a win, but we would not have a win. And either of these two rows, because we don't have three symbols. Now, each symbol will have a varying multiplier. So if I bet, say, $1 on the line and the symbol had a multiplier of five, then that would mean that we won $5 on that specific line and we're going to allow the user to bet on a certain number of lines. So if they bet on one line, they'd just bet on this. So they need to have something in this section. If they bet on two lines, then they're going to be betting on both of these lines. If they bet on three lines and they bet on all three of these and whatever bet amount they make is going to be multiplied by the number of lines that they bet on. So if they bet $1 on three lines, then they bet $3 in total. And if they get symbols in any one of the rows, then they're going to win a certain amount of money based on what the multiplier is for that symbol.

## Project Setup :gear:

All right. So let's dive into it here. First, we just have a little bit of setup. I'm using Node.js, so make sure you [download Node](https://nodejs.org/en/download). And then I'm using Visual Studio Code. Feel free to write your code wherever you want.

## Building The Project :hammer_and_wrench:

I quickly want to explain kind of the steps that we need to go through so that we understand what it is that we're going to be building before we start writing any code. **Project steps:**

1. Despot some money. 
2. Determine number of lines to bet on.
3. Collect a bet amount.
4. Spin the slot machine.
5. Check if the user won.
6. Give the user their winnings.
7. Play again.

**Code Structure:**

The code is organized into functions that perform specific tasks:

1.  `deposit()`: This function gets the user's deposit amount.
2.  `getNumberOfLines()`: This function gets the number of lines to bet on.
3.  `getBet()`: This function gets the bet per line.
4.  `spin()`: This function spins the slot machine.
5.  `transpose()`: This function transposes the slot machine output to get the rows.
6.  `printRows()`: This function displays the rows on the console.
7.  `getWinnings()`: This function calculates the winnings of the player.
8.  `game()`: This function runs the game loop.

To **run the game**, follow these steps:
1.  Clone the repository or download the code as a zip file and extract it to your local.
2.  Open the terminal and navigate to the project directory.
3.  Run the command `node project.js` to start the game.
4.  The game will prompt you to enter the deposit amount to start playing.
5.  After depositing, the game will ask you to enter the number of lines you want to bet on (1-3).
6.  Then, you need to enter the bet per line.
7.  The game will spin the slot machine and display the result.
8.  If you win, the game will show your winnings and update your balance.
9.  You can choose to play again or quit the game.