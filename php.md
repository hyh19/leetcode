<!-- omit in toc -->
# LeetCode 题解：PHP

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

```php

```

## 2. 两数相加

<https://leetcode-cn.com/problems/add-two-numbers/>

```php

```

## 3. 无重复字符的最长子串

<https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/>

```php

```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```php

```

## 5. 最长回文子串

<https://leetcode.cn/problems/longest-palindromic-substring/>

```php

```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```php

```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```php

```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```php

```

## 15. 三数之和

<https://leetcode-cn.com/problems/3sum/>

```php

```

## 18. 四数之和

<https://leetcode.cn/problems/4sum/>

```php

```

## 19. 删除链表的倒数第 N 个结点

<https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/>

```php

```

## 20. 有效的括号

<https://leetcode-cn.com/problems/valid-parentheses/>

```php

```

## 21. 合并两个有序链表

<https://leetcode-cn.com/problems/merge-two-sorted-lists/>

```php

```

## 22. 括号生成

<https://leetcode.cn/problems/generate-parentheses/>

```php

```

## 23. 合并 K 个升序链表

<https://leetcode-cn.com/problems/merge-k-sorted-lists/>

```php

```

## 24. 两两交换链表中的节点

<https://leetcode-cn.com/problems/swap-nodes-in-pairs/>

```php

```

## 25. K 个一组翻转链表

<https://leetcode.cn/problems/reverse-nodes-in-k-group/>

```php

```

## 26. 删除有序数组中的重复项

<https://leetcode.cn/problems/remove-duplicates-from-sorted-array/>

```php

```

## 27. 移除元素

<https://leetcode.cn/problems/remove-element/>

```php

```

## 28. 实现 strStr()

<https://leetcode.cn/problems/implement-strstr/>

```php

```

## 33. 搜索旋转排序数组

<https://leetcode.cn/problems/search-in-rotated-sorted-array/>

```php

```

## 34. 在排序数组中查找元素的第一个和最后一个位置

<https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/>

```php

```

## 37. 解数独

<https://leetcode.cn/problems/sudoku-solver/>

```php

```

## 39. 组合总和

<https://leetcode.cn/problems/combination-sum/>

```php

```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```php

```

## 42. 接雨水

<https://leetcode.cn/problems/trapping-rain-water/>

```php

```

## 46. 全排列

<https://leetcode.cn/problems/permutations/>

```php

```

## 47. 全排列 II

<https://leetcode.cn/problems/permutations-ii/>

```php

```

## 51. N 皇后

<https://leetcode.cn/problems/n-queens/>

```php

```

## 52. N 皇后 II

<https://leetcode.cn/problems/n-queens-ii/>

```php

```

## 53. 最大子数组和

<https://leetcode.cn/problems/maximum-subarray/>

```php

```

## 56. 合并区间

<https://leetcode.cn/problems/merge-intervals/>

```php

```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```php

```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```php

```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```php

```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```php

```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```php

```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```php

```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```php

```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```php

```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```php

```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```php

```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```php

```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```php

```

## 92. 反转链表 II

<https://leetcode-cn.com/problems/reverse-linked-list-ii/>

```php

```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```php

```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```php

```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```php

```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```php

```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```php

```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```php

```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```php

```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```php

```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```php

```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```php

```

## 107. 二叉树的层序遍历 II

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```php

```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```php

```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```php

```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```php

```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```php

```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```php

```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```php

```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```php

```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```php

```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```php

```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```php

```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```php

```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```php

```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```php

```

## 141. 环形链表

<https://leetcode-cn.com/problems/linked-list-cycle/>

```php

```

## 142. 环形链表 II

<https://leetcode-cn.com/problems/linked-list-cycle-ii/>

```php

```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```php

```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```php

```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```php

```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```php

```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```php

```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```php

```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```php

```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```php

```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```php

```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```php

```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```php

```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```php

```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```php

```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```php

```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```php

```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```php

```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```php

```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```php

```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```php

```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```php

```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```php

```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```php

```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```php

```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```php

```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```php

```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```php

```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```php

```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```php

```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```php

```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```php

```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```php

```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```php

```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```php

```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```php

```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```php

```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```php

```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```php

```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```php

```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```php

```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```php

```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```php

```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```php

```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```php

```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```php

```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```php

```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```php

```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```php

```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```php

```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```php

```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```php

```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```php

```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```php

```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```php

```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```php

```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```php

```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```php

```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```php

```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```php

```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```php

```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```php

```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```php

```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```php

```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```php

```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```php

```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```php

```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```php

```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```php

```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```php

```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```php

```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```php

```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```php

```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```php

```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```php

```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```php

```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```php

```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```php

```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```php

```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```php

```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```php

```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```php

```

## 876. 链表的中间结点

<https://leetcode-cn.com/problems/middle-of-the-linked-list/>

```php

```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```php

```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```php

```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```php

```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```php

```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```php

```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```php

```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```php

```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```php

```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```php

```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```php

```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```php

```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```php

```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```php

```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```php

```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```php

```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```php

```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```php

```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```php

```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```php

```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```php

```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```php

```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode-cn.com/problems/kth-node-from-end-of-list-lcci/>

```php

```
