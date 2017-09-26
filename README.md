# SnowingMinecraft3D

![SnowingMinecraft](https://i.imgur.com/bEap3dt.png)

This project is the snowing minecfraft
At the begining, I want to make geometry shapes falling down in the map and until they're not outisde the map, they don't appeared again.
Unfortunately, it's hard to understand why the plan gravity fixed geometry for the map is not considered, and so the shapes fall down like snow and appeared again.
It will be okay for the next version, the same behaviour as the file mooving.html or simplePhysical.html, where the gravity between a fixed mesh (the floor) and a mooving one is well managed


-----
### minecraftSnow.html

![Map Minecraft](https://i.imgur.com/y0WOjZC.png)




Minecraft random generation map with a perlin noise
You have a red transparent plan 30 centimeters above all the floors' blocks of the map which representate the gravity block. These blocks should stop the falling shapes...

You can choose change :
*  the boxes number falling in the map (0 -> 1000)
* The gravity of the map (-100 -> 100)

The directional move with the mouse can be changed. Currently it's orbital move and can be set to first person view in the JS code of the minecraftSnow.html file


-----
### simplePhysical.html
![Simple physical shapes falling down](https://i.imgur.com/croQzq9.png)




This file represent a mooving shape which is falling down in a fixed plane


-----
### mooving.html
![Mooving](https://i.imgur.com/BbTB4Wp.png)




It's an OIMO (gravity library used) example at the begining. I moidified it a bit to understand how it works.
And that's what i want to reproduce in the minecraftSnow

You can find the original example here : https://lo-th.github.io/Oimo.js/examples/test_moving.html




