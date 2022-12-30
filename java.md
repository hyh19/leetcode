<!-- omit in toc -->
# LeetCode 题解：Java

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

```java
class Solution {
    public int[] twoSum(int[] nums, int target) {
        int n = nums.length;
        Map<Integer, Integer> valToIndex = new HashMap(n);
        for (int i = 0; i < n; ++i) {
            int x = nums[i];
            int need = target - x;
            if (valToIndex.containsKey(need)) {
                return new int[]{valToIndex.get(need), i};
            }
            valToIndex.put(x, i);
        }
        return null;
    }
}
// https://leetcode.cn/submissions/detail/366685536/
```

## 2. 两数相加

<https://leetcode-cn.com/problems/add-two-numbers/>

```java
class Solution {
    public ListNode addTwoNumbers(ListNode l1, ListNode l2) {
        ListNode dummyHead = new ListNode();
        ListNode ptr = dummyHead;
        int carry = 0;
        while (l1 != null || l2 != null || carry > 0) {
            int sum = carry;
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
            carry = sum / 10;
        }
        return dummyHead.next;
    }
}
// https://leetcode.cn/submissions/detail/363774916/
```

## 3. 无重复字符的最长子串

<https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/>

```java
class Solution {
    public int lengthOfLongestSubstring(String s) {
        int ans = 0;
        Set<Character> window = new HashSet();
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        int left = 0, right = 0;
        while (right < s.length()) {
            char c = s.charAt(right);
            if (!window.contains(c)) {
                window.add(c);
                ++right;
            } else {
                while (left <= right) {
                    char d = s.charAt(left++);
                    window.remove(d);
                    if (c == d) {
                        break;
                    }
                }
            }
            ans = Math.max(ans, right - left);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/365632675/
```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```java
class Solution {
    public double findMedianSortedArrays(int[] nums1, int[] nums2) {
        int total = nums1.length + nums2.length;
        int half = total / 2;
        if (total % 2 == 0) {
            int k1 = getKthElement(nums1, nums2, half);
            int k2 = getKthElement(nums1, nums2, half + 1);
            return (k1 + k2) / 2.0;
        }
        return getKthElement(nums1, nums2, half + 1);
    }

    // 寻找两个正序数组 nums1 和 nums2 从小到大排列的第 k 个数
    private int getKthElement(int[] nums1, int[] nums2, int k) {
        int n1 = nums1.length, n2 = nums2.length;
        int start1 = 0, start2 = 0;
        while (true) {
            if (start1 == n1) {
                return nums2[start2 + k - 1];
            }
            if (start2 == n2) {
                return nums1[start1 + k - 1];
            }
            if (k == 1) {
                return Math.min(nums1[start1], nums2[start2]);
            }
            int half = k / 2;
            int i = Math.min(n1 - 1, start1 + half - 1);
            int j = Math.min(n2 - 1, start2 + half - 1);
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
    }
}
// https://leetcode.cn/submissions/detail/365182743/
```

```java
class Solution {
    public double findMedianSortedArrays(int[] nums1, int[] nums2) {
        int total = nums1.length + nums2.length;
        int half = total / 2;
        if (total % 2 == 0) {
            int k1 = getKthElement(nums1, 0, nums2, 0, half);
            int k2 = getKthElement(nums1, 0, nums2, 0, half + 1);
            return (k1 + k2) / 2.0;
        }
        return getKthElement(nums1, 0, nums2, 0, half + 1);
    }

    // 寻找两个正序数组 nums1[start1..end1] 和 nums2[start2..end2] 从小到大排列的第 k 个数
    private int getKthElement(int[] nums1, int start1, int[] nums2, int start2, int k) {
        int n1 = nums1.length, n2 = nums2.length;
        if (start1 == n1) {
            return nums2[start2 + k - 1];
        }
        if (start2 == n2) {
            return nums1[start1 + k - 1];
        }
        if (k == 1) {
            return Math.min(nums1[start1], nums2[start2]);
        }
        int half = k / 2;
        int i = Math.min(n1 - 1, start1 + half - 1);
        int j = Math.min(n2 - 1, start2 + half - 1);
        if (nums1[i] < nums2[j]) {
            // 排除 nums1[start1..i] 共 i-start1+1 个元素
            return getKthElement(nums1, i + 1, nums2, start2, k - (i - start1 + 1));
        } else {
            // 排除 nums2[start2..j] 共 j-start2+1 个元素
            return getKthElement(nums1, start1, nums2, j + 1, k - (j - start2 + 1));
        }
    }
}
// https://leetcode.cn/submissions/detail/365181986/
```

## 5. 最长回文子串

<https://leetcode.cn/problems/longest-palindromic-substring/>

```java
class Solution {
    public String longestPalindrome(String s) {
        String s1, s2, ans = "";
        for (int i = 0; i < s.length(); ++i) {
            s1 = longestPalindrome(s, i, i);
            if (s1.length() > ans.length()) {
                ans = s1;
            }
            s2 = longestPalindrome(s, i, i + 1);
            if (s2.length() > ans.length()) {
                ans = s2;
            }
        }
        return ans;
    }

    // 返回字符串 s 中以 s[i] 和 s[j] 为中心的最长回文子串
    String longestPalindrome(String s, int i, int j) {
        if (i > j || j - i > 1) {
            return "";
        }
        while (i >= 0 && j < s.length() && s.charAt(i) == s.charAt(j)) {
            --i;
            ++j;
        }
        return s.substring(i + 1, j);
    }
}
// https://leetcode.cn/submissions/detail/364087990/
```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```java
class Solution {
    public int reverse(int x) {
        int rev = 0;
        while (x != 0) {
            if (Math.abs(rev) > Integer.MAX_VALUE / 10) {
                return 0;
            }
            rev = rev * 10 + x % 10;
            x = x / 10;
        }
        return rev;
    }
}
// https://leetcode.cn/submissions/detail/350865020/
```

```java
class Solution {
    public int reverse(int x) {
        if (x == 0) {
            return 0;
        }
        String original = Integer.toString(Math.abs(x));
        String reverse = (new StringBuilder(original)).reverse().toString();
        String maxint = Integer.toString(Integer.MAX_VALUE);
        if (reverse.length() < maxint.length() ||
                reverse.compareTo(maxint) < 0) {
            return Integer.parseInt(reverse) * (x / Math.abs(x));
        }
        return 0;
    }
}
// https://leetcode.cn/submissions/detail/350873583/
```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```java
class Solution {
    public int maxArea(int[] height) {
        int i = 0, j = height.length - 1;
        int ans = 0;
        while (i < j) {
            int w = j - i;
            int h = Math.min(height[i], height[j]);
            ans = Math.max(ans, w * h);
            if (height[i] < height[j]) {
                ++i;
            } else {
                --j;
            }
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/368395393/
```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```java
class Solution {
    public String longestCommonPrefix(String[] strs) {
        return longestCommonPrefix(strs, 0, strs.length - 1);
    }

    private String longestCommonPrefix(String[] strs, int lo, int hi) {
        if (lo == hi) {
            return strs[lo];
        }
        int mid = lo + (hi - lo) / 2;
        String left = longestCommonPrefix(strs, lo, mid);
        String right = longestCommonPrefix(strs, mid + 1, hi);
        return longestCommonPrefix(left, right);
    }

    private String longestCommonPrefix(String s1, String s2) {
        int len = Math.min(s1.length(), s2.length());
        int i = 0;
        while (i < len && s1.charAt(i) == s2.charAt(i)) {
            ++i;
        }
        return s1.substring(0, i);
    }
}
// https://leetcode.cn/submissions/detail/363203257/
```

```java
class Solution {
    public String longestCommonPrefix(String[] strs) {
        String ans = strs[0];
        for (int i = 1; i < strs.length; ++i) {
            ans = longestCommonPrefix(ans, strs[i]);
        }
        return ans;
    }

    private String longestCommonPrefix(String s1, String s2) {
        int len = Math.min(s1.length(), s2.length());
        int i = 0;
        while (i < len && s1.charAt(i) == s2.charAt(i)) {
            ++i;
        }
        return s1.substring(0, i);
    }
}
// https://leetcode.cn/submissions/detail/363201881/
```

## 15. 三数之和

<https://leetcode-cn.com/problems/3sum/>

