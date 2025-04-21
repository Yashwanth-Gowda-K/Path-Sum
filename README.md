# Path-Sum

📌 Problem Statement

Given the `root` of a binary tree and an integer `targetSum`, return `true` if the tree has a **root-to-leaf** path such that adding up all the values along the path equals `targetSum`.
A **leaf** is a node with **no children**.

## 🧠 Example
Input: root = [5,4,8,11,null,13,4,7,2,null,null,null,1] targetSum = 22
Output: true
Explanation: The path 5 → 4 → 11 → 2 sums up to 22.


Time and Space Complexity:
Time Complexity: O(n) where n is the number of nodes in the tree. We visit each node once.
Space Complexity: O(h) where h is the height of the tree. This is due to the recursion stack.

