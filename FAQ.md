# Introduction:

DHMC 1.8 is finally here, and many things have changed. Knowledge of basic commands and plugins is essential to enjoying your time on DHMC fully. With new plugins and commands comes new questions, and here is where they will be answered. If your question is not here, find a staff member on the server or IRC. Anything not covered here was either unchanged or overlooked.

# General: 

**Why did it take so long?**

The short story is that bukkit had some legal trouble and is no more. Sponge, a completely new platform, was created by a group of concerned coders within the Minecraft community. These coders essentially had to write an entirely new bukkit, which is why it took over a year until we had a stable enough build to run a server on.

**What happened to [plugin]?**

It is likely that said plugin did not port over to Sponge. Sponge is completely different, and it requires a lot of work to move plugins from bukkit to Sponge. McMMO, Towny, and Residence are among the main plugins that did not port. Some replacements have 
arised, such as SafeGuard for Residence, and Keys for LWC. Prism has been ported.

**What happened to everything?**

The world we used on the 1.7 server is no longer suitable for the current version of Minecraft, which means we've moved worlds. We use a 1.8 world now, and the 1.7 world will be put up for download sometime in the near future. We have new spawns, new worlds, and a fresh start.

**Why couldn't I move my stuff?**

We've decided that it was time for a completely fresh start, so your stuff stayed in the old world (which can be downloaded, but the file is huge).

**Where can I go to gather resources?**

Resources are to be gathered in the Resource World to avoid destroying the main world. The Resource World resets at randomly selected times to give a fresh world to raid. Due to the fact that it does reset randomly, **do not build in the Resource World.** Also, *please* replant any trees you chop down; this world is not for you and you alone, and even if it was, you would want your trees back when they're all gone.

**What is the Poster World?**

The Poster World is where you go to build posters, which can be reached by using "/warp p". Posters are maps that have had their land modified to look a certain way (A poster of a map of America can actually be found somewhere in the world, just huge). Maps take a minimum of 128x128 blocks of space in the world, so you can imagine how much valuable main world space posters took up. The Poster World was created as a place to build these posters so we don't take up so much space in the main world, freeing up lots of space for you to build your homes on. **Do not build in the poster world unless it is a poster.**

**Why am I so laggy?**

Assuming you mean server lag, like block lag or chat lag, this is because of a Sponge bug that loads way too many chunks at once. This will not always be the case, but for now, turning down your render distance will help majorly, as will not flying around too much. If you absolutely must, go ahead and fly, but please do not pointlessly fly around because you are bored.

# Commands:


**How do I list my homes?**

"/homes" lists your homes.

**How do I move a home?**

Moving homes has changed a little bit. You cannot actually move homes any more, so you have to delete the home with "/delhome [home name]" and make another with "/sethome [home name]."

**How do I create a residence?**

Unfortunately, Residence was not ported over to Sponge. Vive has coded a replacement, SafeGuard, that does much the same thing. The basic command is "/SG", and "/SG help" gives you a list of commands. Zones protect you from griefers, so it is wise to set one up around your house.

Going a little bit further, in order to create a zone, you will need to use a series of commands, starting with "/SG zone" to make sure that you are not already in a zone. Second, find two opposite corners of a rectangle around your base and mark both of them with "/SG pos". Now that you have a rectangle, you can make it extend to the height limit and bedrock by using "/sg pos fullheight", which makes it not just cover the floor of your house, but also everything.

A full list of SafeGuard commands can be found here: http://puu.sh/n6oK7.png

**How do I lock/unlock my chest?**

LWC, our old plugin for locking things like chests and signs, was not ported, and no suitable replacements arised, so Vive made his own replacement for LWC called *Keys*, which does much the same job. Chests, furnaces, signs, and any other block that is covered by Keys automatically locks for you, preventing any potential theives and griefers from stealing your stored stuff. Use "/unlock" to unlock a chest completely, allowing anyone access. "/lock" will place a lock on your chest, allowing only you to get into it. "/keys add [player]" adds the specified player to the chest, allowing them to use the chest normally. Similarly, "/keys remove [player]" will remove the player from the chest so that they cannot use it.

# Bugs

**I've found a bug!**

Awesome! Please report it to any online staff, or if none are online, a staff on IRC. Try not to bother Vive himself because he is very busy trying to fix the bugs that have already been reported, and if your bug has already been reported, you will have wasted some of his valuable time. Try to find a staff member that can relay your message to vive if the bug has not already been found.

**Can I abuse any bugs I've found?**

No. Do not abuse any bugs you have found. That is ban-worthy. We thank you for finding bugs and reporting them, but abusing them will definitely ruin your run on DHMC.
