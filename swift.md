<!-- omit in toc -->
# LeetCode 题解：Swift

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

```swift
class Solution {
    func twoSum(_ nums: [Int], _ target: Int) -> [Int] {
        var valueToIndex: [Int: Int] = [:];
        for (index, value) in nums.enumerated() {
            let need = target - value;
            if (valueToIndex[need] != nil) {
                return [valueToIndex[need]!, index];
            }
            valueToIndex[value] = index;
        }
        return [];
    }
}
// https://leetcode.cn/submissions/detail/386774665/
```

## 2. 两数相加

<https://leetcode-cn.com/problems/add-two-numbers/>

```swift
class Solution {
    func addTwoNumbers(_ l1: ListNode?, _ l2: ListNode?) -> ListNode? {
        var ptr1 = l1, ptr2 = l2;
        let dummyHead = ListNode();
        var ptr = dummyHead;
        var carry = 0;
        while (ptr1 != nil || ptr2 != nil || carry > 0) {
            var sum = carry;
            if (ptr1 != nil) {
                sum += ptr1!.val;
                ptr1 = ptr1!.next;
            }
            if (ptr2 != nil) {
                sum += ptr2!.val;
                ptr2 = ptr2!.next;
            }
            ptr.next = ListNode(sum % 10);
            ptr = ptr.next!;
            carry = sum / 10;
        }
        return dummyHead.next;
    }
}
// https://leetcode.cn/submissions/detail/384880797/
```

## 3. 无重复字符的最长子串

<https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/>

```swift
class Solution {
    func lengthOfLongestSubstring(_ s: String) -> Int {
        let chs = [Character](s);
        var ans = 0;
        var window = Set<Character>();
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        var left = 0, right = 0;
        while (right < chs.count) {
            let add = chs[right];
            if (!window.contains(add)) {
                window.insert(add);
                right += 1;
            } else {
                while (left < right) {
                    let del = chs[left];
                    left += 1;
                    window.remove(del);
                    if (del == add) {
                        break;
                    }
                }
            }
            ans = max(ans, right - left);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/392738243/
```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```swift
class Solution {
    func findMedianSortedArrays(_ nums1: [Int], _ nums2: [Int]) -> Double {
        let total = nums1.count + nums2.count;
        let half = total / 2;
        if (total % 2 == 0) {
            let k1 = getKthElement(nums1, nums2, half);
            let k2 = getKthElement(nums1, nums2, half + 1);
            return Double(k1 + k2) / 2.0;
        }
        return Double(getKthElement(nums1, nums2, half + 1));
    }

    // 寻找两个正序数组 nums1 和 nums2 从小到大排列的第 k 个数
    private func getKthElement(_ nums1: [Int], _ nums2: [Int], _ k: Int) -> Int {
        let n1 = nums1.count, n2 = nums2.count;
        var start1 = 0, start2 = 0, k = k;
        while (true) {
            if (start1 == n1) {
                return nums2[start2 + k - 1];
            }
            if (start2 == n2) {
                return nums1[start1 + k - 1];
            }
            if (k == 1) {
                return min(nums1[start1], nums2[start2]);
            }
            let half = k / 2;
            let i = min(n1 - 1, start1 + half - 1);
            let j = min(n2 - 1, start2 + half - 1);
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
// https://leetcode.cn/submissions/detail/393662965/
```

```swift
class Solution {
    func findMedianSortedArrays(_ nums1: [Int], _ nums2: [Int]) -> Double {
        let total = nums1.count + nums2.count;
        let half = total / 2;
        if (total % 2 == 0) {
            let k1 = getKthElement(nums1, 0, nums2, 0, half);
            let k2 = getKthElement(nums1, 0, nums2, 0, half + 1);
            return Double(k1 + k2) / 2.0;
        }
        return Double(getKthElement(nums1, 0, nums2, 0, half + 1));
    }

    // 寻找两个正序数组 nums1[start1..end1] 和 nums2[start2..end2] 从小到大排列的第 k 个数
    private func getKthElement(_ nums1: [Int], _ start1: Int, _ nums2: [Int], _ start2: Int, _ k: Int) -> Int {
        let n1 = nums1.count, n2 = nums2.count;
        if (start1 == n1) {
            return nums2[start2 + k - 1];
        }
        if (start2 == n2) {
            return nums1[start1 + k - 1];
        }
        if (k == 1) {
            return min(nums1[start1], nums2[start2]);
        }
        let half = k / 2;
        let i = min(n1 - 1, start1 + half - 1);
        let j = min(n2 - 1, start2 + half - 1);
        if (nums1[i] < nums2[j]) {
            // 排除 nums1[start1..i] 共 i-start1+1 个元素
            return getKthElement(nums1, i + 1, nums2, start2, k - (i - start1 + 1));
        } else {
            // 排除 nums2[start2..j] 共 j-start2+1 个元素
            return getKthElement(nums1, start1, nums2, j + 1, k - (j - start2 + 1));
        }
    }
}
// https://leetcode.cn/submissions/detail/384860307/
```

## 5. 最长回文子串

<https://leetcode.cn/problems/longest-palindromic-substring/>

```swift
class Solution {
    func longestPalindrome(_ s: String) -> String {
        let t = [Character](s);
        var ans = "";
        for i in 0...t.count - 1 {
            let s1 = longestPalindrome(t, i, i);
            if (s1.count > ans.count) {
                ans = s1;
            }
            let s2 = longestPalindrome(t, i, i + 1);
            if (s2.count > ans.count) {
                ans = s2;
            }
        }
        return ans;
    }

    // 返回字符串 s 中以 s[i] 和 s[j] 为中心的最长回文子串
    private func longestPalindrome(_ s: [Character], _ i: Int, _ j: Int) -> String {
        var i = i, j = j;
        while (i >= 0 && j < s.count && s[i] == s[j]) {
            i -= 1;
            j += 1;
        }
        return i + 1 > j - 1 ? "" : String(s[i + 1...j - 1]);
    }
}
// https://leetcode.cn/submissions/detail/394199939/
```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```swift
class Solution {
    private static let INT_MIN = -(1 << 31);
    private static let INT_MAX = (1 << 31) - 1;

    func reverse(_ x: Int) -> Int {
        if (x == 0 || x == Solution.INT_MIN) {
            return 0;
        }
        let sign = (x > 0 ? 1 : -1);
        var val = 0;
        var y = abs(x);
        while (y > 0) {
            if (val > Solution.INT_MAX / 10) {
                return 0;
            }
            val = val * 10 + y % 10;
            y /= 10;
        }
        return val * sign;
    }
}
// https://leetcode.cn/submissions/detail/395337882/
```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```swift
class Solution {
    func maxArea(_ height: [Int]) -> Int {
        var ans = 0;
        var i = 0, j = height.count - 1;
        while (i < j) {
            let area = (j - i) * min(height[i], height[j]);
            ans = max(ans, area);
            if (height[i] < height[j]) {
                i += 1;
            } else {
                j -= 1;
            }
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/395984988/
```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```swift
class Solution {
    func longestCommonPrefix(_ strs: [String]) -> String {
        longestCommonPrefix(strs, 0, strs.count - 1);
    }

    private func longestCommonPrefix(_ strs: [String], _ lo: Int, _ hi: Int) -> String {
        if (lo == hi) {
            return strs[lo];
        }
        let mid = lo + (hi - lo) / 2;
        let left = longestCommonPrefix(strs, lo, mid);
        let right = longestCommonPrefix(strs, mid + 1, hi);
        return longestCommonPrefix(left, right);
    }

    private func longestCommonPrefix(_ s1: String, _ s2: String) -> String {
        let c1 = [Character](s1), c2 = [Character](s2);
        let n = min(c1.count, c2.count);
        var i = 0;
        while (i < n && c1[i] == c2[i]) {
            i += 1;
        }
        return i < 1 ? "" : String(c1[0...i - 1]);
    }
}
// https://leetcode.cn/submissions/detail/398715539/
```

## 15. 三数之和

<https://leetcode-cn.com/problems/3sum/>

```swift
class Solution {
    func threeSum(_ nums: [Int]) -> [[Int]] {
        let copy = nums.sorted();
        return kSum(3, copy, 0, copy.count - 1, 0);
    }

    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
    private func kSum(_ k: Int, _ nums: [Int], _ lo: Int, _ hi: Int, _ target: Int) -> [[Int]] {
        if (hi - lo + 1 < k) {
            return [];
        }
        if (k == 2) {
            return twoSum(nums, lo, hi, target);
        }
        var res: [[Int]] = [];
        var i = lo;
        while (i <= hi) {
            let curNum = nums[i];
            let sp = kSum(k - 1, nums, i + 1, hi, target - curNum);
            for x in sp {
                var t = x;
                t.append(curNum);
                res.append(t);
            }
            while (i <= hi && nums[i] == curNum) {
                i += 1;
            }
        }
        return res;
    }

    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的二元组
    private func twoSum(_ nums: [Int], _ lo: Int, _ hi: Int, _ target: Int) -> [[Int]] {
        var res: [[Int]] = [];
        var i = lo, j = hi;
        while (i < j) {
            let first = nums[i], second = nums[j];
            let sum = first + second;
            if (sum < target) {
                while (i < j && nums[i] == first) {
                    i += 1;
                }
            } else if (sum > target) {
                while (i < j && nums[j] == second) {
                    j -= 1;
                }
            } else {
                res.append([first, second]);
                while (i < j && nums[i] == first) {
                    i += 1;
                }
                while (i < j && nums[j] == second) {
                    j -= 1;
                }
            }
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/386772439/
```

## 18. 四数之和

<https://leetcode.cn/problems/4sum/>

```swift
class Solution {
    func fourSum(_ nums: [Int], _ target: Int) -> [[Int]] {
        var copy = nums.sorted();
        return kSum(4, copy, 0, copy.count - 1, target);
    }

    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
    private func kSum(_ k: Int, _ nums: [Int], _ lo: Int, _ hi: Int, _ target: Int) -> [[Int]] {
        if (hi - lo + 1 < k) {
            return [];
        }
        if (k == 2) {
            return twoSum(nums, lo, hi, target);
        }
        var res: [[Int]] = [];
        var i = lo;
        while (i <= hi) {
            let curNum = nums[i];
            var sp = kSum(k - 1, nums, i + 1, hi, target - curNum);
            for x in sp {
                var t = x;
                t.append(curNum);
                res.append(t);
            }
            while (i <= hi && nums[i] == curNum) {
                i += 1;
            }
        }
        return res;
    }

    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的二元组
    private func twoSum(_ nums: [Int], _ lo: Int, _ hi: Int, _ target: Int) -> [[Int]] {
        var res: [[Int]] = [];
        var i = lo, j = hi;
        while (i < j) {
            let first = nums[i], second = nums[j];
            let sum = first + second;
            if (sum < target) {
                while (i < j && nums[i] == first) {
                    i += 1;
                }
            } else if (sum > target) {
                while (i < j && nums[j] == second) {
                    j -= 1;
                }
            } else {
                res.append([first, second]);
                while (i < j && nums[i] == first) {
                    i += 1;
                }
                while (i < j && nums[j] == second) {
                    j -= 1;
                }
            }
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/386773075/
```

## 19. 删除链表的倒数第 N 个结点

<https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/>

```swift
class Solution {
    func removeNthFromEnd(_ head: ListNode?, _ n: Int) -> ListNode? {
        let dummyHead = ListNode(-1, head);
        var slow = dummyHead, fast = dummyHead;
        for _ in 1...n {
            fast = fast.next!;
        }
        while (fast.next != nil) {
            slow = slow.next!;
            fast = fast.next!;
        }
        slow.next = slow.next!.next;
        return dummyHead.next;
    }
}
// https://leetcode.cn/submissions/detail/384872360/
```

## 20. 有效的括号

<https://leetcode-cn.com/problems/valid-parentheses/>

```swift
class Solution {
    func isValid(_ s: String) -> Bool {
        if (s.count % 2 == 1) {
            return false;
        }
        var stack: [Character] = [];
        for ch in s {
            switch (ch) {
            case "(":
                stack.append(")");
                break;
            case "[":
                stack.append("]");
                break;
            case "{":
                stack.append("}");
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
// https://leetcode.cn/submissions/detail/399500818/
```

## 21. 合并两个有序链表

<https://leetcode-cn.com/problems/merge-two-sorted-lists/>

```swift
class Solution {
    func mergeTwoLists(_ list1: ListNode?, _ list2: ListNode?) -> ListNode? {
        var ptr1 = list1, ptr2 = list2;
        let dummyHead = ListNode();
        var ptr = dummyHead;
        while (ptr1 != nil && ptr2 != nil) {
            if (ptr1!.val < ptr2!.val) {
                ptr.next = ptr1;
                ptr1 = ptr1!.next;
            } else {
                ptr.next = ptr2;
                ptr2 = ptr2!.next;
            }
            ptr = ptr.next!;
        }
        ptr.next = (ptr1 ?? ptr2);
        return dummyHead.next;
    }
}
// https://leetcode.cn/submissions/detail/384919316/
```

## 22. 括号生成

<https://leetcode.cn/problems/generate-parentheses/>

```swift
class Solution {
    private var left = 0; // 已使用的『左括号』数量
    private var right = 0; // 已使用的『右括号』数量
    private var path: [String] = []; // 取 '(', ')' 为元素
    private var ans: [String] = [];

    func generateParenthesis(_ n: Int) -> [String] {
        backtrack(n);
        return ans;
    }

    private func backtrack(_ n: Int) {
        // 对于一个「合法」的括号字符串组合 p，必然对于任何 0 <= i < len(p) 都有：
        // 子串 p[0..i] 中左括号的数量都大于或等于右括号的数量
        if (left < right || left > n) {
            return;
        }
        // 一个「合法」括号组合的左括号数量一定等于右括号数量
        if (left == n && right == n) {
            ans.append(path.joined());
            return;
        }
        // edge = 取 '(', ')' 为值
        // 使用『左括号』
        path.append("(");
        left += 1;
        backtrack(n);
        path.removeLast();
        left -= 1;
        // 使用『右括号』
        path.append(")");
        right += 1;
        backtrack(n);
        path.removeLast();
        right -= 1;
    }
}
// https://leetcode.cn/submissions/detail/387240903/
```

## 23. 合并 K 个升序链表

<https://leetcode-cn.com/problems/merge-k-sorted-lists/>

```swift
class Solution {
    func mergeKLists(_ lists: [ListNode?]) -> ListNode? {
        mergeKLists(lists, 0, lists.count - 1);
    }

    private func mergeKLists(_ lists: [ListNode?], _ lo: Int, _ hi: Int) -> ListNode? {
        if (lo > hi) {
            return nil;
        }
        if (lo == hi) {
            return lists[lo];
        }
        let mid = lo + (hi - lo) / 2;
        let left = mergeKLists(lists, lo, mid);
        let right = mergeKLists(lists, mid + 1, hi);
        return mergeTwoLists(left, right);
    }

    private func mergeTwoLists(_ list1: ListNode?, _ list2: ListNode?) -> ListNode? {
        var ptr1 = list1, ptr2 = list2;
        let dummyHead = ListNode();
        var ptr = dummyHead;
        while (ptr1 != nil && ptr2 != nil) {
            if (ptr1!.val < ptr2!.val) {
                ptr.next = ptr1;
                ptr1 = ptr1!.next;
            } else {
                ptr.next = ptr2;
                ptr2 = ptr2!.next;
            }
            ptr = ptr.next!;
        }
        ptr.next = (ptr1 ?? ptr2);
        return dummyHead.next;
    }
}
// https://leetcode.cn/submissions/detail/384920056/
```

## 24. 两两交换链表中的节点

<https://leetcode-cn.com/problems/swap-nodes-in-pairs/>

```swift
class Solution {
    func swapPairs(_ head: ListNode?) -> ListNode? {
        if (head == nil || head!.next == nil) {
            return head;
        }
        let x = head;
        let y = head!.next;
        let z = head!.next!.next;
        y!.next = x;
        x!.next = swapPairs(z);
        return y;
    }
}
// https://leetcode.cn/submissions/detail/384876511/
```

## 25. K 个一组翻转链表

<https://leetcode.cn/problems/reverse-nodes-in-k-group/>

```swift
class Solution {
    func reverseKGroup(_ head: ListNode?, _ k: Int) -> ListNode? {
        if (head == nil || head!.next == nil || k == 1) {
            return head;
        }
        var ptr = head;
        for _ in 1...k - 1 {
            ptr = ptr!.next;
            if (ptr == nil) {
                return head;
            }
        }
        let nextGroup = ptr!.next;
        ptr!.next = nil;
        let reverseHead = reverseList(head);
        head!.next = reverseKGroup(nextGroup, k);
        return reverseHead;
    }

    private func reverseList(_ head: ListNode?) -> ListNode? {
        var reverseHead: ListNode?;
        var ptr = head;
        while (ptr != nil) {
            let x = ptr!.next;
            ptr!.next = reverseHead;
            reverseHead = ptr;
            ptr = x;
        }
        return reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/400343617/
```

## 26. 删除有序数组中的重复项

<https://leetcode.cn/problems/remove-duplicates-from-sorted-array/>

```swift
class Solution {
    func removeDuplicates(_ nums: inout [Int]) -> Int {
        // [0..i-1] 不重复元素区间
        // [i..j-1] 重复元素区间
        // [j..n-1] 扫描区间
        var i = 0, j = 0;
        let n = nums.count;
        while (j < n) {
            while (j + 1 < n && nums[j] == nums[j + 1]) {
                j += 1;
            }
            nums.swapAt(i, j);
            i += 1;
            j += 1;
        }
        return i;
    }
}
// https://leetcode.cn/submissions/detail/384823368/
```

## 27. 移除元素

<https://leetcode.cn/problems/remove-element/>

```swift
class Solution {
    func removeElement(_ nums: inout [Int], _ val: Int) -> Int {
        // nums[0..i-1]   != val
        // nums[i..j]     Scanning
        // nums[j+1..n-1] == val
        var i = 0, j = nums.count - 1;
        while (i <= j) {
            while (i <= j && nums[i] != val) {
                i += 1;
            }
            while (i <= j && nums[j] == val) {
                j -= 1;
            }
            if (i <= j) {
                nums.swapAt(i, j);
            }
        }
        return i;
    }
}
// https://leetcode.cn/submissions/detail/384787907/
```

## 28. 实现 strStr()

<https://leetcode.cn/problems/implement-strstr/>

```swift
//
// Created by HUANGYUHUI on 2023/2/4.
//

import Foundation

public class ListNode {
    public var val: Int
    public var next: ListNode?

    public init() {
        self.val = 0; self.next = nil;
    }

    public init(_ val: Int) {
        self.val = val; self.next = nil;
    }

    public init(_ val: Int, _ next: ListNode?) {
        self.val = val; self.next = next;
    }
}

struct KMP {
    private let m: Int;
    private var dfa: [[Int]];

    init(_ pat: String) {
        let patArray = [Character](pat);
        m = patArray.count;
        dfa = Array(repeating: Array(repeating: 0, count: m), count: 256);
        dfa[Int(patArray[0].asciiValue!)][0] = 1;
        var x = 0, j = 1;
        while j < m {
            for c in 0...255 {
                dfa[c][j] = dfa[c][x];
            }
            dfa[Int(patArray[j].asciiValue!)][j] = j + 1;
            x = dfa[Int(patArray[j].asciiValue!)][x];
            j += 1;
        }
    }

    public func search(_ txt: String) -> Int {
        let txtArray = [Character](txt);
        let n = txtArray.count;
        var i = 0, j = 0;
        while i < n && j < m {
            j = dfa[Int(txtArray[i].asciiValue!)][j];
            i += 1;
        }
        if j == m {
            return i - m;
        }
        return -1;
    }
}

class Solution {
    func strStr(_ haystack: String, _ needle: String) -> Int {
        let kmp = KMP(needle);
        return kmp.search(haystack);
    }
}
// https://leetcode.cn/submissions/detail/429013885/
```

```swift
struct BoyerMoore {
    private let patArray: [Character];
    private var right: [Int];

    init(_ pat: String) {
        patArray = [Character](pat);
        right = Array(repeating: -1, count: 256);
        for j in 0...patArray.count - 1 {
            right[Int(patArray[j].asciiValue!)] = j;
        }
    }

    public func search(_ txt: String) -> Int {
        let txtArray = [Character](txt);
        let n = txtArray.count;
        let m = patArray.count;
        var i = 0;
        while (i <= n - m) {
            var skip = 0;
            var j = m - 1;
            while (j >= 0) {
                if (patArray[j] != txtArray[i + j]) {
                    skip = max(1, j - right[Int(txtArray[i + j].asciiValue!)]);
                    break;
                }
                j -= 1;
            }
            if (skip == 0) {
                return i;
            }
            i += skip;
        }
        return -1;
    }
}

class Solution {
    func strStr(_ haystack: String, _ needle: String) -> Int {
        let bm = BoyerMoore(needle);
        return bm.search(haystack);
    }
}
// https://leetcode.cn/submissions/detail/386216501/
```

## 33. 搜索旋转排序数组

<https://leetcode.cn/problems/search-in-rotated-sorted-array/>

```swift
class Solution {
    func search(_ nums: [Int], _ target: Int) -> Int {
        var lo = 0, hi = nums.count - 1;
        while (lo <= hi) {
            let mid = lo + (hi - lo) / 2;
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
// https://leetcode.cn/submissions/detail/384828451/
```

## 34. 在排序数组中查找元素的第一个和最后一个位置

<https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/>

```swift
class Solution {
    func searchRange(_ nums: [Int], _ target: Int) -> [Int] {
        [binarySearch(nums, target, true), binarySearch(nums, target, false)];
    }

    private func binarySearch(_ nums: [Int], _ target: Int, _ lower: Bool) -> Int {
        var res = -1;
        var lo = 0, hi = nums.count - 1;
        while (lo <= hi) {
            let mid = lo + (hi - lo) / 2;
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
// https://leetcode.cn/submissions/detail/384831206/
```

## 37. 解数独

<https://leetcode.cn/problems/sudoku-solver/>

```swift
class Solution {
    func solveSudoku(_ board: inout [[Character]]) {
        backtrack(&board, 0, -1);
    }

    // 遍历『决策森林』
    // tree  = row
    // level = (row, col)
    @discardableResult
    private func backtrack(_ board: inout [[Character]], _ row: Int, _ col: Int) -> Bool {
        var res = false;
        let n = board.count;
        if (row == n) {
            res = true;
        } else if (col == n - 1) {
            // 遍历下一棵『决策树』
            res = backtrack(&board, row + 1, -1);
        } else if (board[row][col + 1] != ".") {
            res = backtrack(&board, row, col + 1);
        } else {
            // edge = ['1'..'9']
            for ch in "123456789" {
                if (isValid(board, row, col + 1, ch)) {
                    board[row][col + 1] = ch;
                    res = backtrack(&board, row, col + 1);
                    if (res) {
                        break;
                    }
                    board[row][col + 1] = ".";
                }
            }
        }
        return res;
    }

    // board[row][col] 填入数字 ch 是否有效
    private func isValid(_ board: [[Character]], _ row: Int, _ col: Int, _ ch: Character) -> Bool {
        let n = board.count;
        for i in 0...n - 1 {
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
// https://leetcode.cn/submissions/detail/385973006/
```

## 39. 组合总和

<https://leetcode.cn/problems/combination-sum/>

