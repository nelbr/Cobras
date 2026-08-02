COBRAS

COBRAS is a Snake-inspired game included as a demonstration of the capabilities of my Apple II+ emulator.

The Pleasure of Discovery: Find out the wicked challenges of increasing difficulty included in each level.
The Thrills of High Score Achievements: Beat your own scores or your friends results
The Challenge of Boss Fights: Kill the boss to win the game on the 10th level of this demo


## Features

- Fast low resolution graphics
- 10 increasingly challenging levels
- Intelligent fruit placement to avoid unreachable positions
- Score points by eating fruit
- Obstacles include your own tail, mines, and walls
- Level-up and high-score intermission screens
- Apple II speaker sound effects
- Persistent high-score table stored on disk
- No-Slot Clock support for recording the date of each high score

Controls
A         Move Up
Z         Move Down
←         Move Left
→         Move Right

## Technical Notes

COBRAS was written entirely in Applesoft BASIC and compiled using the Einstein Applesoft Compiler for improved performance.

The original Applesoft source code is also included on the disk. When running the interpreted version, gameplay speed can be adjusted by modifying the DE (delay) variable.

## Performance improvements include:

- Circular buffer used to store the snake body
- Only the head and tail are updated each frame
- Static playfield objects are drawn only once
- Collision detection is performed directly against the video buffer, eliminating the need for a separate playfield array

I hope you find this game interesting. Code is available in Github at: https://github.com/nelbr/Cobras

Feel free to leave game suggestions, bug reports or just a message on the repository if you wish. I would be glad to hear from you. 
