 #cs200 #compsci

## Alec Malcangio, CSCI200C - Asteroids

- **PROBLEM DESCRIPTION:** The goal is to essentially remake the Atari game Asteroids. I have vivid memories of being a young'un and playing my dad's old copy, so, for those unfamiliar, you control a little ship that flys around and shoots asteroids. I want to have (at least) three different sizes of asteroids, preferably with images that I load in through SFML. The file in/out is going to be a local high score tracker, like classic arcade things - enter a three letter identifier and it goes on the board, display the top ten scores at the end of the game, all that kinda vibe.
- **DATA DESCRIPTION:** The data for your program consists of three requirements:
    - The UML class diagrams for the classes you will be creating for your program. _Be sure to include comments to describe what your data members and member functions will do._ This section is NOT in paragraph form; instead, this section is pseudocode made up of the UML class diagrams. This section does NOT include actual C++ code, it is only the UML diagram pseudocode.

| Asteroid                                                       |     |
| -------------------------------------------------------------- | --- |
| int xCoord<br>int yCoord<br>int Size<br>SFML something texture |     |
| drift()<br>getShot()<br>contact()                              |     |


- Going to have a big old vector of all the asteroids, which I'll loop over to determine "Hey, have I hit something?"
- Just going pretty simple here, going to store a list of high scores with three letter identifiers, so each one is probably going to be a little baby array with an int and a string in each (or an array of strings and just read the string as an int)
- **PROCEDURAL DESCRIPTION:** Include a bullet list description in pseudocode of how your main program will operate. This section should also NOT be in paragraph form. If you plan to use SFML, be sure to mention that here. This section does NOT include actual C++ code, it is only pseudocode of the flow and steps within your program as it runs.
- **SPECIAL NEEDS/CONCERNS:** Your Project Proposal should mention any special needs or concerns that the instructor should know about.
    - Will you need extra help on a particularly difficult idea that you will have to conquer in order to make this project work? If you're addressing a domain specific problem, you may need to get advice from someone within that department.
    - Will you need to make use of any third party libraries? If yes, what is the library and what task is it accomplishing? Why is the library necessary?

The document you submit will specifically answer the following questions:

1. What class will you create? What data members and member functions will it have?
2. What data structure (array, linked-list, stack, queue) will you use within your project? How will it be used?
3. Where and how will a data file be used?


