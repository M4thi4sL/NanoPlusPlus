# NanoPlusPlus
Super Tiny, barebones UE4.27 project that builds on windows to 93.6 MB

![BuildSize](https://github.com/MathiasLArt/NanoPlusPlus/assets/59111832/fe949496-ba79-40cc-9fed-5e4358c79632)

This is a stripped down version of a UE4.27 project that you can use when targeting a small buildsize. 
Note that a lot of plugins -and features- you might need during development are currently turned off, enable them at your own discretion.

I left oodle compression plugin enabled as the extra couple of MB by including it outweighs all the disk space you save once you add content to the project. 
oodle compression is at its highest, for maximum compression. 
I also enabled oodle texture compression, with an aggressive bias. you can tune this in the DefaultEngine.ini. 

![oodle](https://github.com/MathiasLArt/NanoPlusPlus/assets/59111832/cfcbb295-8b5c-4869-aa37-b148a3dd11d3)

You can find a blacklist of engine assets, DefaultPakFileRules.ini, /config folder. 
should your project require some of these assets just remove them from the blacklist. 
Using the blacklists saves you an additional extra couple of MB.

Screenshot of the build output
![build](https://github.com/MathiasLArt/NanoPlusPlus/assets/59111832/5e6d650d-21e4-41ab-8fc7-966cce1ad170)
