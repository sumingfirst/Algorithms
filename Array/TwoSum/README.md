# Two Sum（两数之和）
**LeetCode 1**

- [英文版](https://leetcode.com/problems/two-sum/)

- [中文版](https://leetcode-cn.com/problems/two-sum/)

## 题目
给定一个整数数组 nums 和一个目标值 target，请你在该数组中找出和为目标值的那*两个*整数，并返回他们的数组下标。

你可以假设每种输入只会对应一个答案。但是，你不能重复利用这个数组中同样的元素。

示例:
```
给定 nums = [2, 7, 11, 15], target = 9

因为 nums[0] + nums[1] = 2 + 7 = 9
所以返回 [0, 1]
```

## 思路
<details>
<summary>点击展开</summary>
使用散列表，缓存访问过的元素和下标，遍历数组，查找缓存中是否存在元素和当前元素的和等于目标值。
时间复杂度 O(n)。
</details>

## 代码实现
| C++ | Java | Python | JS |
| :--: | :--: | :--: | :---: |
|[😀](TwoSum.cpp) | [😀](TwoSum.java) | [😀](TwoSum.py) | [😀](TwoSum.js) |
