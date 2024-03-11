# SDEV_ProgramLanguage
Easier program language made by me!


1. /Create ()

 This command creates a new object or entity. The parentheses might specify the type of object (e.g., circle, square, sprite, file, text, etc...).

2. /Select ()

 Selects an existing object or element. The parentheses could contain an identifier (e.g., object name, ID).

3. /Move 0,0

 Moves the selected object to the specified position (Y X).

4. /Delete ()

 Removes the selected object from the scene or canvas.

5. /Position 0,0

 Sets the position of an object to the specified coordinates (Y X).

6. /Collides ()

 Checks if the selected object collides with other objects. The parentheses contain the object that collided.

7. /Transparency:

 Adjusts the transparency or opacity of an object. The colon suggests additional parameters (e.g., percentage).

8. /Brightness:

 Controls the brightness of an object. Similar to transparency, additional parameters may follow.

9. /Color 0,0,0

 Sets the color of an object. The colon likely indicates color values (RGB).

10. /Effect [Off]

 Enables or disables visual effects for an object. The square brackets suggest toggling the effect on or off.

11. /Clicked () 

Detects if the object is clicked or interacted with. Parentheses may contain event handlers.

12. /Animation [Off] 

Turns animation on or off for the selected object. (Play/Stop)

13. /Size: 

Adjusts the size or dimensions of an object. Additional parameters would specify the new size.

14. /Gravity: 

Controls world gravity

15. /Physics [Off] 

Enables or disables physics simulation for the object.

16. /Value: 

Sets a number or something on the object value or global value etc...

17. /Open {}

 Opens websites/links/etc...

18. /Change level {}

 Indicates a level change (e.g., in a game). The curly braces likely specify the new level.

19. /Fix cam 0,0: 

Adjusts the camera position to the specified coordinates (Y X).

20. /Play sound {}

 Plays a sound effect. The curly braces would contain the sound file or identifier.

21. /Stop sound {}

 Stops a currently playing sound. The curly braces specify which sound to stop.

22. /Text ""

 Displays text associated with an object. The empty quotes await the actual text content.

23. /Angle: 

Sets the rotation angle for an object. Additional parameters would define the angle.

24. /Stop script {}

 Halts the execution of a specific script or behavior.

25. /Repeat:

 Initiates a loop or repetition. Parameters would determine the number of repeats.

26. /Load file {}

 Loads data from your storage. The curly braces indicate what file you wanna load (It can load files from websites too if you use /Open {Whatever site.yey.png} + Load file {Whatver site.yey.png})

27. /Search:

 Initiates a search operation (e.g., searching for something on the game/app/text etc...).

28. /Save {}

 Saves data





Example: /Create (Cube). /Create (Triangle). /Select (Cube) + /Position -100,0. /Select (Triangle) + /Position 100,0. /Select (Cube) + /Collides (Triangle) = /Delete (Cube)
