### Hi there 👋

My dream is for Linux to become a go-to OS for personal computing, and to have it run well on even the cheapest Single Board Computers under $100. Many things that x86 Linux and Windows users take for granted is not easy or straightforward on ARM Linux, so I try to do what I can as a shell scripter to **lower the barrier to entry.**  

In 2018, when I was in middle school, I was given a Raspberry Pi 3. I knew nothing about Linux or programming. Raspbian was harder to use back then, and I encountered numerous issues, many of which were my own doing. Slowly, through hundreds of Google searches, I began making a list of useful terminal commands to do specific things: copy a file, create a keyboard shortcut, install something, search for a file, make a backup, close an unresponsive program, or recover from a frozen screen. Eventually, my list of commands was getting very long, and that's when I discovered **shell scripts** - a special text file that runs a list of terminal commands. How useful!  

Shell scripting is not suitable for everything, but it sure can get a lot done on the OS level, and it is far more capable than what most people assume. With [YAD](http://smokey01.com/yad/), you can even make fairly complex graphical applications using only shell script!

So as a child and growing up, I have written numerous shell scripts to make what was one hard, easy. Some of my best scripts are published here on github for everyone's benefit.

- [vdesktop](https://github.com/Botspot/vdesktop) - basically VirtualBox but it runs on a Raspberry Pi. This command-line tool was the first RPi-compatible application capable of interacting with the virtual machine's **graphical desktop session.**  
- [Pi Power Tools](https://github.com/Botspot/Pi-Power-Tools) - a suite of tools for creating and modifying Raspberry Pi OS disk-images and SD cards. This was the first application I made with a GUI interface.  
- [Pi-Apps](https://github.com/Botspot/pi-apps) - the most popular Raspberry Pi app store by far.
- [YouTubuddy](https://github.com/Botspot/youtubuddy) - The private, lightweight YouTube search engine & player with the best hardware-acceleration available.
- [CloudBuddy](https://github.com/Botspot/cloudbuddy) - The ultimate way to manage your cloud storage on any Linux computer. This is a bash-powered GUI frontend for `rclone`, and includes built-in support for Google Drive, Dropbox, and OneDrive. It's vastly more convenient than any other web interface or tool available elsewhere.
- [AndroidBuddy](https://github.com/Botspot/androidbuddy) - Manage your Android phone from a Linux computer. Allows complete screen control, file sharing, internet sharing, and much more.
- [Update Buddy](https://github.com/Botspot/update-buddy) - a sleek utility to run on startup. It runs `sudo apt update` in the background, and if any updates are found, it displays a non-intrusive notification, asking permission to install updates.
- [WoR-flasher](https://github.com/Botspot/wor-flasher) - World's first Linux-compatible tool to install Windows 10 or 11 on a Raspberry Pi SD card. Before this tool existed, you had to use a Windows PC to install Windows on a Pi's SD card, but with this tool, you now can use a Pi to do it all.
- [Windows Screensavers](https://github.com/Botspot/Screensavers) - An efficient GUI screensaver manager, preloaded with fourteen classic Windows screensavers that run smoothly on the RPi using Wine.
- [Downgrade Chromium](https://www.raspberrypi.org/forums/viewtopic.php?f=63&t=308303) - The latest and greatest web browsers are not necessarily the best, or the fastest. This application allows you to easily switch versions of Chromium Browser.

Most of these scripts I have written, released, and left alone to slowly rot. Pi-Apps is an exception. Enough people use Pi-Apps that it justifies the time it takes to keep it maintained and forever improving.  
I'm just one guy, a busy college student. If you have read this far and want to help, please reach out! I could use some help with Pi-Apps. Anybody who knows a bit of scripting is welcome to look through the codebase and offer code improvements and new apps. Also, if you want, I would be glad to help you understand how any of my scripts work. Just join [my discord server](https://discord.gg/RXSTvaUvuu) and ask whatever you want.

I have recently fallen on hard financial times. If you would like to donate as a way of saying thanks, I have a [GitHub Sponsors profile](https://github.com/sponsors/Botspot) and a [PayPal link](https://www.paypal.com/donate/?hosted_button_id=97LDEFVY5AU4G).
