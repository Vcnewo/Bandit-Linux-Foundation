# Bandit Level 8 - 9 

## Goal 
In the a file give called dat.txt find the line of text that is only written once and is not duplicated, that text
will be the password of Bandit9

## Concepts Used 

- File Navigation
- Research of contents in a file with specifications

## Commands Used for the Solution 
 
- uniq -u 

uniq only removes duplicates that are adjacent(after eachother) so that they are mentioned onced and the flag -u 
helps to remove all the lines that are not written once and have dupliccates

- sort

sort halps organize a file and put them in order alphabetical or number, in our case it was to put all the lines 
that were the same after each other so that uniq could catch the

- | (pipe)

helps send the output of a command to be used with another command, since we can't run sort and uniq at the same 
time we need to pipe the output of the sorted file to the command uniq -u to find the unique line.

## solution of the level

sort data.txt | uniq -u
