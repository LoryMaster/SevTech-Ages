# SevTech-Ages

## Info
This modpack was made by [Darkosto](https://www.twitch.tv/darkosto) for [Sevadus](https://www.twitch.tv/sevadus) on twitch.  

Things to keep in mind:

1. If you find any bugs, make sure to report them!!!!
2. Access to some mods has been intentionally removed.  Everything is progression based.
3. Look at the advancements, the pack uses them for questing. 

## Downloads
Released files: 
- [Curse/Twitch](https://minecraft.curseforge.com/projects/sevtech-ages)
- [ATLauncher](https://www.atlauncher.com/pack/SevTechAges)

## Performance
This is a heavy pack and will require a computer with pretty decent hardware to even run at a constant 30 fps. Here's a list of things to keep in mind and possibly do for the less tech savvy people:

BEFORE posting a bug report for bad performance, make sure your system can actually handle the game! Read the following!

1. System Requirements:
- Unless you're using shaders, minecraft mostly relies on CPU, RAM and partly on the disk it's ran from. Make sure the computer you're using to play has at the VERY MINIMUM 8 Gigabytes of RAM, if you have 16 Gigabytes even better.
- If you try to run Minecraft on a super old CPU, you won't be able to go far with this pack. You may be able to play at the very beginning, but once the world progress and you have a many machines and entities doing lots of things it's just gonna become a lag and low fps party. I could get into the specifics of which CPUs are better and which are worse, but for the sake of semplicity, let's just say that if your CPU was released more than 5 years ago it's probably a little old.
- The drive you're playing minecraft from CAN and WILL impact: World Generation, World Loading, Startup, Changing Dimensions and probably even more... Make sure you DO NOT play Minecraft from an external Hard Drive (i.e. DO NOT keep the game files in a folder inside an external hard drive) because everything will be much slower!

2. Java:
- Make sure you're running the lastest version of Java, and the appropriate one for your system! You can look at your Java version directly from windows (You can search from the "Start Menu" the keyword "Java" or "About Java"), or from inside Minecraft (By pressing F3 in the game, on the top right of the screen there will be written something like Java: 1.8.0_X 64bit). Make sure you're running Java 1.8.0, the revision is less important, but can impact things. Usually you want the latest version (higher numbers).

- Even if your system has 16 Gigabytes of RAM, the game may NOT be using it and sticking to 4 Gigabytes or even less (You can check this by pressing F3 while in the game and looking at the top right corner, there will be a "Mem:" row which tells how much memory is being used out of a maximum, i.e. "Mem: 60% 5130/8192MB"). If the Minecraft it not actually properly using enough RAM you need to change it:

If you're playing from the Twitch Launcher: On the top left of the launcher, press the 3 lines, go to Files->Settings (Or just press Ctrl+comma). Go in the "Minecraft" Category by choosing from the left. At The bottom there will be "Java Settings". There you can allocate the appropriate amount of RAM (N.B. Make sure NOT To allocate all of your RAM! Your system needs at least 2 Gigabytes free to keep functioning)

While you're in the Java settings, at the very bottom paste in the "Advanced" field this text:
-XX:+UseG1GC -Dsun.rmi.dgc.server.gcInterval=2147483646 -XX:+UnlockExperimentalVMOptions -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M

This is just some parameters the help minecraft use your RAM more efficiently.

3. What you can do:
- So, even if your system is not top of the line, you probably can still play the pack at a reasonable 24-30 fps stable. What you can do is tweak the video settings in Minecraft and add mods like Optifine (Which allow even more tweaking).
- Far Render distance is HEAVY on performance, Fancy Trees / Leaves are HEAVY. If you have Optifine you may even try to set most options on "Fast" (If you keep the mouse on a button in the video settings menu with Optifine installed a tooltip will appear explaining every option in more details).
- Shaders are VERY HEAVY! BUT!! Mostly rely on Graphics Cards, so you may actually be able to use a lightweight one if by chance you have an old system with a new / really good GPU.
- Other applications need CPU and RAM too! Remember that if you have other applications open (Especially youtube videos and livestreams at high qualities like 1080p60) they will eat your CPU and RAM, reducing what minecraft can use. Try playing without other programs / web pages open, it may help you!