```java
class Solution {
    public List<List<Integer>> threeSum(int[] nums) {
        Arrays.sort(nums);
        return kSum(3, nums, 0, nums.length - 1, 0);
    }

    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
    private List<List<Integer>> kSum(int k, int[] nums, int lo, int hi, long target) {
        List<List<Integer>> res = new LinkedList();
        if (k < 2 || hi - lo + 1 < k) {
            return res;
        }
        if (k == 2) {
            return twoSum(nums, lo, hi, target);
        }
        int i = lo;
        while (i <= hi) {
            int curNum = nums[i];
            List<List<Integer>> sub = kSum(k - 1, nums, i + 1, hi, target - curNum);
            for (List<Integer> list : sub) {
                list.add(curNum);
                res.add(list);
            }
            while (++i <= hi && nums[i] == curNum) {
            }
        }
        return res;
    }

    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的二元组
    private List<List<Integer>> twoSum(int[] nums, int lo, int hi, long target) {
        List<List<Integer>> res = new LinkedList();
        while (lo < hi) {
            int first = nums[lo], second = nums[hi];
            int sum = first + second;
            if (sum < target) {
                while (++lo < hi && nums[lo] == first) {
                }
            } else if (sum > target) {
                while (lo < --hi && nums[hi] == second) {
                }
            } else {
                List<Integer> list = new LinkedList();
                list.add(first);
                list.add(second);
                res.add(list);
                while (++lo < hi && nums[lo] == first) {
                }
                while (lo < --hi && nums[hi] == second) {
                }
            }
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/367984584/
```

## 18. 四数之和

<https://leetcode.cn/problems/4sum/>

```java
class Solution {
    public List<List<Integer>> fourSum(int[] nums, int target) {
        Arrays.sort(nums);
        return kSum(4, nums, 0, nums.length - 1, target);
    }

    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
    private List<List<Integer>> kSum(int k, int[] nums, int lo, int hi, long target) {
        List<List<Integer>> res = new LinkedList();
        if (k < 2 || hi - lo + 1 < k) {
            return res;
        }
        if (k == 2) {
            return twoSum(nums, lo, hi, target);
        }
        int i = lo;
        while (i <= hi) {
            int curNum = nums[i];
            List<List<Integer>> sub = kSum(k - 1, nums, i + 1, hi, target - curNum);
            for (List<Integer> list : sub) {
                list.add(curNum);
                res.add(list);
            }
            while (++i <= hi && nums[i] == curNum) {
            }
        }
        return res;
    }

    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的二元组
    private List<List<Integer>> twoSum(int[] nums, int lo, int hi, long target) {
        List<List<Integer>> res = new LinkedList();
        while (lo < hi) {
            int first = nums[lo], second = nums[hi];
            int sum = first + second;
            if (sum < target) {
                while (++lo < hi && nums[lo] == first) {
                }
            } else if (sum > target) {
                while (lo < --hi && nums[hi] == second) {
                }
            } else {
                List<Integer> list = new LinkedList();
                list.add(first);
                list.add(second);
                res.add(list);
                while (++lo < hi && nums[lo] == first) {
                }
                while (lo < --hi && nums[hi] == second) {
                }
            }
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/367981946/
```

## 19. 删除链表的倒数第 N 个结点

<https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/>

```java
class Solution {
    public ListNode removeNthFromEnd(ListNode head, int n) {
        ListNode dummyHead = new ListNode(-1, head);
        ListNode slow = dummyHead;
        ListNode fast = dummyHead;
        for (int i = 1; i <= n; ++i) {
            fast = fast.next;
        }
        while (fast != null && fast.next != null) {
            slow = slow.next;
            fast = fast.next;
        }
        ListNode x = slow.next;
        if (x == head) { // 删除的是头结点
            head = head.next;
        } else {
            slow.next = x.next;
        }
        return head;
    }
}
// https://leetcode.cn/submissions/detail/367675516/
```

## 20. 有效的括号

<https://leetcode-cn.com/problems/valid-parentheses/>

```java
class Solution {
    public boolean isValid(String s) {
        int n = s.length();
        if (n % 2 == 1) {
            return false;
        }
        Deque<Character> stack = new LinkedList();
        for (int i = 0; i < n; ++i) {
            char ch = s.charAt(i);
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
                    if (stack.isEmpty() || stack.pop() != ch) {
                        return false;
                    }
                    break;
                }
            }
        }
        return stack.isEmpty();
    }
}
// https://leetcode.cn/submissions/detail/368935236/
```

## 21. 合并两个有序链表

<https://leetcode-cn.com/problems/merge-two-sorted-lists/>

```java
class Solution {
    public ListNode mergeTwoLists(ListNode list1, ListNode list2) {
        ListNode dummyHead = new ListNode();
        ListNode ptr = dummyHead;
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
    }
}
// https://leetcode.cn/submissions/detail/364489236/
```

## 22. 括号生成

<https://leetcode.cn/problems/generate-parentheses/>

```java
class Solution {
    private int n;
    private int left = 0;  // 已使用的『左括号』数量
    private int right = 0; // 已使用的『右括号』数量
    private StringBuilder path = new StringBuilder(); // 取 '(', ')' 为元素
    private List<String> ans = new LinkedList();

    public List<String> generateParenthesis(int n) {
        this.n = n;
        backtrack();
        return ans;
    }

    private void backtrack() {
        // 对于一个「合法」的括号字符串组合 p，必然对于任何 0 <= i < len(p) 都有：
        // 子串 p[0..i] 中左括号的数量都大于或等于右括号的数量
        if (left < right || left > n || right > n) {
            return;
        }
        // 一个「合法」括号组合的左括号数量一定等于右括号数量
        if (left == n && right == n) {
            ans.add(path.toString());
            return;
        }
        // edge = 取 '(', ')' 为值
        // 使用『左括号』
        path.append('(');
        ++left;
        backtrack();
        path.deleteCharAt(path.length() - 1);
        --left;
        // 使用『右括号』
        path.append(')');
        ++right;
        backtrack();
        path.deleteCharAt(path.length() - 1);
        --right;
    }
}
// https://leetcode.cn/submissions/detail/374097849/
```

```java
class Solution {
    private int n;
    private int left = 0;  // 已使用的『左括号』数量
    private int right = 0; // 已使用的『右括号』数量
    private StringBuilder path = new StringBuilder(); // 取 '(', ')' 为元素
    private List<String> ans = new LinkedList();

    public List<String> generateParenthesis(int n) {
        this.n = n;
        dfs('-');
        return ans;
    }

    // vertex = 取 '(', ')' 为值
    private void dfs(char vertex) {
        if (vertex != '-') {
            path.append(vertex);
            if (vertex == '(') {        // 使用『左括号』
                ++left;
            } else if (vertex == ')') { // 使用『右括号』
                ++right;
            }
        }
        if (left < right || left > n || right > n) {
            // 对于一个「合法」的括号字符串组合 p，必然对于任何 0 <= i < len(p) 都有：
            // 子串 p[0..i] 中左括号的数量都大于或等于右括号的数量
        } else if (left == n && right == n) {
            // 一个「合法」括号组合的左括号数量一定等于右括号数量
            ans.add(path.toString());
        } else {
            dfs('(');
            dfs(')');
        }
        if (vertex != '-') {
            path.deleteCharAt(path.length() - 1);
            if (vertex == '(') {
                --left;
            } else if (vertex == ')') {
                --right;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/374099807/
```

## 23. 合并 K 个升序链表

<https://leetcode-cn.com/problems/merge-k-sorted-lists/>

```java
class Solution {
    public ListNode mergeKLists(ListNode[] lists) {
        ListNode ans = null;
        for (ListNode l : lists) {
            ans = mergeTwoLists(ans, l);
        }
        return ans;
    }

    private ListNode mergeTwoLists(ListNode list1, ListNode list2) {
        ListNode dummyHead = new ListNode();
        ListNode ptr = dummyHead;
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
    }
}
// https://leetcode.cn/submissions/detail/361144131/
```

```java
class Solution {
    public ListNode mergeKLists(ListNode[] lists) {
        return mergeKLists(lists, 0, lists.length - 1);
    }

    // 合并升序链表数组 lists[lo..hi]，返回合并后的链表
    private ListNode mergeKLists(ListNode[] lists, int lo, int hi) {
        if (lo > hi) {
            return null;
        }
        if (lo == hi) {
            return lists[lo];
        }
        int mid = lo + (hi - lo) / 2;
        ListNode left = mergeKLists(lists, lo, mid);
        ListNode right = mergeKLists(lists, mid + 1, hi);
        return mergeTwoLists(left, right);
    }

    private ListNode mergeTwoLists(ListNode list1, ListNode list2) {
        ListNode dummyHead = new ListNode();
        ListNode ptr = dummyHead;
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
    }
}
// https://leetcode.cn/submissions/detail/361145418/
```

## 24. 两两交换链表中的节点

<https://leetcode-cn.com/problems/swap-nodes-in-pairs/>

```java
class Solution {
    public ListNode swapPairs(ListNode head) {
        if (head == null || head.next == null) {
            return head;
        }
        ListNode x = head;
        ListNode y = head.next;
        ListNode z = head.next.next;
        y.next = x;
        x.next = swapPairs(z);
        return y;
    }
}
// https://leetcode.cn/submissions/detail/368411639/
```

