# WARNING
**Update 01.04.2024** - Thanks to Cycling74 support for pointig this out: If this plugin crashes on load, check what 3rd party plugins you already have in your live set. I can confirm, my Ableton 12 crashes on load if Amplitube 5 is present in any track of the live set. I can also reproduce this incompatibility on Ableton 11.
~~29.03.2024 I just upgraded to Ableton 12 and - it crashes Ableton 12. However, it works as intended when opening a Live Set that contains already the plugin. What is strange. Once you have a Live Set loaded with the plugin active, you can even choose to make a "New Live Set" and add the plugin without problems. Very strange indeed ... Same happens with other jitter/gl plugins in Ableton 12.~~

The Skybox feature does not work in Ableton 11/12 using the embedded Max version.

This M4L device is heavy! It may eat a lot of cpu, it uses GPU. This is especialy so if you use it for the 1st time. It is probably not posible to have it running in an already cpu expensive live set. 

## Can I use this without Ableton?

If you have Max8 - as you like. Download the full Max8 Project zip file, open the Project in Max8 and have fun. I deleop it in Max8 standalone and there is an ezdac~ / ezadc~ included. for this reason. If you load the project in Max, you will find two aditional, large, buttons in the visualisation (below the Ableton Plugin verical Limit):
 - High Res ON/OFF: Sets the internal dimension and the external window to 1080P, this will also result in good image quality if you use "esc" in the external window to switch to full screen
 - Esadc ON/OFF: enables signal inpuit from ezadc and pass trougth to to ezdac (ofc you need to switch audio on in Max8) 
 And if you find parts on the patchers that you like, want to copy for yourself - feel free. At Maxforlife.com i used "Creatice commons attribution License". Here it is maked GPL-3. For real, I don't care. Download it and disembowel it as you like. It is open source. It would IMHO just polite, if you use reasonable parts to publich you own work based on this code, to attribute the, now two, creators, Supertramp 162 and me.

 [AudioReacticeVideoSynth-Max8-Project-Zip](https://github.com/th-m-vogel/Max-Patches/raw/main/M4L-Devices/AudioReactiveVideoSynth/AudioReactiveVideoSynth.zip "Download")

 The ZIP File may not always be up to date, better pull the project or fork it using git.

## My System

Deleopment and testing is done using Windows 11, Ableton 11 Suite (latest update), Max8 (latest update), Ableton is configured to NOT use the bundled Max version (Ableton Preference, Folders).
- AMD Ryzen 7 5700 8 Core CPU
- 32 GB
- Geforce RTX 3060
- 32 GB Memory

# DESCRIPTION:

AudioReactiveVideoSynth was originally created by supertramp162 and published on maxforlife.com.

Link to supertramp162
- MaxforLive: https://maxforlive.com/profile/user/Supertramp162
- YouTube: https://www.youtube.com/@Supertramp162

# Download M4L device

[AudioReactiveVideoSynth](https://github.com/th-m-vogel/Max-Patches/raw/main/M4L-Devices/AudioReactiveVideoSynth/AudioReactiveVideoSynth.amxd "Download")

# Custome Skyboxes

You can drop a Cubemap on the VCR preview in the device. For Space cubemaps you may want to visit - https://tools.wwwtyro.net/space-3d/index.html - the skybox included with the plugin is a 1k skybox from tyro. 1st release version included 2k skyboxes - that's somewhat heavy. Keep in mind, a 1k skybox is already a 4k by 3k png file.

# ACTUAL STATE

Tracks created with this device: 
- Version 0.5 - https://youtu.be/GW951CoEjf4
- Latest update - https://youtu.be/m0fzrX3LgxI

2nd release update
- there is now only one skybox included, however, you can apply your own skybox by dropping a cubemap on the VCR preview. For cubmap files see also the cubmap folder here. 
- skybox is deisabled by defailt to make the plugin a bit less demanding by default.

2nd release
- Mous over Help for all UI elements (at least think that i added this for all ... )
- An additional object to chose from (Wave, just to play with jit.gen)
- Many more options to customize the objects rendering and camera control.
- you can use a custome skybox. Just drop the skybox file (cross shape cubemap) on the video preview in the plugin.

1st relaese: 
- added direct recording function
- some internal rework, got some understanding of the internal working
- new UI
- added a skybox

![Screenshot](./Device-Screenshot.png)

# NEXT STEPS

~~- Understand what was done and use it to develop furter from here ... we will see.~~
~~- Use custome Cubemap by dropping file on Plugin~~
- improve on animation ... ongoing
- improve on video effects ... after a 1.0 version.

# Remarks

Enjoy ... make music ... Use at your own risk ... 

