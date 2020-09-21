# Alice 3

## Getting started with Alice
Initial Scene: Starting point of the animation.
It has three components:

1. Background template
2. Non-moving scenery objects (setting)
3. Moving objects (action)

Two different workspace editors (a.k.a. perspectives):

* Scene editor. Allows us to add, position and edit objects.
* Code editor. Allows us to add programming statements.
Run the animation after the programming statements are added to the code editor.

### Scene Editor Display
* Scene setup at top.
* Gallery at the bottom.

The gallery is a collection of 3D objects. They are divided in classes that contain sub-classes:

- i.e. Alice is a sub-class of the Biped class.

### Code Editor
The procedures tab is located within the Methods Panel.
A procedure is a piece of program code that defines how the object should execute a task. The instance menu is above the Procedures tab, you can also just click the instance on the scene.

To create a programming instruction just drag the desired instruction into the myFirstMethod tab of the Code editor. Use the cascading menus to select values for each argument in the selected method.

## Add and Position Objects
2 ways to position an object:

1. Precise positioning.
    - One-shot procedure
    - Enter values for x, y, z
2. Imprecise positioning using the drag-and-drop method.

## Procedures and Arguments
Click on edit code to display the code editor.
The methods panel contains two tabs:

* Procedures.
* Functions.

Control statements are located at the bottom of the myFirstMethod tab.
Remember that object movement is egocentric.

You can enable or disable a programming statement by using right-click on the statement and selecting _Is Enabled_.

## Rotation and Randomization
Use storyboards to guide your animations and be able to evaluate your results.
To rotate an object select the instance of the object, drag a turn or roll procedure to the code editor and set the arguments (1.0 = one full turn/roll)

Control Statements define how programming statements are executed in a program. The default is Do in order. Other examples are: Do together, Count and While.

Random numbers are generated within a range. They can be used to improve the movement of animals or to create games that require unpredictable behaviour. 

## Declare Procedures
Class Inheritance refers to the ability objects to inherit characteristics of their class (such as class methods). Simplify the code by identifying repetitive behaviour.

Class Hierarchy is located to the left of myFirstMethod tab and allows the user to see the list of classes and subclasses in the animaiton. Select a class or subclass to view the procedures, functions and properties defined for the selected class.

If you wish to declare a procedure:

* From the class hierarchy, select the class that should inherit the procedure.
* Click Add Procedure
* Specify the name of the procedure.
* Write the code for the procedure.
* Add the procedure to myFirstMethod to test the animation.

_this_ object identifier is used to indicate the instance calling the procedure.

## Control Statements
setVehicle Procedure: when the "vehicle" object is programmed to move, the "rider" object will automatically move with it. To diasable, drag another setVehicle procedure where the rider should get off the vehicle, set vehicle to _this_, which sets the vehicle of the rider back to the scene.

## Functions
We use functions to:

* Ask questions about properties of an object.
* Compute a value.
* Return a value of a particular type.

Functions such as _getDistanceTo_ allows us to find the distance from object A to B. Furthermore, functions can be used with math operators to improve the obtained results.

## If and While
Control structures are pre-defined statements that determine the order in which programming instructions are executed.

You know what an if and while are.

Process flow is a graphical representation of a process model. It uses chapes to represent the actions in the model.

## Expressions
Combination of values that result in a final value. Typically used to solve timing and distance problems.

Math operators are available in cascading menus when selecting:

* Amount and duration
* getDistance functions

## Variables
A variable is a place in memory where data of a specific type can be stored for later retrieval and use by your program. Each variable is given a unique name to make easy to find and reference. Once a variable is declared it can be used to store and retrieve data.

Variable data types:

- Decimal number
- Whole number
- Boolean
- Classes
- TextString
- Other. Sounds, colors, shapes, other special values

Drag _variable_ from the code editor to initialize it.

Preferences -> Java Code allows us to see the actual code!

Cant change the Java code though...

## Keyboard Controls
Event Handling. Interactivity into animations. Event listeners are created to look for and respond to user input events.

An event is any action initiated by the user, designed to influence the program's execution during play.

Keyboard controls allow the uset to control one or more objects while the animation is running.

Event Listeners. They're procedures in the scene class that listen for input while the animation is running. Types of EL:

* Scene Activation/Time
* Keyboard
* Mouse
* Position/Orientation

To access event listeners:

    Code editor -> Scene tab -> down arrow -> edit -> opens the init event listeners tab

In the init event list tab we can add an event listener. In sceneActivated we can create animation that plays before myFirstMethod. This could be an opening sequence.

Saving a class allows you to save time by using already tested code.

    Select the code -> Save to Class File
    (Save in MyClasses folder for easy access)

## Develop a complete animation

Funtional decomposition is a methodical process of identifying a complex problem and breaking it down into smaller steps that are easier to manage.

Animation development process:

1. Define the scenario
2. Design a storyboard
3. Program the animation
4. Run the animation



_Info obtained from the Java Fundamentals Learner Course by Oracle_
