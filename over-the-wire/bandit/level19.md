# Bandit Level 19
## Level Goal
The password for the next level is stored in a file `readme` in the homedirectory. 
Unfortunately, someone has modified `.bashrc` to log you out when you log in with `SSH`.

Steps:
1. `ssh -t bandit18@bandit.labs.overthewire.org -p 2220 /bin/sh`
1. `ls`
1. `cat readme`
