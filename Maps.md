# Maps in Data Structures

## What is a Map?
A **Map** is a data structure that stores key-value pairs, where each key is unique. Maps are also known as dictionaries, associative arrays, or hash tables in various programming languages.

---

## Common Map Operations

| Operation         | Description                                 | Time Complexity (Average) | Time Complexity (Worst) |
|-------------------|---------------------------------------------|--------------------------|-------------------------|
| Insert            | Add a key-value pair                        | O(1) (HashMap), O(log n) (TreeMap) | O(n) (HashMap), O(log n) (TreeMap) |
| Delete            | Remove a key (and its value)                | O(1) (HashMap), O(log n) (TreeMap) | O(n) (HashMap), O(log n) (TreeMap) |
| Search/Find       | Find value by key                           | O(1) (HashMap), O(log n) (TreeMap) | O(n) (HashMap), O(log n) (TreeMap) |
| Update            | Change value for a key                      | O(1) (HashMap), O(log n) (TreeMap) | O(n) (HashMap), O(log n) (TreeMap) |
| Traversal         | Iterate over all key-value pairs            | O(n)                     | O(n)                    |
| Check existence   | Check if a key exists                       | O(1) (HashMap), O(log n) (TreeMap) | O(n) (HashMap), O(log n) (TreeMap) |
| Size              | Number of key-value pairs                   | O(1)                     | O(1)                    |
| Clear             | Remove all elements                         | O(n)                     | O(n)                    |

---

## Important Topics to Cover

- **Types of Maps:** HashMap, TreeMap, Unordered Map, Ordered Map, Multimap
- **Hash Functions and Collisions**
- **Iterating over Maps**
- **Custom Key Types (e.g., using pairs/structs as keys)**
- **Map vs. Set**
- **Applications of Maps**
- **Map STL in C++ / Dictionary in Python / HashMap in Java**
- **Handling Duplicate Keys**
- **Sorting by Key or Value**
- **Nested Maps**
- **Performance Considerations**

---

## Important DSA Questions on Maps
Here are 10 important DSA questions on Maps with their LeetCode links:

1. [Two Sum](https://leetcode.com/problems/two-sum/) (Find two numbers that add up to a target)
2. [Group Anagrams](https://leetcode.com/problems/group-anagrams/) (Group words with the same characters)
3. [Longest Substring Without Repeating Characters](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
4. [Top K Frequent Elements](https://leetcode.com/problems/top-k-frequent-elements/)
5. [Subarray Sum Equals K](https://leetcode.com/problems/subarray-sum-equals-k/)
6. [Valid Anagram](https://leetcode.com/problems/valid-anagram/)
7. [Minimum Window Substring](https://leetcode.com/problems/minimum-window-substring/)
8. [Longest Consecutive Sequence](https://leetcode.com/problems/longest-consecutive-sequence/)
9. [Isomorphic Strings](https://leetcode.com/problems/isomorphic-strings/)
10. [Word Pattern](https://leetcode.com/problems/word-pattern/)


## Important Topics to Cover: More Information

### 1. Types of Maps
- **HashMap** (C++: `std::unordered_map`, Java: `HashMap`, Python: `dict`): Uses a hash table for storage. No guaranteed order. Average O(1) operations; worst-case O(N). Use when fast lookups matter and order is unimportant.
- **TreeMap** (C++: `std::map`, Java: `TreeMap`): Stores keys in sorted order (typically via a balanced BST). All operations are O(logN). Use when you need sorted keys or range queries.
- **Unordered Map**: Synonym for HashMap; emphasizes lack of order.
- **Ordered Map**: Synonym for TreeMap; emphasizes sorted keys.
- **Multimap** (C++: `std::multimap`): Allows multiple values per key, with keys sorted. Useful when a key maps to several values.

### 2. Hash Functions and Collisions
- **Hash Function**: Converts a key to an integer index. Good hash functions distribute keys uniformly.
- **Collisions**: Occur when different keys map to the same index.
    - **Separate Chaining**: Each bucket holds a list of entries.
    - **Open Addressing**: Finds the next available slot (e.g., linear or quadratic probing).
- High collision rates degrade performance to O(N).

### 3. Iterating over Maps
- **HashMap/Unordered Map**: Iteration order is not guaranteed.
- **TreeMap/Ordered Map**: Iterates in sorted key order.
- **Multimap**: Duplicate keys appear consecutively.

### 4. Custom Key Types
- **HashMap**: Requires custom hash and equality functions (e.g., `operator==` in C++, `hashCode()`/`equals()` in Java, `__hash__`/`__eq__` in Python).
- **TreeMap**: Requires a strict ordering (e.g., `operator<` in C++, `Comparable`/`Comparator` in Java).

### 5. Map vs. Set
- **Map**: Stores key-value pairs; retrieves values by key.
- **Set**: Stores unique elements; checks for membership.
- A set can be seen as a map with ignored values.

### 6. Applications of Maps
- Dictionaries/symbol tables
- Counting frequencies (words, characters)
- Caching
- Graph adjacency lists
- Configuration settings
- Memoization in dynamic programming

### 7. Map Implementations in Languages
- **C++**: `std::map` (ordered), `std::unordered_map` (unordered), `std::multimap` (ordered, duplicates), `std::unordered_multimap` (unordered, duplicates)
- **Python**: `dict` (unordered, preserves insertion order since 3.7)
- **Java**: `HashMap` (unordered), `TreeMap` (ordered), `LinkedHashMap` (insertion order), `ConcurrentHashMap` (thread-safe)

### 8. Handling Duplicate Keys
- **Standard Maps**: No duplicate keys; new value overwrites old.
- **Multimaps**: Allow duplicate keys.
- **Simulation**: Use `Map<Key, List<Value>>` or `Map<Key, Set<Value>>` if multimaps are unavailable.

### 9. Sorting by Key or Value
- **By Key**: Ordered maps are already sorted; unordered maps require extracting and sorting entries.
- **By Value**: Extract entries and sort by value (O(NlogN)).

### 10. Nested Maps
- Maps where values (or keys) are themselves maps, e.g., `Map<Key1, Map<Key2, Value>>`.
- Useful for multi-dimensional or hierarchical data, but increases complexity and memory usage.

### 11. Performance Considerations
- **Map Type**: Choose based on speed (HashMap) vs. order (TreeMap).
- **Hash Function Quality**: Poor hash functions cause collisions and slowdowns.
- **Load Factor**: Affects rehashing in hash maps.
- **Key Design**: Complex or mutable keys can slow operations or cause bugs.
- **Concurrency**: Standard maps are not thread-safe; use concurrent versions or synchronization for multi-threading.


---

## Example (C++)

```cpp
#include <iostream>
#include <map>
using namespace std;

int main() {
    map<string, int> mp;
    mp["apple"] = 2;
    mp["banana"] = 5;
    mp["orange"] = 3;

    // Traversal
    for (auto &p : mp) {
        cout << p.first << ": " << p.second << endl;
    }

    // Search
    if (mp.find("apple") != mp.end()) {
        cout << "Apple found!" << endl;
    }
}
```

---

## References

- [C++ STL Map Documentation](https://en.cppreference.com/w/cpp/container/map)
- [Python dict Documentation](https://docs.python.org/3/library/stdtypes.html#dict)
- [Java HashMap Documentation](https://docs.oracle.com/javase/8/docs/api/java/util/HashMap.html)
