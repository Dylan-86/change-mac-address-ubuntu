# change-mac-address-ubuntu

Instructions to change the MAC address on Ubuntu

Open terminal and run


lshw -C network
sudo ifconfig eth0 down (eth0 or eth1, whatever device mac you wanna change)
sudo ifconfig eth0 hw ether 00:00:00:00:00:00 (choose your mac here)
sudo ifconfig eth0 up


Remember to sign down first your real MAC address so that you can rever if needed.

