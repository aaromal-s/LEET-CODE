# 📦 Arrays

This folder contains solutions to LeetCode problems focused on **Arrays**, **Two Pointers**, and **In-Place Array Manipulation**.

---

## 📑 Problem List

| # | Problem Title | Difficulty | Optimal Approach | Time Complexity | Space Complexity | Solution Document |
| :-: | :--- | :-: | :--- | :-: | :-: | :--- |
| 1 | [Two Sum](https://leetcode.com/problems/two-sum/) | 🟢 Easy | Hash Map Lookup | $O(n)$ | $O(n)$ | [1. Two Sum.md](./1.%20Two%20Sum.md) |
| 26 | [Remove Duplicates from Sorted Array](https://leetcode.com/problems/remove-duplicates-from-sorted-array/) | 🟢 Easy | Two Pointers (Slow/Fast) | $O(n)$ | $O(1)$ | [26. Remove Duplicates from Sorted Array.md](./26.%20Remove%20Duplicates%20from%20Sorted%20Array.md) |
| 27 | [Remove Element](https://leetcode.com/problems/remove-element/) | 🟢 Easy | Two Pointers (In-place) | $O(n)$ | $O(1)$ | [27. Remove Element.md](./27.%20Remove%20Element.md) |
| 66 | [Plus One](https://leetcode.com/problems/plus-one/) | 🟢 Easy | Reverse Traversal & Carry | $O(n)$ | $O(1)$ | [66. Plus One.md](./66.%20Plus%20One.md) |
| 88 | [Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/) | 🟢 Easy | Three Pointers from Back | $O(m + n)$ | $O(1)$ | [88. Merge Sorted Array.md](./88.%20Merge%20Sorted%20Array.md) |
| 118 | [Pascal's Triangle](https://leetcode.com/problems/pascals-triangle/) | 🟢 Easy | Dynamic Row Construction | $O(\text{numRows}^2)$ | $O(1)$ | [118. Pascal's Triangle.md](./118.%20Pascal's%20Triangle.md) |
| 119 | [Pascal's Triangle II](https://leetcode.com/problems/pascals-triangle-ii/) | 🟢 Easy | In-Place Reverse DP | $O(\text{rowIndex}^2)$ | $O(\text{rowIndex})$ | [119. Pascal's Triangle II.md](./119.%20Pascal's%20Triangle%20II.md) |
| 121 | [Best Time to Buy and Sell Stock](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/) | 🟢 Easy | One Pass Running Min | $O(n)$ | $O(1)$ | [121. Best Time to Buy and Sell Stock.md](./121.%20Best%20Time%20to%20Buy%20and%20Sell%20Stock.md) |
| 169 | [Majority Element](https://leetcode.com/problems/majority-element/) | 🟢 Easy | Boyer-Moore Voting | $O(n)$ | $O(1)$ | [169. Majority Element.md](./169.%20Majority%20Element.md) |
| 189 | [Rotate Array](https://leetcode.com/problems/rotate-array/) | 🟡 Medium | 3-Step Reverse | $O(n)$ | $O(1)$ | [189. Rotate Array.md](./189.%20Rotate%20Array.md) |
| 217 | [Contains Duplicate](https://leetcode.com/problems/contains-duplicate/) | 🟢 Easy | Hash Set | $O(n)$ | $O(n)$ | [217. Contains Duplicate.md](./217.%20Contains%20Duplicate.md) |
| 605 | [Can Place Flowers](https://leetcode.com/problems/can-place-flowers/) | 🟢 Easy | Greedy Adjacent Check | $O(n)$ | $O(1)$ | [605. Can Place Flowers.md](./605.%20Can%20Place%20Flowers.md) |
| 1431 | [Kids With the Greatest Number of Candies](https://leetcode.com/problems/kids-with-the-greatest-number-of-candies/) | 🟢 Easy | Precompute Max & Single Pass | $O(n)$ | $O(1)$ | [1431. Kids With the Greatest Number of Candies.md](./1431.%20Kids%20With%20the%20Greatest%20Number%20of%20Candies.md) |
| 1569 | [Number of Ways to Reorder Array to Get Same BST](https://leetcode.com/problems/number-of-ways-to-reorder-array-to-get-same-bst/) | 🔴 Hard | Divide & Conquer + Pascal Combinations | $O(n^2)$ | $O(n^2)$ | [1569. Number of Ways to Reorder Array to Get Same BST.md](./1569.%20Number%20of%20Ways%20to%20Reorder%20Array%20to%20Get%20Same%20BST.md) |
| 2089 | [Find Target Indices After Sorting Array](https://leetcode.com/problems/find-target-indices-after-sorting-array/) | 🟢 Easy | Counting (One-Pass without Sorting) | $O(n)$ | $O(1)$ | [2089. Find Target Indices After Sorting Array.md](./2089.%20Find%20Target%20Indices%20After%20Sorting%20Array.md) |
| 2913 | [Subarrays Distinct Element Sum of Squares I](https://leetcode.com/problems/subarrays-distinct-element-sum-of-squares-i/) | 🟢 Easy | Running Distinct Set | $O(n^2)$ | $O(n)$ | [2913. Subarrays Distinct Element Sum of Squares I.md](./2913.%20Subarrays%20Distinct%20Element%20Sum%20of%20Squares%20I.md) |
| 2916 | [Subarrays Distinct Element Sum of Squares II](https://leetcode.com/problems/subarrays-distinct-element-sum-of-squares-ii/) | 🔴 Hard | Segment Tree with Lazy Propagation | $O(n \log n)$ | $O(n)$ | [2916. Subarrays Distinct Element Sum of Squares II.md](./2916.%20Subarrays%20Distinct%20Element%20Sum%20of%20Squares%20II.md) |
| 3551 | [Minimum Swaps to Sort by Digit Sum](https://leetcode.com/problems/minimum-swaps-to-sort-by-digit-sum/) | 🟡 Medium | Custom Sort & Cycle Decomposition | $O(n \log n)$ | $O(n)$ | [3551. Minimum Swaps to Sort by Digit Sum.md](./3551.%20Minimum%20Swaps%20to%20Sort%20by%20Digit%20Sum.md) |
| 3644 | [Maximum K to Sort a Permutation](https://leetcode.com/problems/maximum-k-to-sort-a-permutation/) | 🟡 Medium | Misplaced Elements & Bitwise AND Invariant | $O(n)$ | $O(1)$ | [3644. Maximum K to Sort a Permutation.md](./3644.%20Maximum%20K%20to%20Sort%20a%20Permutation.md) |
| 3727 | [Maximum Alternating Sum of Squares](https://leetcode.com/problems/maximum-alternating-sum-of-squares/) | 🟡 Medium | Sorting & Greedy Partition | $O(n \log n)$ | $O(n)$ | [3727. Maximum Alternating Sum of Squares.md](./3727.%20Maximum%20Alternating%20Sum%20of%20Squares.md) |
| 3886 | [Sum of Sortable Integers](https://leetcode.com/problems/sum-of-sortable-integers/) | 🔴 Hard | Cyclic Drops Check & Block Bounds | $O(d(n) \cdot n)$ | $O(1)$ | [3886. Sum of Sortable Integers.md](./3886.%20Sum%20of%20Sortable%20Integers.md) |
| 3942 | [Minimum Operations to Sort a Permutation](https://leetcode.com/problems/minimum-operations-to-sort-a-permutation/) | 🟡 Medium | Dihedral Group & Cyclic Direction Evaluation | $O(n)$ | $O(1)$ | [3942. Minimum Operations to Sort a Permutation.md](./3942.%20Minimum%20Operations%20to%20Sort%20a%20Permutation.md) |

