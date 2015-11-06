INFO: It's highly recommend you check out our article on using the web-based File Manager in our control panel. This interface provides a much faster solution to remotely managing your server's files.

FTP, also known as the "File Transfer Protocol", is a protocol used by programs to remotely connect to another computer and make changes to its files. Today most webhosting and game server services such as ourselves utilize FTP to provide our customers with access to their service files. As the protocol itself is highly technical, it's often preferred to use software such as the ones listed below to perform these commands.

### Free FTP Clients by Operating System

| Windows | Mac | Linux|
| ---| ---| ---|
| [WinSCP](http://winscp.net/) | [Cyberduck](https://cyberduck.io/) | [FileZilla](https://filezilla-project.org/download.php?show_all=1)|
| [FileZilla](https://filezilla-project.org/download.php?type=client)| [FileZilla](https://filezilla-project.org/download.php?show_all=1)| [CrossFTP](http://www.crossftp.com/screenshots.htm)|
| | [CrossFTP](http://www.crossftp.com/screenshots.htm) | [LFTP](http://lftp.yar.ru/)|

For the purpose of this tutorial we will be using FileZilla. The following instructions below should translate to the FTP program you are using.

### **Part: I** - Connecting to your server, and transferring files
Before you can start managing files, you must connect and authenticate with the FTP server. This requires four pieces of information:


|Name| Description| Default Value for Customers|
| --- | --- | --- |
| Host  | The address of the server  |  This is typically your server's IP, not including the port |
|Port | The port, where to "dock" on the server  | 21  |
|Username|Authentication username|Use the same login username or email used when logging in to our website|
|Password|Authentication password|Use the same login password used when logging in to our website|

Once you have this information ready, you can open your client. When you first open FileZilla, you will find four input boxes awaiting the aforementioned information:

< img goes here >

After filling these fields out, simply click on the "Quickconnnect" button. If your connection was successful, you will find the two boxes at the bottom of the interface to be filled with files and folders. If this is not the case, please check the log output in the box directly below the connection form. See the screenshot below for more information; red error messages which will help you identify the problem, and our staff will be happy to assist if these issues persist.

After you connect, two windows in the bottom (left and right) will become active. The left window outlines your personal computer, and the right your server and its files. You can navigate through these windows just like you would in your own file system (looking through files in windows).


< img goes here >


### **Part: II** - Server file manipulation
Now that you are connected to the FTP server, you can now start managing your files. The interface now resembles the connection between your computer and the remote server. This interface is recommended for use when moving files from one side to the other. Keep in mind that the folder with the name ".." means "up one folder".

#### Uploading Files
Uploading a file is the most basic operation in FileZilla. You simply drag the file/folder from Your Computer's Files (left side) to the Remote Server Files (right side). Be careful where you drop the file; droping the file into a folder it will upload it to that folder.

#### Downloading Files
Downloading a file is the exact same process as uploading a file, but in reverse. You simply drag the file/folder from the Remote Server Files (right side) to your Computer's Files (left side).

#### Moving Files
Moving files on the remote server is just like your computer. You simply need to drag and drop the files. The same rules when dragging and dropping previously apply here.

#### Editing Files
Unfortunately editing a file directly via FTP isn't possible. While some FTP clients have support for integration with text based editors, they all are doing the same operation. The easiest way to edit a file is to download a file to your computer, make the changes with an editor, and upload the same file back to the server. 
Alternatively you can edit it by right clicking the file and then "View/Edit". A window may pop up asking you what program you want to use. It is strongly recommended to use a more advanced editor like Notepad++, especially when dealing with YAML configurations, but for now, notepad will suffice. After you are done editing the file, save it as you normally would (file->save or the CTRL + S hotkey) and a window will pop up asking you if you want to update the file.

#### Deleting Files
Much like moving files, this process is just like your local computer. You can click on a file/folder and press the delete key on your keyboard or right click and click delete. Note: deleting folders may take an extended amount of time as the FTP client must make a request to delete each file in any folder. Some game server files have hundreds or thousands of files which can take several hours. It's recommended to use our web-based file manager to perform these operations.

#### Any further questions?
If you have any more questions regarding FTP, please open a support ticket and we'll be more than happy to assist.