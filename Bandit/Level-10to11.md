# Bandit Level 10 - 11 

## Goal 

The password for the next level is stored in the file data.txt, which contains base64 encoded data

## Concepts Used 

- File Navigation
- File decoding

## Commands Used for the Solution 

- base64 -d

base64 is a commande used to encode or decode content into base64 format with the flag -d the commande will decode
the content of the file specified after the command if the content is in base64
## Solution:

base64 -d data.txt
