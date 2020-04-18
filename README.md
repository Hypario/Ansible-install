# What is this ?

This project is an ansible playbook allowing me to make a PHP server quickly including :



- setting up a firewall using ufw
- setting up all the tools I'm using (fish, vim, git)
- installing and setting up PHP
- installing and setting up MySQL (It may change for PgSQL)
- installing and setting up NGINX



# How to use

Just use the command `ansible-playbook -k -i hosts install.yml`

It will ask use the install.yml which describe all ansible need to do, using the hosts file which contains the host and name of the user in the server

Note: the hosts file will soon be remove in order to use the /etc/ansible/hosts file instead
