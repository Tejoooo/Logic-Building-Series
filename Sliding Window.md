# Sliding Window DSA Practice – 20 Essential Problems

# Sliding Window Technique 🪟

## 📘 Overview
The Sliding Window technique is used to optimize problems that involve **subarrays or substrings** within an array or string.  
Instead of recomputing results for each possible subarray, we “slide” a window across the data to reuse previous computations.

---

## 🧩 Types of Sliding Windows

### 1. **Fixed-size Sliding Window**
Used when the **window length `k`** is constant.

Example problems:
- Maximum sum of a subarray of size `k`
- Average of each subarray of size `k`

**Key idea:**  
Keep track of the current window sum (or other metric) and adjust when the window slides.

---

### 2. **Variable-size Sliding Window**
Used when we need to find a subarray that satisfies a **condition**, and the window can expand or shrink dynamically.

Example problems:
- Longest substring without repeating characters
- Smallest subarray with sum ≥ target

**Key idea:**  
Use two pointers (`left`, `right`) to expand or contract the window based on constraints.

---

### 3. **Deque-based Sliding Window**
Used when we need to efficiently track **maximum/minimum** values within a window.

Example problems:
- Sliding Window Maximum
- First negative number in every window of size `k`

**Key idea:**  
Maintain a deque of elements in decreasing order of value (or increasing, depending on the problem).

---

## ⚙️ Steps to Solve Sliding Window Problems

1. Identify if it’s a **subarray/substring** problem.  
2. Check if the **window size** is fixed or variable.  
3. Use a **running window** (sum, count, hash map, deque, etc.) to maintain state.  
4. Slide the window and **update the result** dynamically.

---

## 🧠 Common Patterns

| Type | Example Problem | Key Data Structures |
|------|------------------|--------------------|
| Fixed | Max sum of subarray size k | sum variable |
| Variable | Longest substring without repeating characters | hash map or set |
| Deque-based | Sliding window maximum | deque |
| Counting | Count anagrams in string | frequency map |

---

## 💡 Complexity
- **Time Complexity:** O(n) — Each element enters and leaves the window once.  
- **Space Complexity:** O(k) or O(1), depending on window data structures.

---

## 🔥 Tip
If the question involves **"subarray"**, **"substring"**, **"window of size k"**, or **"minimum/maximum length satisfying condition"**,  
then it’s most likely a **Sliding Window** problem!


## 🧊 Fixed Size Sliding Window

1. [Maximum Sum Subarray of Size K (GFG)](https://www.geeksforgeeks.org/problems/max-sum-subarray-of-size-k5313/1)
2. [Maximum Average Subarray I (LeetCode 643)](https://leetcode.com/problems/maximum-average-subarray-i/)
3. [Maximum Sum Circular Subarray (LeetCode 918)](https://leetcode.com/problems/maximum-sum-circular-subarray/)
4. [Count Occurrences of Anagrams (GFG)](https://www.geeksforgeeks.org/problems/count-occurences-of-anagrams5839/1)
5. [Find All Anagrams in a String (LeetCode 438)](https://leetcode.com/problems/find-all-anagrams-in-a-string/)

## 🔄 Variable Size Sliding Window

6. [Longest Substring Without Repeating Characters (LeetCode 3)](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
7. [Longest Substring with At Most K Distinct Characters (LeetCode 340)](https://leetcode.com/problems/longest-substring-with-at-most-k-distinct-characters/)
8. [Fruit Into Baskets (LeetCode 904)](https://leetcode.com/problems/fruit-into-baskets/)
9. [Longest K Unique Characters Substring (GFG)](https://www.geeksforgeeks.org/problems/longest-k-unique-characters-substring0853/1)
10. [Subarrays with K Different Integers (LeetCode 992)](https://leetcode.com/problems/subarrays-with-k-different-integers/)

## 📉 Monotonic Deque / Maximum-Minimum in Window

11. [Sliding Window Maximum (LeetCode 239)](https://leetcode.com/problems/sliding-window-maximum/)
12. [First Negative Integer in Every Window of Size K (GFG)](https://www.geeksforgeeks.org/problems/first-negative-integer-in-every-window-of-size-k3345/1)
13. [Sum of Minimum and Maximum Elements of All Subarrays of Size K (GFG)](https://www.geeksforgeeks.org/problems/sum-of-minimum-and-maximum-elements-of-all-subarrays-of-size-k/0)

## 📊 Counting Patterns / Prefix Sliding

14. [Subarray Product Less Than K (LeetCode 713)](https://leetcode.com/problems/subarray-product-less-than-k/)
15. [Minimum Window Substring (LeetCode 76)](https://leetcode.com/problems/minimum-window-substring/)
16. [Smallest Subarray with Sum Greater Than X (GFG)](https://www.geeksforgeeks.org/problems/smallest-subarray-with-sum-greater-than-x5651/1)
17. [Longest Subarray with Sum K (GFG)](https://www.geeksforgeeks.org/problems/longest-sub-array-with-sum-k0809/1)

## 🎯 Bit Manipulation / Harder Variants

18. [Max Consecutive Ones III (LeetCode 1004)](https://leetcode.com/problems/max-consecutive-ones-iii/)
19. [Longest Repeating Character Replacement (LeetCode 424)](https://leetcode.com/problems/longest-repeating-character-replacement/)
20. [Binary Subarrays With Sum (LeetCode 930)](https://leetcode.com/problems/binary-subarrays-with-sum/)
