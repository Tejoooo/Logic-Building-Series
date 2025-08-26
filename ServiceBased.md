# Problem-Solving Patterns

## 1) Divide and Conquer
**Common Questions:**
- Maximum Subarray Sum → (Kadane’s with D&C)
- Longest Substring/Palindrome using D&C
- Search in Rotated Sorted Array
- Count Inversions in an Array

👉 **Pattern:** Break into subarrays → solve → merge results

---

## 2) Recursion & Heap

### Recursion Questions:
- Generate all subsets / permutations of a set
- N-Queens Problem
- Tower of Hanoi

### Heap Questions:
- Find kth smallest/largest element
- Top K frequent elements
- Merge K sorted arrays/lists

👉 **Pattern:** Recursive exploration OR greedy element selection using priority queue

---

## 3) Bit Manipulation & Hashing

### Bit Manipulation Questions:
- Count number of set bits
- Check if number is a power of 2
- Find unique element where others appear twice/thrice

### Hashing Questions:
- Longest Subarray with Sum = k
- Check Anagrams
- First non-repeating character in string

👉 **Pattern:** Optimize using XOR / bit tricks, or fast lookups with hashmaps

---

## 4) Greedy Algorithms
**Questions:**
- Activity Selection / Job Sequencing
- Minimum cost to connect ropes
- Greedy string problems → remove k digits, reorganize string
- Greedy numbers → coin change (when canonical), fractional knapsack, largest number from array

👉 **Pattern:** Sort + make locally optimal choices that lead to global optimum

---

## 5) Dynamic Programming (DP)
**Questions:**
- Knapsack Problems (0/1 knapsack, subset sum, partition equal subset)
- DP on Graphs → shortest path with constraints, DP on trees
- DP on Subsequences → LCS, Edit Distance, Palindrome subsequence
- DP on Matrices → Minimum path sum, unique paths, gold mine

👉 **Pattern:** Break problem into overlapping subproblems + reuse results (memoization / tabulation)
