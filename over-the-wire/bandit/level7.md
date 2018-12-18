# Bandit Level 7
## Level Goal
The password for the next level is stored somewhere on the server and has all of the following properties:

* owned by user bandit7
* owned by group bandit6
* 33 bytes in size

Steps:
1. `find / -user bandit7 -group bandit6 -size 33c`
1. `cat /var/lib/dpkg/info/bandit7.password`
