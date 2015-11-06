Bukkit or CraftBukkit servers (and servers that use Bukkit, such as Tekkit) utilize an open source plugin system which allows server owners to upload and configure a huge variety of plugins. You can find the plugins at the plugin website: http://dev.bukkit.org
You'll want to check that the plugin is compatible with your version of Bukkit and has the options you'll want to use. To install the plugin you can either use the BukGet feature within NodePanel, or you can upload it NodePanel, or FTP.

### Installing Plugins with BukGet
Within NodePanel, simply select the "Bukkit Plugins" submenu under "File Manager" on the left hand side, and begin searching and managing your plugins. Our intuitive interface should be able to guide you through the process with ease.

### Installing Plugins with FTP
If you aren't familiar with FTP. please read our FTP Tutorial first. Next you'll want to download the plugin you wish to install from the plugin website (http://dev.bukkit.org). Most plugins are a simple "pluginname.jar" file which is all you need to install it however others may be a zip, so you can simply unzip the archive and upload all of the other folder/files with the .jar file, or upload the zip and use NodePanel's File Manager interface to unzip the file after upload. Once you've downloaded the plugin you'll need to upload it to your server. After you've connected to your server via FTP you should see a folder named "plugins". Upload the server plugin to this folder and you will have installed the plugin.

### Configuring Plugins
Most plugins have a configuration which will be in their own folder which is typically the same name as the plugin. For example WorldEdit.jar has the folder "WorldEdit". Simply open the folder and edit each file with a text editor such as NotePad++. You'll need to upload any changes you make to the configuration via FTP as well.

### Updating Plugins
As the plugins are developed and new versions of Minecraft are released, your plugins will need to be updated as well. You'll need to follow the same steps as uploading the plugins, but you will be replacing the older files. Some plugins are more complex than others, so be sure to check the plugin's page on the plugin's website for more information.