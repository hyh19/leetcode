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
import 'dart:collection';

class Solution {
  List<int> twoSum(List<int> nums, int target) {
    final valToIndex = HashMap<int, int>();
    for (var i = 0; i < nums.length; ++i) {
      final x = nums[i];
      final need = target - x;
      if (valToIndex.containsKey(need)) {
        return [valToIndex[need]!, i];
      }
      valToIndex.putIfAbsent(x, () => i);
    }
    return [-1, -1];
  }
}
// https://leetcode.cn/submissions/detail/378331707/
```

## 2. 两数相加

<https://leetcode-cn.com/problems/add-two-numbers/>

```dart
class Solution {
  ListNode? addTwoNumbers(ListNode? l1, ListNode? l2) {
    final dummyHead = ListNode();
    var ptr = dummyHead;
    var carry = 0;
    while (l1 != null || l2 != null || carry > 0) {
      var sum = carry;
      if (l1 != null) {
        sum += l1.val;
        l1 = l1.next;
      }
      if (l2 != null) {
        sum += l2.val;
        l2 = l2.next;
      }
      ptr.next = ListNode(sum % 10);
      ptr = ptr.next!;
      carry = sum ~/ 10;
    }
    return dummyHead.next;
  }
}
// https://leetcode.cn/submissions/detail/378307278/
```

## 3. 无重复字符的最长子串

<https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/>

```dart
import 'dart:collection';

class Solution {
  int lengthOfLongestSubstring(String s) {
    var ans = 0;
    final window = HashSet<String>();
    // s[left..right) = Window Substring
    // s[right..n-1]  = Scanning
    var left = 0;
    var right = 0;
    while (right < s.length) {
      final c = s[right];
      if (!window.contains(c)) {
        window.add(c);
        ++right;
      } else {
        while (left < right) {
          final d = s[left++];
          window.remove(d);
          if (c == d) {
            break;
          }
        }
      }
      ans = max(ans, right - left);
    }
    return ans;
  }
}
// https://leetcode.cn/submissions/detail/378511289/
```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```dart
class Solution {
  double findMedianSortedArrays(List<int> nums1, List<int> nums2) {
    final total = nums1.length + nums2.length;
    final half = total ~/ 2;
    if (total % 2 == 0) {
      final k1 = _getKthElement(nums1, 0, nums2, 0, half);
      final k2 = _getKthElement(nums1, 0, nums2, 0, half + 1);
      return (k1 + k2) / 2;
    }
    return _getKthElement(nums1, 0, nums2, 0, half + 1).toDouble();
  }

  // 寻找两个正序数组 nums1[start1..end1] 和 nums2[start2..end2] 从小到大排列的第 k 个数
  int _getKthElement(
      List<int> nums1, int start1, List<int> nums2, int start2, int k) {
    final n1 = nums1.length;
    final n2 = nums2.length;
    if (start1 >= n1) {
      return nums2[start2 + k - 1];
    }
    if (start2 >= n2) {
      return nums1[start1 + k - 1];
    }
    if (k == 1) {
      return min(nums1[start1], nums2[start2]);
    }
    final half = k ~/ 2;
    final i = min(n1 - 1, start1 + half - 1);
    final j = min(n2 - 1, start2 + half - 1);
    if (nums1[i] < nums2[j]) {
      // 排除 nums1[start1..i] 共 i-start1+1 个元素
      return _getKthElement(nums1, i + 1, nums2, start2, k - (i - start1 + 1));
    } else {
      // 排除 nums2[start2..j] 共 j-start2+1 个元素
      return _getKthElement(nums1, start1, nums2, j + 1, k - (j - start2 + 1));
    }
  }
}
// https://leetcode.cn/submissions/detail/377852201/
```

## 5. 最长回文子串

<https://leetcode.cn/problems/longest-palindromic-substring/>

```dart
class Solution {
  String longestPalindrome(String s) {
    var ans = '';
    for (var i = 0; i < s.length; ++i) {
      final s1 = _longestPalindrome(s, i, i);
      if (s1.length > ans.length) {
        ans = s1;
      }
      final s2 = _longestPalindrome(s, i, i + 1);
      if (s2.length > ans.length) {
        ans = s2;
      }
    }
    return ans;
  }

  // 字符串 s 中以 s[i] 和 s[j] 为中心的最长回文子串
  String _longestPalindrome(String s, int i, int j) {
    if (i > j || j - i > 1) {
      return '';
    }
    while (i >= 0 && j < s.length && s[i] == s[j]) {
      --i;
      ++j;
    }
    return s.substring(i + 1, j);
  }
}
// https://leetcode.cn/submissions/detail/378014362/
```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```dart

```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```dart
class Solution {
  int maxArea(List<int> height) {
    var i = 0;
    var j = height.length - 1;
    var ans = 0;
    while (i < j) {
      final area = min(height[i], height[j]) * (j - i);
      ans = max(ans, area);
      if (height[i] < height[j]) {
        ++i;
      } else {
        --j;
      }
    }
    return ans;
  }
}
// https://leetcode.cn/submissions/detail/378016142/
```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```dart
class Solution {
  String longestCommonPrefix(List<String> strs) {
    return _longestCommonPrefixRange(strs, 0, strs.length - 1);
  }

  String _longestCommonPrefixRange(List<String> strs, int lo, int hi) {
    if (lo == hi) {
      return strs[lo];
    }
    final mid = lo + (hi - lo) ~/ 2;
    final left = _longestCommonPrefixRange(strs, lo, mid);
    final right = _longestCommonPrefixRange(strs, mid + 1, hi);
    return _longestCommonPrefixTwo(left, right);
  }

  String _longestCommonPrefixTwo(String s1, String s2) {
    final n = min(s1.length, s2.length);
    var i = 0;
    while (i < n && s1[i] == s2[i]) {
      ++i;
    }
    return s1.substring(0, i);
  }
}
// https://leetcode.cn/submissions/detail/378436116/
```

## 15. 三数之和

<https://leetcode-cn.com/problems/3sum/>

```dart
class Solution {
  List<List<int>> threeSum(List<int> nums) {
    nums.sort();
    return _kSum(3, nums, 0, nums.length - 1, 0);
  }

  // 升序子数组 nums[lo..hi] 所有和为 target 且不重复的 k 元组
  List<List<int>> _kSum(int k, List<int> nums, int lo, int hi, int target) {
    if (hi - lo + 1 < k) {
      return [];
    }
    if (k == 2) {
      return _twoSum(nums, lo, hi, target);
    }
    final res = <List<int>>[];
    var i = lo;
    while (i <= hi) {
      final curNum = nums[i];
      final sp = _kSum(k - 1, nums, i + 1, hi, target - curNum);
      for (var x in sp) {
        x.add(curNum);
        res.add(x);
      }
      while (++i <= hi && nums[i] == curNum) {}
    }
    return res;
  }

  // 升序子数组 nums[lo..hi] 所有和为 target 且不重复的 2 元组
  List<List<int>> _twoSum(List<int> nums, int lo, int hi, int target) {
    final res = <List<int>>[];
    while (lo < hi) {
      final first = nums[lo];
      final second = nums[hi];
      final sum = first + second;
      if (sum < target) {
        while (++lo < hi && nums[lo] == first) {}
      } else if (sum > target) {
        while (lo < --hi && nums[hi] == second) {}
      } else {
        res.add([first, second]);
        while (++lo < hi && nums[lo] == first) {}
        while (lo < --hi && nums[hi] == second) {}
      }
    }
    return res;
  }
}
// https://leetcode.cn/submissions/detail/378021825/
```

## 18. 四数之和

<https://leetcode.cn/problems/4sum/>

```dart
class Solution {
  List<List<int>> fourSum(List<int> nums, int target) {
    nums.sort();
    return _kSum(4, nums, 0, nums.length - 1, target);
  }

