 #cs200 #compsci

## Alec Malcangio, CSCI200C - Asteroids

- **PROBLEM DESCRIPTION:** The goal is to essentially remake the Atari game Asteroids. I have vivid memories of being a young'un and playing my dad's old copy, so, for those unfamiliar, you control a little ship that flys around and shoots asteroids. I want to have (at least) three different sizes of asteroids, preferably with images that I load in through SFML. The file in/out is going to be a local high score tracker, like classic arcade things - enter a three letter identifier and it goes on the board, display the top ten scores at the end of the game, all that kinda vibe.
- **DATA DESCRIPTION:** The data for your program consists of three requirements:
    - The UML class diagrams for the classes you will be creating for your program. _Be sure to include comments to describe what your data members and member functions will do._ This section is NOT in paragraph form; instead, this section is pseudocode made up of the UML class diagrams. This section does NOT include actual C++ code, it is only the UML diagram pseudocode.

| Thing                                              |     |
| -------------------------------------------------- | --- |
| int xCoord<br>int yCoord<br>SFML something texture |     |
| contact()                                          |     |

| Asteroid (child of Thing)                                      |     |
| -------------------------------------------------------------- | --- |
| int xCoord<br>int yCoord<br>int Size<br>SFML something texture |     |
| contact()                                                      |     |

| Ship (child of Thing)                                          |     |
| -------------------------------------------------------------- | --- |
| int xCoord<br>int yCoord<br>int Size<br>SFML something texture |     |
| move()<br>shoot()<br>contact()                                 |     |


- Going to have a big old vector of all the objects in the game, which I'll loop over to determine "Hey, have I hit something?"
- Just going pretty simple here, going to store a list of high scores with three letter identifiers, so each one is probably going to be a little baby array with an int and a string in each (or an array of strings and just read the string as an int)
- **PROCEDURAL DESCRIPTION:** I
	- Going to generate the basic game, initialize all the objects, get asteroids a-floating around and then hand control to the player to start shooting asteroids, scoring points, and continue on until maybe a certain end point or if they smack into an asteroid and explode in death.
- **SPECIAL NEEDS/CONCERNS:** 
    - Haven't used SFML, planning on using inheritance, nothing too crazy here.




