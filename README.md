# CNA335_Magic8_PiProject


This is a very basic guide to set up a CUPS server on a Rasberri Pi. For this assignment we used a Rasberri Pi B for wireless capability as well as a usb cable.

CUPS-

1. sudo apt-get install cups - installs CUPS capability

2. Configure cups by changing the cupsd.conf file to allow local users at port 631

3. usermod -a -G Ipadmin pi - to give admin privileges to the user 'pi'

4. sudo cupsctl –remote-any - to allow all connections on the network

SAMBA-

1. Sudo apt-get install samba

2. Edit the samba.cnf file to allow guest access and to deny 'read-only' access

PRINTING-

1. Plug in raspberry pi into printer using an A/B cable

2. Access the pi by typing in ip-address of the pi followed by :631

3. Choose add and type in pi user and password.

4. Select printer and YOU CAN PRINT!

(See screenshots to verify functionality)