# Search in Rotated Sorted Array — Modified Binary Search

## 📌 Problem
Given a sorted array that has been rotated at an unknown pivot, find the target's index in O(log n) time.

## 💡 Approach

A modified **Binary Search** is used.

At every iteration:

- Find the middle element.
- Determine which half is sorted.
- Check whether the target belongs to that sorted half.
- Continue searching only in the valid half.

## ✅ Complexity

- **Time:** O(log n)
- **Space:** O(1)

## 📖 Concepts Used

- Binary Search
- Rotated Arrays
- Divide and Conquer
- Searching

## 🚀 Key Idea

Even after rotation, one half of the array is always sorted. Identifying that half allows binary search to eliminate half of the remaining elements in every step.
