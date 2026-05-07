# Wake Up - A game design student experience waking up
Student Name: Darius Palaghie
Student Number: A00027602
Class Group: TU984

# Gameplay video
https://www.youtube.com/watch?v=HMOLhn-QIyk&feature=youtu.be

# Screenshots
Bus stop objective
<img width="1903" height="1078" alt="Screenshot 2026-05-07 232021" src="https://github.com/user-attachments/assets/16022380-c281-4614-b5bf-0fe0464e0df7" />
Coin interactable
<img width="1591" height="952" alt="Screenshot 2026-05-07 232005" src="https://github.com/user-attachments/assets/3cce09f5-b6a3-4030-8af8-3d61b4e4b123" />
Spawn point
<img width="1911" height="1074" alt="Screenshot 2026-05-07 231957" src="https://github.com/user-attachments/assets/6ff4309e-d8cf-437b-8f34-8efa1391de0f" />
2d clicking game
<img width="1868" height="1056" alt="Screenshot 2026-05-07 231951" src="https://github.com/user-attachments/assets/4efd7b4b-d17a-44cc-ad47-d047a9a59d23" />
Intro screen
<img width="1897" height="1023" alt="Screenshot 2026-05-07 231943" src="https://github.com/user-attachments/assets/d8660cc1-fc49-417e-ac0f-ad3b41b7a4ec" />
Credits/end screen
<img width="1912" height="1087" alt="image" src="https://github.com/user-attachments/assets/594ec01d-fe5f-4cc7-83f5-d9e8906327ad" />

# Project Description
This project was for a computational arts module. The game is a simulation of what its like to wake up within a dream world.
You must turn on your brain to begin in 2d then collect all the coins in the 3d world but still within the dream. You then go to the bus stop but its not a bus but a plane and fly to college.

# Instructions to use
The game should have a start screen, credits, ui elements, 2d elements, 3d elements and systems/mechanics.

# How the game works
Start game
Do task
Next Task

# Minigames
First minigame, tap the brain to turn it on.

Second Minigame, find all the collectible coins.

Third minigame, get to the bus and go to college.

# List of Assets/Classes

| Class/Asset        | Source          | Use  |
| ------------- |:-------------:| -----:|
| mainmenu.gd     | Self Written | Where the button to start the game is and switch to next scene |
| brain.gd     | Self Written | Click the brain 2d game |
| bullet.gd     | Self Written | Controls the bullets shot from the gun. |
| busStop.gd     | Self Written | Changes camera when you reach bus stop and plays the animation. |
| coin.gd    | Self Written | Collects and deletes 1 coin through collision while adding it to the counter. |
| coinmanager.gd     | Self Written | keeps coins stored and changes value on the ui. |
| pet_cats.gd     | Self Written | Controls the feed-cats minigame, plays the cats' meows, and sends the player to the next scene. |
| catbowl.gd     | Self Written | Fills the cat bowls when the cat food is put on them. |
| cat_food.gd     | Self Written | Fills the cat bowls when dragged onto them. |
| runbus.gd     | Self Written | Makes the scene end and transition to the main menu 3 seconds after entering the bus. |
| player.gd     | Self Written | Player controller. |
| car_spawner.gd     | Self Written | Spawns car scenes within a certain area, and deactivates when the player gets close enough to it. |
| car.gd     | Self Written | Makes cars move at a constant speed along the z-axis and gives the cars random colours. |
| car_crashed.gd     | Self Written | Gives the cars random colours. |
| enemy_spawner.gd     | Self Written | Spawns the enemy once the player enters an Area3d. |
| enemy.gd     | Self Written | Makes the enemy fall and start following the player after the cutscene, trying to eliminate the player in an Area3D (hitbox). |
| cutscene_controller.gd     | Self Written | Causes and controls the cutscene once the player enters an Area3D. |
| bus.gd     | Self Written | Makes the bus move along the x axis and moves the player's camera once they enter its Area3D. |
| credits.gd   | Self Written | Brings player back to the main menu when the screen is clicked. |
| intro1.gd     | Self Written | Click to go to the next sequence. |
| intro2.gd     | Self Written | Click to go to the next sequence. |
| intro3.gd     | Self Written | Click to go to the next sequence. |
| intro4.gd     | Self Written | Click to go to the next sequence. |
| intro5.gd     | Self Written | Click to go to the next sequence. |
| intro6.gd     | Self Written | Click to go to the next sequence and start the timer. |
| music.gd   | Self Written | Plays the background music globally. |
| timer_ui.gd   | Self Written | Controls the timer through global functions called by other scripts and tweens. |
| game_over.gd   | Self Written | Resets the game's scores, timer, and connects try again and menu buttons to their respective scenes. |
| transition_screen.gd   | Self Written | Controls the transition screen between scenes through global functions called by other scripts. |
| chicken.gltf  | Self Made (Blockbench) | Model made for the chicken enemy. |


