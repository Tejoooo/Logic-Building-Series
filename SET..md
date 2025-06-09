# 📘 SETS - Complete Guide

## 🔹 What is a Set?

A **set** is a collection of distinct, unordered elements.  
In programming, **sets** are used to eliminate duplicates and provide fast membership tests (like `x in set`).

In most languages (e.g., Python, C++, Java):
- **Python**: `set`, `frozenset`
- **C++**: `set`, `unordered_set`
- **Java**: `HashSet`, `TreeSet`, `LinkedHashSet`

---

## 🔹 Basic Operations on Sets

| Operation          | Description                              | Time Complexity |
|--------------------|------------------------------------------|------------------|
| `insert(x)`        | Add an element                           | O(1) in unordered, O(log n) in ordered |
| `erase(x)`         | Remove an element                        | O(1)/O(log n)     |
| `find(x)` / `in`   | Check membership                         | O(1)/O(log n)     |
| `size()`           | Get number of elements                   | O(1)              |
| `clear()`          | Remove all elements                      | O(n)              |
| `set1 & set2`      | Intersection                             | O(min(n, m))      |
| `set1 or set2`      | Union                                    | O(n + m)          |
| `set1 - set2`      | Difference                               | O(n)              |

---


## 🔹 Problems Solved Using Sets

### 1. **Remove Duplicates**
```python
unique_elements = list(set(arr))
```

### 2. **Check for Existence**
```python
if x in my_set:
    # do something
```

### 3. **Find Unique Elements in Two Lists**
```python
A = set(list1)
B = set(list2)
common = A & B  # intersection
unique = A ^ B  # symmetric difference
```

### 4. **Longest Consecutive Subsequence**
Given an array, find the length of the longest consecutive elements sequence.  
Use a set for O(1) lookups.

### 5. **Two Sum / Pair with Given Sum**
Use a set to store complements while traversing.

### 6. **First Repeating / Non-Repeating Element**
Keep a set for lookup and a list to track order of insertion.

### 7. **Find Duplicates in Array**
If `x` is already in set → duplicate found.

### 8. **Anagram Grouping**
Use set of character frequencies or sorted string as key for grouping.

### 9. **Set Covering / Subset Problems**
Use `set.issubset()`, `set.union()`, etc., in brute-force or greedy approaches.

### 10. **Graph Problems**
- Use sets to track visited nodes
- Use adjacency sets for undirected/weighted graphs

---

## 🔹 Key Tips & Concepts

### ✅ When to Use Sets:
- You need fast existence checking
- You want to eliminate duplicates
- You're solving problems involving group membership or relations

### ⚠️ Pitfalls to Avoid:
- Sets are unordered → no indexing
- Can't store mutable types in sets (e.g., lists in Python)
- Hash collisions can degrade performance in `unordered_set` (C++)

---

## ✅ Choose the Right Variant:

| Language | Unordered Set   | Ordered Set         | Notes                                |
|----------|------------------|---------------------|--------------------------------------|
| Python   | `set()`          | `sorted(set)`       | `frozenset()` for immutable sets     |
| C++      | `unordered_set`  | `set`               | `multiset` for allowing duplicates   |
| Java     | `HashSet`        | `TreeSet`           | `LinkedHashSet` maintains insertion order |

---

## 🧠 Memory and Performance

- Set operations in **Python** and **C++** have average-case O(1) for insert/search/delete in **unordered** versions.
- **Ordered sets** have O(log n) complexity (typically implemented using Red-Black trees).

---

## 🛠️ Interview Tips

- **"K most frequent"** → use `Counter` + set
- **"First unique"** → use `OrderedDict` or index tracking with a set
- Avoid linear search where set lookup is sufficient

---

## 📌 Summary

- Sets are ideal for fast, duplicate-free membership.
- Use `intersection`, `union`, `difference` wisely.
- Understand trade-offs between `set`, `list`, and `map`.