```java
class Solution {
    public ListNode swapPairs(ListNode head) {
        ListNode reverseHead = null;
        ListNode reverseTail = null;
        while (true) {
            if (head == null || head.next == null) {
                break;
            }
            ListNode x = head;
            ListNode y = head.next;
            ListNode z = head.next.next;
            y.next = x;
            x.next = z;
            if (reverseHead == null) {
                reverseHead = y;
            } else {
                reverseTail.next = y;
            }
            reverseTail = x;
            head = z;
        }
        return reverseHead == null ? head : reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/368418276/
```

## 25. K 个一组翻转链表

<https://leetcode.cn/problems/reverse-nodes-in-k-group/>

```java
class Solution {
    public ListNode reverseKGroup(ListNode head, int k) {
        ListNode ptr = head;
        for (int i = 1; i <= k - 1 && ptr != null; ++i) {
            ptr = ptr.next;
        }
        if (ptr == null) {
            return head;
        }
        ListNode nextGroup = ptr.next;
        ptr.next = null;
        ListNode reverseHead = reverseList(head);
        head.next = reverseKGroup(nextGroup, k);
        return reverseHead;
    }

    private ListNode reverseList(ListNode head) {
        ListNode reverseHead = null;
        while (head != null) {
            ListNode next = head.next;
            head.next = reverseHead;
            reverseHead = head;
            head = next;
        }
        return reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/368439318/
```

```java
class Solution {
    public ListNode reverseKGroup(ListNode head, int k) {
        ListNode reverseHead = null;
        ListNode reverseTail = null;
        while (true) {
            ListNode ptr = head;
            for (int i = 1; i <= k - 1 && ptr != null; ++i) {
                ptr = ptr.next;
            }
            if (ptr == null) {
                break;
            }
            ListNode nextGroup = ptr.next;
            ptr.next = null;
            if (reverseHead == null) {
                reverseHead = reverseList(head);
            } else {
                reverseTail.next = reverseList(head);
            }
            reverseTail = head;
            reverseTail.next = nextGroup;
            head = nextGroup;
        }
        return reverseHead == null ? head : reverseHead;
    }

    private ListNode reverseList(ListNode head) {
        ListNode reverseHead = null;
        while (head != null) {
            ListNode next = head.next;
            head.next = reverseHead;
            reverseHead = head;
            head = next;
        }
        return reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/368438769/
```

## 26. 删除有序数组中的重复项

<https://leetcode.cn/problems/remove-duplicates-from-sorted-array/>

```java
class Solution {
    public int removeDuplicates(int[] nums) {
        // [0..i-1] 不重复元素区间
        // [i..j-1] 重复元素区间
        // [j..n-1] 遍历区间
        int i = 0, j = 0, n = nums.length;
        while (j < n) {
            while (j + 1 < n && nums[j] == nums[j + 1]) {
                ++j;
            }
            exch(nums, i++, j++);
        }
        return i;
    }

    private void exch(int[] nums, int i, int j) {
        int swap = nums[i];
        nums[i] = nums[j];
        nums[j] = swap;
    }
}
// https://leetcode.cn/submissions/detail/369382643/
```

## 27. 移除元素

<https://leetcode.cn/problems/remove-element/>

```java
class Solution {
    public int removeElement(int[] nums, int val) {
        // nums[0..i-1] ≠ val
        // nums[i..j] Scanning
        // nums[j+1..n-1] = val
        int i = 0, j = nums.length - 1;
        while (i <= j) {
            while (i <= j && nums[i] != val) {
                ++i;
            }
            while (i <= j && nums[j] == val) {
                --j;
            }
            if (i <= j) {
                exch(nums, i++, j--);
            }
        }
        return i;
    }

    private void exch(int[] nums, int i, int j) {
        int swap = nums[i];
        nums[i] = nums[j];
        nums[j] = swap;
    }
}
// https://leetcode.cn/submissions/detail/357729288/
```

```java
class Solution {
    public int removeElement(int[] nums, int val) {
        // nums[0..i-1] ≠ val
        // nums[i..j-1] = val
        // nums[j..n-1] Scanning
        int i = 0, j = 0;
        while (j < nums.length) {
            if (nums[j] == val) {
                ++j;
            } else {
                exch(nums, i++, j++);
            }
        }
        return i;
    }

    private void exch(int[] nums, int i, int j) {
        int swap = nums[i];
        nums[i] = nums[j];
        nums[j] = swap;
    }
}
// https://leetcode.cn/submissions/detail/357722727/
```

## 28. 实现 strStr()

<https://leetcode.cn/problems/implement-strstr/>

```java
class Solution {
    private class KMP {
        private final int R = 26;
        private final int m;
        private int[][] dfa;

        public KMP(String pat) {
            this.m = pat.length();
            dfa = new int[R][m];
            dfa[pat.charAt(0) - 'a'][0] = 1;
            for (int x = 0, j = 1; j < m; j++) {
                for (int c = 'a'; c <= 'z'; c++)
                    dfa[c - 'a'][j] = dfa[c - 'a'][x];
                dfa[pat.charAt(j) - 'a'][j] = j + 1;
                x = dfa[pat.charAt(j) - 'a'][x];
            }
        }

        public int search(String txt) {
            int n = txt.length();
            int i, j;
            for (i = 0, j = 0; i < n && j < m; i++)
                j = dfa[txt.charAt(i) - 'a'][j];
            if (j == m) return i - m;
            return -1;
        }
    }

    public int strStr(String haystack, String needle) {
        KMP kmp = new KMP(needle);
        return kmp.search(haystack);
    }
}
// https://leetcode.cn/submissions/detail/324462455/
```

```java
class Solution {
    private class BoyerMoore {
        private final int R = 26;
        private final String pat;
        private int[] right;

        public BoyerMoore(String pat) {
            this.pat = pat;
            right = new int[R];
            for (int c = 'a'; c <= 'z'; c++)
                right[c - 'a'] = -1;
            for (int j = 0; j < pat.length(); j++)
                right[pat.charAt(j) - 'a'] = j;
        }

        public int search(String txt) {
            int n = txt.length();
            int m = pat.length();
            int skip;
            for (int i = 0; i <= n - m; i += skip) {
                skip = 0;
                for (int j = m - 1; j >= 0; j--) {
                    if (pat.charAt(j) != txt.charAt(i + j)) {
                        skip = Math.max(1, j - right[txt.charAt(i + j) - 'a']);
                        break;
                    }
                }
                if (skip == 0) return i;
            }
            return -1;
        }
    }

    public int strStr(String haystack, String needle) {
        BoyerMoore bm = new BoyerMoore(needle);
        return bm.search(haystack);
    }
}
// https://leetcode.cn/submissions/detail/324463219/
```

## 33. 搜索旋转排序数组

<https://leetcode.cn/problems/search-in-rotated-sorted-array/>

```java
class Solution {
    public int search(int[] nums, int target) {
        int lo = 0, hi = nums.length - 1;
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
            if (nums[mid] == target) {
                return mid;
            }
            // 当 lo = hi 或 hi-lo = 1 时，nums[lo] = nums[mid]，
            // 此时 nums[lo] <= target < nums[mid] 不成立
            if (nums[lo] <= nums[mid]) {
                if (nums[lo] <= target && target < nums[mid]) {
                    hi = mid - 1;
                } else {
                    lo = mid + 1;
                }
            } else {
                if (nums[mid] < target && target <= nums[hi]) {
                    lo = mid + 1;
                } else {
                    hi = mid - 1;
                }
            }
        }
        return -1;
    }
}
// https://leetcode.cn/submissions/detail/357590810/
```

```java
class Solution {
    public int search(int[] nums, int target) {
        int lo = 0, hi = nums.length - 1;
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
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
// https://leetcode.cn/submissions/detail/357591220/
```

```java
class Solution {
    public int search(int[] nums, int target) {
        int lo = 0, hi = nums.length - 1;
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
            if (nums[mid] == target) {
                return mid;
            }
            if (nums[mid] <= nums[hi]) {
                if (nums[mid] < target && target <= nums[hi]) {
                    return binarySearch(nums, mid + 1, hi, target);
                } else {
                    hi = mid - 1;
                }
            } else {
                if (nums[lo] <= target && target < nums[mid]) {
                    return binarySearch(nums, lo, mid - 1, target);
                } else {
                    lo = mid + 1;
                }
            }
        }
        return -1;
    }

    private int binarySearch(int[] nums, int lo, int hi, int target) {
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
            if (target < nums[mid]) {
                hi = mid - 1;
            } else if (nums[mid] < target) {
                lo = mid + 1;
            } else {
                return mid;
            }
        }
        return -1;
    }
}
// https://leetcode.cn/submissions/detail/376148557/
```

