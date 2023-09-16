# NanoPlusPlus
Super Tiny, barebones UE4.27 project that builds on windows to 96.3 MB

I present a stripped down version of a UE4 project. (4.27) that you can use when targeting a small buildsize. 
Note that a lot of plugins -and features- you might need during development are currently turned off, enable at your own discretion the required plugins. 

I left oodle compression plugin enabled as the extra couple of MB by including it outweighs all the disk space you save once you add content to the project. 
oodle compression is at its highest, for maximum compression. 

I also enabled oodle texture compression, with an aggressive bias. you can tune this in the default.ini. 

You can find a blacklist of engine assets, (that get autoshipped but usually arent needed) in the build/win64 section. should your project require some of these assets just remove them from the blacklist. 
