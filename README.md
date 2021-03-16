This is a example playbook for advanced networking class

The playbook is to install a lamp stack application Nextcloud on a centos stream 8 Machine. installation is based on instructions from https://docs.nextcloud.com/server/latest/admin_manual/installation/example_centos.html as a base.

Setup

1. Install python3 and python3-pip on both server and client
2. pip3 install ansible # to get the latest version of ansible
3. ssh-keygen # create keyshare pair on client
4. ssh-copy-id [serveripaddress] # send and authorize ssh key on server
5. nano inventory.yml and change/add ip address of server
6. ansible-playbook playbook.yml # run playbook
