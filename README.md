### Hi there 👋

I'm just a guy who believes everyone should use a Raspberry Pi as their daily, desktop PC. Few developers share this dream and as a result, the desktop experience of Raspberry Pi OS is lacking.  
Rather than complain to the Raspberry Pi developers, I became one myself.  

When I was first given a Raspberry Pi 3 in 2018, I knew nothing about Linux or programming. Raspbian was harder to use back then, and I encountered many problems. Slowly, through hundreds of Google searches, I began making a list of useful terminal commands to do specific things: copy a file, create a keyboard shortcut, install something, search for a file, make a backup, close an unresponsive program, or recover from a frozen screen. Eventually, my list of commands was getting very long, and that's when I discovered **shell scripts** - a special text file that runs a list of terminal commands. How useful!  

My first major shell-script was [vdesktop](https://github.com/Botspot/vdesktop) - basically virtualbox but it runs on a Raspberry Pi. This command-line tool was the first RPi-compatible application capable of interacting with the virtual machine's **graphical desktop session.**  
Next came [Pi Power Tools](https://github.com/Botspot/Pi-Power-Tools). This application is a suite of tools for creating and modifying Raspberry Pi OS disk-images and SD cards. This was the first application I made with a GUI interface.  
Pi Power Tools never became as popular as I had expected it to, so I took a step back and questioned **what people really *wanted***. Did they want a utility to create & manage operating systems with virtual machines? Apparently not.  
Then what did they want? **Desktop software.** In hindsight, I wonder how I missed it before - after all there are thousands (if not *millions*) of Raspberry Pi tutorials! The vast majority of these tutorials explain **how to install 3rd-party software on your Pi**. Unfortunately, most of these tutorials don't work anymore because they were written in the Raspbian Stretch era.  
I thought to myself, "*If only someone maintained a centralized collection of tutorials?* What if those tutorials had a 'Run script' button? And what if you could easily undo the changes it made with an 'Uninstall' button?"  
Thus, [Pi-Apps](https://github.com/Botspot/pi-apps) was born.  
In early 2020 it was a small application that I never imagined would see widespread use. But slowly, word spread through the community that there is finally a convenient alternative to tutorials. Soon it was added to [Twister OS](https://twisteros.com) and not long after, Pi-Apps was featured by all the large RPi YouTubers.  
Today, Pi-Apps has over 100 apps and likely serves over 500,000 users though it's hard to know for sure.  

It turns out Pi-Apps was just the beginning. Over time I found additional software niches that nothing else was filling:

- [YouTubuddy](https://github.com/Botspot/youtubuddy) - The private, lightweight YouTube search engine & player with the best hardware-acceleration available.
- [CloudBuddy](https://github.com/Botspot/cloudbuddy) - The ultimate way to manage your cloud storage on any Linux computer. This is a bash-powered GUI frontend for `rclone`, and includes built-in support for Google Drive, Dropbox, and Microsoft Onedrive. It's vastly more convenient than any web interface or tool available on any OS architecture.
- [Update Buddy](https://github.com/Botspot/update-buddy) - a sleek utility to run on startup. It runs `sudo apt update` in the background, and if any updates are found, it displays a non-intrusive notification, asking permission to upgrade.
- [Zoom](https://www.raspberrypi.org/forums/viewtopic.php?f=63&t=287680) - The popular video-chatting client had no easy way to install properly on Raspberry Pi. One other installation tool existed before mine, but that one did not install `pulseaudio` - a necessary utility if you wanted sound! Additionally, my version of the Zoom installer has Google account sign-in working.
- [WoR-flasher](https://github.com/Botspot/wor-flasher) - World's first Linux-compatible tool to install Windows 10 or 11 on a Raspberry Pi SD card. Before this tool existed, you had to use a Windows PC to install Windows 10 on a Pi's SD card, but with this tool, you now can use a Pi to do it all.
- [Windows Screensavers](https://github.com/Botspot/Screensavers) - An efficient GUI screensaver manager, preloaded with fourteen classic Windows screensavers that run smoothly on the RPi using Wine.
- [Windows 10 Theme](https://github.com/Botspot/Windows-10) - A complete transformation theme for Raspberry Pi OS, designed to look like Windows 10.
- [Chromium Widevine](https://github.com/Botspot/chromium-v84-widevine) - Watch Netflix and play other DRM-protected web-videos using the default Chromium. When Chromium 84 was released, it broke the previous DRM solution. I was the first to get it working, though there are plenty of copycats now.
- [Downgrade Chromium](https://www.raspberrypi.org/forums/viewtopic.php?f=63&t=308303) - The latest and greatest web browsers are not necessarily the best, or the fastest. This application allows you to easily switch versions of Chromium Browser.
- [Twister OS Updater](https://github.com/Botspot/TwistUP) - Twister OS's previous python-powered updating program was a nightmare to understand and maintain. I rewrote it in bash  and added some additional features, and it has proven to be far better than the previous patching program.
- UltiFlash - the world's most advanced and flexible imaging tool. This, by far, is the longest and most complicated bash script I've ever written, and it's not completely finished yet.
- [Scratch 2](https://github.com/Botspot/scratch2) - When Adobe Flash Player was deprecated, Scratch 2 was removed from all RPiOS systems through an apt update. This annoyed many people, so I found a way to bring it back and make it work again.
- Finally, I've written, or at least edited, all of the app-installers on [Pi-Apps](https://github.com/Botspot/pi-apps).

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Botspot&show_icons=true&hide_border=true&&count_private=true&include_all_commits=true" />

