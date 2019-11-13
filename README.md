# Online-Chess-Game-master
An online multiplayer chess game. Supports infinite players playing against random opponents on different machines on different networks. This project was created using python 3.7, pygame and the sockets module from python3. It runs on a basic client server system where a server script handles all incoming connections and game management. The clients simply hanlde the UI and game play.

# TO MAKE THIS CODE WORK...
You will need to change the server address from within the following two files:
- client.py
- server.py

You will also need to run server.py on some kind of server. After that you can launch two instances of game from anywhere to play online chess.

# Known Bugs:
- Checkmate does not work, if you loose or win you will need to end the game by hitting "q"
- Very rare bug where a certain move will crash the game
- No Enpesant Pawn Rule


# LICENSE:
*NOT FOR COMMERCIAL USE*
If you intened to use any of my code for commercial use please contact me and get my permission. If you intend to make money using any of my code please ask my permission.
