#Plan#
This document holds the steps towards completion of Project Stone. It is not very detailed, but provides useful information on our progression along with links to description and pseudo-code relevant to the different sections of the project.


###Table of Contents###

- [Data](#data)
- [Map development](#map-development) [0%]
    - [Tile](#tile) [0%]
    - [GameObject](#gameobject) [0%]
        - [InanimateObject](#inanimateobject) [0%]
        - [InteractiveObject](#interactiveobject) [0%]
        - [UnitObject](#unitobject) [0%]
- [Battle development](#battle-development) [0%]    

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

##Battle development##

The battle feature is quite essential for the game to be interesting at all. It implements features for creating a turn-based combat system between two players, each player controlling up to three units.

<sup>Battle: [folder](battle/) | [description](battle/#description) | [pseudo-code](battle/#pseudo-code)</sup>

###BattleAbility

Battle abilities are pretty much abilities used in battle. They can be harmful or beneficial in various ways, and have different ranges targets and magnitudes.

<sup>Battle: [folder](battle/ability) | [description](battle/ability#description) | [pseudo-code](battle/ability#pseudo-code)</sup>

###BattleAction###

Battle actions are simply a way to store information about what's going to happen when the player has ordered his units.

<sup>Battle: [folder](battle/action) | [description](battle/action#description) | [pseudo-code](battle/action#pseudo-code)</sup>
