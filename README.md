# inverted-search-engine-c
Implementation of an Inverted Search Engine in C that indexes words from multiple files and enables efficient word-based search using data structures like linked lists and hashing.
# Inverted Search Engine in C

## Description
This project implements an Inverted Search Engine using the C programming language. 
The program reads multiple text files, extracts words, and creates an inverted index 
to efficiently search for words and display the files in which they appear.

## Features
- Read and process multiple text files
- Create an inverted index database
- Efficient word searching
- Display word occurrences and file details
- Update and save database
- Uses linked lists and hashing techniques

## Technologies Used
- C Programming
- Data Structures
- File Handling
- Linked Lists
- Hash Tables

## How It Works
1. The program reads multiple input files.
2. Words are extracted from the files.
3. An inverted index database is created.
4. Each word points to the files where it appears.
5. The user can search for words and retrieve file information.

## Example
Input files:

file1.txt  
file2.txt  

Search word:

example

Output:

Word found in:
file1.txt (3 times)
file2.txt (1 time)

## How to Compile

Use GCC:
