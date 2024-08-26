## EXPERIMENT 1 - Introduction to Python Programming
Hello! This repository contains Python codes I made for my ECE2112 course. 

1. Alphabet Soup Problem

#Program to ask the user for input, rearrange it alphabetically, and print.
def alphabet_soup():

#Asks the user for input and removes case sensitivity
    word = input("Enter a word and it will be sorted alphabetically: ").lower()

#Sorts and joins the word/characters into a string 
    sorted_word = ''.join(sorted(word))

#Returns the sorted characters to the caller.
    return sorted_word

#Calls the defined function and then prints.
print(alphabet_soup())