```swift
class Solution {
    private var pathSum = 0;
    private var path: [Int] = []; // 取 nums[edge] 为元素
    private var ans: [[Int]] = [];

    func combinationSum(_ nums: [Int], _ target: Int) -> [[Int]] {
        backtrack(nums, target, -1);
        return ans;
    }

    // edge = 取数组 nums 的索引为值
    private func backtrack(_ nums: [Int], _ target: Int, _ edge: Int) {
        if (pathSum == target) {
            ans.append(path);
            return;
        }
        var e = (edge == -1 ? 0 : edge);
        // 避免重复，从 edge 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (e < nums.count) {
            let x = nums[e];
            if (pathSum + x <= target) {
                pathSum += x;
                path.append(x);
                backtrack(nums, target, e);
                pathSum -= x;
                path.removeLast();
            }
            e += 1;
        }
    }
}
// https://leetcode.cn/submissions/detail/387747572/
```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```swift
class Solution {
    private var pathSum = 0;
    private var path: [Int] = []; // 取 nums[edge] 为元素
    private var ans: [[Int]] = [];

    func combinationSum2(_ nums: [Int], _ target: Int) -> [[Int]] {
        backtrack(nums.sorted(), target, -1);
        return ans;
    }

    // edge = 取数组 nums 的索引为值
    private func backtrack(_ nums: [Int], _ target: Int, _ edge: Int) {
        if (pathSum == target) {
            ans.append(path);
            return;
        }
        var prev: Int? = nil;
        var e = edge + 1;
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (e < nums.count) {
            let x = nums[e];
            if (x != prev && pathSum + x <= target) {
                prev = x;
                pathSum += x;
                path.append(x);
                backtrack(nums, target, e);
                pathSum -= x;
                path.removeLast();
            }
            e += 1;
        }
    }
}
// https://leetcode.cn/submissions/detail/387748090/
```

## 42. 接雨水

<https://leetcode.cn/problems/trapping-rain-water/>

```swift
class Solution {
    func trap(_ height: [Int]) -> Int {
        let n = height.count;
        if (n == 1) {
            return 0;
        }
        // leftMax[i] = max(height[0..i])
        var leftMax = height;
        for i in 1...n - 1 {
            leftMax[i] = max(height[i], leftMax[i - 1]);
        }
        // rightMax[i] = max(height[i..n-1])
        var rightMax = height;
        for i in stride(from: n - 2, through: 0, by: -1) {
            rightMax[i] = max(height[i], rightMax[i + 1]);
        }
        var sum = 0;
        for i in 0...n - 1 {
            sum += min(leftMax[i], rightMax[i]) - height[i];
        }
        return sum;
    }
}
// https://leetcode.cn/submissions/detail/386582598/
```

## 46. 全排列

<https://leetcode.cn/problems/permutations/>

```swift
class Solution {
    private var marked: [Bool] = [];
    private var path: [Int] = []; // 取 nums[edge] 为元素
    private var ans: [[Int]] = [];

    func permute(_ nums: [Int]) -> [[Int]] {
        marked = Array(repeating: false, count: nums.count);
        backtrack(nums);
        return ans;
    }

    private func backtrack(_ nums: [Int]) {
        let n = nums.count;
        if (path.count == n) {
            ans.append(path);
            return;
        }
        // edge = 取数组 nums 的索引为值
        for edge in 0...n - 1 {
            if (!marked[edge]) {
                path.append(nums[edge]);
                marked[edge] = true;
                backtrack(nums);
                path.removeLast();
                marked[edge] = false;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/387748663/
```

## 47. 全排列 II

<https://leetcode.cn/problems/permutations-ii/>

```swift
class Solution {
    private var marked: [Bool] = [];
    private var path: [Int] = []; // 取 nums[edge] 为元素
    private var ans: [[Int]] = [];

    func permuteUnique(_ nums: [Int]) -> [[Int]] {
        marked = Array(repeating: false, count: nums.count);
        backtrack(nums.sorted());
        return ans;
    }

    private func backtrack(_ nums: [Int]) {
        let n = nums.count;
        if path.count == n {
            ans.append(path);
            return;
        }
        var prev: Int? = nil;
        // edge = 取数组 nums 的索引为值
        for edge in 0...n - 1 {
            let x = nums[edge];
            if !marked[edge] && x != prev {
                prev = x;
                path.append(x);
                marked[edge] = true;
                backtrack(nums);
                path.removeLast();
                marked[edge] = false;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/428455251/
```

## 51. N 皇后

<https://leetcode.cn/problems/n-queens/>

```swift
class Solution {
    private var ans: [[String]] = [];

    func solveNQueens(_ n: Int) -> [[String]] {
        var board: [[Character]] = Array(repeating: Array(repeating: ".", count: n), count: n);
        backtrack(&board, -1);
        return ans;
    }

    // level = row
    private func backtrack(_ board: inout [[Character]], _ row: Int) {
        let n = board.count;
        if (row == n - 1) {
            var strs: [String] = [];
            for chs in board {
                strs.append(String(chs));
            }
            ans.append(strs);
            return;
        }
        // edge = col
        for col in 0...n - 1 {
            if (isValid(board, row + 1, col)) {
                board[row + 1][col] = "Q";
                backtrack(&board, row + 1);
                board[row + 1][col] = ".";
            }
        }
    }

    // board[row][col] 放置 Q 是否有效
    private func isValid(_ board: [[Character]], _ row: Int, _ col: Int) -> Bool {
        let n = board.count;
        // 同一列
        var r = row - 1;
        while (r >= 0) {
            if (board[r][col] == "Q") {
                return false;
            }
            r -= 1;
        }
        // 右斜线
        r = row - 1;
        var c = col - 1;
        while (r >= 0 && c >= 0) {
            if (board[r][c] == "Q") {
                return false;
            }
            r -= 1;
            c -= 1;
        }
        // 左斜线
        r = row - 1;
        c = col + 1;
        while (r >= 0 && c < n) {
            if (board[r][c] == "Q") {
                return false;
            }
            r -= 1;
            c += 1;
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/387753261/
```

## 52. N 皇后 II

<https://leetcode.cn/problems/n-queens-ii/>

```swift
class Solution {
    private var ans = 0;

    func totalNQueens(_ n: Int) -> Int {
        var board: [[Character]] = Array(repeating: Array(repeating: ".", count: n), count: n);
        backtrack(&board, -1);
        return ans;
    }

    // level = row
    private func backtrack(_ board: inout [[Character]], _ row: Int) {
        let n = board.count;
        if (row == n - 1) {
            ans += 1;
            return;
        }
        // edge = col
        for col in 0...n - 1 {
            if (isValid(board, row + 1, col)) {
                board[row + 1][col] = "Q";
                backtrack(&board, row + 1);
                board[row + 1][col] = ".";
            }
        }
    }

    // board[row][col] 放置 Q 是否有效
    private func isValid(_ board: [[Character]], _ row: Int, _ col: Int) -> Bool {
        let n = board.count;
        // 同一列
        var r = row - 1;
        while (r >= 0) {
            if (board[r][col] == "Q") {
                return false;
            }
            r -= 1;
        }
        // 右斜线
        r = row - 1;
        var c = col - 1;
        while (r >= 0 && c >= 0) {
            if (board[r][c] == "Q") {
                return false;
            }
            r -= 1;
            c -= 1;
        }
        // 左斜线
        r = row - 1;
        c = col + 1;
        while (r >= 0 && c < n) {
            if (board[r][c] == "Q") {
                return false;
            }
            r -= 1;
            c += 1;
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/387753115/
```

## 53. 最大子数组和

<https://leetcode.cn/problems/maximum-subarray/>

```swift
class Solution {
    func maxSubArray(_ nums: [Int]) -> Int {
        let n = nums.count;
        if (n == 1) {
            return nums[0];
        }
        // dp[i] = max({sum(subarray) | subarray 是以 nums[i] 结尾的子数组})
        var dp = nums;
        var ans = dp[0];
        for i in 1...n - 1 {
            dp[i] = max(nums[i], dp[i - 1] + nums[i]);
            ans = max(ans, dp[i]);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/387508297/
```

## 56. 合并区间

<https://leetcode.cn/problems/merge-intervals/>

```swift
class Solution {
    func merge(_ intervals: [[Int]]) -> [[Int]] {
        let sortedIntervals = intervals.sorted { a, b in
            a[0] == b[0] ? a[1] > b[1] : a[0] < b[0]
        };
        var ans: [[Int]] = [];
        var mStart = sortedIntervals[0][0];
        var mEnd = sortedIntervals[0][1];
        for interval in sortedIntervals {
            let start = interval[0];
            let end = interval[1];
            if (start <= mEnd) {
                // 重叠
                mEnd = max(mEnd, end);
            } else {
                // 不重叠
                ans.append([mStart, mEnd]);
                mStart = start;
                mEnd = end;
            }
        }
        ans.append([mStart, mEnd]);
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/385540334/
```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```swift
class Solution {
    private var memo: [[Int?]] = [];

    func minPathSum(_ grid: [[Int]]) -> Int {
        let m = grid.count;
        let n = grid[0].count;
        memo = Array(repeating: Array(repeating: nil, count: n), count: m);
        return minPathSum(grid, m - 1, n - 1);
    }

    // 从 grid[0][0] 到 grid[row][col] 的最小路径和
    private func minPathSum(_ grid: [[Int]], _ row: Int, _ col: Int) -> Int {
        if (row < 0 || col < 0) {
            return Int.max;
        }
        if (row == 0 && col == 0) {
            return grid[row][col];
        }
        if (memo[row][col] == nil) {
            let sp1 = minPathSum(grid, row - 1, col); // 上
            let sp2 = minPathSum(grid, row, col - 1); // 左
            memo[row][col] = min(sp1, sp2) + grid[row][col];
        }
        return memo[row][col]!;
    }
}
// https://leetcode.cn/submissions/detail/387521034/
```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```swift
class Solution {
    func mySqrt(_ x: Int) -> Int {
        if (x == 0) {
            return 0;
        }
        var lo = 1, hi = x;
        while (lo <= hi) {
            let mid = lo + (hi - lo) / 2;
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
// https://leetcode.cn/submissions/detail/384832196/
```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```swift
class Solution {
    func climbStairs(_ n: Int) -> Int {
        if (n == 1) {
            return 1;
        }
        if (n == 2) {
            return 2;
        }
        // dp[i] = 楼梯有 i 阶时，有几种不同的方法
        var dp = Array(repeating: 0, count: n + 1);
        dp[1] = 1;
        dp[2] = 2;
        for i in 3...n {
            dp[i] = dp[i - 1] + dp[i - 2];
        }
        return dp[n];
    }
}
// https://leetcode.cn/submissions/detail/384860968/
```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```swift
class Solution {
    private var memo: [[Int?]] = [];

    func minDistance(_ word1: String, _ word2: String) -> Int {
        let n1 = word1.count, n2 = word2.count;
        memo = Array(repeating: Array(repeating: nil, count: n2), count: n1);
        return minDistance([Character](word1), n1 - 1, [Character](word2), n2 - 1);
    }

    // 返回子串 s1[0..i] s2[0..j] 的最小编辑距离
    private func minDistance(_ s1: [Character], _ i: Int, _ s2: [Character], _ j: Int) -> Int {
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
        if (memo[i][j] == nil) {
            if (s1[i] == s2[j]) {
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                memo[i][j] = minDistance(s1, i - 1, s2, j - 1);
            } else {
                // 替换 s1[i] 为 s2[j]
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                let sp1 = minDistance(s1, i - 1, s2, j - 1) + 1;
                // 插入 s2[j] 到 s1
                // s1[0..i]
                // s2[0..j-1][j]
                let sp2 = minDistance(s1, i, s2, j - 1) + 1;
                // 删除 s1[i]
                // s1[0..i-1][i]
                // s2[0..j]
                let sp3 = minDistance(s1, i - 1, s2, j) + 1;
                memo[i][j] = min(sp1, sp2, sp3);
            }
        }
        return memo[i][j]!;
    }
}
// https://leetcode.cn/submissions/detail/428200809/
```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```swift
class Solution {
    func sortColors(_ nums: inout [Int]) {
        let v = 1;
        var lt = 0, gt = nums.count - 1;
        var i = 0;
        while (i <= gt) {
            if (nums[i] < v) {
                nums.swapAt(lt, i);
                lt += 1;
                i += 1;
            } else if (nums[i] > v) {
                nums.swapAt(i, gt);
                gt -= 1;
            } else {
                i += 1;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/384851512/
```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```swift
class Solution {
    func minWindow(_ s: String, _ t: String) -> String {
        let schs = [Character](s), tchs = [Character](t);
        var need: [Character: Int] = [:];
        for ch in tchs {
            need[ch] = (need[ch] ?? 0) + 1;
        }
        var window: [Character: Int] = [:];
        var valid = 0;
        var start = 0;
        var len = Int.max;
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        var left = 0;
        var right = 0;
        while (right < schs.count) {
            let add = schs[right];
            right += 1;
            if (need[add] != nil) {
                window[add] = (window[add] ?? 0) + 1;
                if (window[add] == need[add]) {
                    valid += 1;
                }
            }
            if (valid == need.count) {
                while (left < right) {
                    let del = schs[left];
                    if (need[del] != nil && window[del] == need[del]) {
                        break;
                    }
                    if (need[del] != nil) {
                        window[del]! -= 1;
                    }
                    left += 1;
                }
                if (right - left < len) {
                    start = left;
                    len = right - left;
                }
            }
        }
        return len == Int.max ? "" : String(schs[start...start + len - 1]);
    }
}
// https://leetcode.cn/submissions/detail/385506728/
```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```swift
class Solution {
    private var path: [Int] = []; // 取 [1..n] 为元素
    private var ans: [[Int]] = [];

    func combine(_ n: Int, _ k: Int) -> [[Int]] {
        backtrack(n, k, 0);
        return ans;
    }

    // edge = 取 [1..n] 为值
    private func backtrack(_ n: Int, _ k: Int, _ edge: Int) {
        if (path.count == k) {
            ans.append(path);
            return;
        }
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        var e = edge + 1;
        while (e <= n) {
            path.append(e);
            backtrack(n, k, e);
            path.removeLast();
            e += 1;
        }
    }
}
// https://leetcode.cn/submissions/detail/387746835/
```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```swift
class Solution {
    private var path: [Int] = []; // 取 nums[edge] 为元素
    private var ans: [[Int]] = [];

    func subsets(_ nums: [Int]) -> [[Int]] {
        backtrack(nums, -1);
        return ans;
    }

    // edge = 取数组 nums 的索引为值
    private func backtrack(_ nums: [Int], _ edge: Int) {
        ans.append(path);
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        var e = edge + 1;
        while (e < nums.count) {
            path.append(nums[e]);
            backtrack(nums, e);
            path.removeLast();
            e += 1;
        }
    }
}
// https://leetcode.cn/submissions/detail/387745238/
```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```swift
class Solution {
    func search(_ nums: [Int], _ target: Int) -> Bool {
        var lo = 0, hi = nums.count - 1;
        while (lo <= hi) {
            let mid = lo + (hi - lo) / 2;
            if (nums[mid] == target) {
                return true;
            }
            if (nums[lo] == nums[mid] && nums[mid] == nums[hi]) {
                lo += 1;
                hi -= 1;
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
// https://leetcode.cn/submissions/detail/384829399/
```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```swift
class Solution {
    func deleteDuplicates(_ head: ListNode?) -> ListNode? {
        var ptr = head;
        while (ptr != nil && ptr!.next != nil) {
            if (ptr!.val == ptr!.next!.val) {
                ptr!.next = ptr!.next!.next;
            } else {
                ptr = ptr!.next;
            }
        }
        return head;
    }
}
// https://leetcode.cn/submissions/detail/384921135/
```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```swift
class Solution {
    func partition(_ head: ListNode?, _ x: Int) -> ListNode? {
        var ptr = head;
        let lessDummyHead = ListNode();
        var lessPtr = lessDummyHead;
        let greaterDummyHead = ListNode();
        var greaterPtr = greaterDummyHead;
        while (ptr != nil) {
            if (ptr!.val < x) {
                lessPtr.next = ptr;
                lessPtr = lessPtr.next!;
            } else {
                greaterPtr.next = ptr;
                greaterPtr = greaterPtr.next!;
            }
            ptr = ptr!.next;
        }
        greaterPtr.next = nil;
        lessPtr.next = greaterDummyHead.next;
        return lessDummyHead.next;
    }
}
// https://leetcode.cn/submissions/detail/386783676/
```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```swift
class Solution {
    private var path: [Int] = []; // 取 nums[edge] 为元素
    private var ans: [[Int]] = [];

    func subsetsWithDup(_ nums: [Int]) -> [[Int]] {
        backtrack(nums.sorted(), -1);
        return ans;
    }

    // edge = 取数组 nums 的索引为值
    private func backtrack(_ nums: [Int], _ edge: Int) {
        ans.append(path);
        var prev: Int? = nil;
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        var e = edge + 1;
        while (e < nums.count) {
            let x = nums[e];
            if (x != prev) {
                prev = x;
                path.append(x);
                backtrack(nums, e);
                path.removeLast();
            }
            e += 1;
        }
    }
}
// https://leetcode.cn/submissions/detail/387745981/
```

## 92. 反转链表 II

<https://leetcode-cn.com/problems/reverse-linked-list-ii/>

```swift
class Solution {
    func reverseBetween(_ head: ListNode?, _ left: Int, _ right: Int) -> ListNode? {
        if (left == 1) {
            return reverseList(head, right);
        }
        var ptr = head;
        if (left > 2) {
            for _ in 1...left - 2 {
                ptr = ptr!.next;
            }
        }
        ptr!.next = reverseList(ptr!.next, right - left + 1);
        return head;
    }

    // 翻转链表的前 n 个节点，返回翻转后的头节点
    private func reverseList(_ head: ListNode?, _ n: Int) -> ListNode? {
        var reverseHead: ListNode?;
        var ptr = head;
        var count = 0;
        while (ptr != nil && count < n) {
            let x = ptr!.next;
            ptr!.next = reverseHead;
            reverseHead = ptr;
            ptr = x;
            count += 1;
        }
        head!.next = ptr;
        return reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/386777770/
```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```swift
class Solution {
    private var ans: [Int] = [];

    func inorderTraversal(_ root: TreeNode?) -> [Int] {
        dfs(root);
        return ans;
    }

    private func dfs(_ root: TreeNode?) {
        if (root == nil) {
            return;
        }
        dfs(root!.left);
        ans.append(root!.val);
        dfs(root!.right);
    }
}
// https://leetcode.cn/submissions/detail/384924119/
```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```swift
class Solution {
    func generateTrees(_ n: Int) -> [TreeNode?] {
        generateTrees(1, n);
    }

    // 返回所有由 [lo..hi] 组成的节点值互不相同的不同二叉搜索树
    func generateTrees(_ lo: Int, _ hi: Int) -> [TreeNode?] {
        if (lo > hi) {
            return [nil];
        }
        var res: [TreeNode] = [];
        // 根节点为 i
        // 左子树由 [lo..i-1] 组成
        // 右子树由 [i+1..hi] 组成
        for i in lo...hi {
            let leftTrees = generateTrees(lo, i - 1);
            let rightTrees = generateTrees(i + 1, hi);
            for left in leftTrees {
                for right in rightTrees {
                    res.append(TreeNode(i, left, right));
                }
            }
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/384971352/
```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```swift
class Solution {
    private var memo: [Int: Int] = [:];

    // 由 n 个不同数字 x_1 < x_2 < ... < x_n
    // 组成的节点值互不相同的二叉搜索树的种数
    func numTrees(_ n: Int) -> Int {
        if (n == 0 || n == 1) {
            return 1;
        }
        if memo[n] == nil {
            var res = 0;
            // 根节点为 x_i
            // 左子树由 i-1 个数字 x1 < x2 < ... < x_i-1 组成
            // 右子树由 n-i 个数字 x_i+1 < x_i+2 < ... < x_n 组成
            for i in 1...n {
                res += numTrees(i - 1) * numTrees(n - i);
            }
            memo[n] = res;
        }
        return memo[n]!;
    }
}
// https://leetcode.cn/submissions/detail/384969761/
```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```swift
class Solution {
    private var ans = true;

    func isValidBST(_ root: TreeNode?) -> Bool {
        lowerUpper(root, nil, nil);
        return ans;
    }

    // 检查二叉树是否在区间 (lower, upper) 内，递归过程中确定是否满足二叉搜索树的性质
    @discardableResult
    private func lowerUpper(_  root: TreeNode?, _ lower: Int?, _ upper: Int?) -> Bool {
        if (root == nil) {
            return true;
        }
        if (lower != nil && root!.val <= lower!) {
            ans = false;
            return false;
        }
        if (upper != nil && root!.val >= upper!) {
            ans = false;
            return false;
        }
        return lowerUpper(root!.left, lower, root!.val)
                && lowerUpper(root!.right, root!.val, upper);
    }
}
// https://leetcode.cn/submissions/detail/386999627/
```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```swift
class Solution {
    func isSameTree(_ p: TreeNode?, _ q: TreeNode?) -> Bool {
        if (p == nil && q == nil) {
            return true;
        }
        if (p == nil || q == nil || p!.val != q!.val) {
            return false;
        }
        return isSameTree(p!.left, q!.left) && isSameTree(p!.right, q!.right);
    }
}
// https://leetcode.cn/submissions/detail/384929124/
```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```swift
class Solution {
    func levelOrder(_ root: TreeNode?) -> [[Int]] {
        var ans: [[Int]] = [];
        var queue = Deque<TreeNode>();
        if (root != nil) {
            queue.enqueue(root!);
        }
        while (!queue.isEmpty) {
            var level: [Int] = [];
            let n = queue.count;
            for _ in 1...n {
                let x = queue.dequeue();
                level.append(x!.val);
                let left = x!.left;
                if (left != nil) {
                    queue.enqueue(left!);
                }
                let right = x!.right;
                if (right != nil) {
                    queue.enqueue(right!);
                }
            }
            ans.append(level);
        }
        return ans;
    }
}

/*
  Deque (pronounced "deck"), a double-ended queue

  All enqueuing and dequeuing operations are O(1).
*/
public struct Deque<T> {
    private var array: [T?]
    private var head: Int
    private var capacity: Int
    private let originalCapacity: Int

    public init(_ capacity: Int = 10) {
        self.capacity = max(capacity, 1)
        originalCapacity = self.capacity
        array = [T?](repeating: nil, count: capacity)
        head = capacity
    }

    public var isEmpty: Bool {
        return count == 0
    }

    public var count: Int {
        return array.count - head
    }

    public mutating func enqueue(_ element: T) {
        array.append(element)
    }

    public mutating func enqueueFront(_ element: T) {
        if head == 0 {
            capacity *= 2
            let emptySpace = [T?](repeating: nil, count: capacity)
            array.insert(contentsOf: emptySpace, at: 0)
            head = capacity
        }

        head -= 1
        array[head] = element
    }

    public mutating func dequeue() -> T? {
        guard head < array.count, let element = array[head] else {
            return nil
        }

        array[head] = nil
        head += 1

        if capacity >= originalCapacity && head >= capacity * 2 {
            let amountToRemove = capacity + capacity / 2
            array.removeFirst(amountToRemove)
            head -= amountToRemove
            capacity /= 2
        }
        return element
    }

    public mutating func dequeueBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.removeLast()
        }
    }

    public func peekFront() -> T? {
        if isEmpty {
            return nil
        } else {
            return array[head]
        }
    }

    public func peekBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.last!
        }
    }
}
// https://leetcode.cn/submissions/detail/386070058/
```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```swift
class Solution {
    func zigzagLevelOrder(_ root: TreeNode?) -> [[Int]] {
        var ans: [[Int]] = [];
        var queue = Deque<TreeNode>();
        if (root != nil) {
            queue.enqueue(root!);
        }
        var reverse = false;
        while (!queue.isEmpty) {
            var level: [Int] = [];
            let n = queue.count;
            for _ in 1...n {
                let x = queue.dequeue();
                if (reverse) {
                    level.insert(x!.val, at: 0);
                } else {
                    level.append(x!.val);
                }
                let left = x!.left;
                if (left != nil) {
                    queue.enqueue(left!);
                }
                let right = x!.right;
                if (right != nil) {
                    queue.enqueue(right!);
                }
            }
            reverse = !reverse;
            ans.append(level);
        }
        return ans;
    }
}

/*
  Deque (pronounced "deck"), a double-ended queue

  All enqueuing and dequeuing operations are O(1).
*/
public struct Deque<T> {
    private var array: [T?]
    private var head: Int
    private var capacity: Int
    private let originalCapacity: Int

    public init(_ capacity: Int = 10) {
        self.capacity = max(capacity, 1)
        originalCapacity = self.capacity
        array = [T?](repeating: nil, count: capacity)
        head = capacity
    }

    public var isEmpty: Bool {
        return count == 0
    }

    public var count: Int {
        return array.count - head
    }

    public mutating func enqueue(_ element: T) {
        array.append(element)
    }

    public mutating func enqueueFront(_ element: T) {
        if head == 0 {
            capacity *= 2
            let emptySpace = [T?](repeating: nil, count: capacity)
            array.insert(contentsOf: emptySpace, at: 0)
            head = capacity
        }

        head -= 1
        array[head] = element
    }

    public mutating func dequeue() -> T? {
        guard head < array.count, let element = array[head] else {
            return nil
        }

        array[head] = nil
        head += 1

        if capacity >= originalCapacity && head >= capacity * 2 {
            let amountToRemove = capacity + capacity / 2
            array.removeFirst(amountToRemove)
            head -= amountToRemove
            capacity /= 2
        }
        return element
    }

    public mutating func dequeueBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.removeLast()
        }
    }

    public func peekFront() -> T? {
        if isEmpty {
            return nil
        } else {
            return array[head]
        }
    }

    public func peekBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.last!
        }
    }
}
// https://leetcode.cn/submissions/detail/386071783/
```

