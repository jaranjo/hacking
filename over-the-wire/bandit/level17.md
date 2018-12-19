# Bandit Level 17
## Level Goal
The credentials for the next level can be retrieved by submitting the password of the current level to a port on `localhost` in the range 31000 to 32000.
First find out which of these ports have a server listening on them. 
Then find out which of those speak SSL and which don’t. 
There is only 1 server that will give the next credentials, the others will simply send back to you whatever you send to it.

Steps: 
1. `man nmap`
1. `nmap -p 31000-32000 localhost`
1. `openssl s_client -ign_eof -connect localhost:31790`
1. Enter Level 16 password.
1. `mkdir /tmp/jaranjo`
1. Copy and paste the SSH key from the output of the `openssl` command into a file (I called mine `keys.txt`.)
1. `chmod 600 keys.txt`
1. `ssh -i keys.txt bandit17@localhost`
1. Enter "yes"
1. `cat /etc/bandit_pass/bandit17`
