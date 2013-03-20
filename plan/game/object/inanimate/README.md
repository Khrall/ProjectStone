#InanimateObject#

###Description###

The InanimateObject class covers objects like texture and terrain, objects that we will never interact with, and that are static. They mostly just contain information on what type of object it is, and whether it changes the navigability in a Tile.

Inanimate objects come in different "states", which identify how the inanimate object should be drawn to the canvas:

| Object      | ID      | States describe           |
|-------------|:-------:|---------------------------|
| Sand        | 1       | Rotation/shape            |
| Grass       | 2       | Rotation/shape            |
| Dirt        | 3       | Rotation/shape            |
| Snow        | 4       | Rotation/shape            |
| Water       | 5       | Rotation/shape            |
| Mountain    | 6       | Vegetation (snowy, etc..) |
| Tree        | 7       | Vegetation (snowy, etc..) |

###Pseudo-code###

  ```Java
  int state;
  
  //TODO: Create constructor: Assigns variables
  ```