```swift
class Solution {
    func zigzagLevelOrder(_ root: TreeNode?) -> [[Int]] {
        var ans: [[Int]] = [];
        var queue = Deque<TreeNode>();
        if (root != nil) {
            queue.enqueue(root!);
        }
        var reverse = false;
        while (!queue.isEmpty) {
            var level: [Int] = [];
            let n = queue.count;
            for _ in 1...n {
                let x = queue.dequeue();
                level.append(x!.val);
                let left = x!.left;
                if (left != nil) {
                    queue.enqueue(left!);
                }
                let right = x!.right;
                if (right != nil) {
                    queue.enqueue(right!);
                }
            }
            if (reverse) {
                level.reverse();
            }
            reverse = !reverse;
            ans.append(level);
        }
        return ans;
    }
}

/*
  Deque (pronounced "deck"), a double-ended queue

  All enqueuing and dequeuing operations are O(1).
*/
public struct Deque<T> {
    private var array: [T?]
    private var head: Int
    private var capacity: Int
    private let originalCapacity: Int

    public init(_ capacity: Int = 10) {
        self.capacity = max(capacity, 1)
        originalCapacity = self.capacity
        array = [T?](repeating: nil, count: capacity)
        head = capacity
    }

    public var isEmpty: Bool {
        return count == 0
    }

    public var count: Int {
        return array.count - head
    }

    public mutating func enqueue(_ element: T) {
        array.append(element)
    }

    public mutating func enqueueFront(_ element: T) {
        if head == 0 {
            capacity *= 2
            let emptySpace = [T?](repeating: nil, count: capacity)
            array.insert(contentsOf: emptySpace, at: 0)
            head = capacity
        }

        head -= 1
        array[head] = element
    }

    public mutating func dequeue() -> T? {
        guard head < array.count, let element = array[head] else {
            return nil
        }

        array[head] = nil
        head += 1

        if capacity >= originalCapacity && head >= capacity * 2 {
            let amountToRemove = capacity + capacity / 2
            array.removeFirst(amountToRemove)
            head -= amountToRemove
            capacity /= 2
        }
        return element
    }

    public mutating func dequeueBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.removeLast()
        }
    }

    public func peekFront() -> T? {
        if isEmpty {
            return nil
        } else {
            return array[head]
        }
    }

    public func peekBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.last!
        }
    }
}
// https://leetcode.cn/submissions/detail/386071420/
```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```swift
class Solution {
    func maxDepth(_ root: TreeNode?) -> Int {
        if (root == nil) {
            return 0;
        }
        return 1 + max(maxDepth(root!.left), maxDepth(root!.right));
    }
}
// https://leetcode.cn/submissions/detail/384927542/
```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```swift
class Solution {
    private var valueToIndex: [Int: Int] = [:];

    func buildTree(_ preorder: [Int], _ inorder: [Int]) -> TreeNode? {
        for (index, value) in inorder.enumerated() {
            valueToIndex[value] = index;
        }
        return buildTree(preorder, 0, preorder.count - 1,
                inorder, 0, inorder.count - 1);
    }

    private func buildTree(_ preorder: [Int], _ preStart: Int, _ preEnd: Int,
                           _ inorder: [Int], _ inStart: Int, _ inEnd: Int) -> TreeNode? {
        if (preStart > preEnd) {
            return nil;
        }
        let rootVal = preorder[preStart];
        let inRoot = valueToIndex[rootVal]!;
        let leftSize = inRoot - inStart;
        let root = TreeNode(rootVal);
        root.left = buildTree(preorder, preStart + 1, preStart + leftSize,
                inorder, inStart, inRoot - 1);
        root.right = buildTree(preorder, preStart + leftSize + 1, preEnd,
                inorder, inRoot + 1, inEnd);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/384978156/
```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```swift
class Solution {
    private var valueToIndex: [Int: Int] = [:];

    func buildTree(_ inorder: [Int], _ postorder: [Int]) -> TreeNode? {
        for (index, value) in inorder.enumerated() {
            valueToIndex[value] = index;
        }
        return buildTree(inorder, 0, inorder.count - 1,
                postorder, 0, postorder.count - 1);
    }

    private func buildTree(_ inorder: [Int], _ inStart: Int, _ inEnd: Int,
                           _ postorder: [Int], _ postStart: Int, _ postEnd: Int) -> TreeNode? {
        if inStart > inEnd {
            return nil;
        }
        let rootVal = postorder[postEnd];
        let root = TreeNode(rootVal);
        let index = valueToIndex[rootVal]!;
        let leftSize = index - inStart;
        root.left = buildTree(inorder, inStart, index - 1,
                postorder, postStart, postStart + leftSize - 1);
        root.right = buildTree(inorder, index + 1, inEnd,
                postorder, postStart + leftSize, postEnd - 1);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/436425037/
```

## 107. 二叉树的层序遍历 II

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```swift
class Solution {
    func levelOrderBottom(_ root: TreeNode?) -> [[Int]] {
        var ans: [[Int]] = [];
        var queue = Deque<TreeNode>();
        if (root != nil) {
            queue.enqueue(root!);
        }
        while (!queue.isEmpty) {
            var level: [Int] = [];
            let n = queue.count;
            for _ in 1...n {
                let x = queue.dequeue();
                level.append(x!.val);
                let left = x!.left;
                if (left != nil) {
                    queue.enqueue(left!);
                }
                let right = x!.right;
                if (right != nil) {
                    queue.enqueue(right!);
                }
            }
            ans.append(level);
        }
        return ans.reversed();
    }
}

/*
  Deque (pronounced "deck"), a double-ended queue

  All enqueuing and dequeuing operations are O(1).
*/
public struct Deque<T> {
    private var array: [T?]
    private var head: Int
    private var capacity: Int
    private let originalCapacity: Int

    public init(_ capacity: Int = 10) {
        self.capacity = max(capacity, 1)
        originalCapacity = self.capacity
        array = [T?](repeating: nil, count: capacity)
        head = capacity
    }

    public var isEmpty: Bool {
        return count == 0
    }

    public var count: Int {
        return array.count - head
    }

    public mutating func enqueue(_ element: T) {
        array.append(element)
    }

    public mutating func enqueueFront(_ element: T) {
        if head == 0 {
            capacity *= 2
            let emptySpace = [T?](repeating: nil, count: capacity)
            array.insert(contentsOf: emptySpace, at: 0)
            head = capacity
        }

        head -= 1
        array[head] = element
    }

    public mutating func dequeue() -> T? {
        guard head < array.count, let element = array[head] else {
            return nil
        }

        array[head] = nil
        head += 1

        if capacity >= originalCapacity && head >= capacity * 2 {
            let amountToRemove = capacity + capacity / 2
            array.removeFirst(amountToRemove)
            head -= amountToRemove
            capacity /= 2
        }
        return element
    }

    public mutating func dequeueBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.removeLast()
        }
    }

    public func peekFront() -> T? {
        if isEmpty {
            return nil
        } else {
            return array[head]
        }
    }

    public func peekBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.last!
        }
    }
}
// https://leetcode.cn/submissions/detail/386070796/
```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```swift
class Solution {
    func sortedArrayToBST(_ nums: [Int]) -> TreeNode? {
        sortedArrayToBST(nums, 0, nums.count - 1);
    }

    // 将有序子数组 nums[lo..hi] 转换为二叉搜索树
    private func sortedArrayToBST(_ nums: [Int], _ lo: Int, _ hi: Int) -> TreeNode? {
        if (lo > hi) {
            return nil;
        }
        let mid = lo + (hi - lo) / 2;
        let root = TreeNode(nums[mid]);
        root.left = sortedArrayToBST(nums, lo, mid - 1);
        root.right = sortedArrayToBST(nums, mid + 1, hi);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/384967257/
```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```swift
class Solution {
    private var ans: Bool = true;

    func isBalanced(_ root: TreeNode?) -> Bool {
        height(root);
        return ans;
    }

    @discardableResult
    private func height(_ root: TreeNode?) -> Int {
        if (root == nil) {
            return -1;
        }
        let left = height(root!.left);
        let right = height(root!.right);
        if (abs(left - right) > 1) {
            ans = false;
        }
        return 1 + max(left, right);
    }
}
// https://leetcode.cn/submissions/detail/384992534/
```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```swift
class Solution {
    func minDepth(_ root: TreeNode?) -> Int {
        var queue = Deque<TreeNode>();
        if (root != nil) {
            queue.enqueue(root!);
        }
        var depth = 0;
        while (!queue.isEmpty) {
            depth += 1;
            let n = queue.count;
            for _ in 1...n {
                let x = queue.dequeue();
                let left = x!.left;
                let right = x!.right;
                if (left == nil && right == nil) {
                    return depth;
                }
                if (left != nil) {
                    queue.enqueue(left!);
                }
                if (right != nil) {
                    queue.enqueue(right!);
                }
            }
        }
        return 0;
    }
}

/*
  Deque (pronounced "deck"), a double-ended queue

  All enqueuing and dequeuing operations are O(1).
*/
public struct Deque<T> {
    private var array: [T?]
    private var head: Int
    private var capacity: Int
    private let originalCapacity: Int

    public init(_ capacity: Int = 10) {
        self.capacity = max(capacity, 1)
        originalCapacity = self.capacity
        array = [T?](repeating: nil, count: capacity)
        head = capacity
    }

    public var isEmpty: Bool {
        return count == 0
    }

    public var count: Int {
        return array.count - head
    }

    public mutating func enqueue(_ element: T) {
        array.append(element)
    }

    public mutating func enqueueFront(_ element: T) {
        if head == 0 {
            capacity *= 2
            let emptySpace = [T?](repeating: nil, count: capacity)
            array.insert(contentsOf: emptySpace, at: 0)
            head = capacity
        }

        head -= 1
        array[head] = element
    }

    public mutating func dequeue() -> T? {
        guard head < array.count, let element = array[head] else {
            return nil
        }

        array[head] = nil
        head += 1

        if capacity >= originalCapacity && head >= capacity * 2 {
            let amountToRemove = capacity + capacity / 2
            array.removeFirst(amountToRemove)
            head -= amountToRemove
            capacity /= 2
        }
        return element
    }

    public mutating func dequeueBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.removeLast()
        }
    }

    public func peekFront() -> T? {
        if isEmpty {
            return nil
        } else {
            return array[head]
        }
    }

    public func peekBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.last!
        }
    }
}
// https://leetcode.cn/submissions/detail/386110116/
```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```swift
class Solution {
    func hasPathSum(_ root: TreeNode?, _ targetSum: Int) -> Bool {
        if (root == nil) {
            return false;
        }
        if (root!.left == nil && root!.right == nil) {
            return root!.val == targetSum;
        }
        return hasPathSum(root!.left, targetSum - root!.val)
                || hasPathSum(root!.right, targetSum - root!.val);
    }
}
// https://leetcode.cn/submissions/detail/385980102/
```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```swift
class Solution {
    func flatten(_ root: TreeNode?) {
        if (root == nil) {
            return;
        }
        flatten(root!.left);
        flatten(root!.right);
        let left = root!.left;
        let right = root!.right;
        root!.left = nil;
        root!.right = left;
        var ptr = root;
        while (ptr!.right != nil) {
            ptr = ptr!.right!;
        }
        ptr!.right = right;
    }
}
// https://leetcode.cn/submissions/detail/384991503/
```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```swift
// TODO
```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```swift
class Solution {
    func maxProfit(_ prices: [Int]) -> Int {
        let n = prices.count;
        if (n == 1) {
            return 0;
        }
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        var dp = Array(repeating: Array(repeating: 0, count: 2), count: n);
        dp[0][0] = 0;
        dp[0][1] = -prices[0];
        for i in 1...n - 1 {
            // dp[i - 1][0]             >= -prices[i]
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = max(-prices[i], dp[i - 1][1]);
        }
        return dp[n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/385799819/
```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```swift
class Solution {
    func maxProfit(_ prices: [Int]) -> Int {
        let n = prices.count;
        if (n == 1) {
            return 0;
        }
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        var dp = Array(repeating: Array(repeating: 0, count: 2), count: n);
        dp[0][0] = 0;
        dp[0][1] = -prices[0];
        for i in 1...n - 1 {
            // dp[i - 1][0]             >= dp[i - 1][0] - prices[i]
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = max(dp[i - 1][0] - prices[i], dp[i - 1][1]);
        }
        return dp[n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/385800340/
```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```swift
class Solution {
    func maxProfit(_ prices: [Int]) -> Int {
        maxProfit(2, prices);
    }

    private func maxProfit(_ k: Int, _ prices: [Int]) -> Int {
        let n = prices.count;
        if (k == 0 || n <= 1) {
            return 0;
        }
        // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
        // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
        var dp = Array(repeating: Array(repeating: Array(repeating: 0, count: 2), count: n), count: k + 1);
        // 交易次数限制为 0 时
        // 填写第 0 个 n x 2 矩阵
        for i in 0...n - 1 {
            dp[0][i][0] = 0;
            dp[0][i][1] = Int.min;
        }
        // 交易次数限制为 [1..k] 时
        // 填写第 t 个 n x 2 矩阵
        for t in 1...k {
            dp[t][0][0] = 0;
            dp[t][0][1] = -prices[0];
            for i in 1...n - 1 {
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
// https://leetcode.cn/submissions/detail/385802833/
```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```swift
class Solution {
    func isPalindrome(_ s: String) -> Bool {
        let chs = [Character](s);
        let n = chs.count;
        var i = -1, j = n;
        while (true) {
            i += 1;
            while (!isValid(chs[i])) {
                if (i == n - 1) {
                    break;
                }
                i += 1;
            }
            j -= 1;
            while (!isValid(chs[j])) {
                if (j == 0) {
                    break;
                }
                j -= 1;
            }
            if (i >= j) {
                break;
            }
            if (chs[i].lowercased() != chs[j].lowercased()) {
                return false;
            }
        }
        return true;
    }

    private func isValid(_ ch: Character) -> Bool {
        ch.isLetter || ch.isNumber;
    }
}
// https://leetcode.cn/submissions/detail/385429210/
```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```swift
class Solution {
    func longestConsecutive(_ nums: [Int]) -> Int {
        var ans = 0;
        var numSet = Set(nums);
        for x in nums {
            if (numSet.contains(x)) {
                var lo = x - 1;
                while (numSet.contains(lo)) {
                    numSet.remove(lo);
                    lo -= 1;
                }
                var hi = x + 1;
                while (numSet.contains(hi)) {
                    numSet.remove(hi);
                    hi += 1;
                }
                ans = max(ans, hi - lo - 1);
                numSet.remove(x);
            }
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/385981619/
```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```swift
class Solution {
    private static let LAND: Character = "O";
    private static let WATER: Character = "X";
    private var mark = false;
    private var recovery = Set<Int>();

    func solve(_ grid: inout [[Character]]) {
        let m = grid.count;
        let n = grid[0].count;
        mark = true;
        // 淹没与左右边界的陆地相连的岛屿
        for row in 0...m - 1 {
            floodFill(&grid, row, 0);
            floodFill(&grid, row, n - 1);
        }
        // 淹没与上下边界的陆地相连的岛屿
        for col in 0...n - 1 {
            floodFill(&grid, 0, col);
            floodFill(&grid, m - 1, col);
        }
        mark = false;
        for row in 0...m - 1 {
            for col in 0...n - 1 {
                if (grid[row][col] == Solution.LAND) {
                    floodFill(&grid, row, col);
                }
            }
        }
        // 重建原来与边界陆地相连的岛屿
        for x in recovery {
            let row = x / n;
            let col = x % n;
            grid[row][col] = Solution.LAND;
        }
    }

    private func floodFill(_ grid: inout [[Character]], _ row: Int, _ col: Int) {
        if (row < 0 || row >= grid.count || col < 0 || col >= grid[0].count
                || grid[row][col] == Solution.WATER) {
            return;
        }
        if (mark) {
            recovery.insert(row * grid[0].count + col);
        }
        grid[row][col] = Solution.WATER;
        floodFill(&grid, row - 1, col);
        floodFill(&grid, row + 1, col);
        floodFill(&grid, row, col - 1);
        floodFill(&grid, row, col + 1);
    }
}
// https://leetcode.cn/submissions/detail/387744377/
```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```swift
class Solution {
    func singleNumber(_ nums: [Int]) -> Int {
        var ans = 0;
        for x in nums {
            ans ^= x;
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/384852987/
```

## 141. 环形链表

<https://leetcode-cn.com/problems/linked-list-cycle/>

```swift
class Solution {
    func hasCycle(_ head: ListNode?) -> Bool {
        var slow = head, fast = head;
        while (fast != nil && fast!.next != nil) {
            slow = slow!.next;
            fast = fast!.next!.next;
            if (slow === fast) {
                return true;
            }
        }
        return false;
    }
}
// https://leetcode.cn/submissions/detail/384870414/
```

## 142. 环形链表 II

<https://leetcode-cn.com/problems/linked-list-cycle-ii/>

