### I have lag on my server, now what? 
In answering this question there are many things to take into consideration; are you having FPS lag, TPS lag or just latency issues.

< img goes here>

Latency issues are the easiest to diagnose. Firstly, look on your Minecraft client and see how many "bars" you have. This provides a brief overview of your connection to the server and mousing over the green bars will display your ping. This is not always accurate, and we'd recommend pinging the server directly via the related article.

In this example, the top-most server is of further distance from my connection. so my ping, or latency is larger, as the packets have more hops, and distance to travel. This means I could experience a delay logging into this server, and performing actions once connected. The higher the ms ping, the more latency it could cause. Make sure when purchasing a server that you choose the closest to connection to yourself, or the majority of your player-base. 

Other latency issues can be caused by your ISP or connection to the internet. These are harder to diagnose, but our support team will often request something known as a traceroute to help diagnose the issue, and further information regarding these can be found in the related article.

TPS (ticks per second) lag is the second most common cause of appeared "lag" when playing on a server. A perfect server will run at 20TPS however, especially on a modded server in the real world, this isn't always possible. There are few things you can do to relieve the stress of TPS lag on your server, including changing the amount of RAM you have available on your server, especially if you're hitting your 100% cap. Additionally, if you have Opis (or a mod able to perform similar actions) on your server, you can run the “/opis” command and clear all mobs and entities from the world. If you are running Spigot, Bukkit or Cauldron then you can install plugins such as ClearLag or WorldBorder which can clear all entities or create a world border to deter players from living thousands of blocks away and keeping chunks open. Lastly, it's best to keep any kind of chunk loaders to a minimum, especially in demanding areas such as mob farms, or active redstone/machinery as these will often impact the TPS of your server.

The last and most common causes of lag is often misrepresented as server lag, and relies solely on the power of a client computer, and is dubbed, FPS lag, also known as client side lag. You can check your FPS by pressing F3 in game and it will appear in the top left of your screen.

< img goes here>

In the most simple terms, the higher the FPS, then the less "client lag" you are generally going to have. Causes of FPS lag would be many dropped items, entities such as animals and the power of your client system. In the example image here you will have no lag providing it stays above ~60FPS, which is an industry expected standard, and the refresh rate of most monitors to date. Altering various settings in your "video settings" menu within Minecraft may yield further results to increase your FPS. Finally, there are various mods that can help increase FPS such as Fastcraft and Optifine, but mileage with these may often vary heavily.

