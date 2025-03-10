---
title: Setting up Mainsail
layout: home
---


<h1>Configuring Mainsail and KIAUH</h1>

<h2>Option 1 : Raspbery Pi Imager</h2>
<h4>The easiest option is to use raspberry pi imager, allowing most packages to be already installed<br>
Start by going to [Raspberry Pi Imager]https://www.raspberrypi.com/software/ and download the version that suits your machine.</h4>
<image src="Images/rp_imager_ss1.png">
<h4>Select your make of pi (In this case pi 3) and choose mainsail os <br> This can be found in: Other specific-perpose os -> 3D Printing -> Mainsail OS
<br>Once you select your micro sd card, add a hostname, user, wifi details and enable SSH in the 2nd tab. <br>SSH allows us to remotely access the pi and configure communication with Moonraker
<br>Once it is finished flashed, take out the micro sd card from your device and place it into your pi and attach power</h4>

<h3>Step 2</h3>
<h4>Install PuTTy and run it, open it up and enter the hostname that you put into your pi. You should have a terminal opened up and enter your username and password.
<br>Once logged in, we are installing Klipper Installation and Update Helper (KIAUH).
<br>To install, write these 3 commands into the console
<br>sudo apt-get update && sudo apt-get install git -y
<br>cd ~ && git clone https://github.com/dw-0/kiauh.git
<br>./kiauh/kiauh.sh</h4>
----
