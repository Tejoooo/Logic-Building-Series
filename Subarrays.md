# 🌟 Subarrays & Substrings — Complete FREE Resource Pack

> A structured guide to understand, learn, and master **Subarrays** and **Substrings** in DSA.  
> Includes explanations, problem patterns, practice problems, and free video + article resources.

---

## 🧩 1. What Are Subarrays and Substrings?

### 🔹 Subarray:
A **subarray** is a *contiguous* part of an array.  
It is defined by a starting index `i` and an ending index `j` where `0 ≤ i ≤ j < n`.

**Example:**  
Array → `[1, 2, 3]`  
Subarrays → `[1]`, `[2]`, `[3]`, `[1, 2]`, `[2, 3]`, `[1, 2, 3]`

> Total subarrays = `n * (n + 1) / 2`

---

### 🔹 Substring:
A **substring** is a *contiguous* part of a string.

**Example:**  
String → `"abc"`  
Substrings → `"a"`, `"b"`, `"c"`, `"ab"`, `"bc"`, `"abc"`

> Total substrings = `n * (n + 1) / 2`

---

## 🎯 2. How Questions Are Asked

### 💡 Common Subarray-Based Questions:
1. Find the sum of all subarrays  
2. Maximum/Minimum subarray sum (Kadane’s Algorithm)  
3. Count subarrays with a given sum  
4. Longest subarray with given properties (e.g., even sum, equal 0s & 1s, etc.)  
5. Sliding window questions on subarrays of fixed or variable length  

### 💡 Common Substring-Based Questions:
1. Count all substrings that meet a condition (e.g., all vowels, palindrome, etc.)  
2. Longest substring without repeating characters  
3. Count distinct substrings  
4. Longest palindromic substring  
5. Pattern matching (e.g., find substring occurrences)

---

## 🧠 3. Core Concepts to Master

- **Brute Force Approach:** Generate all subarrays/substrings using 2 loops.  
- **Prefix Sum / Prefix Hashing:** For efficient sum or hash-based problems.  
- **Sliding Window:** For fixed-length or constraint-based problems.  
- **Kadane’s Algorithm:** To find max subarray sum efficiently.  
- **HashMap / Set usage:** For checking uniqueness or frequency.  
- **Dynamic Programming:** For advanced substring questions (palindromes, etc.).

---

## 📚 4. Free Learning Resources

### 📘 Articles & Tutorials:
- [GeeksforGeeks – Subarrays Explained](https://www.geeksforgeeks.org/what-are-subarrays/)  
- [GeeksforGeeks – Substrings in Strings](https://www.geeksforgeeks.org/find-all-substrings-of-a-given-string/)  
- [LeetCode Explore Card: Arrays 101](https://leetcode.com/explore/learn/card/fun-with-arrays/)  
- [LeetCode Explore Card: Strings 101](https://leetcode.com/explore/learn/card/array-and-string/)  
- [CP-Algorithms (Prefix Sum and Hashing)](https://cp-algorithms.com/algebra/prefix-sums.html)

---

### 🎥 YouTube Playlists (All Free):
- 🔗 [Striver — Arrays & Subarrays Series](https://www.youtube.com/playlist?list=PLgUwDviBIf0rBT8io74a95xT-hDFZonNs)
- 🔗 [TakeUForward — Strings & Substrings](https://www.youtube.com/playlist?list=PLgUwDviBIf0pMFMWuuvDNMAkoQFi-hyN3)
- 🔗 [Code with Harry — DSA Basics](https://www.youtube.com/watch?v=RBSGKlAvoiM)
- 🔗 [Apna College — Arrays + Strings](https://www.youtube.com/watch?v=37E9ckMDdTk)
- 🔗 [NeetCode — Sliding Window Patterns](https://www.youtube.com/watch?v=MK-NZ4hN7rs)

---

## 💻 5. Practice Problems (with Links)

### 🟢 Easy
1. [Maximum Subarray (Kadane’s Algorithm) – LeetCode #53](https://leetcode.com/problems/maximum-subarray/)  
2. [Find Pivot Index – LeetCode #724](https://leetcode.com/problems/find-pivot-index/)  
3. [Subarray Sum Equals K – LeetCode #560](https://leetcode.com/problems/subarray-sum-equals-k/)  
4. [Longest Common Prefix – LeetCode #14](https://leetcode.com/problems/longest-common-prefix/)  
5. [Reverse String – LeetCode #344](https://leetcode.com/problems/reverse-string/)

---

### 🟡 Medium
1. [Longest Substring Without Repeating Characters – LeetCode #3](https://leetcode.com/problems/longest-substring-without-repeating-characters/)  
2. [Minimum Size Subarray Sum – LeetCode #209](https://leetcode.com/problems/minimum-size-subarray-sum/)  
3. [Longest Palindromic Substring – LeetCode #5](https://leetcode.com/problems/longest-palindromic-substring/)  
4. [Binary Subarrays With Sum – LeetCode #930](https://leetcode.com/problems/binary-subarrays-with-sum/)  
5. [Subarray Product Less Than K – LeetCode #713](https://leetcode.com/problems/subarray-product-less-than-k/)

---

### 🔴 Hard
1. [Count Different Palindromic Subsequences – LeetCode #730](https://leetcode.com/problems/count-different-palindromic-subsequences/)  
2. [Substring with Concatenation of All Words – LeetCode #30](https://leetcode.com/problems/substring-with-concatenation-of-all-words/)  
3. [Maximum Sum Circular Subarray – LeetCode #918](https://leetcode.com/problems/maximum-sum-circular-subarray/)  
4. [Longest Substring with At Most K Distinct Characters – LeetCode #340](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/)  
5. [Count Subarrays with Median K – LeetCode #2488](https://leetcode.com/problems/count-subarrays-with-median-k/)

---

## 🧩 6. Common Patterns to Identify
| Pattern Type | Example Problem | Technique |
|---------------|-----------------|------------|
| Fixed Window | Minimum size subarray sum | Sliding window |
| Variable Window | Longest substring w/o repeating chars | Sliding window + HashSet |
| Max/Min Sum | Maximum subarray | Kadane’s Algorithm |
| Counting | Subarray sum equals K | Prefix sum + HashMap |
| Palindrome | Longest palindromic substring | Expand around center / DP |

---

## ⚙️ 7. Practice Plan

| Day | Topic | Goal |
|-----|--------|------|
| Day 1 | Basics of Subarrays | Understand brute force and prefix sums |
| Day 2 | Kadane’s Algorithm | Solve 2 problems |
| Day 3 | Sliding Window | Learn fixed and variable window types |
| Day 4 | Substrings | Work on string-based patterns |
| Day 5 | Mixed Practice | Combine array + string logic |

---

## 🚀 8. Pro Tips

- Always draw out indices and windows for clarity.  
- Prefix sums and hashmaps are lifesavers for sum-related subarray problems.  
- For strings, mastering the **sliding window** is essential.  
- Rehearse your dry-run explanation — it’s often asked in interviews.

---

## 🧾 Summary

| Concept | Key Focus |
|----------|------------|
| Subarray | Contiguous numbers within an array |
| Substring | Contiguous characters within a string |
| Core Skills | Sliding Window, Prefix Sum, Kadane’s Algorithm, DP |
| Applications | Searching, optimization, pattern detection |

---

**Author:** ✨ *Tejo’s DSA Learning Notes*  
**Last Updated:** October 2025  
**License:** Free for personal learning use  