  // 升序子数组 nums[lo..hi] 所有和为 target 且不重复的 k 元组
  List<List<int>> _kSum(int k, List<int> nums, int lo, int hi, int target) {
    if (hi - lo + 1 < k) {
      return [];
    }
    if (k == 2) {
      return _twoSum(nums, lo, hi, target);
    }
    final res = <List<int>>[];
    var i = lo;
    while (i <= hi) {
      final curNum = nums[i];
      final sp = _kSum(k - 1, nums, i + 1, hi, target - curNum);
      for (var x in sp) {
        x.add(curNum);
        res.add(x);
      }
      while (++i <= hi && nums[i] == curNum) {}
    }
    return res;
  }

  // 升序子数组 nums[lo..hi] 所有和为 target 且不重复的 2 元组
  List<List<int>> _twoSum(List<int> nums, int lo, int hi, int target) {
    final res = <List<int>>[];
    while (lo < hi) {
      final first = nums[lo];
      final second = nums[hi];
      final sum = first + second;
      if (sum < target) {
        while (++lo < hi && nums[lo] == first) {}
      } else if (sum > target) {
        while (lo < --hi && nums[hi] == second) {}
      } else {
        res.add([first, second]);
        while (++lo < hi && nums[lo] == first) {}
        while (lo < --hi && nums[hi] == second) {}
      }
    }
    return res;
  }
}
// https://leetcode.cn/submissions/detail/378020710/
```

## 19. 删除链表的倒数第 N 个结点

<https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/>

```dart
class Solution {
  ListNode? removeNthFromEnd(ListNode? head, int n) {
    final dummyHead = ListNode(-1, head);
    var slow = dummyHead;
    var fast = dummyHead;
    for (var i = 0; i < n; ++i) {
      fast = fast.next!;
    }
    while (fast.next != null) {
      slow = slow.next!;
      fast = fast.next!;
    }
    final x = slow.next;
    if (x == head) {
      // 删除的是头结点
      head = head!.next;
    } else {
      slow.next = x!.next;
    }
    return head;
  }
}
// https://leetcode.cn/submissions/detail/377953429/
```

## 20. 有效的括号

<https://leetcode-cn.com/problems/valid-parentheses/>

```dart
import 'dart:collection';

class Solution {
  bool isValid(String s) {
    final n = s.length;
    if (n % 2 == 1) {
      return false;
    }
    final stack = Queue<String>();
    for (var i = 0; i < n; ++i) {
      final ch = s[i];
      switch (ch) {
        case '(':
          stack.addLast(')');
          break;
        case '[':
          stack.addLast(']');
          break;
        case '{':
          stack.addLast('}');
          break;
        default:
          if (stack.isEmpty || stack.removeLast() != ch) {
            return false;
          }
      }
    }
    return stack.isEmpty;
  }
}
// https://leetcode.cn/submissions/detail/378096157/
```

## 21. 合并两个有序链表

<https://leetcode-cn.com/problems/merge-two-sorted-lists/>

```dart
class Solution {
  ListNode? mergeTwoLists(ListNode? list1, ListNode? list2) {
    final dummyHead = ListNode();
    var ptr = dummyHead;
    while (list1 != null && list2 != null) {
      if (list1.val < list2.val) {
        ptr.next = list1;
        list1 = list1.next;
      } else {
        ptr.next = list2;
        list2 = list2.next;
      }
      ptr = ptr.next!;
    }
    ptr.next = (list1 ?? list2);
    return dummyHead.next;
  }
}
// https://leetcode.cn/submissions/detail/378310668/
```

## 22. 括号生成

<https://leetcode.cn/problems/generate-parentheses/>

```dart
class Solution {
  int _left = 0; // 已使用的『左括号』数量
  int _right = 0; // 已使用的『右括号』数量
  late final int _n;
  late final List<String> _path = []; // 取 '(', ')' 为元素
  late final List<String> _ans = [];

  List<String> generateParenthesis(int n) {
    _n = n;
    _backtrack();
    return _ans;
  }

  void _backtrack() {
    // 对于一个「合法」的括号字符串组合 p，必然对于任何 0 <= i < len(p) 都有：
    // 子串 p[0..i] 中左括号的数量都大于或等于右括号的数量
    if (_left < _right || _left > _n || _right > _n) {
      return;
    }
    // 一个「合法」括号组合的左括号数量一定等于右括号数量
    if (_left == _n && _right == _n) {
      final sb = StringBuffer();
      sb.writeAll(_path);
      _ans.add(sb.toString());
      return;
    }
    // edge = 取 '(', ')' 为值
    // 使用『左括号』
    _path.add('(');
    ++_left;
    _backtrack();
    _path.removeLast();
    --_left;
    // 使用『右括号』
    _path.add(')');
    ++_right;
    _backtrack();
    _path.removeLast();
    --_right;
  }
}
// https://leetcode.cn/submissions/detail/377181373/
```

## 23. 合并 K 个升序链表

<https://leetcode-cn.com/problems/merge-k-sorted-lists/>

```dart
class Solution {
  ListNode? mergeKLists(List<ListNode?> lists) {
    return _mergeKLists(lists, 0, lists.length - 1);
  }

  ListNode? _mergeKLists(List<ListNode?> lists, int lo, int hi) {
    if (lo > hi) {
      return null;
    }
    if (lo == hi) {
      return lists[lo];
    }
    final mid = lo + (hi - lo) ~/ 2;
    final left = _mergeKLists(lists, lo, mid);
    final right = _mergeKLists(lists, mid + 1, hi);
    return _mergeTwoLists(left, right);
  }

  ListNode? _mergeTwoLists(ListNode? list1, ListNode? list2) {
    final dummyHead = ListNode();
    var ptr = dummyHead;
    while (list1 != null && list2 != null) {
      if (list1.val < list2.val) {
        ptr.next = list1;
        list1 = list1.next;
      } else {
        ptr.next = list2;
        list2 = list2.next;
      }
      ptr = ptr.next!;
    }
    ptr.next = (list1 ?? list2);
    return dummyHead.next;
  }
}
// https://leetcode.cn/submissions/detail/378312052/
```

## 24. 两两交换链表中的节点

<https://leetcode-cn.com/problems/swap-nodes-in-pairs/>

```dart
class Solution {
  ListNode? swapPairs(ListNode? head) {
    if (head == null || head.next == null) {
      return head;
    }
    final x = head;
    final y = head.next;
    final z = head.next!.next;
    y!.next = x;
    x.next = swapPairs(z);
    return y;
  }
}
// https://leetcode.cn/submissions/detail/378303619/
```

## 25. K 个一组翻转链表

<https://leetcode.cn/problems/reverse-nodes-in-k-group/>

```dart
class Solution {
  ListNode? reverseKGroup(ListNode? head, int k) {
    if (head == null || head.next == null) {
      return head;
    }
    ListNode? ptr = head;
    for (var i = 1; i <= k - 1; ++i) {
      ptr = ptr!.next;
      if (ptr == null) {
        return head;
      }
    }
    final nextGroup = ptr!.next;
    ptr.next = null;
    final reverseHead = _reverseList(head);
    head.next = reverseKGroup(nextGroup, k);
    return reverseHead;
  }

  ListNode? _reverseList(ListNode? head) {
    ListNode? reverseHead;
    while (head != null) {
      final x = head.next;
      head.next = reverseHead;
      reverseHead = head;
      head = x;
    }
    return reverseHead;
  }
}
// https://leetcode.cn/submissions/detail/378279688/
```

## 26. 删除有序数组中的重复项

<https://leetcode.cn/problems/remove-duplicates-from-sorted-array/>

```dart
class Solution {
  int removeDuplicates(List<int> nums) {
    // [0..i-1] 不重复元素区间
    // [i..j-1] 重复元素区间
    // [j..n-1] 遍历区间
    var i = 0;
    var j = 0;
    final n = nums.length;
    while (j < n) {
      while (j + 1 < n && nums[j] == nums[j + 1]) {
        ++j;
      }
      _swap(nums, i++, j++);
    }
    return i;
  }

