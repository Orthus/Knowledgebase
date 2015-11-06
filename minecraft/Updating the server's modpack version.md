Updating the server's modpack version
Modded Minecraft has become extremely popular over the last few years, and the vast majority of our customers prefer playing with these mods, rather than the standard, default "vanilla" Minecraft.

Generally, preparing, distributing and playing a modpack can be a rather difficult process, however a variety of third party launchers, such as the ATLauncher make this accessible for even the most novice of users. For the purpose of this example, we will be using a pack called Bytesize, which is one we have curated specifically for performance on both low-end servers and client machines, and is available on the ATLauncher.

#### What version are you currently running?
Generally with every pack update, a new version number is pushed. This version number is an important point of comparison to determine if your server is up to date. This can be seen from the top of every page within NodePanel, or the Configure -> Server jar section.

< img goes here>

As you can see, the current version of this server's Bytesize install, is 0.0.6. As we can see from the ATLauncher however, the latest is 0.0.7, so we need to begin the process of updating the server with the new version.

#### Updating the server version
The best way to perform a modpack update is to simply to run the install again via our jar catalog ("Install New Server Jar/Modpack" from the screenshot above), ensuring you select the option to keep old files, which will move your old files to an _old_files/[timestamp] directory. You can review these from the file manager, and in this case, we want the most recent, as performed a few moments ago. **Do not start your server yet**.

#### Accessing your old server files

< img goes here>

Once you have installed the new version and located your old files, you can begin the process of restoring your world. Do note that if you added any additional mods, etc, you will also need to perform this process again.

#### Restoring your server files
Inside this folder, you will find all of your previous files as expected, in the same format you've experienced in the past. For this demo, I will restore my server.properties file, world folder, and ops.json file. 

< img goes here>

After selecting this files, I need to move them back up into the root directory, or "/", so that our new install has access to the files. I simply hit the "move" button in the top right, and select "../", which will move up 1 directory. This isn't quite sufficient yet, as one directory up, will only be "_old_files". We need to head back into our "_old_files" directory, and perform the same task again.

< img goes here>

Our /world (folder), ops.json and server.properties can now be seen in the /_old_files directory, as one would expect after moving them up a directory. We need to perform the same action to move them up to our root directory, or "/".

#### Finalizing the process
If all has gone well, your root directory should now contain a directory structure similar to the following, including your files moved back the previous install.

< img goes here>

You should now be able to start your server again, and enjoy all the benefits an up to date modpack brings! If you have any questions regarding this article, or need any assistance with the steps, feel free to contact us at any time and our team will be happy to assist!