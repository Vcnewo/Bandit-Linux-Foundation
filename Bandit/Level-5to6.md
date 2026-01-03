
# Bandit Level 5 -> 6

## Goal 

The password for the next level is stored in a file somewhere under the inhere directory and has all of the 
following properties:

   human-readable
   1033 bytes in size
   not executable

## Concepts Used

- file navigation
- Permissions

## Commands Used 

- find

this command helps find files or directory and with flags can add more details on the specications of what were 
looking for

## Solution:

- find . -type f -size 1033c !-executable

 
