#Battle#

<sup>[Description](#description) | [Pseudo-code](#pseudo-code)</sup>

###Description###

In a battle, two players engage with their units in combat. The two players will take turns in making moves in order to defeat the opponent by killing all its units. Each player engages with a maximum of three units:

| Player 1  | Player 2  |
|:---------:|:---------:|
| Unit 1    | Unit 1    |
| Unit 2    | Unit 2    |
| Unit 3    | Unit 3    |

The attacker wil commence the battle, and starts by ordering his first unit to perform a *BattleAction*. Each unit has its own set of *BattleAbilities*, so the player will have to choose both an ability and targets for the ability in order to create the BattleAction.

For each unit, the player must:

1. Choose an ability
2. Pick targets to affect

When the player has ordered each of its units, all the BattleActions are executed. If this does not finish the battle (kill the remaining opponents' units), the turn will be passed to the opponent.

###Pseudo-code###

_NOTE:_ Before attempting to read the pseudo-code, you should study the other classes: [BattleAbility](ability/), [BattleAction](action/), [Player](/player) and [Unit](/unit).

  ```java
  list players
  map (player, list of units)
  list battleActions
  int currentPlayer, currentUnit, currentStep
  
  //TODO: Create constructor: public Battle()
  //Input: The attacker and its units along with the defender and its units
  //Does: Initializes all fields
  
  //TODO: Create function: void executeActions()
  //Does: Loops through battleActions and executes them all. Implement randomability of magnitude based on units attributes and playerbonuses
  
  //TODO: Create function: void KeyReleased()
  //Does: Checks if the key released should have effect, and execute if possible according to currentPlayer, currentUnit and currentStep
  //Note: If this function changes the step of combat, you should run outputString() defined belwo
  
  //TODO: Create function: string outputString()
  //Does: In according to the current step of combat, create an outputString relevant for the situation of the player.
  
  //TODO: Create helper methods to simplify code.
  ```
