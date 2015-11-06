Restoring a backup of your world is a very simply process. We'd recommend that you become familiar with your file manager, or FTP before attempting this however, or contact us if you're having any issues.

Before you can restore a backup, you will need to create a backup. There are two types of backup that you can create, but you can read more about this process in the attached article.

##### Retrieving the backup

Firstly, ensure your server is offline before starting the process of restoring a backup. After doing so, you will need to hover your cursor over the manage button on the backup you wish to restore and hit the "upload to server" button.

< img goes here>


A message indicating the file name will be shown. Please take note of this file name as it will make locating the backup easier moving forward.

< img goes here>

You will find this file in your file manager in the root folder "/", however, keep refreshing the directory until the file size matches the original backup size, as the file is retrieved from external servers. Now, depending on if the backup was a "smart" or "full" backup, there are two options.

##### Restoring a full backup

If the backup created was a full backup, you can simply use the file manager (or FTP) to select all, and remove all files except the recently retrieved backup. Simply unzip the backup, and it should contain all your files and folders as expected.

##### Restoring a smart backup

In this scenario, we recommend creating a work directly to unzip your backup into and manipulate without affecting your current files. "Unzipped Backup", or "workdir" are just examples of names you could use for this folder.


< img goes here>

Now you will want to rename your current world folder to something similar to world-old. You can also delete your old world folder, but we recommend renaming it for now, for the sake of redundancy.

< img goes here>

Now, simply move your backup zip file into your working directory, such as "Unzipped Backup" or "workdir", and once the file has been moved, browse into the folder and unzip the backup.

< img goes here>

##### Finalising the world restore

After unzipped, you should see a familiar set of files, including your world folder. A smart backup may not contain folders such as your mods, dynmap, etc, however your world should be intact.

Select your world folder by the small box on the left hand side, and move the folder to ".." which simply means "up one directory". Once complete, verify that the folder is the same name as the currently set world name, in your root, or "/" directory.

< img goes here>

Assuming this information is now correct, the server should be able to be started. If you world name has since changed however, you can either rename the world folder to the current world or update the current world to be the folder name via the "Configure" section of the control panel. The server should now be able to be started. 