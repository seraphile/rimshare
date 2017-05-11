# Custom World Map Icons
These images are for customized world map icons for your mod-made factions.

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/customiconexample.png?raw=true)
###### *Example: [Apini playable race mod](https://ludeon.com/forums/index.php?topic=31076.0)*

## Credits
Author: Sera

Pre-made Icons: [Rimshare](https://github.com/seraphile/rimshare/tree/master/custom%20world%20map%20icons) Edited by *Sera*

Icons Source: [game-icons.net](game-icons.net)



## How to use
Put the icons in your `Textures` folder for your mod

In the factions def,find these fields:
```xml
<homeIconPath></homeIconPath>
<expandingIconTexture></expandingIconTexture>
```
`<expandingIconTexture>` is the texture which shows normally on the world map, and `<homeIconPath>` is the texture that appears when you zoom into the map.

If your icon texture is named `colony.png` and is in the `icon` folder in your Textures folder, the filled in field would look like this:
```xml
<expandingIconTexture>icon/colony</expandingIconTexture>
```
If you want your texture to be coloured in specific colours utilize this field
```xml
   <colorSpectrum>
      <li>(R,G,B)</li>
      <li>(R,G,B)</li>
      <li>(R,G,B)</li>
    </colorSpectrum>
```
With R,G,B being the Red, Green and Blue colour values (a number which ranges from 0-255).

If you want to find out the RGB values of a certain colour, use this [W3Schools color picker](https://www.w3schools.com/colors/colors_picker.asp).


For example if want my factions to be [Chartreuse RGB(127,255,0)](https://www.w3schools.com/colors/color_tryit.asp?color=Chartreuse) and [Coral RGB(255,127,80)](https://www.w3schools.com/colors/color_tryit.asp?color=Coral), the xml would look like this
```xml
   <colorSpectrum>
      <li>(127,255,0)</li>
      <li>(255,127,80)</li>
    </colorSpectrum>
```
## Pre-made icons `![alt text]()`


![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/acid-tube.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/acid-blob.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/acid.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/aerodynamic-harpoon.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/alien-skull.png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/american-shield%20(1).png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/american-shield.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/anarchy.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/animal-hide.png?raw=true)![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/ankh.png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/anubis.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/architect-mask.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/armoured-shell.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/artificial-intelligence.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/at-sea.png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/atom.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/atomic-slashes.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/automatic-sas.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/backbone-shell.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/ball-glow%20(1).png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/ball-glow.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/barbed-coil.png?raw=true)![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/barbed-star.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/barbed-sun.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/barbed-wire.png?raw=true)

![alt text]() ![alt text]() ![alt text]() ![alt text]() ![alt text]()

![alt text]() ![alt text]() ![alt text]() ![alt text]() ![alt text]()

![alt text]() ![alt text]() ![alt text]() ![alt text]() ![alt text]()

![alt text]() ![alt text]() ![alt text]() ![alt text]() ![alt text]()

![alt text]() ![alt text]() ![alt text]() ![alt text]() ![alt text]()

![alt text]() ![alt text]() ![alt text]() ![alt text]() ![alt text]()

![alt text]() ![alt text]() ![alt text]() ![alt text]() ![alt text]()

![alt text]() ![alt text]() ![alt text]() ![alt text]() ![alt text]()