```swift
class Solution {
    func detectCycle(_ head: ListNode?) -> ListNode? {
        var slow = head, fast = head;
        while (fast != nil && fast!.next != nil) {
            slow = slow!.next;
            fast = fast!.next!.next;
            if (slow === fast) {
                fast = head;
                while (slow !== fast) {
                    slow = slow!.next;
                    fast = fast!.next;
                }
                return slow;
            }
        }
        return nil;
    }
}
// https://leetcode.cn/submissions/detail/384870998/
```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```swift
class Solution {
    func reorderList(_ head: ListNode?) {
        var slow = head, fast = head;
        while (fast!.next != nil && fast!.next!.next != nil) {
            slow = slow!.next;
            fast = fast!.next!.next;
        }
        var right = reverseList(slow!.next);
        slow!.next = nil;
        var ptr = ListNode();
        var left = head;
        while (left != nil) {
            ptr.next = left;
            ptr = ptr.next!;
            left = left!.next;
            if (right != nil) {
                ptr.next = right;
                ptr = ptr.next!;
                right = right!.next;
            }
        }
    }

    private func reverseList(_ head: ListNode?) -> ListNode? {
        var reverseHead: ListNode?;
        var ptr = head;
        while (ptr != nil) {
            let x = ptr!.next;
            ptr!.next = reverseHead;
            reverseHead = ptr;
            ptr = x;
        }
        return reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/386781568/
```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```swift
class Solution {
    private var ans: [Int] = [];

    func preorderTraversal(_ root: TreeNode?) -> [Int] {
        dfs(root);
        return ans;
    }

    private func dfs(_ root: TreeNode?) {
        if (root == nil) {
            return;
        }
        ans.append(root!.val);
        dfs(root!.left);
        dfs(root!.right);
    }
}
// https://leetcode.cn/submissions/detail/384923695/
```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```swift
class Solution {
    private var ans: [Int] = [];

    func postorderTraversal(_ root: TreeNode?) -> [Int] {
        dfs(root);
        return ans;
    }

    private func dfs(_ root: TreeNode?) {
        if (root == nil) {
            return;
        }
        dfs(root!.left);
        dfs(root!.right);
        ans.append(root!.val);
    }
}
// https://leetcode.cn/submissions/detail/384924611/
```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```swift
class Node {
    public var key: Int;
    public var val: Int;
    public var prev: Node?;
    public var next: Node?;

    init(_ key: Int, _ val: Int, _ prev: Node? = nil, _ next: Node? = nil) {
        self.key = key
        self.val = val
        self.prev = prev
        self.next = next
    }
}

struct DoublyLinkedList {
    private var first: Node? = nil;
    private var last: Node? = nil;
    private var n = 0;

    public mutating func addLast(_ x: Node) {
        if (n == 0) {
            first = x;
            last = x;
        } else {
            last!.next = x;
            x.prev = last;
            last = x;
        }
        n += 1;
    }

    @discardableResult
    public mutating func removeFirst() -> Node {
        let oldFirst = first;
        if (n == 1) {
            first = nil;
            last = nil;
        } else {
            first = first!.next;
            first!.prev = nil;
            oldFirst!.next = nil;
        }
        n -= 1;
        return oldFirst!;
    }

    @discardableResult
    public mutating func removeLast() -> Node {
        let oldLast = last;
        if (n == 1) {
            first = nil;
            last = nil;
        } else {
            last = last!.prev;
            last!.next = nil;
            oldLast!.prev = nil;
        }
        n -= 1;
        return oldLast!;
    }

    public mutating func remove(_ x: Node) {
        if (x === first) {
            removeFirst();
        } else if (x === last) {
            removeLast();
        } else {
            x.prev!.next = x.next;
            x.next!.prev = x.prev;
            x.prev = nil;
            x.next = nil;
            n -= 1;
        }
    }
}

class LRUCache {
    private var list: DoublyLinkedList = DoublyLinkedList();
    private var keyToNode: [Int: Node] = [:];
    private var capacity: Int;

    init(_ capacity: Int) {
        self.capacity = capacity;
    }

    func get(_ key: Int) -> Int {
        if (contains(key)) {
            return touchCache(key, nil);
        }
        return -1;
    }

    func put(_ key: Int, _ value: Int) {
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

    private func contains(_ key: Int) -> Bool {
        keyToNode[key] != nil;
    }

    private func full() -> Bool {
        keyToNode.count == capacity;
    }

    private func addCache(_ key: Int, _ val: Int) {
        let x = Node(key, val);
        list.addLast(x);
        keyToNode[key] = x;
    }

    private func removeCache() {
        keyToNode.removeValue(forKey: list.removeFirst().key);
    }

    @discardableResult
    private func touchCache(_ key: Int, _ val: Int?) -> Int {
        let x = keyToNode[key]!;
        if (val != nil) {
            x.val = val!;
        }
        list.remove(x);
        list.addLast(x);
        return x.val;
    }
}
// https://leetcode.cn/submissions/detail/387970840/
```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```swift
class Solution {
    func findMin(_ nums: [Int]) -> Int {
        var lo = 0, hi = nums.count - 1;
        while (lo < hi) {
            let mid = lo + (hi - lo) / 2;
            if (nums[mid] < nums[hi]) {
                hi = mid;
            } else {
                lo = mid + 1;
            }
        }
        return nums[lo];
    }
}
// https://leetcode.cn/submissions/detail/384827668/
```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```swift
class MinStack {
    private var stack: [(Int, Int)] = [];

    init() {
    }

    func push(_ val: Int) {
        let x = stack.isEmpty ? val : min(getMin(), val);
        stack.append((val, x));
    }

    func pop() {
        stack.removeLast()
    }

    func top() -> Int {
        stack.last!.0;
    }

    func getMin() -> Int {
        stack.last!.1;
    }
}
// https://leetcode.cn/submissions/detail/385987445/
```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```swift
class Solution {
    func getIntersectionNode(_ headA: ListNode?, _ headB: ListNode?) -> ListNode? {
        var ptrA = headA, ptrB = headB;
        while (ptrA !== ptrB) {
            ptrA = (ptrA == nil ? headB : ptrA!.next);
            ptrB = (ptrB == nil ? headA : ptrB!.next);
        }
        return ptrA;
    }
}
// https://leetcode.cn/submissions/detail/384869511/
```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```swift
class Solution {
    private static let DOT: UInt8 = 46;
    private static let ZERO: UInt8 = 48;

    func compareVersion(_ version1: String, _ version2: String) -> Int {
        let chs1 = [Character](version1), chs2 = [Character](version2);
        let n1 = chs1.count, n2 = chs2.count;
        var i = 0, j = 0;
        while (i < n1 || j < n2) {
            var r1 = 0;
            while (i < n1) {
                let code = chs1[i].asciiValue;
                i += 1;
                if (code! == Solution.DOT) {
                    break;
                }
                r1 = r1 * 10 + Int((code! - Solution.ZERO));
            }
            var r2 = 0;
            while (j < n2) {
                let code = chs2[j].asciiValue;
                j += 1;
                if (code == Solution.DOT) {
                    break;
                }
                r2 = r2 * 10 + Int((code! - Solution.ZERO));
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
// https://leetcode.cn/submissions/detail/387244241/
```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```swift
class Solution {
    func twoSum(_ numbers: [Int], _ target: Int) -> [Int] {
        var i = 0;
        var j = numbers.count - 1;
        while (i < j) {
            let sum = numbers[i] + numbers[j];
            if (sum > target) {
                j -= 1;
            } else if (sum < target) {
                i += 1;
            } else {
                return [i + 1, j + 1];
            }
        }
        return [-1, -1];
    }
}
// https://leetcode.cn/submissions/detail/384817754/
```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```swift
class Solution {
    func majorityElement(_ nums: [Int]) -> Int {
        var candidate = Int.min;
        var count = 0;
        for x in nums {
            if (count == 0) {
                candidate = x;
                count = 1;
            } else {
                if (x == candidate) {
                    count += 1;
                } else {
                    count -= 1;
                }
            }
        }
        return candidate;
    }
}
// https://leetcode.cn/submissions/detail/386587568/
```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```swift
class Solution {
    func largestNumber(_ nums: [Int]) -> String {
        var strs = nums.map {
            String($0)
        };
        strs.sort(by: { s1, s2 in s2 + s1 < s1 + s2 });
        let ans = strs.joined();
        return ans[ans.startIndex] == "0" ? "0" : ans;
    }
}
// https://leetcode.cn/submissions/detail/385531091/
```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```swift
class Solution {
    func maxProfit(_ k: Int, _ prices: [Int]) -> Int {
        let n = prices.count;
        if (k == 0 || n <= 1) {
            return 0;
        }
        // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
        // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
        var dp = Array(repeating: Array(repeating: Array(repeating: 0, count: 2), count: n), count: k + 1);
        // 交易次数限制为 0 时
        // 填写第 0 个 n x 2 矩阵
        for i in 0...n - 1 {
            dp[0][i][0] = 0;
            dp[0][i][1] = Int.min;
        }
        // 交易次数限制为 [1..k] 时
        // 填写第 t 个 n x 2 矩阵
        for t in 1...k {
            dp[t][0][0] = 0;
            dp[t][0][1] = -prices[0];
            for i in 1...n - 1 {
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
// https://leetcode.cn/submissions/detail/385802520/
```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```swift
class Solution {
    func rotate(_ nums: inout [Int], _ k: Int) {
        let n = nums.count;
        let t = k % n;
        if (t > 0) {
            reverse(&nums, 0, n - 1);
            reverse(&nums, 0, t - 1);
            reverse(&nums, t, n - 1);
        }
    }

    private func reverse(_ nums: inout [Int], _ lo: Int, _ hi: Int) {
        var i = lo, j = hi;
        while (i < j) {
            nums.swapAt(i, j);
            i += 1;
            j -= 1;
        }
    }
}
// https://leetcode.cn/submissions/detail/384826900/
```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```swift
class Solution {
    func rob(_ nums: [Int]) -> Int {
        subseqSum(nums);
    }

    // max({sum(subseq) | subseq 是数组 nums 的不连续子序列})
    private func subseqSum(_ nums: [Int]) -> Int {
        let n = nums.count;
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return nums[0];
        }
        // dp[i] = max({sum(subseq) | subseq 是子数组 nums[0..i] 的不连续子序列})
        var dp = Array(repeating: 0, count: n);
        dp[0] = nums[0];
        dp[1] = max(nums[0], nums[1]);
        if (n > 2) {
            for i in 2...n - 1 {
                // 包含 nums[i]
                let sp1 = dp[i - 2] + nums[i];
                // 不包含 nums[i]
                let sp2 = dp[i - 1];
                dp[i] = max(sp1, sp2);
            }
        }
        return dp[n - 1];
    }
}
// https://leetcode.cn/submissions/detail/385790112/
```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```swift
class Solution {
    func rightSideView(_ root: TreeNode?) -> [Int] {
        var ans: [Int] = [];
        var queue = Deque<TreeNode>();
        if (root != nil) {
            queue.enqueue(root!);
        }
        while (!queue.isEmpty) {
            ans.append(queue.peekBack()!.val);
            let n = queue.count;
            for _ in 1...n {
                let x = queue.dequeue();
                let left = x!.left;
                if (left != nil) {
                    queue.enqueue(left!);
                }
                let right = x!.right;
                if (right != nil) {
                    queue.enqueue(right!);
                }
            }
        }
        return ans;
    }
}

/*
  Deque (pronounced "deck"), a double-ended queue

  All enqueuing and dequeuing operations are O(1).
*/
public struct Deque<T> {
    private var array: [T?]
    private var head: Int
    private var capacity: Int
    private let originalCapacity: Int

    public init(_ capacity: Int = 10) {
        self.capacity = max(capacity, 1)
        originalCapacity = self.capacity
        array = [T?](repeating: nil, count: capacity)
        head = capacity
    }

    public var isEmpty: Bool {
        return count == 0
    }

    public var count: Int {
        return array.count - head
    }

    public mutating func enqueue(_ element: T) {
        array.append(element)
    }

    public mutating func enqueueFront(_ element: T) {
        if head == 0 {
            capacity *= 2
            let emptySpace = [T?](repeating: nil, count: capacity)
            array.insert(contentsOf: emptySpace, at: 0)
            head = capacity
        }

        head -= 1
        array[head] = element
    }

    public mutating func dequeue() -> T? {
        guard head < array.count, let element = array[head] else {
            return nil
        }

        array[head] = nil
        head += 1

        if capacity >= originalCapacity && head >= capacity * 2 {
            let amountToRemove = capacity + capacity / 2
            array.removeFirst(amountToRemove)
            head -= amountToRemove
            capacity /= 2
        }
        return element
    }

    public mutating func dequeueBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.removeLast()
        }
    }

    public func peekFront() -> T? {
        if isEmpty {
            return nil
        } else {
            return array[head]
        }
    }

    public func peekBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.last!
        }
    }
}
// https://leetcode.cn/submissions/detail/386072437/
```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```swift
class Solution {
    private static let LAND: Character = "1";
    private static let WATER: Character = "0";

    func numIslands(_ grid: [[Character]]) -> Int {
        var copy = grid;
        var count = 0;
        for row in 0...copy.count - 1 {
            for col in 0...copy[0].count - 1 {
                if (copy[row][col] == Solution.LAND) {
                    floodFill(&copy, row, col);
                    count += 1;
                }
            }
        }
        return count;
    }

    private func floodFill(_ grid: inout [[Character]], _ row: Int, _ col: Int) {
        if (row < 0 || row >= grid.count || col < 0 || col >= grid[0].count
                || grid[row][col] == Solution.WATER) {
            return;
        }
        grid[row][col] = Solution.WATER;
        floodFill(&grid, row - 1, col);
        floodFill(&grid, row + 1, col);
        floodFill(&grid, row, col - 1);
        floodFill(&grid, row, col + 1);
    }
}
// https://leetcode.cn/submissions/detail/387741572/
```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```swift
class Solution {
    func removeElements(_ head: ListNode?, _ val: Int) -> ListNode? {
        let dummyHead = ListNode(-1, head);
        var ptr = dummyHead;
        while (ptr.next != nil) {
            if (ptr.next!.val == val) {
                ptr.next = ptr.next!.next;
            } else {
                ptr = ptr.next!;
            }
        }
        return dummyHead.next;
    }
}
// https://leetcode.cn/submissions/detail/384920642/
```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```swift
class Solution {
    func reverseList(_ head: ListNode?) -> ListNode? {
        var reverseHead: ListNode?;
        var ptr = head;
        while (ptr != nil) {
            let x = ptr!.next;
            ptr!.next = reverseHead;
            reverseHead = ptr;
            ptr = x;
        }
        return reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/384872992/
```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```swift
class Solution {
    private var marked: [Bool] = [];
    private var onStack: [Bool] = [];
    private var hasCycle = false;

    func canFinish(_ numCourses: Int, _ prerequisites: [[Int]]) -> Bool {
        marked = Array(repeating: false, count: numCourses);
        onStack = Array(repeating: false, count: numCourses);
        var graph: [[Int]] = Array(repeating: [], count: numCourses);
        for p in prerequisites {
            let v = p[1];
            let w = p[0];
            graph[v].append(w);
        }
        for v in 0...numCourses - 1 {
            if (!marked[v]) {
                dfs(graph, v);
                if (hasCycle) {
                    return false;
                }
            }
        }
        return true;
    }

    private func dfs(_ graph: [[Int]], _ v: Int) {
        onStack[v] = true;
        marked[v] = true;
        for w in graph[v] {
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
}
// https://leetcode.cn/submissions/detail/387979585/
```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```swift
class Solution {
    private var marked: [Bool] = [];
    private var onStack: [Bool] = [];
    private var postorder: [Int] = [];
    private var hasCycle = false;

    func findOrder(_ numCourses: Int, _ prerequisites: [[Int]]) -> [Int] {
        marked = Array(repeating: false, count: numCourses);
        onStack = Array(repeating: false, count: numCourses);
        var graph: [[Int]] = Array(repeating: [], count: numCourses);
        for p in prerequisites {
            let v = p[1];
            let w = p[0];
            graph[v].append(w);
        }
        for v in 0...numCourses - 1 {
            if (!marked[v]) {
                dfs(graph, v);
                if (hasCycle) {
                    return [];
                }
            }
        }
        return postorder.reversed();
    }

    private func dfs(_ graph: [[Int]], _ v: Int) {
        onStack[v] = true;
        marked[v] = true;
        for w in graph[v] {
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
        postorder.append(v);
        onStack[v] = false;
    }
}
// https://leetcode.cn/submissions/detail/387980235/
```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```swift
class Solution {
    func rob(_ nums: [Int]) -> Int {
        let n = nums.count;
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return nums[0];
        }
        return max(subseqSum(nums, 0, n - 2), subseqSum(nums, 1, n - 1));
    }

    // max({sum(subseq) | subseq 是子数组 nums[lo..hi] 的不连续子序列})
    private func subseqSum(_ nums: [Int], _ lo: Int, _ hi: Int) -> Int {
        let n = hi - lo + 1;
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return nums[lo];
        }
        // dp[i] = max({sum(subseq) | subseq 是子数组 nums[lo..lo+i] 的不连续子序列})
        var dp = Array(repeating: 0, count: n);
        dp[0] = nums[lo];
        dp[1] = max(nums[lo], nums[lo + 1]);
        if (n > 2) {
            for i in 2...n - 1 {
                // 包含 nums[lo+i]
                let sp1 = dp[i - 2] + nums[lo + i];
                // 不包含 nums[lo+i]
                let sp2 = dp[i - 1];
                dp[i] = max(sp1, sp2);
            }
        }
        return dp[n - 1];
    }
}
// https://leetcode.cn/submissions/detail/385793081/
```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```swift
class Solution {
    func findKthLargest(_ nums: [Int], _ k: Int) -> Int {
        var copy = nums.shuffled();
        return select(&copy, copy.count - k);
    }

    // 返回数组 nums 从小到大排在第 rank 位的元素，排位从 0 开始计算，
    // 相当于有 rank 个元素小于该元素。
    private func select(_ nums: inout [Int], _ rank: Int) -> Int {
        var lo = 0, hi = nums.count - 1;
        while (lo < hi) {
            let j = partition(&nums, lo, hi);
            if (rank < j) {
                hi = j - 1;
            } else if (j < rank) {
                lo = j + 1;
            } else {
                return nums[j];
            }
        }
        return nums[lo];
    }

    private func partition(_ nums: inout [Int], _ lo: Int, _ hi: Int) -> Int {
        let v = nums[lo];
        var i = lo, j = hi + 1;
        while (true) {
            i += 1;
            while (nums[i] < v) {
                if (i == hi) {
                    break;
                }
                i += 1;
            }
            j -= 1;
            while (v < nums[j]) {
                if (j == lo) {
                    break;
                }
                j -= 1;
            }
            if (i >= j) {
                break;
            }
            nums.swapAt(i, j);
        }
        nums.swapAt(lo, j);
        return j;
    }
}
// https://leetcode.cn/submissions/detail/384850597/
```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```swift
class Solution {
    private var pathSum = 0;
    private var path: [Int] = []; // 取 [1..9] 为元素
    private var ans: [[Int]] = [];

    func combinationSum3(_ k: Int, _ n: Int) -> [[Int]] {
        backtrack(k, n, 0);
        return ans;
    }

    // edge = 取 [1..9] 为值
    private func backtrack(_ k: Int, _ n: Int, _ edge: Int) {
        if (path.count == k && pathSum == n) {
            ans.append(path);
        } else if (path.count < k && pathSum < n) {
            // 避免重复，从 edge + 1 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            var e = edge + 1;
            while (e <= 9) {
                if (pathSum + e <= n) {
                    pathSum += e;
                    path.append(e);
                    backtrack(k, n, e);
                    pathSum -= e;
                    path.removeLast();
                }
                e += 1;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/387749667/
```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```swift
class Solution {
    func countNodes(_ root: TreeNode?) -> Int {
        if (root == nil) {
            return 0;
        }
        var leftHeight = 0;
        var ptr = root;
        while (ptr != nil) {
            leftHeight += 1;
            ptr = ptr!.left;
        }
        var rightHeight = 0;
        ptr = root;
        while (ptr != nil) {
            rightHeight += 1;
            ptr = ptr!.right;
        }
        if (leftHeight == rightHeight) {
            return (1 << leftHeight) - 1;
        }
        return 1 + countNodes(root!.left) + countNodes(root!.right);
    }
}
// https://leetcode.cn/submissions/detail/385065677/
```

