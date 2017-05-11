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
Fill in these fields with the file path for your icons.

For example, if your icon texture is named `colony.png` and is in the `icon` folder in your Textures folder, the filled in field would look like this:
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
