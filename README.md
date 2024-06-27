# ⛀ Checkers
A simple checkers game, currently only playable on Numworks calculator and coded in micropython  !

## ⌨️ Inputs
To move your selection square you must press on the dedicated directional arrows. 

To select a square you can press the 'OK' or 'EXE' button. First, you have to select the piece you want to move and after select the place where you want to move. 

To give up, it's the 'shift' button and to ask a draw, it's the 'alpha' button. After these to input, a timer of 3 seconds will start to cancel in case you didn't want to do this. 

## 📜 Rules
All classics rules of checkers has been added so check the rules online if you don't know them ! 

I have just added a timer, so make sure not to lose on time!

## ℹ️ Informations
If you select a piece but cannot see the possible squares, it is because there is a forced move to make. In checkers, if you can capture, you must capture, but I have chosen not to display it. You have to figure it out by yourself. 

I didn't have place to display the king when a man is promoted but i changed the color so the basic colors are roughly black or white for the men and full black or white for the kings to distinguish them. 

If you go to a piece, you will see all the movement possibilities from that piece to better visualize the moves you can make.

## 🖥️ Requirements
This program is coded in micropython just for Numwoks calculator but it must works on a computer if you change the module to adapt with Pyhton. But unfortunately, you also have to adapt the size of the boxes to your screen otherwise, it will be hard to see your game.

## 💬 Language
It was coded on a Numworks calculator in Micropython.

## 🛠️ Details
You can change the duration of the timer by yourself by modifying the code. It's at the line 351, you just have to change the value which is currently 600 seconds to let 10 minutes at each players. Don't forget to convert it in seconds !

You can also change the number of square on the board. You have to change the value at the line number ..

Unfortunately, it's in French, but there are not so many text so it won't be hard to understand.

The project has been started the September 6 of 2023 and finished the June 26 of 2024 (I didn't work on it during 9 months strait of course...).