```swift
class Solution {
    func countNodes(_ root: TreeNode?) -> Int {
        if (root == nil) {
            return 0;
        }
        var leftHeight = 0;
        var ptr = root;
        while (ptr != nil) {
            leftHeight += 1;
            ptr = ptr!.left;
        }
        var rightHeight = 0;
        ptr = root;
        while (ptr != nil) {
            rightHeight += 1;
            ptr = ptr!.right;
        }
        if (leftHeight == rightHeight) {
            return Int(pow(2.0, Double(leftHeight))) - 1;
        }
        return 1 + countNodes(root!.left) + countNodes(root!.right);
    }
}
// https://leetcode.cn/submissions/detail/385065414/
```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```swift
class MyStack {
    private var queue = Deque<Int>();

    init() {
    }

    func push(_ x: Int) {
        queue.enqueue(x);
        let n = queue.count;
        if (n > 1) {
            for _ in 1...n - 1 {
                queue.enqueue(queue.dequeue()!);
            }
        }
    }

    func pop() -> Int {
        queue.dequeue()!;
    }

    func top() -> Int {
        queue.peekFront()!;
    }

    func empty() -> Bool {
        queue.isEmpty;
    }
}

/*
  Deque (pronounced "deck"), a double-ended queue

  All enqueuing and dequeuing operations are O(1).
*/
public struct Deque<T> {
    private var array: [T?]
    private var head: Int
    private var capacity: Int
    private let originalCapacity: Int

    public init(_ capacity: Int = 10) {
        self.capacity = max(capacity, 1)
        originalCapacity = self.capacity
        array = [T?](repeating: nil, count: capacity)
        head = capacity
    }

    public var isEmpty: Bool {
        return count == 0
    }

    public var count: Int {
        return array.count - head
    }

    public mutating func enqueue(_ element: T) {
        array.append(element)
    }

    public mutating func enqueueFront(_ element: T) {
        if head == 0 {
            capacity *= 2
            let emptySpace = [T?](repeating: nil, count: capacity)
            array.insert(contentsOf: emptySpace, at: 0)
            head = capacity
        }

        head -= 1
        array[head] = element
    }

    public mutating func dequeue() -> T? {
        guard head < array.count, let element = array[head] else {
            return nil
        }

        array[head] = nil
        head += 1

        if capacity >= originalCapacity && head >= capacity * 2 {
            let amountToRemove = capacity + capacity / 2
            array.removeFirst(amountToRemove)
            head -= amountToRemove
            capacity /= 2
        }
        return element
    }

    public mutating func dequeueBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.removeLast()
        }
    }

    public func peekFront() -> T? {
        if isEmpty {
            return nil
        } else {
            return array[head]
        }
    }

    public func peekBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.last!
        }
    }
}
// https://leetcode.cn/submissions/detail/387965150/
```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```swift
class Solution {
    func invertTree(_ root: TreeNode?) -> TreeNode? {
        if (root == nil) {
            return nil;
        }
        let left = invertTree(root!.left);
        let right = invertTree(root!.right);
        root!.left = right;
        root!.right = left;
        return root;
    }
}
// https://leetcode.cn/submissions/detail/384991097/
```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```swift
extension TreeNode: Hashable {
    public func hash(into hasher: inout Hasher) {
        hasher.combine(val)
        hasher.combine(left)
        hasher.combine(right)
    }

    public static func ==(lhs: TreeNode, rhs: TreeNode) -> Bool {
        if lhs === rhs {
            return true
        }
        if type(of: lhs) != type(of: rhs) {
            return false
        }
        if lhs.val != rhs.val {
            return false
        }
        if lhs.left != rhs.left {
            return false
        }
        if lhs.right != rhs.right {
            return false
        }
        return true
    }
}

class Solution {
    private var nodeToSize: [TreeNode: Int] = [:];

    func kthSmallest(_ root: TreeNode?, _ k: Int) -> Int {
        select(root, k - 1);
    }

    private func select(_ root: TreeNode?, _ rank: Int) -> Int {
        if (root == nil) {
            return -1;
        }
        let leftSize = size(root!.left);
        if (rank < leftSize) {
            return select(root!.left, rank);
        }
        if (leftSize < rank) {
            return select(root!.right, rank - leftSize - 1);
        }
        return root!.val;
    }

    private func size(_ root: TreeNode?) -> Int {
        if (root == nil) {
            return 0;
        }
        if (nodeToSize[root!] == nil) {
            nodeToSize[root!] = 1 + size(root!.left) + size(root!.right);
        }
        return nodeToSize[root!]!;
    }
}
// https://leetcode.cn/submissions/detail/387981743/
```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```swift
/**
 * -----------------------------| |-------------------------------
 * pop <- top Left Stack bottom | | bottom Right Stack top <- push
 * -----------------------------| |-------------------------------
 */
class MyQueue {
    private var leftStack: [Int] = [];
    private var rightStack: [Int] = [];

    init() {
    }

    func push(_ x: Int) {
        rightStack.append(x);
    }

    func pop() -> Int {
        if (leftStack.isEmpty) {
            move();
        }
        return leftStack.removeLast();
    }

    func peek() -> Int {
        if (leftStack.isEmpty) {
            move();
        }
        return leftStack.last!;
    }

    func empty() -> Bool {
        leftStack.isEmpty && rightStack.isEmpty;
    }

    private func move() {
        while (!rightStack.isEmpty) {
            leftStack.append(rightStack.removeLast());
        }
    }
}
// https://leetcode.cn/submissions/detail/387234586/
```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```swift
class Solution {
    func isPalindrome(_ head: ListNode?) -> Bool {
        // 寻找链表的中点（偶数个节点时选择左侧），即前半部分链表的尾节点
        var slow = head;
        var fast = head;
        while (fast!.next != nil && fast!.next!.next != nil) {
            slow = slow!.next;
            fast = fast!.next!.next;
        }
        // 翻转后半部分链表
        let reverseHead = reverseList(slow!.next);
        slow!.next = nil;
        // 判断是否回文链表
        var left = head;
        var right = reverseHead;
        while (right != nil) {
            if (left!.val != right!.val) {
                return false;
            }
            left = left!.next;
            right = right!.next;
        }
        // 还原链表
        slow!.next = reverseList(reverseHead);
        return true;
    }

    private func reverseList(_ head: ListNode?) -> ListNode? {
        var reverseHead: ListNode?;
        var ptr = head;
        while (ptr != nil) {
            let x = ptr!.next;
            ptr!.next = reverseHead;
            reverseHead = ptr;
            ptr = x;
        }
        return reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/384880036/
```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```swift
class Solution {
    func lowestCommonAncestor(_ root: TreeNode?, _ p: TreeNode?, _ q: TreeNode?) -> TreeNode? {
        // 保证 p < q
        if (p!.val > q!.val) {
            return lowestCommonAncestor(root, q, p);
        }
        if (p!.val <= root!.val && root!.val <= q!.val) {
            return root;
        }
        if (q!.val < root!.val) {
            return lowestCommonAncestor(root!.left, p, q);
        }
        if (root!.val < p!.val) {
            return lowestCommonAncestor(root!.right, p, q);
        }
        return nil;
    }
}
// https://leetcode.cn/submissions/detail/385072960/
```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```swift
class Solution {
    private var lca: TreeNode?;

    func lowestCommonAncestor(_ root: TreeNode?, _ p: TreeNode?, _ q: TreeNode?) -> TreeNode? {
        find(root, p, q);
        return lca;
    }

    // 在子树中查找节点 p 或 q，递归过程中确定『最近公共祖先』
    @discardableResult
    private func find(_ root: TreeNode?, _ p: TreeNode?, _ q: TreeNode?) -> Bool {
        if (root == nil) {
            return false;
        }
        if (root === p || root === q) {
            // 如果 lca(p,q) = p 或 q，则此处的 lca = root 是最终答案
            lca = root;
            return true;
        }
        let left = find(root!.left, p, q);
        let right = find(root!.right, p, q);
        if (left && right) {
            // 否则返回到某祖先节点处的 lca = root 才是最终答案
            lca = root;
        }
        return left || right;
    }
}
// https://leetcode.cn/submissions/detail/385073736/
```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```swift
class Solution {
    func deleteNode(_ node: ListNode?) {
        node!.val = node!.next!.val;
        node!.next = node!.next!.next;
    }
}
// https://leetcode.cn/submissions/detail/384921786/
```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```swift
class Solution {
    func maxSlidingWindow(_ nums: [Int], _ k: Int) -> [Int] {
        var ans: [Int] = [];
        var maxMonoQueue = Deque<Int>();
        for i in 0...nums.count - 1 {
            // nums[i] = 进入窗口的数字
            let x = nums[i];
            while (!maxMonoQueue.isEmpty && maxMonoQueue.peekBack()! < x) {
                maxMonoQueue.dequeueBack();
            }
            maxMonoQueue.enqueue(x);
            if (i < k - 1) {
                continue;
            }
            // nums[i-k] = 退出窗口的数字
            if (i >= k && nums[i - k] == maxMonoQueue.peekFront()) {
                maxMonoQueue.dequeue();
            }
            ans.append(maxMonoQueue.peekFront()!);
        }
        return ans;
    }
}

/*
  Deque (pronounced "deck"), a double-ended queue

  All enqueuing and dequeuing operations are O(1).
*/
public struct Deque<T> {
    private var array: [T?]
    private var head: Int
    private var capacity: Int
    private let originalCapacity: Int

    public init(_ capacity: Int = 10) {
        self.capacity = max(capacity, 1)
        originalCapacity = self.capacity
        array = [T?](repeating: nil, count: capacity)
        head = capacity
    }

    public var isEmpty: Bool {
        return count == 0
    }

    public var count: Int {
        return array.count - head
    }

    public mutating func enqueue(_ element: T) {
        array.append(element)
    }

    public mutating func enqueueFront(_ element: T) {
        if head == 0 {
            capacity *= 2
            let emptySpace = [T?](repeating: nil, count: capacity)
            array.insert(contentsOf: emptySpace, at: 0)
            head = capacity
        }

        head -= 1
        array[head] = element
    }

    public mutating func dequeue() -> T? {
        guard head < array.count, let element = array[head] else { return nil }

        array[head] = nil
        head += 1

        if capacity >= originalCapacity && head >= capacity*2 {
            let amountToRemove = capacity + capacity/2
            array.removeFirst(amountToRemove)
            head -= amountToRemove
            capacity /= 2
        }
        return element
    }

    public mutating func dequeueBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.removeLast()
        }
    }

    public func peekFront() -> T? {
        if isEmpty {
            return nil
        } else {
            return array[head]
        }
    }

    public func peekBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.last!
        }
    }
}
// https://leetcode.cn/submissions/detail/386771303/
```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```swift
// TODO
```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```swift
class Solution {
    func moveZeroes(_ nums: inout [Int]) {
        // [0..i-1] != 0
        // [i..j-1] == 0
        // [j..n-1] Scanning
        var i = 0, j = 0;
        let n = nums.count;
        while (j < n) {
            while (j < n && nums[j] == 0) {
                j += 1;
            }
            if (j < n) {
                nums.swapAt(i, j);
                i += 1;
                j += 1;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/384744768/
```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```swift
class Codec {
    func serialize(_ root: TreeNode?) -> String {
        if (root == nil) {
            return "#";
        }
        let left = serialize(root!.left);
        let right = serialize(root!.right);
        return left + "," + right + "," + String(root!.val);
    }

    func deserialize(_ data: String) -> TreeNode? {
        var postorder = data.split(separator: ",");
        return buildTree(&postorder);
    }

    private func buildTree(_ postorder: inout [String.SubSequence]) -> TreeNode? {
        let str = postorder.popLast();
        if (str == "#") {
            return nil;
        }
        let root = TreeNode(Int(str!)!);
        root.right = buildTree(&postorder);
        root.left = buildTree(&postorder);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/384990386/
```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```swift
class Solution {
    func lengthOfLIS(_ nums: [Int]) -> Int {
        let n = nums.count;
        if (n == 1) {
            return 1;
        }
        // dp[i] = max({length(subseq) | subseq 是以 nums[i] 结尾的严格递增子序列})
        var dp = Array(repeating: 1, count: n);
        var ans = 1;
        for i in 1...n - 1 {
            var res = 1;
            for j in stride(from: i - 1, through: 0, by: -1) {
                if (nums[j] < nums[i]) {
                    res = max(res, dp[j] + 1);
                }
            }
            dp[i] = res;
            ans = max(ans, dp[i]);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/387505826/
```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```swift
class NumArray {
    private var sum: [Int];

    init(_ nums: [Int]) {
        let n = nums.count;
        sum = nums;
        if (n > 1) {
            for i in 1...n - 1 {
                sum[i] = sum[i - 1] + nums[i];
            }
        }
    }

    func sumRange(_ left: Int, _ right: Int) -> Int {
        if (left == 0) {
            return sum[right];
        }
        return sum[right] - sum[left - 1];
    }
}
// https://leetcode.cn/submissions/detail/386753750/
```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```swift
class Solution {
    func maxProfit(_ prices: [Int]) -> Int {
        let n = prices.count;
        if (n == 1) {
            return 0;
        }
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        var dp = Array(repeating: Array(repeating: 0, count: 2), count: n);
        dp[0][0] = 0;
        dp[0][1] = -prices[0];
        dp[1][0] = max(dp[0][0], dp[0][1] + prices[1]);
        dp[1][1] = max(dp[0][0] - prices[1], dp[0][1]);
        if (n > 2) {
            for i in 2...n - 1 {
                // dp[i - 1][0]             >= dp[i - 2][0] >= p[i - 2][0] - prices[i]
                // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
                // => dp[i][0] >= dp[i][1]
                dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
                dp[i][1] = max(dp[i - 2][0] - prices[i], dp[i - 1][1]);
            }
        }
        return dp[n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/385801581/
```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```swift
struct Pair {
    let val: Int;
    let idx: Int;

    init(_ val: Int, _ idx: Int) {
        self.val = val
        self.idx = idx
    }
}

class Solution {
    private var counts: [Int]? = nil;

    func countSmaller(_ nums: [Int]) -> [Int] {
        let n = nums.count;
        counts = Array(repeating: 0, count: n);
        var pairs: [Pair] = [];
        for (idx, val) in nums.enumerated() {
            pairs.append(Pair(val, idx));
        }
        var aux = pairs;
        sort(&pairs, &aux, 0, n - 1);
        return counts!;
    }

    private func sort(_ pairs: inout [Pair], _ aux: inout [Pair], _ lo: Int, _ hi: Int) {
        if (lo >= hi) {
            return;
        }
        let mid = lo + (hi - lo) / 2;
        sort(&pairs, &aux, lo, mid);
        sort(&pairs, &aux, mid + 1, hi);
        merge(&pairs, &aux, lo, mid, hi);
    }

    private func merge(_ pairs: inout [Pair], _ aux: inout [Pair], _ lo: Int, _ mid: Int, _ hi: Int) {
        for k in lo...hi {
            aux[k] = pairs[k];
        }
        var i = lo, j = mid + 1;
        for k in lo...hi {
            if (i > mid || (j <= hi && aux[j].val < aux[i].val)) {
                pairs[k] = aux[j];
                j += 1;
            } else {
                let p = aux[i];
                // aux[mid+1..j) < aux[i]
                counts![p.idx] += (j - mid - 1);
                pairs[k] = aux[i];
                i += 1;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/387969052/
```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```swift
class Solution {
    func coinChange(_ coins: [Int], _ amount: Int) -> Int {
        // dp[i] = 凑成总金额 i 所需的最少的硬币个数
        var dp = Array(repeating: -1, count: amount + 1);
        dp[0] = 0;
        if (amount > 0) {
            for i in 1...amount {
                var res = Int.max;
                // c       = 选择放入的硬币
                // i-c     = 剩余总金额
                // dp[i-c] = 凑成剩余总金额所需的最少的硬币个数
                for c in coins {
                    let x = i - c;
                    if (x >= 0 && dp[x] != -1) {
                        res = min(res, dp[x] + 1);
                    }
                }
                dp[i] = (res == Int.max ? -1 : res);
            }
        }
        return dp[amount];
    }
}
// https://leetcode.cn/submissions/detail/385794660/
```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```swift
extension TreeNode: Hashable {
    public func hash(into hasher: inout Hasher) {
        hasher.combine(val)
        hasher.combine(left)
        hasher.combine(right)
    }

    public static func ==(lhs: TreeNode, rhs: TreeNode) -> Bool {
        if lhs === rhs {
            return true
        }
        if type(of: lhs) != type(of: rhs) {
            return false
        }
        if lhs.val != rhs.val {
            return false
        }
        if lhs.left != rhs.left {
            return false
        }
        if lhs.right != rhs.right {
            return false
        }
        return true
    }
}

class Solution {
    private var memo: [TreeNode: Int] = [:];

    func rob(_ root: TreeNode?) -> Int {
        if (root == nil) {
            return 0;
        }
        if (memo[root!] == nil) {
            // 偷 root
            var sp1 = root!.val;
            if (root!.left != nil) {
                sp1 += rob(root!.left!.left) + rob(root!.left!.right);
            }
            if (root!.right != nil) {
                sp1 += rob(root!.right!.left) + rob(root!.right!.right);
            }
            // 不偷 root
            let sp2 = rob(root!.left) + rob(root!.right);
            memo[root!] = max(sp1, sp2);
        }
        return memo[root!]!;
    }
}
// https://leetcode.cn/submissions/detail/387980974/
```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```swift
class Solution {
    func reverseString(_ s: inout [Character]) {
        var i = 0;
        var j = s.count - 1;
        while (i < j) {
            s.swapAt(i, j);
            i += 1;
            j -= 1;
        }
    }
}
// https://leetcode.cn/submissions/detail/385432325/
```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```swift
// TODO
```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```swift
class Solution {
    func decodeString(_ s: String) -> String {
        let chs = [Character](s);
        var stack: [String] = [];
        let n = chs.count;
        var i = 0;
        while (i < n) {
            // Digits
            var digitArray: [Character] = [];
            while (i < n && chs[i].isNumber) {
                digitArray.append(chs[i]);
                i += 1;
            }
            if (digitArray.count > 0) {
                stack.append(String(digitArray));
            }
            // [
            while (i < n && chs[i] == "[") {
                stack.append("[");
                i += 1;
            }
            // Letters
            var letterArray: [Character] = [];
            while (i < n && chs[i].isLetter) {
                letterArray.append(chs[i]);
                i += 1;
            }
            if (letterArray.count > 0) {
                stack.append(String(letterArray));
            }
            // ]
            while (i < n && chs[i] == "]") {
                var letterString = "";
                while (stack.count > 0) {
                    let x = stack.removeLast();
                    if (x == "[") {
                        break;
                    }
                    letterString = x + letterString;
                }
                let digitString = stack.removeLast();
                var repeated = "";
                for _ in 1...Int(digitString)! {
                    repeated += letterString;
                }
                stack.append(repeated);
                i += 1;
            }
        }
        return stack.joined();
    }
}
// https://leetcode.cn/submissions/detail/387239912/
```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```swift
class Solution {
    func canPartition(_ nums: [Int]) -> Bool {
        let sum = nums.reduce(0, +);
        if (sum % 2 == 1) {
            return false;
        }
        return hasSubsetSum(nums, sum / 2);
    }

    // 数组 nums 是否存在和为 sum 的子集
    private func hasSubsetSum(_ nums: [Int], _ sum: Int) -> Bool {
        let n = nums.count;
        // dp[i][j] = 子数组 nums[0..i-1] 是否存在和为 j 的子集
        var dp = Array(repeating: Array(repeating: false, count: sum + 1), count: n + 1);
        // 和为 0
        for i in 1...n {
            dp[i][0] = true;
        }
        // 空数组
        for j in 1...sum {
            dp[0][j] = false;
        }
        // 空集的和为 0，空集是任何数组的子集，包括空数组
        dp[0][0] = true;
        for i in 1...n {
            for j in 1...sum {
                let x = nums[i - 1];
                if (j >= x) {
                    // 包含 x
                    // 当 i >= 1, j = x 时，dp[i - 1][j - x] = dp[i - 1][0]
                    // 因为存在子集 {x} 的和为 j，
                    // 所以定义 dp[i][0] = true (i >= 0)
                    let sp1 = dp[i - 1][j - x];
                    // 不包含 x
                    // 当 i = 1 时，dp[i - 1][j] = dp[0][j]
                    // 因为空数组没有子集的和为 j >= 1
                    // 所以定义 dp[0][j] = false (j >= 1)
                    let sp2 = dp[i - 1][j];
                    dp[i][j] = sp1 || sp2;
                } else {
                    // 不包含 x
                    dp[i][j] = dp[i - 1][j];
                }
            }
        }
        return dp[n][sum];
    }
}
// https://leetcode.cn/submissions/detail/387750751/
```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```swift
class Solution {
    func eraseOverlapIntervals(_ intervals: [[Int]]) -> Int {
        intervals.count - maxNonOverlappingIntervals(intervals);
    }

    // 返回区间数组 intervals 无重叠区间的最大数量
    private func maxNonOverlappingIntervals(_ intervals: [[Int]]) -> Int {
        let sortedIntervals = intervals.sorted { a, b in
            a[1] < b[1]
        };
        var count = 0;
        var minEnd = Int.min;
        for interval in sortedIntervals {
            let start = interval[0];
            let end = interval[1];
            if (start < minEnd) {
                continue;
            }
            count += 1;
            minEnd = end;
        }
        return count;
    }
}
// https://leetcode.cn/submissions/detail/385543314/
```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```swift
class Solution {
    func findAnagrams(_ s: String, _ p: String) -> [Int] {
        let schs = [Character](s), pchs = [Character](p);
        var need: [Character: Int] = [:];
        for ch in pchs {
            need[ch] = (need[ch] ?? 0) + 1;
        }
        var window: [Character: Int] = [:];
        var valid = 0;
        var ans: [Int] = [];
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        var left = 0;
        var right = 0;
        while (right < schs.count) {
            let add = schs[right];
            right += 1;
            if (need[add] != nil) {
                window[add] = (window[add] ?? 0) + 1;
                if (window[add] == need[add]) {
                    valid += 1;
                }
            }
            if (valid == need.count) {
                while (left < right - pchs.count) {
                    let del = schs[left];
                    left += 1;
                    if (need[del] != nil) {
                        if (window[del] == need[del]) {
                            valid -= 1;
                        }
                        window[del]! -= 1;
                    }
                }
                if (valid == need.count) {
                    ans.append(left);
                }
            }
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/385516298/
```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```swift
class Solution {
    func addTwoNumbers(_ l1: ListNode?, _ l2: ListNode?) -> ListNode? {
        var ptr1 = reverseList(l1), ptr2 = reverseList(l2);
        let dummyHead = ListNode();
        var ptr = dummyHead;
        var carry = 0;
        while (ptr1 != nil || ptr2 != nil || carry > 0) {
            var sum = carry;
            if (ptr1 != nil) {
                sum += ptr1!.val;
                ptr1 = ptr1!.next;
            }
            if (ptr2 != nil) {
                sum += ptr2!.val;
                ptr2 = ptr2!.next;
            }
            ptr.next = ListNode(sum % 10);
            ptr = ptr.next!;
            carry = sum / 10;
        }
        reverseList(ptr1);
        reverseList(ptr2);
        return reverseList(dummyHead.next);
    }

    @discardableResult
    private func reverseList(_ head: ListNode?) -> ListNode? {
        var reverseHead: ListNode?;
        var ptr = head;
        while (ptr != nil) {
            let x = ptr!.next;
            ptr!.next = reverseHead;
            reverseHead = ptr;
            ptr = x;
        }
        return reverseHead;
    }
}
// https://leetcode.cn/submissions/detail/384881890/
```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```swift
class Solution {
    func deleteNode(_ root: TreeNode?, _ key: Int) -> TreeNode? {
        if (root == nil) {
            return nil;
        }
        if (key < root!.val) {
            root!.left = deleteNode(root!.left, key);
        } else if (key > root!.val) {
            root!.right = deleteNode(root!.right, key);
        } else {
            if (root!.left == nil) {
                return root!.right;
            }
            if (root!.right == nil) {
                return root!.left;
            }
            let newRoot = findMin(root!.right!);
            newRoot.right = deleteMin(root!.right!);
            newRoot.left = root!.left;
            return newRoot;
        }
        return root;
    }

    private func findMin(_ root: TreeNode) -> TreeNode {
        if (root.left == nil) {
            return root;
        }
        return findMin(root.left!);
    }

    private func deleteMin(_ root: TreeNode) -> TreeNode? {
        if (root.left == nil) {
            return root.right;
        }
        root.left = deleteMin(root.left!);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/385075346/
```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```swift
class Solution {
    func findMinArrowShots(_ points: [[Int]]) -> Int {
        maxNonOverlappingIntervals(points);
    }

    // 返回区间数组 intervals 无重叠区间的最大数量
    private func maxNonOverlappingIntervals(_ intervals: [[Int]]) -> Int {
        let sortedIntervals = intervals.sorted { a, b in
            a[1] < b[1]
        };
        var count = 0;
        var minEnd = Int.min;
        for interval in sortedIntervals {
            let start = interval[0];
            let end = interval[1];
            if (start <= minEnd) {
                continue;
            }
            count += 1;
            minEnd = end;
        }
        return count;
    }
}
// https://leetcode.cn/submissions/detail/385543828/
```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```swift
import Foundation

class Node {
    public var key: Int;
    public var val: Int;
    public var freq: Int;
    public var prev: Node?;
    public var next: Node?;

    init(_ key: Int, _ val: Int, _ freq: Int, _ prev: Node? = nil, _ next: Node? = nil) {
        self.key = key;
        self.val = val;
        self.freq = freq;
        self.prev = prev;
        self.next = next;
    }
}

struct DoublyLinkedList {
    private var first: Node? = nil;
    private var last: Node? = nil;
    private var n = 0;

    public mutating func addLast(_ x: Node) {
        if (n == 0) {
            first = x;
            last = x;
        } else {
            last!.next = x;
            x.prev = last;
            last = x;
        }
        n += 1;
    }

    @discardableResult
    public mutating func removeFirst() -> Node {
        let oldFirst = first;
        if (n == 1) {
            first = nil;
            last = nil;
        } else {
            first = first!.next;
            first!.prev = nil;
            oldFirst!.next = nil;
        }
        n -= 1;
        return oldFirst!;
    }

    @discardableResult
    public mutating func removeLast() -> Node {
        let oldLast = last;
        if (n == 1) {
            first = nil;
            last = nil;
        } else {
            last = last!.prev;
            last!.next = nil;
            oldLast!.prev = nil;
        }
        n -= 1;
        return oldLast!;
    }

    public mutating func remove(_ x: Node) {
        if (x === first) {
            removeFirst();
        } else if (x === last) {
            removeLast();
        } else {
            x.prev!.next = x.next;
            x.next!.prev = x.prev;
            x.prev = nil;
            x.next = nil;
            n -= 1;
        }
    }

    public func empty() -> Bool {
        first == nil;
    }
}

class LFUCache {
    private var capacity: Int;
    private var minFreq = 0;
    private var keyToNode: [Int: Node] = [:];
    private var freqToList: [Int: DoublyLinkedList] = [:];

    init(_ capacity: Int) {
        self.capacity = capacity;
    }

    func get(_ key: Int) -> Int {
        if (contains(key)) {
            return touchCache(key, nil);
        }
        return -1;
    }

    func put(_ key: Int, _ value: Int) {
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

    private func contains(_ key: Int) -> Bool {
        keyToNode[key] != nil;
    }

    private func full() -> Bool {
        keyToNode.count == capacity;
    }

    private func addCache(_ key: Int, _ val: Int) {
        let x = Node(key, val, 1);
        keyToNode[key] = x;
        freqToList[1] = freqToList[1] ?? DoublyLinkedList();
        freqToList[1]!.addLast(x);
        minFreq = 1;
    }

    private func removeCache() {
        keyToNode.removeValue(forKey: freqToList[minFreq]!.removeFirst().key);
        if (freqToList[minFreq]!.empty()) {
            freqToList.removeValue(forKey: minFreq);
        }
    }

    @discardableResult
    private func touchCache(_ key: Int, _ val: Int?) -> Int {
        let x = keyToNode[key]!;
        if (val != nil) {
            x.val = val!;
        }
        let oldFreq = x.freq;
        let newFreq = oldFreq + 1;
        x.freq = newFreq;
        freqToList[oldFreq]!.remove(x);
        if (freqToList[oldFreq]!.empty()) {
            freqToList.removeValue(forKey: oldFreq);
            if (minFreq == oldFreq) {
                minFreq = newFreq;
            }
        }
        freqToList[newFreq] = freqToList[newFreq] ?? DoublyLinkedList();
        freqToList[newFreq]!.addLast(x);
        return x.val;
    }
}
// https://leetcode.cn/submissions/detail/387974541/
```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```swift
class Solution {
    private var ans = 0;

    func reversePairs(_ nums: [Int]) -> Int {
        var copy = nums;
        var aux = nums;
        sort(&copy, 0, copy.count - 1, &aux);
        return ans;
    }

    private func sort(_ nums: inout [Int], _ lo: Int, _ hi: Int, _ aux: inout [Int]) {
        if (lo >= hi) {
            return;
        }
        let mid = lo + (hi - lo) / 2;
        sort(&nums, lo, mid, &aux);
        sort(&nums, mid + 1, hi, &aux);
        merge(&nums, lo, mid, hi, &aux);
    }

    private func merge(_ nums: inout [Int], _ lo: Int, _ mid: Int, _ hi: Int, _ aux: inout [Int]) {
        for k in lo...hi {
            aux[k] = nums[k];
        }
        ans += countReversePairs(nums, lo, mid, hi);
        var i = lo, j = mid + 1;
        for k in lo...hi {
            if (i > mid || (j <= hi && aux[j] < aux[i])) {
                nums[k] = aux[j];
                j += 1;
            } else {
                nums[k] = aux[i];
                i += 1;
            }
        }
    }

    private func countReversePairs(_ nums: [Int], _ lo: Int, _ mid: Int, _ hi: Int) -> Int {
        var res = 0;
        //     nums[i]      > 2*nums[j]
        // (1) nums[i]      > 2*nums[mid+1..j]
        // (2) nums[i..mid] > 2*nums[j]
        //
        //     nums[i]     <= 2*nums[j]
        // (1) nums[i]     <= 2*nums[j..hi]
        // (2) nums[lo..i] <= 2*nums[j]
        var i = lo, j = mid + 1;
        while (i <= mid && j <= hi) {
            if (isReversePair(nums, i, j)) {
                res += (mid - i + 1);
                j += 1;
            } else {
                i += 1;
            }
        }
        return res;
    }

    private func isReversePair(_ nums: [Int], _ i: Int, _ j: Int) -> Bool {
        i < j && nums[i] > 2 * nums[j];
    }
}
// https://leetcode.cn/submissions/detail/385989466/
```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```swift
class Solution {
    private var memo: [String: Int] = [:];

    func findTargetSumWays(_ nums: [Int], _ target: Int) -> Int {
        let sum = nums.reduce(0, +);
        if (abs(target) > sum) {
            return 0;
        }
        return findTargetSumWays(nums, nums.count - 1, target);
    }

    // 子数组 nums[0..i] 目标和为 target 的不同表达式的数目
    private func findTargetSumWays(_ nums: [Int], _ i: Int, _ target: Int) -> Int {
        if (i < 0) {
            return target == 0 ? 1 : 0;
        }
        let key = "\(i),\(target)";
        if (memo[key] == nil) {
            let x = nums[i];
            // x 前添加 + 号
            // sum(nums[0..i-1]) = target - x
            let sp1 = findTargetSumWays(nums, i - 1, target - x);
            // x 前添加 - 号
            // sum(nums[0..i-1]) = target + x
            let sp2 = findTargetSumWays(nums, i - 1, target + x);
            memo[key] = sp1 + sp2;
        }
        return memo[key]!;
    }
}
// https://leetcode.cn/submissions/detail/385960656/
```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```swift
class Solution {
    func nextGreaterElement(_ nums1: [Int], _ nums2: [Int]) -> [Int] {
        let greater = nextGreaterElement(nums2);
        var valueToGreater: [Int: Int] = [:];
        for (index, value) in nums2.enumerated() {
            valueToGreater[value] = greater[index];
        }
        var ans: [Int] = [];
        for value in nums1 {
            ans.append(valueToGreater[value]!);
        }
        return ans;
    }

    private func nextGreaterElement(_ nums: [Int]) -> [Int] {
        let n = nums.count;
        var res = nums;
        var minMonoStack: [Int] = [];
        for i in stride(from: n - 1, through: 0, by: -1) {
            let x = nums[i];
            while (!minMonoStack.isEmpty && minMonoStack.last! < x) {
                minMonoStack.removeLast();
            }
            res[i] = minMonoStack.isEmpty ? -1 : minMonoStack.last!;
            minMonoStack.append(x);
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/386755168/
```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```swift
class Solution {
    func nextGreaterElements(_ nums: [Int]) -> [Int] {
        let n = nums.count;
        var ans = nums;
        var minMonoStack: [Int] = [];
        for i in stride(from: 2 * n - 1, through: 0, by: -1) {
            let k = i % n;
            let x = nums[k];
            while (!minMonoStack.isEmpty && minMonoStack.last! <= x) {
                minMonoStack.removeLast();
            }
            ans[k] = minMonoStack.isEmpty ? -1 : minMonoStack.last!;
            minMonoStack.append(x);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/386755885/
```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```swift
class Solution {
    func fib(_ n: Int) -> Int {
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return 1;
        }
        var dp = Array(repeating: 0, count: n + 1);
        dp[0] = 0;
        dp[1] = 1;
        for i in 2...n {
            dp[i] = dp[i - 1] + dp[i - 2];
        }
        return dp[n];
    }
}
// https://leetcode.cn/submissions/detail/384861495/
```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```swift
class Solution {
    func longestPalindromeSubseq(_ s: String) -> Int {
        let chs = [Character](s);
        let n = chs.count;
        // dp[i][j] = 子串 s[i..j] 的最长回文子序列的长度
        var dp = Array(repeating: Array(repeating: 0, count: n), count: n);
        // 遍历对角线
        for i in 0...n - 1 {
            dp[i][i] = 1;
        }
        // 遍历上三角形
        for i in stride(from: n - 2, through: 0, by: -1) {
            for j in i + 1...n - 1 {
                if (chs[i] == chs[j]) {
                    // s[i][i+1..j-1][j]
                    // s   [i+1..j-1]
                    dp[i][j] = dp[i + 1][j - 1] + 2;
                } else {
                    // s[i..j-1][j]
                    // s[i..j-1]
                    let sp1 = dp[i][j - 1];
                    // s[i][i+1..j]
                    // s   [i+1..j]
                    let sp2 = dp[i + 1][j];
                    dp[i][j] = max(sp1, sp2);
                }
            }
        }
        return dp[0][n - 1];
    }
}
// https://leetcode.cn/submissions/detail/387506894/
```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```swift
class Solution {
    func change(_ amount: Int, _ coins: [Int]) -> Int {
        if (amount == 0) {
            return 1;
        }
        let n = coins.count;
        // dp[i][j] = 使用硬币 coins[0..i-1] 凑成总金额 j 的组合数
        var dp = Array(repeating: Array(repeating: 0, count: amount + 1), count: n + 1);
        // 总金额为 0
        for i in 1...n {
            dp[i][0] = 1;
        }
        // 硬币数为 0
        for j in 1...amount {
            dp[0][j] = 0;
        }
        dp[0][0] = 1;
        for i in 1...n {
            for j in 1...amount {
                let x = coins[i - 1];
                if (j >= x) {
                    let sp1 = dp[i - 1][j]; // 包含    0 个硬币 x
                    let sp2 = dp[i][j - x]; // 包含 >= 1 个硬币 x
                    dp[i][j] = sp1 + sp2;
                    // 注意
                    // dp[i][j - x] = 包含 >= 1 个硬币 x
                    // dp[i-1][j-x] = 包含    1 个硬币 x
                    // 举例 amount = 79, coins = [1, 2, 5]
                    // dp[2][79] = 包含    0 个硬币 5，79 = 0 x 5 + 79，剩余 79 只能从 [1, 2] 凑
                    // dp[2][74] = 包含    1 个硬币 5，79 = 1 x 5 + 74，剩余 74 只能从 [1, 2] 凑
                    // dp[3][74] = 包含 >= 1 个硬币 5，79 = 1 x 5 + 74，剩余 74 可以从 [1, 2, 5] 凑
                } else {
                    // 不包含硬币 x
                    dp[i][j] = dp[i - 1][j];
                }
            }
        }
        return dp[n][amount];
    }
}
// https://leetcode.cn/submissions/detail/385799062/
```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```swift
class Solution {
    private var sum = 0;

    func convertBST(_ root: TreeNode?) -> TreeNode? {
        dfs(root);
        return root;
    }

    private func dfs(_ root: TreeNode?) {
        if (root == nil) {
            return;
        }
        dfs(root!.right);
        sum += root!.val;
        root!.val = sum;
        dfs(root!.left);
    }
}
// https://leetcode.cn/submissions/detail/384994478/
```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```swift
// rootLP = 穿过根节点的最长路径（左右子树的最大深度之和）
// rootLP(root) = maxDepth(root.left) + maxDepth(root.right)
// diameter = 所有子树的 rootLP 的最大值
// diameter(root) = max({rootLP(subtree) | subtree 是 root 的任意子树})
class Solution {
    private var ans = 0;

    func diameterOfBinaryTree(_ root: TreeNode?) -> Int {
        maxDepth(root);
        return ans;
    }

    @discardableResult
    private func maxDepth(_ root: TreeNode?) -> Int {
        if (root == nil) {
            return 0;
        }
        let left = maxDepth(root!.left);
        let right = maxDepth(root!.right);
        ans = max(ans, left + right);
        return 1 + max(left, right);
    }
}
// https://leetcode.cn/submissions/detail/384928600/
```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```swift
class Solution {
    func checkInclusion(_ s1: String, _ s2: String) -> Bool {
        let chs2 = [Character](s2), chs1 = [Character](s1);
        var need: [Character: Int] = [:];
        for ch in chs1 {
            need[ch] = (need[ch] ?? 0) + 1;
        }
        var window: [Character: Int] = [:];
        var valid = 0;
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        var left = 0;
        var right = 0;
        while (right < chs2.count) {
            let add = chs2[right];
            right += 1;
            if (need[add] != nil) {
                window[add] = (window[add] ?? 0) + 1;
                if (window[add] == need[add]) {
                    valid += 1;
                }
            }
            if (valid == need.count) {
                while (left < right - chs1.count) {
                    let del = chs2[left];
                    left += 1;
                    if (need[del] != nil) {
                        if (window[del] == need[del]) {
                            valid -= 1;
                        }
                        window[del]! -= 1;
                    }
                }
                if (valid == need.count) {
                    return true;
                }
            }
        }
        return false;
    }
}
// https://leetcode.cn/submissions/detail/385518118/
```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```swift
import Foundation

class Solution {
    private var memo: [[Int?]] = [];

    func minDistance(_ word1: String, _ word2: String) -> Int {
        let n1 = word1.count, n2 = word2.count;
        memo = Array(repeating: Array(repeating: nil, count: n2), count: n1);
        return minDistance([Character](word1), n1 - 1, [Character](word2), n2 - 1);
    }

    // 子串 s1[0..i] s2[0..j] 的最小删除步数
    private func minDistance(_ s1: [Character], _ i: Int, _ s2: [Character], _ j: Int) -> Int {
        if (i < 0) {
            // 删除 s2[0..j]
            // s1""
            // s2[0..j]
            return j + 1;
        }
        if (j < 0) {
            // 删除 s1[0..i]
            // s1[0..i]
            // s2""
            return i + 1;
        }
        if (memo[i][j] == nil) {
            if (s1[i] == s2[j]) {
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                memo[i][j] = minDistance(s1, i - 1, s2, j - 1);
            } else {
                // 删除 s1[i] s2[j]
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                let sp1 = minDistance(s1, i - 1, s2, j - 1) + 2;
                // 删除 s2[j]
                // s1[0..i]
                // s2[0..j-1][j]
                let sp2 = minDistance(s1, i, s2, j - 1) + 1;
                // 删除 s1[i]
                // s1[0..i-1][i]
                // s2[0..j]
                let sp3 = minDistance(s1, i - 1, s2, j) + 1;
                memo[i][j] = min(sp1, sp2, sp3);
            }
        }
        return memo[i][j]!;
    }
}
// https://leetcode.cn/submissions/detail/387511451/
```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```swift
class Solution {
    func mergeTrees(_ root1: TreeNode?, _ root2: TreeNode?) -> TreeNode? {
        if (root1 == nil) {
            return root2;
        }
        if (root2 == nil) {
            return root1;
        }
        let mRoot = TreeNode(root1!.val + root2!.val);
        mRoot.left = mergeTrees(root1!.left, root2!.left);
        mRoot.right = mergeTrees(root1!.right, root2!.right);
        return mRoot;
    }
}
// https://leetcode.cn/submissions/detail/384991903/
```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```swift
class Solution {
    private var ans: [TreeNode] = [];
    private var counter: [String: Int] = [:];

    func findDuplicateSubtrees(_ root: TreeNode?) -> [TreeNode?] {
        postorder(root);
        return ans;
    }

    @discardableResult
    private func postorder(_ root: TreeNode?) -> String {
        if (root == nil) {
            return "#";
        }
        let left = postorder(root!.left);
        let right = postorder(root!.right);
        let res = left + "," + right + "," + String(root!.val);
        counter[res] = (counter[res] ?? 0) + 1;
        if (counter[res] == 2) {
            ans.append(root!);
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/384927057/
```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```swift
class Solution {
    func constructMaximumBinaryTree(_ nums: [Int]) -> TreeNode? {
        constructMaximumBinaryTree(nums, 0, nums.count - 1);
    }

    private func constructMaximumBinaryTree(_ nums: [Int], _ lo: Int, _ hi: Int) -> TreeNode? {
        if (lo > hi) {
            return nil;
        }
        var maxIndex = lo;
        for i in lo...hi {
            if (nums[i] > nums[maxIndex]) {
                maxIndex = i;
            }
        }
        let root = TreeNode(nums[maxIndex]);
        root.left = constructMaximumBinaryTree(nums, lo, maxIndex - 1);
        root.right = constructMaximumBinaryTree(nums, maxIndex + 1, hi);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/384966110/
```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```swift
class Solution {
    private static let LAND = 1;
    private static let WATER = 0;
    private var area = 0;

    func maxAreaOfIsland(_ grid: [[Int]]) -> Int {
        var copy = grid;
        var ans = 0;
        for row in 0...copy.count - 1 {
            for col in 0...copy[0].count - 1 {
                if (copy[row][col] == Solution.LAND) {
                    area = 0;
                    floodFill(&copy, row, col);
                    ans = max(ans, area);
                }
            }
        }
        return ans;
    }

    private func floodFill(_ grid: inout [[Int]], _ row: Int, _ col: Int) {
        if (row < 0 || row >= grid.count || col < 0 || col >= grid[0].count
                || grid[row][col] == Solution.WATER) {
            return;
        }
        area += 1;
        grid[row][col] = Solution.WATER;
        floodFill(&grid, row - 1, col);
        floodFill(&grid, row + 1, col);
        floodFill(&grid, row, col - 1);
        floodFill(&grid, row, col + 1);
    }
}
// https://leetcode.cn/submissions/detail/387741960/
```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```swift
class Solution {
    private var used = 0;
    private var target = 0;
    private var pathSums: [Int] = [];
    private var memo: [Int: Bool] = [:];

    func canPartitionKSubsets(_ nums: [Int], _ k: Int) -> Bool {
        let sum = nums.reduce(0, +);
        if (sum % k != 0) {
            return false;
        }
        target = sum / k;
        pathSums = Array(repeating: 0, count: k);
        return backtrack(nums, k, 0, -1);
    }

    // 遍历『决策森林』的 k 棵『决策树』
    // 一棵『决策树』的『路径』代表一个『等和子集』
    // tree = 第几棵『决策树』，取 [0..k-1] 为值
    // edge =『决策树』的『边』，取数组 nums 的索引为值
    // pathSums[tree] = 第几棵『决策树』的『路径和』
    private func backtrack(_ nums: [Int], _ k: Int, _ tree: Int, _ edge: Int) -> Bool {
        var res = false;
        if (tree == k) {
            res = true;
        } else if (pathSums[tree] == target) {
            // 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            // 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            // 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            // 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            // 因为 C 的可选『边』是一样的
            if (memo[used] == nil) {
                // 遍历下一棵『决策树』
                memo[used] = backtrack(nums, k, tree + 1, -1);
            }
            res = memo[used]!;
        } else {
            // 通过去重，对同一棵树，优化『边』的遍历，避免『边+边』重复
            // 例如 1 和 2 分别是两条『边』，[1->2] 和 [2->1] 是重复的
            var e = edge + 1;
            while (e < nums.count) {
                let x = nums[e];
                // 检查第 edge 位是否为 1
                // 即 nums[edge] 是否已经被其他『树』使用
                if (((used >> e) & 1 != 1)
                        && pathSums[tree] + x <= target) {
                    pathSums[tree] += x;
                    //『或』运算，将第 edge 位修改为 1
                    used |= (1 << e);
                    res = backtrack(nums, k, tree, e);
                    if (res) {
                        break;
                    }
                    pathSums[tree] -= x;
                    //『异或』运算，将第 edge 位恢复为 0
                    used ^= (1 << e);
                }
                e += 1;
            }
        }
        return res;
    }
}
// https://leetcode.cn/submissions/detail/387962177/
```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```swift
class Solution {
    func searchBST(_ root: TreeNode?, _ val: Int) -> TreeNode? {
        if (root == nil) {
            return nil;
        }
        if (val < root!.val) {
            return searchBST(root!.left, val);
        }
        if (root!.val < val) {
            return searchBST(root!.right, val);
        }
        return root;
    }
}
// https://leetcode.cn/submissions/detail/384992957/
```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```swift
class Solution {
    func insertIntoBST(_ root: TreeNode?, _ val: Int) -> TreeNode? {
        if (root == nil) {
            return TreeNode(val);
        }
        if (val < root!.val) {
            root!.left = insertIntoBST(root!.left, val);
        }
        if (val > root!.val) {
            root!.right = insertIntoBST(root!.right, val);
        }
        return root;
    }
}
// https://leetcode.cn/submissions/detail/384994054/
```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```swift
class Solution {
    func search(_ nums: [Int], _ target: Int) -> Int {
        var lo = 0, hi = nums.count - 1;
        while (lo <= hi) {
            let mid = lo + (hi - lo) / 2;
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
// https://leetcode.cn/submissions/detail/384830033/
```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```swift
class Solution {
    private var memo: [[Int?]] = [];
    private var sum1: [Int] = [];
    private var sum2: [Int] = [];

    func minimumDeleteSum(_ s1: String, _ s2: String) -> Int {
        let chs1 = [Character](s1), chs2 = [Character](s2);
        let n1 = chs1.count, n2 = chs2.count;
        memo = Array(repeating: Array(repeating: nil, count: n2), count: n1);
        sum1 = prefixSum(chs1);
        sum2 = prefixSum(chs2);
        return minimumDeleteSum(chs1, n1 - 1, chs2, n2 - 1);
    }

    // 子串 s1[0..i] s2[0..j] 的最小 ASCII 删除和
    private func minimumDeleteSum(_ s1: [Character], _ i: Int, _ s2: [Character], _ j: Int) -> Int {
        if (i < 0 && j < 0) {
            return 0;
        }
        if (i < 0) {
            // 删除 s2[0..j]
            // s1""
            // s2[0..j]
            return sum2[j];
        }
        if (j < 0) {
            // 删除 s1[0..i]
            // s1[0..i]
            // s2""
            return sum1[i];
        }
        if (memo[i][j] == nil) {
            if (s1[i] == s2[j]) {
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                memo[i][j] = minimumDeleteSum(s1, i - 1, s2, j - 1);
            } else {
                // 删除 s1[i] s2[j]
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                let sp1 = minimumDeleteSum(s1, i - 1, s2, j - 1) + Int(s1[i].asciiValue!) + Int(s2[j].asciiValue!);
                // 删除 s2[j]
                // s1[0..i]
                // s2[0..j-1][j]
                let sp2 = minimumDeleteSum(s1, i, s2, j - 1) + Int(s2[j].asciiValue!);
                // 删除 s1[i]
                // s1[0..i-1][i]
                // s2[0..j]
                let sp3 = minimumDeleteSum(s1, i - 1, s2, j) + Int(s1[i].asciiValue!);
                memo[i][j] = min(sp1, sp2, sp3);
            }
        }
        return memo[i][j]!;
    }

    private func prefixSum(_ s: [Character]) -> [Int] {
        let n = s.count;
        var sum = Array(repeating: 0, count: n);
        sum[0] = Int(s[0].asciiValue!);
        if (n > 1) {
            for i in 1...n - 1 {
                sum[i] = sum[i - 1] + Int(s[i].asciiValue!);
            }
        }
        return sum;
    }
}
// https://leetcode.cn/submissions/detail/387512752/
```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```swift
class Solution {
    func maxProfit(_ prices: [Int], _ fee: Int) -> Int {
        let n = prices.count;
        if (n == 1) {
            return 0;
        }
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        var dp = Array(repeating: Array(repeating: 0, count: 2), count: n);
        dp[0][0] = 0;
        dp[0][1] = -prices[0] - fee;
        for i in 1...n - 1 {
            // dp[i - 1][0]             >= dp[i - 1][0] - prices[i] - fee
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = max(dp[i - 1][0] - prices[i] - fee, dp[i - 1][1]);
        }
        return dp[n - 1][0];
    }
}
// https://leetcode.cn/submissions/detail/385800783/
```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```swift
class Solution {
    func dailyTemperatures(_ temperatures: [Int]) -> [Int] {
        let n = temperatures.count;
        var ans = Array(repeating: 0, count: n);
        var minMonoStack: [Int] = [];
        for i in stride(from: n - 1, through: 0, by: -1) {
            while (!minMonoStack.isEmpty && temperatures[minMonoStack.last!] <= temperatures[i]) {
                minMonoStack.removeLast();
            }
            ans[i] = minMonoStack.isEmpty ? 0 : minMonoStack.last! - i;
            minMonoStack.append(i);
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/386756480/
```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```swift
struct IndexMinPQ {
    private let maxN: Int;
    private var pq: [Int];
    private var qp: [Int];
    private var keys: [Int?];
    private var n = 0;

    init(_ maxN: Int) {
        self.maxN = maxN;
        keys = Array(repeating: nil, count: maxN + 1);
        pq = Array(repeating: -1, count: maxN + 1);
        qp = Array(repeating: -1, count: maxN + 1);
    }

    public var isEmpty: Bool {
        n == 0;
    }

    public var count: Int {
        n
    }

    public func contains(_ i: Int) -> Bool {
        qp[i] != -1;
    }

    public mutating func insert(_ i: Int, _ key: Int) {
        n += 1;
        qp[i] = n;
        pq[n] = i;
        keys[i] = key;
        swim(n);
    }

    public mutating func delMin() -> Int {
        let max = pq[1];
        exch(1, n);
        n -= 1;
        sink(1);
        qp[max] = -1;
        keys[max] = nil;
        pq[n + 1] = -1;
        return max;
    }

    public mutating func changeKey(_ i: Int, _ key: Int) {
        keys[i] = key;
        swim(qp[i]);
        sink(qp[i]);
    }

    private func less(_ i: Int, _ j: Int) -> Bool {
        keys[pq[i]]! < keys[pq[j]]!;
    }

    private mutating func exch(_ i: Int, _ j: Int) {
        pq.swapAt(i, j);
        qp[pq[i]] = i;
        qp[pq[j]] = j;
    }

    private mutating func swim(_ k: Int) {
        var k = k;
        while (k > 1 && less(k / 2, k)) {
            exch(k, k / 2);
            k = k / 2;
        }
    }

    private mutating func sink(_ k: Int) {
        var k = k;
        while (2 * k <= n) {
            var j = 2 * k;
            if (j < n && less(j, j + 1)) {
                j += 1;
            }
            if (!less(k, j)) {
                break;
            }
            exch(k, j);
            k = j;
        }
    }
}

struct DirectedEdge {
    public let from: Int;
    public let to: Int;
    public let weight: Int;

    init(_ from: Int, _ to: Int, _ weight: Int) {
        self.from = from;
        self.to = to;
        self.weight = weight;
    }
}

struct EdgeWeightedDigraph {
    public let V: Int;
    private var E = 0;
    private var adj: [[DirectedEdge]];

    init(_ V: Int) {
        self.V = V;
        adj = Array(repeating: [], count: V);
    }

    public mutating func addEdge(_ e: DirectedEdge) {
        adj[e.from].append(e);
        E += 1;
    }

    public func adj(_ v: Int) -> [DirectedEdge] {
        adj[v];
    }
}

struct DijkstraSP {
    private var distTo: [Int];
    private var pq: IndexMinPQ;

    init(_ G: EdgeWeightedDigraph, _ s: Int) {
        let V = G.V;
        distTo = Array(repeating: Int.max, count: V);
        distTo[s] = 0;
        pq = IndexMinPQ(V);
        pq.insert(s, distTo[s]);
        while (!pq.isEmpty) {
            let v = pq.delMin();
            relax(G, v);
        }
    }

    private mutating func relax(_ G: EdgeWeightedDigraph, _ v: Int) {
        for e in G.adj(v) {
            let w = e.to;
            if (distTo[w] > distTo[v] + e.weight) {
                distTo[w] = distTo[v] + e.weight;
                if (pq.contains(w)) {
                    pq.changeKey(w, distTo[w]);
                } else {
                    pq.insert(w, distTo[w]);
                }
            }
        }
    }

    public func distTo(_ v: Int) -> Int {
        distTo[v];
    }
}

class Solution {
    func networkDelayTime(_ times: [[Int]], _ n: Int, _ k: Int) -> Int {
        var graph = EdgeWeightedDigraph(n);
        for t in times {
            graph.addEdge(DirectedEdge(t[0] - 1, t[1] - 1, t[2]));
        }
        let spt = DijkstraSP(graph, k - 1);
        var maxTime = 0;
        for v in 0...n - 1 {
            maxTime = max(maxTime, spt.distTo(v));
        }
        return maxTime < Int.max ? maxTime : -1;
    }
}
// https://leetcode.cn/submissions/detail/387985305/
```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```swift
class Solution {
    private static let ZERO = 48;
    private static let NINE = 57;

    func openLock(_ deadends: [String], _ target: String) -> Int {
        var marked = Set(deadends);
        var queue = Deque<String>();
        let source = "0000";
        if (!marked.contains(source)) {
            marked.insert(source);
            queue.enqueue(source);
        }
        var count = 0;
        while (!queue.isEmpty) {
            let n = queue.count;
            for _ in 1...n {
                let s = queue.dequeue()!;
                if (s == target) {
                    return count;
                }
                for j in 0...3 {
                    let plus = plusOne(s, j);
                    if (!marked.contains(plus)) {
                        marked.insert(plus);
                        queue.enqueue(plus);
                    }
                    let minus = minusOne(s, j);
                    if (!marked.contains(minus)) {
                        marked.insert(minus);
                        queue.enqueue(minus);
                    }
                }
            }
            count += 1;
        }
        return -1;
    }

    private func plusOne(_ s: String, _ j: Int) -> String {
        var t = [Character](s);
        let code = t[j].asciiValue!;
        if (code == Solution.NINE) {
            t[j] = Character(UnicodeScalar(Solution.ZERO)!);
        } else {
            t[j] = Character(UnicodeScalar(code + 1));
        }
        return String(t);
    }

    private func minusOne(_ s: String, _ j: Int) -> String {
        var t = [Character](s);
        let code = t[j].asciiValue!;
        if (code == Solution.ZERO) {
            t[j] = Character(UnicodeScalar(Solution.NINE)!);
        } else {
            t[j] = Character(UnicodeScalar(code - 1));
        }
        return String(t);
    }
}

/*
  Deque (pronounced "deck"), a double-ended queue

  All enqueuing and dequeuing operations are O(1).
*/
public struct Deque<T> {
    private var array: [T?]
    private var head: Int
    private var capacity: Int
    private let originalCapacity: Int

    public init(_ capacity: Int = 10) {
        self.capacity = max(capacity, 1)
        originalCapacity = self.capacity
        array = [T?](repeating: nil, count: capacity)
        head = capacity
    }

    public var isEmpty: Bool {
        return count == 0
    }

    public var count: Int {
        return array.count - head
    }

    public mutating func enqueue(_ element: T) {
        array.append(element)
    }

    public mutating func enqueueFront(_ element: T) {
        if head == 0 {
            capacity *= 2
            let emptySpace = [T?](repeating: nil, count: capacity)
            array.insert(contentsOf: emptySpace, at: 0)
            head = capacity
        }

        head -= 1
        array[head] = element
    }

    public mutating func dequeue() -> T? {
        guard head < array.count, let element = array[head] else {
            return nil
        }

        array[head] = nil
        head += 1

        if capacity >= originalCapacity && head >= capacity * 2 {
            let amountToRemove = capacity + capacity / 2
            array.removeFirst(amountToRemove)
            head -= amountToRemove
            capacity /= 2
        }
        return element
    }

    public mutating func dequeueBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.removeLast()
        }
    }

    public func peekFront() -> T? {
        if isEmpty {
            return nil
        } else {
            return array[head]
        }
    }

    public func peekBack() -> T? {
        if isEmpty {
            return nil
        } else {
            return array.last!
        }
    }
}
// https://leetcode.cn/submissions/detail/387963947/
```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```swift
class Solution {
    private var bipartite = true;
    private var marked: [Bool] = [];
    private var color: [Bool] = [];

    func isBipartite(_ graph: [[Int]]) -> Bool {
        let n = graph.count;
        marked = Array(repeating: false, count: n);
        color = Array(repeating: false, count: n);
        for v in 0...n - 1 {
            if (!marked[v]) {
                dfs(graph, v);
                if (!bipartite) {
                    return false;
                }
            }
        }
        return true;
    }

    private func dfs(_ graph: [[Int]], _ v: Int) {
        marked[v] = true;
        for w in graph[v] {
            if (!bipartite) {
                return;
            }
            if (!marked[w]) {
                color[w] = !color[v];
                dfs(graph, w);
            } else if (color[w] == color[v]) {
                bipartite = false;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/387959123/
```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```swift
class Solution {
    private var ans: [[Int]] = [];
    private var path: [Int] = [];
    private var target = 0;

    func allPathsSourceTarget(_ graph: [[Int]]) -> [[Int]] {
        target = graph.count - 1;
        dfs(graph, 0);
        return ans;
    }

    private func dfs(_ graph: [[Int]], _ v: Int) {
        path.append(v);
        if (v == target) {
            ans.append(path);
        } else {
            for w in graph[v] {
                dfs(graph, w);
            }
        }
        path.removeLast();
    }
}
// https://leetcode.cn/submissions/detail/386028493/
```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```swift
class Solution {
    func isNStraightHand(_ hand: [Int], _ groupSize: Int) -> Bool {
        if (hand.count % groupSize != 0) {
            return false;
        }
        let sortedHand = hand.sorted();
        var counter: [Int: Int] = [:];
        for card in sortedHand {
            counter[card] = (counter[card] ?? 0) + 1;
        }
        for card in sortedHand {
            if (counter[card]! > 0) {
                for i in 0...groupSize - 1 {
                    let need = card + i;
                    let count = counter[need] ?? 0;
                    if (count == 0) {
                        return false;
                    }
                    counter[need] = count - 1;
                }
            }
        }
        return true;
    }
}
// https://leetcode.cn/submissions/detail/384841447/
```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```swift
class Solution {
    func minEatingSpeed(_ piles: [Int], _ h: Int) -> Int {
        var lo = 1;
        var hi = piles.max()!;
        var ans = lo;
        while (lo <= hi) {
            let mid = lo + (hi - lo) / 2;
            if (canFinish(piles, h, mid)) {
                ans = mid;
                hi = mid - 1;
            } else {
                lo = mid + 1;
            }
        }
        return ans;
    }

    // 当吃香蕉的速度为 k 时，是否能在 h 小时内吃完
    private func canFinish(_ piles: [Int], _ h: Int, _ k: Int) -> Bool {
        var hours = 0;
        for p in piles {
            hours += (p - 1) / k + 1;
        }
        return hours <= h;
    }
}
// https://leetcode.cn/submissions/detail/384833603/
```

