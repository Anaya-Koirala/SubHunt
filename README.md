# Play the Game
[Link](https://itch.io/jam/games-for-blind-gamers-4/rate/3362529)

# **SubHunt: A Submarine Battle Game**  

The vast nothingness of the ocean has been disturbed by a silent enemy! A submarine is lurking somewhere out there, bent on hunting you down. 

No sunlight reaches these depths, no sea creature dares visit these waters—all that exists is the prey and the predator sub. Now it's your job to determine which sub becomes the prey and which becomes the predator.  

## Gameplay  
- Fire torpedoes to attack.  
- Use sonar pings to locate the enemy (*Beware! frequent pings reveal your location*).  
- Predict enemy movement based on the last known ping.  
- Destroy the enemy to advance levels.  

## **Controls**
- *Up, Down, Right, Left* - Move and Turn
- *Space Bar* - Fire Torpedo
- *S* - Sonar Ping
- *E* - Get Last Known Location

## **Debug**
*Note: Not intended for actual gameplay*
- *R* - Randomly place ball (BUG: you may have to press it twice)
- *C* or *`* - Toggle camera (on/off)
 

## What's New?
### 2/26/2025
- Added sound settings and instructions UI
- Added game over and next level functionality
- Added last known location (e key)

### 2/25/2025
- Targets make a noise audible when you are nearby.
- Target can fire torpedo
- Target moves using physics forces 
- Player takes damamge from torpedo hit
- Reduced to one target.

### 2/25/2025
- Incorporated Anaya's code organization (subfolders in res:// ) and torpedo.
- Incorporated Dipto's short sonar sound.
- Incorporated Yash's code for movement.
- Ball is now Target.
- Field is bigger and more square.
- Made individual scenes out of Player, Target, and Field. Main has instances of them.
- Added a script to Field which indicates when the player has gone more than 90m from the center.
- Target responds to torpedo.
- Added a bunch of sounds.
- Handles multiple targets (sonar pings from each one)
- Added this list to README.md

## Controls
- Arrow keys: move and turn
- C or `: Toggle camera (on/off)
- S: Sonar ping
- SPACE: fire torpedo
- R: randomly place ball (BUG: you may have to press it twice)

## TODO
### Game Components
- Make a target that is destroyed when the player touches it.
- Make a torpedo (fire by either the player of enemy)
- Make a target which is destroyed by a torpedo
- Make a mechanism for firing the torpedo

### Game Play
- Create a start, end, and next level mechanism
- Create levels (search, survive, destroy)

### Audio
- Sonar: ping and response
- Text to speech game and level instructions
- Find or make good sounds (see below). These should be licensed for free use, preferable allowing us to alter them. Keep track of where they came from for the credits.

### Sounds 
- Ping noise
- Response noise
- Torpedo noise
- Player destroyed noise
- Target destroyed noise
- Collide with something noise
