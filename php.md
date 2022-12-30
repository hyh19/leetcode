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
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @param Integer $target
     * @return Integer[]
     */
    function twoSum(array $nums, int $target): array
    {
        $valToIndex = [];
        for ($i = 0; $i < count($nums); ++$i) {
            $x = $nums[$i];
            $need = $target - $x;
            if (array_key_exists($need, $valToIndex)) {
                return [$valToIndex[$need], $i];
            }
            $valToIndex[$x] = $i;
        }
        return [];
    }
}
// https://leetcode.cn/submissions/detail/382525462/
```

## 2. 两数相加

<https://leetcode-cn.com/problems/add-two-numbers/>

```php
<?php

class Solution
{
    /**
     * @param ListNode $l1
     * @param ListNode $l2
     * @return ListNode
     */
    function addTwoNumbers(ListNode $l1, ListNode $l2): ListNode
    {
        $dummyHead = new ListNode();
        $ptr = $dummyHead;
        $carry = 0;
        while ($l1 !== null || $l2 !== null || $carry > 0) {
            $sum = $carry;
            if ($l1 !== null) {
                $sum += $l1->val;
                $l1 = $l1->next;
            }
            if ($l2 !== null) {
                $sum += $l2->val;
                $l2 = $l2->next;
            }
            $ptr->next = new ListNode($sum % 10);
            $ptr = $ptr->next;
            $carry = floor($sum / 10);
        }
        return $dummyHead->next;
    }
}
// https://leetcode.cn/submissions/detail/382718463/
```

## 3. 无重复字符的最长子串

<https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/>

```php
<?php

