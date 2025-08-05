# DSA Practice Problems

## Arrays and Hashing

### 1. Two Sum  
**Type**: Hashing  
**Input**: `nums = [2, 7, 11, 15], target = 9`  
**Output**: `[0, 1]` (because `nums[0] + nums[1] == 9`)  
**Goal**: Use a hash map for O(n) solution  

### 2. Find Duplicate Number  
**Type**: Floyd’s Tortoise and Hare (cycle detection) or HashSet  
**Input**: `nums = [1,3,4,2,2]`  
**Output**: `2`  

## Strings and Hashing

### 3. Valid Anagram  
**Type**: Hash map or frequency counter  
**Input**: `s = "anagram", t = "nagaram"`  
**Output**: `True`  

### 4. Group Anagrams  
**Type**: Hash map with sorted keys  
**Input**: `["eat", "tea", "tan", "ate", "nat", "bat"]`  
**Output**: `[["bat"],["nat","tan"],["ate","eat","tea"]]`  

## Sliding Window

### 5. Maximum Subarray Sum of Size K  
**Type**: Sliding Window  
**Input**: `arr = [2,1,5,1,3,2], k = 3`  
**Output**: `9` (5+1+3)  

### 6. Longest Substring Without Repeating Characters  
**Type**: Sliding Window + HashSet  
**Input**: `s = "abcabcbb"`  
**Output**: `3` ("abc")  

## Stack and Queue

### 7. Valid Parentheses  
**Type**: Stack  
**Input**: `s = "({[]})"`  
**Output**: `True`  

### 8. Daily Temperatures  
**Type**: Monotonic Stack  
**Input**: `temps = [73,74,75,71,69,72,76,73]`  
**Output**: `[1,1,4,2,1,1,0,0]`  

## Binary Search

### 9. Binary Search on Sorted Array  
**Type**: Classic binary search  
**Input**: `nums = [-1,0,3,5,9,12], target = 9`  
**Output**: `4`  

## Trees or Linked Lists (Pick One Area for Depth)

### 10. Invert a Binary Tree  
**Type**: Recursion / DFS  
**Input**: A binary tree  
**Output**: Mirror image of the tree  
**Practice**: Pre-order or level-order traversal  
