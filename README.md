# Tower Game  

#### Credits
An implementation of KidsCanCode tutorial #2 -- [found here](http://kidscancode.org/lessons/)  

Art by [Kenney.nl](https://www.kenney.nl/) <-- view Kenney's art

Sounds designed by skunkpirates42 using [https://www.bfxr.net/](https://www.bfxr.net/)

## Playing Tower Game
  - Play to get the highest score!
### Moving
  - To __move left and right__, use the left ⬅️ and right ➡️ arrow keys 
  - To __jump__, use the spacebar
      - __Notes on jumping:__ The jump in this game is variable, meaning that the longer you hold the spacebar down (to an extent), the higher the player will jump. Respectively if you tap the spacebar and let go, the player's jump will be very small
  - You can go __off the left or right side of the screen__. If you do, your player will appear on the opposite side that you left the screen from. <- *Keep this in mind for game play strategy*
### Powerups
  - If your player makes contact with one of these powerups, You will get a large boost up into the sky, but be careful to land on a platform!
### Enemies
  - There are flying propeller driven enemies! Do not make contact with these things or your game will be OVER

### Steps to Set Up Locally
  - Clone this repository onto your machine
  - If you do not have Python3 installed on your machine, you will need to install it
      - The download can be [found here](https://www.python.org/downloads/) at the Python website
  - With your terminal open in the root directory of this project install dependencies with `python3 -m pip install -r requirements.txt`
  - Next, to get the game running, run `python3 main.py` 

### Technologies used
  - [Python3](https://docs.python.org/3/)
  - [Pygame](https://www.pygame.org/)
      - ^^^ For more information on either, click the links above
