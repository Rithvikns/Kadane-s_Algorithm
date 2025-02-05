# Kadane’s Algorithm (Maximum Subarray Sum)

Kadane’s Algorithm is an efficient way to find the **maximum sum of a contiguous subarray** within a given list of numbers. It runs in **O(n) time complexity**, making it much faster than brute-force approaches.

## Algorithm Steps:
1. Initialize:
   - `max_sum` → Stores the maximum sum found so far.
   - `current_sum` → Tracks the sum of the current subarray.
   
2. Iterate through the array:
   - Add the current element to `current_sum`.
   - If `current_sum` exceeds `max_sum`, update `max_sum`.

3. Return `max_sum` after scanning the entire array.

---

## 📝 Example:
### **Input:**
```python
arr = [-2, 1, -3, 4, -1, 2, 1, -5, 4]
### **Output:**
Maximum subarray sum: 6

