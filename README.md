# FlappyBird
## Download
Click on "code", click on "Download ZIP", download the compressed package, unzip it to any location, open "Flappy Bird. py" inside, and you can run the program. Since this is done by Pygame, you need to download Pygame first.

If you have Python installed on your computer, simply run '**pip install pygame**' on cmd, and then use the following command to check the Pygame version.
```
python -m pygame --version
```
## How to play
- Space Start playing and jumping.
- R Return to the main interface.
## Custom skin
### background
The default skin for the game background is random. To customize it, change the code on line 31 of "Flappy Bird. py" to the following one, with 'xxx' being 'day' or 'night'.
```
IMAGES['bgpic']=IMAGES['xxx']
```
### Bird
The default skin of the game is random for the bird. To customize it, change the code on line 32 of "Flappy Bird. py" to the following code, with 'xxx' being any of "red", "blue", or "yellow".
```
color='xxx'
```
### Column
The default skin of the game's pillars is random. To customize it, change the code on line 32 of "Flappy Bird. py" to the following code, with 'xxx' being either "green-pipe" or "red-pipe".
```
pipe = IMAGES['xxx']
```
## Version
### v1.0.1
Added the function of returning to the main interface.
### v1.0.0
Ordinary gaming features.
