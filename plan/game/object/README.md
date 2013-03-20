#GameObject#

###Description###

The GameObject superclass creates a fundament for all subclasses. Alas, since the different types of objects vary very much, this class cannot provide all too many functions/variables.

When objects are drawn, we want some objects to be drawn above others, and thus we have created a new dimension for all the objects, called Z. If one object has a higher posZ than another, the first one will be drawn on top of the other. This also applies when we click a Tile, usually when we click a Tile we expect to do an action based on the topmost object.

Here's a full list of objects and their respective ID's and positions in z-direction <sub>Jump to [pseudo-code](#pseudo-code)</sub>

| Object            | ID    | posZ  |
|-------------------|:-----:|:-----:|
| Sand              | 1     | 1 - 5 |
| Grass             | 2     | 1 - 5 |
| Dirt              | 3     | 1 - 5 |
| Snow              | 4     | 1 - 5 |
| Water             | 5     | 1 - 5 |
| Mountain          | 6     | 6 - 7 |
| Tree              | 7     | 6 - 7 |
| Chest             | 8     | 6 - 7 |
| Gold              | 9     | 6 - 7 |
| Wood              | 10    | 6 - 7 |
| Stone             | 11    | 6 - 7 |
| Meat              | 12    | 6 - 7 |
| Vandir            | 13    | 6 - 7 |
| Torhir            | 14    | 6 - 7 |
| Koron             | 15    | 6 - 7 |
| Fahradohm         | 16    | 6 - 7 |
| Terenas           | 17    | 6 - 7 |
| Zariena           | 18    | 6 - 7 |
| Digitus           | 19    | 6 - 7 |

###Pseudo-code###

  ```Java
  int ID, posX, posY, posZ, width, height
  ```
