## Installing process

### Some research and decisions before installing

After some research ([Debian manuals](https://www.debian.org/doc/manuals/debian-faq/choosing.en.html)), I chose the stable version of the Debian distributions that were available as I'm a new user and I'm mainly going to use this machine on school work and not looking to bump into strange bugs or other confusing situations. If the software is too outdated I just need to work around that later. My hardware shouldn't be too new as this laptop was bought somewhere around 2015.

It took some time to decide which desktop to choose. I checked out [Debian user forum](https://forums.debian.net/viewtopic.php?t=156498) as well as watched plenty of videos on Debian, most of which mentioned a preferred desktop. Cinnamon seemed the easiest to approach so I decided to go with that. None of the options shouldn't be too heavy for my hardware.

I needed a flash drive, so I walked to the nearest department store and picked up a Maxwell 32 GB dual USB drive with USB-C and USB 3.0 connectors.

### The process

I used [Debian 12 Tutorial for Beginners - Installation & Setup [Cinnamon] by Linux Ort](https://www.youtube.com/watch?v=zOZEkzwhThc) Youtube video as a guide for the process. I downloaded the installer from [https://www.debian.org/download](https://www.debian.org/download). 

I used [BalenaEtcher](https://etcher.balena.io/) to use my USB stick for installing. I installed BalenaEtcher and did the following:

![image](https://github.com/user-attachments/assets/2eb49861-1807-4414-b575-21d4eaf9670e)

I ran into an issue. Once I selected the debian-12.7.0-amd64-netinst.iso file on Flash from file, it didn't proceed to Select target. Hovering over "select target" changes pointer to not-allowed. I found that someone else had had the same issue [here](https://github.com/balena-io/etcher/issues/4234) and decided to try another etcher. I installed Rufus from Windows store, and it seemed to work (it was in Finnish as my Windows' language is set to Finnish). It had the USB drive chosen, I selected the Debian file and then it had some questions, I selected yes/OK.

![image](https://github.com/user-attachments/assets/3d0e6ed7-0742-43b7-a333-05779ae3efa6)

![image](https://github.com/user-attachments/assets/02633f6d-84cc-4ae8-aa1d-e5f708169721)

![image](https://github.com/user-attachments/assets/226ee92c-0335-428c-b09b-2ebc8fcfd639)

![image](https://github.com/user-attachments/assets/be532222-f1d6-4365-818f-ccb0166b6fc4)

![image](https://github.com/user-attachments/assets/3cdcdcb2-b196-4dec-accf-18cfdbc5c88c)

It took around a minute and then it was ready. Then it was time to start the laptop from the USB stick.

