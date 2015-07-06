# GNU/Linux 101
Most crucial commands about Linux and the bash

Every new GNU/Linux user has to get to know several commands. The file system differs from Windows, but is similar to the Mac OS. I will take you by the hand and show you step by step everything you have to know.

## Open the Bash
The ```BASH``` or also known as ```TERMINAL``` is the place to be. The terminal unites your desktop, file manager, text editor and many more. Furthermore you can install or uninstall programs, configure your system, start webservers and so one. Hopefully you have recognized the fundamental super power of the secret Pandora's box ... the so called terminal.

**If you are using a Raspbian Desktop, click on the black screen icon in the upper panel bar titled *LXTerminal*.**

## First view

```bash
pi@raspberrypi ~ $
```

- ```pi``` stands for the logged in user.
- ```raspberrypi``` stands for the computer or rather the device you are using.
- ```~``` stands for your home folder. In Windows it is "My Documents" or in German "Eigene Dateien"

## ```cd``` Change the directory
Directories are your folders like "Downloads", "Desktop" etc. Every system has a root directory. The beginning of every path starts in there and is callable by ```/```.

```bash
pi@raspberrypi ~ $ cd /
```
Change directory to / -> Bring me to the root directory

And you can see, that the beginning of your command line changed to something similiar like ```pi@raspberrypi / $```. The only difference is that ```~``` changed to ```/```.

But listen, this is not the only thing happening. This is fundamental stuff to navigate through you your file system. In the next chapter you will learn how to read the containing files and folders. So you can type 

## ```ls``` List content of the current directory
You have seen that your command line is something like a magnifiying glass on a specific folder or rather directory. Every command you will type in the terminal will have its starting point from there. If you have follwed the previous parts you are currently in the root directory ```/```.

Now type in just the these two single letters: ```ls```

```bash
pi@raspberrypi / $ ls
```

The output should be exactly like here: 
```bash
bin  boot  dev  etc  home  lib  lost+found  media  mnt  opt  proc  root  run  sbin  selinux  srv  sys  tmp  usr  var
```

These terms are mostly directories. But in general the ```ls``` command lists all directories and files included in the current path you are.

Now you can add ```options``` to the command. Options are specific parameters to determine the output or rather what the command should do in detail.

Every command got its own options, but some ones are quiet similiar. For example try this:

```bash
pi@raspberrypi / $ ls --help
```
The outout will be a handy documentation of all variaties of the prepend command. You can add ``` --help``` almost to every command. If it does not work, try ``` --man```. This will do the same work. And please, do not forget the white space and remember to hit the double dash. 

## What do we learned so far?

We learned the super fundamental commands ```cd``` and ```ls```. Now we are able to navigate through our file system
