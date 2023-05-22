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
const twoSum = function (nums, target) {
    const valToIndex = new Map()
    for (let i = 0; i < nums.length; ++i) {
        const x = nums[i];
        const need = target - x;
        if (valToIndex.has(need)) {
            return [valToIndex.get(need), i];
        }
        valToIndex.set(x, i);
    }
    return [];
};
// https://leetcode.cn/submissions/detail/392337313/
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
        const add = s.charAt(right);
        if (!window.has(add)) {
            window.add(add);
            ++right;
        } else {
            while (left < right) {
                const del = s.charAt(left++);
                window.delete(del);
                if (del === add) {
                    break;
                }
            }
        }
        ans = Math.max(ans, right - left);
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/392739787/
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
        const k1 = getKthElement(nums1, nums2, half);
        const k2 = getKthElement(nums1, nums2, half + 1);
        return (k1 + k2) / 2;
    }
    return getKthElement(nums1, nums2, half + 1);
};

/**
 * 寻找两个正序数组 nums1 和 nums2 从小到大排列的第 k 个数
 *
 * @param {number[]} nums1
 * @param {number[]} nums2
 * @param {number} k
 * @return {number}
 */
const getKthElement = function (nums1, nums2, k) {
    const n1 = nums1.length, n2 = nums2.length;
    let start1 = 0, start2 = 0;
    while (true) {
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
            k -= (i - start1 + 1);
            start1 = i + 1;
        } else {
            // 排除 nums2[start2..j] 共 j-start2+1 个元素
            k -= (j - start2 + 1);
            start2 = j + 1;
        }
    }
};
// https://leetcode.cn/submissions/detail/393645493/
```

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

/**
 * 寻找两个正序数组 nums1[start1..end1] 和 nums2[start2..end2] 从小到大排列的第 k 个数
 *
 * @param {number[]} nums1
 * @param {number} start1
 * @param {number[]} nums2
 * @param {number} start2
 * @param {number} k
 * @return {number}
 */
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
// https://leetcode.cn/submissions/detail/393260639/
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
        const s1 = longestPalindromeCenter(s, i, i);
        if (s1.length > ans.length) {
            ans = s1;
        }
        const s2 = longestPalindromeCenter(s, i, i + 1);
        if (s2.length > ans.length) {
            ans = s2;
        }
    }
    return ans;
};

/**
 * 返回字符串 s 中以 s[i] 和 s[j] 为中心的最长回文子串
 * 
 * @param {string} s
 * @param {number} i
 * @param {number} j
 * @return {string}
 */
const longestPalindromeCenter = function (s, i, j) {
    if (i > j || j - i > 1) {
        return "";
    }
    while (i >= 0 && j < s.length && s.charAt(i) === s.charAt(j)) {
        --i;
        ++j;
    }
    return s.substring(i + 1, j);
};
// https://leetcode.cn/submissions/detail/394198533/
```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```js
const INT_MIN = -Math.pow(2, 31);
const INT_MAX = Math.pow(2, 31) - 1;

/**
 * @param {number} x
 * @return {number}
 */
const reverse = function (x) {
    if (x === 0 || x === INT_MIN) {
        return 0;
    }
    let ans = 0;
    const sign = (x > 0 ? 1 : -1);
    x = Math.abs(x);
    while (x !== 0) {
        if (ans > Math.floor(INT_MAX / 10)) {
            return 0;
        }
        ans = ans * 10 + x % 10;
        x = Math.floor(x / 10);
    }
    return ans * sign;
};
// https://leetcode.cn/submissions/detail/394905962/
```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```js
/**
 * @param {number[]} height
 * @return {number}
 */
const maxArea = function (height) {
    let ans = 0;
    let i = 0, j = height.length - 1;
    while (i < j) {
        const area = (j - i) * Math.min(height[i], height[j]);
        ans = Math.max(ans, area);
        if (height[i] < height[j]) {
            ++i;
        } else {
            --j;
        }
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/395986456/
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
 *
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
        for (const x of sp) {
            x.push(curNum);
            res.push(x);
        }
        while (++i <= hi && nums[i] === curNum) {
        }
    }
    return res;
};

/**
 * 返回升序子数组 nums[lo..hi] 中所有和为 target 且不重复的二元组
 *
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
// https://leetcode.cn/submissions/detail/421956687/
```

## 19. 删除链表的倒数第 N 个结点

<https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/>

```js
/**
 * @param {ListNode} head
 * @param {number} n
 * @return {ListNode}
 */
const removeNthFromEnd = function (head, n) {
    const dummyHead = new ListNode(-1, head);
    let slow = dummyHead;
    let fast = dummyHead;
    for (let i = 1; i <= n; ++i) {
        fast = fast.next;
    }
    while (fast.next !== null) {
        slow = slow.next;
        fast = fast.next;
    }
    slow.next = slow.next.next;
    return dummyHead.next;
};
// https://leetcode.cn/submissions/detail/399469073/
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
const removeDuplicates = function (nums) {
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
// https://leetcode.cn/submissions/detail/429127967/
```

## 27. 移除元素

<https://leetcode.cn/problems/remove-element/>

