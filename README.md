Project written completely by Benjamin Raidman. To distribute or edit code request permission.
I had some trouble finding a partner so I just did the project alone. As you can see the board game I
chose to do was BattleShip. I chose to do a traditional grid style of battleship and used arrays to keep track
of all the cells on the board.

<*Game Instructions*>

Note: Placing the ships can be confusing at first but once you understand how it works it is easy.
Placing ships vertically can be tricky especially. Below there are instructions to place the ships.

Once you click "Play Game" the BattleShip game will open. It will start with Player 1's turn
as indicated on the screen. The left side marked blue is the current player's area for their ships.
The right side marked red is the enemy's area for the ships that they are attacking. Simply click the
cells to interact with the board game. There are five ships and you must place all five!

This is the trickiest part of the game. Here is how to place your ships on the left side (blue side,
the current player's area). All ships will be set to the size of 3 cells. To place a ship horizontally,
simply click a cell. Keep in mind that when you click this cell, it will occupy from this cell to the
next 2 right cells. So when you click a position, it will start from the left spot you choose and move
two positions to the right. To place a ship vertically, simply click the same spot twice. When placing
horizontally, the full ship will not appear until you place the next ship or click the rightmost position
(two to the right of the cell you just clicked). If you click too far, it will simply place another ship.
Ships will not be placed too close to the border (not a distance of 3) or on other ships. Simply click
"End Turn" when done, and then Player 2 will place theirs and end their turn when done.

Now you can attack. Simply click a cell on the right side (the red side) of the board where the enemy's
ships are and click "End Turn" to allow the opponent to play their turn. You can only hit one cell at a time.
Where you click is where you are attacking. To beat your opponent, you must sink all their ships, which is done
by hitting every cell of the ship. You can use whatever strategy to sink the opponent's ships, but whoever sinks
all their opponent's ships first wins the game.


<*Extra/Stand Out Features*>
Instruction Page.
Icons/Images.
Rotation of ships.
Identification of when an individual ship is completely hit and sunk.
Counters for ships sunk.
Pop ups to notify when ships are sunk and when you win the game.
Seperate boards for both players and using end turn swaps between the boards. 


<*How To Compile Code*>
If you extract hwx.jar you will find the directory bens_battleship. My code is all in the package bens_battleship.
So to run the code simply run the following command from the directory containing bens_battleship:
	
java bens_battleship/BattleShip
