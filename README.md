This is an easy to use unity package that allows you to test your material's Luma reactivity directly into unity 

(as well as audiolink)


It is simply using the Audio Link avatar testing prefab and LumaDriver in a preconfigured way so that they work together :)


All credits goes to the 2 original creators of these prefabs.
I only repackaged and configured them so that it's easy and just a drag and drop to add it into your projects.


Please note that it is not officially supported by Furality.

It will however give you a very good idea of what to expect and allows you to test better your materials and more advanced shader configurations that are not possible to test in Fynn's room or with the shader's debug mode for example.


# Youtube Video how-to and demo: 
https://youtu.be/De-UjNVWko4


# Installation & Use: 
1) Import the unitypackage into your project
2) Drag and drop the "AudioLinkLumaSimulator" prefab into your scene (Located in Assets/AudioLinkLumaSimulation)
3) Hit Unity's play button

# How-to Change the Audio file: 
![image](https://user-images.githubusercontent.com/2088877/172264558-96cf7824-724c-42d4-8e0f-9f49d529b16e.png)

- Select the AudioLinkLumaSimulator Prefab in your hierarchy and right click => unpack prefab
- click on "Rewayde - Attraction [Argofox Release]" and delete
- Drop an audio file of your own into your scene
- Click on AudioLinkAvatar
- Drag and drop the audio file that you added in the scene into the "Audio Source" setting

![image](https://user-images.githubusercontent.com/2088877/172259737-5df1645f-dda8-4a8e-828b-6c0645263c6e.png)


# Different ways of testing your Luma Materials:
## Fynn's room world in VRChat 
it will allow you to test the zones and gives you a very slow changing glow, you can make the first tests there with a basic white emission for example 
(you should then see it glow and change color in fynn's room)

## Debug mode in the AquaShader
If you check the box at the bottom of the shader's settings, it will simulate some of the zones activity too directly in unity 
(don't forget to uncheck it before uploading your avatar)

## Luminescent Ledge's VRChat world made by Thorinair
https://vrchat.com/home/world/wrld_fb4edc80-6c48-43f2-9bd1-2fa9f1345621

In this awesome and super pretty world you can test everything and with nice variety of effects including audio reactivity 
(note that it is not officially supported by Furality) 
In that world you can put a video in the player and it'll react to audio too in addition of simulating the different zones. 

## LumaSimulator Prefab
You are here :P 

You can just drop it into your unity project and it will do something similar to luminescent ledge and allow you to test by just pressing the unity play button.  
(note that it is not officially supported by Furality)

Overall it's still better to also test in VRChat as the lighting is not the same in your unity project, especially if you're using transparency.

All of these methods have their pros and cons.
And keep in mind that the end result will be a bit different because the effects will be human controlled in Furality's worlds and custom for each DJs. 

Note that as the effects are generated for Luma based on the audio(link) in both Luminescent Ledge and this prefab
overall what you see in the simulation is most likely more "dynamic" and keeps the effects on more often at the same time than what you might see in Furality's Club world in the end.


# Credits & Links: 
### LumaDriver made by Thorinair
https://github.com/Thorinair/LumaDriver

### AudioLink Prefab by llealloo
https://github.com/llealloo/vrc-udon-audio-link


### Poiyomi-Luma Shader: 
https://github.com/timduru/Kat.PoiyomiToonShader

### Aqua Shader: 
https://furality.org/aqua-assets

### Furality official website : https://furality.org


See their respective licenses located in their respective directories. 


### Music provided by Argofox:
Rewayde - Attraction [Argofox Release]

https://youtu.be/KtgZG9SI6Ws

You can visit his youtube or soundcloud for many more: 
- https://www.youtube.com/user/MMMontageMusic
- https://soundcloud.com/argofox
