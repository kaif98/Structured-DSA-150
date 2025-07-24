# 🧠 150 NeetCode DSA Solutions (Python)

Welcome to my curated repository of solutions for the **[150 Most Important LeetCode Problems](https://neetcode.io/)** – a hand-picked list ideal for mastering **Data Structures and Algorithms**.

These problems are grouped by topic and solved using clean, readable **Python 3** with explanations and time/space complexity notes.

---

## 📚 Topics Covered

- ✅ Arrays & Hashing
- ✅ Two Pointers
- ✅ Sliding Window
- ✅ Stack
- ✅ Binary Search
- ✅ Linked List
- ✅ Trees
- ✅ Heap / Priority Queue
- ✅ Backtracking
- ✅ Graphs
- ✅ Dynamic Programming
- ✅ Math & Bit Manipulation

---

## 🔧 How to Use

Each folder contains `.py` files named after the problem, with:
- Problem link
- Python solution
- Time/space complexity
- Edge case handling

Example:

```python
# 📌 Problem: Two Sum
# 🔗 https://leetcode.com/problems/two-sum/
# 🧠 Topic: Arrays & Hashing

def twoSum(nums, target):
    hashmap = {}
    for i, num in enumerate(nums):
        if target - num in hashmap:
            return [hashmap[target - num], i]
        hashmap[num] = i

# Time: O(n)
# Space: O(n)
