<!-- omit in toc -->
# LeetCode 题解：Dart

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

```dart

```

## 2. 两数相加

<https://leetcode-cn.com/problems/add-two-numbers/>

```dart

```

## 3. 无重复字符的最长子串

<https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/>

```dart

```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```dart

```

## 5. 最长回文子串

<https://leetcode.cn/problems/longest-palindromic-substring/>

```dart

```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```dart

```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```dart

```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```dart

```

## 15. 三数之和

<https://leetcode-cn.com/problems/3sum/>

```dart

```

## 18. 四数之和

<https://leetcode.cn/problems/4sum/>

```dart

```

## 19. 删除链表的倒数第 N 个结点

<https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/>

```dart

```

## 20. 有效的括号

<https://leetcode-cn.com/problems/valid-parentheses/>

```dart

```

## 21. 合并两个有序链表

<https://leetcode-cn.com/problems/merge-two-sorted-lists/>

```dart

```

## 22. 括号生成

<https://leetcode.cn/problems/generate-parentheses/>

```dart

```

## 23. 合并 K 个升序链表

<https://leetcode-cn.com/problems/merge-k-sorted-lists/>

```dart

```

## 24. 两两交换链表中的节点

<https://leetcode-cn.com/problems/swap-nodes-in-pairs/>

```dart

```

## 25. K 个一组翻转链表

<https://leetcode.cn/problems/reverse-nodes-in-k-group/>

```dart

```

## 26. 删除有序数组中的重复项

<https://leetcode.cn/problems/remove-duplicates-from-sorted-array/>

```dart

```

## 27. 移除元素

<https://leetcode.cn/problems/remove-element/>

```dart

```

## 28. 实现 strStr()

<https://leetcode.cn/problems/implement-strstr/>

```dart

```

## 33. 搜索旋转排序数组

<https://leetcode.cn/problems/search-in-rotated-sorted-array/>

```dart

```

## 34. 在排序数组中查找元素的第一个和最后一个位置

<https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/>

```dart

```

## 37. 解数独

<https://leetcode.cn/problems/sudoku-solver/>

```dart

```

## 39. 组合总和

<https://leetcode.cn/problems/combination-sum/>

```dart

```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```dart

```

## 42. 接雨水

<https://leetcode.cn/problems/trapping-rain-water/>

```dart

```

## 46. 全排列

<https://leetcode.cn/problems/permutations/>

```dart

```

## 47. 全排列 II

<https://leetcode.cn/problems/permutations-ii/>

```dart

```

## 51. N 皇后

<https://leetcode.cn/problems/n-queens/>

```dart

```

## 52. N 皇后 II

<https://leetcode.cn/problems/n-queens-ii/>

```dart

```

## 53. 最大子数组和

<https://leetcode.cn/problems/maximum-subarray/>

```dart

```

## 56. 合并区间

<https://leetcode.cn/problems/merge-intervals/>

```dart

```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```dart

```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```dart

```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```dart

```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```dart

```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```dart

```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```dart

```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```dart

```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```dart

```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```dart

```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```dart

```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```dart

```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```dart

```

## 92. 反转链表 II

<https://leetcode-cn.com/problems/reverse-linked-list-ii/>

```dart

```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```dart

```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```dart

```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```dart

```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```dart

```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```dart

```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```dart

```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```dart

```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```dart

```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```dart

```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```dart

```

## 107. 二叉树的层序遍历 II

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```dart

```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```dart

```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```dart

```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```dart

```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```dart

```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```dart

```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```dart

```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```dart

```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```dart

```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```dart

```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```dart

```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```dart

```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```dart

```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```dart

```

## 141. 环形链表

<https://leetcode-cn.com/problems/linked-list-cycle/>

```dart

```

## 142. 环形链表 II

<https://leetcode-cn.com/problems/linked-list-cycle-ii/>

```dart

```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```dart

```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```dart

```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```dart

```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```dart

```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```dart

```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```dart

```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```dart

```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```dart

```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```dart

```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```dart

```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```dart

```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```dart

```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```dart

```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```dart

```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```dart

```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```dart

```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```dart

```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```dart

```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```dart

```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```dart

```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```dart

```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```dart

```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```dart

```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```dart

```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```dart

```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```dart

```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```dart

```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```dart

```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```dart

```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```dart

```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```dart

```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```dart

```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```dart

```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```dart

```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```dart

```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```dart

```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```dart

```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```dart

```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```dart

```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```dart

```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```dart

```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```dart

```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```dart

```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```dart

```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```dart

```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```dart

```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```dart

```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```dart

```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```dart

```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```dart

```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```dart

```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```dart

```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```dart

```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```dart

```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```dart

```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```dart

```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```dart

```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```dart

```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```dart

```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```dart

```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```dart

```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```dart

```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```dart

```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```dart

```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```dart

```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```dart

```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```dart

```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```dart

```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```dart

```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```dart

```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```dart

```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```dart

```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```dart

```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```dart

```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```dart

```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```dart

```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```dart

```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```dart

```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```dart

```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```dart

```

## 876. 链表的中间结点

<https://leetcode-cn.com/problems/middle-of-the-linked-list/>

```dart

```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```dart

```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```dart

```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```dart

```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```dart

```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```dart

```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```dart

```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```dart

```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```dart

```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```dart

```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```dart

```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```dart

```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```dart

```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```dart

```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```dart

```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```dart

```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```dart

```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```dart

```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```dart

```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```dart

```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```dart

```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```dart

```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode-cn.com/problems/kth-node-from-end-of-list-lcci/>

```dart

```
