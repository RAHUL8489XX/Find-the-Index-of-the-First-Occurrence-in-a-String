

# 🔍 Find the Index of the First Occurrence in a String

**Problem Link**: [LeetCode #28](https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/)

## 🧠 Problem Statement

Given two strings `haystack` and `needle`, return the index of the first occurrence of `needle` in `haystack`, or `-1` if `needle` is not part of `haystack`.

### Examples
```python
Input: haystack = "sadbutsad", needle = "sad"
Output: 0

Input: haystack = "leetcode", needle = "leeto"
Output: -1
```

## 📊 Complexity Analysis

| Approach        | Time Complexity | Space Complexity | Notes |
|----------------|------------------|-------------------|-------|
| `.find()`       | O(n)             | O(1)              | Uses Python's optimized internal implementation |
| Manual Scan     | O(n * m)         | O(1)              | Compares substring at each position manually |
