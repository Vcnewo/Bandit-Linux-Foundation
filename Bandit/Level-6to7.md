
# Bandit Level 6 -> 7 

## Goal 

 The password for the next level is stored somewhere on the server and has all of the following properties:

   owned by user bandit7
   owned by group bandit6
   33 bytes in size

## Concepts Used

- File navigation
- Permission specifications

## Command Used

- find

Used to find files or directories

## Solution:

- find -type f -user Bandit7 -group Bandit6 -size 1033c 2>/dev/null

For this command not only did we add the flags to the command to find specifically with the given owner, group 
and size of the file, however there were a lot of files that matched these conditions that were shown but also
gave an error message because their permission was denied, to filter out all those expected errors and files we
can't open the command have 2>/dev/null at the end to avoid seeing them. 
