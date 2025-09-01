**1. Description**

A Python program that simulates a silent auction by collecting bids from multiple users. Users can input their names and bid amounts, and the program keeps track of all bids. After all bids are collected, the program identifies and announces the highest bidder.

**2. How It Works**

The program repeatedly asks users for their name and bid amount.

Bids are stored in a dictionary with the bidder's name as the key and their bid as the value.

After each bid, the program asks if more bidders want to participate.

Once no more bidders remain, the program determines and prints the highest bid and the winner.


**3. Operators and Functions Used**

Operators:

= (Assignment): Assigns values to variables, dictionary entries, and control flags.

> (Greater Than): Used to compare current bid with the highest bid to update the winner.

. (Dot Operator): Calls methods like .lower().

: (Colon): Defines blocks after conditionals and loops.



Functions and Methods:

input(): Collects user inputs for names, bid amounts, and continuation response.

int(): Converts bid input from string to integer.

print(): Outputs prompts and winner announcement.

for loop: Iterates through all bidders in the dictionary.

find_highest_bidder(): Custom function to determine the highest bid and winner.
