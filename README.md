# 🧠 DSA Solutions — Vaibhav Goswami

Solving Data Structures & Algorithms problems daily using **Java**.  
Organized by topic, with time & space complexity noted on every solution.

[![LeetCode](https://img.shields.io/badge/LeetCode-vaibhavgoswami-orange?style=flat&logo=leetcode)](https://leetcode.com/vaibhavgoswami)
[![GitHub](https://img.shields.io/badge/GitHub-vaibhavgoswami1409-black?style=flat&logo=github)](https://github.com/vaibhavgoswami1409)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Vaibhav%20Goswami-blue?style=flat&logo=linkedin)](https://linkedin.com/in/vaibhavgoswami-14vg)

---

## 📊 Progress Tracker

| Topic | Problems Solved | Difficulty | Status |
|---|---|---|---|
| Arrays | 0 | Easy → Medium | 🔄 In Progress |
| Strings | 0 | Easy → Medium | ⏳ Not Started |
| Linked Lists | 0 | Easy → Medium | ⏳ Not Started |
| Stacks & Queues | 0 | Easy → Medium | ⏳ Not Started |
| Binary Search | 0 | Easy → Medium | ⏳ Not Started |
| Trees | 0 | Easy → Medium | ⏳ Not Started |
| Graphs | 0 | Easy → Medium | ⏳ Not Started |
| Dynamic Programming | 0 | Medium → Hard | ⏳ Not Started |
| Greedy | 0 | Easy → Medium | ⏳ Not Started |
| Recursion & Backtracking | 0 | Medium → Hard | 🔄 In Progress |

**Total solved: 0** — updated weekly

---

## 📁 Folder Structure

```
dsa-solutions/
├── arrays/
├── strings/
├── linked-lists/
├── stacks-queues/
├── binary-search/
├── trees/
├── graphs/
├── dynamic-programming/
├── greedy/
└── recursion-backtracking/
```

---

## 🗂️ Solution Format

Every file follows this format:

```java
// Problem: Two Sum (LeetCode #1)
// Difficulty: Easy
// Approach: HashMap — store complement as key
// Time: O(n) | Space: O(n)

class Solution {
    public int[] twoSum(int[] nums, int target) {
        Map<Integer, Integer> map = new HashMap<>();
        for (int i = 0; i < nums.length; i++) {
            int complement = target - nums[i];
            if (map.containsKey(complement)) {
                return new int[]{map.get(complement), i};
            }
            map.put(nums[i], i);
        }
        return new int[]{};
    }
}
```

---

## ✅ Problems List

### Arrays
| # | Problem | Difficulty | Approach | Solution |
|---|---|---|---|---|
| 1 | Two Sum | Easy | HashMap | [two-sum.java](arrays/two-sum.java) |

### Strings
| # | Problem | Difficulty | Approach | Solution |
|---|---|---|---|---|

### Linked Lists
| # | Problem | Difficulty | Approach | Solution |
|---|---|---|---|---|

### Trees
| # | Problem | Difficulty | Approach | Solution |
|---|---|---|---|---|

### Dynamic Programming
| # | Problem | Difficulty | Approach | Solution |
|---|---|---|---|---|

---

## 📈 LeetCode Stats

![LeetCode Stats](https://leetcard.jacoblin.cool/vaibhavgoswami?theme=light&font=Nunito&ext=contest)

---

## 🛠️ How I Practice

1. Read the problem — understand input/output, constraints
2. Think of brute force first, then optimize
3. Write the solution in Java from scratch
4. Note time and space complexity
5. Commit with a clear message: `solve: two sum - hashmap O(n)`

---

## 📌 Resources I Use

- [ApnaCollege DSA Playlist](https://www.youtube.com/@ApnaCollegeOfficial) — primary course
- [LeetCode](https://leetcode.com) — daily practice
- [GeeksforGeeks](https://geeksforgeeks.org) — concept reference
- [Striver's DSA Sheet](https://takeuforward.org/strivers-a2z-dsa-course/strivers-a2z-dsa-course-sheet-2/) — for structured topic practice

---

*Updated regularly as I solve more problems. Star the repo if you find it useful!*
