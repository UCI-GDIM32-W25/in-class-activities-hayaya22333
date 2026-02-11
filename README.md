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
## W5
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
