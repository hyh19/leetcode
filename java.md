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
            char add = s.charAt(right);
            if (!window.contains(add)) {
                window.add(add);
                ++right;
            } else {
                while (left < right) {
                    char del = s.charAt(left++);
                    window.remove(del);
                    if (del == add) {
                        break;
                    }
                }
            }
            ans = Math.max(ans, right - left);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/392736471/
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
        String ans = "";
        for (int i = 0; i < s.length(); ++i) {
            String s1 = longestPalindrome(s, i, i);
            if (s1.length() > ans.length()) {
                ans = s1;
            }
            String s2 = longestPalindrome(s, i, i + 1);
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
// https://leetcode.cn/submissions/detail/394195923/
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
        int ans = 0;
        int i = 0, j = height.length - 1;
        while (i < j) {
            int area = (j - i) * Math.min(height[i], height[j]);
            ans = Math.max(ans, area);
            if (height[i] < height[j]) {
                ++i;
            } else {
                --j;
            }
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/395986082/
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
        int n = Math.min(s1.length(), s2.length());
        int i = 0;
        while (i < n && s1.charAt(i) == s2.charAt(i)) {
            ++i;
        }
        return s1.substring(0, i);
    }
}
// https://leetcode.cn/submissions/detail/398711600/
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
        int n = Math.min(s1.length(), s2.length());
        int i = 0;
        while (i < n && s1.charAt(i) == s2.charAt(i)) {
            ++i;
        }
        return s1.substring(0, i);
    }
}
// https://leetcode.cn/submissions/detail/398712016/
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
        while (fast.next != null) {
            slow = slow.next;
            fast = fast.next;
        }
        slow.next = slow.next.next;
        return dummyHead.next;
    }
}
// https://leetcode.cn/submissions/detail/399272129/
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
class Solution {
    Map<Integer, Integer> memo = new HashMap<>();

    public int numTrees(int n) {
        if (n == 0) {
            memo.put(0, 1);
            return 1;
        }

        if (memo.get(n) != null) return memo.get(n);

        int sum = 0;
        for (int i = 1; i <= n; i++) {
            sum += numTrees(i - 1) * numTrees(n - i);
        }
        memo.put(n, sum);

        return sum;
    }
}
// https://leetcode.cn/submissions/detail/323108919/
```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```java
class Solution {
    private boolean ans = true;

    public boolean isValidBST(TreeNode root) {
        checkLowerAndUpperBound(root, Long.MIN_VALUE, Long.MAX_VALUE);
        return ans;
    }

    // 检查二叉树是否在区间 (lower, upper) 内，递归过程中确定是否满足二叉搜索树的性质
    private boolean checkLowerAndUpperBound(TreeNode root, long lower, long upper) {
        if (root == null) {
            return true;
        }
        if (root.val <= lower || root.val >= upper) {
            ans = false;
            return false;
        }
        return checkLowerAndUpperBound(root.left, lower, root.val) && checkLowerAndUpperBound(root.right, root.val, upper);
    }
}
// https://leetcode.cn/submissions/detail/365895525/
```

```java
class Solution {
    private boolean ans = true;

    public boolean isValidBST(TreeNode root) {
        getMinAndMaxValue(root);
        return ans;
    }

    // 返回二叉树的最小值和最大值
    private long[] getMinAndMaxValue(TreeNode root) {
        if (root == null) {
            return new long[]{Long.MAX_VALUE, Long.MIN_VALUE};
        }
        long[] left = getMinAndMaxValue(root.left);
        long[] right = getMinAndMaxValue(root.right);
        long leftMin = left[0], leftMax = left[1];
        long rightMin = right[0], rightMax = right[1];
        // max(root.left) < root.val < min(root.right)
        if (!(leftMax < root.val && root.val < rightMin)) {
            ans = false;
        }
        long min = Math.min(root.val, Math.min(leftMin, rightMin));
        long max = Math.max(root.val, Math.max(leftMax, rightMax));
        return new long[]{min, max};
    }
}
// https://leetcode.cn/submissions/detail/365893835/
```

```java
class Solution {
    private boolean ans = true;
    private TreeNode ptr = null;

    public boolean isValidBST(TreeNode root) {
        dfs(root);
        return ans;
    }

    private void dfs(TreeNode root) {
        if (root == null) {
            return;
        }
        dfs(root.left);
        if (ptr != null && root.val <= ptr.val) {
            ans = false;
            return;
        }
        ptr = root;
        dfs(root.right);
    }
}
// https://leetcode.cn/submissions/detail/365896812/
```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```java
class Solution {
    public boolean isSameTree(TreeNode p, TreeNode q) {
        if (p == null && q == null) {
            return true;
        }
        if (p == null || q == null || p.val != q.val) {
            return false;
        }
        return isSameTree(p.left, q.left) && isSameTree(p.right, q.right);
    }
}
// https://leetcode.cn/submissions/detail/364421959/
```

```java
class Solution {
    private boolean ans = true;

    public boolean isSameTree(TreeNode p, TreeNode q) {
        dfs(p, q);
        return ans;
    }

