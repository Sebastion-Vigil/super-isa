# Super Isa 

## Basic Run and Jump Platform Game

*An otherworldy adventure starring Super Isa*

### 5 Basic Components/Conceptual Chunks:
*in no particular order--yet*
- A steadily-moving platform incrementally increasing in speed
  - Increment method?
  - Max speed?
- A much slower steadily moving background
  - R&D Parallax
  - Different speeds?
  - Different worlds/levels?
  - Night/day?
  - Weather/Environment changes?
- A jumping sprite--our one and only, Super Isa
  - Simple jump physics--for now
  - Rainbow laser?
  - Health Meter?
  - Other characters?
- Other sprites--enemies/obstacles to jump over/defeat
  - Same pace as moving platform?
  - Health meter for baddies?
  - Evil laser guns/strange weapons for some baddies?
  - Helpful NPCs?
- A Score/info window somewhere at the top of the screen.
  - Health
  - Character
  - World/level
  - Lives
  - *power ups?*

#### Game Mechanic Brainstorm ####

~~Function that randomly sends enemies onto screen, making game harder at higher levels~~

Sound effects?

Music?

Hit boxes? PX only? Measurement?

Jump how high?

MVP?

Initial GameScreen as layer for choosing game
- Needed to select game
- Only one at first
- Dummie second game for testing purposes
- Build bigger later

GameScreen sends GameEngine title of game selected

GameEngine then grabs corresponding resources from games

One main GameEngine fed all variables for:
- Enemies 
- Background
- Platform
- Super Isa sprite
- Game Info Window

Game starts.

Level determines number of enemies at a time, type of background, speed of platform


