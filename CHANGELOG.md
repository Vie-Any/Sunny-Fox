# Change Log

### The course video from [🔗Unity.cn](https://learn.u3d.cn/)

### [🔗The series course video <sup style="color:red">Need to pay</sup>](https://learn.u3d.cn/tutorial/Visual-Scripting)

## 2021-06-24
- Implement movement for when the player was climb ladder state
- Implement exist from climb ladder state back to other state
- Create climb animation
- Update animation control script machine, add climb ladder animation switch
- [Chapter 15 - video] Part 1 - Climb the ladder - function implementation and climb animation


## 2021-06-22
- Review ground check script machine
- Review crouch script machine
- Implement celling check and keep stay crouch state when the player was in crouch but the vertical button was released
- Add ladder to the scene
- Use script machine to mark the relationship between the player and the ladder
- Implement on ladder check, means the player was on the top of ladder and land on the ladder
- Implement in ladder check, means the player was touch the ladder and land on the ground.
- [Chapter 13 - video] Part 1 - Celling check when the player was crouch
- [Chapter 14 - video] Part 1 - Climb the ladder - state check


## 2021-06-13
- Implement crouch for the player
- Implement movement when the player was crouch state
- [Chapter 12 - video] Part 1 - Player - Crouch


## 2021-06-08
- Create enemy Frog
- Create script machine for switch animation
- Create state machine for control the frog movement and patrol
- [Chapter 11 - video] Part 1 - Enemy - Frog - Patrol


## 2021-06-07
- Create a state machine for the enemy Opossum
- Complete patrol via state machine
- [Chapter 9 - video] Part 1 - Enemy - Opossum - Patrol
- [Chapter 10 - video] Part 1 - Enemy - Eagle - Patrol


## 2021-06-06
- Add an camera instead of the original camera
- Add the background image as a child component of camera
- Add a dead line to stop the game when the player was drop out of the scene and reload the scene again.
- Add an enemy - opossum
- Use event trigger to implement death for the player and enemy
- Uniform death animation for the enemy
- Lear about Animation Event in visual scripting
- [Chapter 6 - video] Part 1 - Cinemachine
- [Chapter 7 - video] Part 1 - Dead line
- [Chapter 8 - video] Part 1 - Enemy - Opossum & death trigger


## 2021-06-03
- Active visual scripting feature in unity
- Know about visual scripting panel
- Learn about get Keyboard/Mouse Input, life cycle and scope of different variables
- Learn about how to set/get variables in visual scripting panel
- Learn about how to use judgement and select node in visual scripting panel
- Learn about how to conbine different process node to implement function in visual scripting panel
- Learn about how to group by nodes
- Implement player movement and flip
- Implement player jump and limit the player could jump only one time
- Change gravity scale for optimize fall down smooth after jump
- Create animator for the player
- Create idle, running, jump, fall animation for the player 
- Use visual scripting node switch different animation state
- [Chapter 3 - video] Part 1 - Movement & Flip
- [Chapter 4 - video] Part 1 - Jump & Ground Check
- [Chapter 5 - video] Part 1 - Player Animation


## 2021-06-02
- Install Unity 2021.1.0
- Create 2D project
- Import [Sunny Land <sup style="color:green">free</sup>](https://assetstore.unity.com/packages/2d/characters/sunny-land-103349) package source from asset store.
- Use 2D extra create a rule map
- Change all the source picture pixle per unit to 16
- Add the player fox to the scene
- [Chapter 1 - video] Part 1 - Install & Import source
- [Chapter 2 - video] Part 1 - 2D extra for draw map
