# 🧠 LeetCode Pattern Recognition Cheat Sheet

Train yourself to **identify the pattern before writing code**.  
Most LeetCode problems are variations of a small set of core patterns.

---

## 1️⃣ Hash Map / Set (Frequency & Lookup)
**Keywords to look for:**
- exists, frequency, unique, duplicates
- anagram, permutation
- two elements that sum to X

**Use when:**
- You need fast lookup or counting  
- Order doesn’t matter

**Time Complexity Goal:** `O(n)`

---

## 2️⃣ Two Pointers
**Keywords to look for:**
- sorted array / string
- palindrome
- pair with condition
- remove in-place

**Use when:**
- You can move from both ends toward the center  
- Input is sorted or order matters

---

## 3️⃣ Sliding Window
**Keywords to look for:**
- subarray, substring
- contiguous
- longest / shortest
- at most K, exactly K

**Use when:**
- You need a dynamic range while iterating  
- Window expands and contracts

---

## 4️⃣ Binary Search
**Keywords to look for:**
- sorted
- search
- minimum / maximum possible value
- first / last occurrence
- monotonic condition

**Use when:**
- The answer space is ordered or monotonic  
- Not always searching indices — sometimes searching values

---

## 5️⃣ Stack (Monotonic Stack)
**Keywords to look for:**
- next greater / smaller element
- previous greater / smaller
- balanced parentheses
- remove characters

**Use when:**
- You need to track previous elements in order

---

## 6️⃣ Prefix Sum
**Keywords to look for:**
- range sum
- sum between i and j
- subarray sum equals K
- cumulative sum

**Use when:**
- Repeated range queries are involved  
- You want to avoid recomputing sums

---

## 7️⃣ Fast & Slow Pointers (Floyd’s Algorithm)
**Keywords to look for:**
- cycle
- linked list
- duplicate number
- middle of list

**Use when:**
- One pointer can “lap” the other  
- Cycle detection or midpoint finding

---

## 8️⃣ DFS / Backtracking
**Keywords to look for:**
- all combinations
- permutations
- subsets
- generate
- choices / decision tree

**Use when:**
- You must explore all possible configurations  
- Recursive exploration with undo steps

---

## 9️⃣ BFS (Breadth-First Search)
**Keywords to look for:**
- shortest path
- minimum steps
- level order
- nearest
- grid / matrix

**Use when:**
- Distance grows uniformly per step  
- You need the shortest or minimum path

---

## 🔟 Dynamic Programming (DP)
**Keywords to look for:**
- maximum / minimum
- optimal
- number of ways
- can you reach
- overlapping subproblems

**Use when:**
- Brute force repeats work  
- You can cache previous results

---

## 1️⃣1️⃣ Greedy
**Keywords to look for:**
- minimum operations
- maximize / minimize
- intervals
- optimal choice at each step

**Use when:**
- A locally optimal choice leads to a global solution

---

## 1️⃣2️⃣ Heap / Priority Queue
**Keywords to look for:**
- top K
- kth smallest / largest
- stream
- most frequent

**Use when:**
- You need efficient access to extremes (min/max)

---

## ⚡ Quick Pattern Detection Flow

Ask these questions **in order**:

1. Is it **contiguous**? → Sliding Window / Prefix Sum  
2. Is it **sorted**? → Two Pointers / Binary Search  
3. Need **fast lookup**? → Hash Map / Set  
4. All **paths / combinations**? → DFS / Backtracking  
5. **Shortest path / steps**? → BFS  
6. **Optimal value / ways**? → Dynamic Programming  
7. **Top K / extremes**? → Heap  

---

## 🎯 Interview Tip

If you can **name the pattern out loud**, interviewers relax instantly:

> “This looks like a sliding window problem because we’re asked for the longest contiguous substring with a constraint.”

Pattern recognition first. Code second.