```java
class Solution {
    public int search(int[] nums, int target) {
        int min = findMin(nums);
        int ans = binarySearch(nums, 0, min - 1, target);
        if (ans == -1) {
            ans = binarySearch(nums, min, nums.length - 1, target);
        }
        return ans;
    }

    // 寻找旋转排序数组中的最小值的索引
    private int findMin(int[] nums) {
        int lo = 0, hi = nums.length - 1;
        while (lo < hi) {
            int mid = lo + (hi - lo) / 2;
            if (nums[mid] < nums[hi]) {
                hi = mid;
            } else {
                lo = mid + 1;
            }
        }
        return lo;
    }

    private int binarySearch(int[] nums, int lo, int hi, int target) {
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
            if (target < nums[mid]) {
                hi = mid - 1;
            } else if (nums[mid] < target) {
                lo = mid + 1;
            } else {
                return mid;
            }
        }
        return -1;
    }
}
// https://leetcode.cn/submissions/detail/376148015/
```

## 34. 在排序数组中查找元素的第一个和最后一个位置

<https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/>

```java
class Solution {
    public int[] searchRange(int[] nums, int target) {
        return new int[]{binarySearch(nums, target, true), binarySearch(nums, target, false)};
    }

    private int binarySearch(int[] nums, int target, boolean lower) {
        int res = -1;
        int lo = 0, hi = nums.length - 1;
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
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
// https://leetcode.cn/submissions/detail/361627563/
```

## 37. 解数独

<https://leetcode.cn/problems/sudoku-solver/>

```java
class Solution {
    public void solveSudoku(char[][] board) {
        backtrack(board, 0, -1);
    }

    // 遍历『决策森林』
    // tree  = row
    // level = (row, col)
    private boolean backtrack(char[][] board, int row, int col) {
        int n = board.length;
        boolean res = false;
        if (row == n - 1 && col == n - 1) {
            res = true;
        } else if (row < n - 1 && col == n - 1) {
            // 遍历下一棵『决策树』
            res = backtrack(board, row + 1, -1);
        } else if (board[row][col + 1] != '.') {
            res = backtrack(board, row, col + 1);
        } else {
            // edge = ['1'..'9']
            for (char ch = '1'; ch <= '9'; ++ch) {
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
    }

    // board[row][col] 填入数字 ch 是否有效
    private boolean isValid(char[][] board, int row, int col, char ch) {
        int n = board.length;
        for (int i = 0; i < n; ++i) {
            // 同一行
            if (board[row][i] == ch) {
                return false;
            }
            // 同一列
            if (board[i][col] == ch) {
                return false;
            }
            // 同九宫
            if (board[(row / 3) * 3 + i / 3][(col / 3) * 3 + i % 3] == ch) {
                return false;
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/374078773/
```

```java
class Solution {
    public void solveSudoku(char[][] board) {
        dfs(board, 0, -1, '#');
    }

    // 遍历『决策森林』
    // tree  = row
    // level = (row, col)
    private boolean dfs(char[][] board, int row, int col, char ch) {
        if (col >= 0 && ch != '#') {
            board[row][col] = ch;
        }
        int n = board.length;
        boolean res = false;
        if (row == n - 1 && col == n - 1) {
            res = true;
        } else if (row < n - 1 && col == n - 1) {
            // 遍历下一棵『决策树』
            res = dfs(board, row + 1, -1, '#');
        } else if (board[row][col + 1] != '.') {
            res = dfs(board, row, col + 1, '#');
        } else {
            // vertex = ['1'..'9']
            for (char c = '1'; c <= '9'; ++c) {
                if (isValid(board, row, col + 1, c)) {
                    res = dfs(board, row, col + 1, c);
                    if (res) {
                        break;
                    }
                }
            }
        }
        if (col >= 0 && ch != '#' && !res) {
            board[row][col] = '.';
        }
        return res;
    }

    // board[row][col] 填入数字 ch 是否有效
    private boolean isValid(char[][] board, int row, int col, char ch) {
        int n = board.length;
        for (int i = 0; i < n; ++i) {
            // 同一行
            if (board[row][i] == ch) {
                return false;
            }
            // 同一列
            if (board[i][col] == ch) {
                return false;
            }
            // 同九宫
            if (board[(row / 3) * 3 + i / 3][(col / 3) * 3 + i % 3] == ch) {
                return false;
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/374080368/
```

## 39. 组合总和

<https://leetcode.cn/problems/combination-sum/>

```java
class Solution {
    private int[] nums;
    private int target;
    private int pathSum = 0;
    private List<Integer> path = new LinkedList(); // 取 nums[edge] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> combinationSum(int[] candidates, int target) {
        this.nums = candidates;
        this.target = target;
        backtrack(-1);
        return ans;
    }

    // edge = 取数组 nums 的索引为值
    private void backtrack(int edge) {
        if (pathSum == target) {
            ans.add(new LinkedList(path));
            return;
        }
        if (edge == -1) {
            edge = 0;
        }
        // 避免重复，从 edge 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (edge < nums.length) {
            int x = nums[edge];
            if (pathSum + x <= target) {
                pathSum += x;
                path.add(x);
                backtrack(edge);
                pathSum -= x;
                path.remove(path.size() - 1);
            }
            ++edge;
        }
    }
}
// https://leetcode.cn/submissions/detail/373323363/
```

```java
class Solution {
    private int[] nums;
    private int target;
    private int pathSum = 0;
    private List<Integer> path = new LinkedList(); // 取 nums[vertex] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> combinationSum(int[] candidates, int target) {
        this.nums = candidates;
        this.target = target;
        dfs(-1);
        return ans;
    }

    // vertex = 取数组 nums 的索引为值
    private void dfs(int vertex) {
        int x = (vertex == -1 ? 0 : nums[vertex]);
        if (vertex >= 0) {
            pathSum += x;
            path.add(x);
        }
        if (pathSum == target) {
            ans.add(new LinkedList(path));
        } else {
            // 避免重复，从 vertex 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            int v = (vertex == -1 ? 0 : vertex);
            while (v < nums.length) {
                if (pathSum + nums[v] <= target) {
                    dfs(v);
                }
                ++v;
            }
        }
        if (vertex >= 0) {
            pathSum -= x;
            path.remove(path.size() - 1);
        }
    }
}
// https://leetcode.cn/submissions/detail/373326766/
```

```java
class Solution {
    private Map<String, List<List<Integer>>> memo = new HashMap();

    public List<List<Integer>> combinationSum(int[] candidates, int target) {
        return combinationSum(candidates, candidates.length - 1, target);
    }

    // 子数组 candidates[0..i] 和为 target 的不同组合
    public List<List<Integer>> combinationSum(int[] candidates, int i, int target) {
        if (i < 0 || target <= 0) {
            return new LinkedList();
        }
        // memo[i][target]
        String key = i + "," + target;
        if (!memo.containsKey(key)) {
            int x = candidates[i];
            List<List<Integer>> sp1 = combinationSum(candidates, i - 1, target); // 不包含 x
            List<List<Integer>> sp2 = combinationSum(candidates, i, target - x); // 包含 x
            List<List<Integer>> res = new LinkedList();
            for (List<Integer> list : sp1) {
                List<Integer> copy = new LinkedList(list);
                res.add(copy);
            }
            for (List<Integer> list : sp2) {
                List<Integer> copy = new LinkedList(list);
                copy.add(x);
                res.add(copy);
            }
            if (target == x) {
                List<Integer> list = new LinkedList();
                list.add(x);
                res.add(list);
            }
            memo.put(key, res);
        }
        return memo.get(key);
    }
}
// https://leetcode.cn/submissions/detail/373349100/
```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```java
class Solution {
    private int[] nums;
    private int target;
    private int pathSum = 0;
    private List<Integer> path = new LinkedList(); // 取 nums[edge] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> combinationSum2(int[] candidates, int target) {
        this.nums = candidates;
        this.target = target;
        Arrays.sort(this.nums);
        backtrack(-1);
        return ans;
    }

    // edge = 取数组 nums 的索引为值
    private void backtrack(int edge) {
        if (pathSum == target) {
            ans.add(new LinkedList(path));
            return;
        }
        int prev = Integer.MIN_VALUE;
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge < nums.length) {
            int x = nums[edge];
            if (x != prev && pathSum + x <= target) {
                prev = x;
                pathSum += x;
                path.add(x);
                backtrack(edge);
                pathSum -= x;
                path.remove(path.size() - 1);
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/373515914/
```

