# Time Complexity


| Complexity | Name          | Example Scenario                          |
| ---------- | ------------- | ----------------------------------------- |
| O(1)       | Constant Time | Accessing an element by index in an array |
| O(log n)   | Logarithmic   | Binary Search                             |
| O(n)       | Linear        | Looping through an array                  |
| O(n log n) | Linearithmic  | Merge Sort, Quick Sort (average)          |
| O(n²)      | Quadratic     | Nested loops over the same array          |


# 🧠 Time Complexity – Intuitive Notes

---

## ✅ What is Time Complexity?

Time complexity tells us **how the time to run an algorithm grows** as the size of the input (`n`) increases.

We use **Big-O notation** (like `O(n)`, `O(log n)`) to describe the **worst-case** or **asymptotic behavior**.

---

## 🔢 Common Time Complexities (with Real-Life Analogies)

### 🔹 O(1) — Constant Time
- **Definition**: Takes the same amount of time, no matter the input size.
- **Analogy**: Grabbing a book off a specific shelf.
- **Example**: Looking at the 1st item in a list.

---

### 🔹 O(log n) — Logarithmic Time
- **Definition**: Time grows slowly as input size increases; each step cuts the problem in half.
- **Analogy**: Guessing a number between 1 and 100 using "higher/lower" — you cut the range in half each time.
- **Common Use**: Binary search.

---

### 🔹 O(n) — Linear Time
- **Definition**: Time grows in direct proportion to input size.
- **Analogy**: Reading every page in a book to find one word.
- **Common Use**: Scanning or summing elements.

---

### 🔹 O(n log n) — Linearithmic Time
- **Definition**: You repeat a logarithmic operation `log n` times across `n` elements.
- **Analogy**: Organizing books by splitting them into groups, sorting each group, and combining.
- **Common Use**: Merge sort, efficient sorting algorithms.

---

### 🔹 O(n²) — Quadratic Time
- **Definition**: Time grows as the square of the input size.
- **Analogy**: Comparing every student to every other student in a class.
- **Common Use**: Brute-force comparisons, nested loops.

---

### 🔹 O(2ⁿ) — Exponential Time
- **Definition**: Time doubles with each additional element.
- **Analogy**: Trying every combination of outfit choices — very quickly gets out of hand.
- **Common Use**: Subsets, brute-force recursion.

---

### 🔹 O(n!) — Factorial Time
- **Definition**: Time grows faster than exponential; all possible orderings.
- **Analogy**: Finding every possible seating arrangement for `n` people at a table.
- **Common Use**: Permutations, traveling salesman problem.

---

## 🧠 Final Tip

- The lower the time complexity, the faster the algorithm.
- Always aim for the **lowest possible time complexity** for large inputs.
- Avoid `O(n²)`, `O(2ⁿ)`, or `O(n!)` unless `n` is small.

---

## 📚 Complexity Growth (Visual Order)

# 🧠 Time Complexity – Intuitive Notes

---

## ✅ What is Time Complexity?

Time complexity tells us **how the time to run an algorithm grows** as the size of the input (`n`) increases.

We use **Big-O notation** (like `O(n)`, `O(log n)`) to describe the **worst-case** or **asymptotic behavior**.

---

## 🔢 Common Time Complexities (with Real-Life Analogies)

### 🔹 O(1) — Constant Time
- **Definition**: Takes the same amount of time, no matter the input size.
- **Analogy**: Grabbing a book off a specific shelf.
- **Example**: Looking at the 1st item in a list.

---

### 🔹 O(log n) — Logarithmic Time
- **Definition**: Time grows slowly as input size increases; each step cuts the problem in half.
- **Analogy**: Guessing a number between 1 and 100 using "higher/lower" — you cut the range in half each time.
- **Common Use**: Binary search.

---

### 🔹 O(n) — Linear Time
- **Definition**: Time grows in direct proportion to input size.
- **Analogy**: Reading every page in a book to find one word.
- **Common Use**: Scanning or summing elements.

---

### 🔹 O(n log n) — Linearithmic Time
- **Definition**: You repeat a logarithmic operation `log n` times across `n` elements.
- **Analogy**: Organizing books by splitting them into groups, sorting each group, and combining.
- **Common Use**: Merge sort, efficient sorting algorithms.

---

### 🔹 O(n²) — Quadratic Time
- **Definition**: Time grows as the square of the input size.
- **Analogy**: Comparing every student to every other student in a class.
- **Common Use**: Brute-force comparisons, nested loops.

---

### 🔹 O(2ⁿ) — Exponential Time
- **Definition**: Time doubles with each additional element.
- **Analogy**: Trying every combination of outfit choices — very quickly gets out of hand.
- **Common Use**: Subsets, brute-force recursion.

---

### 🔹 O(n!) — Factorial Time
- **Definition**: Time grows faster than exponential; all possible orderings.
- **Analogy**: Finding every possible seating arrangement for `n` people at a table.
- **Common Use**: Permutations, traveling salesman problem.

---

## 🧠 Final Tip

- The lower the time complexity, the faster the algorithm.
- Always aim for the **lowest possible time complexity** for large inputs.
- Avoid `O(n²)`, `O(2ⁿ)`, or `O(n!)` unless `n` is small.

---

## 📚 Complexity Growth (Visual Order)
![time-complexity](/assets/time-complexity-chart.png)



## Reference:-

[Big-o-cheat-sheet](https://www.bigocheatsheet.com)