# Hash_Blaster

## Description
This project is intended to be a hash generator that saves the resulting hashes to a file. It will also be used as a way to give myself a deeper understanding of hashing functions.  
The user will be given a menu that allows them to choose the hashing function they want and then prompts for a string. This will repeat until the user chooses to back out.  
Users will also have the option to use a word list as an input.

## Users 
The idea behind this is to streamline the process of creating a large amount of hashed passwords to use when learning tools such as hashcat or john the ripper.  

## Design
Since I will be making the hashing functions myself rather than importing them, I will be relying on the general algorithms of these hashing functions to ensure my resulting hashes are accurate. I will also need to implement some form of file maniplation to allow the saving of these hashes. 