    private void dfs(TreeNode p, TreeNode q) {
        if (p == null && q == null) {
            return;
        }
        if (p == null || q == null || p.val != q.val) {
            ans = false;
            return;
        }
        dfs(p.left, q.left);
        dfs(p.right, q.right);
    }
}
// https://leetcode.cn/submissions/detail/364420203/
```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```java
class Solution {
    public List<List<Integer>> levelOrder(TreeNode root) {
        List<List<Integer>> ans = new LinkedList<>();
        Deque<TreeNode> queue = new LinkedList<>();
        if (root != null) {
            queue.addLast(root);
        }
        while (!queue.isEmpty()) {
            List<Integer> level = new LinkedList<>();
            int n = queue.size();
            for (int i = 0; i < n; ++i) {
                TreeNode x = queue.removeFirst();
                level.add(x.val);
                TreeNode left = x.left;
                if (left != null) {
                    queue.addLast(left);
                }
                TreeNode right = x.right;
                if (right != null) {
                    queue.addLast(right);
                }
            }
            ans.add(level);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/435839522/
```

```java
class Solution {
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> levelOrder(TreeNode root) {
        dfs(root, 0);
        return ans;
    }

    private void dfs(TreeNode root, int depth) {
        if (root == null) {
            return;
        }
        if (ans.size() == depth) {
            ans.add(new LinkedList<Integer>());
        }
        ans.get(depth).add(root.val);
        dfs(root.left, depth + 1);
        dfs(root.right, depth + 1);
    }
}
// https://leetcode.cn/submissions/detail/365906248/
```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```java
class Solution {
    public List<List<Integer>> zigzagLevelOrder(TreeNode root) {
        List<List<Integer>> ans = new LinkedList();
        Deque<TreeNode> queue = new LinkedList();
        if (root != null) {
            queue.addLast(root);
        }
        boolean reverse = false;
        while (!queue.isEmpty()) {
            int sz = queue.size();
            List<Integer> level = new LinkedList();
            for (int i = 0; i < sz; ++i) {
                TreeNode x = queue.removeFirst();
                if (reverse) {
                    level.add(0, x.val);
                } else {
                    level.add(x.val);
                }
                TreeNode left = x.left;
                if (left != null) {
                    queue.addLast(left);
                }
                TreeNode right = x.right;
                if (right != null) {
                    queue.addLast(right);
                }
            }
            reverse = !reverse;
            ans.add(level);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/361391543/
```

```java
class Solution {
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> zigzagLevelOrder(TreeNode root) {
        dfs(root, 0);
        boolean reverse = false;
        for (List<Integer> list : ans) {
            if (reverse) {
                Collections.reverse(list);
            }
            reverse = !reverse;
        }
        return ans;
    }

    private void dfs(TreeNode root, int depth) {
        if (root == null) {
            return;
        }
        if (ans.size() == depth) {
            ans.add(new LinkedList<Integer>());
        }
        ans.get(depth).add(root.val);
        dfs(root.left, depth + 1);
        dfs(root.right, depth + 1);
    }
}
// https://leetcode.cn/submissions/detail/365907568/
```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```java
class Solution {
    public int maxDepth(TreeNode root) {
        if (root == null) {
            return 0;
        }
        return 1 + Math.max(maxDepth(root.left), maxDepth(root.right));
    }
}
// https://leetcode.cn/submissions/detail/361397472/
```

```java
class Solution {
    public int maxDepth(TreeNode root) {
        int ans = 0;
        Deque<TreeNode> queue = new LinkedList();
        if (root != null) {
            queue.offer(root);
        }
        while (!queue.isEmpty()) {
            ++ans;
            int sz = queue.size();
            for (int i = 0; i < sz; ++i) {
                TreeNode x = queue.poll();
                TreeNode left = x.left;
                if (left != null) {
                    queue.offer(left);
                }
                TreeNode right = x.right;
                if (right != null) {
                    queue.offer(right);
                }
            }
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/361402271/
```

```java
class Solution {
    private int path = 0;
    private int ans = 0;

    public int maxDepth(TreeNode root) {
        if (root == null) {
            return 0;
        }
        path = 1;
        backtrack(root);
        return ans;
    }

    private void backtrack(TreeNode root) {
        TreeNode left = root.left, right = root.right;
        if (left == null && right == null) {
            ans = Math.max(ans, path);
            return;
        }
        if (left != null) {
            ++path;
            backtrack(left);
            --path;
        }
        if (right != null) {
            ++path;
            backtrack(right);
            --path;
        }
    }
}
// https://leetcode.cn/submissions/detail/361398423/
```

```java
class Solution {
    private int ans = 0;

    public int maxDepth(TreeNode root) {
        dfs(root, 1);
        return ans;
    }

    private void dfs(TreeNode root, int depth) {
        if (root == null) {
            return;
        }
        ans = Math.max(ans, depth);
        dfs(root.left, depth + 1);
        dfs(root.right, depth + 1);
    }
}
// https://leetcode.cn/submissions/detail/361397756/
```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```java
class Solution {
    private Map<Integer, Integer> valToIndex = new HashMap();

    public TreeNode buildTree(int[] preorder, int[] inorder) {
        for (int i = 0; i < inorder.length; ++i) {
            valToIndex.put(inorder[i], i);
        }
        return buildTree(preorder, 0, preorder.length - 1, inorder, 0, inorder.length - 1);
    }

    private TreeNode buildTree(int[] preorder, int preStart, int preEnd, int[] inorder, int inStart, int inEnd) {
        if (preStart > preEnd) {
            return null;
        }
        int rootVal = preorder[preStart];
        TreeNode root = new TreeNode(rootVal);
        int index = valToIndex.get(rootVal);
        int leftSize = index - inStart;
        root.left = buildTree(preorder, preStart + 1, preStart + leftSize, inorder, inStart, index - 1);
        root.right = buildTree(preorder, preStart + leftSize + 1, preEnd, inorder, index + 1, inEnd);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/361434402/
```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```java
class Solution {
    private Map<Integer, Integer> valToIndex = new HashMap();

    public TreeNode buildTree(int[] inorder, int[] postorder) {
        for (int i = 0; i < inorder.length; ++i) {
            valToIndex.put(inorder[i], i);
        }
        return buildTree(inorder, 0, inorder.length - 1,
                postorder, 0, postorder.length - 1);
    }

    private TreeNode buildTree(int[] inorder, int inStart, int inEnd,
                               int[] postorder, int postStart, int postEnd) {
        if (postStart > postEnd) {
            return null;
        }
        int rootVal = postorder[postEnd];
        TreeNode root = new TreeNode(rootVal);
        if (postStart == postEnd) {
            return root;
        }
        int index = valToIndex.get(rootVal);
        int leftSize = index - inStart;
        root.left = buildTree(inorder, inStart, index - 1,
                postorder, postStart, postStart + leftSize - 1);
        root.right = buildTree(inorder, index + 1, inEnd,
                postorder, postStart + leftSize, postEnd - 1);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/364292845/
```

## 107. 二叉树的层序遍历 II

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```java
class Solution {
    public List<List<Integer>> levelOrderBottom(TreeNode root) {
        List<List<Integer>> ans = new LinkedList<>();
        Deque<TreeNode> queue = new LinkedList<>();
        if (root != null) {
            queue.addLast(root);
        }
        while (!queue.isEmpty()) {
            int size = queue.size();
            List<Integer> level = new LinkedList<>();
            for (int i = 1; i <= size; ++i) {
                TreeNode x = queue.removeFirst();
                level.add(x.val);
                if (x.left != null) {
                    queue.addLast(x.left);
                }
                if (x.right != null) {
                    queue.addLast(x.right);
                }
            }
            ans.add(0, level);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/347797934/
```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```java
class Solution {
    public TreeNode sortedArrayToBST(int[] nums) {
        return sortedArrayToBST(nums, 0, nums.length - 1);
    }

    // 将有序数组 nums[lo..hi] 转换为二叉搜索树
    private TreeNode sortedArrayToBST(int[] nums, int lo, int hi) {
        if (lo > hi) {
            return null;
        }
        int mid = lo + (hi - lo) / 2;
        TreeNode root = new TreeNode(nums[mid]);
        root.left = sortedArrayToBST(nums, lo, mid - 1);
        root.right = sortedArrayToBST(nums, mid + 1, hi);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/362435531/
```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```java
class Solution {
    private boolean ans = true;

    public boolean isBalanced(TreeNode root) {
        height(root);
        return ans;
    }

    private int height(TreeNode root) {
        if (root == null) {
            return -1;
        }
        int left = height(root.left);
        int right = height(root.right);
        if (Math.abs(left - right) > 1) {
            ans = false;
        }
        return 1 + Math.max(left, right);
    }
}
// https://leetcode.cn/submissions/detail/365986983/
```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```java
class Solution {
    public int minDepth(TreeNode root) {
        return bfs(root);
    }

    private int bfs(TreeNode root) {
        int minDepth = 0;
        Deque<TreeNode> queue = new LinkedList<TreeNode>();
        if (root != null) queue.addLast(root);
        while (!queue.isEmpty()) {
            minDepth++;
            int size = queue.size();
            for (int i = 0; i < size; i++) {
                TreeNode node = queue.removeFirst();
                if (node.left == null && node.right == null) return minDepth;
                if (node.left != null) queue.addLast(node.left);
                if (node.right != null) queue.addLast(node.right);
            }
        }
        return minDepth;
    }
}
// https://leetcode.cn/submissions/detail/343765289/
```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```java
class Solution {
    public boolean hasPathSum(TreeNode root, int targetSum) {
        if (root == null) {
            return false;
        }
        if (root.left == null && root.right == null) {
            return root.val == targetSum;
        }
        return hasPathSum(root.left, targetSum - root.val) || hasPathSum(root.right, targetSum - root.val);
    }
}
// https://leetcode.cn/submissions/detail/366300863/
```

```java
class Solution {
    private int targetSum;
    private int pathSum = 0;
    private boolean ans = false;

    public boolean hasPathSum(TreeNode root, int targetSum) {
        this.targetSum = targetSum;
        if (root != null) {
            pathSum += root.val;
            backtrack(root);
            pathSum -= root.val;
        }
        return ans;
    }

    private void backtrack(TreeNode root) {
        TreeNode left = root.left, right = root.right;
        if (left == null && right == null && pathSum == targetSum) {
            ans = true;
        }
        if (left != null) {
            pathSum += left.val;
            backtrack(left);
            pathSum -= left.val;
        }
        if (right != null) {
            pathSum += right.val;
            backtrack(right);
            pathSum -= right.val;
        }
    }
}
// https://leetcode.cn/submissions/detail/366297511/
```

```java
class Solution {
    private int targetSum;
    private int pathSum = 0;
    private boolean ans = false;

    public boolean hasPathSum(TreeNode root, int targetSum) {
        this.targetSum = targetSum;
        dfs(root);
        return ans;
    }

    private void dfs(TreeNode root) {
        if (root == null) {
            return;
        }
        pathSum += root.val;
        if (root.left == null && root.right == null && pathSum == targetSum) {
            ans = true;
        }
        dfs(root.left);
        dfs(root.right);
        pathSum -= root.val;
    }
}
// https://leetcode.cn/submissions/detail/366300496/
```

```java
class Solution {
    private int targetSum;
    private boolean ans;
    
    public boolean hasPathSum(TreeNode root, int targetSum) {
        this.targetSum = targetSum;
        bfs(root);
        return ans;
    }

    private void bfs(TreeNode root) {
        Deque<TreeNode> queue = new LinkedList();
        Map<TreeNode, Integer> map = new HashMap();
        if (root != null) {
            queue.addLast(root);
            map.put(root, root.val);
        }
        while (!queue.isEmpty()) {
            TreeNode x = queue.removeFirst();
            int pathSum = map.get(x);
            if (x.left == null && x.right == null && pathSum == targetSum) {
                ans = true;
                break;
            }
            TreeNode left = x.left;
            if (left != null) {
                queue.addLast(left);
                map.put(left, pathSum + left.val);
            }
            TreeNode right = x.right;
            if (right != null) {
                queue.addLast(right);
                map.put(right, pathSum + right.val);
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/366302345/
```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```java
class Solution {
    public void flatten(TreeNode root) {
        if (root == null) {
            return;
        }
        TreeNode left = root.left;
        TreeNode right = root.right;
        root.left = null;
        root.right = null;
        flatten(left);
        flatten(right);
        root.right = left;
        TreeNode ptr = root;
        while (ptr.right != null) {
            ptr = ptr.right;
        }
        ptr.right = right;
    }
}
// https://leetcode.cn/submissions/detail/364471466/
```

```java
class Solution {
    private TreeNode ptr;

    public void flatten(TreeNode root) {
        TreeNode dummyHead = new TreeNode();
        ptr = dummyHead;
        dfs(root);
        root = dummyHead.right;
    }

    private void dfs(TreeNode root) {
        if (root == null) {
            return;
        }
        ptr.right = root;
        ptr = ptr.right;
        TreeNode left = root.left;
        TreeNode right = root.right;
        root.left = null;
        root.right = null;
        dfs(left);
        dfs(right);
    }
}
// https://leetcode.cn/submissions/detail/365648355/
```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```java
class Solution {
    public Node connect(Node root) {
        if (root == null) return null;
        connect(root.left, root.right);
        return root;
    }

    private void connect(Node left, Node right) {
        if (left == null || right == null) return;
        left.next = right;
        connect(left.left, left.right);
        connect(left.right, right.left);
        connect(right.left, right.right);
    }
}
// https://leetcode.cn/submissions/detail/337336281/
```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```java
class Solution {
    public int maxProfit(int[] prices) {
        int n = prices.length;
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        int[][] dp = new int[n][2];
        dp[0][0] = 0;
        dp[0][1] = -prices[0];
        for (int i = 1; i < n; ++i) {
            // dp[i - 1][0]             >= -prices[i]
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = Math.max(-prices[i], dp[i - 1][1]);
        }
        return dp[n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/365501682/
```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```java
class Solution {
    public int maxProfit(int[] prices) {
        int n = prices.length;
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        int[][] dp = new int[n][2];
        dp[0][0] = 0;
        dp[0][1] = -prices[0];
        for (int i = 1; i < n; ++i) {
            // dp[i - 1][0]             >= dp[i - 1][0] - prices[i]
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = Math.max(dp[i - 1][0] - prices[i], dp[i - 1][1]);
        }
        return dp[n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/365502480/
```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```java
class Solution {
    public int maxProfit(int[] prices) {
        return maxProfit(2, prices);
    }

    // 返回买卖股票的最大利润，交易次数限制为 k
    private int maxProfit(int k, int[] prices) {
        int n = prices.length;
        if (k <= 0 || n <= 1) {
            return 0;
        }
        // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
        // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
        int[][][] dp = new int[k + 1][n][2];
        // 交易次数限制为 0 时
        // 填写第 0 个 n x 2 矩阵
        for (int i = 0; i < n; ++i) {
            dp[0][i][0] = 0;
            dp[0][i][1] = Integer.MIN_VALUE;
        }
        // 交易次数限制为 [1..k] 时
        for (int t = 1; t <= k; ++t) {
            // 填写第 t 个 n x 2 矩阵
            dp[t][0][0] = 0;
            dp[t][0][1] = -prices[0];
            for (int i = 1; i < n; ++i) {
                // dp[t][i - 1][0]             >= dp[t - 1][i - 1][0] - prices[i]
                // dp[t][i - 1][1] + prices[i] >= dp[t][i - 1][1]
                // => dp[t][i][0] >= dp[t][i][1]
                dp[t][i][0] = Math.max(dp[t][i - 1][0], dp[t][i - 1][1] + prices[i]);
                dp[t][i][1] = Math.max(dp[t - 1][i - 1][0] - prices[i], dp[t][i - 1][1]);
            }
        }
        return dp[k][n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/365508809/
```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```java
class Solution {
    public boolean isPalindrome(String s) {
        int n = s.length();
        int i = -1, j = n;
        while (true) {
            while (!Character.isLetterOrDigit(s.charAt(++i))) {
                if (i == n - 1) {
                    break;
                }
            }
            while (!Character.isLetterOrDigit(s.charAt(--j))) {
                if (j == 0) {
                    break;
                }
            }
            if (i >= j) {
                break;
            }
            if (Character.toLowerCase(s.charAt(i)) != Character.toLowerCase(s.charAt(j))) {
                return false;
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/363594350/
```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```java
class Solution {
    public int longestConsecutive(int[] nums) {
        int ans = 0;
        Set<Integer> set = new HashSet<>(nums.length);
        for (int x : nums) {
            set.add(x);
        }
        for (int x : nums) {
            if (set.contains(x)) {
                set.remove(x);
                int lo = x - 1;
                while (set.contains(lo)) {
                    set.remove(lo--);
                }
                int hi = x + 1;
                while (set.contains(hi)) {
                    set.remove(hi++);
                }
                ans = Math.max(ans, hi - lo - 1);
            }
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/437927675/
```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```java
// 1254. 统计封闭岛屿的数目
// https://leetcode.cn/problems/number-of-closed-islands/
class Solution {
    private static final char LAND = 'O';
    private static final char WATER = 'X';
    private Set<Integer> memo = new HashSet();
    private boolean record = false;

    public void solve(char[][] board) {
        char[][] grid = board;
        int m = grid.length;
        int n = grid[0].length;
        record = true;
        // 淹没与左右边界的陆地相连的岛屿
        for (int i = 0; i < m; ++i) {
            floodFill(grid, i, 0);
            floodFill(grid, i, n - 1);
        }
        // 淹没与上下边界的陆地相连的岛屿
        for (int j = 0; j < n; ++j) {
            floodFill(grid, 0, j);
            floodFill(grid, m - 1, j);
        }
        record = false;
        // 淹没封闭岛屿
        for (int i = 0; i < m; ++i) {
            for (int j = 0; j < n; ++j) {
                if (grid[i][j] == LAND) {
                    floodFill(grid, i, j);
                }
            }
        }
        // 重建原来与边界陆地相连的岛屿
        for (int x : memo) {
            int i = x / n;
            int j = x % n;
            grid[i][j] = LAND;
        }
    }

    private void floodFill(char[][] grid, int i, int j) {
        if (i < 0 || i >= grid.length || j < 0 || j >= grid[0].length || grid[i][j] == WATER) {
            return;
        }
        grid[i][j] = WATER;
        if (record) {
            memo.add(i * grid[0].length + j);
        }
        floodFill(grid, i, j + 1);
        floodFill(grid, i, j - 1);
        floodFill(grid, i + 1, j);
        floodFill(grid, i - 1, j);
    }
}
// https://leetcode.cn/submissions/detail/371999467/
```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```java
class Solution {
    public int singleNumber(int[] nums) {
        int ans = 0;
        for (int x : nums) {
            ans ^= x;
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/362944770/
```

```java
class Solution {
    public int singleNumber(int[] nums) {
        Map<Integer, Integer> map = new HashMap();
        for (int x : nums) {
            map.put(x, map.getOrDefault(x, 0) + 1);
        }
        for (Map.Entry<Integer, Integer> e : map.entrySet()) {
            if (e.getValue() == 1) {
                return e.getKey();
            }
        }
        return -1;
    }
}
// https://leetcode.cn/submissions/detail/362946778/
```

```java
class Solution {
    public int singleNumber(int[] nums) {
        Set<Integer> set = new HashSet();
        for (int x : nums) {
            if (set.contains(x)) {
                set.remove(x);
            } else {
                set.add(x);
            }
        }
        return set.iterator().next();
    }
}
// https://leetcode.cn/submissions/detail/362933521/
```

```java
class Solution {
    public int singleNumber(int[] nums) {
        int sumOfArray = 0;
        int sumOfSet = 0;
        Set<Integer> set = new HashSet();
        for (int x : nums) {
            sumOfArray += x;
            if (!set.contains(x)) {
                sumOfSet += x;
                set.add(x);
            }
        }
        return 2 * sumOfSet - sumOfArray;
    }
}
// https://leetcode.cn/submissions/detail/362950898/
```

## 141. 环形链表

<https://leetcode-cn.com/problems/linked-list-cycle/>

```java
public class Solution {
    public boolean hasCycle(ListNode head) {
        ListNode slow = head, fast = head;
        while (fast != null && fast.next != null) {
            slow = slow.next;
            fast = fast.next.next;
            if (slow == fast) {
                return true;
            }
        }
        return false;
    }
}
// https://leetcode.cn/submissions/detail/361358454/
```

```java
public class Solution {
    public boolean hasCycle(ListNode head) {
        Set<ListNode> set = new HashSet<>();
        while (head != null) {
            if (set.contains(head)) return true;
            set.add(head);
            head = head.next;
        }
        return false;
    }
}
// https://leetcode.cn/submissions/detail/340594121/
```

## 142. 环形链表 II

<https://leetcode-cn.com/problems/linked-list-cycle-ii/>

```java
public class Solution {
    public ListNode detectCycle(ListNode head) {
        ListNode slow = head, fast = head;
        while (fast != null && fast.next != null) {
            slow = slow.next;
            fast = fast.next.next;
            if (slow == fast) {
                fast = head;
                while (slow != fast) {
                    slow = slow.next;
                    fast = fast.next;
                }
                return slow;
            }
        }
        return null;
    }
}
// https://leetcode.cn/submissions/detail/364486781/
```

```java
public class Solution {
    public ListNode detectCycle(ListNode head) {
        Set<ListNode> set = new HashSet<>();
        while (head != null) {
            if (set.contains(head)) return head;
            set.add(head);
            head = head.next;
        }
        return null;
    }
}
// https://leetcode.cn/submissions/detail/340600928/
```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```java
class Solution {
    public void reorderList(ListNode head) {
        ListNode slow = head, fast = head;
        while (fast.next != null && fast.next.next != null) {
            slow = slow.next;
            fast = fast.next.next;
        }
        ListNode x = slow.next;
        slow.next = null;
        ListNode reverseHead = reverseList(x);
        ListNode dummyHead = new ListNode();
        ListNode ptr = dummyHead;
        while (head != null) {
            if (head != null) {
                ptr.next = head;
                ptr = ptr.next;
                head = head.next;
            }
            if (reverseHead != null) {
                ptr.next = reverseHead;
                ptr = ptr.next;
                reverseHead = reverseHead.next;
            }
        }
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
// https://leetcode.cn/submissions/detail/366437946/
```

```java
class Solution {
    public void reorderList(ListNode head) {
        List<ListNode> array = new ArrayList();
        while (head != null) {
            ListNode next = head.next;
            head.next = null;
            array.add(head);
            head = next;
        }
        head = new ListNode();
        int left = 0, right = array.size() - 1;
        while (left <= right) {
            head.next = array.get(left);
            head = head.next;
            if (left == right) {
                break;
            }
            head.next = array.get(right);
            head = head.next;
            ++left;
            --right;
        }
    }
}
// https://leetcode.cn/submissions/detail/355978332/
```

```java
class Solution {
    public void reorderList(ListNode head) {
        Deque<ListNode> queue = new LinkedList();
        while (head != null) {
            ListNode next = head.next;
            head.next = null;
            queue.addLast(head);
            head = next;
        }
        head = new ListNode();
        while (!queue.isEmpty()) {
            head.next = queue.removeFirst();
            head = head.next;
            if (!queue.isEmpty()) {
                head.next = queue.removeLast();
                head = head.next;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/355979163/
```

```java
class Solution {
    public void reorderList(ListNode head) {
        ListNode mid = head, ptr = head;
        while (ptr.next != null && ptr.next.next != null) {
            mid = mid.next;
            ptr = ptr.next.next;
        }
        Deque<ListNode> stack = new LinkedList();
        ptr = mid.next;
        mid.next = null;
        while (ptr != null) {
            ListNode next = ptr.next;
            ptr.next = null;
            stack.push(ptr);
            ptr = next;
        }
        ptr = new ListNode();
        while (head != null) {
            ptr.next = head;
            head = head.next;
            ptr = ptr.next;
            if (!stack.isEmpty()) {
                ptr.next = stack.pop();
                ptr = ptr.next;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/355979942/
```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```java
class Solution {
    private List<Integer> ans = new LinkedList();

    public List<Integer> preorderTraversal(TreeNode root) {
        dfs(root);
        return ans;
    }

    private void dfs(TreeNode root) {
        if (root == null) {
            return;
        }
        ans.add(root.val);
        dfs(root.left);
        dfs(root.right);
    }
}
// https://leetcode.cn/submissions/detail/366426193/
```

```java
class Solution {
    public List<Integer> preorderTraversal(TreeNode root) {
        List<Integer> res = new LinkedList();
        if (root == null) {
            return res;
        }
        res.add(root.val);
        res.addAll(preorderTraversal(root.left));
        res.addAll(preorderTraversal(root.right));
        return res;
    }
}
// https://leetcode.cn/submissions/detail/355148730/
```

```java
class Solution {
    public List<Integer> preorderTraversal(TreeNode root) {
        List<Integer> preorder = new LinkedList();
        Deque<TreeNode> stack = new LinkedList();
        if (root != null) {
            stack.push(root);
        }
        while (!stack.isEmpty()) {
            TreeNode x = stack.pop();
            preorder.add(x.val);
            TreeNode right = x.right;
            if (right != null) {
                stack.push(x.right);
            }
            TreeNode left = x.left;
            if (left != null) {
                stack.push(x.left);
            }
        }
        return preorder;
    }
}
// https://leetcode.cn/submissions/detail/355692356/
```

```java
class Solution {
    public List<Integer> preorderTraversal(TreeNode root) {
        List<Integer> preorder = new LinkedList();
        HashSet<TreeNode> marked = new HashSet();
        Deque<TreeNode> stack = new LinkedList();
        if (root != null) {
            stack.push(root);
        }
        while (!stack.isEmpty()) {
            TreeNode x = stack.peek();
            if (!marked.contains(x)) {
                preorder.add(x.val);
                marked.add(x);
            }
            TreeNode left = x.left;
            if (left != null && !marked.contains(left)) {
                stack.push(left);
                continue;
            }
            TreeNode right = x.right;
            if (right != null && !marked.contains(right)) {
                stack.push(right);
                continue;
            }
            stack.pop();
        }
        return preorder;
    }
}
// https://leetcode.cn/submissions/detail/355137201/
```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```java
class Solution {
    private List<Integer> ans = new LinkedList();

    public List<Integer> postorderTraversal(TreeNode root) {
        dfs(root);
        return ans;
    }

    private void dfs(TreeNode root) {
        if (root == null) {
            return;
        }
        dfs(root.left);
        dfs(root.right);
        ans.add(root.val);
    }
}
// https://leetcode.cn/submissions/detail/366428168/
```

```java
class Solution {
    public List<Integer> postorderTraversal(TreeNode root) {
        List<Integer> res = new LinkedList();
        if (root == null) {
            return res;
        }
        res.addAll(postorderTraversal(root.left));
        res.addAll(postorderTraversal(root.right));
        res.add(root.val);
        return res;
    }
}
// https://leetcode.cn/submissions/detail/355146951/
```

```java
class Solution {
    public List<Integer> postorderTraversal(TreeNode root) {
        List<Integer> postorder = new LinkedList();
        HashSet<TreeNode> marked = new HashSet();
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
            TreeNode right = x.right;
            if (right != null && !marked.contains(right)) {
                stack.push(right);
                continue;
            }
            if (!marked.contains(x)) {
                postorder.add(x.val);
                marked.add(x);
            }
            stack.pop();
        }
        return postorder;
    }
}
// https://leetcode.cn/submissions/detail/355147563/
```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```java
class MyListNode {
    public int key, val;
    public MyListNode prev, next;

    public MyListNode(int key, int val) {
        this.key = key;
        this.val = val;
    }
}

class MyDoublyLinkedList {
    private MyListNode first, last;
    private int n;

    public MyDoublyLinkedList() {
        first = null;
        last = null;
        n = 0;
    }

    public void addLast(MyListNode newNode) {
        if (n == 0) {
            first = newNode;
            last = newNode;
        } else {
            last.next = newNode;
            newNode.prev = last;
            last = newNode;
        }
        ++n;
    }

    public MyListNode removeFirst() {
        MyListNode oldFirst = first;
        if (n == 1) {
            first = null;
            last = null;
        } else {
            first = first.next;
            first.prev = null;
            oldFirst.next = null;
        }
        --n;
        return oldFirst;
    }

    public MyListNode removeLast() {
        MyListNode oldLast = last;
        if (n == 1) {
            first = null;
            last = null;
        } else {
            last = last.prev;
            last.next = null;
            oldLast.prev = null;
        }
        --n;
        return oldLast;
    }

    public void remove(MyListNode delNode) {
        if (delNode == first) {
            removeFirst();
        } else if (delNode == last) {
            removeLast();
        } else {
            delNode.prev.next = delNode.next;
            delNode.next.prev = delNode.prev;
            delNode.prev = null;
            delNode.next = null;
            --n;
        }
    }
}

class LRUCache {
    private final MyDoublyLinkedList list = new MyDoublyLinkedList();
    private final Map<Integer, MyListNode> keyToNode = new HashMap<>();
    private final int capacity;

    public LRUCache(int capacity) {
        this.capacity = capacity;
    }

    public int get(int key) {
        if (contains(key)) {
            return touchCache(key, Integer.MIN_VALUE);
        }
        return -1;
    }

    public void put(int key, int value) {
        if (capacity > 0) {
            if (contains(key)) {
                touchCache(key, value);
            } else {
                if (full()) {
                    removeCache();
                }
                addCache(key, value);
            }
        }
    }

    private boolean contains(int key) {
        return keyToNode.containsKey(key);
    }

    private boolean full() {
        return keyToNode.size() == capacity;
    }

    private void addCache(int key, int val) {
        MyListNode newNode = new MyListNode(key, val);
        list.addLast(newNode);
        keyToNode.put(key, newNode);
    }

    private void removeCache() {
        keyToNode.remove(list.removeFirst().key);
    }

    private int touchCache(int key, int val) {
        MyListNode touchNode = keyToNode.get(key);
        if (val != Integer.MIN_VALUE) {
            touchNode.val = val;
        }
        list.remove(touchNode);
        list.addLast(touchNode);
        return touchNode.val;
    }
}
// https://leetcode.cn/submissions/detail/442124950/
```

```java
class LRUCache {
    private final Map<Integer, Integer> keyToVal = new LinkedHashMap<>();
    private final int capacity;

    public LRUCache(int capacity) {
        this.capacity = capacity;
    }

    public int get(int key) {
        if (contains(key)) {
            return touchCache(key, Integer.MIN_VALUE);
        }
        return -1;
    }

    public void put(int key, int value) {
        if (capacity > 0) {
            if (contains(key)) {
                touchCache(key, value);
            } else {
                if (full()) {
                    removeCache();
                }
                addCache(key, value);
            }
        }
    }

    private boolean contains(int key) {
        return keyToVal.containsKey(key);
    }

    private boolean full() {
        return keyToVal.size() == capacity;
    }

    private void addCache(int key, int val) {
        keyToVal.put(key, val);
    }

    private void removeCache() {
        int delKey = keyToVal.keySet().iterator().next();
        keyToVal.remove(delKey);
    }

    private int touchCache(int key, int val) {
        int newVal = keyToVal.get(key);
        if (val != Integer.MIN_VALUE) {
            newVal = val;
        }
        keyToVal.remove(key);
        keyToVal.put(key, newVal);
        return newVal;
    }
}
// https://leetcode.cn/submissions/detail/442129269/
```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```java
class Solution {
    public int findMin(int[] nums) {
        int lo = 0, hi = nums.length - 1;
        while (lo < hi) {
            int mid = lo + (hi - lo) / 2;
            if (nums[mid] < nums[hi]) {
                hi = mid;
            } else {
                lo = mid + 1;
            }
        }
        return nums[lo];
    }
}
// https://leetcode.cn/submissions/detail/348419979/
```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```java
class MinStack {
    private Deque<int[]> stack = new LinkedList();

    public MinStack() {

    }

    public void push(int val) {
        int min = (stack.isEmpty() ? val : Math.min(getMin(), val));
        stack.push(new int[]{val, min});
    }

    public void pop() {
        stack.pop();
    }

    public int top() {
        return stack.peek()[0];
    }

    public int getMin() {
        return stack.peek()[1];
    }
}
// https://leetcode.cn/submissions/detail/364641398/
```

```java
class MinStack {
    private Deque<Integer> stack1 = new LinkedList<Integer>();
    private Deque<Integer> stack2 = new LinkedList<Integer>();

    public MinStack() {

    }

    public void push(int val) {
        stack1.push(val);
        if (stack2.isEmpty() || getMin() >= val) {
            stack2.push(val);
        }
    }

    public void pop() {
        if (stack1.pop() == getMin()) {
            stack2.pop();
        }
    }

    public int top() {
        return stack1.peek();
    }

    public int getMin() {
        return stack2.peek();
    }
}
// https://leetcode.cn/submissions/detail/349250298/
```

```java
class MinStack {
    private int min = Integer.MAX_VALUE;
    private Deque<Integer> stack = new LinkedList<Integer>();

    public MinStack() {

    }

    public void push(int val) {
        if (getMin() >= val) {
            stack.push(min);
            min = val;
        }
        stack.push(val);
    }

    public void pop() {
        if (stack.pop() == min) {
            min = stack.pop();
        }
    }

    public int top() {
        return stack.peek();
    }

    public int getMin() {
        return min;
    }
}
// https://leetcode.cn/submissions/detail/349249224/
```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```java
public class Solution {
    public ListNode getIntersectionNode(ListNode headA, ListNode headB) {
        ListNode ptrA = headA;
        ListNode ptrB = headB;
        while (ptrA != ptrB) {
            ptrA = (ptrA == null ? headB : ptrA.next);
            ptrB = (ptrB == null ? headA : ptrB.next);
        }
        return ptrA;
    }
}
// https://leetcode.cn/submissions/detail/366014060/
```

```java
public class Solution {
    public ListNode getIntersectionNode(ListNode headA, ListNode headB) {
        Set<ListNode> set = new HashSet<>();
        ListNode ptr = headA;
        while (ptr != null) {
            set.add(ptr);
            ptr = ptr.next;
        }
        ptr = headB;
        while (ptr != null) {
            if (set.contains(ptr)) return ptr;
            ptr = ptr.next;
        }
        return null;
    }
}
// https://leetcode.cn/submissions/detail/340617028/
```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```java
class Solution {
    public int compareVersion(String version1, String version2) {
        int len1 = version1.length(), len2 = version2.length();
        int i = 0, j = 0;
        while (i < len1 || j < len2) {
            int r1 = 0;
            while (i < len1) {
                char c = version1.charAt(i++);
                if (c == '.') {
                    break;
                }
                r1 = r1 * 10 + (c - '0');
            }
            int r2 = 0;
            while (j < len2) {
                char c = version2.charAt(j++);
                if (c == '.') {
                    break;
                }
                r2 = r2 * 10 + (c - '0');
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
// https://leetcode.cn/submissions/detail/363320402/
```

```java
class Solution {
    public int compareVersion(String version1, String version2) {
        int len1 = version1.length(), len2 = version2.length();
        int i = 0, j = 0;
        StringBuilder sb1 = new StringBuilder();
        StringBuilder sb2 = new StringBuilder();
        while (i < len1 || j < len2) {
            sb1.setLength(0);
            sb1.append('0');
            while (i < len1) {
                char c = version1.charAt(i++);
                if (c == '.') {
                    break;
                }
                sb1.append(c);
            }
            sb2.setLength(0);
            sb2.append('0');
            while (j < len2) {
                char c = version2.charAt(j++);
                if (c == '.') {
                    break;
                }
                sb2.append(c);
            }
            int r1 = Integer.parseInt(sb1.toString());
            int r2 = Integer.parseInt(sb2.toString());
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
// https://leetcode.cn/submissions/detail/363323985/
```

```java
class Solution {
    public int compareVersion(String version1, String version2) {
        String[] revisions1 = version1.split("\\.");
        String[] revisions2 = version2.split("\\.");
        int n1 = revisions1.length, n2 = revisions2.length;
        int i = 0;
        while (i < n1 || i < n2) {
            int r1 = 0;
            if (i < n1) {
                r1 = Integer.parseInt(revisions1[i]);
            }
            int r2 = 0;
            if (i < n2) {
                r2 = Integer.parseInt(revisions2[i]);
            }
            ++i;
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
// https://leetcode.cn/submissions/detail/368047262/
```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```java
class Solution {
    public int[] twoSum(int[] numbers, int target) {
        int left = 0;
        int right = numbers.length - 1;
        while (left < right) {
            int sum = numbers[left] + numbers[right];
            if (sum > target) {
                right--;
            } else if (sum < target) {
                left++;
            } else {
                return new int[]{left + 1, right + 1};
            }
        }
        return new int[]{-1, -1};
    }
}
// https://leetcode.cn/submissions/detail/341136281/
```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```java
class Solution {
    public int majorityElement(int[] nums) {
        int candidate = Integer.MIN_VALUE;
        int count = 0;
        for (int x : nums) {
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
// https://leetcode.cn/submissions/detail/364344693/
```

```java
class Solution {
    public int majorityElement(int[] nums) {
        Map<Integer, Integer> times = new HashMap();
        int half = nums.length / 2;
        for (int num : nums) {
            int t = times.getOrDefault(num, 0) + 1;
            if (t > half) {
                return num;
            }
            times.put(num, t);
        }
        return Integer.MIN_VALUE;
    }
}
// https://leetcode.cn/submissions/detail/358158495/
```

```java
class Solution {
    public int majorityElement(int[] nums) {
        Arrays.sort(nums);
        return nums[nums.length / 2];
    }
}
// https://leetcode.cn/submissions/detail/349720053/
```

```java
class Solution {
    public int majorityElement(int[] nums) {
        Arrays.sort(nums);
        int n = nums.length;
        int half = n / 2;
        int i = 0;
        while (i < n) {
            int v = nums[i];
            int j = i + 1;
            while (j < n && nums[j] == v) {
                ++j;
            }
            if (j - i > half) {
                return v;
            }
            i = j;
        }
        return Integer.MIN_VALUE;
    }
}
// https://leetcode.cn/submissions/detail/358166250/
```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```java
class Solution {
    public String largestNumber(int[] nums) {
        int n = nums.length;
        String[] strs = new String[n];
        for (int i = 0; i < n; ++i) {
            strs[i] = Integer.toString(nums[i]);
        }
        Arrays.sort(strs, (s1, s2) -> (s2 + s1).compareTo(s1 + s2));
        StringBuilder sb = new StringBuilder();
        for (String s : strs) {
            sb.append(s);
        }
        String ans = sb.toString();
        return ans.charAt(0) == '0' ? "0" : ans;
    }
}
// https://leetcode.cn/submissions/detail/349008072/
```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```java
class Solution {
    public int maxProfit(int k, int[] prices) {
        int n = prices.length;
        if (k <= 0 || n <= 1) {
            return 0;
        }
        // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
        // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
        int[][][] dp = new int[k + 1][n][2];
        // 交易次数限制为 0 时
        // 填写第 0 个 n x 2 矩阵
        for (int i = 0; i < n; ++i) {
            dp[0][i][0] = 0;
            dp[0][i][1] = Integer.MIN_VALUE;
        }
        // 交易次数限制为 [1..k] 时
        for (int t = 1; t <= k; ++t) {
            // 填写第 t 个 n x 2 矩阵
            dp[t][0][0] = 0;
            dp[t][0][1] = -prices[0];
            for (int i = 1; i < n; ++i) {
                // dp[t][i - 1][0]             >= dp[t - 1][i - 1][0] - prices[i]
                // dp[t][i - 1][1] + prices[i] >= dp[t][i - 1][1]
                // => dp[t][i][0] >= dp[t][i][1]
                dp[t][i][0] = Math.max(dp[t][i - 1][0], dp[t][i - 1][1] + prices[i]);
                dp[t][i][1] = Math.max(dp[t - 1][i - 1][0] - prices[i], dp[t][i - 1][1]);
            }
        }
        return dp[k][n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/365507888/
```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```java
class Solution {
    public void rotate(int[] nums, int k) {
        int n = nums.length;
        k %= n;
        if (k > 0) {
            reverse(nums, 0, n - 1);
            reverse(nums, 0, k - 1);
            reverse(nums, k, n - 1);
        }
    }

    private void reverse(int[] nums, int lo, int hi) {
        while (lo < hi) {
            exch(nums, lo++, hi--);
        }
    }

    private void exch(int[] nums, int i, int j) {
        int swap = nums[i];
        nums[i] = nums[j];
        nums[j] = swap;
    }
}
// https://leetcode.cn/submissions/detail/364370375/
```

```java
class Solution {
    public void rotate(int[] nums, int k) {
        int n = nums.length;
        k %= n;
        if (k > 0) {
            int[] aux = new int[n];
            for (int i = 0; i < n; i++) {
                aux[(i + k) % n] = nums[i];
            }
            System.arraycopy(aux, 0, nums, 0, n);
        }
    }
}
// https://leetcode.cn/submissions/detail/364371721/
```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```java
class Solution {
    public int rob(int[] nums) {
        return subseqSum(nums);
    }

    // max({sum(subseq) | subseq 是数组 nums 的不连续子序列})
    private int subseqSum(int[] nums) {
        int n = nums.length;
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return nums[0];
        }
        if (n == 2) {
            return Math.max(nums[0], nums[1]);
        }
        // dp[i] = max({sum(subseq) | subseq 是子数组 nums[0..i] 的不连续子序列})
        int[] dp = new int[n];
        dp[0] = nums[0];
        dp[1] = Math.max(nums[0], nums[1]);
        for (int i = 2; i < n; ++i) {
            // 包含 nums[i]
            int sp1 = dp[i - 2] + nums[i];
            // 不包含 nums[i]
            int sp2 = dp[i - 1];
            dp[i] = Math.max(sp1, sp2);
        }
        return dp[n - 1];
    }
}
// https://leetcode.cn/submissions/detail/374740861/
```

```java
class Solution {
    private int[] memo;
    private int ans;

    public int rob(int[] nums) {
        int n = nums.length;
        memo = new int[n];
        for (int i = 0; i < n; i++) {
            memo[i] = -1;
        }
        ans = Integer.MIN_VALUE;
        for (int i = 0; i < n; i++) {
            dp(nums, i);
        }
        return ans;
    }

    private int dp(int[] nums, int i) {
        if (memo[i] > -1) return memo[i];
        if (i == 0) {
            memo[0] = nums[0];
            ans = Math.max(ans, memo[0]);
            return memo[0];
        }
        if (i == 1) {
            memo[1] = nums[1];
            ans = Math.max(ans, memo[1]);
            return memo[1];
        }
        int sp = Integer.MIN_VALUE;
        for (int j = i - 2; j >= 0; j--) {
            sp = Math.max(sp, dp(nums, j));
        }
        memo[i] = nums[i] + sp;
        ans = Math.max(ans, memo[i]);
        return memo[i];
    }
}
// https://leetcode.cn/submissions/detail/331861729/
```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```java
class Solution {
    public List<Integer> rightSideView(TreeNode root) {
        List<Integer> list = new LinkedList();
        Deque<TreeNode> queue = new LinkedList();
        if (root != null) {
            queue.addLast(root);
        }
        while (!queue.isEmpty()) {
            list.add(queue.getLast().val);
            int sz = queue.size();
            for (int i = 0; i < sz; ++i) {
                TreeNode x = queue.removeFirst();
                TreeNode left = x.left;
                if (left != null) {
                    queue.addLast(left);
                }
                TreeNode right = x.right;
                if (right != null) {
                    queue.addLast(right);
                }
            }
        }
        return list;
    }
}
// https://leetcode.cn/submissions/detail/364462814/
```

```java
class Solution {
    public List<Integer> rightSideView(TreeNode root) {
        List<Integer> list = new LinkedList();
        Queue<TreeNode> queue = new LinkedList();
        if (root != null) {
            queue.offer(root);
        }
        while (!queue.isEmpty()) {
            list.add(queue.peek().val);
            int sz = queue.size();
            for (int i = 0; i < sz; ++i) {
                TreeNode x = queue.poll();
                if (x.right != null) {
                    queue.offer(x.right);
                }
                if (x.left != null) {
                    queue.offer(x.left);
                }
            }
        }
        return list;
    }
}
// https://leetcode.cn/submissions/detail/350423916/
```

```java
class Solution {
    public List<Integer> rightSideView(TreeNode root) {
        Map<Integer, Integer> map = new HashMap();
        dfs(root, 0, map);
        List<Integer> list = new LinkedList();
        for (int i = 0; i < map.size(); ++i) {
            list.add(map.get(i));
        }
        return list;
    }

    private void dfs(TreeNode root, int depth, Map<Integer, Integer> map) {
        if (root == null) {
            return;
        }
        map.put(depth, root.val);
        dfs(root.left, depth + 1, map);
        dfs(root.right, depth + 1, map);
    }
}
// https://leetcode.cn/submissions/detail/350410018/
```

```java
class Solution {
    public List<Integer> rightSideView(TreeNode root) {
        List<Integer> list = new LinkedList();
        dfs(root, 0, list);
        return list;
    }

    private void dfs(TreeNode root, int depth, List<Integer> list) {
        if (root == null) {
            return;
        }
        if (list.size() == depth) {
            list.add(root.val);
        }
        dfs(root.right, depth + 1, list);
        dfs(root.left, depth + 1, list);
    }
}
// https://leetcode.cn/submissions/detail/350413845/
```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```java
class Solution {
    private static final char LAND = '1';
    private static final char WATER = '0';

    public int numIslands(char[][] grid) {
        int count = 0;
        for (int row = 0; row < grid.length; ++row) {
            for (int col = 0; col < grid[0].length; ++col) {
                if (grid[row][col] == LAND) {
                    floodFill(grid, row, col);
                    ++count;
                }
            }
        }
        return count;
    }

    private void floodFill(char[][] grid, int row, int col) {
        if (row < 0 || row >= grid.length || col < 0 || col >= grid[0].length || grid[row][col] == WATER) {
            return;
        }
        grid[row][col] = WATER;
        floodFill(grid, row, col + 1);
        floodFill(grid, row, col - 1);
        floodFill(grid, row + 1, col);
        floodFill(grid, row - 1, col);
    }
}
// https://leetcode.cn/submissions/detail/404383694/
```

```java
class Solution {
    private class UF {
        private int[] parent;
        private byte[] rank;
        private int count;

        public UF(int n) {
            count = n;
            parent = new int[n];
            rank = new byte[n];
            for (int i = 0; i < n; i++) {
                parent[i] = i;
                rank[i] = 0;
            }
        }

        public int find(int p) {
            while (p != parent[p]) {
                parent[p] = parent[parent[p]];
                p = parent[p];
            }
            return p;
        }

        public void union(int p, int q) {
            int rootP = find(p);
            int rootQ = find(q);
            if (rootP != rootQ) {
                if (rank[rootP] < rank[rootQ]) {
                    parent[rootP] = rootQ;
                } else if (rank[rootP] > rank[rootQ]) {
                    parent[rootQ] = rootP;
                } else {
                    parent[rootP] = rootQ;
                    ++rank[rootQ];
                }
                --count;
            }
        }

        public boolean connected(int p, int q) {
            return find(p) == find(q);
        }

        public int count() {
            return count;
        }
    }

    public int numIslands(char[][] grid) {
        int m = grid.length, n = grid[0].length;
        UF uf = new UF(m * n);
        int zero = 0;
        int[][] directions = new int[][]{{0, 1}, {0, -1}, {1, 0}, {-1, 0}};
        for (int i = 0; i < m; ++i) {
            for (int j = 0; j < n; ++j) {
                if (grid[i][j] == '1') {
                    for (int[] d : directions) {
                        int x = i + d[0];
                        int y = j + d[1];
                        if (0 <= x && x <= m - 1 && 0 <= y && y <= n - 1) {
                            if (grid[x][y] == '1') {
                                int p = i * n + j;
                                int q = x * n + y;
                                uf.union(p, q);
                            }
                        }
                    }
                } else {
                    ++zero;
                }
            }
        }
        return uf.count() - zero;
    }
}
// https://leetcode.cn/submissions/detail/358193444/
```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```java
// TODO
```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```java
class Solution {
    public ListNode reverseList(ListNode head) {
        ListNode reverseHead = null;
        while (head != null) {
            ListNode nextHead = head.next;
            head.next = reverseHead;
            reverseHead = head;
            head = nextHead;
        }
        return reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/442649619/
```

```java
class Solution {
    public ListNode reverseList(ListNode head) {
        if (head == null || head.next == null) {
            return head;
        }
        ListNode nextHead = head.next;
        head.next = null;
        ListNode reverseHead = reverseList(nextHead);
        nextHead.next = head;
        return reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/367690337/
```

```java
class Solution {
    private ListNode ptr;

    public ListNode reverseList(ListNode head) {
        ListNode dummyHead = new ListNode();
        ptr = dummyHead;
        dfs(head);
        return dummyHead.next;
    }

    private void dfs(ListNode head) {
        if (head == null) {
            return;
        }
        ListNode nextHead = head.next;
        head.next = null;
        dfs(nextHead);
        ptr.next = head;
        ptr = ptr.next;
    }
}
// https://leetcode.cn/submissions/detail/442646330/
```

```java
class Solution {
    public ListNode reverseList(ListNode head) {
        Deque<ListNode> stack = new LinkedList<>();
        while (head != null) {
            ListNode nextHead = head.next;
            head.next = null;
            stack.push(head);
            head = nextHead;
        }
        ListNode dummyHead = new ListNode();
        ListNode ptr = dummyHead;
        while (!stack.isEmpty()) {
            ptr.next = stack.pop();
            ptr = ptr.next;
        }
        return dummyHead.next;
    }
}
// https://leetcode.cn/submissions/detail/442649017/
```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```java
class Solution {
    private boolean[] marked;
    private boolean[] onStack;
    private boolean hasCycle;

    public boolean canFinish(int numCourses, int[][] prerequisites) {
        marked = new boolean[numCourses];
        onStack = new boolean[numCourses];

        List<Integer>[] graph = new LinkedList[numCourses];
        for (int v = 0; v < numCourses; v++) {
            graph[v] = new LinkedList();
        }

        for (int[] p : prerequisites) {
            int v = p[1];
            int w = p[0];
            graph[v].add(w);
        }

        for (int v = 0; v < numCourses; v++) {
            if (!marked[v]) {
                dfs(graph, v);
            }
        }
        return !hasCycle;
    }

    private void dfs(List<Integer>[] graph, int v) {
        onStack[v] = true;
        marked[v] = true;
        for (int w : graph[v]) {
            if (hasCycle) return;
            if (!marked[w]) {
                dfs(graph, w);
            } else if (onStack[w]) {
                hasCycle = true;
                return;
            }
        }
        onStack[v] = false;
    }
}
// https://leetcode.cn/submissions/detail/326210480/
```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```java
class Solution {
    private boolean[] marked;
    private boolean[] onStack;
    private boolean hasCycle;
    private Deque<Integer> reversePostOrder;

    public int[] findOrder(int numCourses, int[][] prerequisites) {
        marked = new boolean[numCourses];
        onStack = new boolean[numCourses];
        reversePostOrder = new LinkedList();

        List<Integer>[] graph = new LinkedList[numCourses];
        for (int v = 0; v < numCourses; v++) {
            graph[v] = new LinkedList();
        }

        for (int[] p : prerequisites) {
            int v = p[1];
            int w = p[0];
            graph[v].add(w);
        }

        for (int v = 0; v < numCourses; v++) {
            if (!marked[v]) {
                dfs(graph, v);
            }
        }

        return (hasCycle ? new int[]{} : reversePostOrder.stream().mapToInt(i -> i).toArray());
    }

    private void dfs(List<Integer>[] graph, int v) {
        onStack[v] = true;
        marked[v] = true;
        for (int w : graph[v]) {
            if (hasCycle) return;
            if (!marked[w]) {
                dfs(graph, w);
            } else if (onStack[w]) {
                hasCycle = true;
                return;
            }
        }
        reversePostOrder.push(v);
        onStack[v] = false;
    }
}
// https://leetcode.cn/submissions/detail/326216092/
```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```java
class Solution {
    public int rob(int[] nums) {
        int n = nums.length;
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return nums[0];
        }
        return Math.max(subseqSum(nums, 0, n - 2), subseqSum(nums, 1, n - 1));
    }

    // max({sum(subseq) | subseq 是子数组 nums[lo..hi] 的不连续子序列})
    private int subseqSum(int[] nums, int lo, int hi) {
        int n = hi - lo + 1;
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return nums[lo];
        }
        if (n == 2) {
            return Math.max(nums[lo], nums[lo + 1]);
        }
        // dp[i] = max({sum(subseq) | subseq 是子数组 nums[lo..lo+i] 的不连续子序列})
        int[] dp = new int[n];
        dp[0] = nums[lo];
        dp[1] = Math.max(nums[lo], nums[lo + 1]);
        for (int i = 2; i < n; ++i) {
            // 包含 nums[lo+i]
            int sp1 = dp[i - 2] + nums[lo + i];
            // 不包含 nums[lo+i]
            int sp2 = dp[i - 1];
            dp[i] = Math.max(sp1, sp2);
        }
        return dp[n - 1];
    }
}
// https://leetcode.cn/submissions/detail/374748775/
```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```java
class Solution {
    public int findKthLargest(int[] nums, int k) {
        return select(nums, nums.length - k);
    }

    // 返回数组 nums 从小到大排在第 rank 位的元素，排位从 0 开始计算，
    // 相当于有 rank 个元素小于该元素。
    private int select(int[] nums, int rank) {
        int lo = 0, hi = nums.length - 1;
        while (lo <= hi) {
            int j = partition(nums, lo, hi);
            if (rank < j) {
                hi = j - 1;
            } else if (j < rank) {
                lo = j + 1;
            } else {
                return nums[j];
            }
        }
        return Integer.MIN_VALUE;
    }

    private int partition(int[] nums, int lo, int hi) {
        if (lo == hi) {
            return lo;
        }
        int v = nums[lo];
        int i = lo, j = hi + 1;
        while (true) {
            while (nums[++i] < v) {
                if (i == hi) {
                    break;
                }
            }
            while (nums[--j] > v) {
                if (j == lo) {
                    break;
                }
            }
            if (i >= j) {
                break;
            }
            exch(nums, i, j);
        }
        exch(nums, lo, j);
        return j;
    }

    private void exch(int[] nums, int i, int j) {
        int swap = nums[i];
        nums[i] = nums[j];
        nums[j] = swap;
    }
}
// https://leetcode.cn/submissions/detail/367995685/
```

```java
class Solution {
    public int findKthLargest(int[] nums, int k) {
        PriorityQueue<Integer> maxPQ = new PriorityQueue(Collections.reverseOrder());
        for (int x : nums) {
            maxPQ.offer(x);
        }
        for (int i = 1; i <= k - 1; ++i) {
            maxPQ.poll();
        }
        return maxPQ.peek();
    }
}
// https://leetcode.cn/submissions/detail/366039238/
```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```java
class Solution {
    private int k, n;
    private int pathSum = 0;
    private List<Integer> path = new LinkedList(); // 取 [1..9] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> combinationSum3(int k, int n) {
        this.k = k;
        this.n = n;
        backtrack(0);
        return ans;
    }

    // edge = 取 [1..9] 为值
    private void backtrack(int edge) {
        if (path.size() == k && pathSum == n) {
            ans.add(new LinkedList(path));
        } else if (path.size() < k && pathSum < n) {
            // 避免重复，从 edge + 1 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            while (++edge <= 9) {
                if (pathSum + edge <= n) {
                    pathSum += edge;
                    path.add(edge);
                    backtrack(edge);
                    path.remove(path.size() - 1);
                    pathSum -= edge;
                }
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/373531038/
```

```java
class Solution {
    private int k, n;
    private int pathSum = 0;
    private List<Integer> path = new LinkedList(); // 取 [1..9] 为元素
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> combinationSum3(int k, int n) {
        this.k = k;
        this.n = n;
        dfs(0);
        return ans;
    }

    private void dfs(int vertex) {
        if (vertex > 0) {
            pathSum += vertex;
            path.add(vertex);
        }
        if (path.size() == k && pathSum == n) {
            ans.add(new LinkedList(path));
        } else if (path.size() < k && pathSum < n) {
            // 避免重复，从 vertex + 1 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            int v = vertex;
            while (++v <= 9) {
                if (pathSum + v <= n) {
                    dfs(v);
                }
            }
        }
        if (vertex > 0) {
            path.remove(path.size() - 1);
            pathSum -= vertex;
        }
    }
}
// https://leetcode.cn/submissions/detail/373529166/
```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```java
class Solution {
    public int countNodes(TreeNode root) {
        if (root == null) return 0;

        int leftHeight = 0;
        TreeNode ptr = root.left;
        while (ptr != null) {
            leftHeight++;
            ptr = ptr.left;
        }

        int rightHeight = 0;
        ptr = root.right;
        while (ptr != null) {
            rightHeight++;
            ptr = ptr.right;
        }

        if (leftHeight == rightHeight) return (int) Math.pow(2, leftHeight + 1) - 1;

        return 1 + countNodes(root.left) + countNodes(root.right);
    }
}
// https://leetcode.cn/submissions/detail/324438003/
```

```java
class Solution {
    public int countNodes(TreeNode root) {
        if (root == null) return 0;
        return 1 + countNodes(root.left) + countNodes(root.right);
    }
}
// https://leetcode.cn/submissions/detail/324427210/
```

```java
class Solution {
    private int count = 0;

    public int countNodes(TreeNode root) {
        traverse(root);
        return count;
    }

    private void traverse(TreeNode root) {
        if (root == null) return;
        count++;
        traverse(root.left);
        traverse(root.right);
    }
}
// https://leetcode.cn/submissions/detail/324428257/
```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```java
class MyStack {
    private Queue<Integer> queue = new LinkedList();

    public MyStack() {

    }

    public void push(int x) {
        queue.offer(x);
        for (int i = 1; i < queue.size(); ++i) {
            queue.offer(pop());
        }
    }

    public int pop() {
        return queue.poll();
    }

    public int top() {
        return queue.peek();
    }

    public boolean empty() {
        return queue.isEmpty();
    }
}
// https://leetcode.cn/submissions/detail/364629726/
```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```java
class Solution {
    public TreeNode invertTree(TreeNode root) {
        if (root == null) return null;
        TreeNode left = invertTree(root.left);
        TreeNode right = invertTree(root.right);
        root.right = left;
        root.left = right;
        return root;
    }
}
// https://leetcode.cn/submissions/detail/317421010/
```

```java
class Solution {
    public TreeNode invertTree(TreeNode root) {
        if (root == null) return null;
        TreeNode left = root.left;
        TreeNode right = root.right;
        root.left = right;
        root.right = left;
        invertTree(root.left);
        invertTree(root.right);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/343384224/
```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```java
class Solution {
    private Map<TreeNode, Integer> memo = new HashMap();

    public int kthSmallest(TreeNode root, int k) {
        return select(root, k - 1);
    }

    private int select(TreeNode root, int rank) {
        if (root == null) {
            return -1;
        }
        int leftSize = size(root.left);
        if (rank < leftSize) {
            return select(root.left, rank);
        }
        if (leftSize < rank) {
            return select(root.right, rank - leftSize - 1);
        }
        return root.val;
    }

    private int size(TreeNode root) {
        if (root == null) {
            return 0;
        }
        if (memo.containsKey(root)) {
            return memo.get(root);
        }
        int res = 1 + size(root.left) + size(root.right);
        memo.put(root, res);
        return res;
    }
}
// https://leetcode.cn/submissions/detail/368939131/
```

```java
class Solution {
    int ans = 0;
    int rank = 0;

    public int kthSmallest(TreeNode root, int k) {
        traverse(root, k);
        return ans;
    }

    void traverse(TreeNode root, int k) {
        if (root == null) {
            return;
        }
        traverse(root.left, k);
        if (++rank == k) {
            ans = root.val;
            return;
        }
        traverse(root.right, k);
    }
}
// https://leetcode.cn/submissions/detail/322638349/
```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```java
/**
 * ------------------| |--------------------
 * pop <- Left Stack | | Right Stack <- push
 * ------------------| |--------------------
 */
class MyQueue {
    private Stack<Integer> left = new Stack();
    private Stack<Integer> right = new Stack();

    public MyQueue() {

    }

    public void push(int x) {
        right.push(x);
    }

    public int pop() {
        if (left.isEmpty()) {
            move();
        }
        return left.pop();
    }

    public int peek() {
        if (left.isEmpty()) {
            move();
        }
        return left.peek();
    }

    public boolean empty() {
        return left.isEmpty() && right.isEmpty();
    }

    private void move() {
        while (!right.isEmpty()) {
            left.push(right.pop());
        }
    }
}
// https://leetcode.cn/submissions/detail/364380437/
```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```java
class Solution {
    public boolean isPalindrome(ListNode head) {
        // 寻找链表的中点（偶数个节点时选择左侧），即前半部分链表的尾节点
        ListNode mid = head, ptr = head;
        while (ptr.next != null && ptr.next.next != null) {
            mid = mid.next;
            ptr = ptr.next.next;
        }
        // 翻转后半部分链表
        ListNode reverseHead = reverseList(mid.next);
        mid.next = null;
        // 判断是否回文链表
        ListNode left = head;
        ListNode right = reverseHead;
        while (right != null) {
            if (left.val != right.val) {
                return false;
            }
            left = left.next;
            right = right.next;
        }
        // 还原链表
        mid.next = reverseList(reverseHead);
        return true;
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
// https://leetcode.cn/submissions/detail/356156224/
```

```java
class Solution {
    private boolean ans = true;
    private ListNode ptr = null;

    public boolean isPalindrome(ListNode head) {
        ptr = head;
        dfs(head);
        return ans;
    }

    private void dfs(ListNode head) {
        if (head == null) {
            return;
        }
        dfs(head.next);
        if (head.val != ptr.val) {
            ans = false;
        }
        ptr = ptr.next;
    }
}
// https://leetcode.cn/submissions/detail/366670737/
```

```java
class Solution {
    public boolean isPalindrome(ListNode head) {
        Deque<ListNode> stack = new LinkedList<ListNode>();
        ListNode ptr = head;
        while (ptr != null) {
            stack.push(ptr);
            ptr = ptr.next;
        }
        ptr = head;
        while (!stack.isEmpty()) {
            ListNode x = stack.pop();
            if (ptr.val != x.val) {
                return false;
            }
            ptr = ptr.next;
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/354860775/
```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```java
class Solution {
    public TreeNode lowestCommonAncestor(TreeNode root, TreeNode p, TreeNode q) {
        // 保证 p < q
        if (p.val > q.val) {
            return lowestCommonAncestor(root, q, p);
        }
        if (q.val < root.val) {
            return lowestCommonAncestor(root.left, p, q);
        }
        if (root.val < p.val) {
            return lowestCommonAncestor(root.right, p, q);
        }
        return root;
    }
}
// https://leetcode.cn/submissions/detail/394419891/
```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```java
class Solution {
    private TreeNode lca;

    public TreeNode lowestCommonAncestor(TreeNode root, TreeNode p, TreeNode q) {
        find(root, p, q);
        return lca;
    }

    // 在子树中查找节点 p 或 q，递归过程中确定『最近公共祖先』
    private boolean find(TreeNode root, TreeNode p, TreeNode q) {
        if (root == null) {
            return false;
        }
        if (root == p || root == q) {
            // 如果 lca(p,q) = p 或 q，则此处的 lca = root 是最终答案
            lca = root;
            return true;
        }
        boolean left = find(root.left, p, q);
        boolean right = find(root.right, p, q);
        // 否则返回到某祖先节点处的 lca = root 才是最终答案
        if (left && right) {
            lca = root;
        }
        return left || right;
    }
}
// https://leetcode.cn/submissions/detail/356180045/
```

```java
class Solution {
    public TreeNode lowestCommonAncestor(TreeNode root, TreeNode p, TreeNode q) {
        Map<TreeNode, TreeNode> parent = new HashMap();
        dfs(root, parent);
        Set<TreeNode> visited = new HashSet();
        while (p != null) {
            visited.add(p);
            p = parent.get(p);
        }
        while (q != null) {
            if (visited.contains(q)) {
                return q;
            }
            q = parent.get(q);
        }
        return root;
    }

    private void dfs(TreeNode root, Map<TreeNode, TreeNode> parent) {
        TreeNode left = root.left;
        if (left != null) {
            parent.put(left, root);
            dfs(left, parent);
        }
        TreeNode right = root.right;
        if (right != null) {
            parent.put(right, root);
            dfs(right, parent);
        }
    }
}
// https://leetcode.cn/submissions/detail/355579963/
```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```java
// TODO
```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```java
class Solution {
    public int[] maxSlidingWindow(int[] nums, int k) {
        List<Integer> list = new LinkedList<>();
        Deque<Integer> maxMonoQueue = new LinkedList<>();
        for (int i = 0; i < nums.length; ++i) {
            // nums[i] = 进入窗口的数字
            int x = nums[i];
            while (!maxMonoQueue.isEmpty() && maxMonoQueue.getLast() < x) {
                maxMonoQueue.removeLast();
            }
            maxMonoQueue.addLast(x);
            if (i < k - 1) {
                continue;
            }
            // nums[i-k] = 退出窗口的数字
            if (i >= k && nums[i - k] == maxMonoQueue.getFirst()) {
                maxMonoQueue.removeFirst();
            }
            list.add(maxMonoQueue.getFirst());
        }
        int[] ans = new int[list.size()];
        int i = 0;
        for (int x : list) {
            ans[i++] = x;
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/406238156/
```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```java
class Solution {
    public int minMeetingRooms(int[][] intervals) {
        int n = intervals.length;
        int[] begin = new int[n];
        int[] end = new int[n];
        for (int i = 0; i < n; i++) {
            begin[i] = intervals[i][0];
            end[i] = intervals[i][1];
        }
        Arrays.sort(begin);
        Arrays.sort(end);
        int count = 0, ans = 0;
        int i = 0, j = 0;
        while (i < n && j < n) {
            if (begin[i] < end[j]) {
                count++;
                i++;
            } else {
                count--;
                j++;
            }
            ans = Math.max(ans, count);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/333874098/
```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```java
class Solution {
    public void moveZeroes(int[] nums) {
        // [0..i-1] != 0
        // [i..j-1] == 0
        // [j..n-1] Scanning
        int i = 0, j = 0, n = nums.length;
        while (j < n) {
            while (j < n && nums[j] == 0) {
                ++j;
            }
            if (j < n) {
                exch(nums, i++, j++);
            }
        }
    }

    private void exch(int[] nums, int i, int j) {
        int swap = nums[i];
        nums[i] = nums[j];
        nums[j] = swap;
    }
}
// https://leetcode.cn/submissions/detail/369384859/
```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```java
public class Codec {
    // Encodes a tree to a single string.
    public String serialize(TreeNode root) {
        if (root == null) {
            return "#";
        }
        String left = serialize(root.left);
        String right = serialize(root.right);
        return String.valueOf(root.val) + "," + left + "," + right;
    }

    // Decodes your encoded data to tree.
    public TreeNode deserialize(String data) {
        Deque<String> queue = new LinkedList();
        for (String s : data.split(",")) {
            queue.addLast(s);
        }
        return buildTree(queue);
    }

    private TreeNode buildTree(Deque<String> queue) {
        String s = queue.removeFirst();
        if (s.equals("#")) {
            return null;
        }
        TreeNode root = new TreeNode(Integer.parseInt(s));
        root.left = buildTree(queue);
        root.right = buildTree(queue);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/368744798/
```

```java
public class Codec {
    private StringBuilder sb = new StringBuilder();

    // Encodes a tree to a single string.
    public String serialize(TreeNode root) {
        dfs(root);
        return sb.toString();
    }

    private void dfs(TreeNode root) {
        if (root == null) {
            sb.append("#").append(",");
            return;
        }
        sb.append(String.valueOf(root.val)).append(",");
        dfs(root.left);
        dfs(root.right);
    }

    // Decodes your encoded data to tree.
    public TreeNode deserialize(String data) {
        Deque<String> queue = new LinkedList();
        for (String s : data.split(",")) {
            queue.addLast(s);
        }
        return buildTree(queue);
    }

    private TreeNode buildTree(Deque<String> queue) {
        String s = queue.removeFirst();
        if (s.equals("#")) {
            return null;
        }
        TreeNode root = new TreeNode(Integer.parseInt(s));
        root.left = buildTree(queue);
        root.right = buildTree(queue);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/368746345/
```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```java
class Solution {
    public int lengthOfLIS(int[] nums) {
        int ans = 1;
        int n = nums.length;
        // dp[i] = 以 nums[i] 结尾的最长递增子序列的长度
        int[] dp = new int[n];
        dp[0] = 1;
        for (int i = 1; i < n; ++i) {
            int res = 1;
            for (int j = i - 1; j >= 0; --j) {
                if (nums[j] < nums[i]) {
                    res = Math.max(res, dp[j] + 1);
                }
            }
            dp[i] = res;
            ans = Math.max(ans, dp[i]);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/366680503/
```

```java
class Solution {
    public int lengthOfLIS(int[] nums) {
        int n = nums.length;
        int[] memo = new int[n];
        int ans = 1;
        for (int i = 0; i < n; ++i) {
            ans = Math.max(ans, dp(nums, i, memo));
        }
        return ans;
    }

    // 以 nums[i] 结尾的最长递增子序列的长度
    private int dp(int[] nums, int i, int[] memo) {
        if (memo[i] != 0) {
            return memo[i];
        }
        int res = 1;
        for (int j = i - 1; j >= 0; --j) {
            int sp = dp(nums, j, memo);
            if (nums[j] < nums[i]) {
                res = Math.max(res, sp + 1);
            }
        }
        memo[i] = res;
        return res;
    }
}
// https://leetcode.cn/submissions/detail/355566636/
```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```java
class NumArray {
    private int[] sum;

    public NumArray(int[] nums) {
        int n = nums.length;
        sum = new int[n];
        sum[0] = nums[0];
        for (int i = 1; i < n; ++i) {
            sum[i] = sum[i - 1] + nums[i];
        }
    }

    public int sumRange(int left, int right) {
        if (left == 0) {
            return sum[right];
        }
        return sum[right] - sum[left - 1];
    }
}
// https://leetcode.cn/submissions/detail/369386410/
```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```java
class Solution {
    public int maxProfit(int[] prices) {
        int n = prices.length;
        if (n <= 1) {
            return 0;
        }
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        int[][] dp = new int[n][2];
        dp[0][0] = 0;
        dp[0][1] = -prices[0];
        dp[1][0] = Math.max(dp[0][0], dp[0][1] + prices[1]);
        dp[1][1] = Math.max(dp[0][0] - prices[1], dp[0][1]);
        for (int i = 2; i < n; ++i) {
            // dp[i - 1][0]             >= dp[i - 2][0] >= p[i - 2][0] - prices[i]
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = Math.max(dp[i - 2][0] - prices[i], dp[i - 1][1]);
        }
        return dp[n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/365505572/
```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```java
class Solution {
    private int[] counts;

    private class Pair implements Comparable<Pair> {
        public int val;
        public int idx;

        public Pair(int val, int idx) {
            this.val = val;
            this.idx = idx;
        }

        public int compareTo(Pair that) {
            return this.val - that.val;
        }
    }

    public List<Integer> countSmaller(int[] nums) {
        int n = nums.length;
        counts = new int[n];
        Comparable[] a = new Pair[n];
        for (int i = 0; i < n; ++i) {
            a[i] = new Pair(nums[i], i);
        }
        sort(a);
        List<Integer> list = new LinkedList();
        for (int x : counts) {
            list.add(x);
        }
        return list;
    }

    private void sort(Comparable[] a) {
        int n = a.length;
        Comparable[] aux = new Pair[n];
        sort(a, 0, n - 1, aux);
    }

    private void sort(Comparable[] a, int lo, int hi, Comparable[] aux) {
        if (lo >= hi) {
            return;
        }
        int mid = lo + (hi - lo) / 2;
        sort(a, lo, mid, aux);
        sort(a, mid + 1, hi, aux);
        merge(a, lo, mid, hi, aux);
    }

    private void merge(Comparable[] a, int lo, int mid, int hi, Comparable[] aux) {
        for (int k = lo; k <= hi; ++k) {
            aux[k] = a[k];
        }
        int i = lo, j = mid + 1;
        for (int k = lo; k <= hi; ++k) {
            if (i > mid || (j <= hi && less(aux[j], aux[i]))) {
                a[k] = aux[j++];
            } else {
                Pair p = (Pair) aux[i];
                // aux[mid+1..j) < aux[i]
                counts[p.idx] += (j - mid - 1);
                a[k] = aux[i++];
            }
        }
    }

    private boolean less(Comparable v, Comparable w) {
        if (v == w) {
            return false;
        }
        return v.compareTo(w) < 0;
    }
}
// https://leetcode.cn/submissions/detail/366616178/
```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```java
class Solution {
    public int coinChange(int[] coins, int amount) {
        // dp[i] = 凑成总金额 i 所需的最少的硬币个数
        int[] dp = new int[amount + 1];
        dp[0] = 0;
        for (int i = 1; i <= amount; ++i) {
            int res = Integer.MAX_VALUE;
            // c       = 选择放入的硬币
            // i-c     = 剩余总金额
            // dp[i-c] = 凑成剩余总金额所需的最少的硬币个数
            for (int c : coins) {
                int x = i - c;
                if (x >= 0 && dp[x] != -1) {
                    res = Math.min(res, dp[x] + 1);
                }
            }
            dp[i] = (res == Integer.MAX_VALUE ? -1 : res);
        }
        return dp[amount];
    }
}
// https://leetcode.cn/submissions/detail/372575252/
```

```java
class Solution {
    HashMap<Integer, Integer> memo = new HashMap<>();

    public int coinChange(int[] coins, int amount) {
        if (amount == 0) return 0;
        if (amount < 0) return -1;

        if (memo.get(amount) != null) {
            return memo.get(amount);
        }

        int result = Integer.MAX_VALUE;
        for (int c : coins) {
            int sp = coinChange(coins, amount - c);
            if (sp >= 0) {
                result = Math.min(result, sp + 1);
            }
        }

        if (result == Integer.MAX_VALUE) {
            result = -1;
        }
        memo.put(amount, result);

        return result;
    }
}
// https://leetcode.cn/submissions/detail/329261401/
```

```java
class Solution {
    public int coinChange(int[] coins, int amount) {
        int n = coins.length;
        // dp[i][j] = 使用硬币 coins[0..i-1] 凑成总金额 j 所需的最少的硬币个数
        int[][] dp = new int[n + 1][amount + 1];
        // 总金额为 0
        for (int i = 1; i <= n; ++i) {
            dp[i][0] = 0;
        }
        // 硬币数为 0
        for (int j = 1; j <= amount; ++j) {
            dp[0][j] = -1;
        }
        dp[0][0] = 0;
        for (int i = 1; i <= n; ++i) {
            for (int j = 1; j <= amount; ++j) {
                int x = coins[i - 1];
                if (j < x) {
                    // 不包含硬币 x
                    dp[i][j] = dp[i - 1][j];
                } else {
                    int sp1 = dp[i - 1][j]; // 包含    0 个硬币 x
                    int sp2 = dp[i][j - x]; // 包含 >= 1 个硬币 x
                    int res = Integer.MAX_VALUE;
                    if (sp1 != -1) {
                        res = Math.min(res, sp1);
                    }
                    if (sp2 != -1) {
                        res = Math.min(res, sp2 + 1);
                    }
                    dp[i][j] = (res == Integer.MAX_VALUE ? -1 : res);
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
    }
}
// https://leetcode.cn/submissions/detail/372573476/
```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```java
class Solution {
    private final Map<TreeNode, Integer> memo = new HashMap<>();

    // 返回在二叉树 root，能盗取的最高金额
    public int rob(TreeNode root) {
        if (root == null) {
            return 0;
        }
        if (!memo.containsKey(root)) {
            // 不偷 root
            int sp1 = rob(root.left) + rob(root.right);
            // 偷 root
            int sp2 = root.val;
            if (root.left != null) {
                sp2 += rob(root.left.left) + rob(root.left.right);
            }
            if (root.right != null) {
                sp2 += rob(root.right.left) + rob(root.right.right);
            }
            memo.put(root, Math.max(sp1, sp2));
        }
        return memo.get(root);
    }
}
// https://leetcode.cn/submissions/detail/452714303/
```

```java
class Solution {
    public int rob(TreeNode root) {
        int[] ans = dp(root);
        return Math.max(ans[0], ans[1]);
    }

    // 定义
    // a[0] 不抢 root 的最高金额
    // a[1] 抢 root 的最高金额
    private int[] dp(TreeNode root) {
        if (root == null) return new int[]{0, 0};
        int[] left = dp(root.left);
        int[] right = dp(root.right);
        int rob = root.val + left[0] + right[0];
        int notRob = Math.max(left[0], left[1]) +
                Math.max(right[0], right[1]);
        return new int[]{notRob, rob};
    }
}
// https://leetcode.cn/submissions/detail/332286652/
```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```java
class Solution {
    public void reverseString(char[] s) {
        int left = 0, right = s.length - 1;
        while (left < right) {
            exch(s, left++, right--);
        }
    }

    void exch(char[] a, int i, int j) {
        char temp = a[i];
        a[i] = a[j];
        a[j] = temp;
    }
}
// https://leetcode.cn/submissions/detail/321504650/
```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```java
class Solution {
    public int maxEnvelopes(int[][] envelopes) {
        Arrays.sort(envelopes, (a, b) -> (a[0] == b[0] ? a[1] - b[1] : a[0] - b[0]));
        int n = envelopes.length;
        int[] dp = new int[n];
        dp[0] = 1;
        for (int i = 1; i < n; i++) {
            int result = 1;
            for (int j = i - 1; j >= 0; j--) {
                if (greater(envelopes, i, j)) {
                    result = Math.max(result, dp[j] + 1);
                }
            }
            dp[i] = result;
        }
        int ans = 1;
        for (int i = 0; i < n; i++) {
            ans = Math.max(ans, dp[i]);
        }
        return ans;
    }

    private boolean greater(int[][] envelopes, int i, int j) {
        return envelopes[i][0] > envelopes[j][0] &&
                envelopes[i][1] > envelopes[j][1];
    }
}
// https://leetcode.cn/submissions/detail/330571443/
```

```java
class Solution {
    private int[] memo;

    public int maxEnvelopes(int[][] envelopes) {
        Arrays.sort(envelopes, (a, b) -> (a[0] == b[0] ? a[1] - b[1] : a[0] - b[0]));
        int n = envelopes.length;
        memo = new int[n];
        Arrays.fill(memo, Integer.MIN_VALUE);
        dp(envelopes, n - 1);
        int ans = 1;
        for (int i = 0; i < n; i++) {
            ans = Math.max(ans, memo[i]);
        }
        return ans;
    }

    private int dp(int[][] envelopes, int i) {
        if (memo[i] != Integer.MIN_VALUE) {
            return memo[i];
        }

        if (i == 0) {
            memo[0] = 1;
            return 1;
        }

        int result = 1;
        for (int j = i - 1; j >= 0; j--) {
            int temp = dp(envelopes, j);
            if (greater(envelopes, i, j)) {
                result = Math.max(result, temp + 1);
            }
        }
        memo[i] = result;

        return result;
    }

    private boolean greater(int[][] envelopes, int i, int j) {
        return envelopes[i][0] > envelopes[j][0] &&
                envelopes[i][1] > envelopes[j][1];
    }
}
// https://leetcode.cn/submissions/detail/330569441/
```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```java
class Solution {
    public String decodeString(String s) {
        Deque<String> stack = new LinkedList();
        StringBuilder sb = new StringBuilder();
        int len = s.length();
        int i = 0;
        while (i < len) {
            // Digits
            while (i < len && Character.isDigit(s.charAt(i))) {
                sb.append(s.charAt(i));
                ++i;
            }
            if (sb.length() > 0) {
                stack.push(getStringAndClear(sb));
            }
            // [
            while (i < len && s.charAt(i) == '[') {
                stack.push("[");
                ++i;
            }
            // Letters
            while (i < len && Character.isLetter(s.charAt(i))) {
                sb.append(s.charAt(i));
                ++i;
            }
            if (sb.length() > 0) {
                stack.push(getStringAndClear(sb));
            }
            // ]
            while (i < len && s.charAt(i) == ']') {
                while (!stack.isEmpty()) {
                    String str = stack.pop();
                    if (str.equals("[")) {
                        break;
                    } else {
                        sb.insert(0, str);
                    }
                }
                String letters = getStringAndClear(sb);
                String digits = stack.pop();
                String rep = repeatedString(letters, Integer.parseInt(digits));
                stack.push(rep);
                ++i;
            }
        }
        while (!stack.isEmpty()) {
            sb.insert(0, stack.pop());
        }
        return sb.toString();
    }

    private String getStringAndClear(StringBuilder sb) {
        String str = sb.toString();
        sb.setLength(0);
        return str;
    }

    private String repeatedString(String s, int k) {
        StringBuilder sb = new StringBuilder();
        for (int i = 1; i <= k; ++i) {
            sb.append(s);
        }
        return sb.toString();
    }
}
// https://leetcode.cn/submissions/detail/363359587/
```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```java
class Solution {
    public boolean canPartition(int[] nums) {
        int sum = 0;
        for (int x : nums) {
            sum += x;
        }
        if (sum % 2 == 1) {
            return false;
        }
        return hasSubsetSum(nums, sum / 2);
    }

    // 数组 nums 是否存在和为 sum 的子集
    private boolean hasSubsetSum(int[] nums, int sum) {
        int n = nums.length;
        // dp[i][j] = 子数组 nums[0..i-1] 是否存在和为 j 的子集
        boolean[][] dp = new boolean[n + 1][sum + 1];
        // 和为 0
        for (int i = 1; i <= n; ++i) {
            dp[i][0] = true;
        }
        // 空数组
        for (int j = 1; j <= sum; ++j) {
            dp[0][j] = false;
        }
        // 空集的和为 0，空集是任何数组的子集，包括空数组
        dp[0][0] = true;
        for (int i = 1; i <= n; ++i) {
            for (int j = 1; j <= sum; ++j) {
                int x = nums[i - 1];
                if (j >= x) {
                    // 不包含 x
                    // 当 i = 1 时，dp[i - 1][j] = dp[0][j]
                    // 因为空数组没有子集的和为 j >= 1
                    // 所以定义 dp[0][j] = false (j >= 1)
                    boolean sp1 = dp[i - 1][j];
                    // 包含 x
                    // 当 i >= 1, j = x 时，dp[i - 1][j - x] = dp[i - 1][0]
                    // 因为存在子集 {x} 的和为 j，
                    // 所以定义 dp[i][0] = true (i >= 0)
                    boolean sp2 = dp[i - 1][j - x];
                    dp[i][j] = sp1 || sp2;
                } else {
                    dp[i][j] = dp[i - 1][j];
                }
            }
        }
        return dp[n][sum];
    }
}
// https://leetcode.cn/submissions/detail/373549699/
```

```java
class Solution {
    private Map<String, Boolean> memo = new HashMap();

    public boolean canPartition(int[] nums) {
        int sum = 0;
        for (int x : nums) {
            sum += x;
        }
        if (sum % 2 == 1) {
            return false;
        }
        return hasSubsetSum(nums, sum / 2);
    }

    // 数组 nums 是否存在和为 sum 的子集
    private boolean hasSubsetSum(int[] nums, int sum) {
        return hasSubsetSum(nums, nums.length - 1, sum);
    }

    // 子数组 nums[0..i] 是否存在和为 sum 的子集
    private boolean hasSubsetSum(int[] nums, int i, int sum) {
        if (i < 0) {
            return false;
        }
        String key = i + "," + sum;
        if (!memo.containsKey(key)) {
            boolean res;
            int x = nums[i];
            if (sum > x) {
                // 不包含 x || 包含 x
                res = hasSubsetSum(nums, i - 1, sum) || hasSubsetSum(nums, i - 1, sum - x);
            } else if (sum < x) {
                // 不包含 x
                res = hasSubsetSum(nums, i - 1, sum);
            } else {
                // 存在子集 {x} 的和为 sum
                res = true;
            }
            memo.put(key, res);
        }
        return memo.get(key);
    }
}
// https://leetcode.cn/submissions/detail/375135459/
```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```java
class Solution {
    public int eraseOverlapIntervals(int[][] intervals) {
        return intervals.length - maxNonOverlappingIntervals(intervals);
    }

    // 返回区间数组 intervals 无重叠区间的最大数量
    private int maxNonOverlappingIntervals(int[][] intervals) {
        // 按区间终点升序排列
        Arrays.sort(intervals, Comparator.comparingInt(interval -> interval[1]));
        // 最后一个不重叠区间的终点
        int lastEnd = intervals[0][1];
        int count = 1;
        for (int i = 1; i < intervals.length; ++i) {
            int start = intervals[i][0];
            int end = intervals[i][1];
            if (start >= lastEnd) {
                ++count;
                lastEnd = end;
            }
        }
        return count;
    }
}
// https://leetcode.cn/submissions/detail/455268532/
```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```java
class Solution {
    public List<Integer> findAnagrams(String s, String p) {
        Map<Character, Integer> need = new HashMap();
        for (char c : p.toCharArray()) {
            need.put(c, need.getOrDefault(c, 0) + 1);
        }
        Map<Character, Integer> window = new HashMap();
        List<Integer> ans = new LinkedList();
        int valid = 0;
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        int left = 0, right = 0;
        while (right < s.length()) {
            char c = s.charAt(right++);
            if (need.containsKey(c)) {
                window.put(c, window.getOrDefault(c, 0) + 1);
                if (window.get(c).equals(need.get(c))) {
                    ++valid;
                }
            }
            if (valid == need.size()) {
                while (left < right - p.length()) {
                    char d = s.charAt(left++);
                    if (need.containsKey(d)) {
                        if (window.get(d).equals(need.get(d))) {
                            --valid;
                        }
                        window.put(d, window.get(d) - 1);
                    }
                }
            }
            if (valid == need.size()) {
                ans.add(left);
            }
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/365642439/
```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```java
class Solution {
    public ListNode addTwoNumbers(ListNode l1, ListNode l2) {
        l1 = reverseList(l1);
        l2 = reverseList(l2);
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
        return reverseList(dummyHead.next);
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
// https://leetcode.cn/submissions/detail/356164460/
```

```java
class Solution {
    public ListNode addTwoNumbers(ListNode l1, ListNode l2) {
        Deque<ListNode> stack1 = new LinkedList();
        Deque<ListNode> stack2 = new LinkedList();
        while (l1 != null || l2 != null) {
            if (l1 != null) {
                stack1.push(l1);
                l1 = l1.next;
            }
            if (l2 != null) {
                stack2.push(l2);
                l2 = l2.next;
            }
        }
        ListNode first = null;
        int carry = 0;
        while (!stack1.isEmpty() || !stack2.isEmpty() || carry > 0) {
            int sum = carry;
            if (!stack1.isEmpty()) {
                sum += stack1.pop().val;
            }
            if (!stack2.isEmpty()) {
                sum += stack2.pop().val;
            }
            ListNode oldfirst = first;
            first = new ListNode(sum % 10);
            first.next = oldfirst;
            carry = sum / 10;
        }
        return first;
    }
}
// https://leetcode.cn/submissions/detail/361134130/
```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```java
class Solution {
    public TreeNode deleteNode(TreeNode root, int key) {
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
            TreeNode x = root;
            root = findMin(x.right);
            root.right = deleteMin(x.right);
            root.left = x.left;
        }
        return root;
    }

    private TreeNode findMin(TreeNode root) {
        if (root.left == null) {
            return root;
        }
        return findMin(root.left);
    }

    private TreeNode deleteMin(TreeNode root) {
        if (root.left == null) {
            return root.right;
        }
        root.left = deleteMin(root.left);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/368699895/
```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```java
class Solution {
    public int findMinArrowShots(int[][] points) {
        return maxNonOverlappingIntervals(points);
    }

    private int maxNonOverlappingIntervals(int[][] intervals) {
        Arrays.sort(intervals, (a, b) -> {
            if (a[1] > b[1]) {
                return 1;
            }
            if (a[1] < b[1]) {
                return -1;
            }
            return 0;
        });
        int lastEnd = intervals[0][1];
        int count = 1;
        for (int i = 1; i < intervals.length; ++i) {
            int start = intervals[i][0];
            int end = intervals[i][1];
            if (start <= lastEnd) {
                continue;
            }
            ++count;
            lastEnd = end;
        }
        return count;
    }
}
// https://leetcode.cn/submissions/detail/409172016/
```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```java
class MyListNode {
    public int key, val, freq;
    public MyListNode prev, next;

    public MyListNode(int key, int val, int freq) {
        this.key = key;
        this.val = val;
        this.freq = freq;
    }
}

class MyDoublyLinkedList {
    private MyListNode first, last;
    private int n;

    public MyDoublyLinkedList() {
        first = null;
        last = null;
        n = 0;
    }

    public void addLast(MyListNode newNode) {
        if (n == 0) {
            first = newNode;
            last = newNode;
        } else {
            last.next = newNode;
            newNode.prev = last;
            last = newNode;
        }
        ++n;
    }

    public MyListNode removeFirst() {
        MyListNode oldFirst = first;
        if (n == 1) {
            first = null;
            last = null;
        } else {
            first = first.next;
            first.prev = null;
            oldFirst.next = null;
        }
        --n;
        return oldFirst;
    }

    public MyListNode removeLast() {
        MyListNode oldLast = last;
        if (n == 1) {
            first = null;
            last = null;
        } else {
            last = last.prev;
            last.next = null;
            oldLast.prev = null;
        }
        --n;
        return oldLast;
    }

    public void remove(MyListNode delNode) {
        if (delNode == first) {
            removeFirst();
        } else if (delNode == last) {
            removeLast();
        } else {
            delNode.prev.next = delNode.next;
            delNode.next.prev = delNode.prev;
            delNode.prev = null;
            delNode.next = null;
            --n;
        }
    }

    public boolean empty() {
        return first == null;
    }
}

class LFUCache {
    private final int capacity;
    private final Map<Integer, MyListNode> keyToNode = new HashMap<>();
    private final Map<Integer, MyDoublyLinkedList> freqToList = new HashMap<>();
    private int minFreq = 0;

    public LFUCache(int capacity) {
        this.capacity = capacity;
    }

    public int get(int key) {
        if (contains(key)) {
            return touchCache(key, Integer.MIN_VALUE);
        }
        return -1;
    }

    public void put(int key, int value) {
        if (capacity > 0) {
            if (contains(key)) {
                touchCache(key, value);
            } else {
                if (full()) {
                    removeCache();
                }
                addCache(key, value);
            }
        }
    }

    private boolean contains(int key) {
        return keyToNode.containsKey(key);
    }

    private boolean full() {
        return keyToNode.size() == capacity;
    }

    private void addCache(int key, int val) {
        MyListNode newNode = new MyListNode(key, val, 1);
        keyToNode.put(key, newNode);
        freqToList.putIfAbsent(1, new MyDoublyLinkedList());
        freqToList.get(1).addLast(newNode);
        minFreq = 1;
    }

    private void removeCache() {
        MyDoublyLinkedList minFreqList = freqToList.get(minFreq);
        keyToNode.remove(minFreqList.removeFirst().key);
        if (minFreqList.empty()) {
            freqToList.remove(minFreq);
        }
    }

    private int touchCache(int key, int val) {
        MyListNode touchNode = keyToNode.get(key);
        if (val != Integer.MIN_VALUE) {
            touchNode.val = val;
        }
        int oldFreq = touchNode.freq;
        int newFreq = oldFreq + 1;
        touchNode.freq = newFreq;
        MyDoublyLinkedList oldList = freqToList.get(oldFreq);
        oldList.remove(touchNode);
        if (oldList.empty()) {
            freqToList.remove(oldFreq);
            if (minFreq == oldFreq) {
                minFreq = newFreq;
            }
        }
        freqToList.putIfAbsent(newFreq, new MyDoublyLinkedList());
        MyDoublyLinkedList newList = freqToList.get(newFreq);
        newList.addLast(touchNode);
        return touchNode.val;
    }
}
// https://leetcode.cn/submissions/detail/442124154/
```

```java
class LFUCache {
    private final int capacity;
    private final Map<Integer, Integer> keyToVal = new HashMap<>();
    private final Map<Integer, Integer> keyToFreq = new HashMap<>();
    private final Map<Integer, LinkedHashSet<Integer>> freqToKeyList = new HashMap<>();
    private int minFreq = 0;

    public LFUCache(int capacity) {
        this.capacity = capacity;
    }

    public int get(int key) {
        if (contains(key)) {
            return touchCache(key, Integer.MIN_VALUE);
        }
        return -1;
    }

    public void put(int key, int value) {
        if (capacity > 0) {
            if (contains(key)) {
                touchCache(key, value);
            } else {
                if (full()) {
                    removeCache();
                }
                addCache(key, value);
            }
        }
    }

    private boolean contains(int key) {
        return keyToVal.containsKey(key);
    }

    private boolean full() {
        return keyToVal.size() == capacity;
    }

    private void addCache(int key, int val) {
        keyToVal.put(key, val);
        keyToFreq.put(key, 1);
        freqToKeyList.putIfAbsent(1, new LinkedHashSet<>());
        freqToKeyList.get(1).add(key);
        minFreq = 1;
    }

    private void removeCache() {
        LinkedHashSet<Integer> minFreqList = freqToKeyList.get(minFreq);
        int delKey = minFreqList.iterator().next();
        keyToVal.remove(delKey);
        keyToFreq.remove(delKey);
        minFreqList.remove(delKey);
        if (minFreqList.isEmpty()) {
            freqToKeyList.remove(minFreq);
        }
    }

    private int touchCache(int key, int val) {
        if (val != Integer.MIN_VALUE) {
            keyToVal.put(key, val);
        }
        int oldFreq = keyToFreq.get(key);
        int newFreq = oldFreq + 1;
        keyToFreq.put(key, newFreq);
        LinkedHashSet<Integer> oldList = freqToKeyList.get(oldFreq);
        oldList.remove(key);
        if (oldList.isEmpty()) {
            freqToKeyList.remove(oldFreq);
            if (minFreq == oldFreq) {
                minFreq = newFreq;
            }
        }
        freqToKeyList.putIfAbsent(newFreq, new LinkedHashSet<>());
        LinkedHashSet<Integer> newList = freqToKeyList.get(newFreq);
        newList.add(key);
        return keyToVal.get(key);
    }
}
// https://leetcode.cn/submissions/detail/442128400/
```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```java
class Solution {
    private int ans = 0;

    public int reversePairs(int[] nums) {
        sort(nums);
        return ans;
    }

    private void sort(int[] nums) {
        int n = nums.length;
        int[] aux = new int[n];
        sort(nums, 0, n - 1, aux);
    }

    private void sort(int[] nums, int lo, int hi, int[] aux) {
        if (lo >= hi) {
            return;
        }
        int mid = lo + (hi - lo) / 2;
        sort(nums, lo, mid, aux);
        sort(nums, mid + 1, hi, aux);
        merge(nums, lo, mid, hi, aux);
    }

    private void merge(int[] nums, int lo, int mid, int hi, int[] aux) {
        for (int k = lo; k <= hi; ++k) {
            aux[k] = nums[k];
        }
        ans += countReversePairs(nums, lo, mid, hi);
        int i = lo, j = mid + 1;
        for (int k = lo; k <= hi; ++k) {
            if (i > mid || (j <= hi && aux[j] < aux[i])) {
                nums[k] = aux[j++];
            } else {
                nums[k] = aux[i++];
            }
        }
    }

    private int countReversePairs(int[] nums, int lo, int mid, int hi) {
        int res = 0;
        //     nums[i]      > 2*nums[j]
        // (1) nums[i]      > 2*nums[mid+1..j]
        // (2) nums[i..mid] > 2*nums[j]
        //
        //     nums[i]     <= 2*nums[j]
        // (1) nums[i]     <= 2*nums[j..hi]
        // (2) nums[lo..i] <= 2*nums[j]
        int i = lo, j = mid + 1;
        while (i <= mid && j <= hi) {
            if (isReversePair(nums, i, j)) {
                res += (mid - i + 1);
                ++j;
            } else {
                ++i;
            }
        }
        return res;
    }

    private boolean isReversePair(int[] nums, int i, int j) {
        return i < j && (long) nums[i] > (long) 2 * nums[j];
    }
}
// https://leetcode.cn/submissions/detail/366616958/
```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```java
class Solution {
    private Map<String, Integer> memo = new HashMap();

    public int findTargetSumWays(int[] nums, int target) {
        int sum = 0;
        for (int x : nums) {
            sum += x;
        }
        if (Math.abs(target) > sum) {
            return 0;
        }
        return findTargetSumWays(nums, 0, target);
    }

    // 子数组 nums[i..n-1] 目标和为 target 的不同表达式的数目
    private int findTargetSumWays(int[] nums, int i, int target) {
        if (i == nums.length) {
            return target == 0 ? 1 : 0;
        }
        String key = i + "," + target;
        if (!memo.containsKey(key)) {
            int x = nums[i];
            // x 前添加 + 号
            // sum(nums[i+1..n-1]) = target - x
            int sp1 = findTargetSumWays(nums, i + 1, target - x);
            // x 前添加 - 号
            // sum(nums[i+1..n-1]) = target + x
            int sp2 = findTargetSumWays(nums, i + 1, target + x);
            memo.put(key, sp1 + sp2);
        }
        return memo.get(key);
    }
}
// https://leetcode.cn/submissions/detail/373566984/
```

```java
class Solution {
    int findTargetSumWays(int[] nums, int target) {
        // sum(A) - sum(B) = target
        // sum(A) = target + sum(B)
        // sum(A) + sum(A) = target + sum(B) + sum(A)
        // 2 * sum(A) = target + sum(nums)
        // sum(A) = (target + sum(nums)) / 2
        // 问题转化为：数组 nums 中存在几个子集 A
        // 使得 A 中元素的和为 (target + sum(nums)) / 2
        int sum = 0;
        for (int x : nums) {
            sum += x;
        }
        if (Math.abs(target) > sum || (sum + target) % 2 == 1) {
            return 0;
        }
        return numSubsetSum(nums, (sum + target) / 2);
    }

    // 数组 nums 和为 sum 的子集的数目，其中 nums[i] >= 0, sum >= 0
    int numSubsetSum(int[] nums, int sum) {
        int n = nums.length;
        // dp[i][j] = 子数组 nums[0..i-1] 和为 j 的子集的数目
        int[][] dp = new int[n + 1][sum + 1];
        // 空数组
        for (int j = 1; j <= sum; ++j) {
            dp[0][j] = 0;
        }
        // 空集的和为 0，空集是任何数组的子集，包括空数组
        dp[0][0] = 1;
        for (int i = 1; i <= n; ++i) {
            for (int j = 0; j <= sum; ++j) {
                int x = nums[i - 1];
                if (j >= x) {
                    // 不包含 x
                    // 当 i = 1, j >= 1 时，dp[i - 1][j] = dp[0][j]
                    // 因为空数组没有子集的和为 j
                    // 所以定义 dp[0][j] = 0 (j >= 1)
                    int sp1 = dp[i - 1][j];
                    // 包含 x
                    // 当 i = 1, j = x 时，dp[i - 1][j - x] = dp[0][0]
                    // 因为存在子集 {x} 的和为 j，
                    // 所以定义 dp[0][0] = 1
                    // 注意：当 i > 1, j = x 时，dp[i - 1][j - x] = dp[i - 1][0]
                    // 此时，不一定只有 dp[i][0] = 1 (i > 0)
                    // 测试用例
                    // [0,0,0,0,0,0,0,0,1]
                    // 1
                    int sp2 = dp[i - 1][j - x];
                    dp[i][j] = sp1 + sp2;
                } else {
                    dp[i][j] = dp[i - 1][j];
                }
            }
        }
        return dp[n][sum];
    }
}
// https://leetcode.cn/submissions/detail/373566688/
```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```java
class Solution {
    public int[] nextGreaterElement(int[] nums1, int[] nums2) {
        int[] greater = nextGreaterElement(nums2);
        Map<Integer, Integer> valToGreater = new HashMap();
        for (int i = 0; i < nums2.length; ++i) {
            valToGreater.put(nums2[i], greater[i]);
        }
        int n1 = nums1.length;
        int[] ans = new int[n1];
        for (int i = 0; i < n1; ++i) {
            ans[i] = valToGreater.get(nums1[i]);
        }
        return ans;
    }

    private int[] nextGreaterElement(int[] nums) {
        int n = nums.length;
        int[] res = new int[n];
        Deque<Integer> stack = new LinkedList();
        for (int i = n - 1; i >= 0; --i) {
            int x = nums[i];
            while (!stack.isEmpty() && stack.peek() < x) {
                stack.pop();
            }
            res[i] = stack.isEmpty() ? -1 : stack.peek();
            stack.push(x);
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/374122931/
```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```java
class Solution {
    public int[] nextGreaterElements(int[] nums) {
        int n = nums.length;
        int[] ans = new int[n];
        Deque<Integer> stack = new LinkedList();
        for (int i = 2 * n - 1; i >= 0; --i) {
            int k = i % n;
            int x = nums[k];
            while (!stack.isEmpty() && stack.peek() <= x) {
                stack.pop();
            }
            ans[k] = stack.isEmpty() ? -1 : stack.peek();
            stack.push(x);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/374193018/
```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```java
class Solution {
    public int fib(int n) {
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return 1;
        }
        int[] dp = new int[n + 1];
        dp[0] = 0;
        dp[1] = 1;
        for (int i = 2; i <= n; ++i) {
            dp[i] = dp[i - 1] + dp[i - 2];
        }
        return dp[n];
    }
}
// https://leetcode.cn/submissions/detail/375040133/
```

```java
class Solution {
    public int fib(int n) {
        if (n == 0 || n == 1) return n;
        int fib_i_1 = 1;
        int fib_i_2 = 0;
        for (int i = 2; i <= n; i++) {
            int fib_i = fib_i_1 + fib_i_2;
            fib_i_2 = fib_i_1;
            fib_i_1 = fib_i;
        }
        return fib_i_1;
    }
}
// https://leetcode.cn/submissions/detail/329150543/
```

```java
class Solution {
    private HashMap<Integer, Integer> memo = new HashMap<Integer, Integer>();

    public int fib(int n) {
        if (memo.get(n) != null) return memo.get(n);
        if (n == 0 || n == 1) {
            memo.put(n, n);
            return n;
        }
        memo.put(n, fib(n - 1) + fib(n - 2));
        return memo.get(n);
    }
}
// https://leetcode.cn/submissions/detail/329140367/
```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```java
class Solution {
    public int longestPalindromeSubseq(String s) {
        int n = s.length();
        // dp[i][j] = 子串 s[i..j] 的最长回文子序列的长度
        int[][] dp = new int[n][n];
        // 遍历对角线
        for (int i = 0; i < n; ++i) {
            dp[i][i] = 1;
        }
        // 遍历下三角形
        // for (int i = 0; i < n; ++i) {
        //     for (int j = 0; j < i; ++j) {
        //         dp[i][j] = 0;
        //     }
        // }
        for (int i = n - 2; i >= 0; --i) {
            for (int j = i + 1; j < n; ++j) {
                if (s.charAt(i) == s.charAt(j)) {
                    // s[i][i+1..j-1][j]
                    // s   [i+1..j-1]
                    dp[i][j] = dp[i + 1][j - 1] + 2;
                } else {
                    // s[i..j-1][j]
                    // s[i..j-1]
                    int sp1 = dp[i][j - 1];
                    // s[i][i+1..j]
                    // s   [i+1..j]
                    int sp2 = dp[i + 1][j];
                    dp[i][j] = Math.max(sp1, sp2);
                }
            }
        }
        return dp[0][n - 1];
    }
}
// https://leetcode.cn/submissions/detail/374535185/
```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```java
class Solution {
    public int change(int amount, int[] coins) {
        int n = coins.length;
        // dp[i][j] = 使用硬币 coins[0..i-1] 凑成总金额 j 的组合数
        int[][] dp = new int[n + 1][amount + 1];
        // 总金额为 0
        for (int i = 1; i <= n; ++i) {
            dp[i][0] = 1;
        }
        // 硬币数为 0
        for (int j = 1; j <= amount; ++j) {
            dp[0][j] = 0;
        }
        dp[0][0] = 1;
        for (int i = 1; i <= n; ++i) {
            for (int j = 1; j <= amount; ++j) {
                int x = coins[i - 1];
                if (j < x) {
                    // 不包含硬币 x
                    dp[i][j] = dp[i - 1][j];
                } else {
                    int sp1 = dp[i - 1][j]; // 包含    0 个硬币 x
                    int sp2 = dp[i][j - x]; // 包含 >= 1 个硬币 x
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
    }
}
// https://leetcode.cn/submissions/detail/372576859/
```

```java
class Solution {
    private int[][] memo;

    public int change(int amount, int[] coins) {
        int n = coins.length;
        memo = new int[amount + 1][n + 1];
        for (int i = 0; i <= amount; i++) {
            for (int j = 0; j <= n; j++) {
                memo[i][j] = -1;
            }
        }
        dp(amount, coins, n);

        return memo[amount][n];
    }

    private int dp(int amount, int[] coins, int k) {
        if (memo[amount][k] != -1) {
            return memo[amount][k];
        }

        if (amount == 0) {
            memo[0][k] = 1;
            return 1;
        }

        if (k == 0) {
            memo[amount][0] = 0;
            return 0;
        }

        if (amount >= coins[k - 1]) {
            memo[amount][k] = dp(amount, coins, k - 1) + dp(amount - coins[k - 1], coins, k);
        } else {
            memo[amount][k] = dp(amount, coins, k - 1);
        }

        return memo[amount][k];
    }
}
// https://leetcode.cn/submissions/detail/331029268/
```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```java
class Solution {
    int sum = 0;

    public TreeNode convertBST(TreeNode root) {
        traverse(root);
        return root;
    }

    void traverse(TreeNode root) {
        if (root == null) {
            return;
        }
        traverse(root.right);
        sum += root.val;
        root.val = sum;
        traverse(root.left);
    }
}
// https://leetcode.cn/submissions/detail/322655153/
```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```java
// rootLP = 穿过根节点的最长路径（左右子树的最大深度之和）
// rootLP(root) = maxDepth(root.left) + maxDepth(root.right)
// diameter = 所有子树的 rootLP 的最大值
// diameter(root) = max({ rootLP(subtree) | subtree 是 root 的任意子树 })
class Solution {
    private int ans = 0;

    public int diameterOfBinaryTree(TreeNode root) {
        maxDepth(root);
        return ans;
    }

    private int maxDepth(TreeNode root) {
        if (root == null) {
            return 0;
        }
        int left = maxDepth(root.left);
        int right = maxDepth(root.right);
        int rootLP = left + right;
        ans = Math.max(ans, rootLP);
        return 1 + Math.max(left, right);
    }
}
// https://leetcode.cn/submissions/detail/365645931/
```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```java
class Solution {
    public boolean checkInclusion(String s1, String s2) {
        Map<Character, Integer> need = new HashMap();
        for (char c : s1.toCharArray()) {
            need.put(c, need.getOrDefault(c, 0) + 1);
        }
        Map<Character, Integer> window = new HashMap();
        int valid = 0;
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        int left = 0, right = 0;
        while (right < s2.length()) {
            char c = s2.charAt(right++);
            if (need.containsKey(c)) {
                window.put(c, window.getOrDefault(c, 0) + 1);
                if (window.get(c).equals(need.get(c))) {
                    ++valid;
                }
            }
            if (valid == need.size()) {
                while (left < right - s1.length()) {
                    char d = s2.charAt(left++);
                    if (need.containsKey(d)) {
                        if (window.get(d).equals(need.get(d))) {
                            --valid;
                        }
                        window.put(d, window.get(d) - 1);
                    }
                }
            }
            if (valid == need.size()) {
                return true;
            }
        }
        return false;
    }
}
// https://leetcode.cn/submissions/detail/365643758/
```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```java
class Solution {
    public int minDistance(String word1, String word2) {
        int m = word1.length();
        int n = word2.length();
        // dp[i][j] = 子串 s1[0..i-1] s2[0..j-1] 的最小删除步数
        int[][] dp = new int[m + 1][n + 1];
        for (int i = 0; i <= m; i++) {
            dp[i][0] = i;
        }
        for (int j = 0; j <= n; j++) {
            dp[0][j] = j;
        }
        for (int i = 1; i <= m; i++) {
            for (int j = 1; j <= n; j++) {
                int result;
                if (word1.charAt(i - 1) == word2.charAt(j - 1)) {
                    result = dp[i - 1][j - 1];
                } else {
                    result = 1 + Math.min(dp[i][j - 1], dp[i - 1][j]);
                }
                dp[i][j] = result;
            }
        }
        return dp[m][n];
    }
}
// https://leetcode.cn/submissions/detail/448357182/
```

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

    // 返回子串 s1[0..i] s2[0..j] 的最小删除步数
    private int minDistance(String s1, int i, String s2, int j) {
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
        if (memo[i][j] == -1) {
            if (s1.charAt(i) == s2.charAt(j)) {
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                memo[i][j] = minDistance(s1, i - 1, s2, j - 1);
            } else {
                // 删除 s1[i] s2[j]
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                int sp1 = minDistance(s1, i - 1, s2, j - 1) + 2;
                // 删除 s2[j]
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
// https://leetcode.cn/submissions/detail/448353828/
```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```java
class Solution {
    public TreeNode mergeTrees(TreeNode root1, TreeNode root2) {
        if (root1 == null) {
            return root2;
        }
        if (root2 == null) {
            return root1;
        }
        TreeNode mergeRoot = new TreeNode(root1.val + root2.val);
        mergeRoot.left = mergeTrees(root1.left, root2.left);
        mergeRoot.right = mergeTrees(root1.right, root2.right);
        return mergeRoot;
    }
}
// https://leetcode.cn/submissions/detail/350393289/
```

```java
class Solution {
    public TreeNode mergeTrees(TreeNode root1, TreeNode root2) {
        Deque<TreeNode> queue1 = new LinkedList();
        Deque<TreeNode> queue2 = new LinkedList();
        Deque<TreeNode> mergeQueue = new LinkedList();
        TreeNode mergeRoot = merge(root1, root2);
        if (root1 != null && root2 != null) {
            queue1.offer(root1);
            queue2.offer(root2);
            mergeQueue.offer(mergeRoot);
        }
        while (!mergeQueue.isEmpty()) {
            TreeNode node1 = queue1.poll();
            TreeNode node2 = queue2.poll();
            TreeNode mergeNode = mergeQueue.poll();
            // left
            TreeNode left1 = node1.left;
            TreeNode left2 = node2.left;
            mergeNode.left = merge(left1, left2);
            if (left1 != null && left2 != null) {
                queue1.offer(left1);
                queue2.offer(left2);
                mergeQueue.offer(mergeNode.left);
            }
            // right
            TreeNode right1 = node1.right;
            TreeNode right2 = node2.right;
            mergeNode.right = merge(right1, right2);
            if (right1 != null && right2 != null) {
                queue1.offer(right1);
                queue2.offer(right2);
                mergeQueue.offer(mergeNode.right);
            }
        }
        return mergeRoot;
    }

    private TreeNode merge(TreeNode node1, TreeNode node2) {
        if (node1 == null) {
            return node2;
        }
        if (node2 == null) {
            return node1;
        }
        return new TreeNode(node1.val + node2.val);
    }
}
// https://leetcode.cn/submissions/detail/350393022/
```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```java
class Solution {
    String NULL = "#";
    String SEP = ",";
    Map<String, Integer> map = new HashMap<>();
    List<TreeNode> ans = new LinkedList<>();

    public List<TreeNode> findDuplicateSubtrees(TreeNode root) {
        traverse(root);
        return ans;
    }

    String traverse(TreeNode root) {
        if (root == null) {
            return NULL;
        }

        String leftStr = traverse(root.left);
        String rightStr = traverse(root.right);

        StringBuilder sb = new StringBuilder();
        sb.append(root.val).append(SEP);
        sb.append(leftStr).append(SEP);
        sb.append(rightStr);

        String rootStr = sb.toString();

        int freq = map.getOrDefault(rootStr, 0);
        map.put(rootStr, ++freq);
        if (freq == 2) {
            ans.add(root);
        }

        return rootStr;
    }
}
// https://leetcode.cn/submissions/detail/322169652/
```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```java
class Solution {
    public TreeNode constructMaximumBinaryTree(int[] nums) {
        return construct(nums, 0, nums.length - 1);
    }

    private TreeNode construct(int[] nums, int lo, int hi) {
        if (lo > hi) return null;
        int idx = lo;
        for (int i = lo + 1; i <= hi; i++) {
            if (nums[i] > nums[idx]) idx = i;
        }
        TreeNode root = new TreeNode(nums[idx]);
        root.left = construct(nums, lo, idx - 1);
        root.right = construct(nums, idx + 1, hi);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/343841184/
```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```java
class Solution {
    private static final int LAND = 1;
    private static final int WATER = 0;
    private int area;

    public int maxAreaOfIsland(int[][] grid) {
        int ans = 0;
        for (int i = 0; i < grid.length; ++i) {
            for (int j = 0; j < grid[0].length; ++j) {
                if (grid[i][j] == LAND) {
                    area = 0;
                    floodFill(grid, i, j);
                    ans = Math.max(ans, area);
                }
            }
        }
        return ans;
    }

    private void floodFill(int[][] grid, int i, int j) {
        if (i < 0 || i >= grid.length || j < 0 || j >= grid[0].length || grid[i][j] == WATER) {
            return;
        }
        ++area;
        grid[i][j] = WATER;
        floodFill(grid, i, j + 1);
        floodFill(grid, i, j - 1);
        floodFill(grid, i + 1, j);
        floodFill(grid, i - 1, j);
    }
}
// https://leetcode.cn/submissions/detail/366265844/
```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```java
class Solution {
    private int k, target;
    private int used;
    private int[] nums;
    private int[] pathSums;
    private Map<Integer, Boolean> memo = new HashMap();

    public boolean canPartitionKSubsets(int[] nums, int k) {
        int n = nums.length;
        if (k > n) {
            return false;
        }
        int sum = 0;
        for (int x : nums) {
            sum += x;
        }
        if (sum % k != 0) {
            return false;
        }
        this.nums = nums;
        this.k = k;
        this.target = sum / k;
        this.used = 0;
        this.pathSums = new int[k];
        return backtrack(0, -1);
    }

    // 遍历『决策森林』的 k 棵『决策树』
    // 一棵『决策树』的『路径』代表一个『等和子集』
    // tree = 第几棵『决策树』，取 [0..k-1] 为值
    // edge =『决策树』的『边』，取数组 nums 的索引为值
    // pathSums[tree] = 第几棵『决策树』的『路径和』
    private boolean backtrack(int tree, int edge) {
        boolean res = false;
        if (tree == k) {
            res = true;
        } else if (pathSums[tree] == target) {
            // 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            // 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            // 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            // 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            // 因为 C 的可选『边』是一样的
            if (!memo.containsKey(used)) {
                // 遍历下一棵『决策树』
                res = backtrack(tree + 1, -1);
                memo.put(used, res);
            }
            res = memo.get(used);
        } else {
            // 通过去重，对同一棵树，优化『边』的遍历，避免『边+边』重复
            // 例如 1 和 2 分别是两条『边』，[1->2] 和 [2->1] 是重复的
            while (++edge < nums.length) {
                // 检查第 edge 位是否为 1
                // 即 nums[edge] 是否已经被其他『树』使用
                if (((used >> edge) & 1) == 1) {
                    continue;
                }
                int x = nums[edge];
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
                //『异或』运算，将第 edge 位修改为 0
                used ^= 1 << edge;
            }
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/374888808/
```

```java
class Solution {
    private int k, target;
    private int used;
    private int[] nums;
    private int[] pathSums;
    private Map<Integer, Boolean> memo = new HashMap();

    public boolean canPartitionKSubsets(int[] nums, int k) {
        int n = nums.length;
        if (k > n) {
            return false;
        }
        int sum = 0;
        for (int x : nums) {
            sum += x;
        }
        if (sum % k != 0) {
            return false;
        }
        this.nums = nums;
        this.k = k;
        this.target = sum / k;
        this.used = 0;
        this.pathSums = new int[k];
        return dfs(0, -1);
    }

    // 遍历『决策森林』的 k 棵『决策树』
    // 一棵『决策树』的『路径』代表一个『等和子集』
    // tree = 第几棵『决策树』，取 [0..k-1] 为值
    // vertex =『决策树』的『顶点』，取数组 nums 的索引为值
    // pathSums[tree] = 第几棵『决策树』的『路径和』
    private boolean dfs(int tree, int vertex) {
        int x = (vertex == -1 ? 0 : nums[vertex]);
        if (vertex >= 0) {
            pathSums[tree] += x;
            //『或』运算，将第 vertex 位修改为 1
            used |= 1 << vertex;
        }
        boolean res = false;
        if (tree == k) {
            res = true;
        } else if (pathSums[tree] == target) {
            // 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            // 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            // 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            // 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            // 因为 C 的可选『顶点』是一样的
            if (!memo.containsKey(used)) {
                // 遍历下一棵『决策树』
                res = dfs(tree + 1, -1);
                memo.put(used, res);
            }
            res = memo.get(used);
        } else {
            // 通过去重，对同一棵树，优化『顶点』的遍历，避免『顶点+顶点』重复
            // 例如 1 和 2 分别是两条『顶点』，[1->2] 和 [2->1] 是重复的
            int v = vertex;
            while (++v < nums.length) {
                // 检查第 vertex 位是否为 1
                // 即 nums[vertex] 是否已经被其他『树』使用
                if (((used >> v) & 1) == 1) {
                    continue;
                }
                if (pathSums[tree] + nums[v] > target) {
                    continue;
                }
                res = dfs(tree, v);
                if (res) {
                    break;
                }
            }
        }
        if (vertex >= 0 && !res) {
            pathSums[tree] -= x;
            //『异或』运算，将第 vertex 位修改为 0
            used ^= 1 << vertex;
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/374889826/
```

```java
class Solution {
    private int k, target;
    private char[] used;
    private int[] nums;
    private int[] pathSums;
    private Map<String, Boolean> memo = new HashMap();

    public boolean canPartitionKSubsets(int[] nums, int k) {
        int n = nums.length;
        if (k > n) {
            return false;
        }
        int sum = 0;
        for (int x : nums) {
            sum += x;
        }
        if (sum % k != 0) {
            return false;
        }
        this.nums = nums;
        this.k = k;
        this.target = sum / k;
        this.used = new char[16];
        Arrays.fill(this.used, '0');
        this.pathSums = new int[k];
        return backtrack(0, -1);
    }

    // 遍历『决策森林』的 k 棵『决策树』
    // 一棵『决策树』的『路径』代表一个『等和子集』
    // tree = 第几棵『决策树』，取 [0..k-1] 为值
    // edge =『决策树』的『边』，取数组 nums 的索引为值
    // pathSums[tree] = 第几棵『决策树』的『路径和』
    private boolean backtrack(int tree, int edge) {
        boolean res = false;
        if (tree == k) {
            res = true;
        } else if (pathSums[tree] == target) {
            // 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            // 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            // 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            // 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            // 因为 C 的可选『边』是一样的
            String key = new String(used);
            if (!memo.containsKey(key)) {
                // 遍历下一棵『决策树』
                res = backtrack(tree + 1, -1);
                memo.put(key, res);
            }
            res = memo.get(key);
        } else {
            // 通过去重，对同一棵树，优化『边』的遍历，避免『边+边』重复
            // 例如 1 和 2 分别是两条『边』，[1->2] 和 [2->1] 是重复的
            while (++edge < nums.length) {
                // 检查第 edge 位是否为 1
                // 即 nums[edge] 是否已经被其他『树』使用
                if (used[edge] == '1') {
                    continue;
                }
                int x = nums[edge];
                if (pathSums[tree] + x > target) {
                    continue;
                }
                pathSums[tree] += x;
                used[edge] = '1';
                res = backtrack(tree, edge);
                if (res) {
                    break;
                }
                pathSums[tree] -= x;
                used[edge] = '0';
            }
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/374888246/
```

```java
class Solution {
    private int k, target;
    private char[] used;
    private int[] nums;
    private int[] pathSums;
    private Map<String, Boolean> memo = new HashMap();

    public boolean canPartitionKSubsets(int[] nums, int k) {
        int n = nums.length;
        if (k > n) {
            return false;
        }
        int sum = 0;
        for (int x : nums) {
            sum += x;
        }
        if (sum % k != 0) {
            return false;
        }
        this.nums = nums;
        this.k = k;
        this.target = sum / k;
        this.used = new char[16];
        Arrays.fill(this.used, '0');
        this.pathSums = new int[k];
        return dfs(0, -1);
    }

    // 遍历『决策森林』的 k 棵『决策树』
    // 一棵『决策树』的『路径』代表一个『等和子集』
    // tree = 第几棵『决策树』，取 [0..k-1] 为值
    // vertex =『决策树』的『顶点』，取数组 nums 的索引为值
    // pathSums[tree] = 第几棵『决策树』的『路径和』
    private boolean dfs(int tree, int vertex) {
        int x = (vertex == -1 ? 0 : nums[vertex]);
        if (vertex >= 0) {
            pathSums[tree] += x;
            used[vertex] = '1';
        }
        boolean res = false;
        if (tree == k) {
            res = true;
        } else if (pathSums[tree] == target) {
            // 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            // 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            // 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            // 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            // 因为 C 的可选『顶点』是一样的
            String key = new String(used);
            if (!memo.containsKey(key)) {
                // 遍历下一棵『决策树』
                res = dfs(tree + 1, -1);
                memo.put(key, res);
            }
            res = memo.get(key);
        } else {
            // 通过去重，对同一棵树，优化『顶点』的遍历，避免『顶点+顶点』重复
            // 例如 1 和 2 分别是两条『顶点』，[1->2] 和 [2->1] 是重复的
            int v = vertex;
            while (++v < nums.length) {
                // 检查第 vertex 位是否为 1
                // 即 nums[vertex] 是否已经被其他『树』使用
                if (used[v] == '1') {
                    continue;
                }
                if (pathSums[tree] + nums[v] > target) {
                    continue;
                }
                res = dfs(tree, v);
                if (res) {
                    break;
                }
            }
        }
        if (vertex >= 0 && !res) {
            pathSums[tree] -= x;
            used[vertex] = '0';
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/374889201/
```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```java
class Solution {
    public TreeNode searchBST(TreeNode root, int val) {
        if (root == null) return null;
        if (val < root.val) return searchBST(root.left, val);
        else if (val > root.val) return searchBST(root.right, val);
        else return root;
    }
}
// https://leetcode.cn/submissions/detail/322861573/
```

```java
class Solution {
    public TreeNode searchBST(TreeNode root, int val) {
        TreeNode ptr = root;
        while (ptr != null) {
            if (val < ptr.val) ptr = ptr.left;
            else if (val > ptr.val) ptr = ptr.right;
            else return ptr;
        }
        return ptr;
    }
}
// https://leetcode.cn/submissions/detail/322863690/
```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```java
class Solution {
    public TreeNode insertIntoBST(TreeNode root, int val) {
        if (root == null) return new TreeNode(val);
        if (val < root.val) root.left = insertIntoBST(root.left, val);
        else if (val > root.val) root.right = insertIntoBST(root.right, val);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/322869491/
```

```java
class Solution {
    public TreeNode insertIntoBST(TreeNode root, int val) {
        if (root == null) return new TreeNode(val);

        TreeNode ptr = root;
        while (true) {
            if (val < ptr.val) {
                if (ptr.left == null) {
                    ptr.left = new TreeNode(val);
                    break;
                }
                ptr = ptr.left;
            } else if (val > ptr.val) {
                if (ptr.right == null) {
                    ptr.right = new TreeNode(val);
                    break;
                }
                ptr = ptr.right;
            }
        }
        return root;
    }
}
// https://leetcode.cn/submissions/detail/322885847/
```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```java
class Solution {
    public int search(int[] nums, int target) {
        return binarySearch(nums, 0, nums.length - 1, target);
    }

    private int binarySearch(int[] nums, int lo, int hi, int target) {
        if (lo > hi) {
            return -1;
        }
        int mid = lo + (hi - lo) / 2;
        if (target < nums[mid]) {
            return binarySearch(nums, lo, mid - 1, target);
        }
        if (nums[mid] < target) {
            return binarySearch(nums, mid + 1, hi, target);
        }
        return mid;
    }
}
// https://leetcode.cn/submissions/detail/368140881/
```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```java
class Solution {
    private int[][] memo;
    private int[] sum1;
    private int[] sum2;

    public int minimumDeleteSum(String s1, String s2) {
        int n1 = s1.length(), n2 = s2.length();
        memo = new int[n1][n2];
        for (int[] a : memo) {
            Arrays.fill(a, -1);
        }
        sum1 = prefixSum(s1);
        sum2 = prefixSum(s2);
        return minimumDeleteSum(s1, n1 - 1, s2, n2 - 1);
    }

    // 子串 s1[0..i] s2[0..j] 的最小 ASCII 删除和
    private int minimumDeleteSum(String s1, int i, String s2, int j) {
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
        if (memo[i][j] == -1) {
            if (s1.charAt(i) == s2.charAt(j)) {
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                memo[i][j] = minimumDeleteSum(s1, i - 1, s2, j - 1);
            } else {
                // 删除 s1[i] s2[j]
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                int sp1 = minimumDeleteSum(s1, i - 1, s2, j - 1) + s1.charAt(i) + s2.charAt(j);
                // 删除 s2[j]
                // s1[0..i]
                // s2[0..j-1][j]
                int sp2 = minimumDeleteSum(s1, i, s2, j - 1) + s2.charAt(j);
                // 删除 s1[i]
                // s1[0..i-1][i]
                // s2[0..j]
                int sp3 = minimumDeleteSum(s1, i - 1, s2, j) + s1.charAt(i);
                memo[i][j] = Math.min(Math.min(sp1, sp2), sp3);
            }
        }
        return memo[i][j];
    }

    private int[] prefixSum(String s) {
        int n = s.length();
        int[] sum = new int[n];
        sum[0] = s.charAt(0);
        for (int i = 1; i < s.length(); ++i) {
            sum[i] = sum[i - 1] + s.charAt(i);
        }
        return sum;
    }
}
// https://leetcode.cn/submissions/detail/374439181/
```

```java
class Solution {
    public int minimumDeleteSum(String s1, String s2) {
        int m = s1.length();
        int n = s2.length();
        int[][] dp = new int[m + 1][n + 1];
        for (int i = 0; i <= m; i++) {
            dp[i][0] = sum(s1, i);
        }
        for (int j = 0; j <= n; j++) {
            dp[0][j] = sum(s2, j);
        }
        for (int i = 1; i <= m; i++) {
            for (int j = 1; j <= n; j++) {
                int result = Integer.MAX_VALUE;
                if (s1.charAt(i - 1) == s2.charAt(j - 1)) {
                    result = dp[i - 1][j - 1];
                } else {
                    result = Math.min(dp[i][j - 1] + s2.charAt(j - 1),
                            dp[i - 1][j] + s1.charAt(i - 1));
                }
                dp[i][j] = result;
            }
        }
        return dp[m][n];
    }

    private int sum(String s, int len) {
        int sum = 0;
        for (int i = 0; i < len; i++) {
            sum += s.charAt(i);
        }
        return sum;
    }
}
// https://leetcode.cn/submissions/detail/330180804/
```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```java
class Solution {
    public int maxProfit(int[] prices, int fee) {
        int n = prices.length;
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        int[][] dp = new int[n][2];
        dp[0][0] = 0;
        dp[0][1] = -prices[0] - fee;
        for (int i = 1; i < n; ++i) {
            // dp[i - 1][0]             >= dp[i - 1][0] - prices[i] - fee
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            dp[i][0] = Math.max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = Math.max(dp[i - 1][0] - prices[i] - fee, dp[i - 1][1]);
        }
        return dp[n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/365503825/
```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```java
class Solution {
    public int[] dailyTemperatures(int[] temperatures) {
        int n = temperatures.length;
        int[] ans = new int[n];
        Deque<Integer> stack = new LinkedList();
        for (int i = n - 1; i >= 0; --i) {
            while (!stack.isEmpty() && temperatures[stack.peek()] <= temperatures[i]) {
                stack.pop();
            }
            ans[i] = stack.isEmpty() ? 0 : stack.peek() - i;
            stack.push(i);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/372226772/
```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```java
class DirectedEdge {
    private final int v;
    private final int w;
    private final double weight;

    public DirectedEdge(int v, int w, double weight) {
        this.v = v;
        this.w = w;
        this.weight = weight;
    }

    public int from() {
        return v;
    }

    public int to() {
        return w;
    }

    public double weight() {
        return weight;
    }
}

class EdgeWeightedDigraph {
    private final int V;
    private int E;
    private LinkedList<DirectedEdge>[] adj;

    public EdgeWeightedDigraph(int V) {
        this.V = V;
        this.E = 0;
        adj = (LinkedList<DirectedEdge>[]) new LinkedList[V];
        for (int v = 0; v < V; ++v) {
            adj[v] = new LinkedList<DirectedEdge>();
        }
    }

    public int V() {
        return V;
    }

    public int E() {
        return E;
    }

    public void addEdge(DirectedEdge e) {
        int v = e.from();
        adj[v].add(e);
        ++E;
    }

    public Iterable<DirectedEdge> adj(int v) {
        return adj[v];
    }
}

class LazyDijkstraSP {
    private boolean[] marked;
    private double[] distTo;
    private DirectedEdge[] edgeTo;
    private PriorityQueue<DirectedEdge> pq;

    private class ByDistanceFromSource implements Comparator<DirectedEdge> {
        public int compare(DirectedEdge e, DirectedEdge f) {
            double dist1 = distTo[e.from()] + e.weight();
            double dist2 = distTo[f.from()] + f.weight();
            return Double.compare(dist1, dist2);
        }
    }

    public LazyDijkstraSP(EdgeWeightedDigraph G, int s) {
        int V = G.V();
        marked = new boolean[V];
        distTo = new double[V];
        edgeTo = new DirectedEdge[V];
        pq = new PriorityQueue<DirectedEdge>(new ByDistanceFromSource());
        for (int v = 0; v < V; ++v) {
            distTo[v] = Double.POSITIVE_INFINITY;
        }
        distTo[s] = 0.0;
        relax(G, s);
        while (!pq.isEmpty()) {
            DirectedEdge e = pq.poll();
            int w = e.to();
            if (!marked[w]) {
                relax(G, w);
            }
        }
    }

    private void relax(EdgeWeightedDigraph G, int v) {
        marked[v] = true;
        for (DirectedEdge e : G.adj(v)) {
            int w = e.to();
            if (distTo[w] > distTo[v] + e.weight()) {
                distTo[w] = distTo[v] + e.weight();
                edgeTo[w] = e;
                pq.offer(e);
            }
        }
    }

    public double distTo(int v) {
        return distTo[v];
    }
}

class Solution {
    public int networkDelayTime(int[][] times, int n, int k) {
        int V = n;
        EdgeWeightedDigraph graph = new EdgeWeightedDigraph(V);
        for (int[] t : times) {
            DirectedEdge e = new DirectedEdge(t[0] - 1, t[1] - 1, t[2]);
            graph.addEdge(e);
        }
        LazyDijkstraSP spt = new LazyDijkstraSP(graph, k - 1);
        double maxTime = 0;
        for (int v = 0; v < V; ++v) {
            maxTime = Math.max(maxTime, spt.distTo(v));
        }
        return maxTime < Double.POSITIVE_INFINITY ? (int) maxTime : -1;
    }
}
// https://leetcode.cn/submissions/detail/371885227/
```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```java
class Solution {
    public int openLock(String[] deadends, String target) {
        Set<String> marked = new HashSet();
        for (String s : deadends) {
            marked.add(s);
        }
        Deque<String> queue = new LinkedList();
        String source = "0000";
        if (!marked.contains(source)) {
            marked.add(source);
            queue.addLast(source);
        }
        int count = 0;
        while (!queue.isEmpty()) {
            int size = queue.size();
            for (int i = 0; i < size; ++i) {
                String s = queue.removeFirst();
                if (s.equals(target)) {
                    return count;
                }
                for (int j = 0; j < 4; ++j) {
                    String plus = plusOne(s, j);
                    if (!marked.contains(plus)) {
                        marked.add(plus);
                        queue.addLast(plus);
                    }
                    String minus = minusOne(s, j);
                    if (!marked.contains(minus)) {
                        marked.add(minus);
                        queue.addLast(minus);
                    }
                }
            }
            ++count;
        }
        return -1;
    }

    private String plusOne(String s, int j) {
        char[] a = s.toCharArray();
        if (a[j] == '9') {
            a[j] = '0';
        } else {
            a[j] += 1;
        }
        return new String(a);
    }

    private String minusOne(String s, int j) {
        char[] a = s.toCharArray();
        if (a[j] == '0') {
            a[j] = '9';
        } else {
            a[j] -= 1;
        }
        return new String(a);
    }
}
// https://leetcode.cn/submissions/detail/374230848/
```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```java
class Solution {
    private boolean isBipartite;
    private boolean[] marked;
    private boolean[] color;

    public boolean isBipartite(int[][] graph) {
        int n = graph.length;
        isBipartite = true;
        marked = new boolean[n];
        color = new boolean[n];
        for (int v = 0; v < n; v++) {
            if (!marked[v]) {
                bfs(graph, v);
            }
        }
        return isBipartite;
    }

    private void bfs(int[][] graph, int s) {
        Queue<Integer> queue = new LinkedList<>();
        marked[s] = true;
        queue.offer(s);
        while (!queue.isEmpty()) {
            int v = queue.poll();
            for (int w : graph[v]) {
                if (!marked[w]) {
                    marked[w] = true;
                    color[w] = !color[v];
                    queue.offer(w);
                } else if (color[w] == color[v]) {
                    isBipartite = false;
                    return;
                }
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/325961175/
```

```java
class Solution {
    private boolean isBipartite;
    private boolean[] marked;
    private boolean[] color;

    public boolean isBipartite(int[][] graph) {
        int n = graph.length;
        isBipartite = true;
        marked = new boolean[n];
        color = new boolean[n];
        for (int v = 0; v < n; v++) {
            if (!marked[v]) {
                dfs(graph, v);
            }
        }
        return isBipartite;
    }

    private void dfs(int[][] graph, int v) {
        marked[v] = true;
        for (int w : graph[v]) {
            if (!isBipartite) return;
            if (!marked[w]) {
                color[w] = !color[v];
                dfs(graph, w);
            } else if (color[w] == color[v]) {
                isBipartite = false;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/325954154/
```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```java
class Solution {
    private List<List<Integer>> ans = new LinkedList();

    public List<List<Integer>> allPathsSourceTarget(int[][] graph) {
        LinkedList<Integer> path = new LinkedList();
        dfs(graph, 0, graph.length - 1, path);
        return ans;
    }

    private void dfs(int[][] graph, int v, int target, LinkedList<Integer> path) {
        path.addLast(v);

        if (v == target) {
            ans.add(new LinkedList(path));
            path.removeLast();
            return;
        }

        for (int w : graph[v]) {
            dfs(graph, w, target, path);
        }
        path.removeLast();
    }
}
// https://leetcode.cn/submissions/detail/325993495/
```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```java
class Solution {
    public boolean isNStraightHand(int[] hand, int groupSize) {
        int n = hand.length;
        if (n % groupSize != 0) {
            return false;
        }
        PriorityQueue<Integer> minPQ = new PriorityQueue<>(n);
        for (int card : hand) {
            minPQ.offer(card);
        }
        while (!minPQ.isEmpty()) {
            int smallest = minPQ.poll();
            for (int i = 1; i < groupSize; ++i) {
                int card = smallest + i;
                if (minPQ.contains(card)) {
                    minPQ.remove(card);
                } else {
                    return false;
                }
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/414920852/
```

```java
class Solution {
    public boolean isNStraightHand(int[] hand, int groupSize) {
        if (hand.length % groupSize != 0) {
            return false;
        }
        Arrays.sort(hand);
        Map<Integer, Integer> counter = new HashMap<>();
        for (int card : hand) {
            counter.put(card, counter.getOrDefault(card, 0) + 1);
        }
        for (int card : hand) {
            if (counter.get(card) > 0) {
                counter.put(card, counter.get(card) - 1);
                for (int i = 1; i < groupSize; ++i) {
                    int d = card + i;
                    int count = counter.getOrDefault(d, 0);
                    if (count > 0) {
                        counter.put(d, count - 1);
                    } else {
                        return false;
                    }
                }
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/414923600/
```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```java
class Solution {
    public int minEatingSpeed(int[] piles, int h) {
        int lo = 1;
        int hi = 1;
        for (int p : piles) {
            hi = Math.max(hi, p);
        }
        int ans = 1;
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
            if (canFinish(piles, mid, h)) {
                ans = mid;
                hi = mid - 1;
            } else {
                lo = mid + 1;
            }
        }
        return ans;
    }

    // 当吃香蕉的速度为 k 时，是否能在 h 小时内吃完
    private boolean canFinish(int[] piles, int k, int h) {
        long t = 0;
        for (int p : piles) {
            t += (p - 1) / k + 1;
        }
        return t <= h;
    }
}
// https://leetcode.cn/submissions/detail/368207719/
```

## 876. 链表的中间结点

<https://leetcode-cn.com/problems/middle-of-the-linked-list/>

```java
class Solution {
    public ListNode middleNode(ListNode head) {
        ListNode slow = head, fast = head;
        while (fast != null && fast.next != null) {
            slow = slow.next;
            fast = fast.next.next;
        }
        return slow;
    }
}
// https://leetcode.cn/submissions/detail/364477918/
```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```java
class Solution {
    private boolean isBipartite;
    private boolean[] marked;
    private boolean[] color;

    public boolean possibleBipartition(int n, int[][] dislikes) {
        List<Integer>[] graph = new LinkedList[n];
        for (int v = 0; v < n; v++) {
            graph[v] = new LinkedList();
        }
        for (int[] d : dislikes) {
            int v = d[0] - 1;
            int w = d[1] - 1;
            graph[v].add(w);
            graph[w].add(v);
        }
        return isBipartite(graph);
    }

    private boolean isBipartite(List<Integer>[] graph) {
        int n = graph.length;
        isBipartite = true;
        marked = new boolean[n];
        color = new boolean[n];
        for (int v = 0; v < n; v++) {
            if (!marked[v]) {
                dfs(graph, v);
            }
        }
        return isBipartite;
    }

    private void dfs(List<Integer>[] graph, int v) {
        marked[v] = true;
        for (int w : graph[v]) {
            if (!isBipartite) return;
            if (!marked[w]) {
                color[w] = !color[v];
                dfs(graph, w);
            } else if (color[w] == color[v]) {
                isBipartite = false;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/325975046/
```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```java
class Solution {
    private Map<Integer, Integer> valToIndex = new HashMap();

    public TreeNode constructFromPrePost(int[] preorder, int[] postorder) {
        for (int i = 0; i < postorder.length; ++i) {
            valToIndex.put(postorder[i], i);
        }
        return buildTree(preorder, 0, preorder.length - 1,
                postorder, 0, postorder.length - 1);
    }

    private TreeNode buildTree(int[] preorder, int preStart, int preEnd,
                               int[] postorder, int postStart, int postEnd) {
        if (preStart > preEnd) {
            return null;
        }
        int rootVal = preorder[preStart];
        TreeNode root = new TreeNode(rootVal);
        if (preStart == preEnd) {
            return root;
        }
        int leftRootVal = preorder[preStart + 1];
        int index = valToIndex.get(leftRootVal);
        int leftSize = index - postStart + 1;
        root.left = buildTree(preorder, preStart + 1, preStart + leftSize,
                postorder, postStart, index);
        root.right = buildTree(preorder, preStart + leftSize + 1, preEnd,
                postorder, index + 1, postEnd - 1);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/364298806/
```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```java
class Solution {
    public int[] sortArrayByParity(int[] nums) {
        int n = nums.length;
        // nums[0..i]   Even
        // nums(i..j)   Scanning
        // nums[j..n-1] Odd
        int i = -1, j = n;
        while (true) {
            while (nums[++i] % 2 == 0) {
                if (i == n - 1) {
                    break;
                }
            }
            while (nums[--j] % 2 == 1) {
                if (j == 0) {
                    break;
                }
            }
            if (i >= j) {
                break;
            }
            exch(nums, i, j);
        }
        return nums;
    }

    private void exch(int[] nums, int i, int j) {
        int swap = nums[i];
        nums[i] = nums[j];
        nums[j] = swap;
    }
}
// https://leetcode.cn/submissions/detail/362459667/
```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```java
class Solution {
    public int[] sortArray(int[] nums) {
        List<Integer> list = Arrays.stream(nums).boxed().collect(Collectors.toList());
        Collections.shuffle(list);
        nums = list.stream().mapToInt(i -> i).toArray();
        sort(nums, 0, nums.length - 1);
        return nums;
    }

    private void sort(int[] nums, int lo, int hi) {
        if (lo >= hi) {
            return;
        }
        int j = partition(nums, lo, hi);
        sort(nums, lo, j - 1);
        sort(nums, j + 1, hi);
    }

    private int partition(int[] nums, int lo, int hi) {
        int v = nums[lo];
        int i = lo, j = hi + 1;
        while (true) {
            while (nums[++i] < v) {
                if (i == hi) {
                    break;
                }
            }
            while (v < nums[--j]) {
                if (j == lo) {
                    break;
                }
            }
            if (i >= j) {
                break;
            }
            exch(nums, i, j);
        }
        exch(nums, lo, j);
        return j;
    }

    private void exch(int[] nums, int i, int j) {
        int swap = nums[i];
        nums[i] = nums[j];
        nums[j] = swap;
    }
}
// https://leetcode.cn/submissions/detail/366421198/
```

```java
class Solution {
    public int[] sortArray(int[] nums) {
        List<Integer> list = Arrays.stream(nums).boxed().collect(Collectors.toList());
        Collections.shuffle(list);
        nums = list.stream().mapToInt(i -> i).toArray();
        // 三向切分的快速排序算法
        sort(nums, 0, nums.length - 1);
        return nums;
    }

    void sort(int[] nums, int lo, int hi) {
        if (lo >= hi) return;

        int lt = lo, gt = hi, i = lo + 1;
        int v = nums[lo];
        while (i <= gt) {
            if (nums[i] < v) exch(nums, lt++, i++);
            else if (nums[i] > v) exch(nums, i, gt--);
            else i++;
        }

        sort(nums, lo, lt - 1);
        sort(nums, gt + 1, hi);
    }

    void exch(int[] nums, int i, int j) {
        int t = nums[i];
        nums[i] = nums[j];
        nums[j] = t;
    }
}
// https://leetcode.cn/submissions/detail/323470609/
```

```java
class Solution {
    public int[] sortArray(int[] nums) {
        List<Integer> list = Arrays.stream(nums).boxed().collect(Collectors.toList());
        Collections.shuffle(list);
        nums = list.stream().mapToInt(i -> i).toArray();
        // 归并排序算法
        int n = nums.length;
        int[] aux = new int[n];
        sort(nums, 0, n - 1, aux);
        return nums;
    }

    void sort(int[] nums, int lo, int hi, int[] aux) {
        if (lo >= hi) return;
        int mid = lo + (hi - lo) / 2;
        sort(nums, lo, mid, aux);
        sort(nums, mid + 1, hi, aux);
        merge(nums, lo, mid, hi, aux);
    }

    void merge(int[] nums, int lo, int mid, int hi, int[] aux) {
        for (int k = lo; k <= hi; k++)
            aux[k] = nums[k];

        int i = lo, j = mid + 1;
        for (int k = lo; k <= hi; k++) {
            if (i > mid) nums[k] = aux[j++];
            else if (j > hi) nums[k] = aux[i++];
            else if (aux[i] < aux[j]) nums[k] = aux[i++];
            else nums[k] = aux[j++];
        }
    }
}
// https://leetcode.cn/submissions/detail/323478349/
```

```java
class Solution {
    public int[] sortArray(int[] nums) {
        List<Integer> list = Arrays.stream(nums).boxed().collect(Collectors.toList());
        Collections.shuffle(list);
        nums = list.stream().mapToInt(i -> i).toArray();
        // 自底向上的归并排序算法
        int n = nums.length;
        int[] aux = new int[n];
        for (int len = 1; len < n; len *= 2) {
            for (int lo = 0; lo + len < n; lo += 2 * len) {
                int mid = lo + len - 1;
                int hi = Math.min(lo + 2 * len - 1, n - 1);
                merge(nums, lo, mid, hi, aux);
            }
        }
        return nums;
    }

    void merge(int[] nums, int lo, int mid, int hi, int[] aux) {
        for (int k = lo; k <= hi; k++)
            aux[k] = nums[k];

        int i = lo, j = mid + 1;
        for (int k = lo; k <= hi; k++) {
            if (i > mid) nums[k] = aux[j++];
            else if (j > hi) nums[k] = aux[i++];
            else if (aux[i] < aux[j]) nums[k] = aux[i++];
            else nums[k] = aux[j++];
        }
    }
}
// https://leetcode.cn/submissions/detail/323481991/
```

```java
class Solution {
    public int[] sortArray(int[] nums) {
        List<Integer> list = Arrays.stream(nums).boxed().collect(Collectors.toList());
        Collections.shuffle(list);
        nums = list.stream().mapToInt(i -> i).toArray();
        Deque<int[]> stack = new LinkedList();
        stack.push(new int[]{0, nums.length - 1});
        while (!stack.isEmpty()) {
            int[] interval = stack.pop();
            int lo = interval[0];
            int hi = interval[1];
            if (lo >= hi) {
                continue;
            }
            int j = partition(nums, lo, hi);
            stack.push(new int[]{j + 1, hi});
            stack.push(new int[]{lo, j - 1});
        }
        return nums;
    }

    private int partition(int[] nums, int lo, int hi) {
        int v = nums[lo];
        int i = lo, j = hi + 1;
        while (true) {
            while (nums[++i] < v) {
                if (i == hi) {
                    break;
                }
            }
            while (v < nums[--j]) {
                if (j == lo) {
                    break;
                }
            }
            if (i >= j) {
                break;
            }
            exch(nums, i, j);
        }
        exch(nums, lo, j);
        return j;
    }

    private void exch(int[] nums, int i, int j) {
        int swap = nums[i];
        nums[i] = nums[j];
        nums[j] = swap;
    }
}
// https://leetcode.cn/submissions/detail/366421584/
```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```java
// 性质一 一个「合法」括号组合的左括号数量一定等于右括号数量
// 性质二 对于一个「合法」的括号字符串组合 p，必然对于
// 任何 0 <= i < len(p) 都有：子串 p[0..i] 中
// 左括号的数量都大于或等于右括号的数量
class Solution {
    public int minAddToMakeValid(String s) {
        int insertLeft = 0; // 已插入左括号的数量
        int needRight = 0;  // 待插入右括号的数量
        for (int i = 0; i < s.length(); ++i) {
            char ch = s.charAt(i);
            if (ch == '(') {
                ++needRight;
            }
            if (ch == ')') {
                --needRight;
                // 性质二
                if (needRight == -1) {
                    // A).. -> A()..
                    //『必须立即』在位置 i 前插入 1 个左括号
                    // 否则，后续任何插入都不能使区间 [0..i] 的匹配有效
                    ++insertLeft;
                    needRight = 0;
                }
            }
        }
        return insertLeft + needRight;
    }
}
// https://leetcode.cn/submissions/detail/374110551/
```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```java
class Solution {
    public int[] sortArrayByParityII(int[] nums) {
        int n = nums.length;
        int i = 0, j = 1;
        while (true) {
            while (i <= n - 2 && nums[i] % 2 == 0) {
                i += 2;
            }
            while (j <= n - 1 && nums[j] % 2 == 1) {
                j += 2;
            }
            if (i > n - 2 || j > n - 1) {
                break;
            }
            exch(nums, i, j);
        }
        return nums;
    }

    private void exch(int[] nums, int i, int j) {
        int swap = nums[i];
        nums[i] = nums[j];
        nums[j] = swap;
    }
}
// https://leetcode.cn/submissions/detail/363993070/
```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```java
class Solution {
    private int[][] memo;

    public int minFallingPathSum(int[][] matrix) {
        int n = matrix.length;
        memo = new int[n][n];
        for (int[] a : memo) {
            Arrays.fill(a, Integer.MIN_VALUE);
        }
        int ans = Integer.MAX_VALUE;
        for (int col = 0; col < n; ++col) {
            ans = Math.min(ans, minFallingPathSum(matrix, n - 1, col));
        }
        return ans;
    }

    // 从 matrix[0][0..n-1] 到 matrix[row][col] 的最小下降路径和
    private int minFallingPathSum(int[][] matrix, int row, int col) {
        if (col < 0 || col >= matrix.length) {
            return Integer.MAX_VALUE;
        }
        if (row == 0) {
            return matrix[row][col];
        }
        if (memo[row][col] == Integer.MIN_VALUE) {
            int sp1 = minFallingPathSum(matrix, row - 1, col - 1); // 左上
            int sp2 = minFallingPathSum(matrix, row - 1, col);     // 正上
            int sp3 = minFallingPathSum(matrix, row - 1, col + 1); // 右上
            memo[row][col] = Math.min(Math.min(sp1, sp2), sp3) + matrix[row][col];
        }
        return memo[row][col];
    }
}
// https://leetcode.cn/submissions/detail/375061507/
```

```java
class Solution {
    public int minFallingPathSum(int[][] matrix) {
        int n = matrix.length;
        int[][] dp = new int[n][n];
        for (int col = 0; col < n; col++) {
            dp[0][col] = matrix[0][col];
        }

        for (int row = 1; row < n; row++) {
            for (int col = 0; col < n; col++) {
                int result = dp[row - 1][col];
                if (col - 1 >= 0) {
                    result = Math.min(result, dp[row - 1][col - 1]);
                }
                if (col + 1 <= n - 1) {
                    result = Math.min(result, dp[row - 1][col + 1]);
                }
                dp[row][col] = matrix[row][col] + result;
            }
        }
        int ans = Integer.MAX_VALUE;
        for (int col = 0; col < n; col++) {
            ans = Math.min(ans, dp[n - 1][col]);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/331703383/
```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```java
class Solution {
    public int[][] intervalIntersection(int[][] firstList, int[][] secondList) {
        List<int[]> list = new LinkedList();
        int i = 0, j = 0;
        while (i < firstList.length && j < secondList.length) {
            int start1 = firstList[i][0], end1 = firstList[i][1];
            int start2 = secondList[j][0], end2 = secondList[j][1];
            if (end1 < start2) { // 不相交
                ++i;
            } else if (end2 < start1) { // 不相交
                ++j;
            } else { // 相交
                list.add(new int[]{Math.max(start1, start2), Math.min(end1, end2)});
                if (end1 < end2) {
                    ++i;
                } else {
                    ++j;
                }
            }
        }
        int[][] ans = new int[list.size()][2];
        int t = 0;
        for (int[] interval : list) {
            ans[t++] = interval;
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/358945983/
```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```java
class UF {
    private int[] parent;
    private byte[] rank;
    private int count;

    public UF(int n) {
        parent = new int[n];
        rank = new byte[n];
        for (int i = 0; i < n; ++i) {
            parent[i] = i;
        }
        count = n;
    }

    public int find(int p) {
        while (p != parent[p]) {
            parent[p] = parent[parent[p]];
            p = parent[p];
        }
        return p;
    }

    public void union(int p, int q) {
        int rootP = find(p);
        int rootQ = find(q);
        if (rootP != rootQ) {
            if (rank[rootP] < rank[rootQ]) {
                parent[rootP] = rootQ;
            } else if (rank[rootQ] < rank[rootP]) {
                parent[rootQ] = rootP;
            } else {
                parent[rootP] = rootQ;
                ++rank[rootQ];
            }
            --count;
        }
    }

    public boolean connected(int p, int q) {
        return find(p) == find(q);
    }

    public int count() {
        return count;
    }
}

class Solution {
    public boolean equationsPossible(String[] equations) {
        UF uf = new UF(26);
        for (String s : equations) {
            if (s.charAt(1) == '=') {
                int p = s.charAt(0) - 'a';
                int q = s.charAt(3) - 'a';
                uf.union(p, q);
            }
        }
        for (String s : equations) {
            if (s.charAt(1) == '!') {
                int p = s.charAt(0) - 'a';
                int q = s.charAt(3) - 'a';
                if (uf.connected(p, q)) {
                    return false;
                }
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/374243262/
```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```java
class Solution {
    public int shipWithinDays(int[] weights, int days) {
        int lo = 0, hi = 0;
        for (int w : weights) {
            lo = Math.max(lo, w);
            hi += w;
        }
        int ans = lo;
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
            if (canFinish(weights, days, mid)) {
                ans = mid;
                hi = mid - 1;
            } else {
                lo = mid + 1;
            }
        }
        return ans;
    }

    // 当船的运载能力为 capacity 时，是否能在 days 天内送完
    private boolean canFinish(int[] weights, int days, int capacity) {
        int minDays = 0;
        int i = 0, n = weights.length;
        while (i < n) {
            int sum = 0;
            while (i < n && sum + weights[i] <= capacity) {
                sum += weights[i++];
            }
            ++minDays;
        }
        return minDays <= days;
    }
}
// https://leetcode.cn/submissions/detail/393036553/
```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```java
class Solution {
    private static final int LAND = 1;
    private static final int WATER = 0;

    public int numEnclaves(int[][] grid) {
        int m = grid.length;
        int n = grid[0].length;
        // 淹没与左右边界的陆地相连的岛屿
        for (int row = 0; row < m; ++row) {
            floodFill(grid, row, 0);
            floodFill(grid, row, n - 1);
        }
        // 淹没与上下边界的陆地相连的岛屿
        for (int col = 0; col < n; ++col) {
            floodFill(grid, 0, col);
            floodFill(grid, m - 1, col);
        }
        int count = 0;
        for (int row = 0; row < m; ++row) {
            for (int col = 0; col < n; ++col) {
                if (grid[row][col] == LAND) {
                    ++count;
                }
            }
        }
        return count;
    }

    private void floodFill(int[][] grid, int row, int col) {
        if (row < 0 || row >= grid.length || col < 0 || col >= grid[0].length || grid[row][col] == WATER) {
            return;
        }
        grid[row][col] = WATER;
        floodFill(grid, row, col + 1);
        floodFill(grid, row, col - 1);
        floodFill(grid, row + 1, col);
        floodFill(grid, row - 1, col);
    }
}
// https://leetcode.cn/submissions/detail/416184747/
```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```java
// 测试用例
// [[0,1],[6,8],[0,2],[5,6],[0,4],[0,3],[6,7],[1,3],[4,7],[1,4],[2,5],[2,6],[3,4],[4,5],[5,7],[6,9]]
// 9
// 排序后
// [[0,4],[0,3],[0,2],[0,1],[1,4],[1,3],[2,6],[2,5],[3,4],[4,7],[4,5],[5,7],[5,6],[6,9],[6,8],[6,7]]
// 删除被覆盖区间后 [0,4],[2,6],[4,7],[6,9]
// 虽然 [2,6],[4,7] 都与 [0,4] 相交，但是只取 end 最大的区间 [4,7]
// 正确答案 [0,4],[4,7],[6,9]
// 相似题目 1288. 删除被覆盖区间 https://leetcode.cn/problems/remove-covered-intervals/
class Solution {
    public int videoStitching(int[][] clips, int time) {
        Arrays.sort(clips, (a, b) -> {
            if (a[0] == b[0]) {
                return b[1] - a[1];
            }
            return a[0] - b[0];
        });
        int maxEnd = 0;
        int count = 0;
        int i = 0, n = clips.length;
        // 当 clips[i] 与 [0, maxEnd] 重叠（相交或被覆盖）时
        while (i < n && clips[i][0] <= maxEnd) {
            // 记录与 [0, maxEnd] 重叠的所有区间中最大的 end
            int nextEnd = clips[i][1];
            while (++i < n && clips[i][0] <= maxEnd) {
                nextEnd = Math.max(nextEnd, clips[i][1]);
            }
            maxEnd = nextEnd;
            ++count;
            if (maxEnd >= time) {
                return count;
            }
        }
        return -1;
    }
}
// https://leetcode.cn/submissions/detail/374218167/
```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```java
class Solution {
    public int longestCommonSubsequence(String text1, String text2) {
        int n1 = text1.length();
        int n2 = text2.length();
        // text1[0..i-1] = text1 的长度为 i 的前缀
        // text2[0..j-1] = text2 的长度为 j 的前缀
        // dp[i][j] = LCS(text1[0..i-1], text2[0..j-1]) 的长度
        int[][] dp = new int[n1 + 1][n2 + 1];
        for (int i = 1; i <= n1; ++i) {
            for (int j = 1; j <= n2; ++j) {
                // text1[i-1] = text2[j-1]
                if (text1.charAt(i - 1) == text2.charAt(j - 1)) {
                    dp[i][j] = dp[i - 1][j - 1] + 1;
                } else {
                    // text1[i-1] != text2[j-1]

                    // text1[i-1] 是公共字符，text2[j-1] 是公共字符
                    // dp[i][j-1] = dp[i-1][j-1] + 1
                    // dp[i-1][j] = dp[i-1][j-1] + 1
                    // dp[i][j] = dp[i][j-1] = dp[i-1][j] = dp[i-1][j-1] + 1

                    // text1[i-1] 是公共字符，text2[j-1] 不是公共字符
                    // dp[i][j-1] = dp[i-1][j-1] + 1
                    // dp[i-1][j] = dp[i-1][j-1]
                    // dp[i][j-1] > dp[i-1][j]
                    // dp[i][j] = dp[i][j-1]

                    // text1[i-1] 不是公共字符，text2[j-1] 是公共字符
                    // dp[i][j-1] = dp[i-1][j-1]
                    // dp[i-1][j] = dp[i-1][j-1] + 1
                    // dp[i][j-1] < dp[i-1][j]
                    // dp[i][j] = dp[i-1][j]

                    // text1[i-1] 不是公共字符，text2[j-1] 不是公共字符
                    // dp[i][j] = dp[i][j-1] = dp[i-1][j] = dp[i-1][j-1]

                    // if (dp[i][j - 1] > dp[i - 1][j]) {
                    //     dp[i][j] = dp[i][j - 1];
                    // } else if (dp[i][j - 1] < dp[i - 1][j]) {
                    //     dp[i][j] = dp[i - 1][j];
                    // } else if (dp[i][j - 1] > dp[i - 1][j - 1]) {
                    //     dp[i][j] = dp[i - 1][j - 1] + 1;
                    // } else {
                    //     dp[i][j] = dp[i - 1][j - 1];
                    // }
                    dp[i][j] = Math.max(dp[i][j - 1], dp[i - 1][j]);
                }
            }
        }
        return dp[n1][n2];
    }
}
// https://leetcode.cn/submissions/detail/374550792/
```

```java
class Solution {
    private int[][] memo;

    public int longestCommonSubsequence(String text1, String text2) {
        int n1 = text1.length();
        int n2 = text2.length();
        memo = new int[n1][n2];
        for (int[] a : memo) {
            Arrays.fill(a, -1);
        }
        return longestCommonSubsequence(text1, n1 - 1, text2, n2 - 1);
    }

    // LCS(text1[0..i], text2[0..j]) 的长度
    private int longestCommonSubsequence(String text1, int i, String text2, int j) {
        if (i < 0 || j < 0) {
            return 0;
        }
        if (memo[i][j] == -1) {
            if (text1.charAt(i) == text2.charAt(j)) {
                memo[i][j] = longestCommonSubsequence(text1, i - 1, text2, j - 1) + 1;
            } else {
                int sp1 = longestCommonSubsequence(text1, i, text2, j - 1);
                int sp2 = longestCommonSubsequence(text1, i - 1, text2, j);
                memo[i][j] = Math.max(sp1, sp2);
            }
        }
        return memo[i][j];
    }
}
// https://leetcode.cn/submissions/detail/374555858/
```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```java
class Solution {
    private static final int LAND = 0;
    private static final int WATER = 1;

    public int closedIsland(int[][] grid) {
        int m = grid.length;
        int n = grid[0].length;
        // 淹没与左右边界的陆地相连的岛屿
        for (int i = 0; i < m; ++i) {
            floodFill(grid, i, 0);
            floodFill(grid, i, n - 1);
        }
        // 淹没与上下边界的陆地相连的岛屿
        for (int j = 0; j < n; ++j) {
            floodFill(grid, 0, j);
            floodFill(grid, m - 1, j);
        }
        int count = 0;
        for (int i = 0; i < m; ++i) {
            for (int j = 0; j < n; ++j) {
                if (grid[i][j] == LAND) {
                    floodFill(grid, i, j);
                    ++count;
                }
            }
        }
        return count;
    }

    private void floodFill(int[][] grid, int i, int j) {
        if (i < 0 || i >= grid.length || j < 0 || j >= grid[0].length || grid[i][j] == WATER) {
            return;
        }
        grid[i][j] = WATER;
        floodFill(grid, i, j + 1);
        floodFill(grid, i, j - 1);
        floodFill(grid, i + 1, j);
        floodFill(grid, i - 1, j);
    }
}
// https://leetcode.cn/submissions/detail/362789819/
```

```java
class Solution {
    private static final int LAND = 0;
    private static final int WATER = 1;

    private class UF {
        private int[] parent;
        private byte[] rank;
        private int count;

        public UF(int n) {
            count = n;
            parent = new int[n];
            rank = new byte[n];
            for (int i = 0; i < n; i++) {
                parent[i] = i;
                rank[i] = 0;
            }
        }

        public int find(int p) {
            while (p != parent[p]) {
                parent[p] = parent[parent[p]];
                p = parent[p];
            }
            return p;
        }

        public void union(int p, int q) {
            int rootP = find(p);
            int rootQ = find(q);
            if (rootP != rootQ) {
                if (rank[rootP] < rank[rootQ]) {
                    parent[rootP] = rootQ;
                } else if (rank[rootP] > rank[rootQ]) {
                    parent[rootQ] = rootP;
                } else {
                    parent[rootP] = rootQ;
                    ++rank[rootQ];
                }
                --count;
            }
        }

        public boolean connected(int p, int q) {
            return find(p) == find(q);
        }

        public int count() {
            return count;
        }
    }

    public int closedIsland(int[][] grid) {
        int m = grid.length;
        int n = grid[0].length;
        UF uf = new UF(m * n + 1);
        int dummy = m * n;
        // 左右两边的陆地与 dummy 相连
        for (int i = 0; i < m; ++i) {
            if (grid[i][0] == LAND) {
                uf.union(dummy, i * n);
            }
            if (grid[i][n - 1] == LAND) {
                uf.union(dummy, i * n + (n - 1));
            }
        }
        // 上下两边的陆地与 dummy 相连
        for (int j = 0; j < n; ++j) {
            if (grid[0][j] == LAND) {
                uf.union(dummy, j);
            }
            if (grid[m - 1][j] == LAND) {
                uf.union(dummy, (m - 1) * n + j);
            }
        }
        int water = 0;
        int[][] directions = new int[][]{{0, 1}, {0, -1}, {1, 0}, {-1, 0}};
        for (int i = 0; i < m; ++i) {
            for (int j = 0; j < n; ++j) {
                if (grid[i][j] == LAND) {
                    for (int[] d : directions) {
                        int x = i + d[0];
                        int y = j + d[1];
                        if (0 <= x && x < m && 0 <= y && y < n && grid[x][y] == grid[i][j]) {
                            int p = i * n + j;
                            int q = x * n + y;
                            uf.union(p, q);
                        }
                    }
                } else {
                    ++water;
                }
            }
        }
        return uf.count() - water - 1;
    }
}
// https://leetcode.cn/submissions/detail/360609706/
```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```java
class Solution {
    public int removeCoveredIntervals(int[][] intervals) {
        Arrays.sort(intervals, (a, b) -> {
            if (a[0] == b[0]) {
                return b[1] - a[1];
            }
            return a[0] - b[0];
        });
        int n = intervals.length;
        int count = n;
        int maxEnd = 0;
        for (int i = 0; i < n; ++i) {
            int end = intervals[i][1];
            if (end <= maxEnd) {
                --count;
            } else {
                maxEnd = end;
            }
        }
        return count;
    }
}
// https://leetcode.cn/submissions/detail/372387971/
```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```java
class Solution {
    private List<Integer> inorder = new LinkedList();

    public TreeNode balanceBST(TreeNode root) {
        dfs(root);
        int n = inorder.size();
        int[] nums = new int[n];
        int i = 0;
        for (int x : inorder) {
            nums[i++] = x;
        }
        return sortedArrayToBST(nums, 0, n - 1);
    }

    // 深度优先搜索，获取中序遍历结果 inorder
    private void dfs(TreeNode root) {
        if (root == null) {
            return;
        }
        dfs(root.left);
        inorder.add(root.val);
        dfs(root.right);
    }

    // 将有序数组 nums[lo..hi] 转换为二叉搜索树
    private TreeNode sortedArrayToBST(int[] nums, int lo, int hi) {
        if (lo > hi) {
            return null;
        }
        int mid = lo + (hi - lo) / 2;
        TreeNode root = new TreeNode(nums[mid]);
        root.left = sortedArrayToBST(nums, lo, mid - 1);
        root.right = sortedArrayToBST(nums, mid + 1, hi);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/365903001/
```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```java
class DirectedEdge {
    private final int v;
    private final int w;
    private final double weight;

    public DirectedEdge(int v, int w, double weight) {
        this.v = v;
        this.w = w;
        this.weight = weight;
    }

    public int from() {
        return v;
    }

    public int to() {
        return w;
    }

    public double weight() {
        return weight;
    }
}

class EdgeWeightedDigraph {
    private final int V;
    private int E;
    private LinkedList<DirectedEdge>[] adj;

    public EdgeWeightedDigraph(int V) {
        this.V = V;
        this.E = 0;
        adj = (LinkedList<DirectedEdge>[]) new LinkedList[V];
        for (int v = 0; v < V; ++v) {
            adj[v] = new LinkedList<DirectedEdge>();
        }
    }

    public int V() {
        return V;
    }

    public int E() {
        return E;
    }

    public void addEdge(DirectedEdge e) {
        int v = e.from();
        adj[v].add(e);
        ++E;
    }

    public Iterable<DirectedEdge> adj(int v) {
        return adj[v];
    }
}

class LazyDijkstraLP {
    private boolean[] marked;
    private double[] distTo;
    private DirectedEdge[] edgeTo;
    private PriorityQueue<DirectedEdge> pq;

    private class ByDistanceFromSource implements Comparator<DirectedEdge> {
        public int compare(DirectedEdge e, DirectedEdge f) {
            double dist1 = distToEdge(e);
            double dist2 = distToEdge(f);
            return Double.compare(dist2, dist1);
        }
    }

    public LazyDijkstraLP(EdgeWeightedDigraph G, int s) {
        int V = G.V();
        marked = new boolean[V];
        distTo = new double[V];
        edgeTo = new DirectedEdge[V];
        pq = new PriorityQueue<DirectedEdge>(new ByDistanceFromSource());
        for (int v = 0; v < V; ++v) {
            distTo[v] = Double.NEGATIVE_INFINITY;
        }
        distTo[s] = 1.0;
        relax(G, s);
        while (!pq.isEmpty()) {
            DirectedEdge e = pq.poll();
            int w = e.to();
            if (!marked[w]) {
                relax(G, w);
            }
        }
    }

    private void relax(EdgeWeightedDigraph G, int v) {
        marked[v] = true;
        for (DirectedEdge e : G.adj(v)) {
            int w = e.to();
            double d = distToEdge(e);
            if (distTo[w] < d) {
                distTo[w] = d;
                edgeTo[w] = e;
                pq.offer(e);
            }
        }
    }

    private double distToEdge(DirectedEdge e) {
        return distTo[e.from()] * e.weight();
    }

    public boolean hasPathTo(int v) {
        return marked[v];
    }

    public double distTo(int v) {
        return distTo[v];
    }
}

class Solution {
    public double maxProbability(int n, int[][] edges, double[] succProb, int start, int end) {
        EdgeWeightedDigraph graph = new EdgeWeightedDigraph(n);
        for (int i = 0; i < edges.length; ++i) {
            int v = edges[i][0];
            int w = edges[i][1];
            double weight = succProb[i];
            graph.addEdge(new DirectedEdge(v, w, weight));
            graph.addEdge(new DirectedEdge(w, v, weight));
        }
        LazyDijkstraLP lpt = new LazyDijkstraLP(graph, start);
        if (lpt.hasPathTo(end)) {
            return lpt.distTo(end);
        }
        return 0.0;
    }
}
// https://leetcode.cn/submissions/detail/371973442/
```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```java
class Solution {
    public int minInsertions(String s) {
        int insertLeft = 0;  // 已插入左括号的数量
        int insertRight = 0; // 已插入右括号的数量
        int needRight = 0;   // 待插入右括号的数量
        for (int i = 0; i < s.length(); ++i) {
            char ch = s.charAt(i);
            if (ch == '(') {
                // A((B)(.. -> A((B))(..
                if (needRight % 2 == 1) {
                    //『必须立即』在位置 i 前插入 1 个右括号
                    // 否则，后续任何插入都不能使区间 [0..i-1] 的匹配有效
                    ++insertRight;
                    --needRight;
                }
                needRight += 2;
            }
            if (ch == ')') {
                --needRight;
                // A).. -> A()..
                if (needRight == -1) {
                    //『必须立即』在位置 i 前插入 1 个左括号
                    // 否则，后续任何插入都不能使区间 [0..i] 的匹配有效
                    ++insertLeft;
                    needRight = 1;
                }
            }
        }
        return insertLeft + insertRight + needRight;
    }
}
// https://leetcode.cn/submissions/detail/374116635/
```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```java
class Edge implements Comparable<Edge> {
    private final int v;
    private final int w;
    private final double weight;

    public Edge(int v, int w, double weight) {
        this.v = v;
        this.w = w;
        this.weight = weight;
    }

    public double weight() {
        return weight;
    }

    public int either() {
        return v;
    }

    public int other(int vertex) {
        if (vertex == v) {
            return w;
        }
        return v;
    }

    public int compareTo(Edge that) {
        return Double.compare(this.weight, that.weight);
    }
}

class EdgeWeightedGraph {
    private final int V;
    private int E;
    private LinkedList<Edge>[] adj;

    public EdgeWeightedGraph(int V) {
        this.V = V;
        this.E = 0;
        adj = (LinkedList<Edge>[]) new LinkedList[V];
        for (int v = 0; v < V; ++v) {
            adj[v] = new LinkedList<Edge>();
        }
    }

    public int V() {
        return V;
    }

    public int E() {
        return E;
    }

    public void addEdge(Edge e) {
        int v = e.either();
        int w = e.other(v);
        adj[v].add(e);
        adj[w].add(e);
        ++E;
    }

    public Iterable<Edge> adj(int v) {
        return adj[v];
    }

    public Iterable<Edge> edges() {
        LinkedList<Edge> list = new LinkedList();
        for (int v = 0; v < V; ++v) {
            for (Edge e : adj(v)) {
                int w = e.other(v);
                if (v < w) {
                    list.add(e);
                }
            }
        }
        return list;
    }
}

class LazyPrimMST {
    private double weight;
    private Queue<Edge> mst;
    private boolean[] marked;
    private PriorityQueue<Edge> pq;

    public LazyPrimMST(EdgeWeightedGraph G) {
        mst = new LinkedList<Edge>();
        pq = new PriorityQueue<Edge>();
        int V = G.V();
        marked = new boolean[V];
        for (int v = 0; v < V; ++v) {
            if (!marked[v]) {
                prim(G, v);
            }
        }
    }

    private void prim(EdgeWeightedGraph G, int s) {
        scan(G, s);
        while (!pq.isEmpty()) {
            Edge e = pq.poll();
            int v = e.either();
            int w = e.other(v);
            if (marked[v] && marked[w]) {
                continue;
            }
            mst.add(e);
            weight += e.weight();
            if (!marked[v]) {
                scan(G, v);
            }
            if (!marked[w]) {
                scan(G, w);
            }
        }
    }

    private void scan(EdgeWeightedGraph G, int v) {
        marked[v] = true;
        for (Edge e : G.adj(v)) {
            int w = e.other(v);
            if (!marked[w]) {
                pq.offer(e);
            }
        }
    }

    public Iterable<Edge> edges() {
        return mst;
    }

    public double weight() {
        return weight;
    }
}

class Solution {
    public int minCostConnectPoints(int[][] points) {
        int V = points.length;
        EdgeWeightedGraph graph = new EdgeWeightedGraph(V);
        for (int v = 0; v < V; ++v) {
            for (int w = v + 1; w < V; ++w) {
                double weight = Math.abs(points[v][0] - points[w][0]) +
                        Math.abs(points[v][1] - points[w][1]);
                graph.addEdge(new Edge(v, w, weight));
            }
        }
        LazyPrimMST mst = new LazyPrimMST(graph);
        return (int) mst.weight();
    }
}
// https://leetcode.cn/submissions/detail/371885804/
```

```java
class Edge implements Comparable<Edge> {
    private final int v;
    private final int w;
    private final double weight;

    public Edge(int v, int w, double weight) {
        this.v = v;
        this.w = w;
        this.weight = weight;
    }

    public double weight() {
        return weight;
    }

    public int either() {
        return v;
    }

    public int other(int vertex) {
        if (vertex == v) {
            return w;
        }
        return v;
    }

    public int compareTo(Edge that) {
        return Double.compare(this.weight, that.weight);
    }
}

class EdgeWeightedGraph {
    private final int V;
    private int E;
    private LinkedList<Edge>[] adj;

    public EdgeWeightedGraph(int V) {
        this.V = V;
        this.E = 0;
        adj = (LinkedList<Edge>[]) new LinkedList[V];
        for (int v = 0; v < V; ++v) {
            adj[v] = new LinkedList<Edge>();
        }
    }

    public int V() {
        return V;
    }

    public int E() {
        return E;
    }

    public void addEdge(Edge e) {
        int v = e.either();
        int w = e.other(v);
        adj[v].add(e);
        adj[w].add(e);
        ++E;
    }

    public Iterable<Edge> adj(int v) {
        return adj[v];
    }

    public Iterable<Edge> edges() {
        LinkedList<Edge> list = new LinkedList();
        for (int v = 0; v < V; ++v) {
            for (Edge e : adj(v)) {
                int w = e.other(v);
                if (v < w) {
                    list.add(e);
                }
            }
        }
        return list;
    }
}

class UF {
    private int[] parent;
    private byte[] rank;
    private int count;

    public UF(int n) {
        parent = new int[n];
        rank = new byte[n];
        for (int i = 0; i < n; ++i) {
            parent[i] = i;
            rank[i] = 0;
        }
        count = n;
    }

    public int find(int p) {
        while (p != parent[p]) {
            parent[p] = parent[parent[p]];
            p = parent[p];
        }
        return p;
    }

    public void union(int p, int q) {
        int rootP = find(p);
        int rootQ = find(q);
        if (rootP != rootQ) {
            if (rank[rootP] < rank[rootQ]) {
                parent[rootP] = rootQ;
            } else if (rank[rootP] > rank[rootQ]) {
                parent[rootQ] = rootP;
            } else {
                parent[rootP] = rootQ;
                ++rank[rootQ];
            }
            --count;
        }
    }

    public boolean connected(int p, int q) {
        return find(p) == find(q);
    }

    public int count() {
        return count;
    }
}

class KruskalMST {
    private double weight;
    private Queue<Edge> mst = new LinkedList();

    public KruskalMST(EdgeWeightedGraph G) {
        Edge[] edges = new Edge[G.E()];
        int t = 0;
        for (Edge e : G.edges()) {
            edges[t++] = e;
        }
        Arrays.sort(edges);
        int V = G.V();
        UF uf = new UF(V);
        for (Edge e : edges) {
            int v = e.either();
            int w = e.other(v);
            if (!uf.connected(v, w)) {
                uf.union(v, w);
                mst.add(e);
                weight += e.weight();
                if (mst.size() == V - 1) {
                    break;
                }
            }
        }
    }

    public double weight() {
        return weight;
    }
}

class Solution {
    public int minCostConnectPoints(int[][] points) {
        int V = points.length;
        EdgeWeightedGraph graph = new EdgeWeightedGraph(V);
        for (int v = 0; v < V; ++v) {
            for (int w = v + 1; w < V; ++w) {
                double weight = Math.abs(points[v][0] - points[w][0]) +
                        Math.abs(points[v][1] - points[w][1]);
                graph.addEdge(new Edge(v, w, weight));
            }
        }
        KruskalMST mst = new KruskalMST(graph);
        return (int) mst.weight();
    }
}
// https://leetcode.cn/submissions/detail/371885645/
```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```java
class DirectedEdge {
    private final int v;
    private final int w;
    private final double weight;

    public DirectedEdge(int v, int w, double weight) {
        this.v = v;
        this.w = w;
        this.weight = weight;
    }

    public int from() {
        return v;
    }

    public int to() {
        return w;
    }

    public double weight() {
        return weight;
    }
}

class EdgeWeightedDigraph {
    private final int V;
    private int E;
    private LinkedList<DirectedEdge>[] adj;

    public EdgeWeightedDigraph(int V) {
        this.V = V;
        this.E = 0;
        adj = (LinkedList<DirectedEdge>[]) new LinkedList[V];
        for (int v = 0; v < V; ++v) {
            adj[v] = new LinkedList<DirectedEdge>();
        }
    }

    public int V() {
        return V;
    }

    public int E() {
        return E;
    }

    public void addEdge(DirectedEdge e) {
        int v = e.from();
        adj[v].add(e);
        ++E;
    }

    public Iterable<DirectedEdge> adj(int v) {
        return adj[v];
    }
}

class LazyDijkstraSP {
    private boolean[] marked;
    private double[] distTo;
    private DirectedEdge[] edgeTo;
    private PriorityQueue<DirectedEdge> pq;

    private class ByDistanceFromSource implements Comparator<DirectedEdge> {
        public int compare(DirectedEdge e, DirectedEdge f) {
            // 核心代码
            double dist1 = Math.max(distTo[e.from()], e.weight());
            double dist2 = Math.max(distTo[f.from()], f.weight());
            return Double.compare(dist1, dist2);
        }
    }

    public LazyDijkstraSP(EdgeWeightedDigraph G, int s) {
        int V = G.V();
        marked = new boolean[V];
        distTo = new double[V];
        edgeTo = new DirectedEdge[V];
        pq = new PriorityQueue<DirectedEdge>(new ByDistanceFromSource());
        for (int v = 0; v < V; ++v) {
            distTo[v] = Double.POSITIVE_INFINITY;
        }
        distTo[s] = 0.0;
        relax(G, s);
        while (!pq.isEmpty()) {
            DirectedEdge e = pq.poll();
            int w = e.to();
            if (!marked[w]) {
                relax(G, w);
            }
        }
    }

    private void relax(EdgeWeightedDigraph G, int v) {
        marked[v] = true;
        for (DirectedEdge e : G.adj(v)) {
            int w = e.to();
            // 核心代码
            if (distTo[w] > Math.max(distTo[v], e.weight())) {
                distTo[w] = Math.max(distTo[v], e.weight());
                edgeTo[w] = e;
                pq.offer(e);
            }
        }
    }

    public double distTo(int v) {
        return distTo[v];
    }
}

class Solution {
    public int minimumEffortPath(int[][] heights) {
        int m = heights.length;
        int n = heights[0].length;
        EdgeWeightedDigraph graph = new EdgeWeightedDigraph(m * n);
        int[][] directions = new int[][]{{0, 1}, {0, -1}, {1, 0}, {-1, 0}};
        for (int i = 0; i < m; ++i) {
            for (int j = 0; j < n; ++j) {
                for (int[] d : directions) {
                    int x = i + d[0];
                    int y = j + d[1];
                    if (x >= 0 && x <= m - 1 && y >= 0 && y <= n - 1) {
                        int v = i * n + j;
                        int w = x * n + y;
                        double weight = Math.abs(heights[i][j] - heights[x][y]);
                        graph.addEdge(new DirectedEdge(v, w, weight));
                    }
                }
            }
        }
        LazyDijkstraSP spt = new LazyDijkstraSP(graph, 0);
        return (int) spt.distTo((m - 1) * n + n - 1);
    }
}
// https://leetcode.cn/submissions/detail/371889869/
```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```java
class Solution {
    private static final int LAND = 1;
    private static final int WATER = 0;

    public int countSubIslands(int[][] grid1, int[][] grid2) {
        int m = grid2.length, n = grid2[0].length;
        for (int i = 0; i < m; ++i) {
            for (int j = 0; j < n; ++j) {
                // 淹没『非子岛屿』
                if (grid2[i][j] == LAND && grid1[i][j] == WATER) {
                    floodFill(grid2, i, j);
                }
            }
        }
        int count = 0;
        for (int i = 0; i < m; ++i) {
            for (int j = 0; j < n; ++j) {
                if (grid2[i][j] == LAND) {
                    floodFill(grid2, i, j);
                    ++count;
                }
            }
        }
        return count;
    }

    private void floodFill(int[][] grid, int i, int j) {
        if (i < 0 || i >= grid.length || j < 0 || j >= grid[0].length || grid[i][j] == WATER) {
            return;
        }
        grid[i][j] = WATER;
        floodFill(grid, i, j + 1);
        floodFill(grid, i, j - 1);
        floodFill(grid, i + 1, j);
        floodFill(grid, i - 1, j);
    }
}
// https://leetcode.cn/submissions/detail/362777848/
```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode-cn.com/problems/kth-node-from-end-of-list-lcci/>

```java
class Solution {
    public int kthToLast(ListNode head, int k) {
        ListNode slow = head, fast = head;
        for (int i = 0; i < k; ++i) {
            fast = fast.next;
        }
        while (fast != null) {
            slow = slow.next;
            fast = fast.next;
        }
        return slow.val;
    }
}
// https://leetcode.cn/submissions/detail/418807180/
```
