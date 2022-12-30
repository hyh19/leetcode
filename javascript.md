<!-- omit in toc -->
# LeetCode 题解：JavaScript

- [1. 两数之和](#1-两数之和)
- [2. 两数相加](#2-两数相加)
- [3. 无重复字符的最长子串](#3-无重复字符的最长子串)
- [4. 寻找两个正序数组的中位数](#4-寻找两个正序数组的中位数)
- [5. 最长回文子串](#5-最长回文子串)
- [7. 整数反转](#7-整数反转)
- [11. 盛最多水的容器](#11-盛最多水的容器)
- [14. 最长公共前缀](#14-最长公共前缀)
- [15. 三数之和](#15-三数之和)
- [18. 四数之和](#18-四数之和)
- [19. 删除链表的倒数第 N 个结点](#19-删除链表的倒数第-n-个结点)
- [20. 有效的括号](#20-有效的括号)
- [21. 合并两个有序链表](#21-合并两个有序链表)
- [22. 括号生成](#22-括号生成)
- [23. 合并 K 个升序链表](#23-合并-k-个升序链表)
- [24. 两两交换链表中的节点](#24-两两交换链表中的节点)
- [25. K 个一组翻转链表](#25-k-个一组翻转链表)
- [26. 删除有序数组中的重复项](#26-删除有序数组中的重复项)
- [27. 移除元素](#27-移除元素)
- [28. 实现 strStr()](#28-实现-strstr)
- [33. 搜索旋转排序数组](#33-搜索旋转排序数组)
- [34. 在排序数组中查找元素的第一个和最后一个位置](#34-在排序数组中查找元素的第一个和最后一个位置)
- [37. 解数独](#37-解数独)
- [39. 组合总和](#39-组合总和)
- [40. 组合总和 II](#40-组合总和-ii)
- [42. 接雨水](#42-接雨水)
- [46. 全排列](#46-全排列)
- [47. 全排列 II](#47-全排列-ii)
- [51. N 皇后](#51-n-皇后)
- [52. N 皇后 II](#52-n-皇后-ii)
- [53. 最大子数组和](#53-最大子数组和)
- [56. 合并区间](#56-合并区间)
- [64. 最小路径和](#64-最小路径和)
- [69. x 的平方根](#69-x-的平方根)
- [70. 爬楼梯](#70-爬楼梯)
- [72. 编辑距离](#72-编辑距离)
- [75. 颜色分类](#75-颜色分类)
- [76. 最小覆盖子串](#76-最小覆盖子串)
- [77. 组合](#77-组合)
- [78. 子集](#78-子集)
- [81. 搜索旋转排序数组 II](#81-搜索旋转排序数组-ii)
- [83. 删除排序链表中的重复元素](#83-删除排序链表中的重复元素)
- [86. 分隔链表](#86-分隔链表)
- [90. 子集 II](#90-子集-ii)
- [92. 反转链表 II](#92-反转链表-ii)
- [94. 二叉树的中序遍历](#94-二叉树的中序遍历)
- [95. 不同的二叉搜索树 II](#95-不同的二叉搜索树-ii)
- [96. 不同的二叉搜索树](#96-不同的二叉搜索树)
- [98. 验证二叉搜索树](#98-验证二叉搜索树)
- [100. 相同的树](#100-相同的树)
- [102. 二叉树的层序遍历](#102-二叉树的层序遍历)
- [103. 二叉树的锯齿形层序遍历](#103-二叉树的锯齿形层序遍历)
- [104. 二叉树的最大深度](#104-二叉树的最大深度)
- [105. 从前序与中序遍历序列构造二叉树](#105-从前序与中序遍历序列构造二叉树)
- [106. 从中序与后序遍历序列构造二叉树](#106-从中序与后序遍历序列构造二叉树)
- [107. 二叉树的层序遍历 II](#107-二叉树的层序遍历-ii)
- [108. 将有序数组转换为二叉搜索树](#108-将有序数组转换为二叉搜索树)
- [110. 平衡二叉树](#110-平衡二叉树)
- [111. 二叉树的最小深度](#111-二叉树的最小深度)
- [112. 路径总和](#112-路径总和)
- [114. 二叉树展开为链表](#114-二叉树展开为链表)
- [116. 填充每个节点的下一个右侧节点指针](#116-填充每个节点的下一个右侧节点指针)
- [121. 买卖股票的最佳时机](#121-买卖股票的最佳时机)
- [122. 买卖股票的最佳时机 II](#122-买卖股票的最佳时机-ii)
- [123. 买卖股票的最佳时机 III](#123-买卖股票的最佳时机-iii)
- [125. 验证回文串](#125-验证回文串)
- [128. 最长连续序列](#128-最长连续序列)
- [130. 被围绕的区域](#130-被围绕的区域)
- [136. 只出现一次的数字](#136-只出现一次的数字)
- [141. 环形链表](#141-环形链表)
- [142. 环形链表 II](#142-环形链表-ii)
- [143. 重排链表](#143-重排链表)
- [144. 二叉树的前序遍历](#144-二叉树的前序遍历)
- [145. 二叉树的后序遍历](#145-二叉树的后序遍历)
- [146. LRU 缓存](#146-lru-缓存)
- [153. 寻找旋转排序数组中的最小值](#153-寻找旋转排序数组中的最小值)
- [155. 最小栈](#155-最小栈)
- [160. 相交链表](#160-相交链表)
- [165. 比较版本号](#165-比较版本号)
- [167. 两数之和 II - 输入有序数组](#167-两数之和-ii---输入有序数组)
- [169. 多数元素](#169-多数元素)
- [179. 最大数](#179-最大数)
- [188. 买卖股票的最佳时机 IV](#188-买卖股票的最佳时机-iv)
- [189. 轮转数组](#189-轮转数组)
- [198. 打家劫舍](#198-打家劫舍)
- [199. 二叉树的右视图](#199-二叉树的右视图)
- [200. 岛屿数量](#200-岛屿数量)
- [203. 移除链表元素](#203-移除链表元素)
- [206. 反转链表](#206-反转链表)
- [207. 课程表](#207-课程表)
- [210. 课程表 II](#210-课程表-ii)
- [213. 打家劫舍 II](#213-打家劫舍-ii)
- [215. 数组中的第 K 个最大元素](#215-数组中的第-k-个最大元素)
- [216. 组合总和 III](#216-组合总和-iii)
- [222. 完全二叉树的节点个数](#222-完全二叉树的节点个数)
- [225. 用队列实现栈](#225-用队列实现栈)
- [226. 翻转二叉树](#226-翻转二叉树)
- [230. 二叉搜索树中第 K 小的元素](#230-二叉搜索树中第-k-小的元素)
- [232. 用栈实现队列](#232-用栈实现队列)
- [234. 回文链表](#234-回文链表)
- [235. 二叉搜索树的最近公共祖先](#235-二叉搜索树的最近公共祖先)
- [236. 二叉树的最近公共祖先](#236-二叉树的最近公共祖先)
- [237. 删除链表中的节点](#237-删除链表中的节点)
- [239. 滑动窗口最大值](#239-滑动窗口最大值)
- [253. 会议室 II](#253-会议室-ii)
- [283. 移动零](#283-移动零)
- [297. 二叉树的序列化与反序列化](#297-二叉树的序列化与反序列化)
- [300. 最长递增子序列](#300-最长递增子序列)
- [303. 区域和检索 - 数组不可变](#303-区域和检索---数组不可变)
- [309. 最佳买卖股票时机含冷冻期](#309-最佳买卖股票时机含冷冻期)
- [315. 计算右侧小于当前元素的个数](#315-计算右侧小于当前元素的个数)
- [322. 零钱兑换](#322-零钱兑换)
- [337. 打家劫舍 III](#337-打家劫舍-iii)
- [344. 反转字符串](#344-反转字符串)
- [354. 俄罗斯套娃信封问题](#354-俄罗斯套娃信封问题)
- [394. 字符串解码](#394-字符串解码)
- [416. 分割等和子集](#416-分割等和子集)
- [435. 无重叠区间](#435-无重叠区间)
- [438. 找到字符串中所有字母异位词](#438-找到字符串中所有字母异位词)
- [445. 两数相加 II](#445-两数相加-ii)
- [450. 删除二叉搜索树中的节点](#450-删除二叉搜索树中的节点)
- [452. 用最少数量的箭引爆气球](#452-用最少数量的箭引爆气球)
- [460. LFU 缓存](#460-lfu-缓存)
- [493. 翻转对](#493-翻转对)
- [494. 目标和](#494-目标和)
- [496. 下一个更大元素 I](#496-下一个更大元素-i)
- [503. 下一个更大元素 II](#503-下一个更大元素-ii)
- [509. 斐波那契数](#509-斐波那契数)
- [516. 最长回文子序列](#516-最长回文子序列)
- [518. 零钱兑换 II](#518-零钱兑换-ii)
- [538. 把二叉搜索树转换为累加树](#538-把二叉搜索树转换为累加树)
- [543. 二叉树的直径](#543-二叉树的直径)
- [567. 字符串的排列](#567-字符串的排列)
- [583. 两个字符串的删除操作](#583-两个字符串的删除操作)
- [617. 合并二叉树](#617-合并二叉树)
- [652. 寻找重复的子树](#652-寻找重复的子树)
- [654. 最大二叉树](#654-最大二叉树)
- [695. 岛屿的最大面积](#695-岛屿的最大面积)
- [698. 划分为 K 个相等的子集](#698-划分为-k-个相等的子集)
- [700. 二叉搜索树中的搜索](#700-二叉搜索树中的搜索)
- [701. 二叉搜索树中的插入操作](#701-二叉搜索树中的插入操作)
- [704. 二分查找](#704-二分查找)
- [712. 两个字符串的最小 ASCII 删除和](#712-两个字符串的最小-ascii-删除和)
- [714. 买卖股票的最佳时机含手续费](#714-买卖股票的最佳时机含手续费)
- [739. 每日温度](#739-每日温度)
- [743. 网络延迟时间](#743-网络延迟时间)
- [752. 打开转盘锁](#752-打开转盘锁)
- [785. 判断二分图](#785-判断二分图)
- [797. 所有可能的路径](#797-所有可能的路径)
- [846. 一手顺子](#846-一手顺子)
- [875. 爱吃香蕉的珂珂](#875-爱吃香蕉的珂珂)
- [876. 链表的中间结点](#876-链表的中间结点)
- [886. 可能的二分法](#886-可能的二分法)
- [889. 根据前序和后序遍历构造二叉树](#889-根据前序和后序遍历构造二叉树)
- [905. 按奇偶排序数组](#905-按奇偶排序数组)
- [912. 排序数组](#912-排序数组)
- [921. 使括号有效的最少添加](#921-使括号有效的最少添加)
- [922. 按奇偶排序数组 II](#922-按奇偶排序数组-ii)
- [931. 下降路径最小和](#931-下降路径最小和)
- [986. 区间列表的交集](#986-区间列表的交集)
- [990. 等式方程的可满足性](#990-等式方程的可满足性)
- [1011. 在 D 天内送达包裹的能力](#1011-在-d-天内送达包裹的能力)
- [1020. 飞地的数量](#1020-飞地的数量)
- [1024. 视频拼接](#1024-视频拼接)
- [1143. 最长公共子序列](#1143-最长公共子序列)
- [1254. 统计封闭岛屿的数目](#1254-统计封闭岛屿的数目)
- [1288. 删除被覆盖区间](#1288-删除被覆盖区间)
- [1382. 将二叉搜索树变平衡](#1382-将二叉搜索树变平衡)
- [1514. 概率最大的路径](#1514-概率最大的路径)
- [1541. 平衡括号字符串的最少插入次数](#1541-平衡括号字符串的最少插入次数)
- [1584. 连接所有点的最小费用](#1584-连接所有点的最小费用)
- [1631. 最小体力消耗路径](#1631-最小体力消耗路径)
- [1905. 统计子岛屿](#1905-统计子岛屿)
- [CtCI 02.02. 返回倒数第 K 个节点](#ctci-0202-返回倒数第-k-个节点)

## 1. 两数之和

<https://leetcode-cn.com/problems/two-sum/>

```js
/**
 * @param {number[]} nums
 * @param {number} target
 * @return {number[]}
 */
 var twoSum = function (nums, target) {
    const n = nums.length;
    const valToIndex = new Map()
    for (let i = 0; i < n; ++i) {
        const x = nums[i];
        const need = target - x;
        if (valToIndex.has(need)) {
            return [valToIndex.get(need), i];
        }
        valToIndex.set(x, i);
    }
    return [];
};
// https://leetcode.cn/submissions/detail/380705413/
```

## 2. 两数相加

<https://leetcode-cn.com/problems/add-two-numbers/>

```js
/**
 * @param {ListNode} l1
 * @param {ListNode} l2
 * @return {ListNode}
 */
 const addTwoNumbers = function (l1, l2) {
    const dummyHead = new ListNode();
    let ptr = dummyHead;
    let carry = 0;
    while (l1 != null || l2 != null || carry > 0) {
        let sum = carry;
        if (l1 != null) {
            sum += l1.val;
            l1 = l1.next;
        }
        if (l2 != null) {
            sum += l2.val;
            l2 = l2.next;
        }
        ptr.next = new ListNode(sum % 10);
        ptr = ptr.next;
        carry = Math.floor(sum / 10);
    }
    return dummyHead.next;
};
// https://leetcode.cn/submissions/detail/380952831/
```

## 3. 无重复字符的最长子串

<https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/>

```js
/**
 * @param {string} s
 * @return {number}
 */
 const lengthOfLongestSubstring = function (s) {
    let ans = 0;
    const window = new Set();
    // s[left..right) = Window Substring
    // s[right..n-1]  = Scanning
    let left = 0, right = 0;
    while (right < s.length) {
        const c = s.charAt(right);
        if (!window.has(c)) {
            window.add(c);
            ++right;
        } else {
            while (left <= right) {
                const d = s.charAt(left++);
                window.delete(d);
                if (c === d) {
                    break;
                }
            }
        }
        ans = Math.max(ans, right - left);
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381022081/
```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```js
/**
 * @param {number[]} nums1
 * @param {number[]} nums2
 * @return {number}
 */
const findMedianSortedArrays = function (nums1, nums2) {
    const total = nums1.length + nums2.length;
    const half = Math.floor(total / 2);
    if (total % 2 === 0) {
        const k1 = getKthElement(nums1, 0, nums2, 0, half);
        const k2 = getKthElement(nums1, 0, nums2, 0, half + 1);
        return (k1 + k2) / 2;
    }
    return getKthElement(nums1, 0, nums2, 0, half + 1);
};

// 寻找两个正序数组 nums1[start1..end1] 和 nums2[start2..end2] 从小到大排列的第 k 个数
const getKthElement = function (nums1, start1, nums2, start2, k) {
    const n1 = nums1.length, n2 = nums2.length;
    if (start1 === n1) {
        return nums2[start2 + k - 1];
    }
    if (start2 === n2) {
        return nums1[start1 + k - 1];
    }
    if (k === 1) {
        return Math.min(nums1[start1], nums2[start2]);
    }
    const half = Math.floor(k / 2);
    const i = Math.min(n1 - 1, start1 + half - 1);
    const j = Math.min(n2 - 1, start2 + half - 1);
    if (nums1[i] < nums2[j]) {
        // 排除 nums1[start1..i] 共 i-start1+1 个元素
        return getKthElement(nums1, i + 1, nums2, start2, k - (i - start1 + 1));
    } else {
        // 排除 nums2[start2..j] 共 j-start2+1 个元素
        return getKthElement(nums1, start1, nums2, j + 1, k - (j - start2 + 1));
    }
};
// https://leetcode.cn/submissions/detail/381725874/
```

## 5. 最长回文子串

<https://leetcode.cn/problems/longest-palindromic-substring/>

```js
/**
 * @param {string} s
 * @return {string}
 */
 const longestPalindrome = function (s) {
    let ans = "";
    for (let i = 0; i < s.length; ++i) {
        const s1 = longestPalindromeRange(s, i, i);
        if (s1.length > ans.length) {
            ans = s1;
        }
        const s2 = longestPalindromeRange(s, i, i + 1);
        if (s2.length > ans.length) {
            ans = s2;
        }
    }
    return ans;
};

/**
 * 返回字符串 s 中以 s[i] 和 s[j] 为中心的最长回文子串
 * @param {string} s
 * @param {number} i
 * @param {number} j
 * @return {string}
 */
const longestPalindromeRange = function (s, i, j) {
    if (i > j || j - i > 1) {
        return "";
    }
    while (i >= 0 && j < s.length && s.charAt(i) === s.charAt(j)) {
        --i;
        ++j;
    }
    return s.substring(i + 1, j);
};
// https://leetcode.cn/submissions/detail/380910954/
```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```js

```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```js
/**
 * @param {number[]} height
 * @return {number}
 */
 var maxArea = function (height) {
    let ans = 0;
    let i = 0, j = height.length - 1;
    while (i < j) {
        const area = Math.min(height[i], height[j]) * (j - i);
        ans = Math.max(ans, area);
        if (height[i] < height[j]) {
            ++i;
        } else {
            --j;
        }
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/380806635/
```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```js
/**
 * @param {string[]} strs
 * @return {string}
 */
 const longestCommonPrefix = function (strs, lo = 0, hi = strs.length - 1) {
    if (lo === hi) {
        return strs[lo];
    }
    const mid = lo + Math.floor((hi - lo) / 2);
    const left = longestCommonPrefix(strs, lo, mid);
    const right = longestCommonPrefix(strs, mid + 1, hi);
    return longestCommonPrefixTwo(left, right);
};

const longestCommonPrefixTwo = function (s1, s2) {
    const n = Math.min(s1.length, s2.length);
    let i = 0;
    while (i < n && s1.charAt(i) === s2.charAt(i)) {
        ++i;
    }
    return s1.substring(0, i);
};
// https://leetcode.cn/submissions/detail/381488102/
```

## 15. 三数之和

<https://leetcode-cn.com/problems/3sum/>

```js
/**
 * @param {number[]} nums
 * @return {number[][]}
 */
 const threeSum = function (nums) {
    nums.sort((a, b) => a - b);
    return kSum(3, nums, 0, nums.length - 1, 0);
};

/**
 * 返回升序子数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
 * @param {number} k
 * @param {number[]} nums
 * @param {number} lo
 * @param {number} hi
 * @param {number} target
 * @return {number[][]}
 */
const kSum = function (k, nums, lo, hi, target) {
    if (hi - lo + 1 < k) {
        return [];
    }
    if (k === 2) {
        return twoSum(nums, lo, hi, target);
    }
    const res = [];
    let i = lo;
    while (i <= hi) {
        const curNum = nums[i];
        const sp = kSum(k - 1, nums, i + 1, hi, target - curNum);
        for (const a of sp) {
            a.push(curNum);
            res.push(a);
        }
        while (++i <= hi && nums[i] === curNum) {
        }
    }
    return res;
};

/**
 * 返回升序子数组 nums[lo..hi] 中所有和为 target 且不重复的二元组
 * @param {number[]} nums
 * @param {number} lo
 * @param {number} hi
 * @param {number} target
 * @return {number[][]}
 */
const twoSum = function (nums, lo, hi, target) {
    const res = [];
    while (lo < hi) {
        const first = nums[lo], second = nums[hi];
        const sum = first + second;
        if (sum < target) {
            while (++lo < hi && nums[lo] === first) {
            }
        } else if (sum > target) {
            while (lo < --hi && nums[hi] === second) {
            }
        } else {
            res.push([first, second]);
            while (++lo < hi && nums[lo] === first) {
            }
            while (lo < --hi && nums[hi] === second) {
            }
        }
    }
    return res;
};
// https://leetcode.cn/submissions/detail/380878818/
```

## 18. 四数之和

<https://leetcode.cn/problems/4sum/>

```js
/**
 * @param {number[]} nums
 * @param {number} target
 * @return {number[][]}
 */
 const fourSum = function (nums, target) {
    nums.sort((a, b) => a - b);
    return kSum(4, nums, 0, nums.length - 1, target);
};

/**
 * 返回升序子数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
 * @param {number} k
 * @param {number[]} nums
 * @param {number} lo
 * @param {number} hi
 * @param {number} target
 * @return {number[][]}
 */
const kSum = function (k, nums, lo, hi, target) {
    if (hi - lo + 1 < k) {
        return [];
    }
    if (k === 2) {
        return twoSum(nums, lo, hi, target);
    }
    const res = [];
    let i = lo;
    while (i <= hi) {
        const curNum = nums[i];
        const sp = kSum(k - 1, nums, i + 1, hi, target - curNum);
        for (const a of sp) {
            a.push(curNum);
            res.push(a);
        }
        while (++i <= hi && nums[i] === curNum) {
        }
    }
    return res;
};

/**
 * 返回升序子数组 nums[lo..hi] 中所有和为 target 且不重复的二元组
 * @param {number[]} nums
 * @param {number} lo
 * @param {number} hi
 * @param {number} target
 * @return {number[][]}
 */
const twoSum = function (nums, lo, hi, target) {
    const res = [];
    while (lo < hi) {
        const first = nums[lo], second = nums[hi];
        const sum = first + second;
        if (sum < target) {
            while (++lo < hi && nums[lo] === first) {
            }
        } else if (sum > target) {
            while (lo < --hi && nums[hi] === second) {
            }
        } else {
            res.push([first, second]);
            while (++lo < hi && nums[lo] === first) {
            }
            while (lo < --hi && nums[hi] === second) {
            }
        }
    }
    return res;
};
// https://leetcode.cn/submissions/detail/380878482/
```

## 19. 删除链表的倒数第 N 个结点

<https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/>

```js
/**
 * @param {ListNode} head
 * @param {number} n
 * @return {ListNode}
 */
 var removeNthFromEnd = function (head, n) {
    const dummyHead = new ListNode(-1, head);
    let slow = dummyHead, fast = dummyHead;
    for (let i = 1; i <= n; ++i) {
        fast = fast.next;
    }
    while (fast !== null && fast.next !== null) {
        slow = slow.next;
        fast = fast.next;
    }
    const delNode = slow.next;
    if (delNode === head) { // 删除的是头结点
        head = head.next;
    } else {
        slow.next = delNode.next;
    }
    return head;
};
// https://leetcode.cn/submissions/detail/380806133/
```

## 20. 有效的括号

<https://leetcode-cn.com/problems/valid-parentheses/>

```js
/**
 * @param {string} s
 * @return {boolean}
 */
 const isValid = function (s) {
    if (s.length % 2 === 1) {
        return false;
    }
    const stack = [];
    for (const ch of s) {
        switch (ch) {
            case '(': {
                stack.push(')');
                break;
            }
            case '[': {
                stack.push(']');
                break;
            }
            case '{': {
                stack.push('}');
                break;
            }
            default: {
                if (stack.length === 0 || stack.pop() !== ch) {
                    return false;
                }
                break;
            }
        }
    }
    return stack.length === 0;
};
// https://leetcode.cn/submissions/detail/380973229/
```

## 21. 合并两个有序链表

<https://leetcode-cn.com/problems/merge-two-sorted-lists/>

```js
/**
 * @param {ListNode} list1
 * @param {ListNode} list2
 * @return {ListNode}
 */
 const mergeTwoLists = function (list1, list2) {
    const dummyHead = new ListNode();
    let ptr = dummyHead;
    while (list1 != null && list2 != null) {
        if (list1.val < list2.val) {
            ptr.next = list1;
            list1 = list1.next;
        } else {
            ptr.next = list2;
            list2 = list2.next;
        }
        ptr = ptr.next;
    }
    ptr.next = (list1 == null ? list2 : list1);
    return dummyHead.next;
};
// https://leetcode.cn/submissions/detail/380955494/
```

## 22. 括号生成

<https://leetcode.cn/problems/generate-parentheses/>

```js
/**
 * @param {number} n
 * @return {string[]}
 */
 const generateParenthesis = function (n) {
    let left = 0;    // 已使用的『左括号』数量
    let right = 0;   // 已使用的『右括号』数量
    const path = []; // 取 '(', ')' 为元素
    const ans = [];

    const backtrack = function () {
        // 对于一个「合法」的括号字符串组合 p，必然对于任何 0 <= i < len(p) 都有：
        // 子串 p[0..i] 中左括号的数量都大于或等于右括号的数量
        if (left < right || left > n) {
            return;
        }
        // 一个「合法」括号组合的左括号数量一定等于右括号数量
        if (left === n && right === n) {
            ans.push(path.join(""));
            return;
        }
        // edge = 取 '(', ')' 为值
        // 使用『左括号』
        path.push('(');
        ++left;
        backtrack();
        path.pop();
        --left;
        // 使用『右括号』
        path.push(')');
        ++right;
        backtrack();
        path.pop();
        --right;
    };

    backtrack();
    return ans;
};
// https://leetcode.cn/submissions/detail/380978280/
```

## 23. 合并 K 个升序链表

<https://leetcode-cn.com/problems/merge-k-sorted-lists/>

```js
/**
 * @param {ListNode[]} lists
 * @return {ListNode}
 */
 const mergeKLists = function (lists) {
    return mergeKListsRange(lists, 0, lists.length - 1);
};

/**
 * 合并升序链表子数组 lists[lo..hi]，返回合并后的链表
 * @param {ListNode[]} lists
 * @param {number} lo
 * @param {number} hi
 * @return {ListNode}
 */
const mergeKListsRange = function (lists, lo, hi) {
    if (lo > hi) {
        return null;
    }
    if (lo === hi) {
        return lists[lo];
    }
    const mid = lo + Math.floor((hi - lo) / 2);
    const left = mergeKListsRange(lists, lo, mid);
    const right = mergeKListsRange(lists, mid + 1, hi);
    return mergeTwoLists(left, right);
};

/**
 * @param {ListNode} list1
 * @param {ListNode} list2
 * @return {ListNode}
 */
const mergeTwoLists = function (list1, list2) {
    const dummyHead = new ListNode();
    let ptr = dummyHead;
    while (list1 != null && list2 != null) {
        if (list1.val < list2.val) {
            ptr.next = list1;
            list1 = list1.next;
        } else {
            ptr.next = list2;
            list2 = list2.next;
        }
        ptr = ptr.next;
    }
    ptr.next = (list1 == null ? list2 : list1);
    return dummyHead.next;
};
// https://leetcode.cn/submissions/detail/380957426/
```

## 24. 两两交换链表中的节点

<https://leetcode-cn.com/problems/swap-nodes-in-pairs/>

```js
/**
 * @param {ListNode} head
 * @return {ListNode}
 */
 const swapPairs = function (head) {
    if (head == null || head.next == null) {
        return head;
    }
    const x = head;
    const y = head.next;
    const z = head.next.next;
    y.next = x;
    x.next = swapPairs(z);
    return y;
};
// https://leetcode.cn/submissions/detail/380943503/
```

## 25. K 个一组翻转链表

<https://leetcode.cn/problems/reverse-nodes-in-k-group/>

```js
/**
 * @param {ListNode} head
 * @param {number} k
 * @return {ListNode}
 */
 const reverseKGroup = function (head, k) {
    let ptr = head;
    for (let i = 1; i <= k - 1 && ptr != null; ++i) {
        ptr = ptr.next;
    }
    if (ptr == null) {
        return head;
    }
    const nextGroup = ptr.next;
    ptr.next = null;
    const reverseHead = reverseList(head);
    head.next = reverseKGroup(nextGroup, k);
    return reverseHead;
};

/**
 * @param {ListNode} head
 * @return {ListNode}
 */
const reverseList = function (head) {
    let reverseHead = null;
    while (head !== null) {
        const nextHead = head.next;
        head.next = reverseHead;
        reverseHead = head;
        head = nextHead;
    }
    return reverseHead;
};
// https://leetcode.cn/submissions/detail/380942577/
```

## 26. 删除有序数组中的重复项

<https://leetcode.cn/problems/remove-duplicates-from-sorted-array/>

```js
/**
 * @param {number[]} nums
 * @return {number}
 */
 var removeDuplicates = function (nums) {
    const n = nums.length;
    // [0..i-1] 不重复元素区间
    // [i..j-1] 重复元素区间
    // [j..n-1] 扫描区间
    let i = 0, j = 0;
    while (j < n) {
        while (j + 1 < n && nums[j] === nums[j + 1]) {
            ++j;
        }
        [nums[i], nums[j]] = [nums[j], nums[i]]
        ++i;
        ++j;
    }
    return i;
};
// https://leetcode.cn/submissions/detail/380801778/
```

## 27. 移除元素

<https://leetcode.cn/problems/remove-element/>

```js
/**
 * @param {number[]} nums
 * @param {number} val
 * @return {number}
 */
 var removeElement = function (nums, val) {
    // nums[0..i-1]   != val
    // nums[i..j]     Scanning
    // nums[j+1..n-1] == val
    let i = 0, j = nums.length - 1
    while (i <= j) {
        while (i <= j && nums[i] !== val) {
            ++i;
        }
        while (i <= j && nums[j] === val) {
            --j;
        }
        if (i <= j) {
            nums[i++] = nums[j--]
        }
    }
    return i;
};
// https://leetcode.cn/submissions/detail/380798088/
```

## 28. 实现 strStr()

<https://leetcode.cn/problems/implement-strstr/>

```js
class KMP {
    constructor(pat) {
        this.m = pat.length;
        const R = 256;
        this.dfa = new Array(R);
        for (let c = 0; c < R; ++c) {
            this.dfa[c] = new Array(this.m).fill(0);
        }
        this.dfa[pat.charCodeAt(0)][0] = 1;
        for (let x = 0, j = 1; j < this.m; ++j) {
            for (let c = 0; c < R; ++c) {
                this.dfa[c][j] = this.dfa[c][x];
            }
            this.dfa[pat.charCodeAt(j)][j] = j + 1;
            x = this.dfa[pat.charCodeAt(j)][x];
        }
    }

    search(txt) {
        const n = txt.length;
        let i, j;
        for (i = 0, j = 0; i < n && j < this.m; ++i) {
            j = this.dfa[txt.charCodeAt(i)][j];
        }
        if (j === this.m) {
            return i - this.m;
        }
        return -1;
    }
}

/**
 * @param {string} haystack
 * @param {string} needle
 * @return {number}
 */
const strStr = function (haystack, needle) {
    const kmp = new KMP(needle);
    return kmp.search(haystack);
};
// https://leetcode.cn/submissions/detail/382060312/
```

```js
class BoyerMoore {
    constructor(pat) {
        this.pat = pat;
        this.right = new Array(256).fill(-1);
        for (let j = 0; j < pat.length; ++j) {
            this.right[pat.charCodeAt(j)] = j;
        }
    }

    search(txt) {
        const m = this.pat.length;
        const n = txt.length;
        let skip;
        for (let i = 0; i <= n - m; i += skip) {
            skip = 0;
            for (let j = m - 1; j >= 0; --j) {
                if (this.pat.charAt(j) !== txt.charAt(i + j)) {
                    skip = Math.max(1, j - this.right[txt.charCodeAt(i + j)]);
                    break;
                }
            }
            if (skip === 0) {
                return i;
            }
        }
        return -1;
    }
}

/**
 * @param {string} haystack
 * @param {string} needle
 * @return {number}
 */
const strStr = function (haystack, needle) {
    const bm = new BoyerMoore(needle);
    return bm.search(haystack);
};
// https://leetcode.cn/submissions/detail/382063341/
```

## 33. 搜索旋转排序数组

<https://leetcode.cn/problems/search-in-rotated-sorted-array/>

```js
/**
 * @param {number[]} nums
 * @param {number} target
 * @return {number}
 */
 const search = function (nums, target) {
    let lo = 0, hi = nums.length - 1;
    while (lo <= hi) {
        const mid = lo + Math.floor((hi - lo) / 2);
        if (nums[mid] === target) {
            return mid;
        }
        // 当 lo = hi 时，nums[lo] = nums[mid] = nums[hi]，
        // 此时 nums[mid] < target <= nums[hi] 不成立
        if (nums[mid] <= nums[hi]) {
            if (nums[mid] < target && target <= nums[hi]) {
                lo = mid + 1;
            } else {
                hi = mid - 1;
            }
        } else {
            if (nums[lo] <= target && target < nums[mid]) {
                hi = mid - 1;
            } else {
                lo = mid + 1;
            }
        }
    }
    return -1;
};
// https://leetcode.cn/submissions/detail/380965698/
```

## 34. 在排序数组中查找元素的第一个和最后一个位置

<https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/>

```js
/**
 * @param {number[]} nums
 * @param {number} target
 * @return {number[]}
 */
const searchRange = function (nums, target) {
    return [search(nums, target, true), search(nums, target, false)];
};

const search = function (nums, target, lower) {
    let res = -1;
    let lo = 0, hi = nums.length - 1;
    while (lo <= hi) {
        const mid = lo + Math.floor((hi - lo) / 2);
        if (target < nums[mid]) {
            hi = mid - 1;
        } else if (nums[mid] < target) {
            lo = mid + 1;
        } else {
            res = mid;
            if (lower) {
                hi = mid - 1;
            } else {
                lo = mid + 1;
            }
        }
    }
    return res;
};
// https://leetcode.cn/submissions/detail/381717350/
```

## 37. 解数独

<https://leetcode.cn/problems/sudoku-solver/>

```js
/**
 * @param {string[][]} board
 * @return {void} Do not return anything, modify board in-place instead.
 */
const solveSudoku = function (board) {
    backtrack(board, 0, -1);
};

// 遍历『决策森林』
// tree  = row
// level = (row, col)
const backtrack = function (board, row, col) {
    const n = board.length;
    let res = false;
    if (row === n - 1 && col === n - 1) {
        res = true;
    } else if (row < n - 1 && col === n - 1) {
        // 遍历下一棵『决策树』
        res = backtrack(board, row + 1, -1);
    } else if (board[row][col + 1] !== '.') {
        res = backtrack(board, row, col + 1);
    } else {
        // edge = ['1'..'9']
        for (let ch of "123456789") {
            if (isValid(board, row, col + 1, ch)) {
                board[row][col + 1] = ch;
                res = backtrack(board, row, col + 1);
                if (res) {
                    break;
                }
                board[row][col + 1] = '.';
            }
        }
    }
    return res;
};

// board[row][col] 填入数字 ch 是否有效
const isValid = function (board, row, col, ch) {
    for (let i = 0; i < board.length; ++i) {
        // 同一行
        if (board[row][i] === ch) {
            return false;
        }
        // 同一列
        if (board[i][col] === ch) {
            return false;
        }
        // 同九宫
        if (board[Math.floor(row / 3) * 3 + Math.floor(i / 3)][Math.floor(col / 3) * 3 + i % 3] === ch) {
            return false;
        }
    }
    return true;
};
// https://leetcode.cn/submissions/detail/381832278/
```

## 39. 组合总和

<https://leetcode.cn/problems/combination-sum/>

```js
/**
 * @param {number[]} candidates
 * @param {number} target
 * @return {number[][]}
 */
 const combinationSum = function (candidates, target) {
    let pathSum = 0;
    const path = []; // 取 nums[edge] 为元素
    const ans = [];

    // edge = 取数组 nums 的索引为值
    const backtrack = function (edge) {
        if (pathSum === target) {
            ans.push([...path]);
            return;
        }
        if (edge === -1) {
            edge = 0;
        }
        // 避免重复，从 edge 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (edge < candidates.length) {
            const x = candidates[edge];
            if (pathSum + x <= target) {
                pathSum += x;
                path.push(x);
                backtrack(edge);
                pathSum -= x;
                path.pop();
            }
            ++edge;
        }
    }

    backtrack(-1);
    return ans;
};
// https://leetcode.cn/submissions/detail/381234482/
```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```js
/**
 * @param {number[]} candidates
 * @param {number} target
 * @return {number[][]}
 */
 const combinationSum2 = function (candidates, target) {
    let pathSum = 0;
    const path = []; // 取 nums[edge] 为元素
    const ans = [];

    // edge = 取数组 nums 的索引为值
    const backtrack = function (edge) {
        if (pathSum === target) {
            ans.push([...path]);
            return;
        }
        let prev = Number.NEGATIVE_INFINITY;
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge < candidates.length) {
            const x = candidates[edge];
            if (x !== prev && pathSum + x <= target) {
                prev = x;
                pathSum += x;
                path.push(x);
                backtrack(edge);
                pathSum -= x;
                path.pop();
            }
        }
    }

    candidates.sort((a, b) => a - b);
    backtrack(-1);
    return ans;
};
// https://leetcode.cn/submissions/detail/381235954/
```

## 42. 接雨水

<https://leetcode.cn/problems/trapping-rain-water/>

```js
/**
 * @param {number[]} height
 * @return {number}
 */
 const trap = function (height) {
    const n = height.length;
    // leftMax[i] = max(height[0..i])
    const leftMax = [...height];
    for (let i = 1; i <= n - 1; ++i) {
        leftMax[i] = Math.max(height[i], leftMax[i - 1]);
    }
    // rightMax[i] = max(height[i..n-1])
    const rightMax = [...height];
    for (let i = n - 2; i >= 0; --i) {
        rightMax[i] = Math.max(height[i], rightMax[i + 1]);
    }
    let sum = 0;
    for (let i = 0; i < n; ++i) {
        sum += Math.min(leftMax[i], rightMax[i]) - height[i];
    }
    return sum;
};
// https://leetcode.cn/submissions/detail/380902797/
```

## 46. 全排列

<https://leetcode.cn/problems/permutations/>

```js
/**
 * @param {number[]} nums
 * @return {number[][]}
 */
 const permute = function (nums) {
    const path = []; // 取 nums[edge] 为元素
    const ans = [];
    const n = nums.length;
    const marked = new Array(n).fill(false);

    const backtrack = function () {
        if (path.length === n) {
            ans.push([...path]);
            return;
        }
        // edge = 取数组 nums 的索引为值
        for (let edge = 0; edge < n; ++edge) {
            if (!marked[edge]) {
                marked[edge] = true;
                path.push(nums[edge]);
                backtrack();
                marked[edge] = false;
                path.pop();
            }
        }
    }

    backtrack();
    return ans;
};
// https://leetcode.cn/submissions/detail/381240656/
```

## 47. 全排列 II

<https://leetcode.cn/problems/permutations-ii/>

```js
/**
 * @param {number[]} nums
 * @return {number[][]}
 */
 const permuteUnique = function (nums) {
    const path = []; // 取 nums[edge] 为元素
    const ans = [];
    const n = nums.length;
    const marked = new Array(n).fill(false);

    const backtrack = function () {
        if (path.length === n) {
            ans.push([...path]);
            return;
        }
        let prev = Number.NEGATIVE_INFINITY;
        // edge = 取数组 nums 的索引为值
        for (let edge = 0; edge < n; ++edge) {
            const x = nums[edge];
            if (!marked[edge] && x !== prev) {
                prev = x;
                marked[edge] = true;
                path.push(x);
                backtrack();
                marked[edge] = false;
                path.pop();
            }
        }
    }

    nums.sort((a, b) => a - b);
    backtrack();
    return ans;
};
// https://leetcode.cn/submissions/detail/381242321/
```

## 51. N 皇后

<https://leetcode.cn/problems/n-queens/>

```js
/**
 * @param {number} n
 * @return {string[][]}
 */
const solveNQueens = function (n) {
    const board = new Array(n);
    for (let i = 0; i < n; ++i) {
        board[i] = new Array(n).fill('.');
    }
    const ans = [];

    // board[row][col] 放置 Q 是否有效
    const isValid = function (board, row, col) {
        // 同一列
        for (let r = row - 1; r >= 0; --r) {
            if (board[r][col] === 'Q') {
                return false;
            }
        }
        // 右斜线
        for (let r = row - 1, c = col + 1; r >= 0 && c < board.length; --r, ++c) {
            if (board[r][c] === 'Q') {
                return false;
            }
        }
        // 左斜线
        for (let r = row - 1, c = col - 1; r >= 0 && c >= 0; --r, --c) {
            if (board[r][c] === 'Q') {
                return false;
            }
        }
        return true;
    };

    // level = row
    const backtrack = function (board, row) {
        const n = board.length;
        if (row === n - 1) {
            const solution = [];
            for (const x of board) {
                solution.push(x.join(""));
            }
            ans.push(solution);
            return;
        }
        // edge = col
        for (let col = 0; col < n; ++col) {
            if (isValid(board, row + 1, col)) {
                board[row + 1][col] = 'Q';
                backtrack(board, row + 1);
                board[row + 1][col] = '.';
            }
        }
    };

    backtrack(board, -1);
    return ans;
};
// https://leetcode.cn/submissions/detail/381838360/
```

## 52. N 皇后 II

<https://leetcode.cn/problems/n-queens-ii/>

```js
/**
 * @param {number} n
 * @return {number}
 */
const totalNQueens = function (n) {
    const board = new Array(n);
    for (let i = 0; i < n; ++i) {
        board[i] = new Array(n).fill('.');
    }
    let ans = 0;

    // board[row][col] 放置 Q 是否有效
    const isValid = function (board, row, col) {
        // 同一列
        for (let r = row - 1; r >= 0; --r) {
            if (board[r][col] === 'Q') {
                return false;
            }
        }
        // 右斜线
        for (let r = row - 1, c = col + 1; r >= 0 && c < board.length; --r, ++c) {
            if (board[r][c] === 'Q') {
                return false;
            }
        }
        // 左斜线
        for (let r = row - 1, c = col - 1; r >= 0 && c >= 0; --r, --c) {
            if (board[r][c] === 'Q') {
                return false;
            }
        }
        return true;
    };

    // level = row
    const backtrack = function (board, row) {
        const n = board.length;
        if (row === n - 1) {
            ++ans;
            return;
        }
        // edge = col
        for (let col = 0; col < n; ++col) {
            if (isValid(board, row + 1, col)) {
                board[row + 1][col] = 'Q';
                backtrack(board, row + 1);
                board[row + 1][col] = '.';
            }
        }
    };

    backtrack(board, -1);
    return ans;
};
// https://leetcode.cn/submissions/detail/381839156/
```

## 53. 最大子数组和

<https://leetcode.cn/problems/maximum-subarray/>

```js
/**
 * @param {number[]} nums
 * @return {number}
 */
 const maxSubArray = function (nums) {
    // dp[i] = max({sum(subarray) | subarray 是任意以 nums[i] 结尾的子数组})
    const dp = [...nums];
    let ans = dp[0];
    for (let i = 1; i < nums.length; ++i) {
        dp[i] = Math.max(nums[i], dp[i - 1] + nums[i]);
        ans = Math.max(ans, dp[i]);
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381107911/
```

## 56. 合并区间

<https://leetcode.cn/problems/merge-intervals/>

```js
/**
 * @param {number[][]} intervals
 * @return {number[][]}
 */
 const merge = function (intervals) {
    intervals.sort((a, b) => {
        if (a[0] === b[0]) {
            return b[1] - a[1];
        }
        return a[0] - b[0];
    });
    const ans = [];
    let [mStart, mEnd] = intervals[0];
    for (let i = 1; i < intervals.length; ++i) {
        const [start, end] = intervals[i];
        if (start <= mEnd) { // 重叠
            mEnd = Math.max(mEnd, end);
        } else { // 不重叠
            ans.push([mStart, mEnd]);
            mStart = start;
            mEnd = end;
        }
    }
    ans.push([mStart, mEnd]);
    return ans;
};
// https://leetcode.cn/submissions/detail/381051976/
```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```js
/**
 * @param {number[][]} grid
 * @return {number}
 */
const minPathSum = function (grid, row = grid.length - 1, col = grid[0].length - 1,
                             memo = Array.from(new Array(grid.length), (_) => new Array(grid[0].length))) {
    if (row < 0 || col < 0) {
        return Number.POSITIVE_INFINITY;
    }
    if (row === 0 && col === 0) {
        return grid[row][col];
    }
    if (memo[row][col] === undefined) {
        const sp1 = minPathSum(grid, row - 1, col, memo);
        const sp2 = minPathSum(grid, row, col - 1, memo);
        memo[row][col] = Math.min(sp1, sp2) + grid[row][col];
    }
    return memo[row][col];
}
// https://leetcode.cn/submissions/detail/381308877/
```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```js
/**
 * @param {number} x
 * @return {number}
 */
const mySqrt = function (x) {
    if (x === 0) {
        return 0;
    }
    let lo = 1, hi = x;
    while (lo <= hi) {
        const mid = lo + Math.floor((hi - lo) / 2);
        if (mid <= x / mid && (mid + 1) > x / (mid + 1)) {
            return mid;
        }
        if (mid <= x / mid) {
            lo = mid + 1;
        } else {
            hi = mid - 1;
        }
    }
    return -1;
};
// https://leetcode.cn/submissions/detail/381701400/
```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```js
/**
 * @param {number} n
 * @return {number}
 */
const climbStairs = function (n) {
    if (n === 1) {
        return 1;
    }
    if (n === 2) {
        return 2;
    }
    // dp[i] = 楼梯有 i 阶时，有几种不同的方法
    const dp = new Array(n + 1);
    dp[1] = 1;
    dp[2] = 2;
    for (let i = 3; i <= n; i++) {
        dp[i] = dp[i - 1] + dp[i - 2];
    }
    return dp[n];
};
// https://leetcode.cn/submissions/detail/381718297/
```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```js
/**
 * @param {string} word1
 * @param {string} word2
 * @return {number}
 */
 const minDistance = function (word1, word2) {
    const n1 = word1.length;
    const n2 = word2.length;
    const memo = new Array(n1);
    for (let i = 0; i < n1; ++i) {
        memo[i] = new Array(n2).fill(-1);
    }

    // 子串 s1[0..i] s2[0..j] 的最小编辑距离
    const _minDistance = function (s1, i, s2, j) {
        // 插入 s2[0..j] 到 s1
        // s1""
        // s2[0..j]
        if (i < 0) {
            return j + 1;
        }
        // 删除 s1[0..i]
        // s1[0..i]
        // s2""
        if (j < 0) {
            return i + 1;
        }
        if (memo[i][j] === -1) {
            if (s1.charAt(i) === s2.charAt(j)) {
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                memo[i][j] = _minDistance(s1, i - 1, s2, j - 1);
            } else {
                // 替换 s1[i] 为 s2[j]
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                const sp1 = _minDistance(s1, i - 1, s2, j - 1) + 1;
                // 插入 s2[j] 到 s1
                // s1[0..i]
                // s2[0..j-1][j]
                const sp2 = _minDistance(s1, i, s2, j - 1) + 1;
                // 删除 s1[i]
                // s1[0..i-1][i]
                // s2[0..j]
                const sp3 = _minDistance(s1, i - 1, s2, j) + 1;
                memo[i][j] = Math.min(Math.min(sp1, sp2), sp3);
            }
        }
        return memo[i][j];
    };

    return _minDistance(word1, n1 - 1, word2, n2 - 1);
};
// https://leetcode.cn/submissions/detail/381148401/
```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```js
/**
 * @param {number[]} nums
 * @return {void} Do not return anything, modify nums in-place instead.
 */
const sortColors = function (nums) {
    const v = 1;
    let lt = 0, gt = nums.length - 1;
    let i = 0;
    while (i <= gt) {
        const x = nums[i];
        if (x < v) {
            swap(nums, lt++, i++);
        } else if (x > v) {
            swap(nums, i, gt--);
        } else {
            ++i;
        }
    }
};

const swap = function (nums, i, j) {
    const x = nums[i];
    nums[i] = nums[j];
    nums[j] = x;
};
// https://leetcode.cn/submissions/detail/381880814/
```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```js
/**
 * @param {string} s
 * @param {string} t
 * @return {string}
 */
 const minWindow = function (s, t) {
    const need = new Map();
    for (const c of t) {
        if (!need.has(c)) {
            need.set(c, 0);
        }
        need.set(c, need.get(c) + 1);
    }
    const window = new Map();
    let valid = 0;
    let start = 0, len = Number.POSITIVE_INFINITY;
    // s[left..right) = Window Substring
    // s[right..n-1]  = Scanning
    let left = 0, right = 0;
    while (right < s.length) {
        const c = s.charAt(right++);
        if (need.has(c)) {
            if (!window.has(c)) {
                window.set(c, 0);
            }
            window.set(c, window.get(c) + 1);
            if (window.get(c) === need.get(c)) {
                ++valid;
            }
        }
        if (valid === need.size) {
            while (left < right) {
                const d = s.charAt(left);
                if (need.has(d) && window.get(d) === need.get(d)) {
                    break;
                }
                if (need.has(d)) {
                    window.set(d, window.get(d) - 1);
                }
                ++left;
            }
            if (right - left < len) {
                start = left;
                len = right - left;
            }
        }
    }
    return len === Number.POSITIVE_INFINITY ? "" : s.substring(start, start + len);
};
// https://leetcode.cn/submissions/detail/381062564/
```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```js
/**
 * @param {number} n
 * @param {number} k
 * @return {number[][]}
 */
 const combine = function (n, k) {
    const path = []; // 取 [1..n] 为元素
    const ans = [];

    // edge = 取 [1..n] 为值
    const backtrack = function (edge) {
        if (path.length === k) {
            ans.push([...path]);
            return;
        }
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge <= n) {
            path.push(edge);
            backtrack(edge);
            path.pop();
        }
    }

    backtrack(0);
    return ans;
};
// https://leetcode.cn/submissions/detail/381232355/
```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```js
/**
 * @param {number[]} nums
 * @return {number[][]}
 */
 const subsets = function (nums) {
    const path = []; // 取 nums[edge] 为元素
    const ans = [];

    // edge = 取数组 nums 的索引为值
    const backtrack = function (edge) {
        ans.push([...path]);
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge < nums.length) {
            path.push(nums[edge]);
            backtrack(edge);
            path.pop();
        }
    }

    backtrack(-1);
    return ans;
};
// https://leetcode.cn/submissions/detail/381229060/
```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```js
/**
 * @param {number[]} nums
 * @param {number} target
 * @return {boolean}
 */
 const search = function (nums, target) {
    let lo = 0, hi = nums.length - 1;
    while (lo <= hi) {
        const mid = lo + Math.floor((hi - lo) / 2);
        if (nums[mid] === target) {
            return true;
        }
        if (nums[lo] === nums[mid] && nums[mid] === nums[hi]) {
            ++lo;
            --hi;
        } else {
            if (nums[mid] <= nums[hi]) {
                if (nums[mid] < target && target <= nums[hi]) {
                    lo = mid + 1;
                } else {
                    hi = mid - 1;
                }
            } else {
                if (nums[lo] <= target && target < nums[mid]) {
                    hi = mid - 1;
                } else {
                    lo = mid + 1;
                }
            }
        }
    }
    return false;
};
// https://leetcode.cn/submissions/detail/380966742/
```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```js
/**
 * @param {ListNode} head
 * @return {ListNode}
 */
const deleteDuplicates = function (head) {
    let ptr = head;
    while (ptr != null && ptr.next != null) {
        if (ptr.val === ptr.next.val) {
            ptr.next = ptr.next.next;
        } else {
            ptr = ptr.next;
        }
    }
    return head;
};
// https://leetcode.cn/submissions/detail/381695036/
```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```js
/**
 * @param {ListNode} head
 * @param {number} x
 * @return {ListNode}
 */
const partition = function (head, x) {
    const dummyLess = new ListNode();
    let ptrLess = dummyLess;
    const dummyGreater = new ListNode();
    let ptrGreater = dummyGreater;
    while (head != null) {
        if (head.val < x) {
            ptrLess.next = head;
            ptrLess = ptrLess.next;
        } else {
            ptrGreater.next = head;
            ptrGreater = ptrGreater.next;
        }
        head = head.next;
    }
    ptrLess.next = dummyGreater.next;
    ptrGreater.next = null;
    return dummyLess.next;
};
// https://leetcode.cn/submissions/detail/381698621/
```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```js
/**
 * @param {number[]} nums
 * @return {number[][]}
 */
 const subsetsWithDup = function (nums) {
    const path = []; // 取 nums[edge] 为元素
    const ans = [];
    // edge = 取数组 nums 的索引为值
    const backtrack = function (edge) {
        ans.push([...path]);
        let prev = Number.NEGATIVE_INFINITY;
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge < nums.length) {
            const x = nums[edge];
            if (x !== prev) {
                prev = x;
                path.push(x);
                backtrack(edge);
                path.pop();
            }
        }
    }
    nums.sort((a, b) => a - b);
    backtrack(-1);
    return ans;
};
// https://leetcode.cn/submissions/detail/381230708/
```

## 92. 反转链表 II

<https://leetcode-cn.com/problems/reverse-linked-list-ii/>

```js
/**
 * @param {ListNode} head
 * @param {number} left
 * @param {number} right
 * @return {ListNode}
 */
 const reverseBetween = function (head, left, right) {
    if (left === 1) {
        return reverseList(head, right);
    }
    let ptr = head;
    for (let i = 1; i <= left - 2; ++i) {
        ptr = ptr.next;
    }
    ptr.next = reverseList(ptr.next, right - left + 1);
    return head;
};

/**
 * 翻转链表的前 n 个节点，返回翻转后的头节点
 * @param {ListNode} head
 * @param {number} n
 * @return {ListNode}
 */
const reverseList = function (head, n) {
    let reverseHead = null;
    let ptr = head;
    while (ptr != null && n > 0) {
        const nextHead = ptr.next;
        ptr.next = reverseHead;
        reverseHead = ptr;
        ptr = nextHead;
        --n;
    }
    head.next = ptr;
    return reverseHead;
};
// https://leetcode.cn/submissions/detail/380941108/
```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```js
/**
 * @param {TreeNode} root
 * @return {number[]}
 */
 const inorderTraversal = function (root) {
    const ans = [];

    const dfs = function (x) {
        if (x == null) {
            return;
        }
        dfs(x.left);
        ans.push(x.val);
        dfs(x.right);
    };

    dfs(root);
    return ans;
};
// https://leetcode.cn/submissions/detail/381254174/
```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```js
/**
 * @param {number} n
 * @return {TreeNode[]}
 */
const generateTrees = function (n, lo = 1, hi = n) {
    if (lo > hi) {
        return [null];
    }
    const res = [];
    for (let i = lo; i <= hi; ++i) {
        const leftTrees = generateTrees(n, lo, i - 1);
        const rightTrees = generateTrees(n, i + 1, hi);
        for (const left of leftTrees) {
            for (const right of rightTrees) {
                res.push(new TreeNode(i, left, right));
            }
        }
    }
    return res;
};
// https://leetcode.cn/submissions/detail/381340070/
```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```js
/**
 * 由 n 个不同数字 x_1 < x_2 < ... < x_n
 * 组成的节点值互不相同的二叉搜索树的种数
 * @param {number} n
 * @return {number}
 */
const numTrees = function (n, memo = new Map()) {
    if (n <= 1) {
        return 1;
    }
    if (!memo.has(n)) {
        let res = 0;
        // 根节点为 x_i
        // 左子树由 i-1 个数字 x1 < x2 < ... < x_i-1 组成
        // 右子树由 n-i 个数字 x_i+1 < x_i+2 < ... < x_n 组成
        for (let i = 1; i <= n; ++i) {
            res += numTrees(i - 1, memo) * numTrees(n - i, memo);
        }
        memo.set(n, res);
    }
    return memo.get(n);
};
// https://leetcode.cn/submissions/detail/381338928/
```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```js
/**
 * @param {TreeNode} root
 * @return {boolean}
 */
const isValidBST = function (root) {
    let ans = true;

    // 检查二叉树是否在区间 (lower, upper) 内
    // 递归过程中确定是否满足二叉搜索树的性质
    const lowerUpper = function (x, lower, upper) {
        if (x == null) {
            return true;
        }
        if (lower !== undefined && x.val <= lower) {
            ans = false;
            return false;
        }
        if (upper !== undefined && x.val >= upper) {
            ans = false;
            return false;
        }
        return lowerUpper(x.left, lower, x.val)
            && lowerUpper(x.right, x.val, upper);
    };

    lowerUpper(root, undefined, undefined);
    return ans;
};
// https://leetcode.cn/submissions/detail/381574858/
```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```js
/**
 * @param {TreeNode} p
 * @param {TreeNode} q
 * @return {boolean}
 */
 const isSameTree = function (p, q) {
    if (p == null && q == null) {
        return true;
    }
    if (p == null || q == null || p.val !== q.val) {
        return false;
    }
    return isSameTree(p.left, q.left) && isSameTree(p.right, q.right);
};
// https://leetcode.cn/submissions/detail/381491942/
```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```js
/**
 * @param {TreeNode} root
 * @return {number[][]}
 */
 const levelOrder = function (root) {
    const ans = [];
    const queue = new Queue();
    if (root != null) {
        queue.enqueue(root);
    }
    while (!queue.isEmpty()) {
        const level = [];
        const n = queue.size();
        for (let i = 0; i < n; ++i) {
            const x = queue.dequeue();
            level.push(x.val);
            const left = x.left;
            if (left != null) {
                queue.enqueue(left);
            }
            const right = x.right;
            if (right != null) {
                queue.enqueue(right);
            }
        }
        ans.push(level);
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381257927/
```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```js
/**
 * @param {TreeNode} root
 * @return {number[][]}
 */
 const zigzagLevelOrder = function (root) {
    const ans = [];
    const queue = new Queue();
    if (root != null) {
        queue.enqueue(root);
    }
    let reverse = false;
    while (!queue.isEmpty()) {
        const level = [];
        const n = queue.size();
        for (let i = 0; i < n; ++i) {
            const x = queue.dequeue();
            level.push(x.val);
            const left = x.left;
            if (left != null) {
                queue.enqueue(left);
            }
            const right = x.right;
            if (right != null) {
                queue.enqueue(right);
            }
        }
        if (reverse) {
            level.reverse();
        }
        reverse = !reverse;
        ans.push(level);
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381260137/
```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```js
/**
 * @param {TreeNode} root
 * @return {number}
 */
 const maxDepth = function (root) {
    if (root == null) {
        return 0;
    }
    return 1 + Math.max(maxDepth(root.left), maxDepth(root.right));
};
// https://leetcode.cn/submissions/detail/381492828/
```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```js
/**
 * @param {number[]} preorder
 * @param {number[]} inorder
 * @return {TreeNode}
 */
const buildTree = function (preorder, inorder,
                            preStart = 0, preEnd = preorder.length - 1,
                            inStart = 0, inEnd = inorder.length - 1,
                            inorderMap = new Map(inorder.map((e, i) => [e, i]))) {
    if (preStart > preEnd) {
        return null;
    }
    const rootVal = preorder[preStart];
    const inRoot = inorderMap.get(rootVal);
    const leftSize = inRoot - inStart;
    const root = new TreeNode(rootVal);
    root.left = buildTree(preorder, inorder, preStart + 1, preStart + leftSize, inStart, inRoot - 1, inorderMap);
    root.right = buildTree(preorder, inorder, preStart + leftSize + 1, preEnd, inRoot + 1, inEnd, inorderMap);
    return root;
};
// https://leetcode.cn/submissions/detail/381409472/
```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```js
/**
 * @param {number[]} inorder
 * @param {number[]} postorder
 * @return {TreeNode}
 */
const buildTree = function (inorder, postorder,
                            inStart = 0, inEnd = inorder.length - 1,
                            postStart = 0, postEnd = postorder.length - 1,
                            inorderMap = new Map(inorder.map((e, i) => [e, i]))) {
    if (inStart > inEnd) {
        return null;
    }
    const rootVal = postorder[postEnd];
    const inRoot = inorderMap.get(rootVal);
    const leftSize = inRoot - inStart;
    const root = new TreeNode(rootVal);
    root.left = buildTree(inorder, postorder, inStart, inRoot - 1, postStart, postStart + leftSize - 1, inorderMap);
    root.right = buildTree(inorder, postorder, inRoot + 1, inEnd, postStart + leftSize, postEnd - 1, inorderMap);
    return root;
};
// https://leetcode.cn/submissions/detail/381408100/
```

## 107. 二叉树的层序遍历 II

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```js
/**
 * @param {TreeNode} root
 * @return {number[][]}
 */
 const levelOrderBottom = function (root) {
    const ans = [];
    const queue = new Queue();
    if (root != null) {
        queue.enqueue(root);
    }
    while (!queue.isEmpty()) {
        const level = [];
        const n = queue.size();
        for (let i = 0; i < n; ++i) {
            const x = queue.dequeue();
            level.push(x.val);
            const left = x.left;
            if (left != null) {
                queue.enqueue(left);
            }
            const right = x.right;
            if (right != null) {
                queue.enqueue(right);
            }
        }
        ans.push(level);
    }
    return ans.reverse();
};
// https://leetcode.cn/submissions/detail/381258637/
```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```js
/**
 * @param {number[]} nums
 * @return {TreeNode}
 */
 const sortedArrayToBST = function (nums, lo = 0, hi = nums.length - 1) {
    if (lo > hi) {
        return null;
    }
    const mid = lo + Math.floor((hi - lo) / 2);
    const root = new TreeNode(nums[mid]);
    root.left = sortedArrayToBST(nums, lo, mid - 1);
    root.right = sortedArrayToBST(nums, mid + 1, hi);
    return root;
};
// https://leetcode.cn/submissions/detail/381288201/
```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```js
/**
 * @param {TreeNode} root
 * @return {boolean}
 */
const isBalanced = function (root) {
    let ans = true;

    const height = function (x) {
        if (x == null) {
            return -1;
        }
        const left = height(x.left);
        const right = height(x.right);
        if (Math.abs(left - right) > 1) {
            ans = false;
        }
        return 1 + Math.max(left, right);
    };

    height(root);
    return ans;
};
// https://leetcode.cn/submissions/detail/381572583/
```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```js
/**
 * @param {TreeNode} root
 * @return {number}
 */
 const minDepth = function (root) {
    let depth = 0;
    const queue = new Queue();
    if (root != null) {
        queue.enqueue(root);
    }
    while (!queue.isEmpty()) {
        ++depth;
        const n = queue.size();
        for (let i = 0; i < n; ++i) {
            const x = queue.dequeue();
            const left = x.left;
            const right = x.right;
            if (x.left == null && x.right == null) {
                return depth;
            }
            if (left != null) {
                queue.enqueue(left);
            }
            if (right != null) {
                queue.enqueue(right);
            }
        }
    }
    return 0;
};
// https://leetcode.cn/submissions/detail/381491212/
```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```js
/**
 * @param {TreeNode} root
 * @param {number} targetSum
 * @return {boolean}
 */
const hasPathSum = function (root, targetSum) {
    if (root == null) {
        return false;
    }
    if (root.left == null && root.right == null) {
        return root.val === targetSum;
    }
    return hasPathSum(root.left, targetSum - root.val)
        || hasPathSum(root.right, targetSum - root.val);
};
// https://leetcode.cn/submissions/detail/381730224/
```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```js
/**
 * @param {TreeNode} root
 * @return {void} Do not return anything, modify root in-place instead.
 */
const flatten = function (root) {
    if (root == null) {
        return;
    }
    flatten(root.left);
    flatten(root.right);
    const left = root.left;
    const right = root.right;
    root.left = null;
    root.right = left;
    let ptr = root;
    while (ptr.right != null) {
        ptr = ptr.right;
    }
    ptr.right = right;
};
// https://leetcode.cn/submissions/detail/381571219/
```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```js

```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```js
/**
 * @param {number[]} prices
 * @return {number}
 */
 const maxProfit = function (prices) {
    const n = prices.length;
    // dp[i][0] = 第 i 天，空仓状态下的最大利润
    // dp[i][1] = 第 i 天，持仓状态下的最大利润
    const dp = new Array(n);
    for (let i = 0; i < n; ++i) {
        dp[i] = new Array(2).fill(0);
    }
    dp[0][0] = 0;
    dp[0][1] = -prices[0];
    for (let i = 1; i < n; ++i) {
        // dp[i - 1][0]             >= -prices[i]
        // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
        // => dp[i][0] >= dp[i][1]
        dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
        dp[i][1] = Math.max(-prices[i], dp[i - 1][1]);
    }
    return dp[n - 1][0];
};
// https://leetcode.cn/submissions/detail/381156356/
```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```js
/**
 * @param {number[]} prices
 * @return {number}
 */
 const maxProfit = function (prices) {
    const n = prices.length;
    // dp[i][0] = 第 i 天，空仓状态下的最大利润
    // dp[i][1] = 第 i 天，持仓状态下的最大利润
    const dp = new Array(n);
    for (let i = 0; i < n; ++i) {
        dp[i] = new Array(2).fill(0);
    }
    dp[0][0] = 0;
    dp[0][1] = -prices[0];
    for (let i = 1; i < n; ++i) {
        // dp[i - 1][0]             >= dp[i - 1][0] - prices[i]
        // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
        // => dp[i][0] >= dp[i][1]
        dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
        dp[i][1] = Math.max(dp[i - 1][0] - prices[i], dp[i - 1][1]);
    }
    return dp[n - 1][0];
};
// https://leetcode.cn/submissions/detail/381156687/
```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```js
/**
 * @param {number[]} prices
 * @return {number}
 */
 const maxProfit = function (prices) {
    return maxProfitK(2, prices);
};

/**
 * 返回买卖股票的最大利润，交易次数限制为 k
 * @param {number} k
 * @param {number[]} prices
 * @return {number}
 */
const maxProfitK = function (k, prices) {
    const n = prices.length;
    if (k <= 0 || n <= 1) {
        return 0;
    }
    // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
    // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
    const dp = new Array(k + 1);
    for (let t = 0; t <= k; ++t) {
        dp[t] = new Array(n);
        for (let i = 0; i < n; ++i) {
            dp[t][i] = new Array(2).fill(0);
        }
    }
    // 交易次数限制为 0 时
    // 填写第 0 个 n x 2 矩阵
    for (let i = 0; i < n; ++i) {
        dp[0][i][0] = 0;
        dp[0][i][1] = Number.NEGATIVE_INFINITY;
    }
    // 交易次数限制为 [1..k] 时
    for (let t = 1; t <= k; ++t) {
        // 填写第 t 个 n x 2 矩阵
        dp[t][0][0] = 0;
        dp[t][0][1] = -prices[0];
        for (let i = 1; i < n; ++i) {
            // dp[t][i - 1][0]             >= dp[t - 1][i - 1][0] - prices[i]
            // dp[t][i - 1][1] + prices[i] >= dp[t][i - 1][1]
            // => dp[t][i][0] >= dp[t][i][1]
            dp[t][i][0] = Math.max(dp[t][i - 1][0], dp[t][i - 1][1] + prices[i]);
            dp[t][i][1] = Math.max(dp[t - 1][i - 1][0] - prices[i], dp[t][i - 1][1]);
        }
    }
    return dp[k][n - 1][0];
};
// https://leetcode.cn/submissions/detail/381194682/
```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```js
/**
 * @param {string} s
 * @return {boolean}
 */
 var isPalindrome = function (s) {
    const n = s.length;
    let i = -1, j = n;
    while (true) {
        while (!isLetterOrDigit(s.charCodeAt(++i))) {
            if (i === n - 1) {
                break;
            }
        }
        while (!isLetterOrDigit(s.charCodeAt(--j))) {
            if (j === 0) {
                break;
            }
        }
        if (i >= j) {
            break;
        }
        if (s.charAt(i).toLowerCase() !== s.charAt(j).toLowerCase()) {
            return false;
        }
    }
    return true;
};

/**
 * @param {number} charCode
 * @return {boolean}
 */
const isLetterOrDigit = function (charCode) {
    return (charCode >= 48 && charCode <= 57)
        || (charCode >= 65 && charCode <= 90)
        || (charCode >= 97 && charCode <= 122);
}
// https://leetcode.cn/submissions/detail/380923579/
```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```js
/**
 * @param {number[]} nums
 * @return {number}
 */
 const longestConsecutive = function (nums) {
    let ans = 0;
    const set = new Set(nums);
    for (const x of nums) {
        if (set.has(x)) {
            let lo = x - 1;
            while (set.has(lo)) {
                set.delete(lo--);
            }
            let hi = x + 1;
            while (set.has(hi)) {
                set.delete(hi++);
            }
            ans = Math.max(ans, hi - lo - 1);
            set.delete(x);
        }
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381485348/
```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```js
const LAND = 'O';
const WATER = 'X';

/**
 * @param {string[][]} grid
 * @return {void} Do not return anything, modify board in-place instead.
 */
const solve = function (grid) {
    let mark = false;
    const recovery = new Set();

    const floodFill = function (grid, i, j) {
        if (i < 0 || i >= grid.length || j < 0 || j >= grid[0].length || grid[i][j] === WATER) {
            return;
        }
        if (mark) {
            recovery.add(i * grid[0].length + j);
        }
        grid[i][j] = WATER;
        floodFill(grid, i, j + 1);
        floodFill(grid, i, j - 1);
        floodFill(grid, i + 1, j);
        floodFill(grid, i - 1, j);
    };

    const m = grid.length, n = grid[0].length;
    mark = true;
    // 淹没与左右边界的陆地相连的岛屿
    for (let i = 0; i < m; ++i) {
        floodFill(grid, i, 0);
        floodFill(grid, i, n - 1);
    }
    // 淹没与上下边界的陆地相连的岛屿
    for (let j = 0; j < n; ++j) {
        floodFill(grid, 0, j);
        floodFill(grid, m - 1, j);
    }
    mark = false;
    // 淹没封闭岛屿
    for (let i = 0; i < m; ++i) {
        for (let j = 0; j < n; ++j) {
            if (grid[i][j] === LAND) {
                floodFill(grid, i, j);
            }
        }
    }
    // 重建原来与边界陆地相连的岛屿
    for (const x of recovery) {
        const i = Math.floor(x / n);
        const j = x % n;
        grid[i][j] = LAND;
    }
};
// https://leetcode.cn/submissions/detail/381725146/
```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```js
/**
 * @param {number[]} nums
 * @return {number}
 */
const singleNumber = function (nums) {
    let ans = 0;
    for (const x of nums) {
        ans ^= x;
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381732345/
```

## 141. 环形链表

<https://leetcode-cn.com/problems/linked-list-cycle/>

```js
/**
 * @param {ListNode} head
 * @return {boolean}
 */
 var hasCycle = function (head) {
    let slow = head, fast = head;
    while (fast !== null && fast.next !== null) {
        slow = slow.next;
        fast = fast.next.next;
        if (slow === fast) {
            return true;
        }
    }
    return false;
};
// https://leetcode.cn/submissions/detail/380804734/
```

## 142. 环形链表 II

<https://leetcode-cn.com/problems/linked-list-cycle-ii/>

```js
/**
 * @param {ListNode} head
 * @return {ListNode}
 */
 var detectCycle = function (head) {
    let slow = head, fast = head;
    while (fast !== null && fast.next !== null) {
        slow = slow.next;
        fast = fast.next.next;
        if (slow === fast) {
            fast = head;
            while (slow !== fast) {
                slow = slow.next;
                fast = fast.next;
            }
            return slow;
        }
    }
    return null;
};
// https://leetcode.cn/submissions/detail/380805469/
```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```js

```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```js

```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```js

```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```js

```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```js

```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```js

```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```js

```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```js

```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```js

```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```js

```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```js

```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```js

```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```js

```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```js

```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```js

```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```js

```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```js

```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```js

```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```js

```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```js

```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```js

```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```js

```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```js

```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```js

```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```js

```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```js

```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```js

```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```js

```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```js

```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```js

```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```js

```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```js

```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```js

```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```js

```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```js

```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```js

```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```js

```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```js

```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```js

```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```js

```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```js

```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```js

```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```js

```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```js

```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```js

```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```js

```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```js

```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```js

```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```js

```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```js

```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```js

```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```js

```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```js

```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```js

```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```js

```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```js

```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```js

```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```js

```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```js

```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```js

```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```js

```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```js

```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```js

```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```js

```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```js

```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```js

```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```js

```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```js

```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```js

```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```js

```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```js

```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```js

```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```js

```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```js

```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```js

```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```js

```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```js

```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```js

```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```js

```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```js

```

## 876. 链表的中间结点

<https://leetcode-cn.com/problems/middle-of-the-linked-list/>

```js

```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```js

```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```js

```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```js

```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```js

```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```js

```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```js

```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```js

```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```js

```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```js

```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```js

```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```js

```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```js

```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```js

```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```js

```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```js

```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```js

```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```js

```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```js

```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```js

```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```js

```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```js

```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode-cn.com/problems/kth-node-from-end-of-list-lcci/>

```js

```