```js
/**
 * @param {number[]} nums
 * @param {number} val
 * @return {number}
 */
const removeElement = function (nums, val) {
    // nums[0..i-1]   != val
    // nums[i..j]     Scanning
    // nums[j+1..n-1] == val
    let i = 0, j = nums.length - 1;
    while (i <= j) {
        while (i <= j && nums[i] !== val) {
            ++i;
        }
        while (i <= j && nums[j] === val) {
            --j;
        }
        if (i <= j) {
            nums[i++] = nums[j--];
        }
    }
    return i;
};
// https://leetcode.cn/submissions/detail/392346470/
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
let pathSum = 0;
let path = []; // 取 nums[edge] 为元素
let ans = [];

/**
 * @param {number[]} candidates
 * @param {number} target
 * @return {number[][]}
 */
const combinationSum2 = function (candidates, target) {
    pathSum = 0;
    path = [];
    ans = [];
    candidates.sort((a, b) => a - b);
    backtrack(candidates, target, -1);
    return ans;
};

/**
 * @param {number[]} candidates
 * @param {number} target
 * @param {number} edge 取数组 nums 的索引为值
 */
const backtrack = function (candidates, target, edge) {
    if (pathSum === target) {
        ans.push([...path]);
        return;
    }
    let prev = Number.NEGATIVE_INFINITY;
    // 避免重复，从 edge + 1 开始选择
    // 例如 [1->2] 和 [2->1] 是重复的
    while (++edge < candidates.length) {
        const x = candidates[edge];
        if (pathSum + x <= target && x !== prev) {
            prev = x;
            pathSum += x;
            path.push(x);
            backtrack(candidates, target, edge);
            pathSum -= x;
            path.pop();
        }
    }
};
// https://leetcode.cn/submissions/detail/430357992/
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
const minPathSum = function (grid) {
    const m = grid.length;
    const n = grid[0].length;
    const memo = Array.from(new Array(m), (_) => new Array(n));
    return minPathSumSP(grid, m - 1, n - 1, memo);
};

// 返回从 grid[0][0] 到 grid[row][col] 的最小路径和
const minPathSumSP = function (grid, row, col, memo) {
    if (row < 0 || col < 0) {
        return Number.POSITIVE_INFINITY;
    }
    if (row === 0 && col === 0) {
        return grid[row][col];
    }
    if (memo[row][col] === undefined) {
        const sp1 = minPathSumSP(grid, row - 1, col, memo);
        const sp2 = minPathSumSP(grid, row, col - 1, memo);
        memo[row][col] = Math.min(sp1, sp2) + grid[row][col];
    }
    return memo[row][col];
};
// https://leetcode.cn/submissions/detail/427293322/
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
    [nums[i], nums[j]] = [nums[j], nums[i]];
};
// https://leetcode.cn/submissions/detail/433919199/
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
 * 翻转链表的前 n 个节点，返回翻转后的头节点。
 *
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
// https://leetcode.cn/submissions/detail/434403189/
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
const inorderMap = new Map();

/**
 * @param {number[]} inorder
 * @param {number[]} postorder
 * @return {TreeNode}
 */
const buildTree = function (inorder, postorder) {
    inorderMap.clear();
    inorder.forEach((element, index) => inorderMap.set(element, index));
    return buildTreeRange(inorder, 0, inorder.length - 1, postorder, 0, postorder.length - 1);
};

const buildTreeRange = function (inorder, inStart, inEnd, postorder, postStart, postEnd) {
    if (inStart > inEnd) {
        return null;
    }
    const rootVal = postorder[postEnd];
    const inRoot = inorderMap.get(rootVal);
    const leftSize = inRoot - inStart;
    const root = new TreeNode(rootVal);
    root.left = buildTreeRange(inorder, inStart, inRoot - 1, postorder, postStart, postStart + leftSize - 1);
    root.right = buildTreeRange(inorder, inRoot + 1, inEnd, postorder, postStart + leftSize, postEnd - 1);
    return root;
};
// https://leetcode.cn/submissions/detail/403135248/
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
/**
 * @param {ListNode} head
 * @return {void} Do not return anything, modify head in-place instead.
 */
const reorderList = function (head) {
    let slow = head, fast = head;
    while (fast.next != null && fast.next.next != null) {
        slow = slow.next;
        fast = fast.next.next;
    }
    let reverseHead = reverseList(slow.next);
    slow.next = null;
    let ptr = new ListNode();
    while (head != null) {
        ptr.next = head;
        ptr = ptr.next;
        head = head.next;
        if (reverseHead != null) {
            ptr.next = reverseHead;
            ptr = ptr.next;
            reverseHead = reverseHead.next;
        }
    }
};

/**
 * @param {ListNode} head
 * @return {ListNode}
 */
const reverseList = function (head) {
    let reverseHead = null;
    while (head != null) {
        const x = head.next;
        head.next = reverseHead;
        reverseHead = head;
        head = x;
    }
    return reverseHead;
};
// https://leetcode.cn/submissions/detail/403136416/
```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```js
/**
 * @param {TreeNode} root
 * @return {number[]}
 */
 const preorderTraversal = function (root) {
    const ans = [];

    const dfs = function (x) {
        if (x == null) {
            return;
        }
        ans.push(x.val);
        dfs(x.left);
        dfs(x.right);
    };

    dfs(root);
    return ans;
};
// https://leetcode.cn/submissions/detail/381253920/
```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```js
/**
 * @param {TreeNode} root
 * @return {number[]}
 */
 const postorderTraversal = function (root) {
    const ans = [];

    const dfs = function (x) {
        if (x == null) {
            return;
        }
        dfs(x.left);
        dfs(x.right);
        ans.push(x.val);
    };

    dfs(root);
    return ans;
};
// https://leetcode.cn/submissions/detail/381254451/
```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```js
class Node {
    constructor(key, val, prev = null, next = null) {
        this.key = key;
        this.val = val;
        this.prev = prev;
        this.next = next;
    }
}

class DoublyLinkedList {
    constructor() {
        this.first = null;
        this.last = null;
        this.n = 0;
    }

    addLast(x) {
        if (this.n === 0) {
            this.first = x;
            this.last = x;
            this.n = 1;
        } else {
            this.last.next = x;
            x.prev = this.last;
            this.last = x;
            this.n++;
        }
    }

    removeFirst() {
        const oldFirst = this.first;
        if (this.n === 1) {
            this.first = null;
            this.last = null;
            this.n = 0;
        } else {
            this.first = this.first.next;
            this.first.prev = null;
            oldFirst.next = null;
            this.n--;
        }
        return oldFirst;
    }

    removeLast() {
        const oldLast = this.last;
        if (this.n === 1) {
            this.first = null;
            this.last = null;
            this.n = 0;
        } else {
            this.last = this.last.prev;
            this.last.next = null;
            oldLast.prev = null;
            this.n--;
        }
        return oldLast;
    }

    remove(x) {
        if (x === this.first) {
            this.removeFirst();
        } else if (x === this.last) {
            this.removeLast();
        } else {
            x.prev.next = x.next;
            x.next.prev = x.prev;
            x.prev = null;
            x.next = null;
            this.n--;
        }
    }
}

/**
 * @param {number} capacity
 */
const LRUCache = function (capacity) {
    this.capacity = capacity;
    this.list = new DoublyLinkedList();
    this.keyToNode = new Map();
};

/**
 * @param {number} key
 * @return {number}
 */
LRUCache.prototype.get = function (key) {
    if (this.contains(key)) {
        return this.touchCache(key);
    }
    return -1;
};

/**
 * @param {number} key
 * @param {number} value
 * @return {void}
 */
LRUCache.prototype.put = function (key, value) {
    if (this.capacity > 0) {
        if (this.contains(key)) {
            this.touchCache(key, value);
        } else {
            if (this.full()) {
                this.removeCache();
            }
            this.addCache(key, value);
        }
    }
};

LRUCache.prototype.contains = function (key) {
    return this.keyToNode.has(key);
};

LRUCache.prototype.full = function () {
    return this.keyToNode.size === this.capacity;
};

LRUCache.prototype.addCache = function (key, val) {
    const x = new Node(key, val);
    this.list.addLast(x);
    this.keyToNode.set(key, x);
};

LRUCache.prototype.removeCache = function () {
    this.keyToNode.delete(this.list.removeFirst().key);
};

LRUCache.prototype.touchCache = function (key, val) {
    const x = this.keyToNode.get(key);
    if (val !== undefined) {
        x.val = val;
    }
    this.list.remove(x);
    this.list.addLast(x);
    return x.val;
};
// https://leetcode.cn/submissions/detail/382049287/
```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```js
/**
 * @param {number[]} nums
 * @return {number}
 */
 const findMin = function (nums) {
    let lo = 0, hi = nums.length - 1;
    while (lo < hi) {
        const mid = lo + Math.floor((hi - lo) / 2);
        if (nums[mid] < nums[hi]) {
            hi = mid;
        } else {
            lo = mid + 1;
        }
    }
    return nums[lo];
};
// https://leetcode.cn/submissions/detail/380964850/
```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```js
const MinStack = function () {
    this.stack = [];
};

/**
 * @param {number} val
 * @return {void}
 */
MinStack.prototype.push = function (val) {
    const min = (this.stack.length === 0 ? val : Math.min(this.getMin(), val));
    this.stack.push([val, min]);
};

/**
 * @return {void}
 */
MinStack.prototype.pop = function () {
    this.stack.pop();
};

/**
 * @return {number}
 */
MinStack.prototype.top = function () {
    return this.stack.at(-1)[0];
};

/**
 * @return {number}
 */
MinStack.prototype.getMin = function () {
    return this.stack.at(-1)[1];
};
// https://leetcode.cn/submissions/detail/381984622/
```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```js
/**
 * @param {ListNode} headA
 * @param {ListNode} headB
 * @return {ListNode}
 */
 var getIntersectionNode = function (headA, headB) {
    let ptrA = headA;
    let ptrB = headB;
    while (ptrA !== ptrB) {
        ptrA = (ptrA === null ? headB : ptrA.next);
        ptrB = (ptrB === null ? headA : ptrB.next);
    }
    return ptrA;
};
// https://leetcode.cn/submissions/detail/380804892/
```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```js
const DOT = ".".charCodeAt(0);
const ZERO = "0".charCodeAt(0);

/**
 * @param {string} version1
 * @param {string} version2
 * @return {number}
 */
const compareVersion = function (version1, version2) {
    const n1 = version1.length, n2 = version2.length;
    let i = 0, j = 0;
    while (i < n1 || j < n2) {
        let r1 = 0;
        while (i < n1) {
            const code = version1.charCodeAt(i++);
            if (code === DOT) {
                break;
            }
            r1 = r1 * 10 + (code - ZERO);
        }
        let r2 = 0;
        while (j < n2) {
            const code = version2.charCodeAt(j++);
            if (code === DOT) {
                break;
            }
            r2 = r2 * 10 + (code - ZERO);
        }
        if (r1 > r2) {
            return 1;
        }
        if (r1 < r2) {
            return -1;
        }
    }
    return 0;
};
// https://leetcode.cn/submissions/detail/381697553/
```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```js
/**
 * @param {number[]} numbers
 * @param {number} target
 * @return {number[]}
 */
 var twoSum = function (numbers, target) {
    let i = 0, j = numbers.length - 1;
    while (i < j) {
        const sum = numbers[i] + numbers[j];
        if (sum < target) {
            ++i;
        } else if (sum > target) {
            --j;
        } else {
            return [i + 1, j + 1];
        }
    }
    return [];
};
// https://leetcode.cn/submissions/detail/380710327/
```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```js
/**
 * @param {number[]} nums
 * @return {number}
 */
const majorityElement = function (nums) {
    let candidate = undefined;
    let count = 0;
    for (const x of nums) {
        if (count === 0) {
            candidate = x;
            count = 1;
        } else {
            if (x === candidate) {
                ++count;
            } else {
                --count;
            }
        }
    }
    return candidate;
};
// https://leetcode.cn/submissions/detail/381694082/
```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```js
/**
 * @param {number[]} nums
 * @return {string}
 */
const largestNumber = function (nums) {
    const strs = nums.map(x => x.toString());
    strs.sort((s1, s2) => (s2 + s1) - (s1 + s2));
    const ans = strs.join("");
    return ans[0] === "0" ? "0" : ans;
};
// https://leetcode.cn/submissions/detail/381804687/
```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```js
/**
 * @param {number} k
 * @param {number[]} prices
 * @return {number}
 */
 const maxProfit = function (k, prices) {
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
// https://leetcode.cn/submissions/detail/381193168/
```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```js
/**
 * @param {number[]} nums
 * @param {number} k
 * @return {void} Do not return anything, modify nums in-place instead.
 */
 const rotate = function (nums, k) {
    const n = nums.length;
    k %= n;
    if (k > 0) {
        reverse(nums, 0, n - 1);
        reverse(nums, 0, k - 1);
        reverse(nums, k, n - 1);
    }
};

/**
 * @param {number[]} nums
 * @param {number} lo
 * @param {number} hi
 * @return {void}
 */
const reverse = function (nums, lo, hi) {
    while (lo < hi) {
        [nums[lo], nums[hi]] = [nums[hi], nums[lo]];
        ++lo;
        --hi;
    }
};
// https://leetcode.cn/submissions/detail/380963870/
```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```js
/**
 * @param {number[]} nums
 * @return {number}
 */
const rob = function (nums) {
    return subseqSum(nums);
};

/**
 * max({sum(subseq) | subseq 是数组 nums 的任意不连续子序列})
 * @param {number[]} nums
 * @return {number}
 */
const subseqSum = function (nums) {
    const n = nums.length;
    if (n === 0) {
        return 0;
    }
    if (n === 1) {
        return nums[0];
    }
    if (n === 2) {
        return Math.max(nums[0], nums[1]);
    }
    // dp[i] = max({sum(subseq) | subseq 是子数组 nums[0..i] 的任意不连续子序列})
    const dp = new Array(n).fill(0);
    dp[0] = nums[0];
    dp[1] = Math.max(nums[0], nums[1]);
    for (let i = 2; i < n; ++i) {
        // 包含 nums[i]
        const sp1 = dp[i - 2] + nums[i];
        // 不包含 nums[i]
        const sp2 = dp[i - 1];
        dp[i] = Math.max(sp1, sp2);
    }
    return dp[n - 1];
};
// https://leetcode.cn/submissions/detail/381153690/
```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```js
/**
 * @param {TreeNode} root
 * @return {number[]}
 */
 const rightSideView = function (root) {
    const ans = [];
    const queue = new Queue();
    if (root != null) {
        queue.enqueue(root);
    }
    while (!queue.isEmpty()) {
        ans.push(queue.back().val);
        const n = queue.size();
        for (let i = 0; i < n; ++i) {
            const x = queue.dequeue();
            const left = x.left;
            if (left != null) {
                queue.enqueue(left);
            }
            const right = x.right;
            if (right != null) {
                queue.enqueue(right);
            }
        }
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381259321/
```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```js
const LAND = "1";
const WATER = "0";

/**
 * @param {string[][]} grid
 * @return {number}
 */
const numIslands = function (grid) {
    let count = 0;
    for (let i = 0; i < grid.length; ++i) {
        for (let j = 0; j < grid[0].length; ++j) {
            if (grid[i][j] === LAND) {
                floodFill(grid, i, j);
                ++count;
            }
        }
    }
    return count;
};

const floodFill = function (grid, i, j) {
    if (i < 0 || i >= grid.length || j < 0 || j >= grid[0].length || grid[i][j] === WATER) {
        return;
    }
    grid[i][j] = WATER;
    floodFill(grid, i, j + 1);
    floodFill(grid, i, j - 1);
    floodFill(grid, i + 1, j);
    floodFill(grid, i - 1, j);
};
// https://leetcode.cn/submissions/detail/381719876/
```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```js
/**
 * @param {ListNode} head
 * @param {number} val
 * @return {ListNode}
 */
 const removeElements = function (head, val) {
    const dummyHead = new ListNode(-1, head);
    let ptr = dummyHead;
    while (ptr.next != null) {
        if (ptr.next.val === val) {
            ptr.next = ptr.next.next;
        } else {
            ptr = ptr.next;
        }
    }
    return dummyHead.next;
};
// https://leetcode.cn/submissions/detail/380958901/
```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```js
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
// https://leetcode.cn/submissions/detail/380938414/
```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```js
/**
 * @param {number} numCourses
 * @param {number[][]} prerequisites
 * @return {boolean}
 */
const canFinish = function (numCourses, prerequisites) {
    const graph = new Array(numCourses);
    for (let v = 0; v < numCourses; ++v) {
        graph[v] = [];
    }
    for (const p of prerequisites) {
        const v = p[1];
        const w = p[0];
        graph[v].push(w);
    }
    const marked = new Array(numCourses).fill(false);
    const onStack = new Array(numCourses).fill(false);
    let hasCycle = false;

    const dfs = function (graph, v) {
        onStack[v] = true;
        marked[v] = true;
        for (const w of graph[v]) {
            if (hasCycle) {
                return;
            }
            if (!marked[w]) {
                dfs(graph, w);
            } else if (onStack[w]) {
                hasCycle = true;
                return;
            }
        }
        onStack[v] = false;
    }

    for (let v = 0; v < numCourses; ++v) {
        if (!marked[v]) {
            dfs(graph, v);
            if (hasCycle) {
                break;
            }
        }
    }
    return !hasCycle;
};
// https://leetcode.cn/submissions/detail/382167827/
```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```js
/**
 * @param {number} numCourses
 * @param {number[][]} prerequisites
 * @return {number[]}
 */
const findOrder = function (numCourses, prerequisites) {
    const graph = new Array(numCourses);
    for (let v = 0; v < numCourses; ++v) {
        graph[v] = [];
    }
    for (const p of prerequisites) {
        const v = p[0];
        const w = p[1];
        graph[v].push(w);
    }
    const marked = new Array(numCourses).fill(false);
    const onStack = new Array(numCourses).fill(false);
    let hasCycle = false;
    const reversePostorder = [];

    const dfs = function (graph, v) {
        onStack[v] = true;
        marked[v] = true;
        for (const w of graph[v]) {
            if (hasCycle) {
                return;
            }
            if (!marked[w]) {
                dfs(graph, w);
            } else if (onStack[w]) {
                hasCycle = true;
                return;
            }
        }
        reversePostorder.push(v);
        onStack[v] = false;
    }

    for (let v = 0; v < numCourses; ++v) {
        if (!marked[v]) {
            dfs(graph, v);
            if (hasCycle) {
                break;
            }
        }
    }
    return hasCycle ? [] : reversePostorder;
};
// https://leetcode.cn/submissions/detail/382168940/
```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```js
/**
 * @param {number[]} nums
 * @return {number}
 */
 const rob = function (nums) {
    const n = nums.length;
    if (n === 0) {
        return 0;
    }
    if (n === 1) {
        return nums[0];
    }
    return Math.max(subseqSum(nums, 0, n - 2), subseqSum(nums, 1, n - 1));
};

/**
 * max({sum(subseq) | subseq 是子数组 nums[lo..hi] 的任意不连续子序列})
 * @param {number[]} nums
 * @param {number} lo
 * @param {number} hi
 * @return {number}
 */
const subseqSum = function (nums, lo, hi) {
    const n = hi - lo + 1;
    if (n === 0) {
        return 0;
    }
    if (n === 1) {
        return nums[lo];
    }
    if (n === 2) {
        return Math.max(nums[lo], nums[lo + 1]);
    }
    // dp[i] = max({sum(subseq) | subseq 是子数组 nums[lo..lo+i] 的任意不连续子序列})
    const dp = new Array(n).fill(0);
    dp[0] = nums[lo];
    dp[1] = Math.max(nums[lo], nums[lo + 1]);
    for (let i = 2; i < n; ++i) {
        // 包含 nums[lo+i]
        const sp1 = dp[i - 2] + nums[lo + i];
        // 不包含 nums[lo+i]
        const sp2 = dp[i - 1];
        dp[i] = Math.max(sp1, sp2);
    }
    return dp[n - 1];
};
// https://leetcode.cn/submissions/detail/381154532/
```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```js
/**
 * @param {number[]} nums
 * @param {number} k
 * @return {number}
 */
const findKthLargest = function (nums, k) {
    return select(nums, nums.length - k);
};

// 返回数组 nums 从小到大排在第 rank 位的元素，排位从 0 开始计算，
// 相当于有 rank 个元素小于该元素。
const select = function (nums, rank) {
    let lo = 0, hi = nums.length - 1;
    while (lo < hi) {
        const j = partition(nums, lo, hi);
        if (rank < j) {
            hi = j - 1;
        } else if (j < rank) {
            lo = j + 1;
        } else {
            return nums[j];
        }
    }
    return nums[lo];
};

const partition = function (nums, lo, hi) {
    const v = nums[lo];
    let i = lo, j = hi + 1;
    while (true) {
        while (nums[++i] < v) {
            if (i === hi) {
                break;
            }
        }
        while (v < nums[--j]) {
            if (j === lo) {
                break;
            }
        }
        if (i >= j) {
            break;
        }
        swap(nums, i, j);
    }
    swap(nums, lo, j);
    return j;
};

const swap = function (nums, i, j) {
    const x = nums[i];
    nums[i] = nums[j];
    nums[j] = x;
};
// https://leetcode.cn/submissions/detail/381880063/
```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```js
/**
 * @param {number} k
 * @param {number} n
 * @return {number[][]}
 */
 const combinationSum3 = function (k, n) {
    let pathSum = 0;
    const path = []; // 取 [1..9] 为元素
    const ans = [];

    // edge = 取 [1..9] 为值
    const backtrack = function (edge) {
        if (path.length === k && pathSum === n) {
            ans.push([...path]);
        } else if (path.length < k && pathSum < n) {
            // 避免重复，从 edge + 1 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            while (++edge <= 9) {
                if (pathSum + edge <= n) {
                    pathSum += edge;
                    path.push(edge);
                    backtrack(edge);
                    path.pop();
                    pathSum -= edge;
                }
            }
        }
    }

    backtrack(0);
    return ans;
};
// https://leetcode.cn/submissions/detail/381237843/
```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```js
/**
 * @param {TreeNode} root
 * @return {number}
 */
const countNodes = function (root) {
    if (root == null) {
        return 0;
    }
    let leftHeight = 0;
    let ptr = root.left;
    while (ptr != null) {
        ++leftHeight;
        ptr = ptr.left;
    }
    let rightHeight = 0;
    ptr = root.right;
    while (ptr != null) {
        ++rightHeight;
        ptr = ptr.right;
    }
    if (leftHeight === rightHeight) {
        return Math.pow(2, leftHeight + 1) - 1;
    }
    return 1 + countNodes(root.left) + countNodes(root.right);
};
// https://leetcode.cn/submissions/detail/381729708/
```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```js
const MyStack = function () {
    this.queue = new Queue();
};

/**
 * @param {number} x
 * @return {void}
 */
MyStack.prototype.push = function (x) {
    this.queue.enqueue(x);
    for (let i = 1; i < this.queue.size(); ++i) {
        this.queue.enqueue(this.queue.dequeue());
    }
};

/**
 * @return {number}
 */
MyStack.prototype.pop = function () {
    return this.queue.dequeue();
};

/**
 * @return {number}
 */
MyStack.prototype.top = function () {
    return this.queue.front();
};

/**
 * @return {boolean}
 */
MyStack.prototype.empty = function () {
    return this.queue.isEmpty();
};
// https://leetcode.cn/submissions/detail/381982311/
```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```js
/**
 * @param {TreeNode} root
 * @return {TreeNode}
 */
const invertTree = function (root) {
    if (root == null) {
        return null;
    }
    const left = invertTree(root.left);
    const right = invertTree(root.right);
    root.right = left;
    root.left = right;
    return root;
};
// https://leetcode.cn/submissions/detail/381570473/
```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```js
/**
 * @param {TreeNode} root
 * @param {number} k
 * @return {number}
 */
const kthSmallest = function (root, k) {
    return select(root, k - 1);
};

const size = function (root, memo = new Map()) {
    if (root == null) {
        return 0;
    }
    if (!memo.has(root)) {
        memo.set(root, 1 + size(root.left, memo) + size(root.right, memo));
    }
    return memo.get(root);
};

const select = function (root, rank) {
    if (root == null) {
        return -1;
    }
    const leftSize = size(root.left);
    if (rank < leftSize) {
        return select(root.left, rank);
    }
    if (leftSize < rank) {
        return select(root.right, rank - leftSize - 1);
    }
    return root.val;
};
// https://leetcode.cn/submissions/detail/381688547/
```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```js
/**
 * -----------------------------| |-------------------------------
 * pop <- top Left Stack bottom | | bottom Right Stack top <- push
 * -----------------------------| |-------------------------------
 */
const MyQueue = function () {
    this.leftStack = [];
    this.rightStack = [];
};

/**
 * @param {number} x
 * @return {void}
 */
MyQueue.prototype.push = function (x) {
    this.rightStack.push(x);
};

/**
 * @return {number}
 */
MyQueue.prototype.pop = function () {
    if (this.leftStack.length === 0) {
        this.move();
    }
    return this.leftStack.pop();
};

/**
 * @return {number}
 */
MyQueue.prototype.peek = function () {
    if (this.leftStack.length === 0) {
        this.move();
    }
    return this.leftStack.at(-1);
};

/**
 * @return {boolean}
 */
MyQueue.prototype.empty = function () {
    return this.leftStack.length === 0 && this.rightStack.length === 0;
};

MyQueue.prototype.move = function () {
    while (this.rightStack.length > 0) {
        this.leftStack.push(this.rightStack.pop());
    }
};
// https://leetcode.cn/submissions/detail/405929863/
```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```js
/**
 * @param {ListNode} head
 * @return {boolean}
 */
 const isPalindrome = function (head) {
    // 寻找链表的中点（偶数个节点时选择左侧），即前半部分链表的尾节点
    let slow = head, fast = head;
    while (fast.next != null && fast.next.next != null) {
        slow = slow.next;
        fast = fast.next.next;
    }
    // 翻转后半部分链表
    const reverseHead = reverseList(slow.next);
    slow.next = null;
    // 判断是否回文链表
    let left = head;
    let right = reverseHead;
    while (right != null) {
        if (left.val !== right.val) {
            return false;
        }
        left = left.next;
        right = right.next;
    }
    // 还原链表
    slow.next = reverseList(reverseHead);
    return true;
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
// https://leetcode.cn/submissions/detail/380947761/
```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```js
/**
 * @param {TreeNode} root
 * @param {TreeNode} p
 * @param {TreeNode} q
 * @return {TreeNode}
 */
const lowestCommonAncestor = function (root, p, q) {
    // 保证 p < q
    if (p.val > q.val) {
        return lowestCommonAncestor(root, q, p);
    }
    if (p.val <= root.val && root.val <= q.val) {
        return root;
    }
    if (q.val < root.val) {
        return lowestCommonAncestor(root.left, p, q);
    }
    if (root.val < p.val) {
        return lowestCommonAncestor(root.right, p, q);
    }
    return null;
};
// https://leetcode.cn/submissions/detail/381730746/
```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```js
/**
 * @param {TreeNode} root
 * @param {TreeNode} p
 * @param {TreeNode} q
 * @return {TreeNode}
 */
const lowestCommonAncestor = function (root, p, q) {
    let lca = null;

    // 在子树中查找节点 p 或 q，递归过程中确定『最近公共祖先』
    const find = function (root, p, q) {
        if (root == null) {
            return false;
        }
        if (root === p || root === q) {
            // 如果 lca(p,q) = p 或 q，则此处的 lca = root 是最终答案
            lca = root;
            return true;
        }
        const left = find(root.left, p, q);
        const right = find(root.right, p, q);
        // 否则返回到某祖先节点处的 lca = root 才是最终答案
        if (left && right) {
            lca = root;
        }
        return left || right;
    };

    find(root, p, q);
    return lca;
};
// https://leetcode.cn/submissions/detail/381733531/
```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```js
/**
 * @param {ListNode} node
 * @return {void} Do not return anything, modify node in-place instead.
 */
const deleteNode = function (node) {
    node.val = node.next.val;
    node.next = node.next.next;
};
// https://leetcode.cn/submissions/detail/381731860/
```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```js
/**
 * @param {number[]} nums
 * @param {number} k
 * @return {number[]}
 */
 const maxSlidingWindow = function (nums, k) {
    const ans = [];
    const queue = new Deque();
    for (let i = 0; i < nums.length; ++i) {
        // nums[i] = 进入窗口的数字
        const x = nums[i];
        while (!queue.isEmpty() && queue.back() < x) {
            queue.popBack();
        }
        queue.pushBack(x);
        if (i < k - 1) {
            continue;
        }
        // nums[i-k] = 退出窗口的数字
        if (i >= k && nums[i - k] === queue.front()) {
            queue.popFront();
        }
        ans.push(queue.front());
    }
    return ans;
};

class Deque {
    /**
     * Creates a deque
     * @param {array} [elements]
     */
    constructor(elements) {
        this._backElements = Array.isArray(elements) ? elements : [];
        this._frontElements = [];
        this._backOffset = 0;
        this._frontOffset = 0;
    }

    /**
     * Adds an element at the front of the queue
     * @public
     * @param {number|string|object} element
     */
    pushFront(element) {
        this._frontElements.push(element);
        return this;
    }

    /**
     * Adds an element at the back of the queue
     * @public
     * @param {number|string|object} element
     */
    pushBack(element) {
        this._backElements.push(element);
        return this;
    }

    /**
     * Dequeues the front element in the queue
     * @public
     * @returns {number|string|object}
     */
    popFront() {
        if (this.size() === 0) {
            return null;
        }

        if (this._frontElements.length > 0) {
            const front = this._frontElements.pop();
            if (this._frontOffset >= this._frontElements.length) {
                this._frontElements = this._frontElements.slice(this._frontOffset);
                this._frontOffset = 0;
            }
            return front;
        }

        const front = this.front();
        this._backOffset += 1;

        if (this._backOffset * 2 < this._backElements.length) {
            return front;
        }

        this._backElements = this._backElements.slice(this._backOffset);
        this._backOffset = 0;
        return front;
    }

    /**
     * Dequeues the back element of the queue
     * @public
     * @returns {number|string|object}
     */
    popBack() {
        if (this.size() === 0) {
            return null;
        }

        if (this._backElements.length > 0) {
            const back = this._backElements.pop();
            if (this._backOffset >= this._backElements.length) {
                this._backElements = this._backElements.slice(this._backOffset);
                this._backOffset = 0;
            }
            return back;
        }

        const back = this.back();
        this._frontOffset += 1;
        if (this._frontOffset * 2 < this._frontElements.length) {
            return back;
        }

        this._frontElements = this._frontElements.slice(this._frontOffset);
        this._frontOffset = 0;
        return back;
    }

    /**
     * Returns the front element of the queue
     * @public
     * @returns {number|string|object}
     */
    front() {
        if (this.size() === 0) {
            return null;
        }

        if (this._frontElements.length > 0) {
            return this._frontElements[this._frontElements.length - 1];
        }

        return this._backElements[this._backOffset];
    }

    /**
     * Returns the back element of the queue
     * @public
     * @returns {number|string|object}
     */
    back() {
        if (this.size() === 0) {
            return null;
        }

        if (this._backElements.length > 0) {
            return this._backElements[this._backElements.length - 1];
        }

        return this._frontElements[this._frontOffset];
    }

    /**
     * Returns the number of elements in the deque
     * @public
     * @returns {number}
     */
    size() {
        const frontSize = this._frontElements.length - this._frontOffset;
        const backSize = this._backElements.length - this._backOffset;
        return frontSize + backSize;
    }

    /**
     * Checks if the queue is empty
     * @public
     * @returns {boolean}
     */
    isEmpty() {
        return this.size() === 0;
    }

    /**
     * Returns the remaining elements in the queue as an array
     * @public
     * @returns {array}
     */
    toArray() {
        const backElements = this._backElements.slice(this._backOffset);
        const frontElements = this._frontElements.slice(this._frontElements);
        return frontElements.reverse().concat(backElements);
    }

    /**
     * Clears the queue
     * @public
     */
    clear() {
        this._backElements = [];
        this._frontElements = [];
        this._backOffset = 0;
        this._frontOffset = 0;
    }

    /**
     * Creates a shallow copy of the queue
     * @public
     * @return {Deque}
     */
    clone() {
        return new Deque(this.toArray());
    }

    /**
     * Creates a deque from an existing array
     * @public
     * @static
     * @param {array} elements
     * @return {Deque}
     */
    static fromArray(elements) {
        return new Deque(elements);
    }
}
// https://leetcode.cn/submissions/detail/381074368/
```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```js

```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```js
/**
 * @param {number[]} nums
 * @return {void} Do not return anything, modify nums in-place instead.
 */
 var moveZeroes = function (nums) {
    const n = nums.length;
    // [0..i-1] != 0
    // [i..j-1] == 0
    // [j..n-1] Scanning
    let i = 0, j = 0;
    while (j < n) {
        while (j < n && nums[j] === 0) {
            ++j;
        }
        if (j < n) {
            [nums[i], nums[j]] = [nums[j], nums[i]];
            ++i;
            ++j;
        }
    }
};
// https://leetcode.cn/submissions/detail/380797396/
```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```js
/**
 * Encodes a tree to a single string.
 *
 * @param {TreeNode} root
 * @return {string}
 */
const serialize = function (root) {
    if (root == null) {
        return "#";
    }
    const left = serialize(root.left);
    const right = serialize(root.right);
    return left + "," + right + "," + root.val.toString();
};

/**
 * Decodes your encoded data to tree.
 *
 * @param {string} data
 * @return {TreeNode}
 */
const deserialize = function (data) {
    return buildTree(data.split(","));
};

const buildTree = function (array) {
    const val = array.pop();
    if (val === "#") {
        return null;
    }
    const root = new TreeNode(parseInt(val));
    root.right = buildTree(array);
    root.left = buildTree(array);
    return root;
};
// https://leetcode.cn/submissions/detail/406986525/
```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```js
/**
 * @param {number[]} nums
 * @return {number}
 */
 const lengthOfLIS = function (nums) {
    let ans = 0;
    const n = nums.length;
    // dp[i] = max({length(subseq) | subseq 是以 nums[i] 结尾的严格递增子序列})
    const dp = new Array(n).fill(1);
    for (let i = 0; i < n; ++i) {
        for (let j = i - 1; j >= 0; --j) {
            if (nums[j] < nums[i]) {
                dp[i] = Math.max(dp[i], dp[j] + 1);
            }
        }
        ans = Math.max(ans, dp[i]);
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381100078/
```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```js
/**
 * @param {number[]} nums
 */
const NumArray = function (nums) {
    this.prefixSum = [];
    nums.reduce((sum, val) => {
        const res = sum + val;
        this.prefixSum.push(res);
        return res;
    }, 0);
};

/**
 * @param {number} left
 * @param {number} right
 * @return {number}
 */
NumArray.prototype.sumRange = function (left, right) {
    if (left === 0) {
        return this.prefixSum[right];
    }
    return this.prefixSum[right] - this.prefixSum[left - 1];
};
// https://leetcode.cn/submissions/detail/381986466/
```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```js
/**
 * @param {number[]} prices
 * @return {number}
 */
 const maxProfit = function (prices) {
    const n = prices.length;
    if (n <= 1) {
        return 0;
    }
    // dp[i][0] = 第 i 天，空仓状态下的最大利润
    // dp[i][1] = 第 i 天，持仓状态下的最大利润
    const dp = new Array(n);
    for (let i = 0; i < n; ++i) {
        dp[i] = new Array(2).fill(0);
    }
    dp[0][0] = 0;
    dp[0][1] = -prices[0];
    dp[1][0] = Math.max(dp[0][0], dp[0][1] + prices[1]);
    dp[1][1] = Math.max(dp[0][0] - prices[1], dp[0][1]);
    for (let i = 2; i < n; ++i) {
        // dp[i - 1][0]             >= dp[i - 2][0] >= p[i - 2][0] - prices[i]
        // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
        // => dp[i][0] >= dp[i][1]
        dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
        dp[i][1] = Math.max(dp[i - 2][0] - prices[i], dp[i - 1][1]);
    }
    return dp[n - 1][0];
};
// https://leetcode.cn/submissions/detail/381195923/
```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```js
class Pair {
    constructor(val, idx) {
        this.val = val;
        this.idx = idx;
    }

    valueOf() {
        return this.val;
    }
}

/**
 * @param {number[]} nums
 * @return {number[]}
 */
const countSmaller = function (nums) {
    const n = nums.length;
    const counts = new Array(n).fill(0);
    const pairs = nums.map((e, i) => new Pair(e, i));

    const sort = function (pairs, aux, lo, hi) {
        if (lo >= hi) {
            return;
        }
        const mid = lo + Math.floor((hi - lo) / 2);
        sort(pairs, aux, lo, mid);
        sort(pairs, aux, mid + 1, hi);
        merge(pairs, aux, lo, mid, hi);
    };

    const merge = function (pairs, aux, lo, mid, hi) {
        for (let k = lo; k <= hi; ++k) {
            aux[k] = pairs[k];
        }
        let i = lo, j = mid + 1;
        for (let k = lo; k <= hi; ++k) {
            if (i > mid || (j <= hi && aux[j] < aux[i])) {
                pairs[k] = aux[j++];
            } else {
                const p = aux[i];
                // aux[mid+1..j) < aux[i]
                counts[p.idx] += (j - mid - 1);
                pairs[k] = aux[i++];
            }
        }
    };

    sort(pairs, [...pairs], 0, n - 1);
    return counts;
};
// https://leetcode.cn/submissions/detail/382162398/
```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```js
/**
 * @param {number[]} coins
 * @param {number} amount
 * @return {number}
 */
 const coinChange = function (coins, amount) {
    // dp[i] = 凑成总金额 i 所需的最少的硬币个数
    const dp = new Array(amount + 1).fill(-1);
    dp[0] = 0;
    for (let i = 1; i <= amount; ++i) {
        let res = Number.POSITIVE_INFINITY;
        // c       = 选择放入的硬币
        // i-c     = 剩余总金额
        // dp[i-c] = 凑成剩余总金额所需的最少的硬币个数
        for (const c of coins) {
            const x = i - c;
            if (x >= 0 && dp[x] !== -1) {
                res = Math.min(res, dp[x] + 1);
            }
        }
        dp[i] = (res === Number.POSITIVE_INFINITY ? -1 : res);
    }
    return dp[amount];
};
// https://leetcode.cn/submissions/detail/381199924/
```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```js
const memo = new Map();

/**
 * @param {TreeNode} root
 * @return {number}
 */
const rob = function (root) {
    if (root == null) {
        return 0;
    }
    if (!memo.has(root)) {
        // 不偷 root
        const sp1 = rob(root.left) + rob(root.right);
        // 偷 root
        let sp2 = root.val;
        if (root.left != null) {
            sp2 += rob(root.left.left) + rob(root.left.right);
        }
        if (root.right != null) {
            sp2 += rob(root.right.left) + rob(root.right.right);
        }
        memo.set(root, Math.max(sp1, sp2));
    }
    return memo.get(root);
};
// https://leetcode.cn/submissions/detail/381155593/
```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```js
/**
 * @param {string[]} s
 * @return {void} Do not return anything, modify s in-place instead.
 */
 const reverseString = function (s) {
    let i = 0, j = s.length - 1;
    while (i < j) {
        [s[i], s[j]] = [s[j], s[i]];
        ++i;
        --j;
    }
};
// https://leetcode.cn/submissions/detail/380932273/
```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```js

```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```js
/**
 * @param {string} s
 * @return {string}
 */
 const decodeString = function (s) {
    const isDigit = charCode => charCode >= 48 && charCode <= 57;
    const isLetter = charCode => charCode >= 97 && charCode <= 122;

    const stack = [];
    const n = s.length;
    let i = 0;
    while (i < n) {
        // Digits
        let digits = "";
        while (i < n && isDigit(s.charCodeAt(i))) {
            digits += s.charAt(i++);
        }
        if (digits.length > 0) {
            stack.push(digits);
        }
        // [
        while (i < n && s.charAt(i) === '[') {
            stack.push("[");
            ++i;
        }
        // Letters
        let letters = "";
        while (i < n && isLetter(s.charCodeAt(i))) {
            letters += s.charAt(i++);
        }
        if (letters.length > 0) {
            stack.push(letters);
        }
        // ]
        while (i < n && s.charAt(i) === ']') {
            letters = "";
            while (stack.length > 0) {
                const str = stack.pop();
                if (str === "[") {
                    break;
                }
                letters = str + letters;
            }
            digits = stack.pop();
            const rep = letters.repeat(parseInt(digits));
            stack.push(rep);
            ++i;
        }
    }
    return stack.join("");
};
// https://leetcode.cn/submissions/detail/380983654/
```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```js
/**
 * @param {number[]} nums
 * @return {boolean}
 */
 const canPartition = function (nums) {
    let sum = 0;
    for (const x of nums) {
        sum += x;
    }
    if (sum % 2 === 1) {
        return false;
    }
    return hasSubsetSum(nums, sum / 2);
};

// 数组 nums 是否存在和为 sum 的子集
const hasSubsetSum = function (nums, sum) {
    const n = nums.length;
    // dp[i][j] = 子数组 nums[0..i-1] 是否存在和为 j 的子集
    const dp = new Array(n + 1);
    for (let i = 0; i <= n; ++i) {
        dp[i] = new Array(sum + 1).fill(false);
    }
    // 和为 0
    for (let i = 1; i <= n; ++i) {
        dp[i][0] = true;
    }
    // 空数组
    for (let j = 1; j <= sum; ++j) {
        dp[0][j] = false;
    }
    // 空集的和为 0，空集是任何数组的子集，包括空数组
    dp[0][0] = true;
    for (let i = 1; i <= n; ++i) {
        for (let j = 1; j <= sum; ++j) {
            const x = nums[i - 1];
            if (j >= x) {
                // 不包含 x
                // 当 i = 1 时，dp[i - 1][j] = dp[0][j]
                // 因为空数组没有子集的和为 j >= 1
                // 所以定义 dp[0][j] = false (j >= 1)
                const sp1 = dp[i - 1][j];
                // 包含 x
                // 当 i >= 1, j = x 时，dp[i - 1][j - x] = dp[i - 1][0]
                // 因为存在子集 {x} 的和为 j，
                // 所以定义 dp[i][0] = true (i >= 0)
                const sp2 = dp[i - 1][j - x];
                dp[i][j] = sp1 || sp2;
            } else {
                dp[i][j] = dp[i - 1][j];
            }
        }
    }
    return dp[n][sum];
};
// https://leetcode.cn/submissions/detail/381244270/
```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```js
int cmp(const void *a, const void *b) {
    const int *arg1 = *(const int **) a;
    const int *arg2 = *(const int **) b;
    return arg1[1] - arg2[1];
}

// 区间数组 intervals 无重叠区间的最大数量
int maxNonOverlappingIntervals(int **intervals, int intervalsSize) {
    qsort(intervals, intervalsSize, sizeof(int *), cmp);
    int count = 0;
    int minEnd = INT_MIN;
    for (int i = 0; i < intervalsSize; ++i) {
        int start = intervals[i][0];
        int end = intervals[i][1];
        if (start < minEnd) {
            continue;
        }
        ++count;
        minEnd = end;
    }
    return count;
}

int eraseOverlapIntervals(int **intervals, int intervalsSize, int *intervalsColSize) {
    return intervalsSize - maxNonOverlappingIntervals(intervals, intervalsSize);
}
// https://leetcode.cn/submissions/detail/391305215/
```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```js
/**
 * @param {string} s
 * @param {string} p
 * @return {number[]}
 */
 const findAnagrams = function (s, p) {
    const need = new Map();
    for (const c of p) {
        if (!need.has(c)) {
            need.set(c, 0);
        }
        need.set(c, need.get(c) + 1);
    }
    const window = new Map();
    const ans = [];
    let valid = 0;
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
            while (left < right - p.length) {
                const d = s.charAt(left++);
                if (need.has(d)) {
                    if (window.get(d) === need.get(d)) {
                        --valid;
                    }
                    window.set(d, window.get(d) - 1);
                }
            }
        }
        if (valid === need.size) {
            ans.push(left);
        }
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381035184/
```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```js
/**
 * @param {ListNode} l1
 * @param {ListNode} l2
 * @return {ListNode}
 */
 const addTwoNumbers = function (l1, l2) {
    // 翻转链表
    l1 = reverseList(l1);
    l2 = reverseList(l2);
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
    // 还原链表
    reverseList(l1);
    reverseList(l2);
    return reverseList(dummyHead.next);
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
// https://leetcode.cn/submissions/detail/380954487/
```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```js
/**
 * @param {TreeNode} root
 * @param {number} key
 * @return {TreeNode}
 */
const deleteNode = function (root, key) {
    if (root == null) {
        return null;
    }
    if (key < root.val) {
        root.left = deleteNode(root.left, key);
    } else if (key > root.val) {
        root.right = deleteNode(root.right, key);
    } else {
        if (root.left == null) {
            return root.right;
        }
        if (root.right == null) {
            return root.left;
        }
        const x = root;
        root = findMin(x.right);
        root.right = deleteMin(x.right);
        root.left = x.left;
    }
    return root;
};

const findMin = function (root) {
    if (root.left == null) {
        return root;
    }
    return findMin(root.left);
};

const deleteMin = function (root) {
    if (root.left == null) {
        return root.right;
    }
    root.left = deleteMin(root.left);
    return root;
};
// https://leetcode.cn/submissions/detail/381689726/
```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```js
/**
 * @param {number[][]} points
 * @return {number}
 */
 const findMinArrowShots = function (points) {
    return maxNonOverlappingIntervals(points);
};

/**
 * 区间数组 intervals 中无重叠区间的最大数量
 * @param {number[][]} intervals
 * @return {number}
 */
const maxNonOverlappingIntervals = function (intervals) {
    intervals.sort((a, b) => a[1] - b[1]);
    let count = 0;
    let minEnd = Number.NEGATIVE_INFINITY;
    for (let i = 0; i < intervals.length; ++i) {
        const [start, end] = intervals[i];
        if (start <= minEnd) {
            continue;
        }
        ++count;
        minEnd = end;
    }
    return count;
};
// https://leetcode.cn/submissions/detail/381061984/
```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```js
class Node {
    constructor(key, val, freq, prev = null, next = null) {
        this.key = key;
        this.val = val;
        this.freq = freq;
        this.prev = prev;
        this.next = next;
    }
}

class DoublyLinkedList {
    constructor() {
        this.first = null;
        this.last = null;
        this.n = 0;
    }

    addLast(x) {
        if (this.n === 0) {
            this.first = x;
            this.last = x;
            this.n = 1;
        } else {
            this.last.next = x;
            x.prev = this.last;
            this.last = x;
            this.n++;
        }
    }

    removeFirst() {
        const oldFirst = this.first;
        if (this.n === 1) {
            this.first = null;
            this.last = null;
            this.n = 0;
        } else {
            this.first = this.first.next;
            this.first.prev = null;
            oldFirst.next = null;
            this.n--;
        }
        return oldFirst;
    }

    removeLast() {
        const oldLast = this.last;
        if (this.n === 1) {
            this.first = null;
            this.last = null;
            this.n = 0;
        } else {
            this.last = this.last.prev;
            this.last.next = null;
            oldLast.prev = null;
            this.n--;
        }
        return oldLast;
    }

    remove(x) {
        if (x === this.first) {
            this.removeFirst();
        } else if (x === this.last) {
            this.removeLast();
        } else {
            x.prev.next = x.next;
            x.next.prev = x.prev;
            x.prev = null;
            x.next = null;
            this.n--;
        }
    }

    empty() {
        return this.first == null;
    }
}

/**
 * @param {number} capacity
 */
const LFUCache = function (capacity) {
    this.capacity = capacity;
    this.keyToNode = new Map();
    this.freqToList = new Map();
    this.minFreq = 0;
};

/**
 * @param {number} key
 * @return {number}
 */
LFUCache.prototype.get = function (key) {
    if (this.contains(key)) {
        return this.touchCache(key);
    }
    return -1;
};

/**
 * @param {number} key
 * @param {number} value
 * @return {void}
 */
LFUCache.prototype.put = function (key, value) {
    if (this.capacity > 0) {
        if (this.contains(key)) {
            this.touchCache(key, value);
        } else {
            if (this.full()) {
                this.removeCache();
            }
            this.addCache(key, value);
        }
    }
};

LFUCache.prototype.contains = function (key) {
    return this.keyToNode.has(key);
};

LFUCache.prototype.full = function () {
    return this.keyToNode.size === this.capacity;
};

LFUCache.prototype.addCache = function (key, val) {
    const x = new Node(key, val, 1);
    this.keyToNode.set(key, x);
    if (!this.freqToList.has(1)) {
        this.freqToList.set(1, new DoublyLinkedList());
    }
    this.freqToList.get(1).addLast(x);
    this.minFreq = 1;
};

LFUCache.prototype.removeCache = function () {
    const list = this.freqToList.get(this.minFreq);
    this.keyToNode.delete(list.removeFirst().key);
    if (list.empty()) {
        this.freqToList.delete(this.minFreq);
    }
};

LFUCache.prototype.touchCache = function (key, val) {
    const x = this.keyToNode.get(key);
    if (val !== undefined) {
        x.val = val;
    }
    const oldFreq = x.freq;
    const newFreq = oldFreq + 1;
    x.freq = newFreq;
    const oldList = this.freqToList.get(oldFreq);
    oldList.remove(x);
    if (oldList.empty()) {
        this.freqToList.delete(oldFreq);
        if (this.minFreq === oldFreq) {
            this.minFreq = newFreq;
        }
    }
    if (!this.freqToList.has(newFreq)) {
        this.freqToList.set(newFreq, new DoublyLinkedList());
    }
    const newList = this.freqToList.get(newFreq);
    newList.addLast(x);
    return x.val;
};
// https://leetcode.cn/submissions/detail/382053526/
```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```js
/**
 * @param {number[]} nums
 * @return {number}
 */
const reversePairs = function (nums) {
    let ans = 0;

    const sort = function (nums, aux, lo, hi) {
        if (lo >= hi) {
            return;
        }
        const mid = lo + Math.floor((hi - lo) / 2);
        sort(nums, aux, lo, mid);
        sort(nums, aux, mid + 1, hi);
        merge(nums, aux, lo, mid, hi);
    };

    const merge = function (nums, aux, lo, mid, hi) {
        for (let k = lo; k <= hi; ++k) {
            aux[k] = nums[k];
        }
        ans += countReversePairs(nums, lo, mid, hi);
        let i = lo, j = mid + 1;
        for (let k = lo; k <= hi; ++k) {
            if (i > mid || (j <= hi && aux[j] < aux[i])) {
                nums[k] = aux[j++];
            } else {
                nums[k] = aux[i++];
            }
        }
    };

    const countReversePairs = function (nums, lo, mid, hi) {
        let res = 0;
        //     nums[i]      > 2*nums[j]
        // (1) nums[i]      > 2*nums[mid+1..j]
        // (2) nums[i..mid] > 2*nums[j]
        //
        //     nums[i]     <= 2*nums[j]
        // (1) nums[i]     <= 2*nums[j..hi]
        // (2) nums[lo..i] <= 2*nums[j]
        let i = lo, j = mid + 1;
        while (i <= mid && j <= hi) {
            if (isReversePair(nums, i, j)) {
                res += (mid - i + 1);
                ++j;
            } else {
                ++i;
            }
        }
        return res;
    };

    const isReversePair = function (nums, i, j) {
        return i < j && nums[i] > 2 * nums[j];
    };

    sort(nums, [...nums], 0, nums.length - 1);
    return ans;
};
// https://leetcode.cn/submissions/detail/381883474/
```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```js
const memo = new Map();

/**
 * @param {number[]} nums
 * @param {number} target
 * @return {number}
 */
const findTargetSumWays = function (nums, target) {
    let sum = 0;
    for (const x of nums) {
        sum += x;
    }
    if (Math.abs(target) > sum) {
        return 0;
    }
    memo.clear();
    return findTargetSumWaysMemo(nums, nums.length - 1, target);
};

// 返回子数组 nums[0..i] 中目标和为 target 的不同表达式的数目
const findTargetSumWaysMemo = function (nums, i, target) {
    if (i < 0) {
        return target === 0 ? 1 : 0;
    }
    const key = i + "," + target;
    if (!memo.has(key)) {
        const x = nums[i];
        // x 前添加 + 号
        // sum(nums[0..i-1]) = target - x
        const sp1 = findTargetSumWaysMemo(nums, i - 1, target - x);
        // x 前添加 - 号
        // sum(nums[0..i-1]) = target + x
        const sp2 = findTargetSumWaysMemo(nums, i - 1, target + x);
        memo.set(key, sp1 + sp2);
    }
    return memo.get(key);
};
// https://leetcode.cn/submissions/detail/409166446/
```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```js
/**
 * @param {number[]} nums1
 * @param {number[]} nums2
 * @return {number[]}
 */
 const nextGreaterElement = function (nums1, nums2) {
    const greater = _nextGreaterElement(nums2);
    const valToGreater = new Map();
    for (let i = 0; i < nums2.length; ++i) {
        valToGreater.set(nums2[i], greater[i]);
    }
    const ans = [];
    for (const x of nums1) {
        ans.push(valToGreater.get(x))
    }
    return ans;
};

/**
 * @param {number[]} nums
 * @return {number[]}
 */
const _nextGreaterElement = function (nums) {
    const res = [...nums];
    const stack = [];
    const n = nums.length;
    for (let i = n - 1; i >= 0; --i) {
        const x = nums[i];
        while (stack.length > 0 && stack.at(-1) < x) {
            stack.pop();
        }
        res[i] = stack.length === 0 ? -1 : stack.at(-1);
        stack.push(x);
    }
    return res;
};
// https://leetcode.cn/submissions/detail/381067644/
```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```js
/**
 * @param {number[]} nums
 * @return {number[]}
 */
 const nextGreaterElements = function (nums) {
    const ans = [...nums];
    const stack = [];
    const n = nums.length;
    for (let i = 2 * n - 1; i >= 0; --i) {
        const k = i % n;
        const x = nums[k];
        while (stack.length > 0 && stack.at(-1) <= x) {
            stack.pop();
        }
        ans[k] = stack.length === 0 ? -1 : stack.at(-1);
        stack.push(x);
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381068632/
```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```js
/**
 * @param {number} n
 * @return {number}
 */
const fib = function (n) {
    if (n === 0) {
        return 0;
    }
    if (n === 1) {
        return 1;
    }
    const dp = new Array(n + 1);
    dp[0] = 0;
    dp[1] = 1;
    for (let i = 2; i <= n; ++i) {
        dp[i] = dp[i - 1] + dp[i - 2];
    }
    return dp[n];
};
// https://leetcode.cn/submissions/detail/381718808/
```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```js
/**
 * @param {string} s
 * @return {number}
 */
 const longestPalindromeSubseq = function (s) {
    const n = s.length;
    // dp[i][j] = 子串 s[i..j] 的最长回文子序列的长度
    const dp = new Array(n);
    for (let i = 0; i < n; ++i) {
        dp[i] = new Array(n).fill(0);
    }
    // 遍历对角线
    for (let i = 0; i < n; ++i) {
        dp[i][i] = 1;
    }
    // 遍历上三角形
    for (let i = n - 2; i >= 0; --i) {
        for (let j = i + 1; j < n; ++j) {
            if (s.charAt(i) === s.charAt(j)) {
                // s[i][i+1..j-1][j]
                // s   [i+1..j-1]
                dp[i][j] = dp[i + 1][j - 1] + 2;
            } else {
                // s[i..j-1][j]
                // s[i..j-1]
                const sp1 = dp[i][j - 1];
                // s[i][i+1..j]
                // s   [i+1..j]
                const sp2 = dp[i + 1][j];
                dp[i][j] = Math.max(sp1, sp2);
            }
        }
    }
    return dp[0][n - 1];
};
// https://leetcode.cn/submissions/detail/381134314/
```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```js
/**
 * @param {number} amount
 * @param {number[]} coins
 * @return {number}
 */
 const change = function (amount, coins) {
    const n = coins.length;
    // dp[i][j] = 使用硬币 coins[0..i-1] 凑成总金额 j 的组合数
    const dp = new Array(n + 1);
    for (let i = 0; i <= n; ++i) {
        dp[i] = new Array(amount + 1).fill(0);
    }
    // 总金额为 0
    for (let i = 1; i <= n; ++i) {
        dp[i][0] = 1;
    }
    // 硬币数为 0
    for (let j = 1; j <= amount; ++j) {
        dp[0][j] = 0;
    }
    dp[0][0] = 1;
    for (let i = 1; i <= n; ++i) {
        for (let j = 1; j <= amount; ++j) {
            const x = coins[i - 1];
            if (j < x) {
                // 不包含硬币 x
                dp[i][j] = dp[i - 1][j];
            } else {
                const sp1 = dp[i - 1][j]; // 包含    0 个硬币 x
                const sp2 = dp[i][j - x]; // 包含 >= 1 个硬币 x
                dp[i][j] = sp1 + sp2;
                // 注意
                // dp[i][j - x] = 包含 >= 1 个硬币 x
                // dp[i-1][j-x] = 包含    1 个硬币 x
                // 举例 amount = 79, coins = [1, 2, 5]
                // dp[2][79] = 包含    0 个硬币 5，79 = 0 x 5 + 79，剩余 79 只能从 [1, 2] 凑
                // dp[2][74] = 包含    1 个硬币 5，79 = 1 x 5 + 74，剩余 74 只能从 [1, 2] 凑
                // dp[3][74] = 包含 >= 1 个硬币 5，79 = 1 x 5 + 74，剩余 74 可以从 [1, 2, 5] 凑
            }
        }
    }
    return dp[n][amount];
};
// https://leetcode.cn/submissions/detail/381201753/
```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```js
/**
 * @param {TreeNode} root
 * @return {TreeNode}
 */
const convertBST = function (root) {
    let sum = 0;

    const dfs = function (x) {
        if (x == null) {
            return;
        }
        dfs(x.right);
        sum += x.val;
        x.val = sum;
        dfs(x.left);
    };

    dfs(root);
    return root;
};
// https://leetcode.cn/submissions/detail/381684458/
```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```js
/**
 * @param {TreeNode} root
 * @return {number}
 */
const diameterOfBinaryTree = function (root) {
    let ans = 0;

    const maxDepth = function (x) {
        if (x == null) {
            return 0;
        }
        const left = maxDepth(x.left);
        const right = maxDepth(x.right);
        ans = Math.max(ans, left + right);
        return 1 + Math.max(left, right);
    };

    maxDepth(root);
    return ans;
};
// https://leetcode.cn/submissions/detail/381494284/
```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```js
/**
 * @param {string} s1
 * @param {string} s2
 * @return {boolean}
 */
 const checkInclusion = function (s1, s2) {
    const need = new Map();
    for (const c of s1) {
        if (!need.has(c)) {
            need.set(c, 0);
        }
        need.set(c, need.get(c) + 1);
    }
    const window = new Map();
    let valid = 0;
    // s[left..right) = Window Substring
    // s[right..n-1]  = Scanning
    let left = 0, right = 0;
    while (right < s2.length) {
        const c = s2.charAt(right++);
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
            while (left < right - s1.length) {
                const d = s2.charAt(left++);
                if (need.has(d)) {
                    if (window.get(d) === need.get(d)) {
                        --valid;
                    }
                    window.set(d, window.get(d) - 1);
                }
            }
        }
        if (valid === need.size) {
            return true;
        }
    }
    return false;
};
// https://leetcode.cn/submissions/detail/381036803/
```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

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

    // 子串 s1[0..i] s2[0..j] 的最小删除步数
    const _minDistance = function (s1, i, s2, j) {
        // 删除 s2[0..j]
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
                // 删除 s1[i] s2[j]
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                const sp1 = _minDistance(s1, i - 1, s2, j - 1) + 2;
                // 删除 s2[j]
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
// https://leetcode.cn/submissions/detail/381149691/
```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```js
/**
 * @param {TreeNode} root1
 * @param {TreeNode} root2
 * @return {TreeNode}
 */
const mergeTrees = function (root1, root2) {
    if (root1 == null) {
        return root2;
    }
    if (root2 == null) {
        return root1;
    }
    const mRoot = new TreeNode(root1.val + root2.val);
    mRoot.left = mergeTrees(root1.left, root2.left);
    mRoot.right = mergeTrees(root1.right, root2.right);
    return mRoot;
};
// https://leetcode.cn/submissions/detail/381571757/
```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```js
/**
 * @param {TreeNode} root
 * @return {TreeNode[]}
 */
 const findDuplicateSubtrees = function (root) {
    const counter = new Map();
    const ans = [];

    const postorder = function (x) {
        if (x == null) {
            return "#";
        }
        const left = postorder(x.left);
        const right = postorder(x.right);
        const res = left + "," + right + "," + x.val.toString();
        if (!counter.has(res)) {
            counter.set(res, 0);
        }
        counter.set(res, counter.get(res) + 1);
        if (counter.get(res) === 2) {
            ans.push(x);
        }
        return res;
    };

    postorder(root);
    return ans;
};
// https://leetcode.cn/submissions/detail/381256918/
```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```js
/**
 * @param {number[]} nums
 * @return {TreeNode}
 */
 const constructMaximumBinaryTree = function (nums, lo = 0, hi = nums.length - 1) {
    if (lo > hi) {
        return null;
    }
    let maxIndex = lo;
    for (let i = lo + 1; i <= hi; ++i) {
        if (nums[i] > nums[maxIndex]) {
            maxIndex = i;
        }
    }
    const root = new TreeNode(nums[maxIndex]);
    root.left = constructMaximumBinaryTree(nums, lo, maxIndex - 1);
    root.right = constructMaximumBinaryTree(nums, maxIndex + 1, hi);
    return root;
};
// https://leetcode.cn/submissions/detail/381287426/
```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```js
const LAND = 1;
const WATER = 0;

/**
 * @param {number[][]} grid
 * @return {number}
 */
const maxAreaOfIsland = function (grid) {
    let ans = 0, area = 0;

    const floodFill = function (grid, i, j) {
        if (i < 0 || i >= grid.length || j < 0 || j >= grid[0].length || grid[i][j] === WATER) {
            return;
        }
        ++area;
        grid[i][j] = WATER;
        floodFill(grid, i, j + 1);
        floodFill(grid, i, j - 1);
        floodFill(grid, i + 1, j);
        floodFill(grid, i - 1, j);
    };

    for (let i = 0; i < grid.length; ++i) {
        for (let j = 0; j < grid[0].length; ++j) {
            if (grid[i][j] === LAND) {
                area = 0;
                floodFill(grid, i, j);
                ans = Math.max(ans, area);
            }
        }
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381721094/
```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```js
/**
 * @param {number[]} nums
 * @param {number} k
 * @return {boolean}
 */
const canPartitionKSubsets = function (nums, k) {
    const n = nums.length;
    if (k > n) {
        return false;
    }
    const total = nums.reduce((sum, val) => sum + val, 0);
    if (total % k !== 0) {
        return false;
    }
    const target = Math.floor(total / k);
    let used = 0;
    const pathSums = new Array(n).fill(0);
    const memo = new Map();

    // 遍历『决策森林』的 k 棵『决策树』
    // 一棵『决策树』的『路径』代表一个『等和子集』
    // tree = 第几棵『决策树』，取 [0..k-1] 为值
    // edge =『决策树』的『边』，取数组 nums 的索引为值
    // pathSums[tree] = 第几棵『决策树』的『路径和』
    const backtrack = function (tree, edge) {
        let res = false;
        if (tree === k) {
            res = true;
        } else if (pathSums[tree] === target) {
            // 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            // 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            // 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            // 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            // 因为 C 的可选『边』是一样的
            if (!memo.has(used)) {
                // 遍历下一棵『决策树』
                res = backtrack(tree + 1, -1);
                memo.set(used, res);
            }
            res = memo.get(used);
        } else {
            // 通过去重，对同一棵树，优化『边』的遍历，避免『边+边』重复
            // 例如 1 和 2 分别是两条『边』，[1->2] 和 [2->1] 是重复的
            while (++edge < nums.length) {
                // 检查第 edge 位是否为 1
                // 即 nums[edge] 是否已经被其他『树』使用
                if (((used >> edge) & 1) === 1) {
                    continue;
                }
                const x = nums[edge];
                if (pathSums[tree] + x > target) {
                    continue;
                }
                pathSums[tree] += x;
                //『或』运算，将第 edge 位修改为 1
                used |= 1 << edge;
                res = backtrack(tree, edge);
                if (res) {
                    break;
                }
                pathSums[tree] -= x;
                //『异或』运算，将第 edge 位恢复为 0
                used ^= 1 << edge;
            }
        }
        return res;
    };

    return backtrack(0, -1);
};
// https://leetcode.cn/submissions/detail/381872034/
```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```js
/**
 * @param {TreeNode} root
 * @param {number} val
 * @return {TreeNode}
 */
const searchBST = function (root, val) {
    if (root == null) {
        return null;
    }
    if (val < root.val) {
        return searchBST(root.left, val);
    }
    if (root.val < val) {
        return searchBST(root.right, val);
    }
    return root;
};
// https://leetcode.cn/submissions/detail/381682431/
```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```js
/**
 * @param {TreeNode} root
 * @param {number} val
 * @return {TreeNode}
 */
const insertIntoBST = function (root, val) {
    if (root == null) {
        return new TreeNode(val);
    }
    if (val < root.val) {
        root.left = insertIntoBST(root.left, val);
    }
    if (root.val < val) {
        root.right = insertIntoBST(root.right, val);
    }
    return root;
};
// https://leetcode.cn/submissions/detail/381683231/
```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```js
/**
 * @param {number[]} nums
 * @param {number} target
 * @return {number}
 */
const search = function (nums, target, lo = 0, hi = nums.length - 1) {
    if (lo > hi) {
        return -1;
    }
    const mid = lo + Math.floor((hi - lo) / 2);
    if (target < nums[mid]) {
        return search(nums, target, lo, mid - 1);
    }
    if (nums[mid] < target) {
        return search(nums, target, mid + 1, hi);
    }
    return mid;
};
// https://leetcode.cn/submissions/detail/381716243/
```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```js
/**
 * @param {string} word1
 * @param {string} word2
 * @return {number}
 */
 const minimumDeleteSum = function (word1, word2) {
    const n1 = word1.length;
    const n2 = word2.length;
    const memo = new Array(n1);
    for (let i = 0; i < n1; ++i) {
        memo[i] = new Array(n2).fill(-1);
    }
    const sum1 = prefixSum(word1);
    const sum2 = prefixSum(word2);

    // 子串 s1[0..i] s2[0..j] 的最小 ASCII 删除和
    const _minimumDeleteSum = function (s1, i, s2, j) {
        if (i < 0 && j < 0) {
            return 0;
        }
        // 删除 s2[0..j]
        // s1""
        // s2[0..j]
        if (i < 0) {
            return sum2[j];
        }
        // 删除 s1[0..i]
        // s1[0..i]
        // s2""
        if (j < 0) {
            return sum1[i];
        }
        if (memo[i][j] === -1) {
            if (s1.charAt(i) === s2.charAt(j)) {
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                memo[i][j] = _minimumDeleteSum(s1, i - 1, s2, j - 1);
            } else {
                // 删除 s1[i] s2[j]
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                const sp1 = _minimumDeleteSum(s1, i - 1, s2, j - 1) + s1.charCodeAt(i) + s2.charCodeAt(j);
                // 删除 s2[j]
                // s1[0..i]
                // s2[0..j-1][j]
                const sp2 = _minimumDeleteSum(s1, i, s2, j - 1) + s2.charCodeAt(j);
                // 删除 s1[i]
                // s1[0..i-1][i]
                // s2[0..j]
                const sp3 = _minimumDeleteSum(s1, i - 1, s2, j) + s1.charCodeAt(i);
                memo[i][j] = Math.min(sp1, sp2, sp3);
            }
        }
        return memo[i][j];
    };

    return _minimumDeleteSum(word1, n1 - 1, word2, n2 - 1);
};

/**
 * @param {string} s
 * @return {number[]}
 */
const prefixSum = function (s) {
    const n = s.length;
    const sum = new Array(n).fill(0);
    sum[0] = s.charCodeAt(0);
    for (let i = 1; i < n; ++i) {
        sum[i] = sum[i - 1] + s.charCodeAt(i);
    }
    return sum;
}
// https://leetcode.cn/submissions/detail/381152588/
```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```js
/**
 * @param {number[]} prices
 * @param {number} fee
 * @return {number}
 */
 const maxProfit = function (prices, fee) {
    const n = prices.length;
    // dp[i][0] = 第 i 天，空仓状态下的最大利润
    // dp[i][1] = 第 i 天，持仓状态下的最大利润
    const dp = new Array(n);
    for (let i = 0; i < n; ++i) {
        dp[i] = new Array(2).fill(0);
    }
    dp[0][0] = 0;
    dp[0][1] = -prices[0] - fee;
    for (let i = 1; i < n; ++i) {
        // dp[i - 1][0]             >= dp[i - 1][0] - prices[i] - fee
        // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
        // => dp[i][0] >= dp[i][1]
        dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
        dp[i][1] = Math.max(dp[i - 1][0] - prices[i] - fee, dp[i - 1][1]);
    }
    return dp[n - 1][0];
};
// https://leetcode.cn/submissions/detail/381197279/
```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```js
/**
 * @param {number[]} temperatures
 * @return {number[]}
 */
 const dailyTemperatures = function (temperatures) {
    const n = temperatures.length;
    const ans = new Array(n).fill(0);
    const stack = [];
    for (let i = n - 1; i >= 0; --i) {
        while (stack.length > 0 && temperatures[stack.at(-1)] <= temperatures[i]) {
            stack.pop();
        }
        ans[i] = stack.length === 0 ? 0 : stack.at(-1) - i;
        stack.push(i);
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381069500/
```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```js
class DirectedEdge {
    constructor(v, w, weight) {
        this.v = v;
        this.w = w;
        this.weight = weight;
    }

    from() {
        return this.v;
    }

    to() {
        return this.w;
    }
}

class EdgeWeightedDigraph {
    constructor(V) {
        this.V = V;
        this.E = 0;
        this.adj = new Array(V);
        for (let v = 0; v < V; ++v) {
            this.adj[v] = [];
        }
    }

    addEdge(e) {
        const v = e.from();
        const w = e.to();
        this.adj[v].push(e);
        this.E++;
    }
}

class LazyDijkstraSP {
    constructor(G, s) {
        const V = G.V;
        this.marked = new Array(V).fill(false);
        this.distTo = new Array(V).fill(Number.POSITIVE_INFINITY);
        this.pq = new PriorityQueue({
            compare: (e, f) => {
                const dist1 = this.distTo[e.from()] + e.weight;
                const dist2 = this.distTo[f.from()] + f.weight;
                return dist1 - dist2;
            }
        });
        this.distTo[s] = 0.0;
        this.relax(G, s);
        while (!this.pq.isEmpty()) {
            const e = this.pq.dequeue();
            const w = e.to();
            if (!this.marked[w]) {
                this.relax(G, w);
            }
        }
    }

    relax(G, v) {
        this.marked[v] = true;
        for (const e of G.adj[v]) {
            const w = e.to();
            if (this.distTo[w] > this.distTo[v] + e.weight) {
                this.distTo[w] = this.distTo[v] + e.weight;
                this.pq.enqueue(e);
            }
        }
    }
}

/**
 * @param {number[][]} times
 * @param {number} n
 * @param {number} k
 * @return {number}
 */
const networkDelayTime = function (times, n, k) {
    const graph = new EdgeWeightedDigraph(n);
    for (const t of times) {
        graph.addEdge(new DirectedEdge(t[0] - 1, t[1] - 1, t[2]));
    }
    const spt = new LazyDijkstraSP(graph, k - 1);
    let maxTime = 0;
    for (let v = 0; v < n; ++v) {
        maxTime = Math.max(maxTime, spt.distTo[v]);
    }
    return maxTime < Number.POSITIVE_INFINITY ? maxTime : -1;
};
// https://leetcode.cn/submissions/detail/382229221/
```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```js
/**
 * @param {string[]} deadends
 * @param {string} target
 * @return {number}
 */
const openLock = function (deadends, target) {
    const marked = new Set(deadends);
    const queue = new Queue();
    const source = "0000";
    if (!marked.has(source)) {
        marked.add(source);
        queue.enqueue(source);
    }
    let count = 0;
    while (!queue.isEmpty()) {
        const n = queue.size();
        for (let i = 0; i < n; ++i) {
            const s = queue.dequeue();
            if (s === target) {
                return count;
            }
            for (let j = 0; j < 4; ++j) {
                const plus = plusOne(s, j);
                if (!marked.has(plus)) {
                    marked.add(plus);
                    queue.enqueue(plus);
                }
                const minus = minusOne(s, j);
                if (!marked.has(minus)) {
                    marked.add(minus);
                    queue.enqueue(minus);
                }
            }
        }
        ++count;
    }
    return -1;
};

const NINE = 57;
const ZERO = 48;

const plusOne = function (s, j) {
    const a = Array.from(s, x => x.charCodeAt(0));
    if (a[j] === NINE) {
        a[j] = ZERO;
    } else {
        a[j] += 1;
    }
    return String.fromCharCode(...a);
};

const minusOne = function (s, j) {
    const a = Array.from(s, x => x.charCodeAt(0));
    if (a[j] === ZERO) {
        a[j] = NINE;
    } else {
        a[j] -= 1;
    }
    return String.fromCharCode(...a);
};
// https://leetcode.cn/submissions/detail/381503316/
```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```js
/**
 * @param {number[][]} graph
 * @return {boolean}
 */
const isBipartite = function (graph) {
    const n = graph.length;
    const marked = new Array(n).fill(false);
    const color = new Array(n).fill(false);
    let bipartite = true;

    const dfs = function (graph, v) {
        marked[v] = true;
        for (const w of graph[v]) {
            if (!bipartite) {
                return;
            }
            if (!marked[w]) {
                color[w] = !color[v];
                dfs(graph, w);
            } else if (color[w] === color[v]) {
                bipartite = false;
            }
        }
    }

    for (let v = 0; v < n; ++v) {
        if (!marked[v]) {
            dfs(graph, v);
            if (!bipartite) {
                break;
            }
        }
    }
    return bipartite;
};
// https://leetcode.cn/submissions/detail/382164182/
```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```js
/**
 * @param {number[][]} graph
 * @return {number[][]}
 */
const allPathsSourceTarget = function (graph) {
    const ans = [];
    const path = [];
    const target = graph.length - 1;

    const dfs = function (graph, v) {
        path.push(v);
        if (v === target) {
            ans.push([...path]);
        } else {
            for (let w of graph[v]) {
                dfs(graph, w);
            }
        }
        path.pop();
    };

    dfs(graph, 0);
    return ans;
};
// https://leetcode.cn/submissions/detail/382237440/
```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```js
/**
 * @param {number[]} hand
 * @param {number} groupSize
 * @return {boolean}
 */
const isNStraightHand = function (hand, groupSize) {
    if (hand.length % groupSize !== 0) {
        return false;
    }
    hand.sort((a, b) => a - b);
    const counter = new Map();
    for (const card of hand) {
        if (!counter.has(card)) {
            counter.set(card, 0);
        }
        counter.set(card, counter.get(card) + 1);
    }
    for (const card of hand) {
        if (counter.get(card) > 0) {
            for (let i = 0; i < groupSize; ++i) {
                const x = card + i;
                const count = counter.get(x);
                if (!counter.has(x) || count === 0) {
                    return false;
                }
                counter.set(x, count - 1);
            }
        }
    }
    return true;
};
// https://leetcode.cn/submissions/detail/381691851/
```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```js
/**
 * @param {number[]} piles
 * @param {number} h
 * @return {number}
 */
const minEatingSpeed = function (piles, h) {
    let lo = 1;
    let hi = Math.max(...piles);
    let ans = 1;
    while (lo <= hi) {
        const mid = lo + Math.floor((hi - lo) / 2);
        if (canFinish(piles, h, mid)) {
            ans = mid;
            hi = mid - 1;
        } else {
            lo = mid + 1;
        }
    }
    return ans;
};

// 当吃香蕉的速度为 k 时，是否能在 h 小时内吃完
const canFinish = function (piles, h, k) {
    let hours = 0;
    for (const p of piles) {
        hours += Math.ceil(p / k);
    }
    return hours <= h;
};
// https://leetcode.cn/submissions/detail/381726993/
```

## 876. 链表的中间结点

<https://leetcode-cn.com/problems/middle-of-the-linked-list/>

```js
/**
 * @param {ListNode} head
 * @return {ListNode}
 */
 var middleNode = function (head) {
    let slow = head, fast = head;
    while (fast !== null && fast.next !== null) {
        slow = slow.next;
        fast = fast.next.next;
    }
    return slow;
};
// https://leetcode.cn/submissions/detail/380805080/
```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```js
/**
 * @param {number} n
 * @param {number[][]} dislikes
 * @return {boolean}
 */
const possibleBipartition = function (n, dislikes) {
    const graph = new Array(n);
    for (let v = 0; v < n; ++v) {
        graph[v] = [];
    }
    for (const d of dislikes) {
        const v = d[0] - 1;
        const w = d[1] - 1;
        graph[v].push(w);
        graph[w].push(v);
    }
    return isBipartite(graph);
};

/**
 * @param {number[][]} graph
 * @return {boolean}
 */
const isBipartite = function (graph) {
    const n = graph.length;
    const marked = new Array(n).fill(false);
    const color = new Array(n).fill(false);
    let bipartite = true;

    const dfs = function (graph, v) {
        marked[v] = true;
        for (const w of graph[v]) {
            if (!bipartite) {
                return;
            }
            if (!marked[w]) {
                color[w] = !color[v];
                dfs(graph, w);
            } else if (color[w] === color[v]) {
                bipartite = false;
            }
        }
    }

    for (let v = 0; v < n; ++v) {
        if (!marked[v]) {
            dfs(graph, v);
            if (!bipartite) {
                break;
            }
        }
    }
    return bipartite;
};
// https://leetcode.cn/submissions/detail/382165020/
```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```js
/**
 * @param {number[]} preorder
 * @param {number[]} postorder
 * @return {TreeNode}
 */
const constructFromPrePost = function (preorder, postorder,
                                       preStart = 0, preEnd = preorder.length - 1,
                                       postStart = 0, postEnd = postorder.length - 1,
                                       postorderMap = new Map(postorder.map((e, i) => [e, i]))) {
    if (preStart > preEnd) {
        return null;
    }
    const rootVal = preorder[preStart];
    const root = new TreeNode(rootVal);
    if (preStart < preEnd) {
        const leftRootVal = preorder[preStart + 1];
        const postLeftRoot = postorderMap.get(leftRootVal);
        const leftSize = postLeftRoot - postStart + 1;
        root.left = constructFromPrePost(preorder, postorder, preStart + 1, preStart + leftSize, postStart, postLeftRoot, postorderMap);
        root.right = constructFromPrePost(preorder, postorder, preStart + leftSize + 1, preEnd, postLeftRoot + 1, postEnd - 1, postorderMap);
    }
    return root;
};
// https://leetcode.cn/submissions/detail/381412408/
```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```js
/**
 * @param {number[]} nums
 * @return {number[]}
 */
const sortArrayByParity = function (nums) {
    // nums[0..i-1]     Even
    // nums[i..j]       Scanning
    // nums[j+1..n - 1] Odd
    let i = 0, j = nums.length - 1;
    while (i < j) {
        while (i < j && nums[i] % 2 === 0) {
            ++i;
        }
        while (i < j && nums[j] % 2 === 1) {
            --j;
        }
        [nums[i], nums[j]] = [nums[j], nums[i]];
    }
    return nums;
};
// https://leetcode.cn/submissions/detail/393033693/
```

```js
/**
 * @param {number[]} nums
 * @return {number[]}
 */
const sortArrayByParity = function (nums) {
    const n = nums.length;
    // nums[0..i]   Even
    // nums(i..j)   Scanning
    // nums[j..n-1] Odd
    let i = -1, j = n;
    while (true) {
        while (nums[++i] % 2 === 0) {
            if (i === n - 1) {
                break;
            }
        }
        while (nums[--j] % 2 === 1) {
            if (j === 0) {
                break;
            }
        }
        if (i >= j) {
            break;
        }
        [nums[i], nums[j]] = [nums[j], nums[i]];
    }
    return nums;
};
// https://leetcode.cn/submissions/detail/393033258/
```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```js
/**
 * @param {number[]} nums
 * @return {number[]}
 */
const sortArray = function (nums) {
    nums.sort(() => Math.random() - 0.5);
    sort(nums, 0, nums.length - 1);
    return nums;
};

const sort = function (nums, lo, hi) {
    if (lo >= hi) {
        return;
    }
    const j = partition(nums, lo, hi);
    sort(nums, lo, j - 1);
    sort(nums, j + 1, hi);
};

const partition = function (nums, lo, hi) {
    const v = nums[lo];
    let i = lo, j = hi + 1;
    while (true) {
        while (nums[++i] < v) {
            if (i === hi) {
                break;
            }
        }
        while (v < nums[--j]) {
            if (j === lo) {
                break;
            }
        }
        if (i >= j) {
            break;
        }
        swap(nums, i, j);
    }
    swap(nums, lo, j);
    return j;
};

const swap = function (nums, i, j) {
    const x = nums[i];
    nums[i] = nums[j];
    nums[j] = x;
};
// https://leetcode.cn/submissions/detail/381878838/
```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```js
/**
 * @param {string} s
 * @return {number}
 */
 const minAddToMakeValid = function (s) {
    // 性质一 一个「合法」括号组合的左括号数量一定等于右括号数量
    // 性质二 对于一个「合法」的括号字符串组合 p，必然对于
    // 任何 0 <= i < len(p) 都有：子串 p[0..i] 中
    // 左括号的数量都大于或等于右括号的数量
    let insertLeft = 0; // 已插入左括号的数量
    let needRight = 0;  // 待插入右括号的数量
    for (const ch of s) {
        if (ch === '(') {
            ++needRight;
        }
        if (ch === ')') {
            --needRight;
            // 性质二
            if (needRight === -1) {
                // A).. -> A()..
                //『必须立即』在位置 i 前插入 1 个左括号
                // 否则，后续任何插入都不能使区间 [0..i] 的匹配有效
                ++insertLeft;
                needRight = 0;
            }
        }
    }
    return insertLeft + needRight;
};
// https://leetcode.cn/submissions/detail/380974364/
```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```js
/**
 * @param {number[]} nums
 * @return {number[]}
 */
 var sortArrayByParityII = function (nums) {
    const n = nums.length;
    let i = 0, j = 1;
    while (true) {
        while (i <= n - 2 && nums[i] % 2 === 0) {
            i += 2;
        }
        while (j <= n - 1 && nums[j] % 2 === 1) {
            j += 2;
        }
        if (i > n - 2 || j > n - 1) {
            break;
        }
        [nums[i], nums[j]] = [nums[j], nums[i]];
    }
    return nums;
};
// https://leetcode.cn/submissions/detail/380713518/
```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```js
/**
 * @param {number[][]} matrix
 * @return {number}
 */
 const minFallingPathSum = function (matrix) {
    const n = matrix.length;
    const memo = new Array(n);
    for (let i = 0; i < n; ++i) {
        memo[i] = new Array(n);
    }
    let ans = Number.POSITIVE_INFINITY;
    for (let col = 0; col < n; ++col) {
        ans = Math.min(ans, minFallingPathSumSP(matrix, n - 1, col, memo));
    }
    return ans;
};

// 从 matrix[0][0..n-1] 到 matrix[row][col] 的最小下降路径和
const minFallingPathSumSP = function (matrix, row, col, memo) {
    if (col < 0 || col >= matrix.length) {
        return Number.POSITIVE_INFINITY;
    }
    if (row === 0) {
        return matrix[row][col];
    }
    if (memo[row][col] === undefined) {
        const sp1 = minFallingPathSumSP(matrix, row - 1, col - 1, memo);
        const sp2 = minFallingPathSumSP(matrix, row - 1, col, memo);
        const sp3 = minFallingPathSumSP(matrix, row - 1, col + 1, memo);
        memo[row][col] = Math.min(sp1, sp2, sp3) + matrix[row][col];
    }
    return memo[row][col];
}
// https://leetcode.cn/submissions/detail/381306413/
```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```js
/**
 * @param {number[][]} firstList
 * @param {number[][]} secondList
 * @return {number[][]}
 */
 const intervalIntersection = function (firstList, secondList) {
    const ans = [];
    let i = 0, j = 0;
    while (i < firstList.length && j < secondList.length) {
        const [start1, end1] = firstList[i];
        const [start2, end2] = secondList[j];
        if (end1 < start2) { // 不相交
            ++i;
        } else if (end2 < start1) { // 不相交
            ++j;
        } else { // 相交
            ans.push([Math.max(start1, start2), Math.min(end1, end2)]);
            if (end1 < end2) {
                ++i;
            } else {
                ++j;
            }
        }
    }
    return ans;
};
// https://leetcode.cn/submissions/detail/381048396/
```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```js
class UF {
    constructor(n) {
        this.parent = new Array(n);
        for (let i = 0; i < n; ++i) {
            this.parent[i] = i;
        }
        this.rank = new Array(n).fill(0);
        this.count = n;
    }

    find(p) {
        while (p !== this.parent[p]) {
            this.parent[p] = this.parent[this.parent[p]];
            p = this.parent[p];
        }
        return p;
    }

    union(p, q) {
        const rootP = this.find(p);
        const rootQ = this.find(q);
        if (rootP !== rootQ) {
            if (this.rank[rootP] < this.rank[rootQ]) {
                this.parent[rootP] = rootQ;
            } else if (this.rank[rootQ] < this.rank[rootP]) {
                this.parent[rootQ] = rootP;
            } else {
                this.parent[rootP] = rootQ;
                this.rank[rootQ]++;
            }
            this.count--;
        }
    }

    connected(p, q) {
        return this.find(p) === this.find(q);
    }
}

/**
 * @param {string[]} equations
 * @return {boolean}
 */
const equationsPossible = function (equations) {
    const A = 97;
    const uf = new UF(26);
    for (const e of equations) {
        if (e.charAt(1) === '=') {
            const p = e.charCodeAt(0) - A;
            const q = e.charCodeAt(3) - A;
            uf.union(p, q);
        }
    }
    for (const e of equations) {
        if (e.charAt(1) === '!') {
            const p = e.charCodeAt(0) - A;
            const q = e.charCodeAt(3) - A;
            if (uf.connected(p, q)) {
                return false;
            }
        }
    }
    return true;
};
// https://leetcode.cn/submissions/detail/382040104/
```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```js
/**
 * @param {number[]} weights
 * @param {number} days
 * @return {number}
 */
const shipWithinDays = function (weights, days) {
    let lo = Math.max(...weights);
    let hi = weights.reduce((sum, val) => sum + val, 0);
    let ans = lo;
    while (lo <= hi) {
        const mid = lo + Math.floor((hi - lo) / 2);
        if (canFinish(weights, days, mid)) {
            ans = mid;
            hi = mid - 1;
        } else {
            lo = mid + 1;
        }
    }
    return ans;
};

// 当船的运载能力为 capacity 时，是否能在 days 天内送完
const canFinish = function (weights, days, capacity) {
    const n = weights.length;
    let minDays = 0;
    let i = 0;
    while (i < n) {
        let sum = 0;
        while (i < n && sum + weights[i] <= capacity) {
            sum += weights[i++];
        }
        ++minDays;
    }
    return minDays <= days;
};
// https://leetcode.cn/submissions/detail/381729033/
```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```js
const LAND = 1;
const WATER = 0;

/**
 * @param {number[][]} grid
 * @return {number}
 */
const numEnclaves = function (grid) {
    const m = grid.length, n = grid[0].length;
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
    let count = 0;
    for (let i = 0; i < m; ++i) {
        for (let j = 0; j < n; ++j) {
            if (grid[i][j] === LAND) {
                ++count;
            }
        }
    }
    return count;
};

const floodFill = function (grid, i, j) {
    if (i < 0 || i >= grid.length || j < 0 || j >= grid[0].length || grid[i][j] === WATER) {
        return;
    }
    grid[i][j] = WATER;
    floodFill(grid, i, j + 1);
    floodFill(grid, i, j - 1);
    floodFill(grid, i + 1, j);
    floodFill(grid, i - 1, j);
};
// https://leetcode.cn/submissions/detail/381722635/
```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```js
/**
 * @param {number[][]} clips
 * @param {number} time
 * @return {number}
 */
 const videoStitching = function (clips, time) {
    clips.sort((a, b) => {
        if (a[0] === b[0]) {
            return b[1] - a[1];
        }
        return a[0] - b[0];
    });
    const n = clips.length;
    let maxEnd = 0;
    let count = 0;
    let i = 0;
    // 当 clips[i] 与 [0, maxEnd] 重叠（相交或被覆盖）时
    while (i < n && clips[i][0] <= maxEnd) {
        // 记录与 [0, maxEnd] 重叠的所有区间中最大的 end
        let nextEnd = clips[i][1];
        while (++i < n && clips[i][0] <= maxEnd) {
            nextEnd = Math.max(nextEnd, clips[i][1]);
        }
        ++count;
        maxEnd = nextEnd;
        if (maxEnd >= time) {
            return count;
        }
    }
    return -1;
};
// https://leetcode.cn/submissions/detail/381056820/
```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```js
/**
 * @param {string} text1
 * @param {string} text2
 * @return {number}
 */
 const longestCommonSubsequence = function (text1, text2) {
    const n1 = text1.length;
    const n2 = text2.length;
    // text1[0..i-1] = text1 的长度为 i 的前缀
    // text2[0..j-1] = text2 的长度为 j 的前缀
    // dp[i][j] = LCS(text1[0..i-1], text2[0..j-1]) 的长度
    const dp = new Array(n1 + 1);
    for (let i = 0; i <= n1; ++i) {
        dp[i] = new Array(n2 + 1).fill(0);
    }
    for (let i = 1; i <= n1; ++i) {
        for (let j = 1; j <= n2; ++j) {
            if (text1.charAt(i - 1) === text2.charAt(j - 1)) {
                dp[i][j] = dp[i - 1][j - 1] + 1;
            } else {
                dp[i][j] = Math.max(dp[i][j - 1], dp[i - 1][j]);
            }
        }
    }
    return dp[n1][n2];
};
// https://leetcode.cn/submissions/detail/381140639/
```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```js
const LAND = 0;
const WATER = 1;

/**
 * @param {number[][]} grid
 * @return {number}
 */
const closedIsland = function (grid) {
    const m = grid.length, n = grid[0].length;
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
    let count = 0;
    for (let i = 0; i < m; ++i) {
        for (let j = 0; j < n; ++j) {
            if (grid[i][j] === LAND) {
                floodFill(grid, i, j);
                ++count;
            }
        }
    }
    return count;
};

const floodFill = function (grid, i, j) {
    if (i < 0 || i >= grid.length || j < 0 || j >= grid[0].length || grid[i][j] === WATER) {
        return;
    }
    grid[i][j] = WATER;
    floodFill(grid, i, j + 1);
    floodFill(grid, i, j - 1);
    floodFill(grid, i + 1, j);
    floodFill(grid, i - 1, j);
};
// https://leetcode.cn/submissions/detail/381722043/
```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```js
/**
 * @param {number[][]} intervals
 * @return {number}
 */
 const removeCoveredIntervals = function (intervals) {
    intervals.sort((a, b) => {
        if (a[0] === b[0]) {
            return b[1] - a[1];
        }
        return a[0] - b[0];
    });
    const n = intervals.length;
    let count = n;
    let maxEnd = 0;
    for (let i = 0; i < n; ++i) {
        const end = intervals[i][1];
        if (end <= maxEnd) {
            --count;
        } else {
            maxEnd = end;
        }
    }
    return count;
};
// https://leetcode.cn/submissions/detail/381055673/
```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```js
/**
 * @param {TreeNode} root
 * @return {TreeNode}
 */
const balanceBST = function (root) {
    const nums = [];
    // 深度优先搜索，获取中序遍历结果
    const dfs = function (x) {
        if (x == null) {
            return;
        }
        dfs(x.left);
        nums.push(x.val);
        dfs(x.right);
    };
    dfs(root);
    return sortedArrayToBST(nums);
};

/**
 * 将有序数组 nums[lo..hi] 转换为二叉搜索树
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
// https://leetcode.cn/submissions/detail/381338080/
```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```js
class DirectedEdge {
    constructor(v, w, weight) {
        this.v = v;
        this.w = w;
        this.weight = weight;
    }

    from() {
        return this.v;
    }

    to() {
        return this.w;
    }
}

class EdgeWeightedDigraph {
    constructor(V) {
        this.V = V;
        this.E = 0;
        this.adj = new Array(V);
        for (let v = 0; v < V; ++v) {
            this.adj[v] = [];
        }
    }

    addEdge(e) {
        const v = e.from();
        const w = e.to();
        this.adj[v].push(e);
        this.E++;
    }
}

class LazyDijkstraLP {
    constructor(G, s) {
        const V = G.V;
        this.marked = new Array(V).fill(false);
        this.distTo = new Array(V).fill(Number.NEGATIVE_INFINITY);
        this.pq = new PriorityQueue({
            compare: (e, f) => {
                const dist1 = this.distToEdge(e);
                const dist2 = this.distToEdge(f);
                return dist2 - dist1;
            }
        });
        this.distTo[s] = 1.0;
        this.relax(G, s);
        while (!this.pq.isEmpty()) {
            const e = this.pq.dequeue();
            const w = e.to();
            if (!this.marked[w]) {
                this.relax(G, w);
            }
        }
    }

    relax(G, v) {
        this.marked[v] = true;
        for (const e of G.adj[v]) {
            const w = e.to();
            const dist = this.distToEdge(e);
            if (this.distTo[w] < dist) {
                this.distTo[w] = dist;
                this.pq.enqueue(e);
            }
        }
    }

    distToEdge(e) {
        return this.distTo[e.from()] * e.weight;
    }

    hasPathTo(v) {
        return this.marked[v];
    }
}

/**
 * @param {number} n
 * @param {number[][]} edges
 * @param {number[]} succProb
 * @param {number} start
 * @param {number} end
 * @return {number}
 */
const maxProbability = function (n, edges, succProb, start, end) {
    const graph = new EdgeWeightedDigraph(n);
    for (let i = 0; i < edges.length; ++i) {
        const v = edges[i][0];
        const w = edges[i][1];
        const weight = succProb[i];
        graph.addEdge(new DirectedEdge(v, w, weight));
        graph.addEdge(new DirectedEdge(w, v, weight));
    }
    const lpt = new LazyDijkstraLP(graph, start);
    if (lpt.hasPathTo(end)) {
        return lpt.distTo[end];
    }
    return 0.0;
};
// https://leetcode.cn/submissions/detail/382235019/
```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```js
/**
 * @param {string} s
 * @return {number}
 */
 var minInsertions = function (s) {
    let insertLeft = 0;  // 已插入左括号的数量
    let insertRight = 0; // 已插入右括号的数量
    let needRight = 0;   // 待插入右括号的数量
    for (const ch of s) {
        if (ch === '(') {
            // A((B)(.. -> A((B))(..
            if (needRight % 2 === 1) {
                //『必须立即』在位置 i 前插入 1 个右括号
                // 否则，后续任何插入都不能使区间 [0..i-1] 的匹配有效
                ++insertRight;
                --needRight;
            }
            needRight += 2;
        }
        if (ch === ')') {
            --needRight;
            // A).. -> A()..
            if (needRight === -1) {
                //『必须立即』在位置 i 前插入 1 个左括号
                // 否则，后续任何插入都不能使区间 [0..i] 的匹配有效
                ++insertLeft;
                needRight = 1;
            }
        }
    }
    return insertLeft + insertRight + needRight;
};
// https://leetcode.cn/submissions/detail/380974881/
```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```js
class Edge {
    constructor(v, w, weight) {
        this.v = v;
        this.w = w;
        this.weight = weight;
    }

    either() {
        return this.v;
    }

    other(vertex) {
        if (vertex === this.v) {
            return this.w;
        }
        return this.v;
    }
}

class EdgeWeightedGraph {
    constructor(V) {
        this.V = V;
        this.E = 0;
        this.adj = new Array(V);
        for (let v = 0; v < V; ++v) {
            this.adj[v] = [];
        }
    }

    addEdge(e) {
        const v = e.either();
        const w = e.other(v);
        this.adj[v].push(e);
        this.adj[w].push(e);
        this.E++;
    }
}

class LazyPrimMST {
    constructor(G) {
        this.weight = 0.0;
        this.pq = new PriorityQueue({compare: (a, b) => a.weight - b.weight});
        const V = G.V;
        this.marked = new Array(V).fill(false);
        for (let v = 0; v < V; ++v) {
            if (!this.marked[v]) {
                this.prim(G, v);
            }
        }
    }

    prim(G, s) {
        this.scan(G, s);
        while (!this.pq.isEmpty()) {
            const e = this.pq.dequeue();
            const v = e.either();
            const w = e.other(v);
            if (this.marked[v] && this.marked[w]) {
                continue;
            }
            this.weight += e.weight;
            if (!this.marked[v]) {
                this.scan(G, v);
            }
            if (!this.marked[w]) {
                this.scan(G, w);
            }
        }
    }

    scan(G, v) {
        this.marked[v] = true;
        for (const e of G.adj[v]) {
            const w = e.other(v);
            if (!this.marked[w]) {
                this.pq.enqueue(e);
            }
        }
    }
}

/**
 * @param {number[][]} points
 * @return {number}
 */
const minCostConnectPoints = function (points) {
    const V = points.length;
    const graph = new EdgeWeightedGraph(V);
    for (let v = 0; v < V; ++v) {
        for (let w = v + 1; w < V; ++w) {
            const weight = Math.abs(points[v][0] - points[w][0]) + Math.abs(points[v][1] - points[w][1]);
            graph.addEdge(new Edge(v, w, weight));
        }
    }
    const mst = new LazyPrimMST(graph);
    return mst.weight;
};
// https://leetcode.cn/submissions/detail/382218937/
```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```js
class DirectedEdge {
    constructor(v, w, weight) {
        this.v = v;
        this.w = w;
        this.weight = weight;
    }

    from() {
        return this.v;
    }

    to() {
        return this.w;
    }
}

class EdgeWeightedDigraph {
    constructor(V) {
        this.V = V;
        this.E = 0;
        this.adj = new Array(V);
        for (let v = 0; v < V; ++v) {
            this.adj[v] = [];
        }
    }

    addEdge(e) {
        const v = e.from();
        const w = e.to();
        this.adj[v].push(e);
        this.E++;
    }
}

class LazyDijkstraSP {
    constructor(G, s) {
        const V = G.V;
        this.marked = new Array(V).fill(false);
        this.distTo = new Array(V).fill(Number.POSITIVE_INFINITY);
        this.pq = new PriorityQueue({
            compare: (e, f) => {
                const dist1 = Math.max(this.distTo[e.from()], e.weight);
                const dist2 = Math.max(this.distTo[f.from()], f.weight);
                return dist1 - dist2;
            }
        });
        this.distTo[s] = 0.0;
        this.relax(G, s);
        while (!this.pq.isEmpty()) {
            const e = this.pq.dequeue();
            const w = e.to();
            if (!this.marked[w]) {
                this.relax(G, w);
            }
        }
    }

    relax(G, v) {
        this.marked[v] = true;
        for (const e of G.adj[v]) {
            const w = e.to();
            if (this.distTo[w] > Math.max(this.distTo[v], e.weight)) {
                this.distTo[w] = Math.max(this.distTo[v], e.weight);
                this.pq.enqueue(e);
            }
        }
    }
}

/**
 * @param {number[][]} heights
 * @return {number}
 */
const minimumEffortPath = function (heights) {
    const m = heights.length;
    const n = heights[0].length;
    const graph = new EdgeWeightedDigraph(m * n);
    const directions = [[0, 1], [0, -1], [1, 0], [-1, 0]];
    for (let i = 0; i < m; ++i) {
        for (let j = 0; j < n; ++j) {
            for (const d of directions) {
                const x = i + d[0];
                const y = j + d[1];
                if (x >= 0 && x <= m - 1 && y >= 0 && y <= n - 1) {
                    const v = i * n + j;
                    const w = x * n + y;
                    const weight = Math.abs(heights[i][j] - heights[x][y]);
                    graph.addEdge(new DirectedEdge(v, w, weight));
                }
            }
        }
    }
    const spt = new LazyDijkstraSP(graph, 0);
    return spt.distTo[(m - 1) * n + n - 1];
};
// https://leetcode.cn/submissions/detail/382231915/
```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```js
const LAND = 1;
const WATER = 0;

/**
 * @param {number[][]} grid1
 * @param {number[][]} grid2
 * @return {number}
 */
const countSubIslands = function (grid1, grid2) {
    const m = grid2.length, n = grid2[0].length;
    for (let i = 0; i < m; ++i) {
        for (let j = 0; j < n; ++j) {
            // 淹没『非子岛屿』
            if (grid2[i][j] === LAND && grid1[i][j] === WATER) {
                floodFill(grid2, i, j);
            }
        }
    }
    let count = 0;
    for (let i = 0; i < m; ++i) {
        for (let j = 0; j < n; ++j) {
            if (grid2[i][j] === LAND) {
                floodFill(grid2, i, j);
                ++count;
            }
        }
    }
    return count;
};

const floodFill = function (grid, i, j) {
    if (i < 0 || i >= grid.length || j < 0 || j >= grid[0].length || grid[i][j] === WATER) {
        return;
    }
    grid[i][j] = WATER;
    floodFill(grid, i, j + 1);
    floodFill(grid, i, j - 1);
    floodFill(grid, i + 1, j);
    floodFill(grid, i - 1, j);
};
// https://leetcode.cn/submissions/detail/381723390/
```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode-cn.com/problems/kth-node-from-end-of-list-lcci/>

```js
/**
 * @param {ListNode} head
 * @param {number} k
 * @return {number}
 */
const kthToLast = function (head, k) {
    let slow = head, fast = head;
    for (let i = 1; i <= k; ++i) {
        fast = fast.next;
    }
    while (fast !== null) {
        slow = slow.next;
        fast = fast.next;
    }
    return slow.val;
};
// https://leetcode.cn/submissions/detail/393493330/
```
