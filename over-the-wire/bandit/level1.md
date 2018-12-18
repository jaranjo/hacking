# Bandit Level 1
## Level Goal
The password for the next level is stored in a file called readme located in the home directory. 
Use this password to log into bandit1 using SSH. 
Whenever you find a password for a level, use SSH (on port 2220) to log into that level and continue the game.

Steps:
1. Enter: `ssh bandit0@bandit.labs.overthewire.org -p 2220`
1. When prompted for a password, enter: `bandit0`
1. `ls`
1. `cat readme`
1. Copy the password from `readme` onto your clipboard; save for moving to level 2. 
