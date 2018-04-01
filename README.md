# linuxshortcuts
# Set up ssh login:
1. ssh manually into host first time
2. sshpass -p <password> ssh username@hostname


# Enable copy-paste on ubuntu VM from host windows
https://askubuntu.com/questions/22743/how-do-i-install-guest-additions-in-a-virtualbox-vm
sudo apt update
sudo apt-get install virtualbox-guest-dkms.
then restart ubuntu
Then: sudo apt-get install virtualbox-guest-x11

Install any dependencies
Then VBoxClient --clipboard
As per this link:  https://askubuntu.com/questions/63420/how-to-fix-virtualboxs-copy-and-paste-to-host-machine
