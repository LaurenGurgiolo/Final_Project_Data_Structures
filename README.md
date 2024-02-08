# Final_Project_Data_Structures
 This is my final project from Udacity's course on data structures.

This course covered arrays and linked lists, stacks and queues, recursion, trees, maps, 
and hashing.

Problem 1: LRU Cache

For our first problem, the goal will be to design a data structure known as a Least Recently Used (LRU) cache. An LRU cache is a type of cache in which we remove the least recently used entry when the cache memory reaches its limit. 

Problem 2: File Recursion

For this problem, the goal is to write code for finding all files under a directory (and all directories beneath it) that end with ".c"

Here is an example of a test directory listing:

./testdir
./testdir/subdir1
./testdir/subdir1/a.c
./testdir/subdir1/a.h
./testdir/subdir2
./testdir/subdir2/.gitkeep
./testdir/subdir3
./testdir/subdir3/subsubdir1
./testdir/subdir3/subsubdir1/b.c
./testdir/subdir3/subsubdir1/b.h
./testdir/subdir4
./testdir/subdir4/.gitkeep
./testdir/subdir5
./testdir/subdir5/a.c
./testdir/subdir5/a.h
./testdir/t1.c
./testdir/t1.h

Problem 3: Huffman Coding

Phase I - Build the Huffman Tree
A Huffman tree is built in a bottom-up approach.
First, determine the frequency of each character in the message.

Phase II - Generate the Encoded Data
Based on the Huffman tree, generate unique binary code for each character of our string message. For this purpose, you'd have to traverse the path from root to the leaf node.

Phase III - Decode Data
Once we have the encoded data, and the (pointer to the root of) Huffman tree, we can easily decode the encoded data

Problem 4: Active Directory

In Windows Active Directory, a group can consist of user(s) and group(s) themselves. Write a function that provides an efficient look up of whether the user is in a group.

Problem 5: Blockchain

A Blockchain(opens in a new tab) is a sequential chain of records, similar to a linked list. Each block contains some information and how it is connected related to the other blocks in the chain. Each block contains a cryptographic hash of the previous block, a timestamp, and transaction data. For our blockchain we will be using a SHA-256(opens in a new tab) hash, the Greenwich Mean Time(opens in a new tab) when the block was created, and text strings as the data.

Use your knowledge of linked lists and hashing to create a blockchain implementation.

Problem 6: Union and Intersection

Your task for this problem is to fill out the union and intersection functions. The union of two sets A and B is the set of elements which are in A, in B, or in both A and B. For example, the union of A = [1, 2] and B = [3, 4] is [1, 2, 3, 4].

The intersection of two sets A and B, denoted by A ∩ B, is the set of all objects that are members of both sets A and B. For example, the intersection of A = [1, 2, 3] and B = [2, 3, 4] is [2, 3].

You will take in two linked lists and return a linked list that is composed of either the union or intersection, respectively. Once you have completed the problem you will create your own test cases and perform your own run time analysis on the code.

