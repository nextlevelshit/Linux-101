# GNU/Linux 101
Most crucial commands about Linux and the bash

Every new GNU/Linux user has to get to know several commands. The file system differs from Windows, but is similar to the Mac OS. I will take you by the hand and show you step by step everything you have to know.

## Open the Bash
The ```BASH``` or also known as ```TERMINAL``` is the place to be. The terminal unites your desktop, file manager, text editor and many more. Furthermore you can install or uninstall programs, configure your system, start webservers and so one. Hopefully you have recognized the fundamental super power of the secret black box calles terminal

*If you are on your Raspbian Desktop, click on the screen icon in the upper called **LXTerminal**.*

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

## ```ls``` List content of the current directory
You have seen that your command line is something like a magnifiying glass on a specific folder or rather directory. Every command you will type in the terminal will have its starting point from there. If you have follwed the previous parts you are currently in the root directory ```/```.

Now type in just the these two letters: ```ls```

The output will be something like: 
```bash
pi@raspberrypi ] / $ ls
bin  boot  dev  etc  home  lib  lost+found  media  mnt  opt  proc  root  run  sbin  selinux  srv  sys  tmp  usr  var
```

These terms are mostly directories. ```ls``` lists all directories and files included in the current path you are.