```java
class Solution {
    private int[] nums;
    private int target;
    private int pathSum = 0;
    private List<Integer> path = new LinkedList(); // 取 nums[vertex] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> combinationSum2(int[] candidates, int target) {
        this.nums = candidates;
        this.target = target;
        Arrays.sort(this.nums);
        dfs(-1);
        return ans;
    }

    // vertex = 取数组 nums 的索引为值
    private void dfs(int vertex) {
        int x = (vertex == -1 ? 0 : nums[vertex]);
        if (vertex >= 0) {
            pathSum += x;
            path.add(x);
        }
        if (pathSum == target) {
            ans.add(new LinkedList(path));
        } else {
            int prev = Integer.MIN_VALUE;
            // 避免重复，从 vertex + 1 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            int v = vertex;
            while (++v < nums.length) {
                int y = nums[v];
                if (y != prev && pathSum + y <= target) {
                    prev = y;
                    dfs(v);
                }
            }
        }
        if (vertex >= 0) {
            pathSum -= x;
            path.remove(path.size() - 1);
        }
    }
}
// https://leetcode.cn/submissions/detail/373518298/
```

## 42. 接雨水

<https://leetcode.cn/problems/trapping-rain-water/>

```java
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

```java
class Solution {
    public int trap(int[] height) {
        int sum = 0;
        // [0..i-1]   Computed
        // [i..j]     Scanning
        // [j+1..n-1] Computed
        int i = 0, j = height.length - 1;
        // leftMax = max(height[0..i])
        int leftMax = Integer.MIN_VALUE;
        // rightMax = max(height[j..n-1])
        int rightMax = Integer.MIN_VALUE;
        // When i = j, height[i] = height[j] = max(height[0..n-1])
        // height[i] = max(height[0..i]) = leftMax = rightMax = max(height[j..n-1]) = height[j]
        while (i <= j) {
            leftMax = Math.max(leftMax, height[i]);
            rightMax = Math.max(rightMax, height[j]);
            if (leftMax < rightMax) {
                // max(height[0..i]) = leftMax < rightMax = max(height[j..n-1]) <= max(height[i..n-1])
                sum += (leftMax - height[i++]);
            } else {
                // max(height[0..j]) >= max(height[0..i]) = leftMax >= rightMax = max(height[j..n-1])
                sum += (rightMax - height[j--]);
            }
        }
        return sum;
    }
}
// https://leetcode.cn/submissions/detail/358524412/
```

## 46. 全排列

<https://leetcode.cn/problems/permutations/>

```java
class Solution {
    private int[] nums;
    private boolean[] marked;
    private List<Integer> path = new LinkedList(); // 取 nums[edge] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> permute(int[] nums) {
        this.nums = nums;
        marked = new boolean[nums.length];
        backtrack();
        return ans;
    }

    private void backtrack() {
        int n = nums.length;
        if (path.size() == n) {
            ans.add(new LinkedList(path));
            return;
        }
        // edge = 取数组 nums 的索引为值
        for (int edge = 0; edge < n; ++edge) {
            if (!marked[edge]) {
                marked[edge] = true;
                path.add(nums[edge]);
                backtrack();
                marked[edge] = false;
                path.remove(path.size() - 1);
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/373147268/
```

```java
class Solution {
    private int[] nums;
    private boolean[] marked;
    private List<Integer> path = new LinkedList(); // 取 nums[vertex] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> permute(int[] nums) {
        this.nums = nums;
        marked = new boolean[nums.length];
        dfs(-1);
        return ans;
    }

    // vertex = 取数组 nums 的索引为值
    private void dfs(int vertex) {
        if (vertex >= 0) {
            marked[vertex] = true;
            path.add(nums[vertex]);
        }
        int n = nums.length;
        if (path.size() == n) {
            ans.add(new LinkedList(path));
        } else {
            for (int v = 0; v < n; ++v) {
                if (!marked[v]) {
                    dfs(v);
                }
            }
        }
        if (vertex >= 0) {
            marked[vertex] = false;
            path.remove(path.size() - 1);
        }
    }
}
// https://leetcode.cn/submissions/detail/373145343/
```

## 47. 全排列 II

<https://leetcode.cn/problems/permutations-ii/>

```java
class Solution {
    private int[] nums;
    private boolean[] marked;
    private List<Integer> path = new LinkedList(); // 取 nums[edge] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> permuteUnique(int[] nums) {
        this.nums = nums;
        marked = new boolean[nums.length];
        Arrays.sort(nums);
        backtrack();
        return ans;
    }

    private void backtrack() {
        int n = nums.length;
        if (path.size() == n) {
            ans.add(new LinkedList(path));
            return;
        }
        int prev = Integer.MIN_VALUE;
        // edge = 取数组 nums 的索引为值
        for (int edge = 0; edge < n; ++edge) {
            int x = nums[edge];
            if (!marked[edge] && x != prev) {
                prev = x;
                marked[edge] = true;
                path.add(x);
                backtrack();
                marked[edge] = false;
                path.remove(path.size() - 1);
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/373187652/
```

```java
class Solution {
    private int[] nums;
    private boolean[] marked;
    private List<Integer> path = new LinkedList(); // 取 nums[vertex] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> permuteUnique(int[] nums) {
        this.nums = nums;
        marked = new boolean[nums.length];
        Arrays.sort(nums);
        dfs(-1);
        return ans;
    }

    // vertex = 取数组 nums 的索引为值
    private void dfs(int vertex) {
        if (vertex >= 0) {
            marked[vertex] = true;
            path.add(nums[vertex]);
        }
        int n = nums.length;
        if (path.size() == n) {
            ans.add(new LinkedList(path));
        } else {
            int prev = Integer.MIN_VALUE;
            for (int v = 0; v < n; ++v) {
                int x = nums[v];
                if (!marked[v] && x != prev) {
                    prev = x;
                    dfs(v);
                }
            }
        }
        if (vertex >= 0) {
            marked[vertex] = false;
            path.remove(path.size() - 1);
        }
    }
}
// https://leetcode.cn/submissions/detail/373187411/
```

## 51. N 皇后

<https://leetcode.cn/problems/n-queens/>

```java
class Solution {
    private List<List<String>> ans = new LinkedList();

    public List<List<String>> solveNQueens(int n) {
        char[][] board = new char[n][n];
        for (char[] a : board) {
            Arrays.fill(a, '.');
        }
        backtrack(board, -1);
        return ans;
    }

    // level = row
    private void backtrack(char[][] board, int row) {
        int n = board.length;
        if (row == n - 1) {
            List<String> list = new LinkedList();
            for (char[] a : board) {
                list.add(new String(a));
            }
            ans.add(list);
            return;
        }
        // edge = col
        for (int col = 0; col < n; ++col) {
            if (isValid(board, row + 1, col)) {
                board[row + 1][col] = 'Q';
                backtrack(board, row + 1);
                board[row + 1][col] = '.';
            }
        }
    }

    // board[row][col] 放置 Q 是否有效
    private boolean isValid(char[][] board, int row, int col) {
        int n = board.length;
        // 同一列
        for (int r = row - 1; r >= 0; --r) {
            if (board[r][col] == 'Q') {
                return false;
            }
        }
        // 右斜线
        for (int r = row - 1, c = col + 1; r >= 0 && c < n; --r, ++c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        // 左斜线
        for (int r = row - 1, c = col - 1; r >= 0 && c >= 0; --r, --c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/373898790/
```

```java
class Solution {
    private List<List<String>> ans = new LinkedList();

    public List<List<String>> solveNQueens(int n) {
        char[][] board = new char[n][n];
        for (char[] a : board) {
            Arrays.fill(a, '.');
        }
        dfs(board, -1, -1);
        return ans;
    }

    // level  = row
    // vertex = col
    private void dfs(char[][] board, int row, int col) {
        if (col >= 0) {
            board[row][col] = 'Q';
        }
        int n = board.length;
        if (row == n - 1) {
            List<String> list = new LinkedList();
            for (char[] a : board) {
                list.add(new String(a));
            }
            ans.add(list);
        } else {
            for (int c = 0; c < n; ++c) {
                if (isValid(board, row + 1, c)) {
                    dfs(board, row + 1, c);
                }
            }
        }
        if (col >= 0) {
            board[row][col] = '.';
        }
    }

    // board[row][col] 放置 Q 是否有效
    private boolean isValid(char[][] board, int row, int col) {
        int n = board.length;
        // 同一列
        for (int r = row - 1; r >= 0; --r) {
            if (board[r][col] == 'Q') {
                return false;
            }
        }
        // 右斜线
        for (int r = row - 1, c = col + 1; r >= 0 && c < n; --r, ++c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        // 左斜线
        for (int r = row - 1, c = col - 1; r >= 0 && c >= 0; --r, --c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/373900025/
```

```java
class Solution {
    private List<List<String>> ans = new LinkedList();

    public List<List<String>> solveNQueens(int n) {
        char[][] board = new char[n][n];
        for (char[] a : board) {
            Arrays.fill(a, '.');
        }
        backtrack(board, 0, -1);
        return ans;
    }

    // 遍历『决策森林』
    // tree  = row
    // level = (row, col)
    private void backtrack(char[][] board, int row, int col) {
        int n = board.length;
        if (row == n) {
            List<String> list = new LinkedList();
            for (char[] a : board) {
                list.add(new String(a));
            }
            ans.add(list);
        } else if (col >= 0 && board[row][col] == 'Q') {
            if (isValid(board, row, col)) {
                // 遍历下一棵『决策树』
                backtrack(board, row + 1, -1);
            }
        } else if (col + 1 < n) {
            // edge = 'Q', '.'
            board[row][col + 1] = 'Q';
            backtrack(board, row, col + 1);
            board[row][col + 1] = '.';
            backtrack(board, row, col + 1);
        }
    }

    // board[row][col] 放置 Q 是否有效
    private boolean isValid(char[][] board, int row, int col) {
        int n = board.length;
        // 同一列
        for (int r = row - 1; r >= 0; --r) {
            if (board[r][col] == 'Q') {
                return false;
            }
        }
        // 右斜线
        for (int r = row - 1, c = col + 1; r >= 0 && c < n; --r, ++c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        // 左斜线
        for (int r = row - 1, c = col - 1; r >= 0 && c >= 0; --r, --c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/373904231/
```

```java
class Solution {
    private List<List<String>> ans = new LinkedList();

    public List<List<String>> solveNQueens(int n) {
        char[][] board = new char[n][n];
        for (char[] a : board) {
            Arrays.fill(a, '.');
        }
        dfs(board, 0, -1, '-');
        return ans;
    }

    // 遍历『决策森林』
    // tree   = row
    // level  = (row, col)
    // vertex = 'Q', '.'
    private void dfs(char[][] board, int row, int col, char ch) {
        if (col >= 0) {
            board[row][col] = ch;
        }
        int n = board.length;
        if (row == n) {
            List<String> list = new LinkedList();
            for (char[] a : board) {
                list.add(new String(a));
            }
            ans.add(list);
        } else if (col >= 0 && board[row][col] == 'Q') {
            if (isValid(board, row, col)) {
                // 遍历下一棵『决策树』
                dfs(board, row + 1, -1, '-');
            }
        } else if (col + 1 < n) {
            dfs(board, row, col + 1, 'Q');
            dfs(board, row, col + 1, '.');
        }
        if (col >= 0) {
            board[row][col] = '.';
        }
    }

    // board[row][col] 放置 Q 是否有效
    private boolean isValid(char[][] board, int row, int col) {
        int n = board.length;
        // 同一列
        for (int r = row - 1; r >= 0; --r) {
            if (board[r][col] == 'Q') {
                return false;
            }
        }
        // 右斜线
        for (int r = row - 1, c = col + 1; r >= 0 && c < n; --r, ++c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        // 左斜线
        for (int r = row - 1, c = col - 1; r >= 0 && c >= 0; --r, --c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/373907141/
```

## 52. N 皇后 II

<https://leetcode.cn/problems/n-queens-ii/>

```java
class Solution {
    private int ans = 0;

    public int totalNQueens(int n) {
        char[][] board = new char[n][n];
        for (int r = 0; r < n; r++) {
            for (int c = 0; c < n; c++) {
                board[r][c] = '.';
            }
        }
        backtrack(board, 0);
        return ans;
    }

    private void backtrack(char[][] board, int row) {
        int n = board.length;
        if (row == n) {
            ans++;
            return;
        }
        for (int col = 0; col <= n - 1; col++) {
            if (isValid(board, row, col)) {
                board[row][col] = 'Q';
                backtrack(board, row + 1);
                board[row][col] = '.';
            }
        }
    }

    private boolean isValid(char[][] board, int row, int col) {
        int n = board.length;
        // 检查同一列
        for (int r = row - 1; r >= 0; r--) {
            if (board[r][col] == 'Q') return false;
        }
        // 检查右斜线
        for (int r = row - 1, c = col + 1; r >= 0 && c <= n - 1; r--, c++) {
            if (board[r][c] == 'Q') return false;
        }
        // 检查左斜线
        for (int r = row - 1, c = col - 1; r >= 0 && c >= 0; r--, c--) {
            if (board[r][c] == 'Q') return false;
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/342490523/
```

## 53. 最大子数组和

<https://leetcode.cn/problems/maximum-subarray/>

```java
class Solution {
    public int maxSubArray(int[] nums) {
        int n = nums.length;
        // dp[i] = 以 nums[i] 结尾的连续子序列的最大和
        int[] dp = new int[n];
        dp[0] = nums[0];
        int ans = dp[0];
        for (int i = 1; i < n; ++i) {
            dp[i] = Math.max(nums[i], dp[i - 1] + nums[i]);
            ans = Math.max(ans, dp[i]);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/368031513/
```

```java
class Solution {
    public int maxSubArray(int[] nums) {
        int n = nums.length;
        int[] memo = new int[n];
        Arrays.fill(memo, Integer.MIN_VALUE);
        int ans = Integer.MIN_VALUE;
        for (int i = 0; i < n; ++i) {
            ans = Math.max(ans, dp(nums, i, memo));
        }
        return ans;
    }

    // dp[i] = 以 nums[i] 结尾的连续子序列的最大和
    private int dp(int[] nums, int i, int[] memo) {
        if (memo[i] != Integer.MIN_VALUE) {
            return memo[i];
        }
        if (i == 0) {
            memo[i] = nums[0];
        } else {
            memo[i] = Math.max(nums[i], nums[i] + dp(nums, i - 1, memo));
        }
        return memo[i];
    }
}
// https://leetcode.cn/submissions/detail/363533188/
```

## 56. 合并区间

<https://leetcode.cn/problems/merge-intervals/>

```java
class Solution {
    public int[][] merge(int[][] intervals) {
        Arrays.sort(intervals, (a, b) -> {
            if (a[0] == b[0]) {
                return b[1] - a[1];
            }
            return a[0] - b[0];
        });
        List<int[]> list = new LinkedList();
        int mStart = intervals[0][0];
        int mEnd = intervals[0][1];
        for (int i = 1; i < intervals.length; ++i) {
            int start = intervals[i][0];
            int end = intervals[i][1];
            if (start <= mEnd) { // 重叠
                mEnd = Math.max(mEnd, end);
            } else { // 不重叠
                list.add(new int[]{mStart, mEnd});
                mStart = start;
                mEnd = end;
            }
        }
        list.add(new int[]{mStart, mEnd});
        int[][] ans = new int[list.size()][2];
        int t = 0;
        for (int[] interval : list) {
            ans[t++] = interval;
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/375423860/
```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```java
class Solution {
    private int[][] memo;

    public int minPathSum(int[][] grid) {
        int m = grid.length, n = grid[0].length;
        memo = new int[m][n];
        for (int[] a : memo) {
            Arrays.fill(a, -1);
        }
        return minPathSum(grid, m - 1, n - 1);
    }

    // 从 grid[0][0] 到 grid[row][col] 的最小路径和
    private int minPathSum(int[][] grid, int row, int col) {
        if (row < 0 || col < 0) {
            return Integer.MAX_VALUE;
        }
        if (row == 0 && col == 0) {
            return grid[row][col];
        }
        if (memo[row][col] == -1) {
            int sp1 = minPathSum(grid, row - 1, col); // 上
            int sp2 = minPathSum(grid, row, col - 1); // 左
            memo[row][col] = Math.min(sp1, sp2) + grid[row][col];
        }
        return memo[row][col];
    }
}
// https://leetcode.cn/submissions/detail/375048176/
```

```java
class Solution {
    public int minPathSum(int[][] grid) {
        int m = grid.length;
        int n = grid[0].length;
        int[][] dp = new int[m][n];
        dp[0][0] = grid[0][0];
        for (int i = 1; i < m; i++) {
            dp[i][0] = dp[i - 1][0] + grid[i][0];
        }
        for (int j = 1; j < n; j++) {
            dp[0][j] = dp[0][j - 1] + grid[0][j];
        }
        for (int i = 1; i < m; i++) {
            for (int j = 1; j < n; j++) {
                dp[i][j] = grid[i][j] + Math.min(dp[i][j - 1], dp[i - 1][j]);
            }
        }
        return dp[m - 1][n - 1];
    }
}
// https://leetcode.cn/submissions/detail/331681875/
```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```java
class Solution {
    public int mySqrt(int x) {
        if (x == 0) {
            return 0;
        }
        int lo = 1, hi = x;
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
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
    }
}
// https://leetcode.cn/submissions/detail/366030861/
```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```java
class Solution {
    public int climbStairs(int n) {
        if (n == 1) {
            return 1;
        }
        if (n == 2) {
            return 2;
        }
        // dp[i] = 楼梯有 i 阶时，有几种不同的方法
        int[] dp = new int[n + 1];
        dp[1] = 1;
        dp[2] = 2;
        for (int i = 3; i <= n; i++) {
            dp[i] = dp[i - 1] + dp[i - 2];
        }
        return dp[n];
    }
}
// https://leetcode.cn/submissions/detail/360166861/
```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```java
class Solution {
    private int[][] memo;

    public int minDistance(String word1, String word2) {
        int n1 = word1.length(), n2 = word2.length();
        memo = new int[n1][n2];
        for (int[] a : memo) {
            Arrays.fill(a, -1);
        }
        return minDistance(word1, n1 - 1, word2, n2 - 1);
    }

    // 子串 s1[0..i] s2[0..j] 的最小编辑距离
    private int minDistance(String s1, int i, String s2, int j) {
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
        if (memo[i][j] == -1) {
            if (s1.charAt(i) == s2.charAt(j)) {
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                memo[i][j] = minDistance(s1, i - 1, s2, j - 1);
            } else {
                // 替换 s1[i] 为 s2[j]
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                int sp1 = minDistance(s1, i - 1, s2, j - 1) + 1;
                // 插入 s2[j] 到 s1
                // s1[0..i]
                // s2[0..j-1][j]
                int sp2 = minDistance(s1, i, s2, j - 1) + 1;
                // 删除 s1[i]
                // s1[0..i-1][i]
                // s2[0..j]
                int sp3 = minDistance(s1, i - 1, s2, j) + 1;
                memo[i][j] = Math.min(Math.min(sp1, sp2), sp3);
            }
        }
        return memo[i][j];
    }
}
// https://leetcode.cn/submissions/detail/374427602/
```

```java
class Solution {
    public int minDistance(String word1, String word2) {
        int m = word1.length();
        int n = word2.length();

        int[][] dp = new int[m + 1][n + 1];

        for (int i = 0; i <= m; i++) {
            dp[i][0] = i;
        }

        for (int j = 0; j <= n; j++) {
            dp[0][j] = j;
        }
        
        for (int i = 1; i <= m; i++) {
            for (int j = 1; j <= n; j++) {
                if (word1.charAt(i - 1) == word2.charAt(j - 1)) {
                    dp[i][j] = dp[i - 1][j - 1];
                } else {
                    dp[i][j] = 1 + min(dp[i - 1][j - 1],
                            dp[i - 1][j],
                            dp[i][j - 1]);
                }
            }
        }

        return dp[m][n];
    }

    private int min(int a, int b, int c) {
        return Math.min(Math.min(a, b), c);
    }
}
// https://leetcode.cn/submissions/detail/329779941/
```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```java
class Solution {
    public void sortColors(int[] nums) {
        int v = 1;
        int lt = 0;
        int gt = nums.length - 1;
        int i = 0;
        while (i <= gt) {
            int x = nums[i];
            if (x < v) {
                exch(nums, lt++, i++);
            } else if (x > v) {
                exch(nums, i, gt--);
            } else {
                ++i;
            }
        }
    }

    private void exch(int[] nums, int i, int j) {
        int swap = nums[i];
        nums[i] = nums[j];
        nums[j] = swap;
    }
}
// https://leetcode.cn/submissions/detail/362959615/
```

```java
class Solution {
    public void sortColors(int[] nums) {
        int R = 3;
        int[] count = new int[R + 1];
        int n = nums.length;
        int[] aux = new int[n];
        for (int i = 0; i < n; ++i) {
            ++count[nums[i] + 1];
        }
        for (int r = 0; r < R; ++r) {
            count[r + 1] += count[r];
        }
        for (int i = 0; i < n; ++i) {
            aux[count[nums[i]]++] = nums[i];
        }
        for (int i = 0; i < n; ++i) {
            nums[i] = aux[i];
        }
    }
}
// https://leetcode.cn/submissions/detail/364684644/
```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```java
class Solution {
    public String minWindow(String s, String t) {
        Map<Character, Integer> need = new HashMap();
        for (char c : t.toCharArray()) {
            need.put(c, need.getOrDefault(c, 0) + 1);
        }
        Map<Character, Integer> window = new HashMap();
        int valid = 0;
        int start = 0, len = Integer.MAX_VALUE;
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        int left = 0, right = 0;
        while (right < s.length()) {
            char c = s.charAt(right++);
            if (need.containsKey(c)) {
                window.put(c, window.getOrDefault(c, 0) + 1);
                // Java 的 Integer，String 等类型判定相等应该用 equals 方法，
                // 而不能直接用等号 ==，这是 Java 包装类的一个隐晦细节。
                // Integer 会缓存频繁使用的数值，范围是 -128 到 127，
                // 在此范围内直接返回缓存值，超过该范围就会 new 一个对象。
                if (window.get(c).equals(need.get(c))) {
                    ++valid;
                }
            }
            if (valid == need.size()) {
                while (left < right) {
                    char d = s.charAt(left);
                    if (need.containsKey(d) && window.get(d).equals(need.get(d))) {
                        break;
                    } else {
                        if (need.containsKey(d)) {
                            window.put(d, window.get(d) - 1);
                        }
                        ++left;
                    }
                }
                if (right - left < len) {
                    start = left;
                    len = right - left;
                }
            }
        }
        return len == Integer.MAX_VALUE ? "" : s.substring(start, start + len);
    }
}
// https://leetcode.cn/submissions/detail/365625351/
```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```java
class Solution {
    private int n, k;
    private List<Integer> path = new LinkedList(); // 取 [1..n] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> combine(int n, int k) {
        this.n = n;
        this.k = k;
        backtrack(0);
        return ans;
    }

    // edge = 取 [1..n] 为值
    private void backtrack(int edge) {
        if (path.size() == k) {
            ans.add(new LinkedList(path));
            return;
        }
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge <= n) {
            path.add(edge);
            backtrack(edge);
            path.remove(path.size() - 1);
        }
    }
}
// https://leetcode.cn/submissions/detail/373540774/
```

```java
class Solution {
    private int n, k;
    private List<Integer> path = new LinkedList(); // 取 [1..n] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> combine(int n, int k) {
        this.n = n;
        this.k = k;
        dfs(0);
        return ans;
    }

    // vertex = 取 [1..n] 为值
    private void dfs(int vertex) {
        if (vertex > 0) {
            path.add(vertex);
        }
        if (path.size() == k) {
            ans.add(new LinkedList(path));
        } else {
            // 避免重复，从 vertex + 1 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            int v = vertex;
            while (++v <= n) {
                dfs(v);
            }
        }
        if (vertex > 0) {
            path.remove(path.size() - 1);
        }
    }
}
// https://leetcode.cn/submissions/detail/373542384/
```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```java
class Solution {
    private int[] nums;
    private List<Integer> path = new LinkedList(); // 取 nums[edge] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> subsets(int[] nums) {
        this.nums = nums;
        backtrack(-1);
        return ans;
    }

    // edge = 取数组 nums 的索引为值
    private void backtrack(int edge) {
        ans.add(new LinkedList(path));
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge < nums.length) {
            path.add(nums[edge]);
            backtrack(edge);
            path.remove(path.size() - 1);
        }
    }
}
// https://leetcode.cn/submissions/detail/373211586/
```

```java
class Solution {
    private int[] nums;
    private List<Integer> path = new LinkedList(); // 取 nums[vertex] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> subsets(int[] nums) {
        this.nums = nums;
        dfs(-1);
        return ans;
    }

    // vertex = 取数组 nums 的索引为值
    private void dfs(int vertex) {
        if (vertex >= 0) {
            path.add(nums[vertex]);
        }
        ans.add(new LinkedList(path));
        // 避免重复，从 vertex + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        int v = vertex;
        while (++v < nums.length) {
            dfs(v);
        }
        if (vertex >= 0) {
            path.remove(path.size() - 1);
        }
    }
}
// https://leetcode.cn/submissions/detail/373212858/
```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```java
class Solution {
    public boolean search(int[] nums, int target) {
        int lo = 0, hi = nums.length - 1;
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
            if (nums[mid] == target) {
                return true;
            }
            if (nums[lo] == nums[mid] && nums[mid] == nums[hi]) {
                ++lo;
                --hi;
            } else {
                if (nums[lo] <= nums[mid]) {
                    if (nums[lo] <= target && target < nums[mid]) {
                        hi = mid - 1;
                    } else {
                        lo = mid + 1;
                    }
                } else {
                    if (nums[mid] < target && target <= nums[hi]) {
                        lo = mid + 1;
                    } else {
                        hi = mid - 1;
                    }
                }
            }
        }
        return false;
    }
}
// https://leetcode.cn/submissions/detail/357592789/
```

```java
class Solution {
    public boolean search(int[] nums, int target) {
        int lo = 0, hi = nums.length - 1;
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
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
// https://leetcode.cn/submissions/detail/374905441/
```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```java
class Solution {
    public ListNode deleteDuplicates(ListNode head) {
        ListNode ptr = head;
        while (ptr != null && ptr.next != null) {
            if (ptr.val == ptr.next.val) {
                ptr.next = ptr.next.next;
            } else {
                ptr = ptr.next;
            }
        }
        return head;
    }
}
// https://leetcode.cn/submissions/detail/363726841/
```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```java
class Solution {
    public ListNode partition(ListNode head, int x) {
        ListNode dummyLess = new ListNode();
        ListNode ptrLess = dummyLess;
        ListNode dummyGreater = new ListNode();
        ListNode ptrGreater = dummyGreater;
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
    }
}
// https://leetcode.cn/submissions/detail/341380904/
```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```java
class Solution {
    private int[] nums;
    private List<Integer> path = new LinkedList(); // 取 nums[edge] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> subsetsWithDup(int[] nums) {
        this.nums = nums;
        Arrays.sort(this.nums);
        backtrack(-1);
        return ans;
    }

    // edge = 取数组 nums 的索引为值
    private void backtrack(int edge) {
        ans.add(new LinkedList(path));
        int prev = Integer.MIN_VALUE;
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge < nums.length) {
            int x = nums[edge];
            if (x != prev) {
                prev = x;
                path.add(x);
                backtrack(edge);
                path.remove(path.size() - 1);
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/374850940/
```

```java
class Solution {
    private int[] nums;
    private List<Integer> path = new LinkedList(); // 取 nums[vertex] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> subsetsWithDup(int[] nums) {
        this.nums = nums;
        Arrays.sort(this.nums);
        dfs(-1);
        return ans;
    }

    // vertex = 取数组 nums 的索引为值
    private void dfs(int vertex) {
        if (vertex >= 0) {
            path.add(nums[vertex]);
        }
        ans.add(new LinkedList(path));
        int prev = Integer.MIN_VALUE;
        // 避免重复，从 vertex + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        int v = vertex;
        while (++v < nums.length) {
            int x = nums[v];
            if (x != prev) {
                prev = x;
                dfs(v);
            }
        }
        if (vertex >= 0) {
            path.remove(path.size() - 1);
        }
    }
}
// https://leetcode.cn/submissions/detail/374851346/
```

## 92. 反转链表 II

<https://leetcode-cn.com/problems/reverse-linked-list-ii/>

```java
class Solution {
    public ListNode reverseBetween(ListNode head, int left, int right) {
        if (head == null || head.next == null) {
            return head;
        }
        if (left == 1) {
            return reverseList(head, right);
        }
        ListNode ptr = head;
        for (int i = 1; i <= left - 2; ++i) {
            ptr = ptr.next;
        }
        ptr.next = reverseList(ptr.next, right - left + 1);
        return head;
    }

    // 翻转链表的前 n 个节点，返回翻转后的头节点
    private ListNode reverseList(ListNode head, int n) {
        if (head == null || head.next == null || n <= 1) {
            return head;
        }
        ListNode reverseHead = null;
        ListNode ptr = head;
        while (ptr != null && n > 0) {
            ListNode next = ptr.next;
            ptr.next = reverseHead;
            reverseHead = ptr;
            ptr = next;
            --n;
        }
        head.next = ptr;
        return reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/365611990/
```

```java
class Solution {
    ListNode successor = null;

    public ListNode reverseBetween(ListNode head, int left, int right) {
        if (head == null || head.next == null) {
            return head;
        }
        if (left == 1) {
            return reverseList(head, right);
        }
        ListNode ptr = head;
        for (int i = 1; i <= left - 2; i++) {
            ptr = ptr.next;
        }
        ptr.next = reverseList(ptr.next, right - left + 1);
        return head;
    }

    // 翻转链表的前 n 个节点，返回翻转后的头节点
    private ListNode reverseList(ListNode head, int n) {
        if (head == null || head.next == null || n <= 1) {
            successor = (head == null ? null : head.next);
            return head;
        }
        ListNode sub = head.next;
        ListNode reverseHead = reverseList(sub, n - 1);
        sub.next = head;
        head.next = successor;
        return reverseHead;
    }
}
```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```java
class Solution {
    private List<Integer> ans = new LinkedList();

    public List<Integer> inorderTraversal(TreeNode root) {
        dfs(root);
        return ans;
    }

    private void dfs(TreeNode root) {
        if (root == null) {
            return;
        }
        dfs(root.left);
        ans.add(root.val);
        dfs(root.right);
    }
}
// https://leetcode.cn/submissions/detail/366426962/
```

```java
class Solution {
    public List<Integer> inorderTraversal(TreeNode root) {
        List<Integer> res = new LinkedList();
        if (root == null) {
            return res;
        }
        res.addAll(inorderTraversal(root.left));
        res.add(root.val);
        res.addAll(inorderTraversal(root.right));
        return res;
    }
}
// https://leetcode.cn/submissions/detail/355142487/
```

```java
class Solution {
    public List<Integer> inorderTraversal(TreeNode root) {
        List<Integer> inorder = new LinkedList();
        Set<TreeNode> marked = new HashSet();
        Deque<TreeNode> stack = new LinkedList();
        if (root != null) {
            stack.push(root);
        }
        while (!stack.isEmpty()) {
            TreeNode x = stack.peek();
            TreeNode left = x.left;
            if (left != null && !marked.contains(left)) {
                stack.push(left);
                continue;
            }
            if (!marked.contains(x)) {
                inorder.add(x.val);
                marked.add(x);
            }
            TreeNode right = x.right;
            if (right != null && !marked.contains(right)) {
                stack.push(right);
                continue;
            }
            stack.pop();
        }
        return inorder;
    }
}
// https://leetcode.cn/submissions/detail/355142207/
```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```java
class Solution {
    public List<TreeNode> generateTrees(int n) {
        return build(1, n);
    }

    List<TreeNode> build(int lo, int hi) {
        List<TreeNode> list = new LinkedList<>();
        if (lo > hi) {
            list.add(null);
            return list;
        }

        for (int i = lo; i <= hi; i++) {
            List<TreeNode> leftSubtrees = build(lo, i - 1);
            List<TreeNode> rightSubtrees = build(i + 1, hi);
            for (TreeNode lst : leftSubtrees) {
                for (TreeNode rst : rightSubtrees) {
                    list.add(new TreeNode(i, lst, rst));
                }
            }
        }
        return list;
    }
}
// https://leetcode.cn/submissions/detail/323140072/
```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```java

```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```java

```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```java

```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```java

```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```java

```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```java

```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```java

```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```java

```

## 107. 二叉树的层序遍历 II

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```java

```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```java

```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```java

```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```java

```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```java

```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```java

```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```java

```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```java

```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```java

```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```java

```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```java

```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```java

```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```java

```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```java

```

## 141. 环形链表

<https://leetcode-cn.com/problems/linked-list-cycle/>

```java

```

## 142. 环形链表 II

<https://leetcode-cn.com/problems/linked-list-cycle-ii/>

```java

```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```java

```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```java

```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```java

```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```java

```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```java

```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```java

```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```java

```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```java

```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```java

```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```java

```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```java

```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```java

```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```java

```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```java

```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```java

```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```java

```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```java

```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```java

```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```java

```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```java

```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```java

```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```java

```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```java

```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```java

```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```java

```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```java

```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```java

```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```java

```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```java

```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```java

```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```java

```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```java

```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```java

```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```java

```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```java

```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```java

```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```java

```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```java

```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```java

```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```java

```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```java

```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```java

```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```java

```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```java

```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```java

```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```java

```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```java

```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```java

```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```java

```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```java

```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```java

```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```java

```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```java

```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```java

```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```java

```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```java

```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```java

```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```java

```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```java

```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```java

```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```java

```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```java

```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```java

```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```java

```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```java

```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```java

```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```java

```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```java

```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```java

```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```java

```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```java

```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```java

```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```java

```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```java

```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```java

```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```java

```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```java

```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```java

```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```java

```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```java

```

## 876. 链表的中间结点

<https://leetcode-cn.com/problems/middle-of-the-linked-list/>

```java

```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```java

```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```java

```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```java

```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```java

```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```java

```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```java

```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```java

```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```java

```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```java

```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```java

```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```java

```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```java

```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```java

```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```java

```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```java

```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```java

```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```java

```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```java

```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```java

```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```java

```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```java

```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode-cn.com/problems/kth-node-from-end-of-list-lcci/>

```java

```
