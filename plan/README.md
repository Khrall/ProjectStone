#Plan#
This document holds the steps towards completion of Project Stone. It is not very detailed, but provides useful information on our progression along with links to description and pseudo-code relevant to the different sections of the project.


###Table of Contents###

- [Data](#data)
- [Art development](#art-development) [0%]
    - [Inanimate object sprites](#inanimate-object-sprites) [0%]
    - [Interactive object sprites](#interactive-object-sprites) [0%]
    - [Unit object sprites](#unit-object-sprites) [0%]
    - [GUI sprites](#gui-sprites) [0%]
- [Game development](#game-development) [0%]
    - [Tile](#tile) [0%]
    - [GameObject](#gameobject) [0%]
        - [InanimateObject](#inanimateobject) [0%]
        - [InteractiveObject](#interactiveobject) [0%]
        - [UnitObject](#unitobject) [0%]
    - [Player](#player) [0%]
    - [Battle development](#battle-development) [0%]
        - [BattleAbility](#battleability) [0%]
        - [BattleAction](#battleaction) [0%]
    - [City](#city) [0%]
- [Client/Host development](#clienthost-development) [0%]
    - [GameClient](#gameclient) [0%]
    - [GameHost](#gamehost) [0%]
- [ChaosEngine](#chaosengine) [0%]
- [GUI](#gui) [0%]


##Data##

| Progression           | 0%            |
| --------------------- |:-------------:|
| Kickoff               | 24th of March |
| Deadline              | 24th of April |
| Lines of code         | 0             |

##Art development##

A lot of energy is put in the artwork of the game. There can be no true rpg without beautiful surroundings and interesting character designs, but of course the GUI matters a lot as well.

###Inanimate object sprites###

Sprites for objects that are not interacted with, such as texture and terrain.

###Interactive object sprites###

Sprites for objects ready for interaction, such as resources.

###Unit object sprites###

Sprites for the various units found throughout the game.

###GUI sprites###

Sprites for all the different GUI-elements implemented in the game.

##Game development##

The game development step consists of creating the tile- and object classes, and putting them together with reasonable functions providing usability for the Game class. Of course, the Game class should also be able to handle a lot of types of interaction, both in-game and through the graphical user interface.

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

###Player###

The Player class holds information on the player in terms of how much resources the player has, which units it controls, and which city it owns.

###Battle development###

The battle feature is quite essential for the game to be interesting at all. It implements features for creating a turn-based combat system between two players, each player controlling up to three units.

<sup>Battle: [folder](battle/) | [description](battle/#description) | [pseudo-code](battle/#pseudo-code)</sup>

####BattleAbility####

Battle abilities are pretty much abilities used in battle. They can be harmful or beneficial in various ways, and have different ranges targets and magnitudes.

<sup>BattleAbility: [folder](battle/ability) | [description](battle/ability#description) | [pseudo-code](battle/ability#pseudo-code)</sup>

####BattleAction####

Battle actions are simply a way to store information about what's going to happen when the player has ordered his units.

<sup>BattleAction: [folder](battle/action) | [description](battle/action#description) | [pseudo-code](battle/action#pseudo-code)</sup>

###City###

The City class should describe the city, both by having "health points", having states for whether it is under siege or not, and of course having buildings and the means to upgrade them.

##Client/Host development##

The development of clients and hosts should be postponed for as long as possible, but we need to keep in mind that all data that is to be communicated should be easily serialized. In this class we simply create a way to communicate between the GameClient and GameHost classes.

###GameClient###

The GameClient handles the game in terms of converting input into action requests, sent to the GameHost.

###GameHost###

The GameHost handles input from different GameClients and turn them into actions in the Game, updating the clients on the effects of each input.

##ChaosEngine##

The engine of the game, created by Chaos Entertainment, is a class that paints all objects to a canvas. Most of its tasks are very generic, but some are also complex, depending on what kind of object we're painting.

##GUI##

The graphical user interface is very important to the game, both in terms of making the game good-looking and user-friendly, but also for making the game work at all. A lot of work will be put into it.
