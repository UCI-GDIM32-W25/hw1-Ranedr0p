[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity

Put your notes from the W1L2 (Thurs, Jan 9) in-class activity here.

## Devlog
Prompt: Include the HW1 break-down exercise you wrote during the Week 1 - Lecture 2 (Jan 9) in-class activity (above). If you did not attend and perform this activity, review the lecture slides and write your own plan for how you believe HW1 should be built. If your initially proposed plan turned out significantly different than the activity answers given by Prof Reid, you may want to note what was different. Then, write about how the plan you wrote in the break-down connects to the code you wrote. Cite specific class names and method names in the code and GameObjects in your Unity Scene.


Write your Devlog here!

Break down
Objects:
player character 
Seeds
UI

Properties: 
player can move with WASD
player can plant seeds with spacebar
UI displays the amount of seeds and how many have been planted 

Affect: 
When player plants seeds the UI changes
player affects where the seeds are placed
Can’t plant seeds if player doesn’t have seeds 

Devlog - I feel that my initial breakdown was similar to professor Reid’s breakdown from class except that it was less detailed when it came to which buttons were specified. In my project I clearly have a player, plant seeds, and a UI in the Scene and Hierarchy windows as stated in my breakdown. The player can also move around using the WASD keys like stated due to my movement code in the update function.  The seeds are planted at the player’s position which can be seen in the player class with the plantSeed function and how the plantPrefab is instantiated at the player’s transform as a gameObject called plantSeed. The UI is properly set up at the beginning in the player class start function with the updateSeeds function. The UI changes appropriately with the updateSeeds function in the PlantCountUI class being used in the player class to update the UI to match the seeds planted and used. After all the seeds are used and there are 0 remaining the player is then unable to plant seeds as shown in the if statement in the update function of the player class. 


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
