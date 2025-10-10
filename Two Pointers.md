# 🧠 Two Pointers Problem List (LeetCode + GeeksforGeeks)

## 🔹 What is the Two Pointers Technique?

The **Two Pointers** technique is a common and efficient method used to solve problems involving **arrays**, **strings**, or **linked lists**.  
It works by maintaining two indices (pointers) that move through the data structure in a strategic way to achieve the goal — such as finding pairs, reversing data, or detecting patterns.

---

## ⚙️ When to Use Two Pointers

You can usually identify Two Pointer problems when:

1. You need to **find pairs or triplets** that satisfy a condition (like sum = target).  
2. You need to **move elements** or **rearrange** them efficiently (like moving zeros to the end).  
3. You need to **compare** or **merge** two sorted arrays or linked lists.  
4. You’re asked to **check for palindromes** or **reverse** sequences.  
5. You need to **detect loops** or **find middle elements** in a linked list.

---

## 🧩 How to Approach Two Pointer Problems

1. **Identify the pattern**  
   → Is it sorted? Are we looking for a pair/triplet/specific condition?  

2. **Choose the pointer movement strategy**  
   - **Same direction**: Both pointers start together and move forward (e.g., removing duplicates).  
   - **Opposite direction**: Pointers start from both ends (e.g., 3Sum, two-sum in sorted array).  
   - **Different speeds**: One fast and one slow pointer (e.g., finding cycle in a linked list).  

3. **Update pointers based on condition**  
   - Move left or right pointer depending on whether the condition is met.  
   - Adjust the loop until you find or rule out the solution.

4. **Think in terms of optimization**  
   → Two pointers often replace nested loops to bring **O(n²)** down to **O(n)**.

---

## 🔹 LeetCode Two-Pointer Problems

1. [15. 3Sum](https://leetcode.com/problems/3sum/)  
2. [11. Container With Most Water](https://leetcode.com/problems/container-with-most-water/)  
3. [75. Sort Colors](https://leetcode.com/problems/sort-colors/)  
4. [88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/)  
5. [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/)  
6. [142. Linked List Cycle II](https://leetcode.com/problems/linked-list-cycle-ii/)  
7. [234. Palindrome Linked List](https://leetcode.com/problems/palindrome-linked-list/)  
8. [876. Middle of the Linked List](https://leetcode.com/problems/middle-of-the-linked-list/)  
9. [189. Rotate Array](https://leetcode.com/problems/rotate-array/)  
10. [202. Happy Number](https://leetcode.com/problems/happy-number/)  

---

## 🔸 GeeksforGeeks Two-Pointer Problems

11. [Remove Occurrences](https://www.geeksforgeeks.org/remove-occurrences/)  
12. [Intersection of Two Sorted Arrays](https://www.geeksforgeeks.org/intersection-of-two-sorted-arrays/)  
13. [Move Zeros To End](https://www.geeksforgeeks.org/move-zeros-to-end-of-array/)  
14. [Sort an Array of 0s, 1s, and 2s](https://www.geeksforgeeks.org/sort-an-array-of-0s-1s-and-2s/)  
15. [Closest Pair from Two Sorted Arrays](https://www.geeksforgeeks.org/closest-pair-from-two-sorted-arrays/)  
16. [Dominant Pairs](https://www.geeksforgeeks.org/dominant-pairs/)  
17. [Sentence Palindrome](https://www.geeksforgeeks.org/sentence-palindrome/)  
18. [Triplet Sum in Array](https://www.geeksforgeeks.org/triplet-sum-in-array/)  
19. [Sum of Two Equals Third](https://www.geeksforgeeks.org/sum-of-two-equals-third/)  
20. [Reverse a String Preserving Space Positions](https://www.geeksforgeeks.org/reverse-a-string-preserving-space-position/)  

---

## 💡 Pro Tip

Whenever you see:
- **Sorted arrays**
- **Pairs/triplets**
- **Linked list traversal**
- **Comparing or merging elements**

👉 **Think Two Pointers first!**  
