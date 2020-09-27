# PiHole_Setup


touch ssh

$ ssh pi@raspberrypi.local
Press enter / answer yes to the prompts.  When asked for a password,  raspberry is the default.

$ sudo apt-get update && sudo apt-get upgrade -y 

$ passwd

$ curl -sSL https://install.pi-hole.net | bash