class Solution
{
    /**
     * @param string $s
     * @return int
     */
    function lengthOfLongestSubstring(string $s): int
    {
        $ans = 0;
        $win = [];
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        $left = 0;
        $right = 0;
        while ($right < strlen($s)) {
            $add = $s[$right];
            if (!array_key_exists($add, $win)) {
                $win[$add] = $add;
                ++$right;
            } else {
                while ($left <= $right) {
                    $del = $s[$left++];
                    unset($win[$del]);
                    if ($add === $del) {
                        break;
                    }
                }
            }
            $ans = max($ans, $right - $left);
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/383306210/
```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums1
     * @param Integer[] $nums2
     * @return Float
     */
    function findMedianSortedArrays(array $nums1, array $nums2): float
    {
        $total = count($nums1) + count($nums2);
        $half = floor($total / 2);
        if ($total % 2 === 0) {
            $k1 = $this->getKthElement($nums1, 0, $nums2, 0, $half);
            $k2 = $this->getKthElement($nums1, 0, $nums2, 0, $half + 1);
            return ($k1 + $k2) / 2;
        }
        return $this->getKthElement($nums1, 0, $nums2, 0, $half + 1);
    }

    /**
     * 寻找两个正序数组 nums1[start1..end1] 和 nums2[start2..end2] 从小到大排列的第 k 个数
     *
     * @param Integer[] $nums1
     * @param Integer $start1
     * @param Integer[] $nums2
     * @param Integer $start2
     * @param Integer $k
     * @return Integer
     */
    function getKthElement(array $nums1, int $start1, array $nums2, int $start2, int $k): int
    {
        $n1 = count($nums1);
        $n2 = count($nums2);
        if ($start1 === $n1) {
            return $nums2[$start2 + $k - 1];
        }
        if ($start2 === $n2) {
            return $nums1[$start1 + $k - 1];
        }
        if ($k === 1) {
            return min($nums1[$start1], $nums2[$start2]);
        }
        $half = floor($k / 2);
        $i = min($n1 - 1, $start1 + $half - 1);
        $j = min($n2 - 1, $start2 + $half - 1);
        if ($nums1[$i] < $nums2[$j]) {
            // 排除 nums1[start1..i] 共 i-start1+1 个元素
            return $this->getKthElement($nums1, $i + 1, $nums2, $start2, $k - ($i - $start1 + 1));
        } else {
            // 排除 nums2[start2..j] 共 j-start2+1 个元素
            return $this->getKthElement($nums1, $start1, $nums2, $j + 1, $k - ($j - $start2 + 1));
        }
    }
}
// https://leetcode.cn/submissions/detail/382835078/
```

## 5. 最长回文子串

<https://leetcode.cn/problems/longest-palindromic-substring/>

```php
<?php

class Solution
{
    /**
     * @param string $s
     * @param int|null $i
     * @param int|null $j
     * @return string
     */
    function longestPalindrome(string $s, int $i = null, int $j = null): string
    {
        // 子问题：返回字符串 s 中以 s[i] 和 s[j] 为中心的最长回文子串
        if (!is_null($i) && !is_null($j)) {
            while ($i >= 0 && $j < strlen($s) && $s[$i] === $s[$j]) {
                --$i;
                ++$j;
            }
            return substr($s, $i + 1, $j - $i - 1);
        }
        // 原问题：返回字符串 s 的最长回文子串
        if (is_null($i) && is_null($j)) {
            $ans = "";
            for ($k = 0; $k < strlen($s); ++$k) {
                $s1 = $this->longestPalindrome($s, $k, $k);
                if (strlen($s1) > strlen($ans)) {
                    $ans = $s1;
                }
                $s2 = $this->longestPalindrome($s, $k, $k + 1);
                if (strlen($s2) > strlen($ans)) {
                    $ans = $s2;
                }
            }
            return $ans;
        }
        return "";
    }
}
// https://leetcode.cn/submissions/detail/383264536/
```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```php
// TODO
```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $height
     * @return Integer
     */
    function maxArea(array $height): int
    {
        $ans = 0;
        $i = 0;
        $j = count($height) - 1;
        while ($i < $j) {
            $area = min($height[$i], $height[$j]) * ($j - $i);
            $ans = max($ans, $area);
            if ($height[$i] < $height[$j]) {
                ++$i;
            } else {
                --$j;
            }
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/382777174/
```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```php
<?php

class Solution
{
    /**
     * @param string[] $strs
     * @param int|null $lo
     * @param int|null $hi
     * @return string
     */
    function longestCommonPrefix(array $strs, int $lo = null, int $hi = null): string
    {
        if (is_null($lo) && is_null($hi)) {
            return $this->longestCommonPrefix($strs, 0, count($strs) - 1);
        }
        if (!is_null($lo) && !is_null($hi)) {
            if ($lo === $hi) {
                return $strs[$lo];
            }
            $mid = $lo + floor(($hi - $lo) / 2);
            $left = $this->longestCommonPrefix($strs, $lo, $mid);
            $right = $this->longestCommonPrefix($strs, $mid + 1, $hi);
            return $this->longestCommonPrefixTwo($left, $right);
        }
        return "";
    }

    /**
     * @param string $s1
     * @param string $s2
     * @return string
     */
    private function longestCommonPrefixTwo(string $s1, string $s2): string
    {
        $n = min(strlen($s1), strlen($s2));
        $i = 0;
        while ($i < $n && $s1[$i] === $s2[$i]) {
            ++$i;
        }
        return substr($s1, 0, $i);
    }
}
// https://leetcode.cn/submissions/detail/383386400/
```

## 15. 三数之和

<https://leetcode-cn.com/problems/3sum/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @return Integer[][]
     */
    function threeSum(array $nums): array
    {
        sort($nums);
        return $this->kSum(3, $nums, 0, count($nums) - 1, 0);
    }

    /**
     * 返回升序子数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
     *
     * @param Integer $k
     * @param Integer[] $nums
     * @param Integer $lo
     * @param Integer $hi
     * @param Integer $target
     * @return Integer[][]
     */
    function kSum(int $k, array $nums, int $lo, int $hi, int $target): array
    {
        if ($hi - $lo + 1 < $k) {
            return [];
        }
        if ($k === 2) {
            return $this->twoSum($nums, $lo, $hi, $target);
        }
        $res = [];
        $i = $lo;
        while ($i <= $hi) {
            $curNum = $nums[$i];
            $sp = $this->kSum($k - 1, $nums, $i + 1, $hi, $target - $curNum);
            foreach ($sp as $x) {
                $x[] = $curNum;
                $res[] = $x;
            }
            while (++$i <= $hi && $nums[$i] === $curNum) {
            }
        }
        return $res;
    }

    /**
     * 返回升序子数组 $nums[$lo..$hi] 中所有和为 $target 且不重复的二元组
     *
     * @param Integer[] $nums
     * @param Integer $lo
     * @param Integer $hi
     * @param Integer $target
     * @return Integer[][]
     */
    function twoSum(array $nums, int $lo, int $hi, int $target): array
    {
        $res = [];
        while ($lo < $hi) {
            $first = $nums[$lo];
            $second = $nums[$hi];
            $sum = $first + $second;
            if ($sum < $target) {
                while (++$lo < $hi && $nums[$lo] === $first) {
                }
            } else if ($sum > $target) {
                while ($lo < --$hi && $nums[$hi] === $second) {
                }
            } else {
                $res[] = [$first, $second];
                while (++$lo < $hi && $nums[$lo] === $first) {
                }
                while ($lo < --$hi && $nums[$hi] === $second) {
                }
            }
        }
        return $res;
    }
}
// https://leetcode.cn/submissions/detail/382795216/
```

## 18. 四数之和

<https://leetcode.cn/problems/4sum/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @param Integer $target
     * @return Integer[][]
     */
    function fourSum(array $nums, int $target): array
    {
        sort($nums);
        return $this->kSum(4, $nums, 0, count($nums) - 1, $target);
    }

    /**
     * 返回升序子数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
     *
     * @param Integer $k
     * @param Integer[] $nums
     * @param Integer $lo
     * @param Integer $hi
     * @param Integer $target
     * @return Integer[][]
     */
    function kSum(int $k, array $nums, int $lo, int $hi, int $target): array
    {
        if ($hi - $lo + 1 < $k) {
            return [];
        }
        if ($k === 2) {
            return $this->twoSum($nums, $lo, $hi, $target);
        }
        $res = [];
        $i = $lo;
        while ($i <= $hi) {
            $curNum = $nums[$i];
            $sp = $this->kSum($k - 1, $nums, $i + 1, $hi, $target - $curNum);
            foreach ($sp as $x) {
                $x[] = $curNum;
                $res[] = $x;
            }
            while (++$i <= $hi && $nums[$i] === $curNum) {
            }
        }
        return $res;
    }

    /**
     * 返回升序子数组 $nums[$lo..$hi] 中所有和为 $target 且不重复的二元组
     *
     * @param Integer[] $nums
     * @param Integer $lo
     * @param Integer $hi
     * @param Integer $target
     * @return Integer[][]
     */
    function twoSum(array $nums, int $lo, int $hi, int $target): array
    {
        $res = [];
        while ($lo < $hi) {
            $first = $nums[$lo];
            $second = $nums[$hi];
            $sum = $first + $second;
            if ($sum < $target) {
                while (++$lo < $hi && $nums[$lo] === $first) {
                }
            } else if ($sum > $target) {
                while ($lo < --$hi && $nums[$hi] === $second) {
                }
            } else {
                $res[] = [$first, $second];
                while (++$lo < $hi && $nums[$lo] === $first) {
                }
                while ($lo < --$hi && $nums[$hi] === $second) {
                }
            }
        }
        return $res;
    }
}
// https://leetcode.cn/submissions/detail/382793511/
```

## 19. 删除链表的倒数第 N 个结点

<https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/>

```php
<?php

class Solution
{
    /**
     * @param ListNode $head
     * @param Integer $n
     * @return ListNode|null
     */
    function removeNthFromEnd(ListNode $head, int $n): ?ListNode
    {
        $dummyHead = new ListNode(-1, $head);
        $slow = $dummyHead;
        $fast = $dummyHead;
        for ($i = 1; $i <= $n; ++$i) {
            $fast = $fast->next;
        }
        while ($fast !== null && $fast->next !== null) {
            $slow = $slow->next;
            $fast = $fast->next;
        }
        $delNode = $slow->next;
        if ($delNode === $head) { // 删除的是头结点
            $head = $head->next;
        } else {
            $slow->next = $delNode->next;
        }
        return $head;
    }
}
// https://leetcode.cn/submissions/detail/382545635/
```

## 20. 有效的括号

<https://leetcode-cn.com/problems/valid-parentheses/>

```php
<?php

class Solution
{
    /**
     * @param string $s
     * @return bool
     */
    function isValid(string $s): bool
    {
        $n = strlen($s);
        if ($n % 2 == 1) {
            return false;
        }
        $stack = new SplStack();
        for ($i = 0; $i < $n; ++$i) {
            $ch = $s[$i];
            switch ($ch) {
                case '(':
                {
                    $stack->push(')');
                    break;
                }
                case '[':
                {
                    $stack->push(']');
                    break;
                }
                case '{':
                {
                    $stack->push('}');
                    break;
                }
                default:
                {
                    if ($stack->isEmpty() || $stack->top() !== $ch) {
                        return false;
                    }
                    $stack->pop();
                    break;
                }
            }
        }
        return $stack->isEmpty();
    }
}
// https://leetcode.cn/submissions/detail/383273552/
```

```php
<?php

class Solution
{
    /**
     * @param string $s
     * @return bool
     */
    function isValid(string $s): bool
    {
        $n = strlen($s);
        if ($n % 2 === 1) {
            return false;
        }
        $stack = [];
        for ($i = 0; $i < $n; ++$i) {
            $ch = $s[$i];
            switch ($ch) {
                case '(':
                {
                    $stack[] = ')';
                    break;
                }
                case '[':
                {
                    $stack[] = ']';
                    break;
                }
                case '{':
                {
                    $stack[] = '}';
                    break;
                }
                default:
                {
                    if (count($stack) === 0 || array_pop($stack) !== $ch) {
                        return false;
                    }
                    break;
                }
            }
        }
        return count($stack) === 0;
    }
}
// https://leetcode.cn/submissions/detail/383278174/
```

## 21. 合并两个有序链表

<https://leetcode-cn.com/problems/merge-two-sorted-lists/>

```php
<?php

class Solution
{
    /**
     * @param ListNode|null $list1
     * @param ListNode|null $list2
     * @return ListNode|null
     */
    function mergeTwoLists(?ListNode $list1, ?ListNode $list2): ?ListNode
    {
        $dummyHead = new ListNode();
        $ptr = $dummyHead;
        while ($list1 !== null && $list2 !== null) {
            if ($list1->val < $list2->val) {
                $ptr->next = $list1;
                $list1 = $list1->next;
            } else {
                $ptr->next = $list2;
                $list2 = $list2->next;
            }
            $ptr = $ptr->next;
        }
        $ptr->next = $list1 ?? $list2;
        return $dummyHead->next;
    }
}
// https://leetcode.cn/submissions/detail/382721812/
```

## 22. 括号生成

<https://leetcode.cn/problems/generate-parentheses/>

```php
<?php

class Solution
{
    private int $n = 0;
    private int $left = 0;    // 已使用的『左括号』数量
    private int $right = 0;   // 已使用的『右括号』数量
    private array $path = []; // 取 '(', ')' 为元素
    private array $ans = [];

    /**
     * @param int $n
     * @return string[]
     */
    function generateParenthesis(int $n): array
    {
        $this->n = $n;
        $this->backtrack();
        return $this->ans;
    }

    /**
     * @return void
     */
    private function backtrack(): void
    {
        // 对于一个「合法」的括号字符串组合 p，必然对于任何 0 <= i < len(p) 都有：
        // 子串 p[0..i] 中左括号的数量都大于或等于右括号的数量
        if ($this->left < $this->right || $this->left > $this->n) {
            return;
        }
        // 一个「合法」括号组合的左括号数量一定等于右括号数量
        if ($this->left === $this->n && $this->right === $this->n) {
            $this->ans[] = join($this->path);
            return;
        }
        // edge = 取 '(', ')' 为值
        // 使用『左括号』
        $this->path[] = '(';
        ++$this->left;
        $this->backtrack();
        array_pop($this->path);
        --$this->left;
        // 使用『右括号』
        $this->path[] = ')';
        ++$this->right;
        $this->backtrack();
        array_pop($this->path);
        --$this->right;
    }
}
// https://leetcode.cn/submissions/detail/383300726/
```

## 23. 合并 K 个升序链表

<https://leetcode-cn.com/problems/merge-k-sorted-lists/>

```php
<?php

class Solution
{
    /**
     * @param ListNode[] $lists
     * @param int|null $lo
     * @param int|null $hi
     * @return ListNode|null
     */
    function mergeKLists(array $lists, int $lo = null, int $hi = null): ?ListNode
    {
        if (is_null($lo) && is_null($hi)) {
            return $this->mergeKLists($lists, 0, count($lists) - 1);
        }
        if ($lo > $hi) {
            return null;
        }
        if ($lo == $hi) {
            return $lists[$lo];
        }
        $mid = $lo + floor(($hi - $lo) / 2);
        $left = $this->mergeKLists($lists, $lo, $mid);
        $right = $this->mergeKLists($lists, $mid + 1, $hi);
        return $this->mergeTwoLists($left, $right);
    }

    /**
     * @param ListNode|null $list1
     * @param ListNode|null $list2
     * @return ListNode|null
     */
    function mergeTwoLists(?ListNode $list1, ?ListNode $list2): ?ListNode
    {
        $dummyHead = new ListNode();
        $ptr = $dummyHead;
        while ($list1 !== null && $list2 !== null) {
            if ($list1->val < $list2->val) {
                $ptr->next = $list1;
                $list1 = $list1->next;
            } else {
                $ptr->next = $list2;
                $list2 = $list2->next;
            }
            $ptr = $ptr->next;
        }
        $ptr->next = $list1 ?? $list2;
        return $dummyHead->next;
    }
}
// https://leetcode.cn/submissions/detail/382726233/
```

## 24. 两两交换链表中的节点

<https://leetcode-cn.com/problems/swap-nodes-in-pairs/>

```php
<?php

class Solution
{
    /**
     * @param ListNode|null $head
     * @return ListNode|null
     */
    function swapPairs(?ListNode $head): ?ListNode
    {
        if ($head === null || $head->next === null) {
            return $head;
        }
        $x = $head;
        $y = $head->next;
        $z = $head->next->next;
        $y->next = $x;
        $x->next = $this->swapPairs($z);
        return $y;
    }
}
// https://leetcode.cn/submissions/detail/382713313/
```

## 25. K 个一组翻转链表

<https://leetcode.cn/problems/reverse-nodes-in-k-group/>

```php
<?php

class Solution
{
    /**
     * @param ListNode|null $head
     * @param Integer $k
     * @return ListNode|null
     */
    function reverseKGroup(?ListNode $head, int $k): ?ListNode
    {
        if ($head === null || $head->next === null) {
            return $head;
        }
        $ptr = $head;
        for ($i = 1; $i <= $k - 1; ++$i) {
            $ptr = $ptr->next;
            if ($ptr === null) {
                return $head;
            }
        }
        $nextGroup = $ptr->next;
        $ptr->next = null;
        $reverseHead = $this->reverseList($head);
        $head->next = $this->reverseKGroup($nextGroup, $k);
        return $reverseHead;
    }

    /**
     * @param ListNode|null $head
     * @return ListNode|null
     */
    function reverseList(?ListNode $head): ?ListNode
    {
        $reverseHead = null;
        while ($head !== null) {
            $nextHead = $head->next;
            $head->next = $reverseHead;
            $reverseHead = $head;
            $head = $nextHead;
        }
        return $reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/382711074/
```

## 26. 删除有序数组中的重复项

<https://leetcode.cn/problems/remove-duplicates-from-sorted-array/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @return Integer
     */
    function removeDuplicates(array &$nums): int
    {
        $n = count($nums);
        // [0..i-1] 不重复元素区间
        // [i..j-1] 重复元素区间
        // [j..n-1] 扫描区间
        $i = 0;
        $j = 0;
        while ($j < $n) {
            while ($j + 1 < $n && $nums[$j] === $nums[$j + 1]) {
                ++$j;
            }
            [$nums[$i], $nums[$j]] = [$nums[$j], $nums[$i]];
            ++$i;
            ++$j;
        }
        return $i;
    }
}
// https://leetcode.cn/submissions/detail/382532833/
```

## 27. 移除元素

<https://leetcode.cn/problems/remove-element/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @param Integer $val
     * @return Integer
     */
    function removeElement(array &$nums, int $val): int
    {
        // nums[0..i-1]   != val
        // nums[i..j]     Scanning
        // nums[j+1..n-1] == val
        $i = 0;
        $j = count($nums) - 1;
        while ($i <= $j) {
            while ($i <= $j && $nums[$i] != $val) {
                ++$i;
            }
            while ($i <= $j && $nums[$j] == $val) {
                --$j;
            }
            if ($i <= $j) {
                [$nums[$i], $nums[$j]] = [$nums[$j], $nums[$j]];
                ++$i;
                --$j;
            }
        }
        return $i;
    }
}
// https://leetcode.cn/submissions/detail/382477145/
```

## 28. 实现 strStr()

<https://leetcode.cn/problems/implement-strstr/>

```php
<?php

class KMP
{
    private int $m;
    private array $dfa;

    /**
     * @param string $pat
     */
    public function __construct(string $pat)
    {
        $this->m = strlen($pat);
        $this->dfa = array_fill(0, 256, array_fill(0, $this->m, 0));
        $this->dfa[ord($pat[0])][0] = 1;
        for ($x = 0, $j = 1; $j < $this->m; ++$j) {
            for ($c = 0; $c < 256; ++$c) {
                $this->dfa[$c][$j] = $this->dfa[$c][$x];
            }
            $this->dfa[ord($pat[$j])][$j] = $j + 1;
            $x = $this->dfa[ord($pat[$j])][$x];
        }
    }

    /**
     * @param string $txt
     * @return int
     */
    public function search(string $txt): int
    {
        $n = strlen($txt);
        for ($i = 0, $j = 0; $i < $n && $j < $this->m; ++$i) {
            $j = $this->dfa[ord($txt[$i])][$j];
        }
        if ($j === $this->m) {
            return $i - $this->m;
        }
        return -1;
    }
}

class Solution
{
    /**
     * @param string $haystack
     * @param string $needle
     * @return int
     */
    function strStr(string $haystack, string $needle): int
    {
        $kmp = new KMP($needle);
        return $kmp->search($haystack);
    }
}
// https://leetcode.cn/submissions/detail/384091503/
```

```php
<?php

class BoyerMoore
{
    private string $pat;
    private array $right;

    /**
     * @param string $pat
     */
    public function __construct(string $pat)
    {
        $this->pat = $pat;
        $this->right = array_fill(0, 256, -1);
        for ($j = 0; $j < strlen($pat); ++$j) {
            $this->right[ord($pat[$j])] = $j;
        }
    }

    /**
     * @param string $txt
     * @return int
     */
    public function search(string $txt): int
    {
        $n = strlen($txt);
        $m = strlen($this->pat);
        for ($i = 0; $i <= $n - $m; $i += $skip) {
            $skip = 0;
            for ($j = $m - 1; $j >= 0; $j--) {
                if ($this->pat[$j] !== $txt[$i + $j]) {
                    $skip = max(1, $j - $this->right[ord($txt[$i + $j])]);
                    break;
                }
            }
            if ($skip === 0) {
                return $i;
            }
        }
        return -1;
    }
}

class Solution
{
    /**
     * @param string $haystack
     * @param string $needle
     * @return int
     */
    function strStr(string $haystack, string $needle): int
    {
        $bm = new BoyerMoore($needle);
        return $bm->search($haystack);
    }
}
// https://leetcode.cn/submissions/detail/384089431/
```

## 33. 搜索旋转排序数组

<https://leetcode.cn/problems/search-in-rotated-sorted-array/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @param Integer $target
     * @return Integer
     */
    function search(array $nums, int $target): int
    {
        $lo = 0;
        $hi = count($nums) - 1;
        while ($lo <= $hi) {
            $mid = $lo + floor(($hi - $lo) / 2);
            if ($nums[$mid] === $target) {
                return $mid;
            }
            // 当 lo = hi 时，nums[lo] = nums[mid] = nums[hi]，
            // 此时 nums[mid] < target <= nums[hi] 不成立
            if ($nums[$mid] <= $nums[$hi]) {
                if ($nums[$mid] < $target && $target <= $nums[$hi]) {
                    $lo = $mid + 1;
                } else {
                    $hi = $mid - 1;
                }
            } else {
                if ($nums[$lo] <= $target && $target < $nums[$mid]) {
                    $hi = $mid - 1;
                } else {
                    $lo = $mid + 1;
                }
            }
        }
        return -1;
    }
}
// https://leetcode.cn/submissions/detail/382821766/
```

## 34. 在排序数组中查找元素的第一个和最后一个位置

<https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @param Integer $target
     * @return Integer[]
     */
    function searchRange(array $nums, int $target): array
    {
        return [$this->search($nums, $target, true), $this->search($nums, $target, false)];
    }

    /**
     * @param Integer[] $nums
     * @param Integer $target
     * @param Integer $lower
     * @return Integer
     */
    function search(array $nums, int $target, int $lower): int
    {
        $res = -1;
        $lo = 0;
        $hi = count($nums) - 1;
        while ($lo <= $hi) {
            $mid = $lo + floor(($hi - $lo) / 2);
            if ($target < $nums[$mid]) {
                $hi = $mid - 1;
            } else if ($nums[$mid] < $target) {
                $lo = $mid + 1;
            } else {
                $res = $mid;
                if ($lower) {
                    $hi = $mid - 1;
                } else {
                    $lo = $mid + 1;
                }
            }
        }
        return $res;
    }
}
// https://leetcode.cn/submissions/detail/382830812/
```

## 37. 解数独

<https://leetcode.cn/problems/sudoku-solver/>

```php
<?php

class Solution
{
    /**
     * @param string[][] $board
     * @return void
     */
    function solveSudoku(array &$board): void
    {
        $this->backtrack($board, 0, -1);
    }

    /**
     * 遍历『决策森林』
     * tree  = row
     * level = (row, col)
     *
     * @param string[][] $board
     * @param int $row
     * @param int $col
     * @return bool
     */
    private function backtrack(array &$board, int $row, int $col): bool
    {
        $n = count($board);
        $res = false;
        if ($row === $n - 1 && $col === $n - 1) {
            $res = true;
        } else if ($row < $n - 1 && $col === $n - 1) {
            // 遍历下一棵『决策树』
            $res = $this->backtrack($board, $row + 1, -1);
        } else if ($board[$row][$col + 1] !== '.') {
            $res = $this->backtrack($board, $row, $col + 1);
        } else {
            // edge = ['1'..'9']
            $digits = "123456789";
            for ($i = 0; $i < strlen($digits); ++$i) {
                $ch = $digits[$i];
                if ($this->isValid($board, $row, $col + 1, $ch)) {
                    $board[$row][$col + 1] = $ch;
                    $res = $this->backtrack($board, $row, $col + 1);
                    if ($res) {
                        break;
                    }
                    $board[$row][$col + 1] = '.';
                }
            }
        }
        return $res;
    }

    /**
     * board[row][col] 填入数字 ch 是否有效
     *
     * @param string[][] $board
     * @param int $row
     * @param int $col
     * @param string $ch
     * @return bool
     */
    private function isValid(array $board, int $row, int $col, string $ch): bool
    {
        for ($i = 0; $i < count($board); ++$i) {
            // 同一行
            if ($board[$row][$i] === $ch) {
                return false;
            }
            // 同一列
            if ($board[$i][$col] === $ch) {
                return false;
            }
            // 同九宫
            if ($board[floor($row / 3) * 3 + floor($i / 3)][floor($col / 3) * 3 + $i % 3] === $ch) {
                return false;
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/383750148/
```

## 39. 组合总和

<https://leetcode.cn/problems/combination-sum/>

```php
<?php

class Solution
{
    private int $pathSum = 0;
    private array $path = []; // 取 nums[edge] 为元素
    private array $ans = [];

    /**
     * @param int[] $nums
     * @param int $target
     * @return int[][]
     */
    function combinationSum(array $nums, int $target): array
    {
        $this->backtrack($nums, $target, -1);
        return $this->ans;
    }

    /**
     * @param int[] $nums
     * @param int $target
     * @param int $edge 取数组 nums 的索引为值
     * @return void
     */
    private function backtrack(array $nums, int $target, int $edge): void
    {
        if ($this->pathSum === $target) {
            $this->ans[] = [...$this->path];
            return;
        }
        if ($edge === -1) {
            $edge = 0;
        }
        // 避免重复，从 edge 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while ($edge < count($nums)) {
            $x = $nums[$edge];
            if ($this->pathSum + $x <= $target) {
                $this->pathSum += $x;
                $this->path[] = $x;
                $this->backtrack($nums, $target, $edge);
                $this->pathSum -= $x;
                array_pop($this->path);
            }
            ++$edge;
        }
    }
}
// https://leetcode.cn/submissions/detail/383696770/
```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```php
<?php

class Solution
{
    private int $pathSum = 0;
    private array $path = []; // 取 nums[edge] 为元素
    private array $ans = [];

    /**
     * @param int[] $nums
     * @param int $target
     * @return int[][]
     */
    function combinationSum2(array $nums, int $target): array
    {
        sort($nums);
        $this->backtrack($nums, $target, -1);
        return $this->ans;
    }

    /**
     * @param int[] $nums
     * @param int $target
     * @param int $edge 取数组 nums 的索引为值
     * @return void
     */
    private function backtrack(array $nums, int $target, int $edge): void
    {
        if ($this->pathSum === $target) {
            $this->ans[] = [...$this->path];
            return;
        }
        $prev = null;
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++$edge < count($nums)) {
            $x = $nums[$edge];
            if ($x !== $prev && $this->pathSum + $x <= $target) {
                $prev = $x;
                $this->pathSum += $x;
                $this->path[] = $x;
                $this->backtrack($nums, $target, $edge);
                $this->pathSum -= $x;
                array_pop($this->path);
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/383698456/
```

## 42. 接雨水

<https://leetcode.cn/problems/trapping-rain-water/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $height
     * @return Integer
     */
    function trap(array $height): int
    {
        $n = count($height);
        // leftMax[i] = max(height[0..i])
        $leftMax = [...$height];
        for ($i = 1; $i <= $n - 1; ++$i) {
            $leftMax[$i] = max($height[$i], $leftMax[$i - 1]);
        }
        // rightMax[i] = max(height[i..n-1])
        $rightMax = [...$height];
        for ($i = $n - 2; $i >= 0; --$i) {
            $rightMax[$i] = max($height[$i], $rightMax[$i + 1]);
        }
        $sum = 0;
        for ($i = 0; $i < $n; ++$i) {
            $sum += min($leftMax[$i], $rightMax[$i]) - $height[$i];
        }
        return $sum;
    }
}
// https://leetcode.cn/submissions/detail/382815997/
```

## 46. 全排列

<https://leetcode.cn/problems/permutations/>

```php
<?php

class Solution
{
    private array $marked;
    private array $path = []; // 取 nums[$edge] 为元素
    private array $ans = [];

    /**
     * @param int[] $nums
     * @return int[][]
     */
    function permute(array $nums): array
    {
        $this->marked = array_fill(0, count($nums), false);
        $this->backtrack($nums);
        return $this->ans;
    }

    /**
     * @param int[] $nums
     * @return void
     */
    private function backtrack(array $nums): void
    {
        $n = count($nums);
        if (count($this->path) === $n) {
            $this->ans[] = [...$this->path];
            return;
        }
        // edge = 取数组 nums 的索引为值
        for ($edge = 0; $edge < $n; ++$edge) {
            if (!$this->marked[$edge]) {
                $this->marked[$edge] = true;
                $this->path[] = $nums[$edge];
                $this->backtrack($nums);
                $this->marked[$edge] = false;
                array_pop($this->path);
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/383713111/
```

## 47. 全排列 II

<https://leetcode.cn/problems/permutations-ii/>

```php
<?php

class Solution
{
    private array $marked;
    private array $path = []; // 取 nums[$edge] 为元素
    private array $ans = [];

    /**
     * @param int[] $nums
     * @return int[][]
     */
    function permuteUnique(array $nums): array
    {
        sort($nums);
        $this->marked = array_fill(0, count($nums), false);
        $this->backtrack($nums);
        return $this->ans;
    }

    /**
     * @param int[] $nums
     * @return void
     */
    private function backtrack(array $nums): void
    {
        $n = count($nums);
        if (count($this->path) === $n) {
            $this->ans[] = [...$this->path];
            return;
        }
        $prev = null;
        // edge = 取数组 nums 的索引为值
        for ($edge = 0; $edge < $n; ++$edge) {
            $x = $nums[$edge];
            if (!$this->marked[$edge] && $x !== $prev) {
                $prev = $x;
                $this->marked[$edge] = true;
                $this->path[] = $x;
                $this->backtrack($nums);
                $this->marked[$edge] = false;
                array_pop($this->path);
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/383713768/
```

## 51. N 皇后

<https://leetcode.cn/problems/n-queens/>

```php
<?php

class Solution
{
    private array $ans = [];

    /**
     * @param int $n
     * @return string[][]
     */
    function solveNQueens(int $n): array
    {
        $board = array_fill(0, $n, array_fill(0, $n, '.'));
        $this->backtrack($board, -1);
        return $this->ans;
    }

    /**
     * 回溯决策树
     * level = row
     *
     * @param string[][] $board
     * @param int $row
     * @return void
     */
    function backtrack(array &$board, int $row): void
    {
        $n = count($board);
        if ($row === $n - 1) {
            $this->ans[] = array_map(fn($item) => join("", $item), $board);
            // $this->ans[] = array_reduce($board, fn($carry, $item) => [...$carry, join("", $item)], []);
            return;
        }
        // edge = col
        for ($col = 0; $col < $n; ++$col) {
            if ($this->isValid($board, $row + 1, $col)) {
                $board[$row + 1][$col] = 'Q';
                $this->backtrack($board, $row + 1);
                $board[$row + 1][$col] = '.';
            }
        }
    }

    /**
     * board[row][col] 放置 Q 是否有效
     *
     * @param string[][] $board
     * @param int $row
     * @param int $col
     * @return bool
     */
    private function isValid(array $board, int $row, int $col): bool
    {
        // 同一列
        for ($r = $row - 1; $r >= 0; --$r) {
            if ($board[$r][$col] === 'Q') {
                return false;
            }
        }
        // 右斜线
        for ($r = $row - 1, $c = $col + 1; $r >= 0 && $c < count($board); --$r, ++$c) {
            if ($board[$r][$c] === 'Q') {
                return false;
            }
        }
        // 左斜线
        for ($r = $row - 1, $c = $col - 1; $r >= 0 && $c >= 0; --$r, --$c) {
            if ($board[$r][$c] === 'Q') {
                return false;
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/383766117/
```

## 52. N 皇后 II

<https://leetcode.cn/problems/n-queens-ii/>

```php
<?php

class Solution
{
    private int $ans = 0;

    /**
     * @param int $n
     * @return int
     */
    function totalNQueens(int $n): int
    {
        $board = array_fill(0, $n, array_fill(0, $n, '.'));
        $this->backtrack($board, -1);
        return $this->ans;
    }

    /**
     * 回溯决策树
     * level = row
     *
     * @param string[][] $board
     * @param int $row
     * @return void
     */
    function backtrack(array &$board, int $row): void
    {
        $n = count($board);
        if ($row === $n - 1) {
            ++$this->ans;
            return;
        }
        // edge = col
        for ($col = 0; $col < $n; ++$col) {
            if ($this->isValid($board, $row + 1, $col)) {
                $board[$row + 1][$col] = 'Q';
                $this->backtrack($board, $row + 1);
                $board[$row + 1][$col] = '.';
            }
        }
    }

    /**
     * board[row][col] 放置 Q 是否有效
     *
     * @param string[][] $board
     * @param int $row
     * @param int $col
     * @return bool
     */
    private function isValid(array $board, int $row, int $col): bool
    {
        // 同一列
        for ($r = $row - 1; $r >= 0; --$r) {
            if ($board[$r][$col] === 'Q') {
                return false;
            }
        }
        // 右斜线
        for ($r = $row - 1, $c = $col + 1; $r >= 0 && $c < count($board); --$r, ++$c) {
            if ($board[$r][$c] === 'Q') {
                return false;
            }
        }
        // 左斜线
        for ($r = $row - 1, $c = $col - 1; $r >= 0 && $c >= 0; --$r, --$c) {
            if ($board[$r][$c] === 'Q') {
                return false;
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/383767178/
```

## 53. 最大子数组和

<https://leetcode.cn/problems/maximum-subarray/>

```php
<?php

class Solution
{
    /**
     * @param int[] $nums
     * @return int
     */
    function maxSubArray(array $nums): int
    {
        // dp[i] = max({sum(subarray) | subarray 是任意以 nums[i] 结尾的子数组})
        $dp = [...$nums];
        $ans = $dp[0];
        for ($i = 1; $i < count($nums); ++$i) {
            $dp[$i] = max($nums[$i], $dp[$i - 1] + $nums[$i]);
            $ans = max($ans, $dp[$i]);
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/383552158/
```

## 56. 合并区间

<https://leetcode.cn/problems/merge-intervals/>

```php
<?php

class Solution
{
    /**
     * @param int[][] $intervals
     * @return int[][]
     */
    function merge(array $intervals): array
    {
        usort($intervals, fn($a, $b) => $a[0] === $b[0] ? $b[1] - $a[1] : $a[0] - $b[0]);
        $ans = [];
        [$mStart, $mEnd] = $intervals[0];
        for ($i = 1; $i < count($intervals); ++$i) {
            [$start, $end] = $intervals[$i];
            if ($start <= $mEnd) { // 重叠
                $mEnd = max($mEnd, $end);
            } else { // 不重叠
                $ans[] = [$mStart, $mEnd];
                $mStart = $start;
                $mEnd = $end;
            }
        }
        $ans[] = [$mStart, $mEnd];
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/383510402/
```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```php
<?php

class Solution
{
    private array $memo = [];

    /**
     * @param int[][] $grid
     * @param int|null $row
     * @param int|null $col
     * @return int|null
     */
    function minPathSum(array $grid, int $row = null, int $col = null): ?int
    {
        // 原问题
        if (is_null($row) && is_null($col)) {
            return $this->minPathSum($grid, count($grid) - 1, count($grid[0]) - 1);
        }
        // 子问题：从 grid[0][0] 到 grid[row][col] 的最小路径和
        if (!is_null($row) && !is_null($col)) {
            if ($row < 0 || $col < 0) {
                return PHP_INT_MAX;
            }
            if ($row === 0 && $col === 0) {
                return $grid[$row][$col];
            }
            if (is_null($this->memo[$row][$col])) {
                $sp1 = $this->minPathSum($grid, $row - 1, $col, $this->memo);
                $sp2 = $this->minPathSum($grid, $row, $col - 1, $this->memo);
                $this->memo[$row][$col] = min($sp1, $sp2) + $grid[$row][$col];
            }
            return $this->memo[$row][$col];
        }
        return null;
    }
}
// https://leetcode.cn/submissions/detail/383637348/
```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```php
<?php

class Solution
{
    /**
     * @param Integer $x
     * @return Integer
     */
    function mySqrt(int $x): int
    {
        if ($x === 0) {
            return 0;
        }
        $lo = 1;
        $hi = $x;
        while ($lo <= $hi) {
            $mid = $lo + floor(($hi - $lo) / 2);
            if ($mid <= $x / $mid && ($mid + 1) > $x / ($mid + 1)) {
                return $mid;
            }
            if ($mid <= $x / $mid) {
                $lo = $mid + 1;
            } else {
                $hi = $mid - 1;
            }
        }
        return -1;
    }
}
// https://leetcode.cn/submissions/detail/382831539/
```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```php
<?php

class Solution
{
    /**
     * @param int $n
     * @return int
     */
    function climbStairs(int $n): int
    {
        if ($n === 1) {
            return 1;
        }
        if ($n === 2) {
            return 2;
        }
        // dp[i] = 楼梯有 i 阶时，有几种不同的方法
        $dp = [];
        $dp[1] = 1;
        $dp[2] = 2;
        for ($i = 3; $i <= $n; $i++) {
            $dp[$i] = $dp[$i - 1] + $dp[$i - 2];
        }
        return $dp[$n];
    }
}
// https://leetcode.cn/submissions/detail/383631094/
```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```php
<?php

class Solution
{
    private array $memo = [];

    /**
     * @param string $s1
     * @param string $s2
     * @param int|null $i
     * @param int|null $j
     * @return int|null
     */
    function minDistance(string $s1, string $s2, int $i = null, int $j = null): ?int
    {
        // 原问题
        if (is_null($i) && is_null($j)) {
            return $this->minDistance($s1, $s2, strlen($s1) - 1, strlen($s2) - 1);
        }
        // 子问题：子串 s1[0..i] s2[0..j] 的最小编辑距离
        if (!is_null($i) && !is_null($j)) {
            // 插入 s2[0..j] 到 s1
            // s1""
            // s2[0..j]
            if ($i < 0) {
                return $j + 1;
            }
            // 删除 s1[0..i]
            // s1[0..i]
            // s2""
            if ($j < 0) {
                return $i + 1;
            }
            if (is_null($this->memo[$i][$j])) {
                if ($s1[$i] === $s2[$j]) {
                    // s1[0..i-1][i]
                    // s2[0..j-1][j]
                    $this->memo[$i][$j] = $this->minDistance($s1, $s2, $i - 1, $j - 1);
                } else {
                    // 替换 s1[i] 为 s2[j]
                    // s1[0..i-1][i]
                    // s2[0..j-1][j]
                    $sp1 = $this->minDistance($s1, $s2, $i - 1, $j - 1) + 1;
                    // 插入 s2[j] 到 s1
                    // s1[0..i]
                    // s2[0..j-1][j]
                    $sp2 = $this->minDistance($s1, $s2, $i, $j - 1) + 1;
                    // 删除 s1[i]
                    // s1[0..i-1][i]
                    // s2[0..j]
                    $sp3 = $this->minDistance($s1, $s2, $i - 1, $j) + 1;
                    $this->memo[$i][$j] = min($sp1, $sp2, $sp3);
                }
            }
            return $this->memo[$i][$j];
        }
        return null;
    }
}
// https://leetcode.cn/submissions/detail/383615597/
```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```php
<?php

class Solution
{
    /**
     * @param int[] $nums
     * @return void
     */
    function sortColors(array &$nums): void
    {
        $v = 1;
        $lt = 0;
        $gt = count($nums) - 1;
        $i = 0;
        while ($i <= $gt) {
            $x = $nums[$i];
            if ($x < $v) {
                $this->swap($nums, $lt++, $i++);
            } else if ($x > $v) {
                $this->swap($nums, $i, $gt--);
            } else {
                ++$i;
            }
        }
    }

    /**
     * @param int[] $nums
     * @param int $i
     * @param int $j
     * @return void
     */
    private function swap(array &$nums, int $i, int $j): void
    {
        [$nums[$i], $nums[$j]] = [$nums[$j], $nums[$i]];
    }
}
// https://leetcode.cn/submissions/detail/382900446/
```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```php
<?php

class Solution
{
    /**
     * @param string $s
     * @param string $t
     * @return string
     */
    function minWindow(string $s, string $t): string
    {
        $need = [];
        for ($i = 0; $i < strlen($t); ++$i) {
            $ch = $t[$i];
            $need[$ch] = ($need[$ch] ?? 0) + 1;
        }
        $win = [];
        $valid = 0;
        $start = 0;
        $len = PHP_INT_MAX;
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        $left = 0;
        $right = 0;
        while ($right < strlen($s)) {
            $ch = $s[$right++];
            if (array_key_exists($ch, $need)) {
                $win[$ch] = ($win[$ch] ?? 0) + 1;
                if ($win[$ch] === $need[$ch]) {
                    ++$valid;
                }
            }
            if ($valid === count($need)) {
                while ($left < $right) {
                    $del = $s[$left];
                    if (array_key_exists($del, $win) && $win[$del] === $need[$del]) {
                        break;
                    }
                    if (array_key_exists($del, $win)) {
                        --$win[$del];
                    }
                    ++$left;
                }
                if ($right - $left < $len) {
                    $start = $left;
                    $len = $right - $left;
                }
            }
        }
        return $len === PHP_INT_MAX ? "" : substr($s, $start, $len);
    }
}
// https://leetcode.cn/submissions/detail/383312320/
```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```php
<?php

class Solution
{
    private array $path = []; // 取 [1..n] 为元素
    private array $ans = [];

    /**
     * @param int $n
     * @param int $k
     * @return int[][]
     */
    function combine(int $n, int $k): array
    {
        $this->backtrack($n, $k, 0);
        return $this->ans;
    }

    /**
     * @param int $n
     * @param int $k
     * @param int $edge 取 [1..n] 为值
     * @return void
     */
    private function backtrack(int $n, int $k, int $edge): void
    {
        if (count($this->path) === $k) {
            $this->ans[] = [...$this->path];
            return;
        }
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++$edge <= $n) {
            $this->path[] = $edge;
            $this->backtrack($n, $k, $edge);
            array_pop($this->path);
        }
    }
}
// https://leetcode.cn/submissions/detail/383699244/
```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```php
<?php

class Solution
{
    private array $path = []; // 取 nums[edge] 为元素
    private array $ans = [];

    /**
     * @param int[] $nums
     * @return int[][]
     */
    function subsets(array $nums): array
    {
        $this->backtrack($nums, -1);
        return $this->ans;
    }

    /**
     * @param int[] $nums
     * @param int $edge 取数组 nums 的索引为值
     * @return void
     */
    private function backtrack(array $nums, int $edge): void
    {
        $this->ans[] = [...$this->path];
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++$edge < count($nums)) {
            $this->path[] = $nums[$edge];
            $this->backtrack($nums, $edge);
            array_pop($this->path);
        }
    }
}
// https://leetcode.cn/submissions/detail/383699723/
```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @param Integer $target
     * @return Boolean
     */
    function search(array $nums, int $target): bool
    {
        $lo = 0;
        $hi = count($nums) - 1;
        while ($lo <= $hi) {
            $mid = $lo + floor(($hi - $lo) / 2);
            if ($nums[$mid] === $target) {
                return true;
            }
            if ($nums[$lo] === $nums[$mid] && $nums[$mid] === $nums[$hi]) {
                ++$lo;
                --$hi;
            } else {
                if ($nums[$mid] <= $nums[$hi]) {
                    if ($nums[$mid] < $target && $target <= $nums[$hi]) {
                        $lo = $mid + 1;
                    } else {
                        $hi = $mid - 1;
                    }
                } else {
                    if ($nums[$lo] <= $target && $target < $nums[$mid]) {
                        $hi = $mid - 1;
                    } else {
                        $lo = $mid + 1;
                    }
                }
            }
        }
        return false;
    }
}
// https://leetcode.cn/submissions/detail/382823287/
```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```php
<?php

class Solution
{
    /**
     * @param ListNode|null $head
     * @return ListNode|null
     */
    function deleteDuplicates(?ListNode $head): ?ListNode
    {
        $ptr = $head;
        while ($ptr !== null && $ptr->next !== null) {
            if ($ptr->val === $ptr->next->val) {
                $ptr->next = $ptr->next->next;
            } else {
                $ptr = $ptr->next;
            }
        }
        return $head;
    }
}
// https://leetcode.cn/submissions/detail/382773452/
```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```php
<?php

class Solution
{
    /**
     * @param ListNode|null $head
     * @param Integer $x
     * @return ListNode|null
     */
    function partition(?ListNode $head, int $x): ?ListNode
    {
        $dummyLess = new ListNode();
        $ptrLess = $dummyLess;
        $dummyGreater = new ListNode();
        $ptrGreater = $dummyGreater;
        while ($head != null) {
            if ($head->val < $x) {
                $ptrLess->next = $head;
                $ptrLess = $ptrLess->next;
            } else {
                $ptrGreater->next = $head;
                $ptrGreater = $ptrGreater->next;
            }
            $head = $head->next;
        }
        $ptrLess->next = $dummyGreater->next;
        $ptrGreater->next = null;
        return $dummyLess->next;
    }
}
// https://leetcode.cn/submissions/detail/382832599/
```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```php
<?php

class Solution
{
    private array $path = []; // 取 nums[edge] 为元素
    private array $ans = [];

    /**
     * @param int[] $nums
     * @return int[][]
     */
    function subsetsWithDup(array $nums): array
    {
        sort($nums);
        $this->backtrack($nums, -1);
        return $this->ans;
    }

    /**
     * @param int[] $nums
     * @param int $edge 取数组 nums 的索引为值
     * @return void
     */
    private function backtrack(array $nums, int $edge): void
    {
        $this->ans[] = [...$this->path];
        $prev = null;
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++$edge < count($nums)) {
            $x = $nums[$edge];
            if ($x !== $prev) {
                $prev = $x;
                $this->path[] = $x;
                $this->backtrack($nums, $edge);
                array_pop($this->path);
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/383700153/
```

## 92. 反转链表 II

<https://leetcode-cn.com/problems/reverse-linked-list-ii/>

```php
<?php

class Solution
{
    /**
     * @param ListNode $head
     * @param Integer $left
     * @param Integer $right
     * @return ListNode
     */
    function reverseBetween(ListNode $head, int $left, int $right): ListNode
    {
        if ($left === 1) {
            return $this->reverseList($head, $right);
        }
        $ptr = $head;
        for ($i = 1; $i <= $left - 2; ++$i) {
            $ptr = $ptr->next;
        }
        $ptr->next = $this->reverseList($ptr->next, $right - $left + 1);
        return $head;
    }

    // 翻转链表的前 n 个节点，返回翻转后的头节点
    function reverseList(ListNode $head, int $n): ListNode
    {
        $reverseHead = null;
        $ptr = $head;
        while ($ptr !== null && $n > 0) {
            $nextHead = $ptr->next;
            $ptr->next = $reverseHead;
            $reverseHead = $ptr;
            $ptr = $nextHead;
            --$n;
        }
        $head->next = $ptr;
        return $reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/382706867/
```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```php
<?php

class Solution
{
    private array $ans = [];

    /**
     * @param TreeNode|null $root
     * @return int[]
     */
    function inorderTraversal(?TreeNode $root): array
    {
        $this->dfs($root);
        return $this->ans;
    }

    /**
     * @param TreeNode|null $root
     * @return void
     */
    private function dfs(?TreeNode $root): void
    {
        if ($root === null) {
            return;
        }
        $this->dfs($root->left);
        $this->ans[] = $root->val;
        $this->dfs($root->right);
    }
}
// https://leetcode.cn/submissions/detail/382905725/
```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```php
<?php

class Solution
{
    /**
     * @param int $n
     * @param int|null $lo
     * @param int|null $hi
     * @return TreeNode[]
     */
    function generateTrees(int $n, int $lo = null, int $hi = null): array
    {
        if (is_null($lo) && is_null($hi)) {
            return $this->generateTrees($n, 1, $n);
        }
        if ($lo > $hi) {
            return [null];
        }
        $res = [];
        for ($i = $lo; $i <= $hi; ++$i) {
            $leftTrees = $this->generateTrees($n, $lo, $i - 1);
            $rightTrees = $this->generateTrees($n, $i + 1, $hi);
            foreach ($leftTrees as $left) {
                foreach ($rightTrees as $right) {
                    $res[] = new TreeNode($i, $left, $right);
                }
            }
        }
        return $res;
    }
}
// https://leetcode.cn/submissions/detail/383048503/
```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```php
<?php

class Solution
{
    private array $memo = [];

    /**
     * 由 n 个不同数字 x_1 < x_2 < ... < x_n 组成的
     * 节点值互不相同的二叉搜索树的种数
     *
     * @param int $n
     * @return int
     */
    function numTrees(int $n): int
    {
        if ($n <= 1) {
            return 1;
        }
        if (!array_key_exists($n, $this->memo)) {
            $res = 0;
            // 根节点为 x_i
            // 左子树由 i-1 个数字 x1 < x2 < ... < x_i-1 组成
            // 右子树由 n-i 个数字 x_i+1 < x_i+2 < ... < x_n 组成
            for ($i = 1; $i <= $n; ++$i) {
                $res += $this->numTrees($i - 1) * $this->numTrees($n - $i);
            }
            $this->memo[$n] = $res;
        }
        return $this->memo[$n];
    }
}
// https://leetcode.cn/submissions/detail/383045370/
```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```php
<?php

class Solution
{
    private bool $ans = true;

    /**
     * @param TreeNode $root
     * @return bool
     */
    function isValidBST(TreeNode $root): bool
    {
        $this->lowerUpper($root, null, null);
        return $this->ans;
    }

    /**
     * 检查二叉树是否在区间 (lower, upper) 内，递归过程中确定是否满足二叉搜索树的性质。
     *
     * @param TreeNode|null $root
     * @param int|null $lower
     * @param int|null $upper
     * @return bool
     */
    private function lowerUpper(?TreeNode $root, ?int $lower, ?int $upper): bool
    {
        if ($root === null) {
            return true;
        }
        if (!is_null($lower) && $root->val <= $lower) {
            $this->ans = false;
            return false;
        }
        if (!is_null($upper) && $root->val >= $upper) {
            $this->ans = false;
            return false;
        }
        return $this->lowerUpper($root->left, $lower, $root->val)
            && $this->lowerUpper($root->right, $root->val, $upper);
    }
}
// https://leetcode.cn/submissions/detail/383155093/
```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $p
     * @param TreeNode|null $q
     * @return bool
     */
    function isSameTree(?TreeNode $p, ?TreeNode $q): bool
    {
        if ($p === null && $q === null) {
            return true;
        }
        if ($p === null || $q === null || $p->val !== $q->val) {
            return false;
        }
        return $this->isSameTree($p->left, $q->left)
            && $this->isSameTree($p->right, $q->right);
    }
}
// https://leetcode.cn/submissions/detail/382916043/
```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return int[][]
     */
    function levelOrder(?TreeNode $root): array
    {
        $ans = [];
        $queue = [];
        if ($root !== null) {
            $queue[] = $root;
        }
        while (count($queue) > 0) {
            $level = [];
            $n = count($queue);
            for ($i = 0; $i < $n; ++$i) {
                $x = array_shift($queue);
                $level[] = $x->val;
                $left = $x->left;
                if ($left !== null) {
                    $queue[] = $left;
                }
                $right = $x->right;
                if ($right !== null) {
                    $queue[] = $right;
                }
            }
            $ans[] = $level;
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/382979393/
```

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return int[][]
     */
    function levelOrder(?TreeNode $root): array
    {
        $ans = [];
        $queue = new SplQueue();
        if ($root !== null) {
            $queue->enqueue($root);
        }
        while (!$queue->isEmpty()) {
            $level = [];
            $n = $queue->count();
            for ($i = 0; $i < $n; ++$i) {
                $x = $queue->dequeue();
                $level[] = $x->val;
                $left = $x->left;
                if ($left !== null) {
                    $queue->enqueue($left);
                }
                $right = $x->right;
                if ($right !== null) {
                    $queue->enqueue($right);
                }
            }
            $ans[] = $level;
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/382980244/
```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return int[][]
     */
    function zigzagLevelOrder(?TreeNode $root): array
    {
        $ans = [];
        $queue = new SplQueue();
        if ($root !== null) {
            $queue->enqueue($root);
        }
        $reverse = false;
        while (!$queue->isEmpty()) {
            $level = [];
            $n = $queue->count();
            for ($i = 0; $i < $n; ++$i) {
                $x = $queue->dequeue();
                $level[] = $x->val;
                $left = $x->left;
                if ($left !== null) {
                    $queue->enqueue($left);
                }
                $right = $x->right;
                if ($right !== null) {
                    $queue->enqueue($right);
                }
            }
            if ($reverse) {
                $level = array_reverse($level);
            }
            $reverse = !$reverse;
            $ans[] = $level;
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/382988778/
```

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return int[][]
     */
    function zigzagLevelOrder(?TreeNode $root): array
    {
        $ans = [];
        $queue = new SplQueue();
        if ($root !== null) {
            $queue->enqueue($root);
        }
        $reverse = false;
        while (!$queue->isEmpty()) {
            $level = [];
            $n = $queue->count();
            for ($i = 0; $i < $n; ++$i) {
                $x = $queue->dequeue();
                if ($reverse) {
                    array_unshift($level, $x->val);
                } else {
                    $level[] = $x->val;
                }
                $left = $x->left;
                if ($left !== null) {
                    $queue->enqueue($left);
                }
                $right = $x->right;
                if ($right !== null) {
                    $queue->enqueue($right);
                }
            }
            $reverse = !$reverse;
            $ans[] = $level;
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/382987275/
```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return int
     */
    function maxDepth(?TreeNode $root): int
    {
        if ($root === null) {
            return 0;
        }
        return 1 + max($this->maxDepth($root->left), $this->maxDepth($root->right));
    }
}
// https://leetcode.cn/submissions/detail/382912828/
```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```php
<?php

class Solution
{
    private ?array $inorderMap = null;

    /**
     * @param int[] $preorder
     * @param int[] $inorder
     * @param int|null $preStart
     * @param int|null $preEnd
     * @param int|null $inStart
     * @param int|null $inEnd
     * @return TreeNode|null
     */
    function buildTree(array $preorder, array $inorder,
                       int   $preStart = null, int $preEnd = null,
                       int   $inStart = null, int $inEnd = null): ?TreeNode
    {
        if (is_null($preStart) && is_null($preEnd) &&
            is_null($inStart) && is_null($inEnd)) {
            $this->inorderMap = array_combine(array_values($inorder), array_keys($inorder));
            return $this->buildTree($preorder, $inorder, 0, count($preorder) - 1, 0, count($inorder) - 1);
        }
        if ($preStart > $preEnd) {
            return null;
        }
        $rootVal = $preorder[$preStart];
        $inRoot = $this->inorderMap[$rootVal];
        $leftSize = $inRoot - $inStart;
        $root = new TreeNode($rootVal);
        $root->left = $this->buildTree($preorder, $inorder, $preStart + 1, $preStart + $leftSize, $inStart, $inRoot - 1);
        $root->right = $this->buildTree($preorder, $inorder, $preStart + $leftSize + 1, $preEnd, $inRoot + 1, $inEnd);
        return $root;
    }
}
// https://leetcode.cn/submissions/detail/383056286/
```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```php
<?php

class Solution
{
    private ?array $inorderMap = null;

    /**
     * @param int[] $inorder
     * @param int[] $postorder
     * @param int|null $inStart
     * @param int|null $inEnd
     * @param int|null $postStart
     * @param int|null $postEnd
     * @return TreeNode|null
     */
    function buildTree(array $inorder, array $postorder,
                       int   $inStart = null, int $inEnd = null,
                       int   $postStart = null, int $postEnd = null): ?TreeNode
    {
        if (is_null($inStart) && is_null($inEnd) &&
            is_null($postStart) && is_null($postEnd)) {
            $this->inorderMap = array_combine(array_values($inorder), array_keys($inorder));
            return $this->buildTree($inorder, $postorder, 0, count($inorder) - 1, 0, count($postorder) - 1);
        }
        if ($inStart > $inEnd) {
            return null;
        }
        $rootVal = $postorder[$postEnd];
        $inRoot = $this->inorderMap[$rootVal];
        $leftSize = $inRoot - $inStart;
        $root = new TreeNode($rootVal);
        $root->left = $this->buildTree($inorder, $postorder, $inStart, $inRoot - 1, $postStart, $postStart + $leftSize - 1);
        $root->right = $this->buildTree($inorder, $postorder, $inRoot + 1, $inEnd, $postStart + $leftSize, $postEnd - 1);
        return $root;
    }
}
// https://leetcode.cn/submissions/detail/383059753/
```

## 107. 二叉树的层序遍历 II

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return int[][]
     */
    function levelOrderBottom(?TreeNode $root): array
    {
        $ans = [];
        $queue = new SplQueue();
        if ($root !== null) {
            $queue->enqueue($root);
        }
        while (!$queue->isEmpty()) {
            $level = [];
            $n = $queue->count();
            for ($i = 0; $i < $n; ++$i) {
                $x = $queue->dequeue();
                $level[] = $x->val;
                $left = $x->left;
                if ($left !== null) {
                    $queue->enqueue($left);
                }
                $right = $x->right;
                if ($right !== null) {
                    $queue->enqueue($right);
                }
            }
            $ans[] = $level;
        }
        return array_reverse($ans);
    }
}
// https://leetcode.cn/submissions/detail/382984084/
```

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return int[][]
     */
    function levelOrderBottom(?TreeNode $root): array
    {
        $ans = [];
        $queue = new SplQueue();
        if ($root !== null) {
            $queue->enqueue($root);
        }
        while (!$queue->isEmpty()) {
            $level = [];
            $n = $queue->count();
            for ($i = 0; $i < $n; ++$i) {
                $x = $queue->dequeue();
                $level[] = $x->val;
                $left = $x->left;
                if ($left !== null) {
                    $queue->enqueue($left);
                }
                $right = $x->right;
                if ($right !== null) {
                    $queue->enqueue($right);
                }
            }
            array_unshift($ans, $level);
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/382983752/
```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```php
<?php

class Solution
{
    /**
     * @param int[] $nums
     * @param int|null $lo
     * @param int|null $hi
     * @return TreeNode|null
     */
    function sortedArrayToBST(array $nums, int $lo = null, int $hi = null): ?TreeNode
    {
        if (is_null($lo) && is_null($hi)) {
            return $this->sortedArrayToBST($nums, 0, count($nums) - 1);
        }
        if ($lo > $hi) {
            return null;
        }
        $mid = $lo + floor(($hi - $lo) / 2);
        $root = new TreeNode($nums[$mid]);
        $root->left = $this->sortedArrayToBST($nums, $lo, $mid - 1);
        $root->right = $this->sortedArrayToBST($nums, $mid + 1, $hi);
        return $root;
    }
}
// https://leetcode.cn/submissions/detail/382995024/
```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```php
<?php

class Solution
{
    private bool $ans = true;

    /**
     * @param TreeNode|null $root
     * @return bool
     */
    function isBalanced(?TreeNode $root): bool
    {
        $this->height($root);
        return $this->ans;
    }

    /**
     * @param TreeNode|null $root
     * @return int
     */
    private function height(?TreeNode $root): int
    {
        if ($root === null) {
            return -1;
        }
        $left = $this->height($root->left);
        $right = $this->height($root->right);
        if (abs($left - $right) > 1) {
            $this->ans = false;
        }
        return 1 + max($left, $right);
    }
}
// https://leetcode.cn/submissions/detail/383097271/
```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return int
     */
    function minDepth(?TreeNode $root): int
    {
        $depth = 0;
        $queue = new SplQueue();
        if ($root !== null) {
            $queue->enqueue($root);
        }
        while (!$queue->isEmpty()) {
            ++$depth;
            $n = $queue->count();
            for ($i = 0; $i < $n; ++$i) {
                $x = $queue->dequeue();
                $left = $x->left;
                $right = $x->right;
                if ($left === null && $right === null) {
                    return $depth;
                }
                if ($left !== null) {
                    $queue->enqueue($left);
                }
                if ($right !== null) {
                    $queue->enqueue($right);
                }
            }
        }
        return $depth;
    }
}
// https://leetcode.cn/submissions/detail/383092574/
```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @param int $targetSum
     * @return bool
     */
    function hasPathSum(?TreeNode $root, int $targetSum): bool
    {
        if ($root === null) {
            return false;
        }
        if ($root->left === null && $root->right === null) {
            return $root->val === $targetSum;
        }
        return $this->hasPathSum($root->left, $targetSum - $root->val)
            || $this->hasPathSum($root->right, $targetSum - $root->val);
    }
}
// https://leetcode.cn/submissions/detail/383769887/
```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return void
     */
    function flatten(?TreeNode $root): void
    {
        if ($root === null) {
            return;
        }
        $this->flatten($root->left);
        $this->flatten($root->right);
        $left = $root->left;
        $right = $root->right;
        $root->left = null;
        $root->right = $left;
        $ptr = $root;
        while ($ptr->right !== null) {
            $ptr = $ptr->right;
        }
        $ptr->right = $right;
    }
}
// https://leetcode.cn/submissions/detail/383095079/
```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```php

```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```php
<?php

class Solution
{
    /**
     * @param int[] $prices
     * @return int
     */
    function maxProfit(array $prices): int
    {
        $n = count($prices);
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        $dp = [];
        $dp[0][0] = 0;
        $dp[0][1] = -$prices[0];
        for ($i = 1; $i < $n; ++$i) {
            // dp[i - 1][0]             >= -prices[i]
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            $dp[$i][0] = max($dp[$i - 1][0], $dp[$i - 1][1] + $prices[$i]);
            $dp[$i][1] = max(-$prices[$i], $dp[$i - 1][1]);
        }
        return $dp[$n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/383634438/
```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```php
<?php

class Solution
{
    /**
     * @param int[] $prices
     * @return int
     */
    function maxProfit(array $prices): int
    {
        $n = count($prices);
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        $dp = [];
        $dp[0][0] = 0;
        $dp[0][1] = -$prices[0];
        for ($i = 1; $i < $n; ++$i) {
            // dp[i - 1][0]             >= dp[i - 1][0] - prices[i]
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            $dp[$i][0] = max($dp[$i - 1][0], $dp[$i - 1][1] + $prices[$i]);
            $dp[$i][1] = max($dp[$i - 1][0] - $prices[$i], $dp[$i - 1][1]);
        }
        return $dp[$n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/383634715/
```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```php
<?php

class Solution
{
    /**
     * @param int[] $prices
     * @return int
     */
    function maxProfit(array $prices): int
    {
        return $this->maxProfitK(2, $prices);
    }

    /**
     * 返回买卖股票的最大利润，交易次数限制为 k
     *
     * @param int $k
     * @param int[] $prices
     * @return int
     */
    private function maxProfitK(int $k, array $prices): int
    {
        $n = count($prices);
        if ($k <= 0 || $n <= 1) {
            return 0;
        }
        // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
        // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
        $dp = [];
        // 交易次数限制为 0 时
        // 填写第 0 个 n x 2 矩阵
        for ($i = 0; $i < $n; ++$i) {
            $dp[0][$i][0] = 0;
            $dp[0][$i][1] = PHP_INT_MIN;
        }
        // 交易次数限制为 [1..k] 时
        for ($t = 1; $t <= $k; ++$t) {
            // 填写第 t 个 n x 2 矩阵
            $dp[$t][0][0] = 0;
            $dp[$t][0][1] = -$prices[0];
            for ($i = 1; $i < $n; ++$i) {
                // dp[t][i - 1][0]             >= dp[t - 1][i - 1][0] - prices[i]
                // dp[t][i - 1][1] + prices[i] >= dp[t][i - 1][1]
                // => dp[t][i][0] >= dp[t][i][1]
                $dp[$t][$i][0] = max($dp[$t][$i - 1][0], $dp[$t][$i - 1][1] + $prices[$i]);
                $dp[$t][$i][1] = max($dp[$t - 1][$i - 1][0] - $prices[$i], $dp[$t][$i - 1][1]);
            }
        }
        return $dp[$k][$n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/383636507/
```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```php
<?php

class Solution
{
    /**
     * @param string $s
     * @return bool
     */
    function isPalindrome(string $s): bool
    {
        $n = strlen($s);
        $i = -1;
        $j = $n;
        while (true) {
            while (!ctype_alnum($s[++$i])) {
                if ($i === $n - 1) {
                    break;
                }
            }
            while (!ctype_alnum($s[--$j])) {
                if ($j === 0) {
                    break;
                }
            }
            if ($i >= $j) {
                break;
            }
            if (strtolower($s[$i]) !== strtolower($s[$j])) {
                return false;
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/383269259/
```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```php
<?php

class Solution
{
    /**
     * @param int[] $nums
     * @return int
     */
    function longestConsecutive(array $nums): int
    {
        $ans = 0;
        $counter = array_count_values($nums);
        foreach ($nums as $x) {
            if (isset($counter[$x])) {
                $lo = $x - 1;
                while (isset($counter[$lo])) {
                    unset($counter[$lo--]);
                }
                $hi = $x + 1;
                while (isset($counter[$hi])) {
                    unset($counter[$hi++]);
                }
                $ans = max($ans, $hi - $lo - 1);
                unset($counter[$x]);
            }
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/383777612/
```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```php
<?php

class Solution
{
    const LAND = "O";
    const WATER = "X";
    private bool $mark = false;
    private array $recovery = [];

    /**
     * @param string[][] $grid
     * @return void
     */
    function solve(array &$grid): void
    {
        $m = count($grid);
        $n = count($grid[0]);
        $this->mark = true;
        // 淹没与左右边界的陆地相连的岛屿
        for ($i = 0; $i < $m; ++$i) {
            $this->floodFill($grid, $i, 0);
            $this->floodFill($grid, $i, $n - 1);
        }
        // 淹没与上下边界的陆地相连的岛屿
        for ($j = 0; $j < $n; ++$j) {
            $this->floodFill($grid, 0, $j);
            $this->floodFill($grid, $m - 1, $j);
        }
        $this->mark = false;
        // 淹没封闭岛屿
        for ($i = 0; $i < $m; ++$i) {
            for ($j = 0; $j < $n; ++$j) {
                if ($grid[$i][$j] === self::LAND) {
                    $this->floodFill($grid, $i, $j);
                }
            }
        }
        // 重建原来与边界陆地相连的岛屿
        foreach ($this->recovery as $x) {
            $i = floor($x / $n);
            $j = $x % $n;
            $grid[$i][$j] = self::LAND;
        }
    }

    /**
     * @param string[][] $grid
     * @param int $i
     * @param int $j
     * @return void
     */
    private function floodFill(array &$grid, int $i, int $j): void
    {
        if ($i < 0 || $i >= count($grid) ||
            $j < 0 || $j >= count($grid[0]) ||
            $grid[$i][$j] === self::WATER) {
            return;
        }
        if ($this->mark) {
            $this->recovery[] = $i * count($grid[0]) + $j;
        }
        $grid[$i][$j] = self::WATER;
        $this->floodFill($grid, $i, $j + 1);
        $this->floodFill($grid, $i, $j - 1);
        $this->floodFill($grid, $i + 1, $j);
        $this->floodFill($grid, $i - 1, $j);
    }
}
// https://leetcode.cn/submissions/detail/383805631/
```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```php
<?php

class Solution
{
    /**
     * @param int[] $nums
     * @return int
     */
    function singleNumber(array $nums): int
    {
        $ans = 0;
        foreach ($nums as $x) {
            $ans ^= $x;
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/384178954/
```

## 141. 环形链表

<https://leetcode-cn.com/problems/linked-list-cycle/>

```php
<?php

class Solution
{
    /**
     * @param ListNode|null $head
     * @return Boolean
     */
    function hasCycle(?ListNode $head): bool
    {
        $slow = $head;
        $fast = $head;
        while ($fast !== null && $fast->next !== null) {
            $slow = $slow->next;
            $fast = $fast->next->next;
            if ($slow === $fast) {
                return true;
            }
        }
        return false;
    }
}
// https://leetcode.cn/submissions/detail/382541479/
```

## 142. 环形链表 II

<https://leetcode-cn.com/problems/linked-list-cycle-ii/>

```php

```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```php
<?php

class Solution
{
    /**
     * @param ListNode $head
     * @return NULL
     */
    function reorderList(ListNode $head)
    {
        $slow = $head;
        $fast = $head;
        while ($fast->next !== null && $fast->next->next !== null) {
            $slow = $slow->next;
            $fast = $fast->next->next;
        }
        $reverseHead = $this->reverseList($slow->next);
        $slow->next = null;
        $ptr = new ListNode();
        while ($head !== null) {
            $ptr->next = $head;
            $ptr = $ptr->next;
            $head = $head->next;
            if ($reverseHead !== null) {
                $ptr->next = $reverseHead;
                $ptr = $ptr->next;
                $reverseHead = $reverseHead->next;
            }
        }
    }

    /**
     * @param ListNode|null $head
     * @return ListNode|null
     */
    function reverseList(?ListNode $head): ?ListNode
    {
        $reverseHead = null;
        while ($head !== null) {
            $nextHead = $head->next;
            $head->next = $reverseHead;
            $reverseHead = $head;
            $head = $nextHead;
        }
        return $reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/382715487/
```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```php
<?php

class Solution
{
    private array $ans = [];

    /**
     * @param TreeNode|null $root
     * @return int[]
     */
    function preorderTraversal(?TreeNode $root): array
    {
        $this->dfs($root);
        return $this->ans;
    }

    /**
     * @param TreeNode|null $root
     * @return void
     */
    private function dfs(?TreeNode $root): void
    {
        if ($root === null) {
            return;
        }
        $this->ans[] = $root->val;
        $this->dfs($root->left);
        $this->dfs($root->right);
    }
}
// https://leetcode.cn/submissions/detail/382904946/
```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```php
<?php

class Solution
{
    private array $ans = [];

    /**
     * @param TreeNode|null $root
     * @return int[]
     */
    function postorderTraversal(?TreeNode $root): array
    {
        $this->dfs($root);
        return $this->ans;
    }

    /**
     * @param TreeNode|null $root
     * @return void
     */
    private function dfs(?TreeNode $root): void
    {
        if ($root === null) {
            return;
        }
        $this->dfs($root->left);
        $this->dfs($root->right);
        $this->ans[] = $root->val;
    }
}
// https://leetcode.cn/submissions/detail/382906307/
```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```php
<?php

class Node
{
    public int $key;
    public int $val;
    public ?Node $prev;
    public ?Node $next;

    /**
     * @param int $key
     * @param int $val
     * @param Node|null $prev
     * @param Node|null $next
     */
    public function __construct(int $key, int $val, Node $prev = null, Node $next = null)
    {
        $this->key = $key;
        $this->val = $val;
        $this->prev = $prev;
        $this->next = $next;
    }
}

class DoublyLinkedList
{
    private ?Node $first = null;
    private ?Node $last = null;
    private int $n = 0;

    /**
     * @param Node $x
     * @return void
     */
    public function addLast(Node $x): void
    {
        if ($this->n === 0) {
            $this->first = $x;
            $this->last = $x;
        } else {
            $this->last->next = $x;
            $x->prev = $this->last;
            $this->last = $x;
        }
        ++$this->n;
    }

    /**
     * @return Node
     */
    public function removeFirst(): Node
    {
        $oldFirst = $this->first;
        if ($this->n === 1) {
            $this->first = null;
            $this->last = null;
        } else {
            $this->first = $this->first->next;
            $this->first->prev = null;
            $oldFirst->next = null;
        }
        --$this->n;
        return $oldFirst;
    }

    /**
     * @return Node
     */
    public function removeLast(): Node
    {
        $oldLast = $this->last;
        if ($this->n === 1) {
            $this->first = null;
            $this->last = null;
        } else {
            $this->last = $this->last->prev;
            $this->last->next = null;
            $oldLast->prev = null;
        }
        --$this->n;
        return $oldLast;
    }

    /**
     * @param Node $x
     * @return void
     */
    public function remove(Node $x): void
    {
        if ($x === $this->first) {
            $this->removeFirst();
        } else if ($x === $this->last) {
            $this->removeLast();
        } else {
            $x->prev->next = $x->next;
            $x->next->prev = $x->prev;
            $x->prev = null;
            $x->next = null;
            --$this->n;
        }
    }
}

class LRUCache
{
    private DoublyLinkedList $list;
    private array $keyToNode = [];
    private int $capacity;

    /**
     * @param int $capacity
     */
    function __construct(int $capacity)
    {
        $this->capacity = $capacity;
        $this->list = new DoublyLinkedList();
    }

    /**
     * @param int $key
     * @return int
     */
    function get(int $key): int
    {
        if ($this->contains($key)) {
            return $this->touchCache($key);
        }
        return -1;
    }

    /**
     * @param int $key
     * @param int $value
     * @return void
     */
    function put(int $key, int $value): void
    {
        if ($this->capacity > 0) {
            if ($this->contains($key)) {
                $this->touchCache($key, $value);
            } else {
                if ($this->full()) {
                    $this->removeCache();
                }
                $this->addCache($key, $value);
            }
        }
    }

    /**
     * @param int $key
     * @return bool
     */
    private function contains(int $key): bool
    {
        return array_key_exists($key, $this->keyToNode);
    }

    /**
     * @return bool
     */
    private function full(): bool
    {
        return count($this->keyToNode) === $this->capacity;
    }

    /**
     * @param int $key
     * @param int $val
     * @return void
     */
    private function addCache(int $key, int $val): void
    {
        $x = new Node($key, $val);
        $this->list->addLast($x);
        $this->keyToNode[$key] = $x;
    }

    /**
     * @return void
     */
    private function removeCache(): void
    {
        unset($this->keyToNode[$this->list->removeFirst()->key]);
    }

    /**
     * @param int $key
     * @param int|null $val
     * @return int
     */
    private function touchCache(int $key, int $val = null): int
    {
        $x = $this->keyToNode[$key];
        if (isset($val)) {
            $x->val = $val;
        }
        $this->list->remove($x);
        $this->list->addLast($x);
        return $x->val;
    }
}
// https://leetcode.cn/submissions/detail/384083756/
```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @return Integer
     */
    function findMin(array $nums): int
    {
        $lo = 0;
        $hi = count($nums) - 1;
        while ($lo < $hi) {
            $mid = $lo + floor(($hi - $lo) / 2);
            if ($nums[$mid] < $nums[$hi]) {
                $hi = $mid;
            } else {
                $lo = $mid + 1;
            }
        }
        return $nums[$lo];
    }
}
// https://leetcode.cn/submissions/detail/382820423/
```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```php
<?php

class MinStack
{
    private SplStack $stack;

    function __construct()
    {
        $this->stack = new SplStack();
    }

    /**
     * @param int $val
     * @return void
     */
    function push(int $val): void
    {
        $min = $this->stack->isEmpty() ? $val : min($this->getMin(), $val);
        $this->stack->push([$val, $min]);
    }

    /**
     * @return void
     */
    function pop(): void
    {
        $this->stack->pop();
    }

    /**
     * @return int
     */
    function top(): int
    {
        return $this->stack->top()[0];
    }

    /**
     * @return int
     */
    function getMin(): int
    {
        return $this->stack->top()[1];
    }
}
// https://leetcode.cn/submissions/detail/383810332/
```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```php
<?php

class Solution
{
    /**
     * @param ListNode $headA
     * @param ListNode $headB
     * @return ListNode|null
     */
    function getIntersectionNode(ListNode $headA, ListNode $headB): ?ListNode
    {
        $ptrA = $headA;
        $ptrB = $headB;
        while ($ptrA !== $ptrB) {
            $ptrA = ($ptrA === null ? $headB : $ptrA->next);
            $ptrB = ($ptrB === null ? $headA : $ptrB->next);
        }
        return $ptrA;
    }
}
// https://leetcode.cn/submissions/detail/382539898/
```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```php
<?php

class Solution
{
    const ZERO = 48;
    const DOT = 46;

    /**
     * @param string $version1
     * @param string $version2
     * @return int
     */
    function compareVersion(string $version1, string $version2): int
    {
        $n1 = strlen($version1);
        $n2 = strlen($version2);
        $i = 0;
        $j = 0;
        while ($i < $n1 || $j < $n2) {
            $r1 = 0;
            while ($i < $n1) {
                $code = ord($version1[$i++]);
                if ($code === self::DOT) {
                    break;
                }
                $r1 = $r1 * 10 + ($code - self::ZERO);
            }
            $r2 = 0;
            while ($j < $n2) {
                $code = ord($version2[$j++]);
                if ($code === self::DOT) {
                    break;
                }
                $r2 = $r2 * 10 + ($code - self::ZERO);
            }
            if ($r1 > $r2) {
                return 1;
            }
            if ($r1 < $r2) {
                return -1;
            }
        }
        return 0;
    }
}
// https://leetcode.cn/submissions/detail/383385363/
```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $numbers
     * @param Integer $target
     * @return Integer[]
     */
    function twoSum(array $numbers, int $target): array
    {
        $i = 0;
        $j = count($numbers) - 1;
        while ($i < $j) {
            $sum = $numbers[$i] + $numbers[$j];
            if ($sum < $target) {
                ++$i;
            } else if ($sum > $target) {
                --$j;
            } else {
                return [$i + 1, $j + 1];
            }
        }
        return [];
    }
}
// https://leetcode.cn/submissions/detail/382527881/
```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @return Integer
     */
    function majorityElement(array $nums): int
    {
        $candidate = null;
        $count = 0;
        foreach ($nums as $x) {
            if ($count === 0) {
                $candidate = $x;
                $count = 1;
            } else {
                if ($x === $candidate) {
                    ++$count;
                } else {
                    --$count;
                }
            }
        }
        return $candidate;
    }
}
// https://leetcode.cn/submissions/detail/382828312/
```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```php
<?php

class Solution
{
    /**
     * @param int[] $nums
     * @return string
     */
    function largestNumber(array $nums): string
    {
        $strs = array_map(fn($x): string => strval($x), $nums);
        usort($strs, fn($s1, $s2): int => strcmp(($s2 . $s1), ($s1 . $s2)));
        $ans = join($strs);
        return $ans[0] === '0' ? "0" : $ans;
    }
}
// https://leetcode.cn/submissions/detail/383387913/
```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```php
<?php

class Solution
{
    /**
     * @param int $k
     * @param int[] $prices
     * @return int
     */
    function maxProfit(int $k, array $prices): int
    {
        $n = count($prices);
        if ($k <= 0 || $n <= 1) {
            return 0;
        }
        // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
        // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
        $dp = [];
        // 交易次数限制为 0 时
        // 填写第 0 个 n x 2 矩阵
        for ($i = 0; $i < $n; ++$i) {
            $dp[0][$i][0] = 0;
            $dp[0][$i][1] = PHP_INT_MIN;
        }
        // 交易次数限制为 [1..k] 时
        for ($t = 1; $t <= $k; ++$t) {
            // 填写第 t 个 n x 2 矩阵
            $dp[$t][0][0] = 0;
            $dp[$t][0][1] = -$prices[0];
            for ($i = 1; $i < $n; ++$i) {
                // dp[t][i - 1][0]             >= dp[t - 1][i - 1][0] - prices[i]
                // dp[t][i - 1][1] + prices[i] >= dp[t][i - 1][1]
                // => dp[t][i][0] >= dp[t][i][1]
                $dp[$t][$i][0] = max($dp[$t][$i - 1][0], $dp[$t][$i - 1][1] + $prices[$i]);
                $dp[$t][$i][1] = max($dp[$t - 1][$i - 1][0] - $prices[$i], $dp[$t][$i - 1][1]);
            }
        }
        return $dp[$k][$n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/383636102/
```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @param Integer $k
     * @return void
     */
    function rotate(array &$nums, int $k): void
    {
        $n = count($nums);
        $k %= $n;
        if ($k > 0) {
            $this->reverse($nums, 0, $n - 1);
            $this->reverse($nums, 0, $k - 1);
            $this->reverse($nums, $k, $n - 1);
        }
    }

    /**
     * @param Integer[] $nums
     * @param Integer $lo
     * @param Integer $hi
     * @return void
     */
    function reverse(array &$nums, int $lo, int $hi): void
    {
        while ($lo < $hi) {
            [$nums[$lo], $nums[$hi]] = [$nums[$hi], $nums[$lo]];
            ++$lo;
            --$hi;
        }
    }
}
// https://leetcode.cn/submissions/detail/382819195/
```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```php
<?php

class Solution
{
    /**
     * @param int[] $nums
     * @return int
     */
    function rob(array $nums): int
    {
        return $this->subseqSum($nums);
    }

    /**
     * max({sum(subseq) | subseq 是数组 nums 的任意不连续子序列})
     *
     * @param int[] $nums
     * @return int
     */
    private function subseqSum(array $nums): int
    {
        $n = count($nums);
        if ($n === 0) {
            return 0;
        }
        if ($n === 1) {
            return $nums[0];
        }
        if ($n === 2) {
            return max($nums[0], $nums[1]);
        }
        // dp[i] = max({sum(subseq) | subseq 是子数组 nums[0..i] 的任意不连续子序列})
        $dp = [];
        $dp[0] = $nums[0];
        $dp[1] = max($nums[0], $nums[1]);
        for ($i = 2; $i < $n; ++$i) {
            // 包含 nums[i]
            $sp1 = $dp[$i - 2] + $nums[$i];
            // 不包含 nums[i]
            $sp2 = $dp[$i - 1];
            $dp[$i] = max($sp1, $sp2);
        }
        return $dp[$n - 1];
    }
}
// https://leetcode.cn/submissions/detail/383625936/
```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return int[]
     */
    function rightSideView(?TreeNode $root): array
    {
        $ans = [];
        $queue = new SplQueue();
        if ($root !== null) {
            $queue->enqueue($root);
        }
        while (!$queue->isEmpty()) {
            $ans[] = $queue->top()->val;
            $n = $queue->count();
            for ($i = 0; $i < $n; ++$i) {
                $x = $queue->dequeue();
                $left = $x->left;
                if ($left !== null) {
                    $queue->enqueue($left);
                }
                $right = $x->right;
                if ($right !== null) {
                    $queue->enqueue($right);
                }
            }
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/382991417/
```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```php
<?php

class Solution
{
    const LAND = "1";
    const WATER = "0";

    /**
     * @param string[][] $grid
     * @return int
     */
    function numIslands(array $grid): int
    {
        $ans = 0;
        for ($i = 0; $i < count($grid); ++$i) {
            for ($j = 0; $j < count($grid[0]); ++$j) {
                if ($grid[$i][$j] === self::LAND) {
                    $this->floodFill($grid, $i, $j);
                    ++$ans;
                }
            }
        }
        return $ans;
    }

    /**
     * @param string[][] $grid
     * @param int $i
     * @param int $j
     * @return void
     */
    private function floodFill(array &$grid, int $i, int $j): void
    {
        if ($i < 0 || $i >= count($grid) ||
            $j < 0 || $j >= count($grid[0]) ||
            $grid[$i][$j] === self::WATER) {
            return;
        }
        $grid[$i][$j] = self::WATER;
        $this->floodFill($grid, $i, $j + 1);
        $this->floodFill($grid, $i, $j - 1);
        $this->floodFill($grid, $i + 1, $j);
        $this->floodFill($grid, $i - 1, $j);
    }
}
// https://leetcode.cn/submissions/detail/383799432/
```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```php
<?php

class Solution
{
    /**
     * @param ListNode|null $head
     * @param Integer $val
     * @return ListNode|null
     */
    function removeElements(?ListNode $head, int $val): ?ListNode
    {
        $dummyHead = new ListNode(-1, $head);
        $ptr = $dummyHead;
        while ($ptr !== null && $ptr->next !== null) {
            if ($ptr->next->val === $val) {
                $ptr->next = $ptr->next->next;
            } else {
                $ptr = $ptr->next;
            }
        }
        return $dummyHead->next;
    }
}
// https://leetcode.cn/submissions/detail/382770268/
```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```php
<?php

class Solution
{
    /**
     * @param ListNode|null $head
     * @return ListNode|null
     */
    function reverseList(?ListNode $head): ?ListNode
    {
        $reverseHead = null;
        while ($head !== null) {
            $nextHead = $head->next;
            $head->next = $reverseHead;
            $reverseHead = $head;
            $head = $nextHead;
        }
        return $reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/382715914/
```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```php
<?php

class Solution
{
    private array $marked;
    private array $onStack;
    private bool $hasCycle = false;

    /**
     * @param int $numCourses
     * @param int[][] $prerequisites
     * @return bool
     */
    function canFinish(int $numCourses, array $prerequisites): bool
    {
        $this->marked = array_fill(0, $numCourses, false);
        $this->onStack = array_fill(0, $numCourses, false);
        $graph = [];
        foreach ($prerequisites as $p) {
            $v = $p[1];
            $w = $p[0];
            $graph[$v][] = $w;
        }
        for ($v = 0; $v < $numCourses; ++$v) {
            if (!$this->marked[$v]) {
                $this->dfs($graph, $v);
                if ($this->hasCycle) {
                    break;
                }
            }
        }
        return !$this->hasCycle;
    }

    /**
     * @param int[][] $graph
     * @param int $v
     * @return void
     */
    private function dfs(array $graph, int $v): void
    {
        $this->onStack[$v] = true;
        $this->marked[$v] = true;
        foreach ($graph[$v] as $w) {
            if ($this->hasCycle) {
                return;
            }
            if (!$this->marked[$w]) {
                $this->dfs($graph, $w);
            } else if ($this->onStack[$w]) {
                $this->hasCycle = true;
                return;
            }
        }
        $this->onStack[$v] = false;
    }
}
// https://leetcode.cn/submissions/detail/384103423/
```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```php
<?php

class Solution
{
    private array $marked;
    private array $onStack;
    private bool $hasCycle = false;
    private array $postorder = [];

    /**
     * @param int $numCourses
     * @param int[][] $prerequisites
     * @return int[]
     */
    function findOrder(int $numCourses, array $prerequisites): array
    {
        if ($this->canFinish($numCourses, $prerequisites)) {
            return array_reverse($this->postorder);
        }
        return [];
    }

    /**
     * @param int $numCourses
     * @param int[][] $prerequisites
     * @return bool
     */
    private function canFinish(int $numCourses, array $prerequisites): bool
    {
        $this->marked = array_fill(0, $numCourses, false);
        $this->onStack = array_fill(0, $numCourses, false);
        $graph = [];
        foreach ($prerequisites as $p) {
            $v = $p[1];
            $w = $p[0];
            $graph[$v][] = $w;
        }
        for ($v = 0; $v < $numCourses; ++$v) {
            if (!$this->marked[$v]) {
                $this->dfs($graph, $v);
                if ($this->hasCycle) {
                    break;
                }
            }
        }
        return !$this->hasCycle;
    }

    /**
     * @param int[][] $graph
     * @param int $v
     * @return void
     */
    private function dfs(array $graph, int $v): void
    {
        $this->onStack[$v] = true;
        $this->marked[$v] = true;
        foreach ($graph[$v] as $w) {
            if ($this->hasCycle) {
                return;
            }
            if (!$this->marked[$w]) {
                $this->dfs($graph, $w);
            } else if ($this->onStack[$w]) {
                $this->hasCycle = true;
                return;
            }
        }
        $this->postorder[] = $v;
        $this->onStack[$v] = false;
    }
}
// https://leetcode.cn/submissions/detail/384106988/
```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```php
<?php

class Solution
{
    /**
     * @param int[] $nums
     * @return int
     */
    function rob(array $nums): int
    {
        $n = count($nums);
        if ($n === 0) {
            return 0;
        }
        if ($n === 1) {
            return $nums[0];
        }
        return max($this->subseqSum($nums, 0, $n - 2), $this->subseqSum($nums, 1, $n - 1));
    }

    /**
     * max({sum(subseq) | subseq 是子数组 nums[lo..hi] 的任意不连续子序列})
     *
     * @param int[] $nums
     * @param int $lo
     * @param int $hi
     * @return int
     */
    private function subseqSum(array $nums, int $lo, int $hi): int
    {
        $n = $hi - $lo + 1;
        if ($n === 0) {
            return 0;
        }
        if ($n === 1) {
            return $nums[$lo];
        }
        if ($n === 2) {
            return max($nums[$lo], $nums[$lo + 1]);
        }
        // dp[i] = max({sum(subseq) | subseq 是子数组 nums[lo..lo+i] 的任意不连续子序列})
        $dp = [];
        $dp[0] = $nums[$lo];
        $dp[1] = max($nums[$lo], $nums[$lo + 1]);
        for ($i = 2; $i < $n; ++$i) {
            // 包含 nums[lo+i]
            $sp1 = $dp[$i - 2] + $nums[$lo + $i];
            // 不包含 nums[lo+i]
            $sp2 = $dp[$i - 1];
            $dp[$i] = max($sp1, $sp2);
        }
        return $dp[$n - 1];
    }
}
// https://leetcode.cn/submissions/detail/383625283/
```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```php
<?php

class Solution
{
    /**
     * @param int[] $nums
     * @param int $k
     * @return int
     */
    function findKthLargest(array $nums, int $k): int
    {
        shuffle($nums);
        return $this->select($nums, count($nums) - $k);
    }

    /**
     * @param int[] $nums
     * @param int $rank
     * @return int
     */
    private function select(array &$nums, int $rank): int
    {
        $lo = 0;
        $hi = count($nums) - 1;
        while ($lo < $hi) {
            $j = $this->partition($nums, $lo, $hi);
            if ($rank < $j) {
                $hi = $j - 1;
            } else if ($j < $rank) {
                $lo = $j + 1;
            } else {
                return $nums[$j];
            }
        }
        return $nums[$lo];
    }

    /**
     * @param int[] $nums
     * @param int $lo
     * @param int $hi
     * @return int
     */
    private function partition(array &$nums, int $lo, int $hi): int
    {
        $v = $nums[$lo];
        $i = $lo;
        $j = $hi + 1;
        while (true) {
            while ($nums[++$i] < $v) {
                if ($i === $hi) {
                    break;
                }
            }
            while ($v < $nums[--$j]) {
                if ($j === $lo) {
                    break;
                }
            }
            if ($i >= $j) {
                break;
            }
            $this->swap($nums, $i, $j);
        }
        $this->swap($nums, $lo, $j);
        return $j;
    }

    /**
     * @param int[] $nums
     * @param int $i
     * @param int $j
     * @return void
     */
    private function swap(array &$nums, int $i, int $j): void
    {
        [$nums[$i], $nums[$j]] = [$nums[$j], $nums[$i]];
    }
}
// https://leetcode.cn/submissions/detail/382895173/
```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```php
<?php

class Solution
{
    private int $pathSum = 0;
    private array $path = []; // 取 [1..9] 为元素
    private array $ans = [];

    /**
     * @param int $k
     * @param int $n
     * @return int[][]
     */
    function combinationSum3(int $k, int $n): array
    {
        $this->backtrack($k, $n, 0);
        return $this->ans;
    }

    /**
     * @param int $k
     * @param int $n
     * @param int $edge 取 [1..9] 为值
     * @return void
     */
    private function backtrack(int $k, int $n, int $edge): void
    {
        if (count($this->path) === $k && $this->pathSum === $n) {
            $this->ans[] = [...$this->path];
        } else if (count($this->path) < $k && $this->pathSum < $n) {
            // 避免重复，从 edge + 1 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            while (++$edge <= 9) {
                if ($this->pathSum + $edge <= $n) {
                    $this->pathSum += $edge;
                    $this->path[] = $edge;
                    $this->backtrack($k, $n, $edge);
                    $this->pathSum -= $edge;
                    array_pop($this->path);
                }
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/383704488/
```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return int
     */
    function countNodes(?TreeNode $root): int
    {
        if ($root === null) {
            return 0;
        }
        $leftHeight = 0;
        $ptr = $root;
        while ($ptr !== null) {
            ++$leftHeight;
            $ptr = $ptr->left;
        }
        $rightHeight = 0;
        $ptr = $root->right;
        while ($ptr !== null) {
            ++$rightHeight;
            $ptr = $ptr->right;
        }
        if ($leftHeight === $rightHeight) {
            return 2 ** $leftHeight - 1;
        }
        return 1 + $this->countNodes($root->left) + $this->countNodes($root->right);
    }
}
// https://leetcode.cn/submissions/detail/383163858/
```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```php
<?php

class MyStack
{
    private SplQueue $queue;
    
    function __construct()
    {
        $this->queue = new SplQueue();
    }

    /**
     * @param int $x
     * @return void
     */
    function push(int $x): void
    {
        $this->queue->enqueue($x);
        for ($i = 1; $i < count($this->queue); ++$i) {
            $this->queue->enqueue($this->queue->dequeue());
        }
    }

    /**
     * @return int
     */
    function pop(): int
    {
        return $this->queue->dequeue();
    }

    /**
     * @return int
     */
    function top(): int
    {
        return $this->queue->bottom();
    }

    /**
     * @return bool
     */
    function empty(): bool
    {
        return $this->queue->isEmpty();
    }
}
// https://leetcode.cn/submissions/detail/383807100/
```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode|null $root
     * @return TreeNode|null
     */
    function invertTree(?TreeNode $root): ?TreeNode
    {
        if ($root === null) {
            return null;
        }
        $left = $this->invertTree($root->left);
        $right = $this->invertTree($root->right);
        $root->left = $right;
        $root->right = $left;
        return $root;
    }
}
// https://leetcode.cn/submissions/detail/383094064/
```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```php
<?php

class Solution
{
    private ?SplObjectStorage $memo = null;

    /**
     * @param TreeNode $root
     * @param int $k
     * @return int
     */
    function kthSmallest(TreeNode $root, int $k): int
    {
        $this->memo = new SplObjectStorage();
        return $this->select($root, $k - 1);
    }

    /**
     * @param TreeNode|null $root
     * @param int $rank
     * @return int|null
     */
    private function select(?TreeNode $root, int $rank): ?int
    {
        if ($root === null) {
            return null;
        }
        $leftSize = $this->size($root->left);
        if ($rank < $leftSize) {
            return $this->select($root->left, $rank);
        }
        if ($leftSize < $rank) {
            return $this->select($root->right, $rank - $leftSize - 1);
        }
        return $root->val;
    }

    /**
     * @param TreeNode|null $root
     * @return int
     */
    private function size(?TreeNode $root): int
    {
        if ($root === null) {
            return 0;
        }
        if (!$this->memo->contains($root)) {
            $res = 1 + $this->size($root->left) + $this->size($root->right);
            $this->memo[$root] = $res;
        }
        return $this->memo[$root];
    }
}
// https://leetcode.cn/submissions/detail/383160387/
```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```php
<?php

/**
 * -----------------------------| |-------------------------------
 * pop <- top Left Stack bottom | | bottom Right Stack top <- push
 * -----------------------------| |-------------------------------
 */
class MyQueue
{
    private SplStack $left;
    private SplStack $right;

    function __construct()
    {
        $this->left = new SplStack();
        $this->right = new SplStack();
    }

    /**
     * @param int $x
     * @return void
     */
    function push(int $x): void
    {
        $this->right->push($x);
    }

    /**
     * @return int
     */
    function pop(): int
    {
        if ($this->left->isEmpty()) {
            $this->move();
        }
        return $this->left->pop();
    }

    /**
     * @return int
     */
    function peek(): int
    {
        if ($this->left->isEmpty()) {
            $this->move();
        }
        return $this->left->top();
    }

    /**
     * @return bool
     */
    function empty(): bool
    {
        return $this->left->isEmpty() && $this->right->isEmpty();
    }

    /**
     * @return void
     */
    private function move(): void
    {
        while (!$this->right->isEmpty()) {
            $this->left->push($this->right->pop());
        }
    }
}
// https://leetcode.cn/submissions/detail/383809121/
```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```php
<?php

class Solution
{
    /**
     * @param ListNode $head
     * @return Boolean
     */
    function isPalindrome(ListNode $head): bool
    {
        // 寻找链表的中点（偶数个节点时选择左侧），即前半部分链表的尾节点
        $slow = $head;
        $fast = $head;
        while ($fast->next !== null && $fast->next->next !== null) {
            $slow = $slow->next;
            $fast = $fast->next->next;
        }
        // 翻转后半部分链表
        $reverseHead = $this->reverseList($slow->next);
        $slow->next = null;
        // 判断是否回文链表
        $left = $head;
        $right = $reverseHead;
        while ($right !== null) {
            if ($left->val !== $right->val) {
                return false;
            }
            $left = $left->next;
            $right = $right->next;
        }
        // 还原链表
        $slow->next = $this->reverseList($reverseHead);
        return true;
    }

    /**
     * @param ListNode|null $head
     * @return ListNode|null
     */
    function reverseList(?ListNode $head): ?ListNode
    {
        $reverseHead = null;
        while ($head !== null) {
            $nextHead = $head->next;
            $head->next = $reverseHead;
            $reverseHead = $head;
            $head = $nextHead;
        }
        return $reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/382717214/
```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```php
<?php

class Solution
{
    /**
     * @param TreeNode $root
     * @param TreeNode $p
     * @param TreeNode $q
     * @return TreeNode|null
     */
    function lowestCommonAncestor(TreeNode $root, TreeNode $p, TreeNode $q): ?TreeNode
    {
        // 保证 p < q
        if ($p->val > $q->val) {
            return $this->lowestCommonAncestor($root, $q, $p);
        }
        if ($p->val <= $root->val && $root->val <= $q->val) {
            return $root;
        }
        if ($q->val < $root->val) {
            return $this->lowestCommonAncestor($root->left, $p, $q);
        }
        if ($root->val < $p->val) {
            return $this->lowestCommonAncestor($root->right, $p, $q);
        }
        return null;
    }
}
// https://leetcode.cn/submissions/detail/383165043/
```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```php
<?php

class Solution
{
    private ?TreeNode $lca = null;

    /**
     * @param TreeNode $root
     * @param TreeNode $p
     * @param TreeNode $q
     * @return TreeNode
     */
    function lowestCommonAncestor(TreeNode $root, TreeNode $p, TreeNode $q): TreeNode
    {
        $this->find($root, $p, $q);
        return $this->lca;
    }

    /**
     * 在子树中查找节点 p 或 q，递归过程中确定『最近公共祖先』
     *
     * @param TreeNode|null $root
     * @param TreeNode $p
     * @param TreeNode $q
     * @return bool
     */
    function find(?TreeNode $root, TreeNode $p, TreeNode $q): bool
    {
        if ($root === null) {
            return false;
        }
        if ($root === $p || $root === $q) {
            // 如果 lca(p,q) = p 或 q，则此处的 lca = root 是最终答案
            $this->lca = $root;
            return true;
        }
        $left = $this->find($root->left, $p, $q);
        $right = $this->find($root->right, $p, $q);
        // 否则返回到某祖先节点处的 lca = root 才是最终答案
        if ($left && $right) {
            $this->lca = $root;
        }
        return $left || $right;
    }
}
// https://leetcode.cn/submissions/detail/383166720/
```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```php
<?php

class Solution
{
    /**
     * @param ListNode $node
     * @return void
     */
    function deleteNode(ListNode $node): void
    {
        $node->val = $node->next->val;
        $node->next = $node->next->next;
    }
}
// https://leetcode.cn/submissions/detail/382775338/
```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```php
<?php

class Solution
{
    /**
     * @param int[] $nums
     * @param int $k
     * @return int[]
     */
    function maxSlidingWindow(array $nums, int $k): array
    {
        $ans = [];
        $maxMonoQueue = new SplQueue();
        for ($i = 0; $i < count($nums); ++$i) {
            // nums[i] = 进入窗口的数字
            $x = $nums[$i];
            while (!$maxMonoQueue->isEmpty() && $maxMonoQueue->top() < $x) {
                $maxMonoQueue->pop();
            }
            $maxMonoQueue->enqueue($x);
            if ($i < $k - 1) {
                continue;
            }
            // nums[i-k] = 退出窗口的数字
            if ($i >= $k && $nums[$i - $k] === $maxMonoQueue->bottom()) {
                $maxMonoQueue->dequeue();
            }
            $ans[] = $maxMonoQueue->bottom();
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/383550468/
```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```php

```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```php
<?php

class Solution
{
    /**
     * @param Integer[] $nums
     * @return void
     */
    function moveZeroes(array &$nums): void
    {
        // [0..$i-1] != 0
        // [$i..j-1] == 0
        // [j..$n-1] Scanning
        $i = 0;
        $j = 0;
        $n = count($nums);
        while ($j < $n) {
            while ($j < $n && $nums[$j] == 0) {
                ++$j;
            }
            if ($j < $n) {
                [$nums[$i], $nums[$j]] = [$nums[$j], $nums[$i]];
                ++$i;
                ++$j;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/382475791/
```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```php
<?php

class Codec
{
    /**
     * @param TreeNode|null $root
     * @return string
     */
    function serialize(?TreeNode $root): string
    {
        if ($root === null) {
            return "#";
        }
        $left = $this->serialize($root->left);
        $right = $this->serialize($root->right);
        return $left . "," . $right . "," . $root->val;
    }

    /**
     * @param string $data
     * @return TreeNode|null
     */
    function deserialize(string $data): ?TreeNode
    {
        $postorder = explode(",", $data);
        return $this->buildTree($postorder);
    }

    /**
     * @param string[] $postorder
     * @return TreeNode|null
     */
    private function buildTree(array &$postorder): ?TreeNode
    {
        $str = array_pop($postorder);
        if ($str === "#") {
            return null;
        }
        $right = $this->buildTree($postorder);
        $left = $this->buildTree($postorder);
        return new TreeNode(intval($str), $left, $right);
    }
}
// https://leetcode.cn/submissions/detail/383080601/
```

```php
<?php

class Codec
{
    /**
     * @param TreeNode|null $root
     * @return string
     */
    function serialize(?TreeNode $root): string
    {
        if ($root === null) {
            return "#";
        }
        $left = $this->serialize($root->left);
        $right = $this->serialize($root->right);
        return $left . "," . $right . "," . $root->val;
    }

    /**
     * @param string $data
     * @return TreeNode|null
     */
    function deserialize(string $data): ?TreeNode
    {
        $postorder = explode(",", $data);
        $queue = new SplQueue();
        foreach ($postorder as $x) {
            $queue->enqueue($x);
        }
        return $this->buildTree($queue);
    }

    /**
     * @param SplQueue $queue
     * @return TreeNode|null
     */
    private function buildTree(SplQueue &$queue): ?TreeNode
    {
        $str = $queue->pop();
        if ($str === "#") {
            return null;
        }
        $right = $this->buildTree($queue);
        $left = $this->buildTree($queue);
        return new TreeNode(intval($str), $left, $right);
    }
}
// https://leetcode.cn/submissions/detail/383086304/
```

```php
<?php

class Codec
{
    /**
     * @param TreeNode|null $root
     * @return string
     */
    function serialize(?TreeNode $root): string
    {
        if ($root === null) {
            return "#";
        }
        $left = $this->serialize($root->left);
        $right = $this->serialize($root->right);
        return $root->val . "," . $left . "," . $right;
    }

    /**
     * @param string $data
     * @return TreeNode|null
     */
    function deserialize(string $data): ?TreeNode
    {
        $preorder = explode(",", $data);
        return $this->buildTree($preorder);
    }

    /**
     * @param string[] $preorder
     * @return TreeNode|null
     */
    private function buildTree(array &$preorder): ?TreeNode
    {
        $str = array_shift($preorder);
        if ($str === "#") {
            return null;
        }
        $left = $this->buildTree($preorder);
        $right = $this->buildTree($preorder);
        return new TreeNode(intval($str), $left, $right);
    }
}
// https://leetcode.cn/submissions/detail/383079134/
```

```php
<?php

class Codec
{
    /**
     * @param TreeNode|null $root
     * @return string
     */
    function serialize(?TreeNode $root): string
    {
        if ($root === null) {
            return "#";
        }
        $left = $this->serialize($root->left);
        $right = $this->serialize($root->right);
        return $root->val . "," . $left . "," . $right;
    }

    /**
     * @param string $data
     * @return TreeNode|null
     */
    function deserialize(string $data): ?TreeNode
    {
        $preorder = explode(",", $data);
        $queue = new SplQueue();
        foreach ($preorder as $x) {
            $queue->enqueue($x);
        }
        return $this->buildTree($queue);
    }

    /**
     * @param SplQueue $queue
     * @return TreeNode|null
     */
    private function buildTree(SplQueue &$queue): ?TreeNode
    {
        $str = $queue->dequeue();
        if ($str === "#") {
            return null;
        }
        $left = $this->buildTree($queue);
        $right = $this->buildTree($queue);
        return new TreeNode(intval($str), $left, $right);
    }
}
// https://leetcode.cn/submissions/detail/383083625/
```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```php
<?php

class Solution
{
    /**
     * @param int[] $nums
     * @return int
     */
    function lengthOfLIS(array $nums): int
    {
        $ans = 0;
        $n = count($nums);
        // dp[i] = max({length(subseq) | subseq 是以 nums[i] 结尾的严格递增子序列})
        $dp = array_fill(0, $n, 1);
        for ($i = 0; $i < $n; ++$i) {
            for ($j = $i - 1; $j >= 0; --$j) {
                if ($nums[$j] < $nums[$i]) {
                    $dp[$i] = max($dp[$i], $dp[$j] + 1);
                }
            }
            $ans = max($ans, $dp[$i]);
        }
        return $ans;
    }
}
// https://leetcode.cn/submissions/detail/383551427/
```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```php
<?php

class NumArray
{
    private array $prefixSum;

    /**
     * @param int[] $nums
     */
    function __construct(array $nums)
    {
        $this->prefixSum[0] = $nums[0];
        foreach ($nums as $index => $value) {
            $this->prefixSum[$index] = $this->prefixSum[$index - 1] + $value;
        }
    }

    /**
     * @param int $left
     * @param int $right
     * @return int
     */
    function sumRange(int $left, int $right): int
    {
        if ($left === 0) {
            return $this->prefixSum[$right];
        }
        return $this->prefixSum[$right] - $this->prefixSum[$left - 1];
    }
}
// https://leetcode.cn/submissions/detail/383812714/
```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```php
<?php

class Solution
{
    /**
     * @param int[] $prices
     * @return int
     */
    function maxProfit(array $prices): int
    {
        $n = count($prices);
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        $dp = [];
        $dp[0][0] = 0;
        $dp[0][1] = -$prices[0];
        $dp[1][0] = max($dp[0][0], $dp[0][1] + $prices[1]);
        $dp[1][1] = max($dp[0][0] - $prices[1], $dp[0][1]);
        for ($i = 2; $i < $n; ++$i) {
            // dp[i - 1][0]             >= dp[i - 2][0] >= p[i - 2][0] - prices[i]
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            $dp[$i][0] = max($dp[$i - 1][0], $dp[$i - 1][1] + $prices[$i]);
            $dp[$i][1] = max($dp[$i - 2][0] - $prices[$i], $dp[$i - 1][1]);
        }
        return $dp[$n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/383635130/
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
