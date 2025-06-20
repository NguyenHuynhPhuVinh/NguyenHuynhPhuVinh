sudo apt update

sudo apt upgrade -y

sudo apt install open-vm-tools-desktop -y

sudo add-apt-repository ppa:bamboo-engine/ibus-bamboo

sudo apt-get update

sudo apt-get install ibus-bamboo

sudo apt install curl

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash

\. "$HOME/.nvm/nvm.sh"

nvm install 22

sudo apt-get install git

------------------------------------------------------------------------------------

sudo su

mkdir /mnt/hgfs

nano /etc/fstab

vmhgfs-fuse /mnt/hgfs fuse defaults,allow_other,_netdev   0   0

(Ctrl + O|Enter|Ctrl + X)

exit

sudo reboot
