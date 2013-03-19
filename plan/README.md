#Plan#
This document holds the steps towards completion of Project Stone. It is not very detailed, but provides useful information on our progression along with links to description and pseudo-code relevant to the different sections of the project.


###Table of Contents###

1. [Data](#data)
2. [Map development](#map-development) [0%]
    1. [Tile](#tile) [0%]
    2. [GameObject](#gameobject) [0%]
        1. [InanimateObject](#inanimateobject) [0%]
        2. [InteractiveObject](#interactiveobject) [0%]
        3. [UnitObject](#unitobject) [0%]
3.     

##Data##

| Progression           | 0%            |
| --------------------- |:-------------:|
| Kickoff               | 24th of March |
| Deadline              | 24th of April |
| Lines of code         | 0             |

##Map development##

The map development step consists of creating the tile- and object classes, and putting them together with reasonable functions providing usability for the Game class.

*An own folder will be created for the Game class* 

###Tile###

The Tile class holds its own position along with objects, and should provide usability both for a map editor, aswell as the game itself. Such functions include targeting features, and navigability queries.

*An own folder will be created for the Tile class*

###GameObject###

The GameObject class is an interface for all the game objects available in the game.

*An own folder will be created for the GameObject interface*

####InanimateObject####

*An own folder will be created for the InanimateObject class*

####InteractiveObject####

*An own folder will be created for the InteractiveObject class*

####UnitObject###

*An own folder will be created for the UnitObject class*
