# Bandit Level 11 - 12 

## Goal 

The password for the next level is stored in the file data.txt, where all lowercase (a-z) and uppercase (A-Z) letters
 have been rotated by 13 positions

## Concepts Used 

- Character substitution (ROT13)

- Piping command output

## Commands Used for the Solution 

- |(pipe operator) 

- tr 
 
tr is a command used to translate, substitute or delete characters from a standard input

## Solution:

-cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'

in this solution we have rotated the order of the alphabet by 13 position the first letter that should be A is now
N and onward everyother letter with be changed by the 13th letter after it.
