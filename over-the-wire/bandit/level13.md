# Bandit Level 13
## Level Goal
The password for the next level is stored in the `file data.txt`, which is a hexdump of a file that has been repeatedly compressed. 
For this level it may be useful to create a directory under `/tmp` in which you can work using `mkdir`. 
For example: `mkdir /tmp/myname123`. Then copy the datafile using `cp`, and rename it using `mv` (read the manpages!).

Steps:
1. `ls -l`
1. `mkdir /tmp/decoded`
1. `cp data.txt /tmp/decoded`
1. `cd /tmp/decoded`
1. `file data.txt`
1. `xxd -r data.txt > temp`
1. `file temp`
1. `mv temp temp.gz`
1. `gunzip temp.gz`
1. `ls`
1. `file temp`
1. `man bzip2`
1. `ls`
1. `file temp.out`
1. `mv temp.out temp.gz`
1. `gunzip temp.gz`
1. `ls`
1. `file temp`
1. `man tar`
1. `ls`
1. `file data5.bin`
1. `tar xvf data5.bin`
1. `file data6.bin`
1. `bzip2 -d data6.bin`
1. `file data6.bin.out`
1. `tar xvf data6.bin.out`
1. `file data8.bin`
1. `mv data8.bin temp.gz`
1. `ls`
1. `file temp`
1. `cat temp`
