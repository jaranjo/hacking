# Bandit Level 16
## Level Goal
The password for the next level can be retrieved by submitting the password of the current level to port 30001 on `localhost` using SSL encryption.

Helpful note: Getting `“HEARTBEATING”` and `“Read R BLOCK”? Use -ign_eof and read the “CONNECTED COMMANDS”` section in the manpage. 
Next to ‘R’ and ‘Q’, the ‘B’ command also works in this version of that command…

Steps:
1. `man openssl`
1. `man s_client`
1. `openssl s_client -ign_eof -connect localhost:30001`
1. Enter the level 15 password.
