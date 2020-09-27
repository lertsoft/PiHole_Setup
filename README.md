# PiHole_Setup

If you don't have a wire connection to the router you might need to set up a wireless connection. To do so you need to create a [wpa_supplicant.conf](https://github.com/lertsoft/PiHole_Setup/blob/master/wpa_supplicant.conf) and write the script for the wireless connection as shown in the hyperlink.

Created an ssh file on the boot drive, so that the raspberry pi knows that it is activated.
This is so that I can configure all the setting on my laptop instead of having to connect the Raspberry pi to a screen.

  `$ touch ssh`


  `$ ssh pi@raspberrypi.local`
Press enter / answer yes to the prompts.  When asked for a password,  raspberry is the default.

  `$ sudo apt-get update && sudo apt-get upgrade -y`

  `$ passwd`

  `$ curl -sSL https://install.pi-hole.net | bash`
