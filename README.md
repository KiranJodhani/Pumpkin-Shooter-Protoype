# Left Field Labs: Unity Engineer Take Home

## Pumpkin Shooter

Currently using Unity 2020.3.0f1

Please see instructions in the file `Left Field Labs Unity Engineer Take Home.pdf`.

- In menu screen Textmesh pro was not used so to make in proper I disabled/removed old ui and added new one
- There is one json file located at scripts/data/ConfigurationJSON.text which has some property to load game title,version,game length
-Fixed issue in main menu start button,game over screen
- Added splash screen and confuguration file in donotdestroyonload to stay persistence through out the game session
- Added playerprebs to store last high score
- All game related configuration can be found in Configuration.cs (Scene name,text file,instance of the configuration class)
- Fixed pumpkin spawn issue after being hit by player
- Score manager added to store and track score
- In polish task. 4.b is integrated. Sound file can be found in spash screen and it play in loop even scene changed
- Additional optimizesation to destroy pumpkin and bullet after they are below certain (-10) in y position 
- Scene name changed to allow easy to understand their sequence in game. 
