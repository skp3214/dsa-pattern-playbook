# Sliding Window Pattern

## 📋 Table of Contents
- [What is Sliding Window?](#what-is-sliding-window)
- [When to Use Sliding Window](#when-to-use-sliding-window)
- [Question Sheets](#question-sheets)

---

## [What is Sliding Window?]()

The **Sliding Window** technique is used to process sequential data (arrays/strings) by maintaining a "window" of elements that slides through the data structure. This technique optimizes problems from **O(n²)** or **O(n×k)** to **O(n)**.

**Key Concept:** Instead of recalculating from scratch for each position, we add new elements entering the window and remove elements leaving the window.

**Data Structures:** Primarily used with:
- Arrays
- Strings
- Linked Lists (occasionally)

---

## [When to Use Sliding Window]()

### ✅ Clear Indicators to Use This Pattern:

#### 1. **Contiguous Subarray/Substring Problems**
- Find subarray/substring with specific property
- Must be contiguous (adjacent elements)
- **Example:** Maximum sum subarray of size k

#### 2. **Keywords: "Subarray", "Substring", "Consecutive"**
- Problems explicitly mention contiguous sequences
- **Example:** Longest substring without repeating characters

#### 3. **Fixed or Variable Window Size**
- Fixed: Window size is given (e.g., k elements)
- Variable: Window expands/shrinks based on condition
- **Example:** Minimum window substring

#### 4. **Optimization Problems on Sequences**
- Find minimum/maximum length
- Find minimum/maximum sum
- **Example:** Smallest subarray with sum ≥ target

#### 5. **Count Subarrays with Specific Property**
- Count subarrays matching condition
- **Example:** Count subarrays with exactly k distinct elements

#### 6. **Pattern Matching in Strings**
- Find all anagrams
- Find permutation in string
- **Example:** Find all anagrams of pattern in text

#### 7. **Running Aggregates**
- Maintain sum, product, count in window
- **Example:** Maximum average subarray


## [Question Sheets]()

| Problem Name | Difficulty |
|-------------|------------|
|[Max Sum SubArray of Size K](https://www.geeksforgeeks.org/problems/max-sum-subarray-of-size-k5313/1)|Easy|
|[Minimum Size Subarray Sum](https://leetcode.com/problems/minimum-size-subarray-sum/description/)|Medium|