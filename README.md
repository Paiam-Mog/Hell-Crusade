# Hell Crusade

# Game Description
Hell Crusade is a 2D top-down, bullet hell game built as a final project for a network programming class in collaboration with 5 other students. Players take on the role of an angel descending down into hell to defeat the demon army and overtake the Demon Queen. The game portion of the project is developed using the Unity Engine. All code samples are written in C#.

# Role on the Project
I worked as the gameplay engineer for the project, collaborating with the team on design and art direction. As the gameplay engineer, I designed and implemented the systems associated with the gameplay including the behavior of the enemys, bullet controller, player controller, and a wave manager system. I worked with our networking frontend engineer on connecting the points system in the game to add player scores to the leaderboard.

# Implemented Systems and Features 
Some of the systems and features that I have worked on or implemented during my time include:
 * Enemy Manager System that handles spawning the enemies in each wave, keeping track on when the enemies die and when to transition from one wave to another
 * Bullet Manager System that handles spawning bullets (both player and enemy bullets) and assigns them their sprites and flight path as well as handles their death 

# Playing the game
Download the Hell Crusade zip file, unzip the file and inside the Hell Crusade folder run the executable file. 
Note: The server is no longer up so game boot up may take some time as it attempts to connect to the server. Login, Register, and Leaderboard are unavailable.

The game also features a "Hacks On" mode (toggled by pressing the 'h' key) where the player cannot be hurt, shooting cooldown is extremely reduced, 10 times as many enemies spawn, and the boss has much more health. This mode is mostly for fun and may cause small issues in the game such as frame rate drops and delays in bullet spawning.
