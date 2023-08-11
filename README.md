# TP: ALBWStyleMeter
A "The Legend of Zelda: Twilight Princess" mod that modifies the mechanics of several items to utilize a meter similarly to how they do/could in "A Link Between Worlds", a 3DS Zelda game.

## Modified items:

* Lantern: consumes meter faster.
* Slingshot: each shot consumes 1/4 off the meter.
* Bow: each shot consumes 1/4 off the meter.
* Normal and Water Bombs: consumes 1/3 off the meter.
* Bomblings: can not be used at all. (The code is not decompiled enough to integrate properly with the meter afaik.)
* Bomb Arrows: each shot consumes 7/12 off the meter.
* Magic Armor: Consumes meter when worn. Still lose rupees when hit. (The code for rupee loss when hit may not be fully decompiled atm.)
* Spinner: consumes meter when on rails and when attacking/jumping.
* Dominion Rod: consumes meter when swung, when controlling object, and when attacking with controlled object.

## Extra features:

* Toggle bewtween Kokiri, Zora, and Magic armor by pressing Dpad-down. (Must unlock armor to toggle.)
   * Kokiri/Armor->Zora Armor: press Dpad-down once.
   * Kokiri/Zora->Armor: press Dpad-down twice.
   * Zora->Kokiri: press Dpad-down once.
   * Armor->Kokiri: press Dpad-down twice.

## Known Major Issues:

* Need to acquire Lantern for meter to work for the mod. Because of this, I added a chest on Ordon Spring that has the lantern in it. Make sure to go and get it after starting the game.
* Glitch when using clawshot (on ceilings, not sure about walls) that makes Link respawn at last spawn point.
* Disable all cheat codes (like hyrule field speed hack) since can interfere with modified code and crash the game.

## Clips:
### Lantern
| Twilight Princess                            | A Link Between Worlds                            |
| ----------------------------------- | ----------------------------------- |
| ![](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/LanternTP.gif) | ![image](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/LampALBW.gif) |
### Bow
| Twilight Princess                            | A Link Between Worlds                            |
| ----------------------------------- | ----------------------------------- |
| ![](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/BowTP.gif) | ![image](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/BowALBW.gif) |
### Bombs
| Twilight Princess                            | A Link Between Worlds                            |
| ----------------------------------- | ----------------------------------- |
| ![](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/BombsTP.gif) | ![image](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/BombsALBW.gif) |
### More
| Slingshot                            | Armor                            |
| ----------------------------------- | ----------------------------------- |
| ![](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/Slingshot.gif) | ![image](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/Armor.gif) |
| Spinner                            | Dominion Rod                            |
| ----------------------------------- | ----------------------------------- |
| ![](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/Spinner.gif) | ![image](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/DominionRod.gif) |

### Clothes Quick-toggle
| Kokiri->Zora                            | Kokiri->Armor                            |
| ----------------------------------- | ----------------------------------- |
| ![](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/KokiritoZora.gif) | ![image](https://github.com/Captainkittyca2/TP_ALBWStyleMeter/blob/main/GIFs/KokiriToArmor.gif) |
