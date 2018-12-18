# Bandit Level 10
## Level Goal
The password for the next level is stored in the file `data.txt` in one of the few human-readable strings, beginning with several `‘=’` characters.

Steps:
1. `ls -l`
1. `strings data.txt | grep "====="`
