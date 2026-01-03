
# Bandit Level 1 -> 2

## Goal 
Find the password of bandit2 in the file given in the system which is names with a hyphen (-)

## Concepts Used

- File accessing
- working directory
 
## Command Used 

- cat 

Cat (concatonate) allows to read a file in the terminal, but doesn't allow to modify it

## Solution:

- cat ./-

hyphen (-) has a lot of meanings in linux so trying to directly open the file gave using (cat -) error, so to
clarify that we're trying to reach the file we have to mention the directory we're working in and give the name
of the file being -.
