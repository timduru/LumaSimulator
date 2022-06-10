# This is an easy to use unity package that allows you to test your material's Furality Luma reactivity directly into unity 

You can easily test your materials with the [AquaShader](https://furality.org/aqua-assets) or [Poiyomi-Luma](https://github.com/timduru/Kat.PoiyomiToonShader) that way and see the result in real time as you change parameters in the shaders while running the scene in unity.
(You can also test your pure audiolink materials the same way too)


It is simply using the Audio Link avatar testing prefab and LumaDriver in a preconfigured way so that they work together :)
I only repackaged and configured them so that it's easy and just a drag and drop to add it into your projects.

**All credits goes to the 2 original creators of these prefabs: Thorinair and llealloo.**


Please note that it is not an officially supported method of testing by Furality (yet ? ;) ). 
As such don't request for assistance about it to the Furality staff. 

If you need official help about the Aqua shader, make sure you have also tested with the shader's debug mode and Fynn's room before asking for help in Furality's discord.


# Youtube Video how-to and demo: 
https://youtu.be/pCTmMCsuEOQ

# Installation & Use: 
Download the latest package from [Releases](https://github.com/timduru/LumaSimulator/releases)
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

# Configuration

By default both audiolink and luma are on by default, so your audiolink materials will also react.

If you want to force one or the other mode (Luma / Audiolink) you can either disable LumaDriver or the AudiolinkAvatar  in the Hierarchy 

But if you deactivate the AudioLinkAvatar, as lumadriver is using audiolink to simulate the effects by default, it will fallback to its idle mode and slowly changing gradients in the zones and you won't be able to test with dynamic audio. Which is also a good test, as furality's worlds (outside of the club) will have simular slowly changing effects.
(it does the same when there is no audio with this prefab, Lumadriver will fall back into idle mode)

If you need to , you can see on Lumadriver's github page for more information on how to further configure its different modes, speeds, colors and so on. You have many options at hand to do further testings ! :)

Configuration can be accessed from the LumaDriver_Driver Material in your Project's assets: 
![image](https://user-images.githubusercontent.com/2088877/172584795-1c6575c0-a612-47a1-8f4f-41502f846cf7.png)



# Different ways of testing your Luma Materials:
## Fynn's room world in VRChat 
it will allow you to test the zones and by default gives you a very slow changing glow, you can make your first test in that mode with a white emission and a zone for example (and you should then see it glow and change color in fynn's room)

There is also now a "Luma Glow Test" button that feeds a loop of past Furality Legends data from one of the previous DJ.
![image](https://user-images.githubusercontent.com/2088877/173049539-2aab8006-bf9a-494c-86c8-810862842332.png)
Using this button you'll get a more accurate representation of the live data. 


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

Overall it's still better to also test in VRChat as the lighting is not the same in your unity project, especially if you're using transparency.

## Additional remarks

All of these methods have their pros and cons.
And keep in mind that the end result will be a bit different because the effects will be human controlled in Furality's worlds and custom for each DJs. 

Note that as the effects are generated for Luma based on the audio(link) in both Luminescent Ledge and this prefab
overall what you see in the simulation is most likely more "dynamic" and keeps the effects on more often at the same time than what you might see in Furality's Club world in the end. 
Especially if you use both a zone + audio on an emission, as the gradient zones in Furality's club tend to have more "holes" in them,  your emission will turn off more often.

To do further testing you can also play with lumadriver's rich options.

And be prepared to fine tunes things on the 1st day as we get the new updated luma data from the club and worlds :)


# Credits & Links: 
### LumaDriver made by Thorinair
https://github.com/Thorinair/LumaDriver

There you will also find all the information you need to configure it differently than the default in this prefab.
It has a many powerfull options to tailor it and change the generated effects.

### AudioLink Prefab by llealloo
https://github.com/llealloo/vrc-udon-audio-link


### Poiyomi-Luma Shader: 
https://github.com/timduru/Kat.PoiyomiToonShader

### Aqua Shader: 
https://furality.org/aqua-assets

### Furality official website : 
https://furality.org


### Licenses
See each different license located in their respective directories or packages 


### Music provided by Argofox:
Rewayde - Attraction [Argofox Release]

https://youtu.be/KtgZG9SI6Ws

You can visit his youtube or soundcloud for many more: 
- https://www.youtube.com/user/MMMontageMusic
- https://soundcloud.com/argofox
