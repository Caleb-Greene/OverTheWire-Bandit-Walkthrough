# OverTheWire Bandit Walkthrough & Writeup

~~~
      ,----..            ,----,          .---.
     /   /   \         ,/   .`|         /. ./|
    /   .     :      ,`   .'  :     .--'.  ' ;
   .   /   ;.  \   ;    ;     /    /__./ \ : |
  .   ;   /  ` ; .'___,/    ,' .--'.  '   \' .
  ;   |  ; \ ; | |    :     | /___/ \ |    ' '
  |   :  | ; | ' ;    |.';  ; ;   \  \;      :
  .   |  ' ' ' : `----'  |  |  \   ;  `      |
  '   ;  \; /  |     '   :  ;   .   \    .\  ;
   \   \  ',  /      |   |  '    \   \   ' \ |
    ;   :    /       '   :  |     :   '  |--"
     \   \ .'        ;   |.'       \   \ ;
  www. `---` ver     '---' he       '---" ire.org
~~~

## :book: Table of Contents
- :blue_book: [OverTheWire Bandit Description](#overthewire-bandit-description)
- :green_book: [Quick Start Guide](#quick-start-guide)
- :gear: [Level 0](#level-0)
- :gear: [Level 0 → Level 1](#level-0-→-level-1)
- :gear: [Level 1 → Level 2](#level-1-→-level-2)
- :gear: [Level 2 → Level 3](#level-2-→-level-3)
- :gear: [Level 3 → Level 4](#level-3-→-level-4)
  
## :book: OverTheWire Bandit Description
[OverTheWire](https://overthewire.org/wargames/) offers various wargames to help learners practice and apply security and hacking concepts in a hands-on and fun way. The Bandit wargame is for complete beginners to learn the basics of many different cybersecurity concepts. Each level progressively increases in difficulty, with the player having to solve new and more complicated challenges to progress. 

Each level also provides the player with a list of commands that the player may need to use to complete that level. This guide will provide descriptions of each command, but not to their full extent. If you would like to learn more about each command, I recommend reviewing either Ubuntu's Manpage or running ```man [command_name]``` in your Linux terminal, which will provide you with the documentation of the specified command.

## :book: Quick Start Guide
### Operating System (OS)
OverTheWire Bandit relies heavily upon the Linux terminal and Secure Shell (SSH) to navigate between levels and connect to the game's remote servers.

<img width="430" height="450" alt="image" src="https://github.com/user-attachments/assets/343d5d16-cace-4826-ade4-2c1116023eb9" /> 

While the SSH protocol can be used on other operating systems (Windows, MacOS), I STRONGLY recommend downloading Linux and running it inside a Virtual Machine (VM) for the best learning experience, as Linux is a valuable OS to learn in the realm of cybersecurity and hacking.

### Downloading & Running Linux
If you are unfamiliar with what Linux is, learn more [here](https://www.linux.com/what-is-linux/). The Linux operating system I will be focusing on is Kali Linux:

#### [Kali Linux](https://www.kali.org/)

<img width="889" height="500" alt="image" src="https://github.com/user-attachments/assets/bebee32a-b6f8-4751-964d-e5962916c580" />

The Quickest way to get Linux up and running on your computer on a VM is to install Oracle's VirtualBox and download Kali's Pre-built Virtual Machine distribution, which can be immediately run with VirtualBox with little to no setup.

1. Download VirtualBox on your computer [here](https://www.virtualbox.org/wiki/Downloads)
2. Download the Kali Pre-built Virtual Machine [here](https://www.kali.org/get-kali/#kali-virtual-machines), selecting the VirtualBox option.
3. Simply drag and drop the vbox file into VirtualBox and run the VM. (default username and password is kali)
