# Bandit Level 12
## Level Goal

The password for the next level is stored in the file `data.txt`, where all lowercase (a-z) and uppercase (A-Z) letters have been rotated by 13 positions.

Steps:
1. `ls -l`
1. `cat data.txt`
1. `man tr`
1. `cat data.txt | tr '[A-Za-z]' [N-ZA-Mn-za-m]'`