  void _swap(List<int> nums, int i, int j) {
    final temp = nums[i];
    nums[i] = nums[j];
    nums[j] = temp;
  }
}
// https://leetcode.cn/submissions/detail/377803743/
```

## 27. 移除元素

<https://leetcode.cn/problems/remove-element/>

```dart
class Solution {
  int removeElement(List<int> nums, int val) {
    // nums[0..i-1]   数值不等于 val 的元素区间
    // nums[i..j]     遍历区间
    // nums[j+1..n-1] 数值等于 val 的元素区间
    var i = 0;
    var j = nums.length - 1;
    while (i <= j) {
      while (i <= j && nums[i] != val) {
        ++i;
      }
      while (i <= j && nums[j] == val) {
        --j;
      }
      if (i <= j) {
        _swap(nums, i++, j--);
      }
    }
    return i;
  }

  void _swap(List<int> nums, int i, int j) {
    final temp = nums[i];
    nums[i] = nums[j];
    nums[j] = temp;
  }
}
// https://leetcode.cn/submissions/detail/377811197/
```

## 28. 实现 strStr()

<https://leetcode.cn/problems/implement-strstr/>

```dart

```

## 33. 搜索旋转排序数组

<https://leetcode.cn/problems/search-in-rotated-sorted-array/>

```dart
class Solution {
  int search(List<int> nums, int target) {
    var lo = 0;
    var hi = nums.length - 1;
    while (lo <= hi) {
      final mid = lo + (hi - lo) ~/ 2;
      if (nums[mid] == target) {
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
  }
}
// https://leetcode.cn/submissions/detail/376149140/
```

## 34. 在排序数组中查找元素的第一个和最后一个位置

<https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/>

```dart
class Solution {
  List<int> searchRange(List<int> nums, int target) {
    return [_search(nums, target, true), _search(nums, target, false)];
  }

  int _search(List<int> nums, int target, bool lower) {
    var res = -1;
    var lo = 0;
    var hi = nums.length - 1;
    while (lo <= hi) {
      final mid = lo + (hi - lo) ~/ 2;
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
  }
}
// https://leetcode.cn/submissions/detail/377820190/
```

## 37. 解数独

<https://leetcode.cn/problems/sudoku-solver/>

```dart
class Solution {
  void solveSudoku(List<List<String>> board) {
    _backtrack(board, 0, -1);
  }

  // 遍历『决策森林』
  // tree  = row
  // level = (row, col)
  bool _backtrack(List<List<String>> board, int row, int col) {
    var res = false;
    final n = board.length;
    if (row == n) {
      res = true;
    } else if (col == n - 1) {
      // 遍历下一棵『决策树』
      res = _backtrack(board, row + 1, -1);
    } else if (board[row][col + 1] != '.') {
      res = _backtrack(board, row, col + 1);
    } else {
      // edge = ['1'..'9']
      for (var i = 1; i <= 9; ++i) {
        final ch = i.toString();
        if (_isValid(board, row, col + 1, ch)) {
          board[row][col + 1] = ch;
          res = _backtrack(board, row, col + 1);
          if (res) {
            break;
          }
          board[row][col + 1] = '.';
        }
      }
    }
    return res;
  }

  // board[row][col] 填入数字 ch 是否有效
  bool _isValid(List<List<String>> board, int row, int col, String ch) {
    final n = board.length;
    for (var i = 0; i < n; ++i) {
      // 同一行
      if (board[row][i] == ch) {
        return false;
      }
      // 同一列
      if (board[i][col] == ch) {
        return false;
      }
      // 同九宫
      if (board[(row ~/ 3) * 3 + i ~/ 3][(col ~/ 3) * 3 + i % 3] == ch) {
        return false;
      }
    }
    return true;
  }
}
// https://leetcode.cn/submissions/detail/377028199/
```

## 39. 组合总和

<https://leetcode.cn/problems/combination-sum/>

```dart
class Solution {
  int _pathSum = 0;
  late final int _target;
  late final List<int> _nums;
  late final List<int> _path = []; // 取 nums[edge] 为元素
  late final List<List<int>> _ans = [];

  List<List<int>> combinationSum(List<int> candidates, int target) {
    _nums = candidates;
    _target = target;
    _backtrack(-1);
    return _ans;
  }

  // edge = 取数组 nums 的索引为值
  void _backtrack(int edge) {
    if (_pathSum == _target) {
      _ans.add(List<int>.of(_path));
      return;
    }
    if (edge == -1) {
      edge = 0;
    }
    // 避免重复，从 edge 开始选择
    // 例如 [1->2] 和 [2->1] 是重复的
    while (edge < _nums.length) {
      final x = _nums[edge];
      if (_pathSum + x <= _target) {
        _pathSum += x;
        _path.add(x);
        _backtrack(edge);
        _pathSum -= x;
        _path.removeLast();
      }
      ++edge;
    }
  }
}
// https://leetcode.cn/submissions/detail/376925810/
```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```dart
class Solution {
  int _pathSum = 0;
  late final int _target;
  late final List<int> _nums;
  late final List<int> _path = []; // 取 nums[edge] 为元素
  late final List<List<int>> _ans = [];

  List<List<int>> combinationSum2(List<int> candidates, int target) {
    _nums = candidates;
    _target = target;
    _nums.sort();
    _backtrack(-1);
    return _ans;
  }

  // edge = 取数组 nums 的索引为值
  void _backtrack(int edge) {
    if (_pathSum == _target) {
      _ans.add(List<int>.of(_path));
      return;
    }
    var prev = -1;
    // 避免重复，从 edge + 1 开始选择
    // 例如 [1->2] 和 [2->1] 是重复的
    while (++edge < _nums.length) {
      final x = _nums[edge];
      if (x != prev && _pathSum + x <= _target) {
        prev = x;
        _pathSum += x;
        _path.add(x);
        _backtrack(edge);
        _pathSum -= x;
        _path.removeLast();
      }
    }
  }
}
// https://leetcode.cn/submissions/detail/376927180/
```

## 42. 接雨水

<https://leetcode.cn/problems/trapping-rain-water/>

```dart
class Solution {
    public int trap(int[] height) {
        int n = height.length;
        // leftMax[i] = max(height[0..i])
        int[] leftMax = new int[n];
        leftMax[0] = height[0];
        for (int i = 1; i <= n - 1; ++i) {
            leftMax[i] = Math.max(height[i], leftMax[i - 1]);
        }
        // rightMax[i] = max(height[i..n-1])
        int[] rightMax = new int[n];
        rightMax[n - 1] = height[n - 1];
        for (int i = n - 2; i >= 0; --i) {
            rightMax[i] = Math.max(height[i], rightMax[i + 1]);
        }
        int sum = 0;
        for (int i = 0; i < n; ++i) {
            sum += Math.min(leftMax[i], rightMax[i]) - height[i];
        }
        return sum;
    }
}
// https://leetcode.cn/submissions/detail/365499343/
```

## 46. 全排列

<https://leetcode.cn/problems/permutations/>

```dart
class Solution {
  late final List<int> _nums;
  late final List<bool> _marked;
  late final List<int> _path = []; // 取 nums[edge] 为元素
  late final List<List<int>> _ans = [];

  List<List<int>> permute(List<int> nums) {
    _nums = nums;
    _marked = List<bool>.filled(_nums.length, false);
    _backtrack();
    return _ans;
  }

  void _backtrack() {
    final n = _nums.length;
    if (_path.length == n) {
      _ans.add(List<int>.of(_path));
      return;
    }
    // edge = 取数组 nums 的索引为值
    for (var edge = 0; edge < n; ++edge) {
      if (!_marked[edge]) {
        _path.add(_nums[edge]);
        _marked[edge] = true;
        _backtrack();
        _path.removeLast();
        _marked[edge] = false;
      }
    }
  }
}
// https://leetcode.cn/submissions/detail/376921744/
```

## 47. 全排列 II

<https://leetcode.cn/problems/permutations-ii/>

```dart
class Solution {
  late final List<int> _nums;
  late final List<bool> _marked;
  late final List<int> _path = []; // 取 nums[edge] 为元素
  late final List<List<int>> _ans = [];

  List<List<int>> permuteUnique(List<int> nums) {
    _nums = nums;
    _marked = List<bool>.filled(_nums.length, false);
    _nums.sort();
    _backtrack();
    return _ans;
  }

  void _backtrack() {
    final n = _nums.length;
    if (_path.length == n) {
      _ans.add(List<int>.of(_path));
      return;
    }
    var prev = -11;
    // edge = 取数组 nums 的索引为值
    for (var edge = 0; edge < n; ++edge) {
      final x = _nums[edge];
      if (!_marked[edge] && x != prev) {
        prev = x;
        _path.add(x);
        _marked[edge] = true;
        _backtrack();
        _path.removeLast();
        _marked[edge] = false;
      }
    }
  }
}
// https://leetcode.cn/submissions/detail/376922796/
```

## 51. N 皇后

<https://leetcode.cn/problems/n-queens/>

```dart
class Solution {
  late final List<List<String>> _ans = [];

  List<List<String>> solveNQueens(int n) {
    final board = List.generate(n, (_) => List.filled(n, '.'));
    _backtrack(board, -1);
    return _ans;
  }

  // level = row
  void _backtrack(List<List<String>> board, int row) {
    final n = board.length;
    if (row == n - 1) {
      final strs = <String>[];
      for (final chs in board) {
        final sb = StringBuffer();
        sb.writeAll(chs);
        strs.add(sb.toString());
      }
      _ans.add(strs);
      return;
    }
    // edge = col
    for (var col = 0; col < n; ++col) {
      if (_isValid(board, row + 1, col)) {
        board[row + 1][col] = 'Q';
        _backtrack(board, row + 1);
        board[row + 1][col] = '.';
      }
    }
  }

  // board[row][col] 放置 Q 是否有效
  bool _isValid(List<List<String>> board, int row, int col) {
    final n = board.length;
    // 同一列
    for (var r = row - 1; r >= 0; --r) {
      if (board[r][col] == 'Q') {
        return false;
      }
    }
    // 右斜线
    for (var r = row - 1, c = col - 1; r >= 0 && c >= 0; --r, --c) {
      if (board[r][c] == 'Q') {
        return false;
      }
    }
    // 左斜线
    for (var r = row - 1, c = col + 1; r >= 0 && c < n; --r, ++c) {
      if (board[r][c] == 'Q') {
        return false;
      }
    }
    return true;
  }
}
// https://leetcode.cn/submissions/detail/377035352/
```

## 52. N 皇后 II

<https://leetcode.cn/problems/n-queens-ii/>

```dart
class Solution {
  int _ans = 0;

  int totalNQueens(int n) {
    final board = List.generate(n, (_) => List.filled(n, '.'));
    _backtrack(board, -1);
    return _ans;
  }

  // level = row
  void _backtrack(List<List<String>> board, int row) {
    final n = board.length;
    if (row == n - 1) {
      ++_ans;
      return;
    }
    // edge = col
    for (var col = 0; col < n; ++col) {
      if (_isValid(board, row + 1, col)) {
        board[row + 1][col] = 'Q';
        _backtrack(board, row + 1);
        board[row + 1][col] = '.';
      }
    }
  }

  // board[row][col] 放置 Q 是否有效
  bool _isValid(List<List<String>> board, int row, int col) {
    final n = board.length;
    // 同一列
    for (var r = row - 1; r >= 0; --r) {
      if (board[r][col] == 'Q') {
        return false;
      }
    }
    // 右斜线
    for (var r = row - 1, c = col - 1; r >= 0 && c >= 0; --r, --c) {
      if (board[r][c] == 'Q') {
        return false;
      }
    }
    // 左斜线
    for (var r = row - 1, c = col + 1; r >= 0 && c < n; --r, ++c) {
      if (board[r][c] == 'Q') {
        return false;
      }
    }
    return true;
  }
}
// https://leetcode.cn/submissions/detail/377036254/
```

## 53. 最大子数组和

<https://leetcode.cn/problems/maximum-subarray/>

```dart
class Solution {
  int maxSubArray(List<int> nums) {
    final n = nums.length;
    // dp[i] = max({sum(subarray) | subarray 是以 nums[i] 结尾的子数组})
    final dp = List<int>.filled(n + 1, 0);
    dp[0] = nums[0];
    var ans = dp[0];
    for (var i = 1; i < n; ++i) {
      dp[i] = max(nums[i], dp[i - 1] + nums[i]);
      ans = max(ans, dp[i]);
    }
    return ans;
  }
}
// https://leetcode.cn/submissions/detail/376517250/
```

## 56. 合并区间

<https://leetcode.cn/problems/merge-intervals/>

```dart
class Solution {
  List<List<int>> merge(List<List<int>> intervals) {
    intervals.sort((a, b) => a[0] == b[0] ? b[1] - a[1] : a[0] - b[0]);
    final ans = <List<int>>[];
    var mStart = intervals[0][0];
    var mEnd = intervals[0][1];
    for (var i = 1; i < intervals.length; ++i) {
      final start = intervals[i][0];
      final end = intervals[i][1];
      if (start <= mEnd) {
        // 重叠
        mEnd = max(mEnd, end);
      } else {
        // 不重叠
        ans.add([mStart, mEnd]);
        mStart = start;
        mEnd = end;
      }
    }
    ans.add([mStart, mEnd]);
    return ans;
  }
}
// https://leetcode.cn/submissions/detail/376156566/
```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```dart
class Solution {
  late final List<List<int>> _memo;

  int minPathSum(List<List<int>> grid) {
    final m = grid.length;
    final n = grid[0].length;
    _memo = List.generate(m, (_) => List.filled(n, -1));
    return _minPathSum(grid, m - 1, n - 1);
  }

  // 从 grid[0][0] 到 grid[row][col] 的最小路径和
  int _minPathSum(List<List<int>> grid, int row, int col) {
    if (row < 0 || col < 0) {
      return 20000;
    }
    if (row == 0 && col == 0) {
      return grid[row][col];
    }
    if (_memo[row][col] == -1) {
      final sp1 = _minPathSum(grid, row - 1, col); // 上
      final sp2 = _minPathSum(grid, row, col - 1); // 左
      _memo[row][col] = min(sp1, sp2) + grid[row][col];
    }
    return _memo[row][col];
  }
}
// https://leetcode.cn/submissions/detail/376905428/
```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```dart
class Solution {
  int mySqrt(int x) {
    if (x == 0) {
      return 0;
    }
    var lo = 1;
    var hi = x;
    while (true) {
      final mid = lo + (hi - lo) ~/ 2;
      if (mid <= x ~/ mid && (mid + 1) > x ~/ (mid + 1)) {
        return mid;
      }
      if (mid < x ~/ mid) {
        lo = mid + 1;
      } else {
        hi = mid - 1;
      }
    }
    return -1;
  }
}
// https://leetcode.cn/submissions/detail/377814425/
```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```dart
class Solution {
  int climbStairs(int n) {
    if (n == 1) {
      return 1;
    }
    if (n == 2) {
      return 2;
    }
    // dp[i] = 楼梯有 i 阶时，有几种不同的方法
    final dp = List.filled(n + 1, 0);
    dp[1] = 1;
    dp[2] = 2;
    for (var i = 3; i <= n; ++i) {
      dp[i] = dp[i - 1] + dp[i - 2];
    }
    return dp[n];
  }
}
// https://leetcode.cn/submissions/detail/377153933/
```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```dart
class Solution {
  late final List<List<int>> _memo;

  int minDistance(String s1, String s2) {
    final n1 = s1.length;
    final n2 = s2.length;
    _memo = List.generate(n1, (_) => List.filled(n2, -1));
    return _minDistance(s1, n1 - 1, s2, n2 - 1);
  }

  // 子串 s1[0..i] s2[0..j] 的最小编辑距离
  int _minDistance(String s1, int i, String s2, int j) {
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
    if (_memo[i][j] == -1) {
      if (s1.codeUnitAt(i) == s2.codeUnitAt(j)) {
        // s1[0..i-1][i]
        // s2[0..j-1][j]
        _memo[i][j] = _minDistance(s1, i - 1, s2, j - 1);
      } else {
        // 替换 s1[i] 为 s2[j]
        // s1[0..i-1][i]
        // s2[0..j-1][j]
        final sp1 = _minDistance(s1, i - 1, s2, j - 1) + 1;
        // 插入 s2[j] 到 s1
        // s1[0..i]
        // s2[0..j-1][j]
        final sp2 = _minDistance(s1, i, s2, j - 1) + 1;
        // 删除 s1[i]
        // s1[0..i-1][i]
        // s2[0..j]
        final sp3 = _minDistance(s1, i - 1, s2, j) + 1;
        _memo[i][j] = min(min(sp1, sp2), sp3);
      }
    }
    return _memo[i][j];
  }
}
// https://leetcode.cn/submissions/detail/376601684/
```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```dart

```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```dart
import 'dart:collection';

class Solution {
  String minWindow(String s, String t) {
    final need = HashMap<String, int>();
    for (var i = 0; i < t.length; ++i) {
      need.update(t[i], (val) => val + 1, ifAbsent: () => 1);
    }
    final window = HashMap<String, int>();
    var valid = 0;
    var start = 0;
    var len = pow(10, 5).toInt();
    // s[left..right) = Window Substring
    // s[right..n-1]  = Scanning
    var left = 0;
    var right = 0;
    while (right < s.length) {
      final c = s[right++];
      if (need.containsKey(c)) {
        window.update(c, (val) => val + 1, ifAbsent: () => 1);
        if (window[c] == need[c]) {
          ++valid;
        }
      }
      if (valid == need.length) {
        while (left < right) {
          final d = s[left];
          if (need.containsKey(d) && window[d] == need[d]) {
            break;
          }
          if (need.containsKey(d)) {
            window.update(d, (val) => val - 1);
          }
          ++left;
        }
        if (right - left < len) {
          start = left;
          len = right - left;
        }
      }
    }
    return len == pow(10, 5).toInt() ? '' : s.substring(start, start + len);
  }
}
// https://leetcode.cn/submissions/detail/378515443/
```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```dart
class Solution {
  late final int _n;
  late final int _k;
  late final List<int> _path = []; // 取 [1..n] 为元素
  late final List<List<int>> _ans = [];

  List<List<int>> combine(int n, int k) {
    _n = n;
    _k = k;
    _backtrack(0);
    return _ans;
  }

  // edge = 取 [1..n] 为值
  void _backtrack(int edge) {
    if (_path.length == _k) {
      _ans.add(List<int>.of(_path));
      return;
    }
    // 避免重复，从 edge + 1 开始选择
    // 例如 [1->2] 和 [2->1] 是重复的
    while (++edge <= _n) {
      _path.add(edge);
      _backtrack(edge);
      _path.removeLast();
    }
  }
}
// https://leetcode.cn/submissions/detail/376920083/
```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```dart
class Solution {
  late final List<int> _nums;
  late final List<int> _path = []; // 取 nums[edge] 为元素
  late final List<List<int>> _ans = [];

  List<List<int>> subsets(List<int> nums) {
    _nums = nums;
    _backtrack(-1);
    return _ans;
  }

  // edge = 取数组 nums 的索引为值
  void _backtrack(int edge) {
    _ans.add(List<int>.of(_path));
    // 避免重复，从 edge + 1 开始选择
    // 例如 [1->2] 和 [2->1] 是重复的
    while (++edge < _nums.length) {
      _path.add(_nums[edge]);
      _backtrack(edge);
      _path.removeLast();
    }
  }
}
// https://leetcode.cn/submissions/detail/376919789/
```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```dart
class Solution {
  bool search(List<int> nums, int target) {
    var lo = 0;
    var hi = nums.length - 1;
    while (lo <= hi) {
      final mid = lo + (hi - lo) ~/ 2;
      if (nums[mid] == target) {
        return true;
      }
      if (nums[lo] == nums[mid] && nums[mid] == nums[hi]) {
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
  }
}
// https://leetcode.cn/submissions/detail/376151285/
```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```dart
class Solution {
  ListNode? deleteDuplicates(ListNode? head) {
    var ptr = head;
    while (ptr != null && ptr.next != null) {
      if (ptr.val == ptr.next!.val) {
        ptr.next = ptr.next!.next;
      } else {
        ptr = ptr.next;
      }
    }
    return head;
  }
}
// https://leetcode.cn/submissions/detail/378382280/
```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```dart
class Solution {
  ListNode? partition(ListNode? head, int x) {
    final lessDummyHead = ListNode();
    var lessPtr = lessDummyHead;
    final greaterDummyHead = ListNode();
    var greaterPtr = greaterDummyHead;
    while (head != null) {
      if (head.val < x) {
        lessPtr.next = head;
        lessPtr = lessPtr.next!;
      } else {
        greaterPtr.next = head;
        greaterPtr = greaterPtr.next!;
      }
      head = head.next;
    }
    lessPtr.next = null;
    greaterPtr.next = null;
    lessPtr.next = greaterDummyHead.next;
    return lessDummyHead.next;
  }
}
// https://leetcode.cn/submissions/detail/378415346/
```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```dart
class Solution {
  late final List<int> _nums;
  late final List<int> _path = []; // 取 nums[edge] 为元素
  late final List<List<int>> _ans = [];

  List<List<int>> subsetsWithDup(List<int> nums) {
    _nums = nums;
    _nums.sort();
    _backtrack(-1);
    return _ans;
  }

  // edge = 取数组 nums 的索引为值
  void _backtrack(int edge) {
    _ans.add(List<int>.of(_path));
    var prev = -11;
    // 避免重复，从 edge + 1 开始选择
    // 例如 [1->2] 和 [2->1] 是重复的
    while (++edge < _nums.length) {
      final x = _nums[edge];
      if (x != prev) {
        prev = x;
        _path.add(x);
        _backtrack(edge);
        _path.removeLast();
      }
    }
  }
}
// https://leetcode.cn/submissions/detail/376919388/
```

## 92. 反转链表 II

<https://leetcode-cn.com/problems/reverse-linked-list-ii/>

```dart
class Solution {
  ListNode? reverseBetween(ListNode? head, int left, int right) {
    if (left == 1) {
      return _reverseList(head, right);
    }
    var ptr = head;
    for (var i = 1; i <= left - 2; ++i) {
      ptr = ptr!.next;
    }
    ptr!.next = _reverseList(ptr.next, right - left + 1);
    return head;
  }

  // 翻转链表的前 n 个节点，返回翻转后的头节点
  ListNode? _reverseList(ListNode? head, int n) {
    ListNode? reverseHead;
    var ptr = head;
    while (ptr != null && n > 0) {
      final x = ptr.next;
      ptr.next = reverseHead;
      reverseHead = ptr;
      ptr = x;
      --n;
    }
    head!.next = ptr;
    return reverseHead;
  }
}
// https://leetcode.cn/submissions/detail/378257975/
```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```dart
class Solution {
  late final List<int> _ans = [];

  List<int> inorderTraversal(TreeNode? root) {
    _dfs(root);
    return _ans;
  }

  void _dfs(TreeNode? root) {
    if (root == null) {
      return;
    }
    _dfs(root.left);
    _ans.add(root.val);
    _dfs(root.right);
  }
}
// https://leetcode.cn/submissions/detail/377311912/
```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```dart
class Solution {
  List<TreeNode?> generateTrees(int n) {
    return _generateTrees(1, n);
  }

  // 所有由 [lo..hi] 组成的节点值互不相同的不同二叉搜索树
  List<TreeNode?> _generateTrees(int lo, int hi) {
    if (lo > hi) {
      return [null];
    }
    final List<TreeNode?> res = [];
    // 根节点为 i
    // 左子树由 [lo..i-1] 组成
    // 右子树由 [i+1..hi] 组成
    for (var i = lo; i <= hi; ++i) {
      final left = _generateTrees(lo, i - 1);
      final right = _generateTrees(i + 1, hi);
      for (var l in left) {
        for (var r in right) {
          res.add(TreeNode(i, l, r));
        }
      }
    }
    return res;
  }
}
// https://leetcode.cn/submissions/detail/377322499/
```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```dart
import 'dart:collection';

class Solution {
  late final Map<int, int> _memo = HashMap();

  // 由 n 个不同数字 x_1 < x_2 < ... < x_n
  // 组成的节点值互不相同的二叉搜索树的种数
  int numTrees(int n) {
    if (n == 0 || n == 1) {
      return 1;
    }
    if (!_memo.containsKey(n)) {
      var res = 0;
      // 根节点为 x_i
      // 左子树由 i-1 个数字 x1 < x2 < ... < x_i-1 组成
      // 右子树由 n-i 个数字 x_i+1 < x_i+2 < ... < x_n 组成
      for (var i = 1; i <= n; ++i) {
        res += numTrees(i - 1) * numTrees(n - i);
      }
      _memo[n] = res;
    }
    return _memo[n]!;
  }
}
// https://leetcode.cn/submissions/detail/377316813/
```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```dart
class Solution {
  bool _ans = true;

  bool isValidBST(TreeNode? root) {
    _checkLowerAndUpperBound(root, null, null);
    return _ans;
  }

  // 检查二叉树是否在区间 (lower, upper) 内，递归过程中确定是否满足二叉搜索树的性质
  bool _checkLowerAndUpperBound(TreeNode? root, int? lower, int? upper) {
    if (root == null) {
      return true;
    }
    if (lower != null && root.val <= lower) {
      _ans = false;
      return false;
    }
    if (upper != null && root.val >= upper) {
      _ans = false;
      return false;
    }
    return _checkLowerAndUpperBound(root.left, lower, root.val) &&
        _checkLowerAndUpperBound(root.right, root.val, upper);
  }
}
// https://leetcode.cn/submissions/detail/378378622/
```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```dart
class Solution {
  bool isSameTree(TreeNode? p, TreeNode? q) {
    if (p == null && q == null) {
      return true;
    }
    if (p == null || q == null || p.val != q.val) {
      return false;
    }
    return isSameTree(p.left, q.left) && isSameTree(p.right, q.right);
  }
}
// https://leetcode.cn/submissions/detail/377208347/
```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```dart
import 'dart:collection';

class Solution {
  List<List<int>> levelOrder(TreeNode? root) {
    final ans = <List<int>>[];
    final queue = Queue<TreeNode>();
    if (root != null) {
      queue.addLast(root);
    }
    while (queue.isNotEmpty) {
      final level = <int>[];
      final n = queue.length;
      for (var i = 0; i < n; ++i) {
        final x = queue.removeFirst();
        level.add(x.val);
        final left = x.left;
        if (left != null) {
          queue.addLast(left);
        }
        final right = x.right;
        if (right != null) {
          queue.addLast(right);
        }
      }
      ans.add(level);
    }
    return ans;
  }
}
// https://leetcode.cn/submissions/detail/377329906/
```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```dart
import 'dart:collection';

class Solution {
  List<List<int>> zigzagLevelOrder(TreeNode? root) {
    final ans = <List<int>>[];
    final queue = Queue<TreeNode>();
    if (root != null) {
      queue.addLast(root);
    }
    var reverse = false;
    while (queue.isNotEmpty) {
      final level = <int>[];
      final n = queue.length;
      for (var i = 0; i < n; ++i) {
        final x = queue.removeFirst();
        if (reverse) {
          level.insert(0, x.val);
        } else {
          level.add(x.val);
        }
        final left = x.left;
        if (left != null) {
          queue.addLast(left);
        }
        final right = x.right;
        if (right != null) {
          queue.addLast(right);
        }
      }
      ans.add(level);
      reverse = !reverse;
    }
    return ans;
  }
}
// https://leetcode.cn/submissions/detail/377507542/
```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```dart
class Solution {
  int maxDepth(TreeNode? root) {
    if (root == null) {
      return 0;
    }
    return 1 + max(maxDepth(root.left), maxDepth(root.right));
  }
}
// https://leetcode.cn/submissions/detail/377209045/
```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```dart
import 'dart:collection';

class Solution {
  late final Map<int, int> _valToIndex = HashMap();

  TreeNode? buildTree(List<int> preorder, List<int> inorder) {
    for (var i = 0; i < inorder.length; ++i) {
      _valToIndex[inorder[i]] = i;
    }
    return _buildTree(
        preorder, 0, preorder.length - 1, inorder, 0, inorder.length - 1);
  }

  TreeNode? _buildTree(List<int> preorder, int preStart, int preEnd,
      List<int> inorder, int inStart, int inEnd) {
    if (preStart > preEnd) {
      return null;
    }
    final rootVal = preorder[preStart];
    final index = _valToIndex[rootVal]!;
    final leftSize = index - inStart;
    final root = TreeNode(rootVal);
    root.left = _buildTree(preorder, preStart + 1, preStart + leftSize, inorder,
        inStart, index - 1);
    root.right = _buildTree(
        preorder, preStart + leftSize + 1, preEnd, inorder, index + 1, inEnd);
    return root;
  }
}
// https://leetcode.cn/submissions/detail/377515375/
```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```dart
import 'dart:collection';

class Solution {
  late final Map<int, int> _valToIndex = HashMap();

  TreeNode? buildTree(List<int> inorder, List<int> postorder) {
    for (var i = 0; i < inorder.length; ++i) {
      _valToIndex[inorder[i]] = i;
    }
    return _buildTree(
        inorder, 0, inorder.length - 1, postorder, 0, postorder.length - 1);
  }

  TreeNode? _buildTree(List<int> inorder, int inStart, int inEnd,
      List<int> postorder, int postStart, int postEnd) {
    if (inStart > inEnd) {
      return null;
    }
    final rootVal = postorder[postEnd];
    final index = _valToIndex[rootVal]!;
    final leftSize = index - inStart;
    final root = TreeNode(rootVal);
    root.left = _buildTree(inorder, inStart, index - 1, postorder, postStart,
        postStart + leftSize - 1);
    root.right = _buildTree(inorder, index + 1, inEnd, postorder,
        postStart + leftSize, postEnd - 1);
    return root;
  }
}
// https://leetcode.cn/submissions/detail/377518529/
```

## 107. 二叉树的层序遍历 II

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```dart
import 'dart:collection';

class Solution {
  List<List<int>> levelOrderBottom(TreeNode? root) {
    final ans = <List<int>>[];
    final queue = Queue<TreeNode>();
    if (root != null) {
      queue.addLast(root);
    }
    while (queue.isNotEmpty) {
      final level = <int>[];
      final n = queue.length;
      for (var i = 0; i < n; ++i) {
        final x = queue.removeFirst();
        level.add(x.val);
        final left = x.left;
        if (left != null) {
          queue.addLast(left);
        }
        final right = x.right;
        if (right != null) {
          queue.addLast(right);
        }
      }
      ans.insert(0, level);
    }
    return ans;
  }
}
// https://leetcode.cn/submissions/detail/377505347/
```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```dart
class Solution {
  TreeNode? sortedArrayToBST(List<int> nums) {
    return _sortedArrayToBST(nums, 0, nums.length - 1);
  }

  // 将有序子数组 nums[lo..hi] 转换为二叉搜索树
  TreeNode? _sortedArrayToBST(List<int> nums, int lo, int hi) {
    if (lo > hi) {
      return null;
    }
    final mid = lo + (hi - lo) ~/ 2;
    final root = TreeNode(nums[mid]);
    root.left = _sortedArrayToBST(nums, lo, mid - 1);
    root.right = _sortedArrayToBST(nums, mid + 1, hi);
    return root;
  }
}
// https://leetcode.cn/submissions/detail/377227806/
```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```dart
class Solution {
  bool _ans = true;

  bool isBalanced(TreeNode? root) {
    _height(root);
    return _ans;
  }

  int _height(TreeNode? root) {
    if (root == null) {
      return -1;
    }
    final left = _height(root.left);
    final right = _height(root.right);
    if ((left - right).abs() > 1) {
      _ans = false;
    }
    return 1 + max(left, right);
  }
}
// https://leetcode.cn/submissions/detail/377226421/
```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```dart
import 'dart:collection';

class Solution {
  int minDepth(TreeNode? root) {
    final queue = Queue<TreeNode>();
    if (root != null) {
      queue.addLast(root);
    }
    var depth = 0;
    while (queue.isNotEmpty) {
      ++depth;
      final n = queue.length;
      for (var i = 0; i < n; ++i) {
        final x = queue.removeFirst();
        final left = x.left;
        final right = x.right;
        if (left == null && right == null) {
          return depth;
        }
        if (left != null) {
          queue.addLast(left);
        }
        if (right != null) {
          queue.addLast(right);
        }
      }
    }
    return 0;
  }
}
// https://leetcode.cn/submissions/detail/377683928/
```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```dart
class Solution {
  int _pathSum = 0;
  late final int _targetSum;

  bool hasPathSum(TreeNode? root, int targetSum) {
    _targetSum = targetSum;
    if (root != null) {
      _pathSum += root.val;
      if (_backtrack(root)) {
        return true;
      }
      _pathSum -= root.val;
    }
    return false;
  }

  bool _backtrack(TreeNode root) {
    final left = root.left;
    final right = root.right;
    if (left == null && right == null) {
      return _pathSum == _targetSum;
    }
    if (left != null) {
      _pathSum += left.val;
      if (_backtrack(left)) {
        return true;
      }
      _pathSum -= left.val;
    }
    if (right != null) {
      _pathSum += right.val;
      if (_backtrack(right)) {
        return true;
      }
      _pathSum -= right.val;
    }
    return false;
  }
}
// https://leetcode.cn/submissions/detail/377194086/
```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```dart
class Solution {
  void flatten(TreeNode? root) {
    if (root == null) {
      return;
    }
    flatten(root.left);
    flatten(root.right);
    final left = root.left;
    final right = root.right;
    root.left = null;
    root.right = left;
    var ptr = root;
    while (ptr.right != null) {
      ptr = ptr.right!;
    }
    ptr.right = right;
  }
}
// https://leetcode.cn/submissions/detail/377212736/
```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```dart

```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```dart
class Solution {
  int maxProfit(List<int> prices) {
    final n = prices.length;
    // dp[i][0] = 第 i 天，空仓状态下的最大利润
    // dp[i][1] = 第 i 天，持仓状态下的最大利润
    final dp = List.generate(n, (_) => List.filled(2, 0));
    dp[0][0] = 0;
    dp[0][1] = -prices[0];
    for (var i = 1; i < n; ++i) {
      // dp[i - 1][0]             >= -prices[i]
      // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
      // => dp[i][0] >= dp[i][1]
      dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
      dp[i][1] = max(-prices[i], dp[i - 1][1]);
    }
    return dp[n - 1][0];
  }
}
// https://leetcode.cn/submissions/detail/376687275/
```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```dart
class Solution {
  int maxProfit(List<int> prices) {
    final n = prices.length;
    // dp[i][0] = 第 i 天，空仓状态下的最大利润
    // dp[i][1] = 第 i 天，持仓状态下的最大利润
    final dp = List.generate(n, (_) => List.filled(2, 0));
    dp[0][0] = 0;
    dp[0][1] = -prices[0];
    for (var i = 1; i < n; ++i) {
      // dp[i - 1][0]             >= dp[i - 1][0] - prices[i]
      // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
      // => dp[i][0] >= dp[i][1]
      dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
      dp[i][1] = max(dp[i - 1][0] - prices[i], dp[i - 1][1]);
    }
    return dp[n - 1][0];
  }
}
// https://leetcode.cn/submissions/detail/376686786/
```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```dart
class Solution {
  int maxProfit(List<int> prices) {
    return _maxProfit(2, prices);
  }

  int _maxProfit(int k, List<int> prices) {
    final n = prices.length;
    if (k <= 0 || n <= 1) {
      return 0;
    }
    // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
    // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
    final dp =
        List.generate(k + 1, (_) => List.generate(n, (_) => List.filled(2, 0)));
    // 交易次数限制为 0 时
    // 填写第 0 个 n x 2 矩阵
    for (var i = 0; i < n; ++i) {
      dp[0][i][0] = 0;
      dp[0][i][1] = -1000000;
    }
    // 交易次数限制为 [1..k] 时
    // 填写第 t 个 n x 2 矩阵
    for (var t = 1; t <= k; ++t) {
      dp[t][0][0] = 0;
      dp[t][0][1] = -prices[0];
      for (var i = 1; i < n; ++i) {
        // dp[t][i - 1][0]             >= dp[t - 1][i - 1][0] - prices[i]
        // dp[t][i - 1][1] + prices[i] >= dp[t][i - 1][1]
        // => dp[t][i][0] >= dp[t][i][1]
        dp[t][i][0] = max(dp[t][i - 1][0], dp[t][i - 1][1] + prices[i]);
        dp[t][i][1] = max(dp[t - 1][i - 1][0] - prices[i], dp[t][i - 1][1]);
      }
    }
    return dp[k][n - 1][0];
  }
}
// https://leetcode.cn/submissions/detail/376692047/
```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```dart
class Solution {
  bool isPalindrome(String s) {
    final t = s
        .toLowerCase()
        .codeUnits
        .where((x) => (48 <= x && x <= 57) || (97 <= x && x <= 122))
        .toList();
    var i = 0;
    var j = t.length - 1;
    while (i < j) {
      if (t[i++] != t[j--]) {
        return false;
      }
    }
    return true;
  }
}
// https://leetcode.cn/submissions/detail/378006834/
```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```dart
import 'dart:collection';

class Solution {
  int longestConsecutive(List<int> nums) {
    var ans = 0;
    final numSet = HashSet<int>.of(nums);
    for (final x in nums) {
      if (numSet.contains(x)) {
        var lo = x - 1;
        while (numSet.contains(lo)) {
          numSet.remove(lo--);
        }
        var hi = x + 1;
        while (numSet.contains(hi)) {
          numSet.remove(hi++);
        }
        ans = max(ans, hi - lo - 1);
        numSet.remove(x);
      }
    }
    return ans;
  }
}
// https://leetcode.cn/submissions/detail/378439302/
```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```dart
// 1254. 统计封闭岛屿的数目
// https://leetcode.cn/problems/number-of-closed-islands/
import 'dart:collection';

class Solution {
  static const LAND = 'O';
  static const WATER = 'X';
  bool _mark = false;
  late final _recovery = HashSet<int>();

  void solve(List<List<String>> grid) {
    final m = grid.length;
    final n = grid[0].length;
    _mark = true;
    // 淹没与左右边界的陆地相连的岛屿
    for (var row = 0; row < m; ++row) {
      _floodFill(grid, row, 0);
      _floodFill(grid, row, n - 1);
    }
    // 淹没与上下边界的陆地相连的岛屿
    for (var col = 0; col < n; ++col) {
      _floodFill(grid, 0, col);
      _floodFill(grid, m - 1, col);
    }
    _mark = false;
    // 淹没封闭岛屿
    for (var row = 0; row < m; ++row) {
      for (var col = 0; col < n; ++col) {
        if (grid[row][col] == LAND) {
          _floodFill(grid, row, col);
        }
      }
    }
    // 重建原来与边界陆地相连的岛屿
    _recovery.forEach((x) {
      final row = x ~/ n;
      final col = x % n;
      grid[row][col] = LAND;
    });
  }

  void _floodFill(List<List<String>> grid, int row, int col) {
    final m = grid.length;
    final n = grid[0].length;
    if (row < 0 || row >= m || col < 0 || col >= n || grid[row][col] == WATER) {
      return;
    }
    if (_mark) {
      _recovery.add(row * n + col);
    }
    grid[row][col] = WATER;
    _floodFill(grid, row - 1, col);
    _floodFill(grid, row + 1, col);
    _floodFill(grid, row, col - 1);
    _floodFill(grid, row, col + 1);
  }
}
// Stack Overflow https://leetcode.cn/submissions/detail/377646750/ 2943
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
class Solution {
  void reorderList(ListNode? head) {
    var slow = head;
    var fast = head;
    while (fast!.next != null && fast.next!.next != null) {
      slow = slow!.next;
      fast = fast.next!.next;
    }
    var reverseHead = _reverseList(slow!.next);
    slow.next = null;
    var ptr = ListNode();
    while (head != null) {
      ptr.next = head;
      ptr = ptr.next!;
      head = head.next;
      if (reverseHead != null) {
        ptr.next = reverseHead;
        ptr = ptr.next!;
        reverseHead = reverseHead.next;
      }
    }
  }

  ListNode? _reverseList(ListNode? head) {
    ListNode? reverseHead;
    while (head != null) {
      final x = head.next;
      head.next = reverseHead;
      reverseHead = head;
      head = x;
    }
    return reverseHead;
  }
}
// https://leetcode.cn/submissions/detail/378296753/
```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```dart
class Solution {
  late final List<int> _ans = [];

  List<int> preorderTraversal(TreeNode? root) {
    _dfs(root);
    return _ans;
  }

  void _dfs(TreeNode? root) {
    if (root == null) {
      return;
    }
    _ans.add(root.val);
    _dfs(root.left);
    _dfs(root.right);
  }
}
// https://leetcode.cn/submissions/detail/377325777/
```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```dart
class Solution {
  late final List<int> _ans = [];

  List<int> postorderTraversal(TreeNode? root) {
    _dfs(root);
    return _ans;
  }

  void _dfs(TreeNode? root) {
    if (root == null) {
      return;
    }
    _dfs(root.left);
    _dfs(root.right);
    _ans.add(root.val);
  }
}
// https://leetcode.cn/submissions/detail/377323768/
```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```dart

```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```dart
class Solution {
  int findMin(List<int> nums) {
    var lo = 0;
    var hi = nums.length - 1;
    while (lo < hi) {
      final mid = lo + (hi - lo) ~/ 2;
      if (nums[mid] < nums[hi]) {
        hi = mid;
      } else {
        lo = mid + 1;
      }
    }
    return nums[lo];
  }
}
// https://leetcode.cn/submissions/detail/376142956/
```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```dart
import 'dart:collection';

class MinStack {
  late final _stack = Queue<List<int>>();

  MinStack();

  void push(int val) {
    final x = _stack.isEmpty ? val : min(getMin(), val);
    _stack.addLast([val, x]);
  }

  void pop() {
    _stack.removeLast();
  }

  int top() {
    return _stack.last[0];
  }

  int getMin() {
    return _stack.last[1];
  }
}
// https://leetcode.cn/submissions/detail/378432620/
```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```dart

```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```dart
class Solution {
  late final _DOT = '.'.codeUnitAt(0);
  late final _ZERO = '0'.codeUnitAt(0);

  int compareVersion(String version1, String version2) {
    final n1 = version1.length;
    final n2 = version2.length;
    var i = 0;
    var j = 0;
    while (i < n1 || j < n2) {
      var r1 = 0;
      while (i < n1) {
        final ch = version1.codeUnitAt(i++);
        if (ch == _DOT) {
          break;
        }
        r1 = r1 * 10 + (ch - _ZERO);
      }
      var r2 = 0;
      while (j < n2) {
        final ch = version2.codeUnitAt(j++);
        if (ch == _DOT) {
          break;
        }
        r2 = r2 * 10 + (ch - _ZERO);
      }
      if (r1 > r2) {
        return 1;
      }
      if (r1 < r2) {
        return -1;
      }
    }
    return 0;
  }
}
// https://leetcode.cn/submissions/detail/378388288/
```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```dart
class Solution {
  List<int> twoSum(List<int> numbers, int target) {
    final n = numbers.length;
    var i = 0;
    var j = n - 1;
    while (i < j) {
      final sum = numbers[i] + numbers[j];
      if (sum < target) {
        ++i;
      } else if (sum > target) {
        --j;
      } else {
        return [i + 1, j + 1];
      }
    }
    return [-1, -1];
  }
}
// https://leetcode.cn/submissions/detail/377991574/
```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```dart
class Solution {
  int majorityElement(List<int> nums) {
    var candidate = 0;
    var count = 0;
    for (final x in nums) {
      if (count == 0) {
        candidate = x;
        count = 1;
      } else {
        if (x == candidate) {
          ++count;
        } else {
          --count;
        }
      }
    }
    return candidate;
  }
}
// https://leetcode.cn/submissions/detail/378328300/
```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```dart
class Solution {
  String largestNumber(List<int> nums) {
    final strs = nums.map((x) => x.toString()).toList();
    strs.sort((s1, s2) => (s2 + s1).compareTo(s1 + s2));
    final sb = StringBuffer();
    sb.writeAll(strs);
    final ans = sb.toString();
    return ans[0] == '0' ? '0' : ans;
  }
}
// https://leetcode.cn/submissions/detail/378400068/
```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```dart
class Solution {
  int maxProfit(int k, List<int> prices) {
    final n = prices.length;
    if (k <= 0 || n <= 1) {
      return 0;
    }
    // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
    // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
    final dp =
        List.generate(k + 1, (_) => List.generate(n, (_) => List.filled(2, 0)));
    // 交易次数限制为 0 时
    // 填写第 0 个 n x 2 矩阵
    for (var i = 0; i < n; ++i) {
      dp[0][i][0] = 0;
      dp[0][i][1] = -1000000;
    }
    // 交易次数限制为 [1..k] 时
    // 填写第 t 个 n x 2 矩阵
    for (var t = 1; t <= k; ++t) {
      dp[t][0][0] = 0;
      dp[t][0][1] = -prices[0];
      for (var i = 1; i < n; ++i) {
        // dp[t][i - 1][0]             >= dp[t - 1][i - 1][0] - prices[i]
        // dp[t][i - 1][1] + prices[i] >= dp[t][i - 1][1]
        // => dp[t][i][0] >= dp[t][i][1]
        dp[t][i][0] = max(dp[t][i - 1][0], dp[t][i - 1][1] + prices[i]);
        dp[t][i][1] = max(dp[t - 1][i - 1][0] - prices[i], dp[t][i - 1][1]);
      }
    }
    return dp[k][n - 1][0];
  }
}
// https://leetcode.cn/submissions/detail/376691291/
```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```dart
class Solution {
  void rotate(List<int> nums, int k) {
    final n = nums.length;
    k %= n;
    _reverse(nums, 0, n - 1);
    _reverse(nums, 0, k - 1);
    _reverse(nums, k, n - 1);
  }

  void _reverse(List<int> nums, int lo, int hi) {
    while (lo < hi) {
      _swap(nums, lo++, hi--);
    }
  }

  void _swap(List<int> nums, int i, int j) {
    final swap = nums[i];
    nums[i] = nums[j];
    nums[j] = swap;
  }
}
// https://leetcode.cn/submissions/detail/376047347/
```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```dart
class Solution {
  int rob(List<int> nums) {
    return _subseqSum(nums);
  }

  // max({sum(subseq) | subseq 是数组 nums 的不连续子序列})
  int _subseqSum(List<int> nums) {
    final n = nums.length;
    if (n == 0) {
      return 0;
    }
    if (n == 1) {
      return nums[0];
    }
    // dp[i] = max({sum(subseq) | subseq 是子数组 nums[0..i] 的不连续子序列})
    final dp = List.filled(n, 0);
    dp[0] = nums[0];
    dp[1] = max(nums[0], nums[1]);
    for (var i = 2; i < n; ++i) {
      // 包含 nums[i]
      final sp1 = dp[i - 2] + nums[i];
      // 不包含 nums[i]
      final sp2 = dp[i - 1];
      dp[i] = max(sp1, sp2);
    }
    return dp[n - 1];
  }
}
// https://leetcode.cn/submissions/detail/376664936/
```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```dart
import 'dart:collection';

class Solution {
  List<int> rightSideView(TreeNode? root) {
    final ans = <int>[];
    final queue = Queue<TreeNode>();
    if (root != null) {
      queue.addLast(root);
    }
    while (queue.isNotEmpty) {
      ans.add(queue.last.val);
      final n = queue.length;
      for (var i = 0; i < n; ++i) {
        final x = queue.removeFirst();
        final left = x.left;
        if (left != null) {
          queue.addLast(left);
        }
        final right = x.right;
        if (right != null) {
          queue.addLast(right);
        }
      }
    }
    return ans;
  }
}
// https://leetcode.cn/submissions/detail/377694625/
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
