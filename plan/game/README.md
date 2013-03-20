#Game#

###Description###

The Game class should have two cases, as should all its children classes, one for the host and one for the client. On the host-side, the Game class will take input and do operations/actions on the different Game elements. On the client-side, it should be responsible for holding information about the map, the objects and basically everything, so that we can draw it to screen by using the ChaosEngine. Some operations will be done on the client-side as well, for example, we need to filter out user input that may be illegal both in the client-side AND the host-side Game classes, and we also need to handle clicks on the user interface, which does not exist on the host-side.

The different classes that lie "under" the Game class are as follows:

| Class                     | Links                                                                             |
|---------------------------|-----------------------------------------------------------------------------------|
| Tile                      | [Description](tile/#description), [Pseudo-Code](tile/#pseudo-code)                |
| GameObject                | [Description](gameobject/#description), [Pseudo-Code](gameobject/#pseudo-code)    |
| Player                    | [Description](player/#description), [Pseudo-Code](player/#pseudo-code)            |
| Battle                    | [Description](battle/#description), [Pseudo-Code](battle/#pseudo-code)            |

###Pseudo-code###

  ```Java
  //TODO: Get this class going
  ```
