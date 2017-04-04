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

- 379  
Design a Phone Directory which supports the following operations:  

1. get: Provide a number which is not assigned to anyone.  
2. check: Check if a number is available or not.  
3. release: Recycle or release a number.  

- 408  
Given a non-empty string s and an abbreviation abbr, return whether the string matches with the given abbreviation.  


- 411  
Given a target string and a set of strings in a dictionary, find an abbreviation of this target string with the smallest possible length such that it does not conflict with abbreviations of the strings in the dictionary.  

Each number or letter in the abbreviation is considered length = 1. For example, the abbreviation "a32bc" has length = 4.  
- 418  
Given a rows x cols screen and a sentence represented by a list of non-empty words, find how many times the given sentence can be fitted on the screen.  


- 422  
Given a sequence of words, check whether it forms a valid word square.  

A sequence of words forms a valid word square if the kth row and column read the exact same string, where 0 ≤ k < max(numRows, numColumns).  
- 425  
Given a set of words (without duplicates), find all word squares you can build from them.  

A sequence of words forms a valid word square if the kth row and column read the exact same string, where 0 ≤ k < max(numRows, numColumns).  

- 439  
Given a string representing arbitrarily nested ternary expressions, calculate the result of the expression. You can always assume that the given expression is valid and only consists of digits 0-9, ?, :, T and F (T and F represent True and False respectively).  

- 444  
Check whether the original sequence org can be uniquely reconstructed from the sequences in seqs. The org sequence is a permutation of the integers from 1 to n, with 1 ≤ n ≤ 104. Reconstruction means building a shortest common supersequence of the sequences in seqs (i.e., a shortest sequence so that all sequences in seqs are subsequences of it). Determine whether there is only one sequence that can be reconstructed from seqs and it is the org sequence.


- 465
A group of friends went on holiday and sometimes lent each other money. For example, Alice paid for Bill's lunch for $10. Then later Chris gave Alice $5 for a taxi ride. We can model each transaction as a tuple (x, y, z) which means person x gave person y $z. Assuming Alice, Bill, and Chris are person 0, 1, and 2 respectively (0, 1, 2 are the person's ID), the transactions can be represented as [[0, 1, 10], [2, 0, 5]].  

Given a list of transactions between a group of people, return the minimum number of transactions required to settle the debt.  
- 469  
Given a list of points that form a polygon when joined sequentially, find if this polygon is convex

- 471   
Given a non-empty string, encode the string such that its encoded length is the shortest.  

The encoding rule is: k[encoded_string], where the encoded_string inside the square brackets is being repeated exactly k times.  

Note:  
k will be a positive integer and encoded string will not be empty or have extra space.
You may assume that the input string contains only lowercase English letters. The string's length is at most 160.
If an encoding process does not make the string shorter, then do not encode it. If there are several solutions, return any of them is fine.   
- 484  
By now, you are given a secret signature consisting of character 'D' and 'I'. 'D' represents a decreasing relationship between two numbers, 'I' represents an increasing relationship between two numbers. And our secret signature was constructed by a special integer array, which contains uniquely all the different number from 1 to n (n is the length of the secret signature plus 1). For example, the secret signature "DI" can be constructed by array [2,1,3] or [3,1,2], but won't be constructed by array [3,2,4] or [2,1,3,4], which are both illegal constructing special string that can't represent the "DI" secret signature.  

On the other hand, now your job is to find the lexicographically smallest permutation of [1, 2, ... n] could refer to the given secret signature in the input.  

- 487  
Given a binary array, find the maximum number of consecutive 1s in this array if you can flip at most one 0.   

- 490
- 499  
- 505


- 527  
Given an array of n distinct non-empty strings, you need to generate minimal possible abbreviations for every word following rules below.  
1. Begin with the first character and then the number of characters abbreviated, which followed by the last character.  
2. If there are any conflict, that is more than one words share the same abbreviation, a longer prefix is used instead of only the first character until making the map from word to abbreviation become unique. In other words, a final abbreviation cannot map to more than one original words.  
3. If the abbreviation doesn't make the word shorter, then keep it as original.  

- 531  
Given a picture consisting of black and white pixels, find the number of black lonely pixels.  

The picture is represented by a 2D char array consisting of 'B' and 'W', which means black and white pixels respectively.  

A black lonely pixel is character 'B' that located at a specific position where the same row and same column don't have any other black pixels.  

- 533  
Given a picture consisting of black and white pixels, and a positive integer N, find the number of black pixels located at some specific row R and column C that align with all the following rules:  

1. Row R and column C both contain exactly N black pixels.  
2. For all rows that have a black pixel at column C, they should be exactly the same as row R  
The picture is represented by a 2D char array consisting of 'B' and 'W', which means black and white pixels respectively.   

- 536  
You need to construct a binary tree from a string consisting of parenthesis and integers.  

The whole input represents a binary tree. It contains an integer followed by zero, one or two pairs of parenthesis. The integer represents the root's value and a pair of parenthesis contains a child binary tree with the same structure.  

You always start to construct the left child node of the parent first if it exists.  

- 544  
During the NBA playoffs, we always arrange the rather strong team to play with the rather weak team, like make the rank 1 team play with the rank nth team, which is a good strategy to make the contest more interesting. Now, you're given n teams, you need to output their final contest matches in the form of a string.  

The n teams are given in the form of positive integers from 1 to n, which represents their initial rank. (Rank 1 is the strongest team and Rank n is the weakest team.) We'll use parentheses('(', ')') and commas(',') to represent the contest team pairing - parentheses('(' , ')') for pairing and commas(',') for partition. During the pairing process in each round, you always need to follow the strategy of making the rather strong one pair with the rather weak one.  

- 545
Given a binary tree, return the values of its boundary in anti-clockwise direction starting from root. Boundary includes left boundary, leaves, and right boundary in order without duplicate nodes.  

Left boundary is defined as the path from root to the left-most node. Right boundary is defined as the path from root to the right-most node. If the root doesn't have left subtree or right subtree, then the root itself is left boundary or right boundary. Note this definition only applies to the input binary tree, and not applies to any subtrees.  

The left-most node is defined as a leaf node you could reach when you always firstly travel to the left subtree if exists. If not, travel to the right subtree. Repeat until you reach a leaf node.  

The right-most node is also defined by the same way with left and right exchanged.  

- 548  
Given an array with n integers, you need to find if there are triplets (i, j, k) which satisfies following conditions:   

0 < i, i + 1 < j, j + 1 < k < n - 1  
Sum of subarrays (0, i - 1), (i + 1, j - 1), (j + 1, k - 1) and (k + 1, n - 1) should be equal.  
where we define that subarray (L, R) represents a slice of the original array starting from the element indexed L to the element indexed R.  

