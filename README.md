# SpriteLightKit

SpriteLightKit brings back the old two buffered blend trick to get pseudo lighting with just sprites.

![low ambient light](http://cl.ly/c7Lf/darker.png)
![brighter ambient light](http://cl.ly/c7DN/lighter.png)

## Setup

- create an empty GameObject as a child of your main camera
- add the SpriteLightKit component to the GameObject
- set the Camera and Material (SpriteLightKitBlendMaterial) in the inspector
- set the Light Layer, which is the layer you want to place your lights on
- create some sprites using the SpriteLightMaterial and make sure they are on the Light Layer you chose in the previous step


You can set the ambient lighting by changing the background color of the camera on the SpriteLightKit GameObject. Each of your lights can use the normal sprite tint color to change how it affects the underlying scene.


Lights look best when they are white and falloff to 0 alpha. That lets you use the tint color to color the lights. Setting the tint color's alpha lets you set the intensity of the lights.



#### License

[Attribution-NonCommercial-ShareAlike 3.0 Unported](http://creativecommons.org/licenses/by-nc-sa/3.0/legalcode) with [simple explanation](http://creativecommons.org/licenses/by-nc-sa/3.0/deed.en_US) with the attribution clause waived. You are free to use SpriteLightKit in any and all games that you make. You cannot sell SpriteLightKit directly or as part of a larger game asset.