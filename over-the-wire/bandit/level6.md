# Bandit Level 6
## Level Goal
The password for the next level is stored in a file somewhere under the inhere directory and has all of the following properties:

* human-readable
* 1033 bytes in size
* not executable

1. `cd inhere`
1. `ls -Ual`
1. `find -type f -size 1033c`
1. `cat ./maybehere07/.file2
