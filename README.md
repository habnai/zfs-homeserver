
# zfs-homeserver
A full server for your home using ZFS, files &amp; Ansible for setup.

# Installation
sudo apt install git ansible

git clone https://github.com/habnai/zfs-homeserver.git

cd zfs-homeserver/ansible

// udpate the variables in the ./vars/main_vars.yml file to your liking

ansible-playbook setup_playbook.yml -K

