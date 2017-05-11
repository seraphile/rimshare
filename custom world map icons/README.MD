# Custom World Map Icons
These images are for customized world map icons for your mod-made factions.

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/customiconexample.png?raw=true)
###### *Example: [Apini playable race mod](https://ludeon.com/forums/index.php?topic=31076.0)*

## How to use

### Graphics
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
### Colours
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
## Pre-made icons


![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/acid-tube.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/acid-blob.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/acid.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/aerodynamic-harpoon.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/alien-skull.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/american-shield%20(1).png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/american-shield.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/anarchy.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/animal-hide.png?raw=true)![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/ankh.png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/anubis.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/architect-mask.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/armoured-shell.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/artificial-intelligence.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/at-sea.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/atom.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/atomic-slashes.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/automatic-sas.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/backbone-shell.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/ball-glow%20(1).png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/ball-glow.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/barbed-coil.png?raw=true)![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/barbed-star.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/barbed-sun.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/barbed-wire.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/bat-blade.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/batwing-emblem.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/behold.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/bestial-fangs.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/biohazard.png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/black-hole-bolas.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/blackball.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/bleeding-heart.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/brass-eye.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/brazil-flag.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/broken-skull.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/bubbles.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/butterfly-warning.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/caged-ball.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/carnival-mask.png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/castle.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/circle-claws.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/circular-sawblade.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/clover%20copy.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/clover.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/cog.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/compact-disc.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/compass.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/concentric-crescents.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/condylura-skull.png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/corporal.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/crab-claw.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/cracked-alien-skull.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/cracked-helm.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/cracked-mask.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/cracked-saber.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/cracked-shield.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/crags.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/crenulated-shield.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/crescent-blade.png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/croissants-pupil.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/crossed-bones.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/crown-of-thorns.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/cupidon-arrow.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/cursed-star.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/desert-skull.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/detour.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/dinosaur-bones.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/divided-spiral.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/divided-square.png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/dna1.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/doubled.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/dragon-head.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/dwennimmen.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/eagle-emblem.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/ermine.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/evil-moon.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/factory.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/fairy.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/fall-down.png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/feather.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/fishing-net.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/fishing-spoon.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/flake.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/fleshy-mass.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/fleur-de-lys.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/flowers.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/forward-sun.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/frayed-arrow.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/gas-mask.png?raw=true)

![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/gecko.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/gluttonous-smile.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/goo-skull.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/halberd-shuriken.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/half-body-crawling.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/hammer-sickle.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/heart-wings.png?raw=true) ![alt text](https://github.com/seraphile/rimshare/blob/master/custom%20world%20map%20icons/heavy-thorny-triskelion.png?raw=true)

## Credits
Author: Sera

Pre-made Icons: [Rimshare](https://github.com/seraphile/rimshare/tree/master/custom%20world%20map%20icons) Edited by *Sera*

Icons Source: [game-icons.net](game-icons.net)
