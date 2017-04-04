# leetcode locked problems

- 156  
Given a binary tree where all the right nodes are either leaf nodes with a sibling (a left node that shares the same parent node) or empty,  
flip it upside down and turn it into a tree where the original right nodes turned into left leaf nodes. Return the new root.  

- 157  
The API: int read4(char *buf) reads 4 characters at a time from a file.  
The return value is the actual number of characters read. For example, it returns 3 if there is only 3 characters left in the file.  
By using the read4 API, implement the function int read(char *buf, int n) that reads n characters from the file.  

- 158  
The API: int read4(char *buf) reads 4 characters at a time from a file.  

The return value is the actual number of characters read. For example, it returns 3 if there is only 3 characters left in the file.  

By using the read4 API, implement the function int read(char *buf, int n) that reads n characters from the file.  

- 159
Given a string, find the length of the longest substring T that contains at most 2 distinct characters.  

For example, Given s = “eceba”,  

T is "ece" which its length is 3.  


- 161  
Given two strings S and T, determine if they are both one edit distance apart.  

- 163  
Given a sorted integer array where the range of elements are in the inclusive range [lower, upper], return its missing ranges.  

For example, given [0, 1, 3, 50, 75], lower = 0 and upper = 99, return ["2", "4->49", "51->74", "76->99"].  

- 170  
Design and implement a TwoSum class. It should support the following operations: add and find.  

add - Add the number to an internal data structure.  
find - Find if there exists any pair of numbers which sum is equal to the value.  

- 186  
Given an input string, reverse the string word by word. A word is defined as a sequence of non-space characters.  

The input string does not contain leading or trailing spaces and the words are always separated by a single space.  

For example,  
Given s = "the sky is blue",  
return "blue is sky the".  

Could you do it in-place without allocating extra space?  

- 243  
Given a list of words and two words word1 and word2, return the shortest distance between these two words in the list.  

For example,  
Assume that words = ["practice", "makes", "perfect", "coding", "makes"].  

Given word1 = “coding”, word2 = “practice”, return 3.  
Given word1 = "makes", word2 = "coding", return 1.  


- 244  
This is a follow up of Shortest Word Distance. The only difference is now you are given the list of words and your method will be called repeatedly many times with different parameters. How would you optimize it?  

Design a class which receives a list of words in the constructor, and implements a method that takes two words word1 and word2 and return the shortest distance between these two words in the list.  

For example,  
Assume that words = ["practice", "makes", "perfect", "coding", "makes"].  

Given word1 = “coding”, word2 = “practice”, return 3.  
Given word1 = "makes", word2 = "coding", return 1.  

- 245
This is a follow up of Shortest Word Distance. The only difference is now word1 could be the same as word2.  

Given a list of words and two words word1 and word2, return the shortest distance between these two words in the list.  

word1 and word2 may be the same and they represent two individual words in the list.  

For example,  
Assume that words = ["practice", "makes", "perfect", "coding", "makes"].  

Given word1 = “makes”, word2 = “coding”, return 1.  
Given word1 = "makes", word2 = "makes", return 3.  

Note:  
You may assume word1 and word2 are both in the list.  

- 246
A strobogrammatic number is a number that looks the same when rotated 180 degrees (looked at upside down).  

Write a function to determine if a number is strobogrammatic. The number is represented as a string.  

For example, the numbers "69", "88", and "818" are all strobogrammatic.  


- 247  
A strobogrammatic number is a number that looks the same when rotated 180 degrees (looked at upside down).  

Find all strobogrammatic numbers that are of length = n.  

For example,  
Given n = 2, return ["11","69","88","96"].  

- 248
A strobogrammatic number is a number that looks the same when rotated 180 degrees (looked at upside down).  

Write a function to count the total strobogrammatic numbers that exist in the range of low <= num <= high.  

For example,  
Given low = "50", high = "100", return 3. Because 69, 88, and 96 are three strobogrammatic numbers.  


- 249  
Given a string, we can "shift" each of its letter to its successive letter, for example: "abc" -> "bcd". We can keep "shifting" which forms the sequence:



- 250  
Given a binary tree, count the number of uni-value subtrees.  

A Uni-value subtree means all nodes of the subtree have the same value.  

- 251
Implement an iterator to flatten a 2d vector.  

- 252
Given an array of meeting time intervals consisting of start and end times [[s1,e1],[s2,e2],...] (si < ei), determine if a person could attend all meetings.  

For example,  
Given [[0, 30],[5, 10],[15, 20]],  
return false.  


- 253
Given an array of meeting time intervals consisting of start and end times [[s1,e1],[s2,e2],...] (si < ei), find the minimum number of conference rooms required.  

For example,  
Given [[0, 30],[5, 10],[15, 20]],  
return 2.  

