# Tetris Game

### There are 4 files in our project, 
```
newgame.py  -- invoked when new game is needed
tetris_game.py -- actions performed after key is pressed, updating GUi after update is maintained by this code
tetris_ai.py -- this file contains code for AI agent, which returns best strategy to tetris_game.py
Tetris_models.py -- this file has characteristics of game, grid size , co-ordinates, shapes etc
```
### Follow the instructions below to run the code
```
For heuristic agent, set agent=1 in line 1 of tetris_ai.py
For greedy agent, set agent=2 in line 1 of tetris_ai.py
For random agent, set agent=3 in line 1 of tetris_ai.py
To play manually, uncomment line 10 in tetris_game.py
```
To slow up the game speed , increase speed at line 25 in tetris_game.py (increase value of self.speed)<br>
<br>


### Installl requirements using the folllowing command
```
pip3 install -r requirements.txt
```
### Start the game using following commad
```
python3 tetris_game.py
```
