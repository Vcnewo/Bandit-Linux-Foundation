
# Bandit Level 2 -> 3

##Goal

Read the password by accessing the file given in the directory were working the file is named"--space in the files"

## Concepts Used

- File accessing 
- Proper file naming

## Commands used 

- cat 

Used to read files on the terminal 

## Solution: 

- cat ./--space\ in\ the\ files--

when we try to access a file and it's name has spaces, if a space is added when writing it the command will act
as if it's trying to open two different files one after the other

for example:  cat jingle bell (this command will try to open a file called jingle and then a file called bell in the directory )

To avoid that misunderspanding you have to add a backslash(\) before and add the space after.

