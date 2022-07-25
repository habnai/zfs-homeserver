#zfs-homeserver
A full server for your home using ZFS, Docker &amp; Ansible for setup.
# Installation
sudo apt install git ansible
git clone https://github.com/habnai/zfs-homeserver.git
cd docker-zfs-homeserver/ansible
// udpate the variables in the ./vars/main_vars.yml file to your liking
ansible-playbook setup_playbook.yml -K

# Running services
docker-compose -f /path/to/yaml/file --env /path/to/.env/file up -d


