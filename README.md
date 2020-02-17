# Basic-Linux-Commands

**Managed by - Shivani Baldwa**

Learn basic commands for Linux, a free and open-source operating system.
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/linux_terminal.png">
</p>

## What is Linux?
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/linux.png">
</p>
Linux is an operating system's kernel.Linux is a UNIX clone. But it was actually created by Linus Torvalds from Scratch. Linux is free and open-source, that means that you can simply change anything in Linux. There are several Linux Distributions, commonly called “distros”.

Ubuntu Linux
Red Hat Enterprise Linux
Linux Mint
Debian
Fedora
Linux is Mainly used in servers. About 90% of the internet is powered by Linux servers. This is because Linux is fast, secure, and free.

## Linux Shell or "Terminal"

So, basically, a shell is a program that receives commands from the user and gives it to the OS to process, and it shows the output.To open the terminal, press Ctrl+Alt+T in Ubuntu, or press Alt+F2, type in gnome-terminal, and press enter. 
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/command_line_terminal.png">
</p>
           
## Linux Commands

### Basic Commands
1.pwd — When you first open the terminal, you are in the home directory of your user. To know which directory you are in, you can use the “pwd” command. It gives us the absolute path, which means the path that starts from the root. The root is the base of the Linux file system. It is denoted by a forward slash( / ). The user directory is usually something like "/home/username".
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/pwd.png">
</p>

2.ls — Use the "ls" command to know what files are in the directory you are in. You can see all the hidden files by using the command “ls -a”.
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/ls.png">
</p>

3.cd — Use the "cd" command to go to a directory. For example, if you are in the home folder, and you want to go to the downloads folder, then you can type in “cd Downloads”. Remember, this command is case sensitive, and you have to type in the name of the folder exactly as it is. 
To go back from a folder to the folder before that, you can type “cd ..” . The two dots represent back.
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/cd.png">
</p>

4.mkdir — Use the mkdir command when you need to create a folder or a directory.
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/mkdir.png">
</p>

5.rmdir  — Use rmdir to delete a directory. But rmdir can only be used to delete an empty directory. To delete a directory containing files, use rm.
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/rmdir.png">
</p>

6.rm - Use the rm command to delete files and directories.  Use "rm -r" to delete just the directory. It deletes both the folder and the files it contains when using only the rm command.
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/rm.png">
</p>

7.touch — The touch command is used to create a file. It can be anything, from an empty txt file to an empty zip file. For example, “touch new.txt”.
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/touch.png">
</p>

8.cp — Use the cp command to copy files through the command line. It takes two arguments: The first is the location of the file to be copied, the second is where to copy.
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/cp.png">
</p>

9.mv — Use the mv command to move files through the command line. We can also use the mv command to rename a file.
<p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/mv.png">
</p>

10.help  — To get help in Linux type -help or -h .
 <p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/help.png">
</p>

 ### Intermediate Commands
 
 1.echo — The "echo" command helps us move some data, usually text into a file. For example, if you want to create a new text file or add to an already made text file, you just need to type in,EXAMPLE : “ echo HEllo, My name is Shivani . I am from India >> new.txt"
 
 2.cat — Use the cat command to display the contents of a file. It is usually used to easily view programs.
  <p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/cat.png">
</p>

 3.nano, vi — nano and vi are already installed text editors in the Linux command line. The nano command is a good text editor   that denotes keywords with color and can recognize most languages. And vi is simpler than nano. You can create a new file or modify a file using this editor.You can save your files after editing by using the sequence Ctrl+X, then Y (or N for no).
  <p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/nano.png">
</p>

 <p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/vi.png">
</p>

 4.sudo — A widely used command in the Linux command line, sudo stands for "SuperUser Do". So, if you want any command to be done with administrative or root privileges, you can use the sudo command.You can also use the command “su” to do this, but you need to set a root password before that. For that, you can use the command “sudo passwd” *(not misspelled, it is passwd).* Then type in the new root password.
  <p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/sudo.png">
</p>

 5.df — Use the df command to see the available disk space in each of the partitions in your system. You can just type in df in the command line and you can see each mounted partition and their used/available space in % and in KBs. If you want it shown in megabytes, you can use the command “df -m”.
  <p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/df.png">
</p>

6.du — Use du to know the disk usage of a file in your system. If you want to know the disk usage for a particular folder or file in Linux, you can type in the command df and the name of the folder or file. 
  <p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/du.png">
</p>

7.tar — Use tar to work with tarballs (or files compressed in a tarball archive) in the Linux command line. It has a long list of uses. It can be used to compress and uncompress different types of tar archives like .tar, .tar.gz, .tar.bz2,etc.

8. zip, unzip — Use zip to compress files into a zip archive, and unzip to extract files from a zip archive.

9.uname — Use uname to show the information about the system your Linux distro is running. Using the command “uname -a” prints most of the information about the system. This prints the kernel release date, version, processor type, etc.
 <p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/uname.png">
</p>

10.apt-get — Use apt to work with packages in the Linux command line. Use apt-get to install packages. This requires root privileges, so use the sudo command with it.You can do that by typing “sudo apt-get update”. You can upgrade the system by typing “sudo apt-get upgrade”.
 <p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/apt-get.png">
</p>

11.chmod — Use chmod to make a file executable and to change the permissions granted to it in Linux.

12.hostname — Use hostname to know your name in your host or network. Basically, it displays your hostname and IP address. Just typing “hostname” gives the output. Typing in “hostname -I” gives you your IP address in your network.
 <p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/hostname.png">
</p>

13.ping — Use ping to check your connection to a server. Wikipedia says, "Ping is a computer network administration software utility used to test the reachability of a host on an Internet Protocol (IP) network". Simply, when you type in, for example, “ping google.com”, it checks if it can connect to the server and come back.
 <p align="center">
  <img src="https://github.com/oilmcut-2020/Basic-Linux-Commands/blob/master/images/ping.png">
</p>

## Tips and Tricks for Using Linux Command Line
- You can use the clear command to clear the terminal if it gets filled up with too many commands.
- TAB can be used to fill up in terminal. For example, You just need to type “cd Doc” and then TAB and the terminal fills the rest up and makes it “cd Documents”.
- Ctrl+C can be used to stop any command in terminal safely. If it doesn't stop with that, then Ctrl+Z can be used to force stop it.
- You can exit from the terminal by using the exit command.
- You can power off or reboot the computer by using the command sudo halt and sudo reboot.
