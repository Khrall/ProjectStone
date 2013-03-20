#GameObject#

###Description###

The GameObject superclass creates a fundament for all subclasses. Alas, since the different types of objects vary very much, this class cannot provide all too many functions/variables.

When objects are drawn, we want some objects to be drawn above others, and thus we have created a new dimension for all the objects, called Z. If one object has a higher posZ than another, the first one will be drawn on top of the other. This also applies when we click a Tile, usually when we click a Tile we expect to do an action based on the topmost object.



###Pseudo-code###

  ```Java
  int posX, posY, posZ, width, height
  ```
