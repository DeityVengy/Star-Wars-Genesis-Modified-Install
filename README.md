# Star Wars Genesis Modified Install

## Warning
Okay well, first things first. You should be aware that you will receive limited support if you modify your list. I don't have the time or patience to help everyone that does so and encounters issues because of it. Additionally, you must only ask for help in the #Modified-Install channel of my Discord. This is because your issues are low priority due to most probably being caused by what you've done to the list, and not what I've done to the list. I have extensively tested the list and know nearly all the bugs with it. You aren't helping anyone by throwing bugs at me in the normal help channel and misleading me with your modified list. I can help you better if you're honest and I'm aware you are running a modified install. If I find that you're repeatedly asking for help in the normal channel with a modified list, I will simply give you a role that limits your view to only the modified help channel and the News channel.


## Guide
### Creation Store
I would personally just avoid the Creation Store. If a mod is on both Creations and NexusMods, then get it from NexusMods. If a mod is only on Creations, then just don't bother. This is because the mods on Creation are usually built for consoles. And consoles have some major differences compared to the PC version. You are begging to break your game by installing mods from there. 

### The Tool
One of the most important tools for every Starfield modlist is called [Starfield Engine Fixes](https://www.nexusmods.com/starfield/mods/10457?tab=files). It has a tool that tells you how many mod indexes are in use. You must enable this as it is currently an optional setting. Everytime you launch your game, it'll tell you how close you are to the cap. When you reach the cap, things break.

### What increases this index?
Each plugin, regardless of type, has 1 index. That 1 index is caused by overriding Starfield.esm. That's the basic functionality of plugins in every Bethesda game. In Starfield however, a plugin can have multiple indexes depending on other mods in your list. If a plugin you download overrides another mod's plugin (even if it is a single record) then that plugin you downloaded is now taking up two index slots, not just one. Now, you can imagine this can get messy real quick. Let's say you download a mod that extensively touches hundreds of records, like a worldspace mod, difficulty mod, etc. That single plugin can have like 10 indexes.

### How can I fix this?
Well, there are two ways to fix this, and one is easier than the other. The easiest solution is don't install a mod that touches hundreds of records and raises your index count by that much. The hard solution is you open your modlist in xEdit and literally delete every record that this plugin is overriding. You're not deleting records from the new plugin. Only the records of the plugins getting overrrided. If you do this correctly, you can drop a normal plugin to 1 pretty fast (or slow) depending on the size of the mod you installed. You won't lose any functionality doing this, since all the records you deleted aren't being used anyway. The new plugin was overwriting these records anyway. Now I can't promise that this mod you installed is gonna work correctly tho. That's a whole other ordeal lol.
