Both CraftBukkit and Forge are server-side modifications to the Minecraft server jar. Each provide their own APIs for developers to use and create their own content, and also each provide some basic commands, however, CraftBukkit has various limitations that Forge does not, but also, provides much more ease-of-use to the average client.

### CraftBukkit
CraftBukkit offers the ability to install "plugins" onto your server, which can use the offered APIs to manipulate gameplay, create minigames, RPG based systems, etc, but all things that operate on the server only. For this reason, it is impossible for a CraftBukkit plugin to add additional content to the game such as new blocks/items, but this also means that clients can connect using a vanilla Minecraft client, without having to make any modifications on their side.

### Forge
Forge however offers the ability to manipulate almost anything in the game, including the ability to add blocks, items, entities, etc. Forge isn't limited in the same way as it can also exist on the client, however this also creates some difficulties and less ease-of-use, as every client connecting to the server would generally require the same set of mods to be allowed to join (there are some exceptions with server-only and client-only mods, but any mod that adds new content to the game will definitely be required to exist on both the server and each and every client connecting). As you've likely seen with various modpack distributors such as FTB and Technic, this is made a lot easier nowadays, and even easier in 1.7 Forge now with the lack of specific item IDs causing conflicts between servers and clients.

### Additional information
Beyond this, there also exists various jars such as Spigot and MCPC/Cauldron which are forks of CraftBukkit and Forge/CraftBukkit respectively. Cauldron does allow you to run both Forge mods and CraftBukkit plugins alongside each other, but of course, clients are still required to have the modifications that exist on the server, also on their client.