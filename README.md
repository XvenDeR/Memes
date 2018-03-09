# You need to modify this or you will be banned by BattleEye

![Boat](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/boat.png?raw=true)
![Buggy](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/buggy.png?raw=true)
![Enemy](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/arrow.png?raw=true)
![Player](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/player.png?raw=true)
![Nade](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/grenade.png?raw=true)
![Jetski](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/jetski.png?raw=true)
![Parachute](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/parachute.png?raw=true)

![Memes](https://github.com/NoParamedic/Memes/blob/master/src/main/resources/images/item-sprites.png?raw=true)


# Changes
* Get self player's location by parsing `CharMoveComp` RPC. So the player's direction is corrected now. 
* Get item's relative locaiton by `DroppedItemInteractionComponent`. So the item location is corrected now.
* Change `readRotator()` to `readRotationShort()` fixes empty player state.
* `DroppedItem` is shown.
* Fully parse `ATslCharacter`. So player health is shown.
* Correct player color when driving.
* `Equipped weapons` are shown.
* Clear `DroppedItem` and `DroppedItemGroup` when `picking up`.
