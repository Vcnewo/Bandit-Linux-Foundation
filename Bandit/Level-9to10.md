# Bandit Level 8 - 9 

## Goal 

The password for the next level is stored in the file data.txt in one of the few human-readable strings, preceded
 by several ‘=’ characters.

## Concepts Used 

- File Navigation

## Commands Used for the Solution 

- grep -a

grep is used to search for a specific label or text in a file that is human readable, however it doesn't work for
files that contain data and are not human readable, adding -a as flag let's grep serach in a binary file and other
none human readable file as if they were text files 
## Solution:

grep -a "=" data.txt
