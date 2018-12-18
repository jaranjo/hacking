# Bandit Level 3
## Level Goal

The password for the next level is stored in a file called `spaces in this filename` located in the home directory.

Steps: 
1. Open a terminal and enter `ssh bandit2@bandit.labs.overthewire.org -p 2220`.
1. When prompted for a password, enter the password obtained from the completion of the previous level.
1. To open a filename with spaces, you must escape them with a backslash `\`. 
1. `cat spaces\ in\ this\ filename`
1. Copy and/or save the password printed to stdout. 
