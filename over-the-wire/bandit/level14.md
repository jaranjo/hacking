# Bandit Level 14
## Level Goal

The password for the next level is stored in `/etc/bandit_pass/bandit14` and can only be read by user `bandit14`. 
For this level, you don’t get the next password, but you get a private SSH key that can be used to log into the next level. 
Note: localhost is a hostname that refers to the machine you are working on.

Steps:
1. `ls`
1. `cat sshkey.private`
1. `ssh -i sshkey.private bandit14@localhost`
1. `cat /etc/bandit_pass/bandit14`
