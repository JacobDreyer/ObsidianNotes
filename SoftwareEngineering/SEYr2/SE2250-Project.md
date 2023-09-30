## Design Stage
#### Classes
- Player Class
- Enemy Class
- World Class
	- Level Class
- Obstacle Class
	- Wall Class
	- Floor Class

### [[SE2250-Project-PotentialStoryLines]]
- [[SE2250-Project-PotentialStoryLines-QuestForTheCrystal]]

![[Drawing 2023-03-06 10.17.50.excalidraw]]

### What still needs to be implemented:
- Challenges
- NPCs to add dialogue
- Tower Killing enemies in TD mode
- TD mode ending
- Level Implementation
- Buying/Upgrading Towers

![[Drawing 2023-03-23 09.18.17.excalidraw]]

# Testing

### Player
- ##### Criteria
- Moves left, right, down, up with the arrow keys
- Cannot pass through walls
- Ability to Interact with NPCs in close proximity
- Ability to Interact with Doors in close proximity
- Ability to Interact with Items in close proximity

##### Move Criteria
| Input                          | Expected Output             | Actual Output               | Result |
| ------------------------------ | --------------------------- | --------------------------- | ------ |
| No Input                       | Player Stands Still         | Player Stands Still         | Pass   |
| Left Arrow                     | Player Moves Left           | Player Moves Left           | Pass   |
| Right Arrow                    | Player Moves Right          | Player Moves Right          | Pass   |
| Up Arrow                       | Player Moves Up             | Player Moves Up             | Pass   |
| Down Arrow                     | Player Moves Down           | Player Moves Down           | Pass   |
| Left & Right Arrow             | Player Stands Still         | Player Stands Still         | Pass   |
| Up & Down Arrow                | Player Stands Still         | Player Stands Still         | Pass   |
| Left & Up Arrow                | Player Moves Up and Left    | Player Moves Up and Left    | Pass   |
| Right & Up Arrow               | Player Moves Right and Up   | Player Moves Right and Up   | Pass   |
| Left & Down Arrow              | Player Moves Left and Down  | Player Moves Left and Down  | Pass   |
| Right & Down Arrow             | Player Moves Right and Down | Player Moves Right and Down | Pass   |
| Left & Right & Up Arrow        | Player Moves Up             | Player Moves Up             | Pass   |
| Left & Right & Down Arrow      | Player Moves Down           | Player Moves Down           | Pass   |
| Up & Down & Left Arrow         | Player Moves Left           | Player Moves Left           | Pass   |
| Up & Down & Right Arrow        | Player Moves Right          | Player Moves Right          | Pass   |
| Up & Down & Right & Left Arrow | Player Stands Still         | Player Stands Still         | Pass   |


