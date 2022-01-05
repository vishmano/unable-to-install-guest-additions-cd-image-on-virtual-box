# unable-to-install-guest-additions-cd-image-on-virtual-box
https://askubuntu.com/questions/573596/unable-to-install-guest-additions-cd-image-on-virtual-box

Assume your host operating system is Mac OS X and you have installed Ubuntu as the guest operating system.

There is no need to mount the guest additions ISO and install from it if your guest OS is Ubuntu.

Instead, open a terminal and enter the following:
 
 sudo apt-get install virtualbox-guest-utils**
