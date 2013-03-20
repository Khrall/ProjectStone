#InanimateObject#

###Description###

The InanimateObject class covers objects like texture and terrain, objects that we will never interact with, and that are static. They mostly just contain information on what type of object it is, and whether it changes the navigability in a Tile.

Inanimate objects come in different "states", which identify how the inanimate object should be drawn to the canvas:

| Type        | Integer | States describe           |
|-------------|:-------:|---------------------------|
| Grass       | 0       | Rotation/shape            |
| Dirt        | 1       | Rotation/shape            |
| Waater      | 2       | Rotation/shape            |
| Snow        | 3       | Rotation/shape            |
| Sand        | 4       | Rotation/shape            |
| Mountain    | 5       | Vegetation (snowy, etc..) |
| Tree        | 6       | Vegetation (snowy, etc..) |

###Pseudo-code###

  ```Java
  int type, state;
  ```
