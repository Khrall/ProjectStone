#BattleAbility#

<sup>[Description](#description) | [Pseudo-code](#pseudo-code)</sup>

###Description###

The BattleAbility class holds the name of an ability, its "class" which classifies its nature, its magnitude, and the range of targets the ability may be used on.

| abilityClass    | classification  | effect                    |
|:---------------:|:---------------:|:-------------------------:|
| 0               | Attack          | Deals damage              |
| 1               | Heal            | Restores health points    |
| 2               | Empower         | Increases attack          |
| 3               | Reduce          | Reduces attack            |
| 4               | Strengthen      | Increases defense         |
| 5               | Weaken          | Reduce defence            |

<sup>You are free to add ability classifications at any time, Olav</sup>

| targetRange     | target    |
|:---------------:|:---------:|
| 0               | Self      |
| 1               | Enemy     |
| 2               | Friendly  |
| 3               | Hostile   |

<sup>Note that friendly and hostile refers to up to a multiple of units</sup>

###Pseudo-code###

  ```java
  int abilityClass, magnitude, targetRange
  string name
  
  //TODO: Create constructor, simply assigns attributes, available abilities and name
  ```
