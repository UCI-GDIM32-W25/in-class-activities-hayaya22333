# GDIM32 In Class Activities
## W1
### Activity 1
- Make sure to understand all code that you're writing
- Listening to advices that play testers give you
- Attend office hours


### Activity 2
1. 10
2. 2
3. outputs "hello world" in debug log for every update frame
4. MonoBehaviour
5. outputs "x = 10" in the debug log after starting the program
6. They are parameters of the PrintMessage and Debug.Log functions that affects the function output.
7. Transform is a class, which doesn't work with Translate.
8. Transform should be replaced with _playerTransform, so it's an object being transformed.

### Activity 3
[MG1 breakdown document link ](https://docs.google.com/document/d/1RY8G4u76Aeqqu-rppdIJhAqMhHotRh3U2m445UlfjAs/edit?usp=sharing)
## W2
### Activity 1
![W2_A2](https://github.com/user-attachments/assets/8583b89a-9695-4924-8732-f615ca527c62)
### Activity 2
[In-class commit to MG2](https://github.com/UCI-GDIM32-W25/mg2-oop-review-hayaya22333/commit/bd5a7a369d52643f444a54364b6b7816e7edbfe0)
## W3
### Activities 0-2
Partner: Leo
### Activity 3
![W3InClass](https://github.com/user-attachments/assets/0962d7f1-6f29-47b4-b3e0-cc3104a1a54b)
## W4
### Activity 0
Partner: Leo
### Activity 1
In Awake(), the Locator class removes any extra Locator objects when there are more than one existing in the scene.
### Activity 2
![IMG_8923](https://github.com/user-attachments/assets/da49cc6d-b1f2-4d2f-a720-f4157fa208dc)
### Activity 3
[In-class commit to MG4](https://github.com/hayaya22333/HW4/commit/90e4bedf81fa90b58ea86d9824efb1fa5903b7a1)

I created all the objects for the scene and created respective script files for each of them.
## W5
### Activity 1
I think the design of the interface and abstract class is really smart. The abstract class Item includes the abstract method Use() to tell programmers that all items should have a function that triggers something when the item is used. The IBreakable interface adds to the Item class when inheriting, and only for items that inherits from it will be able to lower their durability and be broken. If anything, the _durability variable might be clearer if it's defined in the interface instead of the child classes.
### Activity 2
PlayerW5Demo2 is the controller, DialogueBubble, EnemyW5Demo2, and InventoryUI are the view, and EnemyStats and ItemW5Demo2 are the Model. 
### Activity 3
#### scenario 1
The different beats would use inheritance with polymorphism, where they inherit from beat parent class and deviate into different types of beats. Different types of beats would have prefabs to keep their sprite. Scriptable objects would keep the timing of beats for different songs.
#### scenario 2
Model keeps track of the location of players, obstacles, shot line, and skills data. Controller executes damage. View is the UI showing attack, skills, etc.
#### scenario 3
Inheritance with polymorphism applies to when different types of crops inherit similar traits and status from a parent prop class. State machine might not apply, since crop states won't move backwards.
### Activity 4
Attendance: Han Yang, Leo Abe, Jing Chen

[Final Project Core Concept Link](https://docs.google.com/document/d/13jJEC-fdvdxtT06lxVfHc2n7kMfb3ouPPp6kTowmMfg/edit?tab=t.0#heading=h.y4j3q551ojs1)
## W6
### Activity 1
- Use simple colliders (circles are most efficient), avoid polygon colliders.
- Avoid puting unnecessary programs in Update() when they don't need to be checked every frame.
- Only use RigidBody when necessary, don't add on unmovable objects.
- Avoid iterating lists and arrays too frequently.
- Performance profiling shows a histogram of time consumed each fram for different functionalities. Find the usage spikes and work around what's consuming to much resources. Selecting a frame will show hierarchy and list all methods along with their resource consumption.
- Gizmos can show vector of rigidbody movement, for our project it can indicate where the player is moving and help fix irregular physics that happened on interactable objects in the scene if we apply any RigidBody to them.
- Breakpoints can be inserted in codes to only run codes up to a point and check for where bugs occur.
### Activity 2
Attendance: Han Yang, Leo Abe, Jing Chen

[Final Project Core Concept Link](https://docs.google.com/document/d/13jJEC-fdvdxtT06lxVfHc2n7kMfb3ouPPp6kTowmMfg/edit?tab=t.0#heading=h.y4j3q551ojs1)
## W7
### Activity 1
- Use finite state machine to switch status/behavior of NPC
- Use Gizmos to show raycast of sight, for our project check if the player's crosshair can reach interactable items: Gizmos.DrawRay(transform.position, direction). Raycasts return a boolean.
- Check tag: "gameObject.tag.Equals(_playerTag)"
- SphereCast checks for colliders that escaped the raycast, useful for NPC logic.
### Activity 2
Jing Chen, Han Yang, Leo Ave
### Activity 3
![IMAGE](https://github.com/user-attachments/assets/5c667878-cc5f-4a8d-a09b-b1a15cf2d6b1)
### Activity 4
[Task manager link](https://trello.com/invite/b/6995204f10128a75a7a1bc20/ATTI644d9b17f0193b959eec057e6ce3f61f73B9245B/froggiest-frog)
### Activity 5
[Commit Log](https://github.com/lindenreid/GDIM32-Final/commit/cfd9f542b2c99611cfafbdcb73dc703040b8a84f)

I made a scene for testing our project and reuploaded 3D mesh for environment objects. 
## W8
### Activity 1
Post-processing:
- Camera effects
- Adds render effect after drawing objects
- Bloom, brightness, colors, screen deform...
### Activity 2
Attendance: Han Yang, Leo Abe, Jing Chen
### Activity 3
Use keybinds for interacting with stuff. Lock cursor to the center of the screen. Disable player movement while dialogue exchange is happening. Add in-dialogue and out-of-dialogue states to control player behavior while dialogue is and isn't happening.
### Activity 4
I'll finish the audio system when interacting with items. I used interface for item interaction, today I'll switch to using locators.
### Activity 5
[Recent commit link](https://github.com/hayaya22333/GDIM32-Final/commit/3756a30f428bf4b16881a6f54e340b2ca484ec72)
I fixed the audio system and used locators. There's issues with using event to collect objects to fix later.
## W9
### Activity 1
- Code dialogue to scale well, and can accept increasing number of branches without touching the script.
- Connect dialogue to NPC state.
- Change dialogue based on latest player action.
### Activity 2
Attendance: Han Yang, Leo Abe, Jing Chen
### Activity 3
Navigating the UI is difficult. Inventory UI is confusing because it is not clear which box is selected. The environment could use less plants so that the sun shines through. Instantiate the objects at an offset when dropping items. Use the same key for interacting and progressing dialogue for NPC.
### Activity 4
We're up to date with our project plan, and even a bit ahead in item and environment category. The UI and pause system still needs work, but in general we're more than 50% done.
### Activity 5
I updated the game UI for quest display.
[Git commit link](https://github.com/hayaya22333/GDIM32-Final/commit/1b9266757421d862997680b5d208b48c20454322)
## W10
### Activity 1
Attendance: Han Yang, Leo Abe, Jing Chen
### Activity 2
Add player dialogue options and corresponding NPC responses. Fix the Frogman NPC shooter because its aiming is bugged. Have the Frogman NPC move around or start in an idle animation instead of walk.
### Activity 3
We're done with all the mechanical aspects of the project. We need to add more objects using the same scripts and update sprites for UI.
### Activity 4
[Commit link](https://github.com/hayaya22333/GDIM32-Final/commit/e919995893801db700c09f88b9b19d1ab45fe16e)
I updated terrain texture and added a stray walking script to our npc, so he walks at given target points.