## 876. 链表的中间结点

<https://leetcode-cn.com/problems/middle-of-the-linked-list/>

```swift
class Solution {
    func middleNode(_ head: ListNode?) -> ListNode? {
        var slow = head, fast = head;
        while (fast != nil && fast!.next != nil) {
            slow = slow!.next;
            fast = fast!.next!.next;
        }
        return slow;
    }
}
// https://leetcode.cn/submissions/detail/384867087/
```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```swift
class Solution {
    private var bipartite = true;
    private var marked: [Bool] = [];
    private var color: [Bool] = [];

    func possibleBipartition(_ n: Int, _ dislikes: [[Int]]) -> Bool {
        var graph: [[Int]] = Array(repeating: [], count: n);
        for d in dislikes {
            let v = d[0] - 1;
            let w = d[1] - 1;
            graph[v].append(w);
            graph[w].append(v);
        }
        return isBipartite(graph);
    }

    private func isBipartite(_ graph: [[Int]]) -> Bool {
        let n = graph.count;
        marked = Array(repeating: false, count: n);
        color = Array(repeating: false, count: n);
        for v in 0...n - 1 {
            if (!marked[v]) {
                dfs(graph, v);
                if (!bipartite) {
                    return false;
                }
            }
        }
        return true;
    }

    private func dfs(_ graph: [[Int]], _ v: Int) {
        marked[v] = true;
        for w in graph[v] {
            if (!bipartite) {
                return;
            }
            if (!marked[w]) {
                color[w] = !color[v];
                dfs(graph, w);
            } else if (color[w] == color[v]) {
                bipartite = false;
            }
        }
    }
}
// https://leetcode.cn/submissions/detail/387959975/
```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```swift
class Solution {
    private var valueToIndex: [Int: Int] = [:];

    func constructFromPrePost(_ preorder: [Int], _ postorder: [Int]) -> TreeNode? {
        for (index, value) in postorder.enumerated() {
            valueToIndex[value] = index;
        }
        return constructFromPrePost(preorder, 0, preorder.count - 1,
                postorder, 0, postorder.count - 1);
    }

    private func constructFromPrePost(_ preorder: [Int], _ preStart: Int, _ preEnd: Int,
                                      _ postorder: [Int], _ postStart: Int, _ postEnd: Int) -> TreeNode? {
        if (preStart > preEnd) {
            return nil;
        }
        let rootVal = preorder[preStart];
        let root = TreeNode(rootVal);
        if (preStart < preEnd) {
            let leftRootVal = preorder[preStart + 1];
            let postLeftRoot = valueToIndex[leftRootVal]!;
            let leftSize = postLeftRoot - postStart + 1;
            root.left = constructFromPrePost(preorder, preStart + 1, preStart + leftSize,
                    postorder, postStart, postLeftRoot);
            root.right = constructFromPrePost(preorder, preStart + leftSize + 1, preEnd,
                    postorder, postLeftRoot + 1, postEnd - 1);
        }
        return root;
    }
}
// https://leetcode.cn/submissions/detail/384981069/
```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```swift
class Solution {
    func sortArrayByParity(_ nums: [Int]) -> [Int] {
        // nums[0..i]   Even
        // nums[i..j]   Scanning
        // nums[j..n-1] Odd
        var copy = nums;
        let n = copy.count;
        var i = 0, j = n - 1;
        while (i < j) {
            while (i < j && copy[i] % 2 == 0) {
                i += 1;
            }
            while (i < j && copy[j] % 2 == 1) {
                j -= 1;
            }
            copy.swapAt(i, j);
        }
        return copy;
    }
}
// https://leetcode.cn/submissions/detail/386583014/
```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```swift
class Solution {
    func sortArray(_ nums: [Int]) -> [Int] {
        var copy = nums.shuffled();
        sort(&copy, 0, copy.count - 1);
        return copy;
    }

    private func sort(_ nums: inout [Int], _ lo: Int, _ hi: Int) {
        if (lo >= hi) {
            return;
        }
        let j = partition(&nums, lo, hi);
        sort(&nums, lo, j - 1);
        sort(&nums, j + 1, hi);
    }

    private func partition(_ nums: inout [Int], _ lo: Int, _ hi: Int) -> Int {
        let v = nums[lo];
        var i = lo, j = hi + 1;
        while (true) {
            i += 1;
            while (nums[i] < v) {
                if (i == hi) {
                    break;
                }
                i += 1;
            }
            j -= 1;
            while (v < nums[j]) {
                if (j == lo) {
                    break;
                }
                j -= 1;
            }
            if (i >= j) {
                break;
            }
            nums.swapAt(i, j);
        }
        nums.swapAt(lo, j);
        return j;
    }
}
// https://leetcode.cn/submissions/detail/384849886/
```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```swift
// 性质一 一个「合法」括号组合的左括号数量一定等于右括号数量
// 性质二 对于一个「合法」的括号字符串组合 p，必然对于
// 任何 0 <= i < len(p) 都有：子串 p[0..i] 中
// 左括号的数量都大于或等于右括号的数量
class Solution {
    func minAddToMakeValid(_ s: String) -> Int {
        var insertLeft = 0; // 已插入左括号的数量
        var needRight = 0; // 待插入右括号的数量
        for ch in s {
            if (ch == "(") {
                needRight += 1;
            }
            if (ch == ")") {
                needRight -= 1;
                // 性质二
                if (needRight == -1) {
                    // A).. -> A()..
                    //『必须立即』在位置 i 前插入 1 个左括号
                    // 否则，后续任何插入都不能使区间 [0..i] 的匹配有效
                    insertLeft += 1;
                    needRight = 0;
                }
            }
        }
        return insertLeft + needRight;
    }
}
// https://leetcode.cn/submissions/detail/385442576/
```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```swift
class Solution {
    func sortArrayByParityII(_ nums: [Int]) -> [Int] {
        var copy = nums;
        let n = copy.count;
        var i = 0, j = 1;
        while (true) {
            while (i <= n - 2 && copy[i] % 2 == 0) {
                i += 2;
            }
            while (j <= n - 1 && copy[j] % 2 == 1) {
                j += 2;
            }
            if (i > n - 2 || j > n - 1) {
                break;
            }
            copy.swapAt(i, j);
        }
        return copy;
    }
}
// https://leetcode.cn/submissions/detail/386583322/
```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```swift
class Solution {
    private var memo: [[Int?]] = [];

    func minFallingPathSum(_ matrix: [[Int]]) -> Int {
        let m = matrix.count;
        let n = matrix[0].count;
        memo = Array(repeating: Array(repeating: nil, count: n), count: m);
        var ans = Int.max;
        for col in 0...n - 1 {
            ans = min(ans, minFallingPathSum(matrix, m - 1, col));
        }
        return ans;
    }

    // 返回从 matrix[0][0..n-1] 到 matrix[row][col] 的最小下降路径和
    private func minFallingPathSum(_ matrix: [[Int]], _ row: Int, _ col: Int) -> Int {
        if (col < 0 || col >= matrix[0].count) {
            return Int.max;
        }
        if (row == 0) {
            return matrix[row][col];
        }
        if (memo[row][col] == nil) {
            let sp1 = minFallingPathSum(matrix, row - 1, col - 1);
            let sp2 = minFallingPathSum(matrix, row - 1, col);
            let sp3 = minFallingPathSum(matrix, row - 1, col + 1);
            memo[row][col] = min(sp1, sp2, sp3) + matrix[row][col];
        }
        return memo[row][col]!;
    }
}
// https://leetcode.cn/submissions/detail/415736274/
```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```swift
class Solution {
    func intervalIntersection(_ firstList: [[Int]], _ secondList: [[Int]]) -> [[Int]] {
        var ans: [[Int]] = [];
        var i = 0, j = 0;
        while (i < firstList.count && j < secondList.count) {
            let start1 = firstList[i][0];
            let end1 = firstList[i][1];
            let start2 = secondList[j][0];
            let end2 = secondList[j][1];
            if (end1 < start2) {
                // 不相交
                i += 1;
            } else if (end2 < start1) {
                // 不相交
                j += 1;
            } else {
                // 相交
                ans.append([max(start1, start2), min(end1, end2)]);
                if (end1 < end2) {
                    i += 1;
                } else {
                    j += 1;
                }
            }
        }
        return ans;
    }
}
// https://leetcode.cn/submissions/detail/385539111/
```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```swift
class Solution {
    private static let A: UInt8 = 97;

    func equationsPossible(_ equations: [String]) -> Bool {
        var uf = UF(26);
        for str in equations {
            let chs = [Character](str);
            if (chs[1] == "=") {
                let p = chs[0].asciiValue! - Solution.A;
                let q = chs[3].asciiValue! - Solution.A;
                uf.union(Int(p), Int(q));
            }
        }
        for str in equations {
            let chs = [Character](str);
            if (chs[1] == "!") {
                let p = chs[0].asciiValue! - Solution.A;
                let q = chs[3].asciiValue! - Solution.A;
                if (uf.connected(Int(p), Int(q))) {
                    return false;
                }
            }
        }
        return true;
    }
}

struct UF {
    private var parent: [Int];
    private var rank: [Int];
    private var count: Int;

    init(_ n: Int) {
        parent = Array(0...n - 1);
        rank = Array(repeating: 0, count: n);
        count = n;
    }

    public mutating func find(_ p: Int) -> Int {
        var t = p;
        while (t != parent[t]) {
            parent[t] = parent[parent[t]];
            t = parent[t];
        }
        return t;
    }

    public mutating func union(_ p: Int, _ q: Int) {
        let rootP = find(p);
        let rootQ = find(q);
        if (rootP != rootQ) {
            if (rank[rootP] < rank[rootQ]) {
                parent[rootP] = rootQ;
            } else if (rank[rootQ] < rank[rootP]) {
                parent[rootQ] = rootP;
            } else {
                parent[rootP] = rootQ;
                rank[rootQ] += 1;
            }
            count -= 1;
        }
    }

    public mutating func connected(_ p: Int, _ q: Int) -> Bool {
        find(p) == find(q);
    }
}
// https://leetcode.cn/submissions/detail/387966486/
```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```swift
class Solution {
    func shipWithinDays(_ weights: [Int], _ days: Int) -> Int {
        var lo = weights.max()!;
        var hi = weights.reduce(0, +);
        var ans = lo;
        while (lo <= hi) {
            let mid = lo + (hi - lo) / 2;
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
    private func canFinish(_ weights: [Int], _ days: Int, _ capacity: Int) -> Bool {
        var minDays = 0;
        var i = 0;
        let n = weights.count;
        while (i < n) {
            var sum = 0;
            while (i < n && sum + weights[i] <= capacity) {
                sum += weights[i];
                i += 1;
            }
            minDays += 1;
        }
        return minDays <= days;
    }
}
// https://leetcode.cn/submissions/detail/386587115/
```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```swift
class Solution {
    private static let LAND = 1;
    private static let WATER = 0;

    func numEnclaves(_ grid: [[Int]]) -> Int {
        var copy = grid;
        let m = copy.count;
        let n = copy[0].count;
        // 淹没与左右边界的陆地相连的岛屿
        for row in 0...m - 1 {
            floodFill(&copy, row, 0);
            floodFill(&copy, row, n - 1);
        }
        // 淹没与上下边界的陆地相连的岛屿
        for col in 0...n - 1 {
            floodFill(&copy, 0, col);
            floodFill(&copy, m - 1, col);
        }
        var count = 0;
        for row in 0...m - 1 {
            for col in 0...n - 1 {
                if (copy[row][col] == Solution.LAND) {
                    count += 1;
                }
            }
        }
        return count;
    }

    private func floodFill(_ grid: inout [[Int]], _ row: Int, _ col: Int) {
        if (row < 0 || row >= grid.count || col < 0 || col >= grid[0].count
                || grid[row][col] == Solution.WATER) {
            return;
        }
        grid[row][col] = Solution.WATER;
        floodFill(&grid, row - 1, col);
        floodFill(&grid, row + 1, col);
        floodFill(&grid, row, col - 1);
        floodFill(&grid, row, col + 1);
    }
}
// https://leetcode.cn/submissions/detail/387742936/
```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```swift
class Solution {
    func videoStitching(_ clips: [[Int]], _ time: Int) -> Int {
        let sortedClips = clips.sorted { a, b in
            a[0] == b[0] ? a[1] > b[1] : a[0] < b[0]
        };
        var count = 0;
        var maxEnd = 0;
        var i = 0;
        let n = sortedClips.count;
        // 当 clips[i] 与 [0, maxEnd] 重叠（相交或被覆盖）时
        while (i < n && sortedClips[i][0] <= maxEnd) {
            // 记录与 [0, maxEnd] 重叠的所有区间中最大的 end
            var nextEnd = sortedClips[i][1];
            while (i < n && sortedClips[i][0] <= maxEnd) {
                nextEnd = max(nextEnd, sortedClips[i][1]);
                i += 1;
            }
            count += 1;
            maxEnd = nextEnd;
            if (maxEnd >= time) {
                return count;
            }
        }
        return -1;
    }
}
// https://leetcode.cn/submissions/detail/385541993/
```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```swift
class Solution {
    func longestCommonSubsequence(_ text1: String, _ text2: String) -> Int {
        let chs1 = [Character](text1), chs2 = [Character](text2);
        let n1 = chs1.count, n2 = chs2.count;
        // text1[0..i-1] = text1 的长度为 i 的前缀
        // text2[0..j-1] = text2 的长度为 j 的前缀
        // dp[i][j] = LCS(text1[0..i-1], text2[0..j-1]) 的长度
        var dp = Array(repeating: Array(repeating: 0, count: n2 + 1), count: n1 + 1);
        for i in 1...n1 {
            for j in 1...n2 {
                if (chs1[i - 1] == chs2[j - 1]) {
                    dp[i][j] = dp[i - 1][j - 1] + 1;
                } else {
                    dp[i][j] = max(dp[i][j - 1], dp[i - 1][j]);
                }
            }
        }
        return dp[n1][n2];
    }
}
// https://leetcode.cn/submissions/detail/385772210/
```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```swift
class Solution {
    private static let LAND = 0;
    private static let WATER = 1;

    func closedIsland(_ grid: [[Int]]) -> Int {
        var copy = grid;
        let m = copy.count;
        let n = copy[0].count;
        // 淹没与左右边界的陆地相连的岛屿
        for row in 0...m - 1 {
            floodFill(&copy, row, 0);
            floodFill(&copy, row, n - 1);
        }
        // 淹没与上下边界的陆地相连的岛屿
        for col in 0...n - 1 {
            floodFill(&copy, 0, col);
            floodFill(&copy, m - 1, col);
        }
        var count = 0;
        for row in 0...m - 1 {
            for col in 0...n - 1 {
                if (copy[row][col] == Solution.LAND) {
                    floodFill(&copy, row, col);
                    count += 1;
                }
            }
        }
        return count;
    }

    private func floodFill(_ grid: inout [[Int]], _ row: Int, _ col: Int) {
        if (row < 0 || row >= grid.count || col < 0 || col >= grid[0].count
                || grid[row][col] == Solution.WATER) {
            return;
        }
        grid[row][col] = Solution.WATER;
        floodFill(&grid, row - 1, col);
        floodFill(&grid, row + 1, col);
        floodFill(&grid, row, col - 1);
        floodFill(&grid, row, col + 1);
    }
}
// https://leetcode.cn/submissions/detail/387742504/
```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```swift
class Solution {
    func removeCoveredIntervals(_ intervals: [[Int]]) -> Int {
        let sortedIntervals = intervals.sorted { a, b in
            a[0] == b[0] ? a[1] > b[1] : a[0] < b[0]
        };
        var count = sortedIntervals.count;
        var maxEnd = 0;
        for interval in sortedIntervals {
            let end = interval[1];
            if (end <= maxEnd) {
                count -= 1;
            } else {
                maxEnd = end;
            }
        }
        return count;
    }
}
// https://leetcode.cn/submissions/detail/385541044/
```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```swift
class Solution {
    private var nums: [Int] = [];

    func balanceBST(_ root: TreeNode?) -> TreeNode? {
        dfs(root);
        return sortedArrayToBST(nums, 0, nums.count - 1);
    }

    // 深度优先搜索，获取中序遍历结果
    private func dfs(_ root: TreeNode?) {
        if (root == nil) {
            return;
        }
        dfs(root!.left);
        nums.append(root!.val);
        dfs(root!.right);
    }

    // 将有序子数组 nums[lo..hi] 转换为二叉搜索树
    private func sortedArrayToBST(_ nums: [Int], _ lo: Int, _ hi: Int) -> TreeNode? {
        if (lo > hi) {
            return nil;
        }
        let mid = lo + (hi - lo) / 2;
        let root = TreeNode(nums[mid]);
        root.left = sortedArrayToBST(nums, lo, mid - 1);
        root.right = sortedArrayToBST(nums, mid + 1, hi);
        return root;
    }
}
// https://leetcode.cn/submissions/detail/384968609/
```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```swift
class IndexMaxPQ {
    private let maxN: Int;
    private var n: Int;
    private var pq: [Int];
    private var qp: [Int];
    private var keys: [Double?];

    init(_ maxN: Int) {
        self.maxN = maxN;
        n = 0;
        keys = Array(repeating: nil, count: maxN + 1);
        pq = Array(repeating: -1, count: maxN + 1);
        qp = Array(repeating: -1, count: maxN + 1);
    }

    public func isEmpty() -> Bool {
        n == 0;
    }

    public func contains(_ i: Int) -> Bool {
        qp[i] != -1;
    }

    public func insert(_ i: Int, _ key: Double) {
        n += 1;
        qp[i] = n;
        pq[n] = i;
        keys[i] = key;
        swim(n);
    }

    public func delMax() -> Int {
        let max = pq[1];
        exch(1, n);
        n -= 1;
        sink(1);
        qp[max] = -1;
        keys[max] = nil;
        pq[n + 1] = -1;
        return max;
    }

    public func changeKey(_ i: Int, _ key: Double) {
        keys[i] = key;
        swim(qp[i]);
        sink(qp[i]);
    }

    private func less(_ i: Int, _ j: Int) -> Bool {
        keys[pq[i]]! < keys[pq[j]]!;
    }

    private func exch(_ i: Int, _ j: Int) {
        pq.swapAt(i, j);
        qp[pq[i]] = i;
        qp[pq[j]] = j;
    }

    private func swim(_ k: Int) {
        var k = k;
        while (k > 1 && less(k / 2, k)) {
            exch(k, k / 2);
            k = k / 2;
        }
    }

    private func sink(_ k: Int) {
        var k = k;
        while (2 * k <= n) {
            var j = 2 * k;
            if (j < n && less(j, j + 1)) {
                j += 1;
            }
            if (!less(k, j)) {
                break;
            }
            exch(k, j);
            k = j;
        }
    }
}

struct DirectedEdge {
    private let v: Int;
    private let w: Int;
    public let weight: Double;

    init(_ v: Int, _ w: Int, _ weight: Double) {
        self.v = v
        self.w = w
        self.weight = weight
    }

    public func from() -> Int {
        v;
    }

    public func to() -> Int {
        w;
    }
}

struct EdgeWeightedDigraph {
    public let V: Int;
    private var E = 0;
    private var adj: [[DirectedEdge]];

    init(_ V: Int) {
        self.V = V;
        adj = Array(repeating: [], count: V);
    }

    public mutating func addEdge(_ e: DirectedEdge) {
        let v = e.from();
        adj[v].append(e);
        E += 1;
    }

    public func adj(_ v: Int) -> [DirectedEdge] {
        adj[v];
    }
}

struct DijkstraLP {
    private var distTo: [Double];
    private var pq: IndexMaxPQ;

    init(_ G: EdgeWeightedDigraph, _ s: Int) {
        let V = G.V;
        distTo = Array(repeating: -Double.infinity, count: V);
        distTo[s] = 1.0;
        pq = IndexMaxPQ(V);
        pq.insert(s, distTo[s]);
        while (!pq.isEmpty()) {
            let v = pq.delMax();
            relax(G, v);
        }
    }

    private mutating func relax(_ G: EdgeWeightedDigraph, _ v: Int) {
        for e in G.adj(v) {
            let w = e.to();
            if (distTo[w] < distTo[v] * e.weight) {
                distTo[w] = distTo[v] * e.weight;
                if (pq.contains(w)) {
                    pq.changeKey(w, distTo[w]);
                } else {
                    pq.insert(w, distTo[w]);
                }
            }
        }
    }

    public func hasPathTo(_ v: Int) -> Bool {
        distTo[v] > -Double.infinity;
    }

    public func distTo(_ v: Int) -> Double {
        distTo[v];
    }
}

class Solution {
    func maxProbability(_ n: Int, _ edges: [[Int]], _ succProb: [Double], _ start: Int, _ end: Int) -> Double {
        var graph = EdgeWeightedDigraph(n);
        for (i, e) in edges.enumerated() {
            let v = e[0];
            let w = e[1];
            let weight = succProb[i];
            graph.addEdge(DirectedEdge(v, w, weight));
            graph.addEdge(DirectedEdge(w, v, weight));
        }
        let lpt = DijkstraLP(graph, start);
        if (lpt.hasPathTo(end)) {
            return lpt.distTo(end);
        }
        return 0.0;
    }
}
// https://leetcode.cn/submissions/detail/386383043/
```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```swift
class Solution {
    func minInsertions(_ s: String) -> Int {
        var insertLeft = 0; // 已插入左括号的数量
        var insertRight = 0; // 已插入右括号的数量
        var needRight = 0; // 待插入右括号的数量
        for ch in s {
            if (ch == "(") {
                // A((B)(.. -> A((B))(..
                if (needRight % 2 == 1) {
                    //『必须立即』在位置 i 前插入 1 个右括号
                    // 否则，后续任何插入都不能使区间 [0..i-1] 的匹配有效
                    insertRight += 1;
                    needRight -= 1;
                }
                needRight += 2;
            }
            if (ch == ")") {
                needRight -= 1;
                // A).. -> A()..
                if (needRight == -1) {
                    //『必须立即』在位置 i 前插入 1 个左括号
                    // 否则，后续任何插入都不能使区间 [0..i] 的匹配有效
                    insertLeft += 1;
                    needRight = 1;
                }
            }
        }
        return insertLeft + insertRight + needRight;
    }
}
// https://leetcode.cn/submissions/detail/385443436/
```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```swift
class Solution {
    func minCostConnectPoints(_ points: [[Int]]) -> Int {
        let n = points.count;
        var graph = Graph<Int>();
        var v = 0;
        while (v < n) {
            var w = v + 1;
            while (w < n) {
                let weight = abs(points[v][0] - points[w][0]) + abs(points[v][1] - points[w][1]);
                graph.addEdge(vertex1: v, vertex2: w, weight: weight);
                w += 1
            }
            v += 1;
        }
        let mst = minimumSpanningTreePrim(graph: graph);
        return mst.cost;
    }
}

//
//  Heap.swift
//  Written for the Swift Algorithm Club by Kevin Randrup and Matthijs Hollemans
//

public struct Heap<T> {
    /** The array that stores the heap's nodes. */
    var elements = [T]()

    /** Determines whether this is a max-heap (>) or min-heap (<). */
    fileprivate var isOrderedBefore: (T, T) -> Bool

    /**
   * Creates an empty heap.
   * The sort function determines whether this is a min-heap or max-heap.
   * For integers, > makes a max-heap, < makes a min-heap.
   */
    public init(sort: @escaping (T, T) -> Bool) {
        self.isOrderedBefore = sort
    }

    /**
   * Creates a heap from an array. The order of the array does not matter;
   * the elements are inserted into the heap in the order determined by the
   * sort function.
   */
    public init(array: [T], sort: @escaping (T, T) -> Bool) {
        self.isOrderedBefore = sort
        buildHeap(fromArray: array)
    }

    /*
  // This version has O(n log n) performance.
  private mutating func buildHeap(array: [T]) {
    elements.reserveCapacity(array.count)
    for value in array {
      insert(value)
    }
  }
  */

    /**
   * Converts an array to a max-heap or min-heap in a bottom-up manner.
   * Performance: This runs pretty much in O(n).
   */
    fileprivate mutating func buildHeap(fromArray array: [T]) {
        elements = array
        for i in stride(from: (elements.count/2 - 1), through: 0, by: -1) {
            shiftDown(i, heapSize: elements.count)
        }
    }

    public var isEmpty: Bool {
        return elements.isEmpty
    }

    public var count: Int {
        return elements.count
    }

    /**
   * Returns the index of the parent of the element at index i.
   * The element at index 0 is the root of the tree and has no parent.
   */
    @inline(__always) func parentIndex(ofIndex i: Int) -> Int {
        return (i - 1) / 2
    }

    /**
   * Returns the index of the left child of the element at index i.
   * Note that this index can be greater than the heap size, in which case
   * there is no left child.
   */
    @inline(__always) func leftChildIndex(ofIndex i: Int) -> Int {
        return 2*i + 1
    }

    /**
   * Returns the index of the right child of the element at index i.
   * Note that this index can be greater than the heap size, in which case
   * there is no right child.
   */
    @inline(__always) func rightChildIndex(ofIndex i: Int) -> Int {
        return 2*i + 2
    }

    /**
   * Returns the maximum value in the heap (for a max-heap) or the minimum
   * value (for a min-heap).
   */
    public func peek() -> T? {
        return elements.first
    }

    /**
   * Adds a new value to the heap. This reorders the heap so that the max-heap
   * or min-heap property still holds. Performance: O(log n).
   */
    public mutating func insert(_ value: T) {
        elements.append(value)
        shiftUp(elements.count - 1)
    }

    public mutating func insert<S: Sequence>(_ sequence: S) where S.Iterator.Element == T {
        for value in sequence {
            insert(value)
        }
    }

    /**
   * Allows you to change an element. In a max-heap, the new element should be
   * larger than the old one; in a min-heap it should be smaller.
   */
    public mutating func replace(index i: Int, value: T) {
        guard i < elements.count else { return }

        assert(isOrderedBefore(value, elements[i]))
        elements[i] = value
        shiftUp(i)
    }

    /**
   * Removes the root node from the heap. For a max-heap, this is the maximum
   * value; for a min-heap it is the minimum value. Performance: O(log n).
   */
    @discardableResult public mutating func remove() -> T? {
        if elements.isEmpty {
            return nil
        } else if elements.count == 1 {
            return elements.removeLast()
        } else {
            // Use the last node to replace the first one, then fix the heap by
            // shifting this new first node into its proper position.
            let value = elements[0]
            elements[0] = elements.removeLast()
            shiftDown()
            return value
        }
    }

    /**
   * Removes an arbitrary node from the heap. Performance: O(log n). You need
   * to know the node's index, which may actually take O(n) steps to find.
   */
    public mutating func removeAt(_ index: Int) -> T? {
        guard index < elements.count else { return nil }

        let size = elements.count - 1
        if index != size {
            elements.swapAt(index,size)
            shiftDown(index, heapSize: size)
            shiftUp(index)
        }
        return elements.removeLast()
    }

    /**
   * Takes a child node and looks at its parents; if a parent is not larger
   * (max-heap) or not smaller (min-heap) than the child, we exchange them.
   */
    mutating func shiftUp(_ index: Int) {
        var childIndex = index
        let child = elements[childIndex]
        var parentIndex = self.parentIndex(ofIndex: childIndex)

        while childIndex > 0 && isOrderedBefore(child, elements[parentIndex]) {
            elements[childIndex] = elements[parentIndex]
            childIndex = parentIndex
            parentIndex = self.parentIndex(ofIndex: childIndex)
        }

        elements[childIndex] = child
    }

    mutating func shiftDown() {
        shiftDown(0, heapSize: elements.count)
    }

    /**
   * Looks at a parent node and makes sure it is still larger (max-heap) or
   * smaller (min-heap) than its childeren.
   */
    mutating func shiftDown(_ index: Int, heapSize: Int) {
        var parentIndex = index

        while true {
            let leftChildIndex = self.leftChildIndex(ofIndex: parentIndex)
            let rightChildIndex = leftChildIndex + 1

            // Figure out which comes first if we order them by the sort function:
            // the parent, the left child, or the right child. If the parent comes
            // first, we're done. If not, that element is out-of-place and we make
            // it "float down" the tree until the heap property is restored.
            var first = parentIndex
            if leftChildIndex < heapSize && isOrderedBefore(elements[leftChildIndex], elements[first]) {
                first = leftChildIndex
            }
            if rightChildIndex < heapSize && isOrderedBefore(elements[rightChildIndex], elements[first]) {
                first = rightChildIndex
            }
            if first == parentIndex { return }

            elements.swapAt(parentIndex,first)
            parentIndex = first
        }
    }
}

// MARK: - Searching

extension Heap where T: Equatable {
    /**
   * Searches the heap for the given element. Performance: O(n).
   */
    public func index(of element: T) -> Int? {
        return index(of: element, 0)
    }

    fileprivate func index(of element: T, _ i: Int) -> Int? {
        if i >= count { return nil }
        if isOrderedBefore(element, elements[i]) { return nil }
        if element == elements[i] { return i }
        if let j = index(of: element, self.leftChildIndex(ofIndex: i)) { return j }
        if let j = index(of: element, self.rightChildIndex(ofIndex: i)) { return j }
        return nil
    }
}

/*
  Priority Queue, a queue where the most "important" items are at the front of
  the queue.

  The heap is a natural data structure for a priority queue, so this object
  simply wraps the Heap struct.

  All operations are O(lg n).

  Just like a heap can be a max-heap or min-heap, the queue can be a max-priority
  queue (largest element first) or a min-priority queue (smallest element first).
*/
public struct PriorityQueue<T> {
    fileprivate var heap: Heap<T>

    /*
    To create a max-priority queue, supply a > sort function. For a min-priority
    queue, use <.
  */
    public init(sort: @escaping (T, T) -> Bool) {
        heap = Heap(sort: sort)
    }

    public var isEmpty: Bool {
        return heap.isEmpty
    }

    public var count: Int {
        return heap.count
    }

    public func peek() -> T? {
        return heap.peek()
    }

    public mutating func enqueue(_ element: T) {
        heap.insert(element)
    }

    public mutating func dequeue() -> T? {
        return heap.remove()
    }

    /*
    Allows you to change the priority of an element. In a max-priority queue,
    the new priority should be larger than the old one; in a min-priority queue
    it should be smaller.
  */
    public mutating func changePriority(index i: Int, value: T) {
        return heap.replace(index: i, value: value)
    }
}

extension PriorityQueue where T: Equatable {
    public func index(of element: T) -> Int? {
        return heap.index(of: element)
    }
}

// Undirected edge
public struct Edge<T>: CustomStringConvertible {
    public let vertex1: T
    public let vertex2: T
    public let weight: Int

    public var description: String {
        return "[\(vertex1)-\(vertex2), \(weight)]"
    }
}

// Undirected weighted graph
public struct Graph<T: Hashable>: CustomStringConvertible {

    public private(set) var edgeList: [Edge<T>]
    public private(set) var vertices: Set<T>
    public private(set) var adjList: [T: [(vertex: T, weight: Int)]]

    public init() {
        edgeList = [Edge<T>]()
        vertices = Set<T>()
        adjList = [T: [(vertex: T, weight: Int)]]()
    }

    public var description: String {
        var description = ""
        for edge in edgeList {
            description += edge.description + "\n"
        }
        return description
    }

    public mutating func addEdge(vertex1 v1: T, vertex2 v2: T, weight w: Int) {
        edgeList.append(Edge(vertex1: v1, vertex2: v2, weight: w))
        vertices.insert(v1)
        vertices.insert(v2)

        adjList[v1] = adjList[v1] ?? []
        adjList[v1]?.append((vertex: v2, weight: w))

        adjList[v2] = adjList[v2] ?? []
        adjList[v2]?.append((vertex: v1, weight: w))
    }

    public mutating func addEdge(_ edge: Edge<T>) {
        addEdge(vertex1: edge.vertex1, vertex2: edge.vertex2, weight: edge.weight)
    }
}

//
//  Prim.swift
//
//
//  Created by xiang xin on 16/3/17.
//
//

func minimumSpanningTreePrim<T>(graph: Graph<T>) -> (cost: Int, tree: Graph<T>) {
    var cost: Int = 0
    var tree = Graph<T>()

    guard let start = graph.vertices.first else {
        return (cost: cost, tree: tree)
    }

    var visited = Set<T>()
    var priorityQueue = PriorityQueue<(vertex: T, weight: Int, parent: T?)>(
            sort: { $0.weight < $1.weight })

    priorityQueue.enqueue((vertex: start, weight: 0, parent: nil))
    while let head = priorityQueue.dequeue() {
        let vertex = head.vertex
        if visited.contains(vertex) {
            continue
        }
        visited.insert(vertex)

        cost += head.weight
        if let prev = head.parent {
            tree.addEdge(vertex1: prev, vertex2: vertex, weight: head.weight)
        }

        if let neighbours = graph.adjList[vertex] {
            for neighbour in neighbours {
                let nextVertex = neighbour.vertex
                if !visited.contains(nextVertex) {
                    priorityQueue.enqueue((vertex: nextVertex, weight: neighbour.weight, parent: vertex))
                }
            }
        }
    }

    return (cost: cost, tree: tree)
}
// https://leetcode.cn/submissions/detail/386300293/
```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```swift
import Foundation

class IndexMinPQ {
    private let maxN: Int;
    private var n: Int;
    private var pq: [Int];
    private var qp: [Int];
    private var keys: [Int?];

    init(_ maxN: Int) {
        self.maxN = maxN;
        n = 0;
        keys = Array(repeating: nil, count: maxN + 1);
        pq = Array(repeating: -1, count: maxN + 1);
        qp = Array(repeating: -1, count: maxN + 1);
    }

    public func isEmpty() -> Bool {
        n == 0;
    }

    public func contains(_ i: Int) -> Bool {
        qp[i] != -1;
    }

    public func insert(_ i: Int, _ key: Int) {
        n += 1;
        qp[i] = n;
        pq[n] = i;
        keys[i] = key;
        swim(n);
    }

    public func delMin() -> Int {
        let max = pq[1];
        exch(1, n);
        n -= 1;
        sink(1);
        qp[max] = -1;
        keys[max] = nil;
        pq[n + 1] = -1;
        return max;
    }

    public func changeKey(_ i: Int, _ key: Int) {
        keys[i] = key;
        swim(qp[i]);
        sink(qp[i]);
    }

    private func less(_ i: Int, _ j: Int) -> Bool {
        keys[pq[i]]! < keys[pq[j]]!;
    }

    private func exch(_ i: Int, _ j: Int) {
        pq.swapAt(i, j);
        qp[pq[i]] = i;
        qp[pq[j]] = j;
    }

    private func swim(_ k: Int) {
        var k = k;
        while (k > 1 && less(k / 2, k)) {
            exch(k, k / 2);
            k = k / 2;
        }
    }

    private func sink(_ k: Int) {
        var k = k;
        while (2 * k <= n) {
            var j = 2 * k;
            if (j < n && less(j, j + 1)) {
                j += 1;
            }
            if (!less(k, j)) {
                break;
            }
            exch(k, j);
            k = j;
        }
    }
}

struct DirectedEdge {
    private let v: Int;
    private let w: Int;
    public let weight: Int;

    init(_ v: Int, _ w: Int, _ weight: Int) {
        self.v = v
        self.w = w
        self.weight = weight
    }

    public func from() -> Int {
        v;
    }

    public func to() -> Int {
        w;
    }
}

struct EdgeWeightedDigraph {
    public let V: Int;
    private var E = 0;
    private var adj: [[DirectedEdge]];

    init(_ V: Int) {
        self.V = V;
        adj = Array(repeating: [], count: V);
    }

    public mutating func addEdge(_ e: DirectedEdge) {
        let v = e.from();
        adj[v].append(e);
        E += 1;
    }

    public func adj(_ v: Int) -> [DirectedEdge] {
        adj[v];
    }
}

struct DijkstraSP {
    private var distTo: [Int];
    private var pq: IndexMinPQ;

    init(_ G: EdgeWeightedDigraph, _ s: Int) {
        let V = G.V;
        distTo = Array(repeating: Int.max, count: V);
        distTo[s] = 0;
        pq = IndexMinPQ(V);
        pq.insert(s, distTo[s]);
        while (!pq.isEmpty()) {
            let v = pq.delMin();
            relax(G, v);
        }
    }

    private mutating func relax(_ G: EdgeWeightedDigraph, _ v: Int) {
        for e in G.adj(v) {
            let w = e.to();
            if (distTo[w] > max(distTo[v], e.weight)) {
                distTo[w] = max(distTo[v], e.weight);
                if (pq.contains(w)) {
                    pq.changeKey(w, distTo[w]);
                } else {
                    pq.insert(w, distTo[w]);
                }
            }
        }
    }

    public func distTo(_ v: Int) -> Int {
        distTo[v];
    }
}

class Solution {
    func minimumEffortPath(_ heights: [[Int]]) -> Int {
        let m = heights.count;
        let n = heights[0].count;
        var graph = EdgeWeightedDigraph(m * n);
        let directions = [[0, 1], [0, -1], [1, 0], [-1, 0]];
        for i in 0...m - 1 {
            for j in 0...n - 1 {
                for d in directions {
                    let x = i + d[0];
                    let y = j + d[1];
                    if (x >= 0 && x <= m - 1 && y >= 0 && y <= n - 1) {
                        let v = i * n + j;
                        let w = x * n + y;
                        let weight = abs(heights[i][j] - heights[x][y]);
                        graph.addEdge(DirectedEdge(v, w, weight));
                    }
                }
            }
        }
        let spt = DijkstraSP(graph, 0);
        return spt.distTo((m - 1) * n + n - 1);
    }
}
// 超出时间限制
```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```swift
class Solution {
    private static let LAND = 1;
    private static let WATER = 0;

    func countSubIslands(_ grid1: [[Int]], _ grid2: [[Int]]) -> Int {
        var copy2 = grid2;
        let m = copy2.count, n = copy2[0].count;
        for i in 0...m - 1 {
            for j in 0...n - 1 {
                // 淹没『非子岛屿』
                if (copy2[i][j] == Solution.LAND && grid1[i][j] == Solution.WATER) {
                    floodFill(&copy2, i, j);
                }
            }
        }
        var count = 0;
        for i in 0...m - 1 {
            for j in 0...n - 1 {
                if (copy2[i][j] == Solution.LAND) {
                    floodFill(&copy2, i, j);
                    count += 1;
                }
            }
        }
        return count;
    }

    private func floodFill(_ grid: inout [[Int]], _ row: Int, _ col: Int) {
        if (row < 0 || row >= grid.count || col < 0 || col >= grid[0].count
                || grid[row][col] == Solution.WATER) {
            return;
        }
        grid[row][col] = Solution.WATER;
        floodFill(&grid, row - 1, col);
        floodFill(&grid, row + 1, col);
        floodFill(&grid, row, col - 1);
        floodFill(&grid, row, col + 1);
    }
}
// https://leetcode.cn/submissions/detail/387743712/
```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode-cn.com/problems/kth-node-from-end-of-list-lcci/>

```swift
class Solution {
    func kthToLast(_ head: ListNode?, _ k: Int) -> Int {
        var slow = head, fast = head;
        for _ in 1...k {
            fast = fast!.next;
        }
        while (fast != nil) {
            slow = slow!.next;
            fast = fast!.next;
        }
        return slow!.val;
    }
}
// https://leetcode.cn/submissions/detail/384867877/
```
