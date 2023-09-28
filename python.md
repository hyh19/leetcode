<!-- omit in toc -->
# LeetCode 题解：Python 实现

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

<https://leetcode.cn/problems/two-sum/>

```py
class Solution:
    def twoSum(self, nums: List[int], target: int) -> List[int]:
        valToIndex = {}
        for i in range(len(nums)):
            x = nums[i]
            need = target - x
            if need in valToIndex:
                return [valToIndex[need], i]
            valToIndex[x] = i
        return [-1, -1]
# https://leetcode.cn/submissions/detail/378695722/
```

## 2. 两数相加

<https://leetcode.cn/problems/add-two-numbers/>

```py
class Solution:
    def addTwoNumbers(self, l1: Optional[ListNode], l2: Optional[ListNode]) -> Optional[ListNode]:
        ptr = dummyHead = ListNode()
        carry = 0
        while (l1 is not None) or (l2 is not None) or carry > 0:
            sum = carry
            if l1 is not None:
                sum += l1.val
                l1 = l1.next
            if l2 is not None:
                sum += l2.val
                l2 = l2.next
            ptr.next = ListNode(sum % 10)
            ptr = ptr.next
            carry = sum // 10
        return dummyHead.next
# https://leetcode.cn/submissions/detail/378904137/
```

## 3. 无重复字符的最长子串

<https://leetcode.cn/problems/longest-substring-without-repeating-characters/>

```py
class Solution:
    def lengthOfLongestSubstring(self, s: str) -> int:
        ans = 0
        window = set()
        # s[left..right) = Window Substring
        # s[right..n-1]  = Scanning
        left = right = 0
        while right < len(s):
            c = s[right]
            if c not in window:
                window.add(c)
                right += 1
            else:
                while left < right:
                    d = s[left]
                    left += 1
                    window.remove(d)
                    if d == c:
                        break
            ans = max(ans, right - left)
        return ans
# https://leetcode.cn/submissions/detail/392738890/
```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```py
class Solution:
    def findMedianSortedArrays(self, nums1: List[int], nums2: List[int]) -> float:
        total = len(nums1) + len(nums2)
        half = total // 2
        if total % 2 == 0:
            k1 = self.getKthElement(nums1, nums2, half)
            k2 = self.getKthElement(nums1, nums2, half + 1)
            return (k1 + k2) / 2
        return self.getKthElement(nums1, nums2, half + 1)

    # 寻找两个正序数组 nums1 和 nums2 从小到大排列的第 k 个数
    def getKthElement(self, nums1: List[int], nums2: List[int], k: int) -> int:
        n1 = len(nums1)
        n2 = len(nums2)
        start1 = 0
        start2 = 0
        while True:
            if start1 == n1:
                return nums2[start2 + k - 1]
            if start2 == n2:
                return nums1[start1 + k - 1]
            if k == 1:
                return min(nums1[start1], nums2[start2])
            half = k // 2
            i = min(n1 - 1, start1 + half - 1)
            j = min(n2 - 1, start2 + half - 1)
            if nums1[i] < nums2[j]:
                # 排除 nums1[start1..i] 共 i-start1+1 个元素
                k -= (i - start1 + 1)
                start1 = i + 1
            else:
                # 排除 nums2[start2..j] 共 j-start2+1 个元素
                k -= (j - start2 + 1)
                start2 = j + 1
# https://leetcode.cn/submissions/detail/393647977/
```

```py
class Solution:
    def findMedianSortedArrays(self, nums1: List[int], nums2: List[int]) -> float:
        total = len(nums1) + len(nums2)
        half = total // 2
        if total % 2 == 0:
            k1 = self.getKthElement(nums1, 0, nums2, 0, half)
            k2 = self.getKthElement(nums1, 0, nums2, 0, half + 1)
            return (k1 + k2) / 2
        return self.getKthElement(nums1, 0, nums2, 0, half + 1)

    # 寻找两个正序数组 nums1[start1..end1] 和 nums2[start2..end2] 从小到大排列的第 k 个数
    def getKthElement(self, nums1: List[int], start1: int, nums2: List[int], start2: int, k: int) -> int:
        n1 = len(nums1)
        n2 = len(nums2)
        if start1 >= n1:
            return nums2[start2 + k - 1]
        if start2 >= n2:
            return nums1[start1 + k - 1]
        if k == 1:
            return min(nums1[start1], nums2[start2])
        half = k // 2
        i = min(n1 - 1, start1 + half - 1)
        j = min(n2 - 1, start2 + half - 1)
        if nums1[i] < nums2[j]:
            # 排除 nums1[start1..i] 共 i-start1+1 个元素
            return self.getKthElement(nums1, i + 1, nums2, start2, k - (i - start1 + 1))
        else:
            # 排除 nums2[start2..j] 共 j-start2+1 个元素
            return self.getKthElement(nums1, start1, nums2, j + 1, k - (j - start2 + 1))
# https://leetcode.cn/submissions/detail/380270678/
```

## 5. 最长回文子串

<https://leetcode.cn/problems/longest-palindromic-substring/>

```py
class Solution:
    def longestPalindrome(self, s: str) -> str:
        ans = ''
        for i in range(len(s)):
            s1 = self.longestPalindromeCenter(s, i, i)
            if len(s1) > len(ans):
                ans = s1
            s2 = self.longestPalindromeCenter(s, i, i + 1)
            if len(s2) > len(ans):
                ans = s2
        return ans

    # 返回字符串 s 中以 s[i] 和 s[j] 为中心的最长回文子串
    def longestPalindromeCenter(self, s: str, i: int, j: int) -> str:
        if i > j or j - i > 1:
            return ''
        while i >= 0 and j < len(s) and s[i] == s[j]:
            i -= 1
            j += 1
        return s[i + 1:j]
# https://leetcode.cn/submissions/detail/394199293/
```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```py
class Solution:
    INT_MIN = -(1 << 31)
    INT_MAX = (1 << 31) - 1

    def reverse(self, x: int) -> int:
        if x == 0 or x == Solution.INT_MIN:
            return 0
        ans = 0
        sign = 1 if x > 0 else -1
        x = abs(x)
        while x != 0:
            if ans > Solution.INT_MAX // 10:
                return 0
            ans = ans * 10 + x % 10
            x = x // 10
        return ans * sign
# https://leetcode.cn/submissions/detail/394909701/
```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```py
class Solution:
    def maxArea(self, height: List[int]) -> int:
        ans = 0
        i = 0
        j = len(height) - 1
        while i < j:
            area = (j - i) * min(height[i], height[j])
            ans = max(ans, area)
            if height[i] < height[j]:
                i += 1
            else:
                j -= 1
        return ans
# https://leetcode.cn/submissions/detail/395987844/
```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```py
class Solution:
    def longestCommonPrefix(self, strs: List[str]) -> str:
        return self.longestCommonPrefixRange(strs, 0, len(strs) - 1)

    def longestCommonPrefixRange(self, strs: List[str], lo: int, hi: int) -> str:
        if lo == hi:
            return strs[lo]
        mid = lo + (hi - lo) // 2
        left = self.longestCommonPrefixRange(strs, lo, mid)
        right = self.longestCommonPrefixRange(strs, mid + 1, hi)
        return self.longestCommonPrefixTwo(left, right)

    def longestCommonPrefixTwo(self, s1: str, s2: str) -> str:
        n = min(len(s1), len(s2))
        i = 0
        while i < n and s1[i] == s2[i]:
            i += 1
        return s1[0:i]
# https://leetcode.cn/submissions/detail/380062660/
```

## 15. 三数之和

<https://leetcode.cn/problems/3sum/>

```py
class Solution:
    def threeSum(self, nums: List[int]) -> List[List[int]]:
        nums.sort()
        return self.kSum(3, nums, 0, len(nums) - 1, 0)

    # 返回升序子数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
    def kSum(self, k: int, nums: List[int], lo: int, hi: int, target: int) -> List[List[int]]:
        if hi - lo + 1 < k:
            return []
        if k == 2:
            return self.twoSum(nums, lo, hi, target)
        res = []
        i = lo
        while i <= hi:
            curNum = nums[i]
            sp = self.kSum(k - 1, nums, i + 1, hi, target - curNum)
            for x in sp:
                x.append(curNum)
                res.append(x)
            while i <= hi and nums[i] == curNum:
                i += 1
        return res

    # 返回升序子数组 nums[lo..hi] 中所有和为 target 且不重复的 2 元组
    def twoSum(self, nums: List[int], lo: int, hi: int, target: int) -> List[List[int]]:
        res = []
        while lo < hi:
            first, second = nums[lo], nums[hi]
            sum = first + second
            if sum < target:
                while lo < hi and nums[lo] == first:
                    lo += 1
            elif sum > target:
                while lo < hi and nums[hi] == second:
                    hi -= 1
            else:
                res.append([first, second])
                while lo < hi and nums[lo] == first:
                    lo += 1
                while lo < hi and nums[hi] == second:
                    hi -= 1
        return res
# https://leetcode.cn/submissions/detail/421268011/
```

## 18. 四数之和

<https://leetcode.cn/problems/4sum/>

```py
class Solution:
    def fourSum(self, nums: List[int], target: int) -> List[List[int]]:
        nums.sort()
        return self.kSum(4, nums, 0, len(nums) - 1, target)

    # 升序子数组 nums[lo..hi] 所有和为 target 且不重复的 k 元组
    def kSum(self, k: int, nums: List[int], lo: int, hi: int, target: int) -> List[List[int]]:
        if hi - lo + 1 < k:
            return []
        if k == 2:
            return self.twoSum(nums, lo, hi, target)
        res = []
        i = lo
        while i <= hi:
            curNum = nums[i]
            sp = self.kSum(k - 1, nums, i + 1, hi, target - curNum)
            for x in sp:
                x.append(curNum)
                res.append(x)
            while i <= hi and nums[i] == curNum:
                i += 1
        return res

    # 升序子数组 nums[lo..hi] 所有和为 target 且不重复的 2 元组
    def twoSum(self, nums: List[int], lo: int, hi: int, target: int) -> List[List[int]]:
        res = []
        while lo < hi:
            first = nums[lo]
            second = nums[hi]
            sum = first + second
            if sum < target:
                while lo < hi and nums[lo] == first:
                    lo += 1
            elif sum > target:
                while lo < hi and nums[hi] == second:
                    hi -= 1
            else:
                res.append([first, second])
                while lo < hi and nums[lo] == first:
                    lo += 1
                while lo < hi and nums[hi] == second:
                    hi -= 1
        return res
# https://leetcode.cn/submissions/detail/378733988/
```

## 19. 删除链表的倒数第 N 个结点

<https://leetcode.cn/problems/remove-nth-node-from-end-of-list/>

```py
class Solution:
    def removeNthFromEnd(self, head: Optional[ListNode], n: int) -> Optional[ListNode]:
        dummyHead = ListNode(-1, head)
        slow = fast = dummyHead
        for i in range(n):
            fast = fast.next
        while fast.next is not None:
            slow = slow.next
            fast = fast.next
        slow.next = slow.next.next   
        return dummyHead.next
# https://leetcode.cn/submissions/detail/399274667/
```

## 20. 有效的括号

<https://leetcode.cn/problems/valid-parentheses/>

```py
class Solution:
    def isValid(self, s: str) -> bool:
        if len(s) % 2 == 1:
            return False
        stack = []
        for ch in s:
            if ch == '(':
                stack.append(')')
            elif ch == '[':
                stack.append(']')
            elif ch == '{':
                stack.append('}')
            else:
                if len(stack) == 0 or stack.pop() != ch:
                    return False
        return len(stack) == 0
# https://leetcode.cn/submissions/detail/399499144/
```

## 21. 合并两个有序链表

<https://leetcode.cn/problems/merge-two-sorted-lists/>

```py
class Solution:
    def mergeTwoLists(self, list1: Optional[ListNode], list2: Optional[ListNode]) -> Optional[ListNode]:
        ptr = dummyHead = ListNode()
        while (list1 is not None) and (list2 is not None):
            if list1.val < list2.val:
                ptr.next = list1
                list1 = list1.next
            else:
                ptr.next = list2
                list2 = list2.next
            ptr = ptr.next
        ptr.next = list2 if list1 is None else list1
        return dummyHead.next
# https://leetcode.cn/submissions/detail/378918423/
```

## 22. 括号生成

<https://leetcode.cn/problems/generate-parentheses/>

```py
class Solution:
    def __init__(self):
        self.left = 0  # 已使用的『左括号』数量
        self.right = 0  # 已使用的『右括号』数量
        self.n = 0
        self.path = []
        self.ans = []

    def generateParenthesis(self, n: int) -> List[str]:
        self.n = n
        self.backtrack()
        return self.ans

    def backtrack(self) -> None:
        # 对于一个「合法」的括号字符串组合 p，必然对于任何 0 <= i < len(p) 都有：
        # 子串 p[0..i] 中左括号的数量都大于或等于右括号的数量
        if self.left < self.right or self.left > self.n:
            return
        # 一个「合法」括号组合的左括号数量一定等于右括号数量
        if self.left == self.n and self.right == self.n:
            self.ans.append(''.join(self.path))
            return
        # edge = 取 '(', ')' 为值
        # 使用『左括号』
        self.path.append('(')
        self.left += 1
        self.backtrack()
        self.path.pop()
        self.left -= 1
        # 使用『右括号』
        self.path.append(')')
        self.right += 1
        self.backtrack()
        self.path.pop()
        self.right -= 1
# https://leetcode.cn/submissions/detail/378945611/
```

## 23. 合并 K 个升序链表

<https://leetcode.cn/problems/merge-k-sorted-lists/>

```py
class Solution:
    def mergeKLists(self, lists: List[Optional[ListNode]]) -> Optional[ListNode]:
        return self._mergeKLists(lists, 0, len(lists) - 1)

    def _mergeKLists(self, lists: List[Optional[ListNode]], lo: int, hi: int) -> Optional[ListNode]:
        if lo > hi:
            return None
        if lo == hi:
            return lists[lo]
        mid = lo + (hi - lo) // 2
        left = self._mergeKLists(lists, lo, mid)
        right = self._mergeKLists(lists, mid + 1, hi)
        return self.mergeTwoLists(left, right)

    def mergeTwoLists(self, list1: Optional[ListNode], list2: Optional[ListNode]) -> Optional[ListNode]:
        ptr = dummyHead = ListNode()
        while (list1 is not None) and (list2 is not None):
            if list1.val < list2.val:
                ptr.next = list1
                list1 = list1.next
            else:
                ptr.next = list2
                list2 = list2.next
            ptr = ptr.next
        ptr.next = list2 if list1 is None else list1
        return dummyHead.next
# https://leetcode.cn/submissions/detail/378920663/
```

## 24. 两两交换链表中的节点

<https://leetcode.cn/problems/swap-nodes-in-pairs/>

```py
class Solution:
    def swapPairs(self, head: Optional[ListNode]) -> Optional[ListNode]:
        if head is None or head.next is None:
            return head
        x = head
        y = head.next
        z = head.next.next
        y.next = x
        x.next = self.swapPairs(z)
        return y
# https://leetcode.cn/submissions/detail/378894947/
```

## 25. K 个一组翻转链表

<https://leetcode.cn/problems/reverse-nodes-in-k-group/>

```py
class Solution:
    def reverseKGroup(self, head: Optional[ListNode], k: int) -> Optional[ListNode]:
        if (head is None) or (head.next is None):
            return head
        ptr = head
        for i in range(k - 1):
            ptr = ptr.next
            if ptr is None:
                return head
        nextGroup = ptr.next
        ptr.next = None
        reverseHead = self.reverseList(head)
        head.next = self.reverseKGroup(nextGroup, k)
        return reverseHead

    def reverseList(self, head: Optional[ListNode]) -> Optional[ListNode]:
        reverseHead = None
        while head is not None:
            x = head.next
            head.next = reverseHead
            reverseHead = head
            head = x
        return reverseHead
# https://leetcode.cn/submissions/detail/429130122/
```

## 26. 删除有序数组中的重复项

<https://leetcode.cn/problems/remove-duplicates-from-sorted-array/>

```py
class Solution:
    def removeDuplicates(self, nums: List[int]) -> int:
        # [0..i-1] 不重复元素区间
        # [i..j-1] 重复元素区间
        # [j..n-1] 遍历区间
        n = len(nums)
        i = 0
        j = 0
        while j < n:
            while j + 1 < n and nums[j] == nums[j + 1]:
                j += 1
            nums[i], nums[j] = nums[j], nums[i]
            i += 1
            j += 1
        return i
# https://leetcode.cn/submissions/detail/378709311/
```

## 27. 移除元素

<https://leetcode.cn/problems/remove-element/>

```py
class Solution:
    def removeElement(self, nums: List[int], val: int) -> int:
        # nums[0..i-1]   != val
        # nums[i..j]     Scanning
        # nums[j+1..n-1] == val
        i = 0
        j = len(nums) - 1
        while i <= j:
            while i <= j and nums[i] != val:
                i += 1
            while i <= j and nums[j] == val:
                j -= 1
            if i <= j:
                nums[i], nums[j] = nums[j], nums[i]
        return i
# https://leetcode.cn/submissions/detail/378656870/
```

## 28. 实现 strStr()

<https://leetcode.cn/problems/implement-strstr/>

```py
class KMP:
    def __init__(self, pat: str):
        R = 256
        self.m = len(pat)
        self.dfa = [[0] * self.m for _ in range(R)]
        self.dfa[ord(pat[0])][0] = 1
        x, j = 0, 1
        while j < self.m:
            for c in range(R):
                self.dfa[c][j] = self.dfa[c][x]
            self.dfa[ord(pat[j])][j] = j + 1
            x = self.dfa[ord(pat[j])][x]
            j += 1

    def search(self, txt: str) -> int:
        n = len(txt)
        i, j = 0, 0
        while i < n and j < self.m:
            j = self.dfa[ord(txt[i])][j]
            i += 1
        if j == self.m:
            return i - self.m
        return -1


class Solution:
    def strStr(self, haystack: str, needle: str) -> int:
        kmp = KMP(needle)
        return kmp.search(haystack)
# https://leetcode.cn/submissions/detail/380392047/
```

```py
class BoyerMoore:
    def __init__(self, pat: str):
        self.pat = pat
        self.right = [-1] * 256
        for j in range(len(pat)):
            self.right[ord(pat[j])] = j

    def search(self, txt: str) -> int:
        n = len(txt)
        m = len(self.pat)
        i = 0
        while i <= n - m:
            skip = 0
            j = m - 1
            while j >= 0:
                if self.pat[j] != txt[i + j]:
                    skip = max(1, j - self.right[ord(txt[i + j])])
                    break
                j -= 1
            if skip == 0:
                return i
            i += skip
        return -1


class Solution:
    def strStr(self, haystack: str, needle: str) -> int:
        bm = BoyerMoore(needle)
        return bm.search(haystack)
# https://leetcode.cn/submissions/detail/380386570/
```

## 33. 搜索旋转排序数组

<https://leetcode.cn/problems/search-in-rotated-sorted-array/>

```py
class Solution:
    def search(self, nums: List[int], target: int) -> int:
        lo = 0
        hi = len(nums) - 1
        while lo <= hi:
            mid = lo + (hi - lo) // 2
            if nums[mid] == target:
                return mid
            if nums[mid] <= nums[hi]:
                if nums[mid] < target <= nums[hi]:
                    lo = mid + 1
                else:
                    hi = mid - 1
            else:
                if nums[lo] <= target < nums[mid]:
                    hi = mid - 1
                else:
                    lo = mid + 1
        return -1
# https://leetcode.cn/submissions/detail/378928407/
```

## 34. 在排序数组中查找元素的第一个和最后一个位置

<https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/>

```py
class Solution:
    def searchRange(self, nums: List[int], target: int) -> List[int]:
        return [self.search(nums, target, True), self.search(nums, target, False)]

    def search(self, nums: List[int], target: int, lower: bool) -> int:
        res = -1
        lo, hi = 0, len(nums) - 1
        while lo <= hi:
            mid = lo + (hi - lo) // 2
            if target < nums[mid]:
                hi = mid - 1
            elif nums[mid] < target:
                lo = mid + 1
            else:
                res = mid
                if lower:
                    hi = mid - 1
                else:
                    lo = mid + 1
        return res
# https://leetcode.cn/submissions/detail/380214793/
```

## 37. 解数独

<https://leetcode.cn/problems/sudoku-solver/>

```py
class Solution:
    def solveSudoku(self, board: List[List[str]]) -> None:
        self.backtrack(board, 0, -1)

    # 遍历『决策森林』
    # tree  = row
    # level = (row, col)
    def backtrack(self, board: List[List[str]], row: int, col: int) -> bool:
        n = len(board)
        res = False
        if row == n:
            res = True
        elif col == n - 1:
            # 遍历下一棵『决策树』
            res = self.backtrack(board, row + 1, -1)
        elif board[row][col + 1] != '.':
            res = self.backtrack(board, row, col + 1)
        else:
            # edge = ['1'..'9']
            for ch in '123456789':
                if self.isValid(board, row, col + 1, ch):
                    board[row][col + 1] = ch
                    res = self.backtrack(board, row, col + 1)
                    if res:
                        break
                    board[row][col + 1] = '.'
        return res

    # board[row][col] 填入数字 ch 是否有效
    def isValid(self, board: List[List[str]], row: int, col: int, ch: str) -> bool:
        for i in range(len(board)):
            # 同一行
            if board[row][i] == ch:
                return False
            # 同一列
            if board[i][col] == ch:
                return False
            # 同九宫
            if board[(row // 3) * 3 + i // 3][(col // 3) * 3 + i % 3] == ch:
                return False
        return True
# https://leetcode.cn/submissions/detail/379841387/
```

## 39. 组合总和

<https://leetcode.cn/problems/combination-sum/>

```py
class Solution:
    def __init__(self):
        self.pathSum = 0
        self.path = []  # 取 nums[edge] 为元素
        self.ans = []

    def combinationSum(self, candidates: List[int], target: int) -> List[List[int]]:
        self.backtrack(candidates, target, -1)
        return self.ans

    # edge = 取数组 nums 的索引为值
    def backtrack(self, nums: List[int], target: int, edge: int) -> None:
        if self.pathSum == target:
            self.ans.append(self.path.copy())
            return
        if edge == -1:
            edge = 0
        # 避免重复，从 edge 开始选择
        # 例如 [1->2] 和 [2->1] 是重复的
        for e in range(edge, len(nums)):
            x = nums[e]
            if self.pathSum + x <= target:
                self.pathSum += x
                self.path.append(x)
                self.backtrack(nums, target, e)
                self.pathSum -= x
                self.path.pop()
# https://leetcode.cn/submissions/detail/430080039/
```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```py
class Solution:
    def __init__(self):
        self.nums = None
        self.target = None
        self.pathSum = 0
        self.path = []  # 取 nums[edge] 为元素
        self.ans = []

    def combinationSum2(self, candidates: List[int], target: int) -> List[List[int]]:
        candidates.sort()
        self.nums = candidates
        self.target = target
        self.backtrack(-1)
        return self.ans

    # edge = 取数组 nums 的索引为值
    def backtrack(self, edge: int) -> None:
        if self.pathSum == self.target:
            self.ans.append(self.path.copy())
            return
        prev = None
        # 避免重复，从 edge + 1 开始选择
        # 例如 [1->2] 和 [2->1] 是重复的
        for e in range(edge + 1, len(self.nums)):
            x = self.nums[e]
            if x != prev and self.pathSum + x <= self.target:
                prev = x
                self.pathSum += x
                self.path.append(x)
                self.backtrack(e)
                self.pathSum -= x
                self.path.pop()
# https://leetcode.cn/submissions/detail/379641878/
```

## 42. 接雨水

<https://leetcode.cn/problems/trapping-rain-water/>

```py
class Solution:
    def trap(self, height: List[int]) -> int:
        n = len(height)
        # leftMax[i] = max(height[0..i])
        leftMax = height.copy()
        for i in range(1, n):
            leftMax[i] = max(height[i], leftMax[i - 1])
        # rightMax[i] = max(height[i..n-1])
        rightMax = height.copy()
        for i in range(n - 2, -1, -1):
            rightMax[i] = max(height[i], rightMax[i + 1])
        sum = 0
        for i in range(n):
            sum += min(leftMax[i], rightMax[i]) - height[i]
        return sum
# https://leetcode.cn/submissions/detail/378848303/
```

## 46. 全排列

<https://leetcode.cn/problems/permutations/>

```py
class Solution:
    def __init__(self):
        self.nums = None
        self.marked = None
        self.path = []  # 取 nums[edge] 为元素
        self.ans = []

    def permute(self, nums: List[int]) -> List[List[int]]:
        self.nums = nums
        self.marked = [False] * len(nums)
        self.backtrack()
        return self.ans

    def backtrack(self) -> None:
        n = len(self.nums)
        if len(self.path) == n:
            self.ans.append(self.path.copy())
        # edge = 取数组 nums 的索引为值
        for edge in range(n):
            if not self.marked[edge]:
                self.path.append(self.nums[edge])
                self.marked[edge] = True
                self.backtrack()
                self.path.pop()
                self.marked[edge] = False
# https://leetcode.cn/submissions/detail/379638155/
```

## 47. 全排列 II

<https://leetcode.cn/problems/permutations-ii/>

```py
class Solution:
    def __init__(self):
        self.nums = None
        self.marked = None
        self.path = []  # 取 nums[edge] 为元素
        self.ans = []

    def permuteUnique(self, nums: List[int]) -> List[List[int]]:
        nums.sort()
        self.nums = nums
        self.marked = [False] * len(nums)
        self.backtrack()
        return self.ans

    def backtrack(self) -> None:
        n = len(self.nums)
        if len(self.path) == n:
            self.ans.append(self.path.copy())
        prev = None
        # edge = 取数组 nums 的索引为值
        for edge in range(n):
            x = self.nums[edge]
            if not self.marked[edge] and x != prev:
                prev = x
                self.path.append(x)
                self.marked[edge] = True
                self.backtrack()
                self.path.pop()
                self.marked[edge] = False
# https://leetcode.cn/submissions/detail/379638888/
```

## 51. N 皇后

<https://leetcode.cn/problems/n-queens/>

```py
class Solution:
    def __init__(self):
        self.ans = []

    def solveNQueens(self, n: int) -> List[List[str]]:
        board = [['.'] * n for _ in range(n)]
        self.backtrack(board, -1)
        return self.ans

    # level = row
    def backtrack(self, board: List[List[str]], row: int) -> None:
        n = len(board)
        if row == n - 1:
            self.ans.append([''.join(x) for x in board])
            return
        # edge = col
        for col in range(n):
            if self.isValid(board, row + 1, col):
                board[row + 1][col] = 'Q'
                self.backtrack(board, row + 1)
                board[row + 1][col] = '.'

    # board[row][col] 放置 Q 是否有效
    def isValid(self, board: List[List[str]], row: int, col: int) -> bool:
        n = len(board)
        # 同一列
        for r in range(row):
            if board[r][col] == 'Q':
                return False
        # 右斜线
        r = row - 1
        c = col - 1
        while r >= 0 and c >= 0:
            if board[r][c] == 'Q':
                return False
            r -= 1
            c -= 1
        # 左斜线
        r = row - 1
        c = col + 1
        while r >= 0 and c < n:
            if board[r][c] == 'Q':
                return False
            r -= 1
            c += 1
        return True
# https://leetcode.cn/submissions/detail/379912024/
```

## 52. N 皇后 II

<https://leetcode.cn/problems/n-queens-ii/>

```py
class Solution:
    def __init__(self):
        self.ans = 0

    def totalNQueens(self, n: int) -> int:
        board = [['.'] * n for _ in range(n)]
        self.backtrack(board, -1)
        return self.ans

    # level = row
    def backtrack(self, board: List[List[str]], row: int) -> None:
        n = len(board)
        if row == n - 1:
            self.ans += 1
            return
        # edge = col
        for col in range(n):
            if self.isValid(board, row + 1, col):
                board[row + 1][col] = 'Q'
                self.backtrack(board, row + 1)
                board[row + 1][col] = '.'

    # board[row][col] 放置 Q 是否有效
    def isValid(self, board: List[List[str]], row: int, col: int) -> bool:
        n = len(board)
        # 同一列
        for r in range(row):
            if board[r][col] == 'Q':
                return False
        # 右斜线
        r = row - 1
        c = col - 1
        while r >= 0 and c >= 0:
            if board[r][c] == 'Q':
                return False
            r -= 1
            c -= 1
        # 左斜线
        r = row - 1
        c = col + 1
        while r >= 0 and c < n:
            if board[r][c] == 'Q':
                return False
            r -= 1
            c += 1
        return True
# https://leetcode.cn/submissions/detail/379912963/
```

## 53. 最大子数组和

<https://leetcode.cn/problems/maximum-subarray/>

```py
class Solution:
    def maxSubArray(self, nums: List[int]) -> int:
        n = len(nums)
        # dp[i] = max({sum(subarray) | subarray 是以 nums[i] 结尾的子数组})
        dp = [0] * n
        ans = dp[0] = nums[0]
        for i in range(1, n):
            dp[i] = max(nums[i], dp[i - 1] + nums[i])
            ans = max(ans, dp[i])
        return ans
# https://leetcode.cn/submissions/detail/379233096/
```

## 56. 合并区间

<https://leetcode.cn/problems/merge-intervals/>

```py
class Solution:
    def merge(self, intervals: List[List[int]]) -> List[List[int]]:
        intervals.sort(key=lambda interval: (interval[0], -interval[1]))
        ans = []
        mStart, mEnd = intervals[0]
        for i in range(1, len(intervals)):
            start, end = intervals[i]
            if start <= mEnd:
                # 重叠
                mEnd = max(mEnd, end)
            else:
                # 不重叠
                ans.append([mStart, mEnd])
                mStart, mEnd = start, end
        ans.append([mStart, mEnd])
        return ans
# https://leetcode.cn/submissions/detail/379137344/
```

```py
class Solution:
    def merge(self, intervals: List[List[int]]) -> List[List[int]]:
        def cmp(a, b):
            return b[1] - a[1] if a[0] == b[0] else a[0] - b[0]

        intervals.sort(key=functools.cmp_to_key(cmp))
        ans = []
        mStart, mEnd = intervals[0]
        for i in range(1, len(intervals)):
            start, end = intervals[i]
            if start <= mEnd:
                # 重叠
                mEnd = max(mEnd, end)
            else:
                # 不重叠
                ans.append([mStart, mEnd])
                mStart, mEnd = start, end
        ans.append([mStart, mEnd])
        return ans
# https://leetcode.cn/submissions/detail/379045710/
```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```py
class Solution:
    def __init__(self):
        self.memo = {}

    def minPathSum(self, grid: List[List[int]]) -> int:
        return self._minPathSum(grid, len(grid) - 1, len(grid[0]) - 1)

    # 从 grid[0][0] 到 grid[row][col] 的最小路径和
    def _minPathSum(self, grid: List[List[int]], row: int, col: int) -> int:
        if row < 0 or col < 0:
            return math.inf
        if row == 0 and col == 0:
            return grid[row][col]
        key = (row, col)
        if key not in self.memo:
            sp1 = self._minPathSum(grid, row - 1, col)  # 上
            sp2 = self._minPathSum(grid, row, col - 1)  # 左
            self.memo[key] = min(sp1, sp2) + grid[row][col]
        return self.memo[key]
# https://leetcode.cn/submissions/detail/379622187/
```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```py
class Solution:
    def mySqrt(self, x: int) -> int:
        if x == 0:
            return 0
        lo, hi = 1, x
        while True:
            mid = lo + (hi - lo) // 2
            if mid <= x // mid and (mid + 1) > x // (mid + 1):
                return mid
            if mid < x // mid:
                lo = mid + 1
            else:
                hi = mid - 1
        return -1
# https://leetcode.cn/submissions/detail/380215242/
```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```py
class Solution:
    def climbStairs(self, n: int) -> int:
        if n == 1:
            return 1
        if n == 2:
            return 2
        # dp[i] = 楼梯有 i 阶时，有几种不同的方法
        dp = [0] * (n + 1)
        dp[1] = 1
        dp[2] = 2
        for i in range(3, n + 1):
            dp[i] = dp[i - 1] + dp[i - 2]
        return dp[n]
# https://leetcode.cn/submissions/detail/380215679/
```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```py
class Solution:
    def __init__(self):
        self.memo = {}

    def minDistance(self, s1: str, s2: str) -> int:
        return self.dp(s1, len(s1) - 1, s2, len(s2) - 1)

    # 返回子串 s1[0..i] s2[0..j] 的最小编辑距离
    def dp(self, s1: str, i: int, s2: str, j: int) -> int:
        # 插入 s2[0..j] 到 s1
        # s1""
        # s2[0..j]
        if i < 0:
            return j + 1
        # 删除 s1[0..i]
        # s1[0..i]
        # s2""
        if j < 0:
            return i + 1
        if (i, j) not in self.memo:
            if s1[i] == s2[j]:
                # s1[0..i-1][i]
                # s2[0..j-1][j]
                self.memo[(i, j)] = self.dp(s1, i - 1, s2, j - 1)
            else:
                # 替换 s1[i] 为 s2[j]
                # s1[0..i-1][i]
                # s2[0..j-1][j]
                sp1 = self.dp(s1, i - 1, s2, j - 1) + 1
                # 插入 s2[j] 到 s1
                # s1[0..i]
                # s2[0..j-1][j]
                sp2 = self.dp(s1, i, s2, j - 1) + 1
                # 删除 s1[i]
                # s1[0..i-1][i]
                # s2[0..j]
                sp3 = self.dp(s1, i - 1, s2, j) + 1
                self.memo[(i, j)] = min(sp1, sp2, sp3)
        return self.memo[(i, j)]
# https://leetcode.cn/submissions/detail/433542854/
```

```py
class Solution:
    def minDistance(self, s1: str, s2: str) -> int:
        return self.dp(s1, len(s1) - 1, s2, len(s2) - 1)

    # 返回子串 s1[0..i] s2[0..j] 的最小编辑距离
    @cache
    def dp(self, s1: str, i: int, s2: str, j: int) -> int:
        # 插入 s2[0..j] 到 s1
        # s1""
        # s2[0..j]
        if i < 0:
            return j + 1
        # 删除 s1[0..i]
        # s1[0..i]
        # s2""
        if j < 0:
            return i + 1
        if s1[i] == s2[j]:
            # s1[0..i-1][i]
            # s2[0..j-1][j]
            return self.dp(s1, i - 1, s2, j - 1)
        else:
            # 替换 s1[i] 为 s2[j]
            # s1[0..i-1][i]
            # s2[0..j-1][j]
            sp1 = self.dp(s1, i - 1, s2, j - 1) + 1
            # 插入 s2[j] 到 s1
            # s1[0..i]
            # s2[0..j-1][j]
            sp2 = self.dp(s1, i, s2, j - 1) + 1
            # 删除 s1[i]
            # s1[0..i-1][i]
            # s2[0..j]
            sp3 = self.dp(s1, i - 1, s2, j) + 1
            return min(sp1, sp2, sp3)
# https://leetcode.cn/submissions/detail/433543228/
```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```py
class Solution:
    def sortColors(self, nums: List[int]) -> None:
        v = 1
        lt, gt = 0, len(nums) - 1
        i = 0
        while i <= gt:
            if nums[i] < v:
                nums[lt], nums[i] = nums[i], nums[lt]
                lt += 1
                i += 1
            elif nums[i] > v:
                nums[i], nums[gt] = nums[gt], nums[i]
                gt -= 1
            else:
                i += 1
# https://leetcode.cn/submissions/detail/380345213/
```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```py
class Solution:
    def minWindow(self, s: str, t: str) -> str:
        need = {}
        for c in t:
            need.setdefault(c, 0)
            need[c] += 1
        window = {}
        valid = 0
        start = 0
        length = math.inf
        # s[left..right) = Window Substring
        # s[right..n-1]  = Scanning
        left = right = 0
        while right < len(s):
            c = s[right]
            right += 1
            if c in need:
                window.setdefault(c, 0)
                window[c] += 1
                if window[c] == need[c]:
                    valid += 1
            if valid == len(need):
                while left < right:
                    d = s[left]
                    if (d in need) and window[d] == need[d]:
                        break
                    if d in need:
                        window[d] -= 1
                    left += 1
                if right - left < length:
                    start = left
                    length = right - left
        return '' if length == math.inf else s[start:start + length]
# https://leetcode.cn/submissions/detail/379018302/
```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```py
class Solution:
    def __init__(self):
        self.n = None
        self.k = None
        self.path = []  # 取 [1..n] 为元素
        self.ans = []

    def combine(self, n: int, k: int) -> List[List[int]]:
        self.n = n
        self.k = k
        self.backtrack(0)
        return self.ans

    # edge = 取 [1..n] 为值
    def backtrack(self, edge: int) -> None:
        if len(self.path) == self.k:
            self.ans.append(self.path.copy())
            return
        # 避免重复，从 edge + 1 开始选择
        # 例如 [1->2] 和 [2->1] 是重复的
        for e in range(edge + 1, self.n + 1):
            self.path.append(e)
            self.backtrack(e)
            self.path.pop()
# https://leetcode.cn/submissions/detail/379634980/
```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```py
class Solution:
    def __init__(self):
        self.nums = None
        self.path = []  # 取 nums[edge] 为元素
        self.ans = []

    def subsets(self, nums: List[int]) -> List[List[int]]:
        self.nums = nums
        self.backtrack(-1)
        return self.ans

    # edge = 取数组 nums 的索引为值
    def backtrack(self, edge: int) -> None:
        self.ans.append(self.path.copy())
        # 避免重复，从 edge + 1 开始选择
        # 例如 [1->2] 和 [2->1] 是重复的
        for e in range(edge + 1, len(self.nums)):
            self.path.append(self.nums[e])
            self.backtrack(e)
            self.path.pop()
# https://leetcode.cn/submissions/detail/379631791/
```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```py
class Solution:
    def search(self, nums: List[int], target: int) -> bool:
        lo = 0
        hi = len(nums) - 1
        while lo <= hi:
            mid = lo + (hi - lo) // 2
            if nums[mid] == target:
                return True
            if nums[lo] == nums[mid] == nums[hi]:
                lo += 1
                hi -= 1
            else:
                if nums[mid] <= nums[hi]:
                    if nums[mid] < target <= nums[hi]:
                        lo = mid + 1
                    else:
                        hi = mid - 1
                else:
                    if nums[lo] <= target < nums[mid]:
                        hi = mid - 1
                    else:
                        lo = mid + 1
        return False
# https://leetcode.cn/submissions/detail/378929481/
```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```py
class Solution:
    def deleteDuplicates(self, head: Optional[ListNode]) -> Optional[ListNode]:
        ptr = head
        while (ptr is not None) and (ptr.next is not None):
            if ptr.val == ptr.next.val:
                ptr.next = ptr.next.next
            else:
                ptr = ptr.next
        return head
# https://leetcode.cn/submissions/detail/380183992/
```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```py
class Solution:
    def partition(self, head: Optional[ListNode], x: int) -> Optional[ListNode]:
        lessPtr = lessDummyHead = ListNode()
        greaterPtr = greaterDummyHead = ListNode()
        while head is not None:
            if head.val < x:
                lessPtr.next = head
                lessPtr = lessPtr.next
            else:
                greaterPtr.next = head
                greaterPtr = greaterPtr.next
            head = head.next
        lessPtr.next = greaterDummyHead.next
        greaterPtr.next = None
        return lessDummyHead.next
# https://leetcode.cn/submissions/detail/380209407/
```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```py
class Solution:
    def __init__(self):
        self.path = []  # 取 nums[edge] 为元素
        self.ans = []

    def subsetsWithDup(self, nums: List[int]) -> List[List[int]]:
        self.backtrack(sorted(nums), -1)
        return self.ans

    # edge = 取数组 nums 的索引为值
    def backtrack(self, nums: List[int], edge: int) -> None:
        self.ans.append(self.path.copy())
        prev = None
        # 避免重复，从 edge + 1 开始选择
        # 例如 [1->2] 和 [2->1] 是重复的
        for e in range(edge + 1, len(nums)):
            x = nums[e]
            if x != prev:
                prev = x
                self.path.append(x)
                self.backtrack(nums, e)
                self.path.pop()
# https://leetcode.cn/submissions/detail/434400854/
```

## 92. 反转链表 II

<https://leetcode.cn/problems/reverse-linked-list-ii/>

```py
class Solution:
    def reverseBetween(self, head: Optional[ListNode], left: int, right: int) -> Optional[ListNode]:
        if left == 1:
            return self.reverseList(head, right)
        ptr = head
        for i in range(left - 2):
            ptr = ptr.next
        ptr.next = self.reverseList(ptr.next, right - left + 1)
        return head

    # 翻转链表的前 n 个节点，返回翻转后的头节点
    def reverseList(self, head: Optional[ListNode], n: int) -> Optional[ListNode]:
        reverseHead = None
        ptr = head
        while ptr is not None and n > 0:
            x = ptr.next
            ptr.next = reverseHead
            reverseHead = ptr
            ptr = x
            n -= 1
        head.next = ptr
        return reverseHead
# https://leetcode.cn/submissions/detail/378891261/
```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```py
class TreeNode:
    def __init__(self, val=0, left=None, right=None):
        self.val = val
        self.left = left
        self.right = right


class Solution:
    def __init__(self):
        self.ans = []

    def inorderTraversal(self, root: Optional[TreeNode]) -> List[int]:
        self.dfs(root)
        return self.ans

    def dfs(self, root: Optional[TreeNode]) -> None:
        if root is None:
            return
        self.dfs(root.left)
        self.ans.append(root.val)
        self.dfs(root.right)
# https://leetcode.cn/submissions/detail/379976808/
```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```py
class Solution:
    def generateTrees(self, n: int) -> List[Optional[TreeNode]]:
        return self._generateTrees(1, n)

    # 所有由 [lo..hi] 组成的节点值互不相同的不同二叉搜索树
    def _generateTrees(self, lo: int, hi: int) -> List[Optional[TreeNode]]:
        if lo > hi:
            return [None]
        res = []
        # 根节点为 i
        # 左子树由 [lo..i-1] 组成
        # 右子树由 [i+1..hi] 组成
        for i in range(lo, hi + 1):
            left = self._generateTrees(lo, i - 1)
            right = self._generateTrees(i + 1, hi)
            for l in left:
                for r in right:
                    res.append(TreeNode(i, l, r))
        return res
# https://leetcode.cn/submissions/detail/380049138/
```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```py
class Solution:
    # 由 n 个不同数字 x_1 < x_2 < ... < x_n
    # 组成的节点值互不相同的二叉搜索树的种数
    @cache
    def numTrees(self, n: int) -> int:
        if n == 0 or n == 1:
            return 1
        res = 0
        # 根节点为 x_i
        # 左子树由 i-1 个数字 x1 < x2 < ... < x_i-1 组成
        # 右子树由 n-i 个数字 x_i+1 < x_i+2 < ... < x_n 组成
        for i in range(1, n + 1):
            res += self.numTrees(i - 1) * self.numTrees(n - i)
        return res
# https://leetcode.cn/submissions/detail/380046582/
```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```py
class Solution:
    def __init__(self):
        self.ans = True

    def isValidBST(self, root: Optional[TreeNode]) -> bool:
        self.checkLowerAndUpperBound(root, None, None)
        return self.ans

    # 检查二叉树是否在区间 (lower, upper) 内，递归过程中确定是否满足二叉搜索树的性质
    def checkLowerAndUpperBound(self, root: Optional[TreeNode], lower: Optional[int], upper: Optional[int]) -> bool:
        if root is None:
            return True
        if (lower is not None) and root.val <= lower:
            self.ans = False
            return False
        if (upper is not None) and root.val >= upper:
            self.ans = False
            return False
        left = self.checkLowerAndUpperBound(root.left, lower, root.val)
        right = self.checkLowerAndUpperBound(root.right, root.val, upper)
        return left and right
# https://leetcode.cn/submissions/detail/380132027/
```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```py
class Solution:
    def isSameTree(self, p: Optional[TreeNode], q: Optional[TreeNode]) -> bool:
        if (p is None) and (q is None):
            return True
        if (p is None) or (q is None) or (p.val != q.val):
            return False
        return self.isSameTree(p.left, q.left) and self.isSameTree(p.right, q.right)
# https://leetcode.cn/submissions/detail/380120716/
```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```py
class Solution:
    def levelOrder(self, root: Optional[TreeNode]) -> List[List[int]]:
        ans = []
        q = deque()
        if root is not None:
            q.append(root)
        while len(q) > 0:
            level = []
            n = len(q)
            for _ in range(n):
                x = q.popleft()
                level.append(x.val)
                left = x.left
                if left is not None:
                    q.append(left)
                right = x.right
                if right is not None:
                    q.append(right)
            ans.append(level)
        return ans
# https://leetcode.cn/submissions/detail/435841848/
```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode.cn/problems/binary-tree-zigzag-level-order-traversal/>

```py
class Solution:
    def zigzagLevelOrder(self, root: Optional[TreeNode]) -> List[List[int]]:
        ans = []
        q = deque()
        if root is not None:
            q.append(root)
        reverse = False
        while len(q) > 0:
            level = []
            n = len(q)
            for i in range(n):
                x = q.popleft()
                level.append(x.val)
                left = x.left
                if left is not None:
                    q.append(left)
                right = x.right
                if right is not None:
                    q.append(right)
            if reverse:
                level.reverse()
            reverse = not reverse
            ans.append(level)
        return ans
# https://leetcode.cn/submissions/detail/379988860/
```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```py
class Solution:
    def maxDepth(self, root: Optional[TreeNode]) -> int:
        if root is None:
            return 0
        return 1 + max(self.maxDepth(root.left), self.maxDepth(root.right))
# https://leetcode.cn/submissions/detail/380117622/
```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```py
class Solution:
    def __init__(self):
        self.valToIndex = {}

    def buildTree(self, preorder: List[int], inorder: List[int]) -> Optional[TreeNode]:
        for i in range(len(inorder)):
            self.valToIndex[inorder[i]] = i
        return self._buildTree(preorder, 0, len(preorder) - 1, inorder, 0, len(inorder) - 1)

    def _buildTree(self, preorder: List[int], preStart: int, preEnd: int, inorder: List[int], inStart: int,
                   inEnd: int) -> Optional[TreeNode]:
        if preStart > preEnd:
            return None
        rootVal = preorder[preStart]
        index = self.valToIndex[rootVal]
        leftSize = index - inStart
        root = TreeNode(rootVal)
        root.left = self._buildTree(preorder, preStart + 1, preStart + leftSize, inorder, inStart, index - 1)
        root.right = self._buildTree(preorder, preStart + leftSize + 1, preEnd, inorder, index + 1, inEnd)
        return root
# https://leetcode.cn/submissions/detail/379995506/
```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```py
class Solution:
    def __init__(self):
        self.valToIndex = {}

    def buildTree(self, inorder: List[int], postorder: List[int]) -> Optional[TreeNode]:
        for i in range(len(inorder)):
            self.valToIndex[inorder[i]] = i
        return self._buildTree(inorder, 0, len(inorder) - 1, postorder, 0, len(postorder) - 1)

    def _buildTree(self, inorder: List[int], inStart: int, inEnd: int, postorder: List[int], postStart: int,
                   postEnd: int) -> Optional[TreeNode]:
        if inStart > inEnd:
            return None
        rootVal = postorder[postEnd]
        index = self.valToIndex[rootVal]
        leftSize = index - inStart
        root = TreeNode(rootVal)
        root.left = self._buildTree(inorder, inStart, index - 1, postorder, postStart, postStart + leftSize - 1)
        root.right = self._buildTree(inorder, index + 1, inEnd, postorder, postStart + leftSize, postEnd - 1)
        return root
# https://leetcode.cn/submissions/detail/379997202/
```

## 107. 二叉树的层序遍历 II

<https://leetcode.cn/problems/binary-tree-level-order-traversal-ii/>

```py
class Solution:
    def levelOrderBottom(self, root: Optional[TreeNode]) -> List[List[int]]:
        ans = []
        q = deque()
        if root is not None:
            q.append(root)
        while len(q) > 0:
            level = []
            n = len(q)
            for i in range(n):
                x = q.popleft()
                level.append(x.val)
                left = x.left
                if left is not None:
                    q.append(left)
                right = x.right
                if right is not None:
                    q.append(right)
            ans.append(level)
        ans.reverse()
        return ans
# https://leetcode.cn/submissions/detail/379987801/
```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```py
class Solution:
    def sortedArrayToBST(self, nums: List[int]) -> Optional[TreeNode]:
        return self.sortedArrayToBSTRange(nums, 0, len(nums) - 1)

    # 将有序子数组 nums[lo..hi] 转换为二叉搜索树
    def sortedArrayToBSTRange(self, nums: List[int], lo: int, hi: int) -> Optional[TreeNode]:
        if lo > hi:
            return None
        mid = lo + (hi - lo) // 2
        root = TreeNode(nums[mid])
        root.left = self.sortedArrayToBSTRange(nums, lo, mid - 1)
        root.right = self.sortedArrayToBSTRange(nums, mid + 1, hi)
        return root
# https://leetcode.cn/submissions/detail/393687141/
```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```py
class Solution:
    def __init__(self):
        self.ans = True

    def isBalanced(self, root: Optional[TreeNode]) -> bool:
        self.height(root)
        return self.ans

    def height(self, root: Optional[TreeNode]) -> int:
        if root is None:
            return -1
        left = self.height(root.left)
        right = self.height(root.right)
        if abs(left - right) > 1:
            self.ans = False
        return 1 + max(left, right)
# https://leetcode.cn/submissions/detail/380127232/
```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```py
class Solution:
    def minDepth(self, root: Optional[TreeNode]) -> int:
        depth = 0
        q = deque()
        if root is not None:
            q.append(root)
        while len(q) > 0:
            depth += 1
            n = len(q)
            for _ in range(n):
                x = q.popleft()
                left = x.left
                right = x.right
                if (left is None) and (right is None):
                    return depth
                if left is not None:
                    q.append(left)
                if right is not None:
                    q.append(right)
        return 0
# https://leetcode.cn/submissions/detail/437322341/
```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```py
class Solution:
    def hasPathSum(self, root: Optional[TreeNode], targetSum: int) -> bool:
        if root is None:
            return False
        if (root.left is None) and (root.right is None):
            return root.val == targetSum
        return self.hasPathSum(root.left, targetSum - root.val) or self.hasPathSum(root.right, targetSum - root.val)
# https://leetcode.cn/submissions/detail/380297443/
```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```py
class Solution:
    def flatten(self, root: Optional[TreeNode]) -> None:
        if root is None:
            return
        self.flatten(root.left)
        self.flatten(root.right)
        left = root.left
        right = root.right
        root.left = None
        root.right = left
        ptr = root
        while ptr.right is not None:
            ptr = ptr.right
        ptr.right = right
# https://leetcode.cn/submissions/detail/380124010/
```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```py
# TODO
```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```py
class Solution:
    def maxProfit(self, prices: List[int]) -> int:
        n = len(prices)
        # dp[i][0] = 第 i 天，空仓状态下的最大利润
        # dp[i][1] = 第 i 天，持仓状态下的最大利润
        dp = [[0] * 2 for _ in range(n)]
        dp[0][0] = 0
        dp[0][1] = -prices[0]
        for i in range(1, n):
            # dp[i - 1][0]             >= -prices[i]
            # dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            # => dp[i][0] >= dp[i][1]
            dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i])
            dp[i][1] = max(-prices[i], dp[i - 1][1])
        return dp[n - 1][0]
# https://leetcode.cn/submissions/detail/379358404/
```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```py
class Solution:
    def maxProfit(self, prices: List[int]) -> int:
        n = len(prices)
        # dp[i][0] = 第 i 天，空仓状态下的最大利润
        # dp[i][1] = 第 i 天，持仓状态下的最大利润
        dp = [[0] * 2 for _ in range(n)]
        dp[0][0] = 0
        dp[0][1] = -prices[0]
        for i in range(1, n):
            # dp[i - 1][0]             >= dp[i - 1][0] - prices[i]
            # dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            # => dp[i][0] >= dp[i][1]
            dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i])
            dp[i][1] = max(dp[i - 1][0] - prices[i], dp[i - 1][1])
        return dp[n - 1][0]
# https://leetcode.cn/submissions/detail/379359304/
```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```py
class Solution:
    def maxProfit(self, prices: List[int]) -> int:
        return self._maxProfit(2, prices)

    def _maxProfit(self, k: int, prices: List[int]) -> int:
        n = len(prices)
        if k <= 0 or n <= 1:
            return 0
        # dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
        # dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
        dp = [[[0] * 2 for _ in range(n)] for _ in range(k + 1)]
        # 交易次数限制为 0 时
        # 填写第 0 个 n x 2 矩阵
        for i in range(n):
            dp[0][i][0] = 0
            dp[0][i][1] = -math.inf
        # 交易次数限制为 [1..k] 时
        # 填写第 t 个 n x 2 矩阵
        for t in range(1, k + 1):
            dp[t][0][0] = 0
            dp[t][0][1] = -prices[0]
            for i in range(1, n):
                # dp[t][i - 1][0]             >= dp[t - 1][i - 1][0] - prices[i]
                # dp[t][i - 1][1] + prices[i] >= dp[t][i - 1][1]
                # => dp[t][i][0] >= dp[t][i][1]
                dp[t][i][0] = max(dp[t][i - 1][0], dp[t][i - 1][1] + prices[i])
                dp[t][i][1] = max(dp[t - 1][i - 1][0] - prices[i], dp[t][i - 1][1])
        return dp[k][n - 1][0]
# https://leetcode.cn/submissions/detail/379363236/
```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```py
class Solution:
    def isPalindrome(self, s: str) -> bool:
        i = 0
        j = len(s) - 1
        while i < j:
            while i < j and not s[i].isalnum():
                i += 1
            while i < j and not s[j].isalnum():
                j -= 1
            if s[i].lower() != s[j].lower():
                return False
            i += 1
            j -= 1
        return True
# https://leetcode.cn/submissions/detail/378874027/
```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```py
class Solution:
    def longestConsecutive(self, nums: List[int]) -> int:
        ans = 0
        numSet = set(nums)
        for x in nums:
            if x in numSet:
                lo = x - 1
                while lo in numSet:
                    numSet.remove(lo)
                    lo -= 1
                hi = x + 1
                while hi in numSet:
                    numSet.remove(hi)
                    hi += 1
                ans = max(ans, hi - lo - 1)
                numSet.remove(x)
        return ans
# https://leetcode.cn/submissions/detail/380059965/
```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```py
class Solution:
    LAND = 'O'
    WATER = 'X'

    def __init__(self):
        self.mark = False
        self.recovery = set()

    def solve(self, grid: List[List[str]]) -> None:
        m = len(grid)
        n = len(grid[0])
        self.mark = True
        # 淹没与左右边界的陆地相连的岛屿
        for row in range(m):
            self.floodFill(grid, row, 0)
            self.floodFill(grid, row, n - 1)
        # 淹没与上下边界的陆地相连的岛屿
        for col in range(n):
            self.floodFill(grid, 0, col)
            self.floodFill(grid, m - 1, col)
        self.mark = False
        # 淹没封闭岛屿
        for row in range(m):
            for col in range(n):
                self.floodFill(grid, row, col)
        # 重建原来与边界陆地相连的岛屿
        for x in self.recovery:
            row = x[0]
            col = x[1]
            grid[row][col] = Solution.LAND

    def floodFill(self, grid: List[List[str]], row: int, col: int) -> None:
        if row < 0 or row >= len(grid) or col < 0 or col >= len(grid[0]) or grid[row][col] == Solution.WATER:
            return
        if self.mark:
            self.recovery.add((row, col))
        grid[row][col] = Solution.WATER
        self.floodFill(grid, row - 1, col)
        self.floodFill(grid, row + 1, col)
        self.floodFill(grid, row, col - 1)
        self.floodFill(grid, row, col + 1)
# https://leetcode.cn/submissions/detail/437929296/
```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```py
class Solution:
    def singleNumber(self, nums: List[int]) -> int:
        ans = 0
        for x in nums:
            ans ^= x
        return ans
# https://leetcode.cn/submissions/detail/380301369/
```

## 141. 环形链表

<https://leetcode.cn/problems/linked-list-cycle/>

```py
class Solution:
    def hasCycle(self, head: Optional[ListNode]) -> bool:
        slow = fast = head
        while (fast is not None) and (fast.next is not None):
            slow = slow.next
            fast = fast.next.next
            if slow is fast:
                return True
        return False
# https://leetcode.cn/submissions/detail/393497407/
```

## 142. 环形链表 II

<https://leetcode.cn/problems/linked-list-cycle-ii/>

```py
class Solution:
    def detectCycle(self, head: Optional[ListNode]) -> Optional[ListNode]:
        slow = fast = head
        while (fast is not None) and (fast.next is not None):
            slow = slow.next
            fast = fast.next.next
            if slow is fast:
                fast = head
                while slow is not fast:
                    slow = slow.next
                    fast = fast.next
                return slow
        return None
# https://leetcode.cn/submissions/detail/403432491/
```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```py
class Solution:
    def reorderList(self, head: Optional[ListNode]) -> None:
        slow = fast = head
        while (fast.next is not None) and (fast.next.next is not None):
            slow = slow.next
            fast = fast.next.next
        reverseHead = self.reverseList(slow.next)
        slow.next = None
        ptr = ListNode()
        while head is not None:
            ptr.next = head
            ptr = ptr.next
            head = head.next
            if reverseHead is not None:
                ptr.next = reverseHead
                ptr = ptr.next
                reverseHead = reverseHead.next

    def reverseList(self, head: Optional[ListNode]) -> Optional[ListNode]:
        reverseHead = None
        while head is not None:
            x = head.next
            head.next = reverseHead
            reverseHead = head
            head = x
        return reverseHead
# https://leetcode.cn/submissions/detail/438457650/
```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```py
class Solution:
    def __init__(self):
        self.ans = []

    def preorderTraversal(self, root: Optional[TreeNode]) -> List[int]:
        self.dfs(root)
        return self.ans

    def dfs(self, root: Optional[TreeNode]) -> None:
        if root is None:
            return
        self.ans.append(root.val)
        self.dfs(root.left)
        self.dfs(root.right)
# https://leetcode.cn/submissions/detail/379975704/
```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```py
class Solution:
    def __init__(self):
        self.ans = []

    def postorderTraversal(self, root: Optional[TreeNode]) -> List[int]:
        self.dfs(root)
        return self.ans

    def dfs(self, root: Optional[TreeNode]) -> None:
        if root is None:
            return
        self.dfs(root.left)
        self.dfs(root.right)
        self.ans.append(root.val)
# https://leetcode.cn/submissions/detail/379977598/
```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```py
class MyListNode:
    def __init__(self, key: int, val: int):
        self.key = key
        self.val = val
        self.prev = None
        self.next = None


class MyDoublyLinkedList:
    def __init__(self):
        self.__first = None
        self.__last = None
        self.__n = 0

    def addLast(self, x: MyListNode) -> None:
        if self.__n == 0:
            self.__first = x
            self.__last = x
            self.__n = 1
        else:
            self.__last.next = x
            x.prev = self.__last
            self.__last = x
            self.__n += 1

    def removeFirst(self) -> MyListNode:
        oldFirst = self.__first
        if self.__n == 1:
            self.__first = None
            self.__last = None
            self.__n = 0
        else:
            self.__first = self.__first.next
            self.__first.prev = None
            oldFirst.next = None
            self.__n -= 1
        return oldFirst

    def removeLast(self) -> MyListNode:
        oldLast = self.__last
        if self.__n == 1:
            self.__first = None
            self.__last = None
            self.__n = 0
        else:
            self.__last = self.__last.prev
            self.__last.next = None
            oldLast.prev = None
            self.__n -= 1
        return oldLast

    def remove(self, x: MyListNode) -> None:
        if x is self.__first:
            self.removeFirst()
        elif x is self.__last:
            self.removeLast()
        else:
            x.prev.next = x.next
            x.next.prev = x.prev
            x.prev = None
            x.next = None
            self.__n -= 1


class LRUCache:
    def __init__(self, capacity: int):
        self.__capacity = capacity
        self.__list = MyDoublyLinkedList()
        self.__keyToNode = {}

    def get(self, key: int) -> int:
        if self.__contains(key):
            return self.__touchCache(key, None)
        return -1

    def put(self, key: int, value: int) -> None:
        if self.__capacity > 0:
            if self.__contains(key):
                self.__touchCache(key, value)
            else:
                if self.__full():
                    self.__removeCache()
                self.__addCache(key, value)

    def __contains(self, key: int) -> bool:
        return key in self.__keyToNode

    def __full(self) -> bool:
        return len(self.__keyToNode) == self.__capacity

    def __addCache(self, key: int, val: int) -> None:
        x = MyListNode(key, val)
        self.__list.addLast(x)
        self.__keyToNode[key] = x

    def __removeCache(self) -> None:
        self.__keyToNode.pop(self.__list.removeFirst().key)

    def __touchCache(self, key: int, val: Optional[int]) -> int:
        x = self.__keyToNode[key]
        if val is not None:
            x.val = val
        self.__list.remove(x)
        self.__list.addLast(x)
        return x.val
# https://leetcode.cn/submissions/detail/441422814/
```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```py
class Solution:
    def findMin(self, nums: List[int]) -> int:
        lo = 0
        hi = len(nums) - 1
        while lo < hi:
            mid = lo + (hi - lo) // 2
            if nums[mid] < nums[hi]:
                hi = mid
            else:
                lo = mid + 1
        return nums[lo]
# https://leetcode.cn/submissions/detail/378926511/
```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```py
class MinStack:
    def __init__(self):
        self.stack = []

    def push(self, val: int) -> None:
        minval = val if len(self.stack) == 0 else min(self.getMin(), val)
        self.stack.append((val, minval))

    def pop(self) -> None:
        self.stack.pop()

    def top(self) -> int:
        return self.stack[-1][0]

    def getMin(self) -> int:
        return self.stack[-1][1]
# https://leetcode.cn/submissions/detail/380067650/
```

## 160. 相交链表

<https://leetcode.cn/problems/intersection-of-two-linked-lists/>

```py
class Solution:
    def getIntersectionNode(self, headA: ListNode, headB: ListNode) -> Optional[ListNode]:
        ptrA = headA
        ptrB = headB
        while ptrA is not ptrB:
            ptrA = headB if ptrA is None else ptrA.next
            ptrB = headA if ptrB is None else ptrB.next
        return ptrA
# https://leetcode.cn/submissions/detail/378717241/
```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```py
class Solution:
    DOT = ord('.')
    ZERO = ord('0')

    def compareVersion(self, version1: str, version2: str) -> int:
        bytes1 = version1.encode()
        bytes2 = version2.encode()
        n1 = len(bytes1)
        n2 = len(bytes2)
        i, j = 0, 0
        while i < n1 or j < n2:
            r1 = 0
            while i < n1:
                ch = bytes1[i]
                i += 1
                if ch == Solution.DOT:
                    break
                r1 = r1 * 10 + ch - Solution.ZERO
            r2 = 0
            while j < n2:
                ch = bytes2[j]
                j += 1
                if ch == Solution.DOT:
                    break
                r2 = r2 * 10 + ch - Solution.ZERO
            if r1 > r2:
                return 1
            if r1 < r2:
                return -1
        return 0
# https://leetcode.cn/submissions/detail/380189352/
```

```py
class Solution:
    def compareVersion(self, version1: str, version2: str) -> int:
        n1 = len(version1)
        n2 = len(version2)
        i, j = 0, 0
        while i < n1 or j < n2:
            r1 = 0
            while i < n1:
                ch = version1[i]
                i += 1
                if ch == '.':
                    break
                r1 = r1 * 10 + ord(ch) - ord('0')
            r2 = 0
            while j < n2:
                ch = version2[j]
                j += 1
                if ch == '.':
                    break
                r2 = r2 * 10 + ord(ch) - ord('0')
            if r1 > r2:
                return 1
            if r1 < r2:
                return -1
        return 0
# https://leetcode.cn/submissions/detail/380189826/
```

## 167. 两数之和 II - 输入有序数组

<https://leetcode.cn/problems/two-sum-ii-input-array-is-sorted/>

```py
class Solution:
    def twoSum(self, numbers: List[int], target: int) -> List[int]:
        i = 0
        j = len(numbers) - 1
        while i < j:
            sum = numbers[i] + numbers[j]
            if sum < target:
                i += 1
            elif sum > target:
                j -= 1
            else:
                return [i + 1, j + 1]
        return [-1, -1]
# https://leetcode.cn/submissions/detail/378698010/
```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```py
class Solution:
    def majorityElement(self, nums: List[int]) -> int:
        candidate = math.inf
        count = 0
        for x in nums:
            if count == 0:
                candidate = x
                count = 1
            else:
                if x == candidate:
                    count += 1
                else:
                    count -= 1
        return candidate
# https://leetcode.cn/submissions/detail/380182891/
```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```py
class Solution:
    def largestNumber(self, nums: List[int]) -> str:
        strs = [str(x) for x in nums]

        def cmp(s1, s2):
            a = s1 + s2
            b = s2 + s1
            if a > b:
                return -1
            if a < b:
                return 1
            return 0

        strs.sort(key=functools.cmp_to_key(cmp))
        ans = ''.join(strs)
        return '0' if ans[0] == '0' else ans
# https://leetcode.cn/submissions/detail/380213463/
```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```py
class Solution:
    def maxProfit(self, k: int, prices: List[int]) -> int:
        n = len(prices)
        if k <= 0 or n <= 1:
            return 0
        # dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
        # dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
        dp = [[[0] * 2 for _ in range(n)] for _ in range(k + 1)]
        # 交易次数限制为 0 时
        # 填写第 0 个 n x 2 矩阵
        for i in range(n):
            dp[0][i][0] = 0
            dp[0][i][1] = -math.inf
        # 交易次数限制为 [1..k] 时
        # 填写第 t 个 n x 2 矩阵
        for t in range(1, k + 1):
            dp[t][0][0] = 0
            dp[t][0][1] = -prices[0]
            for i in range(1, n):
                # dp[t][i - 1][0]             >= dp[t - 1][i - 1][0] - prices[i]
                # dp[t][i - 1][1] + prices[i] >= dp[t][i - 1][1]
                # => dp[t][i][0] >= dp[t][i][1]
                dp[t][i][0] = max(dp[t][i - 1][0], dp[t][i - 1][1] + prices[i])
                dp[t][i][1] = max(dp[t - 1][i - 1][0] - prices[i], dp[t][i - 1][1])
        return dp[k][n - 1][0]
# https://leetcode.cn/submissions/detail/379362384/
```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```py
class Solution:
    def rotate(self, nums: List[int], k: int) -> None:
        n = len(nums)
        k %= n
        self.reverse(nums, 0, n - 1)
        self.reverse(nums, 0, k - 1)
        self.reverse(nums, k, n - 1)

    def reverse(self, nums: List[int], lo: int, hi: int) -> None:
        while lo < hi:
            nums[lo], nums[hi] = nums[hi], nums[lo]
            lo += 1
            hi -= 1
# https://leetcode.cn/submissions/detail/378924954/
```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```py
class Solution:
    def rob(self, nums: List[int]) -> int:
        return self.subseqSum(nums)

    # max({sum(subseq) | subseq 是数组 nums 的不连续子序列})
    def subseqSum(self, nums: List[int]) -> int:
        n = len(nums)
        if n == 0:
            return 0
        if n == 1:
            return nums[0]
        # dp[i] = max({sum(subseq) | subseq 是子数组 nums[0..i] 的不连续子序列})
        dp = [0] * n
        dp[0] = nums[0]
        dp[1] = max(nums[0], nums[1])
        for i in range(2, n):
            # 包含 nums[i]
            sp1 = dp[i - 2] + nums[i]
            # 不包含 nums[i]
            sp2 = dp[i - 1]
            dp[i] = max(sp1, sp2)
        return dp[n - 1]
# https://leetcode.cn/submissions/detail/379343781/
```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```py
class Solution:
    def rightSideView(self, root: Optional[TreeNode]) -> List[int]:
        ans = []
        q = deque()
        if root is not None:
            q.append(root)
        while len(q) > 0:
            ans.append(q[-1].val)
            n = len(q)
            for i in range(n):
                x = q.popleft()
                left = x.left
                if left is not None:
                    q.append(left)
                right = x.right
                if right is not None:
                    q.append(right)
        return ans
# https://leetcode.cn/submissions/detail/379990630/
```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```py
class Solution:
    LAND = '1'
    WATER = '0'

    def numIslands(self, grid: List[List[str]]) -> int:
        count = 0
        for row in range(len(grid)):
            for col in range(len(grid[0])):
                if grid[row][col] == Solution.LAND:
                    self.floodFill(grid, row, col)
                    count += 1
        return count

    def floodFill(self, grid: List[List[str]], row: int, col: int) -> None:
        if row < 0 or row >= len(grid) or col < 0 or col >= len(grid[0]) or grid[row][col] == Solution.WATER:
            return
        grid[row][col] = Solution.WATER
        self.floodFill(grid, row - 1, col)
        self.floodFill(grid, row + 1, col)
        self.floodFill(grid, row, col - 1)
        self.floodFill(grid, row, col + 1)
# https://leetcode.cn/submissions/detail/380248973/
```

## 203. 移除链表元素

<https://leetcode.cn/problems/remove-linked-list-elements/>

```py
class Solution:
    def removeElements(self, head: Optional[ListNode], val: int) -> Optional[ListNode]:
        ptr = dummyHead = ListNode(-1, head)
        while ptr.next is not None:
            if ptr.next.val == val:
                ptr.next = ptr.next.next
            else:
                ptr = ptr.next
        return dummyHead.next
# https://leetcode.cn/submissions/detail/378922761/
```

## 206. 反转链表

<https://leetcode.cn/problems/reverse-linked-list/>

```py
class Solution:
    def reverseList(self, head: Optional[ListNode]) -> Optional[ListNode]:
        reverseHead = None
        while head is not None:
            x = head.next
            head.next = reverseHead
            reverseHead = head
            head = x
        return reverseHead
# https://leetcode.cn/submissions/detail/378888438/
```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```py
class Solution:
    def __init__(self):
        self.marked = None
        self.onStack = None
        self.hasCycle = False

    def canFinish(self, numCourses: int, prerequisites: List[List[int]]) -> bool:
        graph = [[] for _ in range(numCourses)]
        for p in prerequisites:
            v, w = p[1], p[0]
            graph[v].append(w)
        self.marked = [False] * numCourses
        self.onStack = [False] * numCourses
        for v in range(numCourses):
            if not self.marked[v]:
                self.dfs(graph, v)
                if self.hasCycle:
                    break
        return not self.hasCycle

    def dfs(self, graph: List[List[int]], v: int) -> None:
        self.onStack[v] = True
        self.marked[v] = True
        for w in graph[v]:
            if not self.marked[w]:
                self.dfs(graph, w)
            elif self.onStack[w]:
                self.hasCycle = True
                return
        self.onStack[v] = False
# https://leetcode.cn/submissions/detail/380404957/
```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```py
class Solution:
    def __init__(self):
        self.marked = None
        self.onStack = None
        self.postorder = []
        self.hasCycle = False

    def findOrder(self, numCourses: int, prerequisites: List[List[int]]) -> List[int]:
        if self.canFinish(numCourses, prerequisites):
            return self.postorder
        return []

    def canFinish(self, numCourses: int, prerequisites: List[List[int]]) -> bool:
        graph = [[] for _ in range(numCourses)]
        for p in prerequisites:
            v, w = p[0], p[1]
            graph[v].append(w)
        self.marked = [False] * numCourses
        self.onStack = [False] * numCourses
        for v in range(numCourses):
            if not self.marked[v]:
                self.dfs(graph, v)
                if self.hasCycle:
                    break
        return not self.hasCycle

    def dfs(self, graph: List[List[int]], v: int) -> None:
        self.onStack[v] = True
        self.marked[v] = True
        for w in graph[v]:
            if not self.marked[w]:
                self.dfs(graph, w)
            elif self.onStack[w]:
                self.hasCycle = True
                return
        self.postorder.append(v)
        self.onStack[v] = False
# https://leetcode.cn/submissions/detail/380406746/
```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```py
class Solution:
    def rob(self, nums: List[int]) -> int:
        n = len(nums)
        if n == 0:
            return 0
        if n == 1:
            return nums[0]
        return max(self.subseqSum(nums[:-1]), self.subseqSum(nums[1:]))

    # max({sum(subseq) | subseq 是数组 nums 的不连续子序列})
    def subseqSum(self, nums: List[int]) -> int:
        n = len(nums)
        if n == 0:
            return 0
        if n == 1:
            return nums[0]
        # dp[i] = max({sum(subseq) | subseq 是子数组 nums[0..i] 的不连续子序列})
        dp = [0] * n
        dp[0] = nums[0]
        dp[1] = max(nums[0], nums[1])
        for i in range(2, n):
            # 包含 nums[i]
            sp1 = dp[i - 2] + nums[i]
            # 不包含 nums[i]
            sp2 = dp[i - 1]
            dp[i] = max(sp1, sp2)
        return dp[n - 1]
# https://leetcode.cn/submissions/detail/379352325/
```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```py
class Solution:
    def findKthLargest(self, nums: List[int], k: int) -> int:
        shuffle(nums)
        return self.quickSelect(nums, len(nums) - k)

    # 数组 nums 从小到大排在第 rank 位的元素，排位从 0 开始计算，
    # 相当于有 rank 个元素小于该元素。
    def quickSelect(self, nums: List[int], rank: int) -> int:
        lo, hi = 0, len(nums) - 1
        while lo < hi:
            j = self.partition(nums, lo, hi)
            if rank < j:
                hi = j - 1
            elif j < rank:
                lo = j + 1
            else:
                return nums[j]
        return nums[lo]

    def partition(self, nums: List[int], lo: int, hi: int) -> int:
        v = nums[lo]
        i, j = lo, hi + 1
        while True:
            i += 1
            while nums[i] < v:
                if i == hi:
                    break
                i += 1
            j -= 1
            while nums[j] > v:
                if j == lo:
                    break
                j -= 1
            if i >= j:
                break
            nums[i], nums[j] = nums[j], nums[i]
        nums[lo], nums[j] = nums[j], nums[lo]
        return j
# https://leetcode.cn/submissions/detail/442873594/
```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```py
class Solution:
    def __init__(self):
        self.k = None
        self.n = None
        self.pathSum = 0
        self.path = []  # 取 [1..9] 为元素
        self.ans = []

    def combinationSum3(self, k: int, n: int) -> List[List[int]]:
        self.k = k
        self.n = n
        self.backtrack(0)
        return self.ans

    # edge = 取 [1..9] 为值
    def backtrack(self, edge: int) -> None:
        if len(self.path) == self.k and self.pathSum == self.n:
            self.ans.append(self.path.copy())
        elif len(self.path) < self.k and self.pathSum < self.n:
            # 避免重复，从 edge + 1 开始选择
            # 例如 [1->2] 和 [2->1] 是重复的
            for e in range(edge + 1, 10):
                if self.pathSum + e <= self.n:
                    self.pathSum += e
                    self.path.append(e)
                    self.backtrack(e)
                    self.pathSum -= e
                    self.path.pop()
# https://leetcode.cn/submissions/detail/379643434/
```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```py
class Solution:
    def countNodes(self, root: Optional[TreeNode]) -> int:
        if root is None:
            return 0
        leftHeight = 0
        ptr = root
        while ptr is not None:
            leftHeight += 1
            ptr = ptr.left
        rightHeight = 0
        ptr = root
        while ptr is not None:
            rightHeight += 1
            ptr = ptr.right
        if leftHeight == rightHeight:
            return 2 ** leftHeight - 1
        return 1 + self.countNodes(root.left) + self.countNodes(root.right)
# https://leetcode.cn/submissions/detail/380296123/
```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```py
class MyStack:
    def __init__(self):
        self.q = deque()

    def push(self, x: int) -> None:
        self.q.append(x)
        for i in range(len(self.q) - 1):
            self.q.append(self.q.popleft())

    def pop(self) -> int:
        return self.q.popleft()

    def top(self) -> int:
        return self.q[0]

    def empty(self) -> bool:
        return len(self.q) == 0
# https://leetcode.cn/submissions/detail/380065369/
```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```py
class Solution:
    def invertTree(self, root: Optional[TreeNode]) -> Optional[TreeNode]:
        if root is None:
            return None
        left = self.invertTree(root.left)
        right = self.invertTree(root.right)
        root.left, root.right = right, left
        return root
# https://leetcode.cn/submissions/detail/380122501/
```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```py
class Solution:
    def kthSmallest(self, root: Optional[TreeNode], k: int) -> int:
        return self._select(root, k - 1)

    def _select(self, root: Optional[TreeNode], rank: int) -> int:
        if root is None:
            return -1
        leftSize = self._size(root.left)
        if rank < leftSize:
            return self._select(root.left, rank)
        if leftSize < rank:
            return self._select(root.right, rank - leftSize - 1)
        return root.val

    @cache
    def _size(self, root: Optional[TreeNode]) -> int:
        if root is None:
            return 0
        return 1 + self._size(root.left) + self._size(root.right)
# https://leetcode.cn/submissions/detail/469886518/
```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```py
# ------------------| |--------------------
# pop <- Left Stack | | Right Stack <- push
# ------------------| |--------------------
class MyQueue:
    def __init__(self):
        self.leftStack = []
        self.rightStack = []

    def push(self, x: int) -> None:
        self.rightStack.append(x)

    def pop(self) -> int:
        if len(self.leftStack) == 0:
            self.move()
        return self.leftStack.pop()

    def peek(self) -> int:
        if len(self.leftStack) == 0:
            self.move()
        return self.leftStack[-1]

    def empty(self) -> bool:
        return len(self.leftStack) == 0 and len(self.rightStack) == 0

    def move(self) -> None:
        while len(self.rightStack) > 0:
            self.leftStack.append(self.rightStack.pop())
# https://leetcode.cn/submissions/detail/380070029/
```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```py
class Solution:
    def isPalindrome(self, head: Optional[ListNode]) -> bool:
        # 寻找链表的中点（偶数个节点时选择左侧），即前半部分链表的尾节点
        slow = fast = head
        while fast.next is not None and fast.next.next is not None:
            slow = slow.next
            fast = fast.next.next
        # 翻转后半部分链表
        reverseHead = self.reverseList(slow.next)
        slow.next = None
        # 判断是否回文链表
        left = head
        right = reverseHead
        while right is not None:
            if left.val != right.val:
                return False
            left = left.next
            right = right.next
        # 还原链表
        slow.next = self.reverseList(reverseHead)
        return True

    def reverseList(self, head: Optional[ListNode]) -> Optional[ListNode]:
        reverseHead = None
        while head is not None:
            x = head.next
            head.next = reverseHead
            reverseHead = head
            head = x
        return reverseHead
# https://leetcode.cn/submissions/detail/378900910/
```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```py
class Solution:
    def lowestCommonAncestor(self, root: 'TreeNode', p: 'TreeNode', q: 'TreeNode') -> 'TreeNode':
        # 保证 p < q
        if p.val > q.val:
            return self.lowestCommonAncestor(root, q, p)
        if q.val < root.val:
            return self.lowestCommonAncestor(root.left, p, q)
        if root.val < p.val:
            return self.lowestCommonAncestor(root.right, p, q)
        return root
# https://leetcode.cn/submissions/detail/470328592/
```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```py
class Solution:
    def __init__(self):
        self.lca = None

    def lowestCommonAncestor(self, root: TreeNode, p: TreeNode, q: TreeNode) -> TreeNode:
        self.find(root, p, q)
        return self.lca

    # 在子树中查找节点 p 或 q，递归过程中确定『最近公共祖先』
    def find(self, root: Optional[TreeNode], p: TreeNode, q: TreeNode) -> bool:
        if root is None:
            return False
        if (root is p) or (root is q):
            # 如果 lca(p,q) = p 或 q，则此处的 lca = root 是最终答案
            self.lca = root
            return True
        left = self.find(root.left, p, q)
        right = self.find(root.right, p, q)
        if left and right:
            # 否则返回到某祖先节点处的 lca = root 才是最终答案
            self.lca = root
        return left or right
# https://leetcode.cn/submissions/detail/380341756/
```

## 237. 删除链表中的节点

<https://leetcode.cn/problems/delete-node-in-a-linked-list/>

```py
class Solution:
    def deleteNode(self, node):
        while True:
            node.val = node.next.val
            if node.next.next is None:
                node.next = None
                break
            node = node.next
# https://leetcode.cn/submissions/detail/380301024/
```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```py
class Solution:
    def maxSlidingWindow(self, nums: List[int], k: int) -> List[int]:
        ans = []
        maxMonoQueue = collections.deque()
        for i, v in enumerate(nums):
            # nums[i] = 进入窗口的数字
            while len(maxMonoQueue) > 0 and maxMonoQueue[-1] < v:
                maxMonoQueue.pop()
            maxMonoQueue.append(v)
            if i < k - 1:
                continue
            # nums[i-k] = 退出窗口的数字
            if i >= k and nums[i - k] == maxMonoQueue[0]:
                maxMonoQueue.popleft()
            ans.append(maxMonoQueue[0])
        return ans
# https://leetcode.cn/submissions/detail/379209648/
```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```py
# TODO
```

## 283. 移动零

<https://leetcode.cn/problems/move-zeroes/>

```py
class Solution:
    def moveZeroes(self, nums: List[int]) -> None:
        n = len(nums)
        # nums[0..i-1] != 0
        # nums[i..j-1] == 0
        # nums[j..n-1] Scanning
        i, j = 0, 0
        while j < n:
            while j < n and nums[j] == 0:
                j += 1
            if j < n:
                nums[i], nums[j] = nums[j], nums[i]
                i += 1
                j += 1
# https://leetcode.cn/submissions/detail/405577693/
```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```py
class Codec:
    def serialize(self, root):
        if root is None:
            return '#'
        left = self.serialize(root.left)
        right = self.serialize(root.right)
        return str(root.val) + ',' + left + ',' + right

    def deserialize(self, data):
        return self.buildTree(deque(data.split(',')))

    def buildTree(self, queue):
        val = queue.popleft()
        if val == '#':
            return None
        root = TreeNode(val)
        root.left = self.buildTree(queue)
        root.right = self.buildTree(queue)
        return root
# https://leetcode.cn/submissions/detail/380039350/
```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```py
class Solution:
    def lengthOfLIS(self, nums: List[int]) -> int:
        n = len(nums)
        # dp[i] = max({length(subseq) | subseq 是以 nums[i] 结尾的严格递增子序列})
        dp = [1] * n
        ans = 0
        for i in range(n):
            for j in range(i):
                if nums[j] < nums[i]:
                    dp[i] = max(dp[i], dp[j] + 1)
            ans = max(ans, dp[i])
        return ans
# https://leetcode.cn/submissions/detail/379235099/
```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```py
class NumArray:
    def __init__(self, nums: List[int]):
        n = len(nums)
        self.sums = [0] * n
        self.sums[0] = nums[0]
        for i in range(1, n):
            self.sums[i] = self.sums[i - 1] + nums[i]

    def sumRange(self, left: int, right: int) -> int:
        if left == 0:
            return self.sums[right]
        return self.sums[right] - self.sums[left - 1]
# https://leetcode.cn/submissions/detail/380205940/
```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```py
class Solution:
    def maxProfit(self, prices: List[int]) -> int:
        n = len(prices)
        if n <= 1:
            return 0
        # dp[i][0] = 第 i 天，空仓状态下的最大利润
        # dp[i][1] = 第 i 天，持仓状态下的最大利润
        dp = [[0] * 2 for _ in range(n)]
        dp[0][0] = 0
        dp[0][1] = -prices[0]
        dp[1][0] = max(dp[0][0], dp[0][1] + prices[1])
        dp[1][1] = max(dp[0][0] - prices[1], dp[0][1])
        for i in range(2, n):
            # dp[i - 1][0]             >= dp[i - 2][0] >= p[i - 2][0] - prices[i]
            # dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            # => dp[i][0] >= dp[i][1]
            dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = max(dp[i - 2][0] - prices[i], dp[i - 1][1]);
        return dp[n - 1][0]
# https://leetcode.cn/submissions/detail/379364431/
```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```py
@total_ordering
class Pair:
    def __init__(self, val: int, idx: int):
        self.val = val
        self.idx = idx

    def __lt__(self, other):
        return self.val < other.val

    def __eq__(self, other):
        return self.val == other.val


class Solution:
    def __init__(self):
        self.counts = None

    def countSmaller(self, nums: List[int]) -> List[int]:
        n = len(nums)
        self.counts = [0] * n
        pairs = [Pair(nums[i], i) for i in range(n)]
        aux = pairs.copy()
        self.sort(pairs, 0, n - 1, aux)
        return self.counts

    def sort(self, pairs: List[Pair], lo: int, hi: int, aux: List[Pair]) -> None:
        if lo >= hi:
            return
        mid = lo + (hi - lo) // 2
        self.sort(pairs, lo, mid, aux)
        self.sort(pairs, mid + 1, hi, aux)
        self.merge(pairs, lo, mid, hi, aux)

    def merge(self, pairs: List[Pair], lo: int, mid: int, hi: int, aux: List[Pair]) -> None:
        for k in range(lo, hi + 1):
            aux[k] = pairs[k]
        i, j = lo, mid + 1
        for k in range(lo, hi + 1):
            if i > mid or (j <= hi and aux[j] < aux[i]):
                pairs[k] = aux[j]
                j += 1
            else:
                # aux[mid+1..j) < aux[i]
                self.counts[aux[i].idx] += (j - mid - 1)
                pairs[k] = aux[i]
                i += 1
# https://leetcode.cn/submissions/detail/380602127/
```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```py
class Solution:
    def coinChange(self, coins: List[int], amount: int) -> int:
        # dp[i] = 凑成总金额 i 所需的最少的硬币个数
        dp = [-1] * (amount + 1)
        dp[0] = 0
        for i in range(1, amount + 1):
            res = math.inf
            # c       = 选择放入的硬币
            # i-c     = 剩余总金额
            # dp[i-c] = 凑成剩余总金额所需的最少的硬币个数
            for c in coins:
                x = i - c
                if x >= 0 and dp[x] != -1:
                    res = min(res, dp[x] + 1)
            dp[i] = -1 if res == math.inf else res
        return dp[amount]
# https://leetcode.cn/submissions/detail/379487504/
```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```py
class Solution:
    @cache
    def rob(self, root: Optional[TreeNode]) -> int:
        if root is None:
            return 0
        # 偷 root
        sp1 = root.val
        if root.left is not None:
            sp1 += self.rob(root.left.left) + self.rob(root.left.right)
        if root.right is not None:
            sp1 += self.rob(root.right.left) + self.rob(root.right.right)
        # 不偷 root
        sp2 = self.rob(root.left) + self.rob(root.right)
        return max(sp1, sp2)
# https://leetcode.cn/submissions/detail/379356114/
```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```py
class Solution:
    def reverseString(self, s: List[str]) -> None:
        i, j = 0, len(s) - 1
        while i < j:
            s[i], s[j] = s[j], s[i]
            i += 1
            j -= 1
# https://leetcode.cn/submissions/detail/407451616/
```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```py
# TODO
```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```py
class Solution:
    def decodeString(self, s: str) -> str:
        stack = []
        n = len(s)
        i = 0
        while i < n:
            # Digits
            digits = ''
            while i < n and s[i].isdigit():
                digits += s[i]
                i += 1
            if len(digits) > 0:
                stack.append(digits)
            # [
            while i < n and s[i] == '[':
                stack.append('[')
                i += 1
            # Letters
            letters = ''
            while i < n and s[i].isalpha():
                letters += s[i]
                i += 1
            if len(letters) > 0:
                stack.append(letters)
            # ]
            while i < n and s[i] == ']':
                letters = ''
                while len(stack) > 0:
                    ch = stack.pop()
                    if ch == '[':
                        break
                    letters = ch + letters
                digits = stack.pop()
                repeated = letters * int(digits)
                stack.append(repeated)
                i += 1
        return ''.join(stack)
# https://leetcode.cn/submissions/detail/378949673/
```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```py
class Solution:
    def canPartition(self, nums: List[int]) -> bool:
        s = sum(nums)
        if s % 2 == 1:
            return False
        return self.hasSubsetSum(nums, s // 2)

    # 数组 nums 是否存在和为 target 的子集
    def hasSubsetSum(self, nums: List[int], target: int) -> bool:
        n = len(nums)
        # dp[i][j] = 子数组 nums[0..i-1] 是否存在和为 j 的子集
        dp = [[False] * (target + 1) for _ in range(n + 1)]
        # 和为 0
        for i in range(1, n + 1):
            dp[i][0] = True
        # 空数组
        for j in range(1, target + 1):
            dp[0][j] = False
        # 空集的和为 0，空集是任何数组的子集，包括空数组
        dp[0][0] = True
        for i in range(1, n + 1):
            for j in range(1, target + 1):
                x = nums[i - 1]
                if j >= x:
                    # 包含 x
                    # 当 i >= 1, j = x 时，dp[i - 1][j - x] = dp[i - 1][0]
                    # 因为存在子集 {x} 的和为 j，
                    # 所以定义 dp[i][0] = true (i >= 0)
                    sp1 = dp[i - 1][j - x]
                    # 不包含 x
                    # 当 i = 1 时，dp[i - 1][j] = dp[0][j]
                    # 因为空数组没有子集的和为 j >= 1
                    # 所以定义 dp[0][j] = false (j >= 1)
                    sp2 = dp[i - 1][j]
                    dp[i][j] = sp1 or sp2
                else:
                    # 不包含 x
                    dp[i][j] = dp[i - 1][j]
        return dp[n][target]
# https://leetcode.cn/submissions/detail/379614657/
```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```py
class Solution:
    def eraseOverlapIntervals(self, intervals: List[List[int]]) -> int:
        return len(intervals) - Solution.maxNonOverlappingIntervals(intervals)

    # 返回区间数组 intervals 无重叠区间的最大数量
    @staticmethod
    def maxNonOverlappingIntervals(intervals: List[List[int]]) -> int:
        # 按区间终点升序排列
        intervals.sort(key=lambda interval: interval[1])
        # 最后一个不重叠区间的终点
        lastEnd = intervals[0][1]
        count = 1
        for i in range(1, len(intervals)):
            start, end = intervals[i]
            if start >= lastEnd:
                count += 1
                lastEnd = end
        return count
# https://leetcode.cn/submissions/detail/456434440/
```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```py
class Solution:
    def findAnagrams(self, s: str, p: str) -> List[int]:
        need = {}
        for c in p:
            need.setdefault(c, 0)
            need[c] += 1
        window = {}
        ans = []
        valid = 0
        # s[left..right) = Window Substring
        # s[right..n-1]  = Scanning
        left = right = 0
        while right < len(s):
            c = s[right]
            right += 1
            if c in need:
                window.setdefault(c, 0)
                window[c] += 1
                if window[c] == need[c]:
                    valid += 1
            if valid == len(need):
                while left < right - len(p):
                    d = s[left]
                    left += 1
                    if d in need:
                        if window[d] == need[d]:
                            valid -= 1
                        window[d] -= 1
                if valid == len(need):
                    ans.append(left)
        return ans
# https://leetcode.cn/submissions/detail/379020999/
```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```py
class Solution:
    def addTwoNumbers(self, l1: Optional[ListNode], l2: Optional[ListNode]) -> Optional[ListNode]:
        # 翻转链表
        l1 = self.reverseList(l1)
        l2 = self.reverseList(l2)
        ptr = dummyHead = ListNode()
        carry = 0
        while (l1 is not None) or (l2 is not None) or carry > 0:
            sum = carry
            if l1 is not None:
                sum += l1.val
                l1 = l1.next
            if l2 is not None:
                sum += l2.val
                l2 = l2.next
            ptr.next = ListNode(sum % 10)
            ptr = ptr.next
            carry = sum // 10
        # 还原链表
        self.reverseList(l1)
        self.reverseList(l2)
        return self.reverseList(dummyHead.next)

    def reverseList(self, head: Optional[ListNode]) -> Optional[ListNode]:
        reverseHead = None
        while head is not None:
            x = head.next
            head.next = reverseHead
            reverseHead = head
            head = x
        return reverseHead
# https://leetcode.cn/submissions/detail/378905700/
```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```py
class Solution:
    def deleteNode(self, root: Optional[TreeNode], key: int) -> Optional[TreeNode]:
        if root is None:
            return None
        if key < root.val:
            root.left = self.deleteNode(root.left, key)
        elif root.val < key:
            root.right = self.deleteNode(root.right, key)
        else:
            if root.left is None:
                return root.right
            if root.right is None:
                return root.left
            x = root
            root = self.findMin(x.right)
            root.right = self.deleteMin(x.right)
            root.left = x.left
        return root

    def findMin(self, root: TreeNode) -> TreeNode:
        if root.left is None:
            return root
        return self.findMin(root.left)

    def deleteMin(self, root: TreeNode) -> Optional[TreeNode]:
        if root.left is None:
            return root.right
        root.left = self.deleteMin(root.left)
        return root
# https://leetcode.cn/submissions/detail/394416894/
```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```py
class Solution:
    def findMinArrowShots(self, points: List[List[int]]) -> int:
        return Solution.maxNonOverlappingIntervals(points)

    # 返回区间数组 intervals 无重叠区间的最大数量
    @staticmethod
    def maxNonOverlappingIntervals(intervals: List[List[int]]) -> int:
        # 按区间终点升序排列
        intervals.sort(key=lambda interval: interval[1])
        # 最后一个不重叠区间的终点
        lastEnd = intervals[0][1]
        count = 1
        for i in range(1, len(intervals)):
            start, end = intervals[i]
            if start > lastEnd:
                count += 1
                lastEnd = end
        return count
# https://leetcode.cn/submissions/detail/456435233/
```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```py
class MyListNode:
    def __init__(self, key: int, val: int, freq: int):
        self.key = key
        self.val = val
        self.freq = freq
        self.prev = None
        self.next = None


class MyDoublyLinkedList:
    def __init__(self):
        self.__first = None
        self.__last = None
        self.__n = 0

    def add_last(self, new_node: MyListNode) -> None:
        if self.__n == 0:
            self.__first = new_node
            self.__last = new_node
            self.__n = 1
        else:
            self.__last.next = new_node
            new_node.prev = self.__last
            self.__last = new_node
            self.__n += 1

    def remove_first(self) -> MyListNode:
        old_first = self.__first
        if self.__n == 1:
            self.__first = None
            self.__last = None
            self.__n = 0
        else:
            self.__first = self.__first.next
            self.__first.prev = None
            old_first.next = None
            self.__n -= 1
        return old_first

    def remove_last(self) -> MyListNode:
        old_last = self.__last
        if self.__n == 1:
            self.__first = None
            self.__last = None
            self.__n = 0
        else:
            self.__last = self.__last.prev
            self.__last.next = None
            old_last.prev = None
            self.__n -= 1
        return old_last

    def remove(self, del_node: MyListNode) -> None:
        if del_node is self.__first:
            self.remove_first()
        elif del_node is self.__last:
            self.remove_last()
        else:
            del_node.prev.next = del_node.next
            del_node.next.prev = del_node.prev
            del_node.prev = None
            del_node.next = None
            self.__n -= 1

    def empty(self) -> bool:
        return self.__n == 0


class LFUCache:
    def __init__(self, capacity: int):
        self.__capacity = capacity
        self.__min_freq = 0
        self.__key_to_node = {}
        self.__freq_to_list = defaultdict(MyDoublyLinkedList)

    def get(self, key: int) -> int:
        if self.__contains(key):
            return self.__touch_cache(key, None)
        return -1

    def put(self, key: int, value: int) -> None:
        if self.__capacity > 0:
            if self.__contains(key):
                self.__touch_cache(key, value)
            else:
                if self.__full():
                    self.__remove_cache()
                self.__add_cache(key, value)

    def __contains(self, key: int) -> bool:
        return key in self.__key_to_node

    def __full(self) -> bool:
        return len(self.__key_to_node) == self.__capacity

    def __add_cache(self, key: int, val: int) -> None:
        new_node = MyListNode(key, val, 1)
        self.__key_to_node[key] = new_node
        self.__freq_to_list[1].add_last(new_node)
        self.__min_freq = 1

    def __remove_cache(self) -> None:
        min_freq_list = self.__freq_to_list[self.__min_freq]
        self.__key_to_node.pop(min_freq_list.remove_first().key)
        if min_freq_list.empty():
            self.__freq_to_list.pop(self.__min_freq)

    def __touch_cache(self, key: int, val: Optional[int]) -> int:
        touch_node = self.__key_to_node[key]
        if val is not None:
            touch_node.val = val
        old_freq = touch_node.freq
        new_freq = old_freq + 1
        touch_node.freq = new_freq
        old_list = self.__freq_to_list[old_freq]
        old_list.remove(touch_node)
        if old_list.empty():
            self.__freq_to_list.pop(old_freq)
            if self.__min_freq == old_freq:
                self.__min_freq = new_freq
        new_list = self.__freq_to_list[new_freq]
        new_list.add_last(touch_node)
        return touch_node.val
# https://leetcode.cn/submissions/detail/442599806/
```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```py
class Solution:
    def __init__(self):
        self.ans = 0

    def reversePairs(self, nums: List[int]) -> int:
        aux = nums.copy()
        self.sort(nums, 0, len(nums) - 1, aux)
        return self.ans

    def sort(self, nums: List[int], lo: int, hi: int, aux: List[int]) -> None:
        if lo >= hi:
            return
        mid = lo + (hi - lo) // 2
        self.sort(nums, lo, mid, aux)
        self.sort(nums, mid + 1, hi, aux)
        self.merge(nums, lo, mid, hi, aux)

    def merge(self, nums: List[int], lo: int, mid: int, hi: int, aux: List[int]) -> None:
        for k in range(lo, hi + 1):
            aux[k] = nums[k]
        self.ans += self.countReversePairs(nums, lo, mid, hi)
        i, j = lo, mid + 1
        for k in range(lo, hi + 1):
            if i > mid or (j <= hi and aux[j] < aux[i]):
                nums[k] = aux[j]
                j += 1
            else:
                nums[k] = aux[i]
                i += 1

    def countReversePairs(self, nums: List[int], lo: int, mid: int, hi: int) -> int:
        res = 0
        #     nums[i]      > 2*nums[j]
        # (1) nums[i]      > 2*nums[mid+1..j]
        # (2) nums[i..mid] > 2*nums[j]
        #
        #     nums[i]     <= 2*nums[j]
        # (1) nums[i]     <= 2*nums[j..hi]
        # (2) nums[lo..i] <= 2*nums[j]
        i, j = lo, mid + 1
        while i <= mid and j <= hi:
            if self.isReversePair(nums, i, j):
                res += (mid - i + 1)
                j += 1
            else:
                i += 1
        return res

    def isReversePair(self, nums: List[int], i: int, j: int) -> bool:
        return i < j and nums[i] > 2 * nums[j]
# https://leetcode.cn/submissions/detail/380596187/
```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```py
class Solution:
    def __init__(self):
        self.memo = {}

    def findTargetSumWays(self, nums: List[int], target: int) -> int:
        if abs(target) > sum(nums):
            return 0
        return self._findTargetSumWays(nums, len(nums) - 1, target)

    # 子数组 nums[0..i] 目标和为 target 的不同表达式的数目
    def _findTargetSumWays(self, nums: List[int], i: int, target: int) -> int:
        if i < 0:
            return 1 if target == 0 else 0
        key = (i, target)
        if key not in self.memo:
            x = nums[i]
            # x 前添加 + 号
            # sum(nums[0..i-1]) = target - x
            sp1 = self._findTargetSumWays(nums, i - 1, target - x)
            # x 前添加 - 号
            # sum(nums[0..i-1]) = target + x
            sp2 = self._findTargetSumWays(nums, i - 1, target + x)
            self.memo[key] = sp1 + sp2
        return self.memo[key]
# https://leetcode.cn/submissions/detail/379526024/
```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```py
class Solution:
    def nextGreaterElement(self, nums1: List[int], nums2: List[int]) -> List[int]:
        greater = self._nextGreaterElement(nums2)
        valToGreater = {}
        for i, v in enumerate(nums2):
            valToGreater[v] = greater[i]
        return [valToGreater[v] for v in nums1]

    def _nextGreaterElement(self, nums: List[int]) -> List[int]:
        n = len(nums)
        res = [-1] * n
        minMonoStack = []
        for i in range(-1, - n - 1, -1):
            v = nums[i]
            while len(minMonoStack) > 0 and minMonoStack[-1] < v:
                minMonoStack.pop()
            res[i] = -1 if len(minMonoStack) == 0 else minMonoStack[-1]
            minMonoStack.append(v)
        return res
# https://leetcode.cn/submissions/detail/379215888/
```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```py
class Solution:
    def nextGreaterElements(self, nums: List[int]) -> List[int]:
        n = len(nums)
        ans = [-1] * n
        minMonoStack = []
        for i in range(2 * n - 1, -1, -1):
            j = i % n
            v = nums[j]
            while len(minMonoStack) > 0 and minMonoStack[-1] <= v:
                minMonoStack.pop()
            ans[j] = -1 if len(minMonoStack) == 0 else minMonoStack[-1]
            minMonoStack.append(v)
        return ans
# https://leetcode.cn/submissions/detail/379217114/
```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```py
class Solution:
    def fib(self, n: int) -> int:
        if n == 0:
            return 0
        if n == 1:
            return 1
        dp = [0] * (n + 1)
        dp[0] = 0
        dp[1] = 1
        for i in range(2, n + 1):
            dp[i] = dp[i - 1] + dp[i - 2]
        return dp[n]
# https://leetcode.cn/submissions/detail/380215990/
```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```py
class Solution:
    def longestPalindromeSubseq(self, s: str) -> int:
        n = len(s)
        # dp[i][j] = 子串 s[i..j] 的最长回文子序列的长度
        dp = [[0] * n for _ in range(n)]
        # 遍历对角线
        for i in range(n):
            dp[i][i] = 1
        # 遍历上三角形
        for i in range(n - 2, -1, -1):
            for j in range(i + 1, n):
                if s[i] == s[j]:
                    # s[i][i+1..j-1][j]
                    # s   [i+1..j-1]
                    dp[i][j] = dp[i + 1][j - 1] + 2
                else:
                    # s[i..j-1][j]
                    # s[i..j-1]
                    sp1 = dp[i][j - 1]
                    # s[i][i+1..j]
                    # s   [i+1..j]
                    sp2 = dp[i + 1][j]
                    dp[i][j] = max(sp1, sp2)
        return dp[0][n - 1]
# https://leetcode.cn/submissions/detail/379242302/
```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```py
class Solution:
    def change(self, amount: int, coins: List[int]) -> int:
        n = len(coins)
        # dp[i][j] = 使用硬币 coins[0..i-1] 凑成总金额 j 的组合数
        dp = [[0] * (amount + 1) for _ in range(n + 1)]
        # 总金额为 0
        for i in range(1, n + 1):
            dp[i][0] = 1
        # 硬币数为 0
        for j in range(1, amount + 1):
            dp[0][j] = 0
        dp[0][0] = 1
        for i in range(1, n + 1):
            for j in range(1, amount + 1):
                x = coins[i - 1]
                if j >= x:
                    sp1 = dp[i - 1][j]  # 包含    0 个硬币 x
                    sp2 = dp[i][j - x]  # 包含 >= 1 个硬币 x
                    dp[i][j] = sp1 + sp2
                    # 注意
                    # dp[i][j - x] = 包含 >= 1 个硬币 x
                    # dp[i-1][j-x] = 包含    1 个硬币 x
                    # 举例 amount = 79, coins = [1, 2, 5]
                    # dp[2][79] = 包含    0 个硬币 5，79 = 0 x 5 + 79，剩余 79 只能从 [1, 2] 凑
                    # dp[2][74] = 包含    1 个硬币 5，79 = 1 x 5 + 74，剩余 74 只能从 [1, 2] 凑
                    # dp[3][74] = 包含 >= 1 个硬币 5，79 = 1 x 5 + 74，剩余 74 可以从 [1, 2, 5] 凑
                else:
                    # 不包含硬币 x
                    dp[i][j] = dp[i - 1][j]
        return dp[n][amount]
# https://leetcode.cn/submissions/detail/379489135/
```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```py
class Solution:
    def __init__(self):
        self._sum = 0

    def convertBST(self, root: Optional[TreeNode]) -> Optional[TreeNode]:
        self._dfs(root)
        return root

    def _dfs(self, root: Optional[TreeNode]) -> None:
        if root is None:
            return
        self._dfs(root.right)
        self._sum += root.val
        root.val = self._sum
        self._dfs(root.left)
# https://leetcode.cn/submissions/detail/470139706/
```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```py
# rootLP = 穿过根节点的最长路径（左右子树的最大深度之和）
# rootLP(root) = maxDepth(root.left) + maxDepth(root.right)
# diameter = 所有子树的 rootLP 的最大值
# diameter(root) = max({rootLP(subtree) | subtree 是 root 的任意子树})
class Solution:
    def __init__(self):
        self.ans = 0

    def diameterOfBinaryTree(self, root: Optional[TreeNode]) -> int:
        self.maxDepth(root)
        return self.ans

    def maxDepth(self, root: Optional[TreeNode]) -> int:
        if root is None:
            return 0
        left = self.maxDepth(root.left)
        right = self.maxDepth(root.right)
        self.ans = max(self.ans, left + right)
        return 1 + max(left, right)
# https://leetcode.cn/submissions/detail/380119502/
```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```py
class Solution:
    def checkInclusion(self, s1: str, s2: str) -> bool:
        need = {}
        for c in s1:
            need.setdefault(c, 0)
            need[c] += 1
        window = {}
        valid = 0
        # s[left..right) = Window Substring
        # s[right..n-1]  = Scanning
        left = right = 0
        while right < len(s2):
            c = s2[right]
            right += 1
            if c in need:
                window.setdefault(c, 0)
                window[c] += 1
                if window[c] == need[c]:
                    valid += 1
            if valid == len(need):
                while left < right - len(s1):
                    d = s2[left]
                    left += 1
                    if d in need:
                        if window[d] == need[d]:
                            valid -= 1
                        window[d] -= 1
                if valid == len(need):
                    return True
        return False
# https://leetcode.cn/submissions/detail/379022373/
```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```py
class Solution:
    def __init__(self) -> None:
        self._memo: Dict[Tuple, int] = {}

    def minDistance(self, s1: str, s2: str) -> int:
        return self._minDistance(s1, len(s1) - 1, s2, len(s2) - 1)

    # 返回子串 s1[0..i] s2[0..j] 的最小删除步数
    def _minDistance(self, s1: str, i: int, s2: str, j: int) -> int:
        # 删除 s2[0..j]
        # s1""
        # s2[0..j]
        if i < 0:
            return j + 1

        # 删除 s1[0..i]
        # s1[0..i]
        # s2""
        if j < 0:
            return i + 1

        if (i, j) not in self._memo:
            if s1[i] == s2[j]:
                # s1[0..i-1][i]
                # s2[0..j-1][j]
                self._memo[(i, j)] = self._minDistance(s1, i - 1, s2, j - 1)
            else:
                # 删除 s1[i] s2[j]
                # s1[0..i-1][i]
                # s2[0..j-1][j]
                sp1 = self._minDistance(s1, i - 1, s2, j - 1) + 2
                # 删除 s2[j]
                # s1[0..i]
                # s2[0..j-1][j]
                sp2 = self._minDistance(s1, i, s2, j - 1) + 1
                # 删除 s1[i]
                # s1[0..i-1][i]
                # s2[0..j]
                sp3 = self._minDistance(s1, i - 1, s2, j) + 1
                self._memo[(i, j)] = min(sp1, sp2, sp3)

        return self._memo[(i, j)]
# https://leetcode.cn/submissions/detail/448366754/
```

```py
class Solution:
    def minDistance(self, s1: str, s2: str) -> int:
        return self._minDistance(s1, len(s1) - 1, s2, len(s2) - 1)

    # 返回子串 s1[0..i] s2[0..j] 的最小删除步数
    @cache
    def _minDistance(self, s1: str, i: int, s2: str, j: int) -> int:
        # 删除 s2[0..j]
        # s1""
        # s2[0..j]
        if i < 0:
            return j + 1

        # 删除 s1[0..i]
        # s1[0..i]
        # s2""
        if j < 0:
            return i + 1

        if s1[i] == s2[j]:
            # s1[0..i-1][i]
            # s2[0..j-1][j]
            return self._minDistance(s1, i - 1, s2, j - 1)
        else:
            # 删除 s1[i] s2[j]
            # s1[0..i-1][i]
            # s2[0..j-1][j]
            sp1 = self._minDistance(s1, i - 1, s2, j - 1) + 2
            # 删除 s2[j]
            # s1[0..i]
            # s2[0..j-1][j]
            sp2 = self._minDistance(s1, i, s2, j - 1) + 1
            # 删除 s1[i]
            # s1[0..i-1][i]
            # s2[0..j]
            sp3 = self._minDistance(s1, i - 1, s2, j) + 1
            return min(sp1, sp2, sp3)
# https://leetcode.cn/submissions/detail/448365688/
```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```py
class Solution:
    def mergeTrees(self, root1: Optional[TreeNode], root2: Optional[TreeNode]) -> Optional[TreeNode]:
        if root1 is None:
            return root2
        if root2 is None:
            return root1
        mRoot = TreeNode(root1.val + root2.val)
        mRoot.left = self.mergeTrees(root1.left, root2.left)
        mRoot.right = self.mergeTrees(root1.right, root2.right)
        return mRoot
# https://leetcode.cn/submissions/detail/380125448/
```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```py
class Solution:
    def __init__(self):
        self.ans = []
        self.counter = Counter()

    def findDuplicateSubtrees(self, root: Optional[TreeNode]) -> List[Optional[TreeNode]]:
        self.postorder(root)
        return self.ans

    def postorder(self, root: Optional[TreeNode]) -> str:
        if root is None:
            return '#'
        left = self.postorder(root.left)
        right = self.postorder(root.right)
        res = left + ',' + right + ',' + str(root.val)
        self.counter[res] += 1
        if self.counter[res] == 2:
            self.ans.append(root)
        return res
# https://leetcode.cn/submissions/detail/379980974/
```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```py
class Solution:
    def constructMaximumBinaryTree(self, nums: List[int]) -> Optional[TreeNode]:
        return self._constructMaximumBinaryTree(nums, 0, len(nums) - 1)

    def _constructMaximumBinaryTree(self, nums: List[int], lo: int, hi: int) -> Optional[TreeNode]:
        if lo > hi:
            return None
        maxIndex = lo
        for i in range(lo + 1, hi + 1):
            if nums[i] > nums[maxIndex]:
                maxIndex = i
        root = TreeNode(nums[maxIndex])
        root.left = self._constructMaximumBinaryTree(nums, lo, maxIndex - 1)
        root.right = self._constructMaximumBinaryTree(nums, maxIndex + 1, hi)
        return root
# https://leetcode.cn/submissions/detail/379991812/
```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```py
class Solution:
    LAND = 1
    WATER = 0

    def __init__(self):
        self.area = 0

    def maxAreaOfIsland(self, grid: List[List[int]]) -> int:
        ans = 0
        for row in range(len(grid)):
            for col in range(len(grid[0])):
                if grid[row][col] == Solution.LAND:
                    self.area = 0
                    self.floodFill(grid, row, col)
                    ans = max(ans, self.area)
        return ans

    def floodFill(self, grid: List[List[int]], row: int, col: int) -> None:
        if row < 0 or row >= len(grid) or col < 0 or col >= len(grid[0]) or grid[row][col] == Solution.WATER:
            return
        self.area += 1
        grid[row][col] = Solution.WATER
        self.floodFill(grid, row - 1, col)
        self.floodFill(grid, row + 1, col)
        self.floodFill(grid, row, col - 1)
        self.floodFill(grid, row, col + 1)
# https://leetcode.cn/submissions/detail/380250845/
```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```py
class Solution:
    def __init__(self):
        self.nums = None
        self.k = None
        self.target = None
        self.pathSums = None
        self.used = 0
        self.memo = {}

    def canPartitionKSubsets(self, nums: List[int], k: int) -> bool:
        s = sum(nums)
        if s % k != 0:
            return False
        self.nums = nums
        self.k = k
        self.target = s // k
        self.pathSums = [0] * k
        return self.backtrack(0, -1)

    # 遍历『决策森林』的 k 棵『决策树』
    # 一棵『决策树』的『路径』代表一个『等和子集』
    # tree = 第几棵『决策树』，取 [0..k-1] 为值
    # edge =『决策树』的『边』，取数组 nums 的索引为值
    # pathSums[tree] = 第几棵『决策树』的『路径和』
    def backtrack(self, tree: int, edge: int) -> bool:
        res = False
        if tree == self.k:
            res = True
        elif self.pathSums[tree] == self.target:
            # 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            # 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            # 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            # 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            # 因为 C 的可选『边』是一样的
            if self.used not in self.memo:
                self.memo[self.used] = self.backtrack(tree + 1, -1)
            res = self.memo[self.used]
        else:
            # 通过去重，对同一棵树，优化『边』的遍历，避免『边+边』重复
            # 例如 1 和 2 分别是两条『边』，[1->2] 和 [2->1] 是重复的
            for e in range(edge + 1, len(self.nums)):
                # 检查第 e 位是否为 1，即 nums[e] 是否已经被其他『树』使用
                if (self.used >> e) & 1 == 1:
                    continue
                x = self.nums[e]
                if self.pathSums[tree] + x > self.target:
                    continue
                self.pathSums[tree] += x
                self.used |= (1 << e)  # 『或』运算，将第 e 位修改为 1
                res = self.backtrack(tree, e)
                if res:
                    break
                self.pathSums[tree] -= x
                self.used ^= (1 << e)  # 『异或』运算，将第 e 位恢复为 0
        return res
# https://leetcode.cn/submissions/detail/379813608/
```

```py
class Solution:
    def __init__(self):
        self.nums = None
        self.k = None
        self.target = None
        self.pathSums = None
        self.memo = {}
        self.used = bytearray(b'0000000000000000')

    def canPartitionKSubsets(self, nums: List[int], k: int) -> bool:
        s = sum(nums)
        if s % k != 0:
            return False
        self.nums = nums
        self.k = k
        self.target = s // k
        self.pathSums = [0] * k
        return self.backtrack(0, -1)

    # 遍历『决策森林』的 k 棵『决策树』
    # 一棵『决策树』的『路径』代表一个『等和子集』
    # tree = 第几棵『决策树』，取 [0..k-1] 为值
    # edge =『决策树』的『边』，取数组 nums 的索引为值
    # pathSums[tree] = 第几棵『决策树』的『路径和』
    def backtrack(self, tree: int, edge: int) -> bool:
        res = False
        if tree == self.k:
            res = True
        elif self.pathSums[tree] == self.target:
            # 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            # 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            # 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            # 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            # 因为 C 的可选『边』是一样的
            key = self.used.decode()
            if key not in self.memo:
                self.memo[key] = self.backtrack(tree + 1, -1)
            res = self.memo[key]
        else:
            # 通过去重，对同一棵树，优化『边』的遍历，避免『边+边』重复
            # 例如 1 和 2 分别是两条『边』，[1->2] 和 [2->1] 是重复的
            for e in range(edge + 1, len(self.nums)):
                # 检查第 e 位是否为 1，即 nums[e] 是否已经被其他『树』使用
                if self.used[e] == ord('1'):
                    continue
                x = self.nums[e]
                if self.pathSums[tree] + x > self.target:
                    continue
                self.pathSums[tree] += x
                self.used[e] = ord('1')
                res = self.backtrack(tree, e)
                if res:
                    break
                self.pathSums[tree] -= x
                self.used[e] = ord('0')
        return res
# https://leetcode.cn/submissions/detail/379824409/
```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```py
class Solution:
    def searchBST(self, root: Optional[TreeNode], val: int) -> Optional[TreeNode]:
        if root is None:
            return None
        if val < root.val:
            return self.searchBST(root.left, val)
        if val > root.val:
            return self.searchBST(root.right, val)
        return root
# https://leetcode.cn/submissions/detail/380133429/
```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```py
class Solution:
    def insertIntoBST(self, root: Optional[TreeNode], val: int) -> Optional[TreeNode]:
        if root is None:
            return TreeNode(val)
        if val < root.val:
            root.left = self.insertIntoBST(root.left, val)
        if val > root.val:
            root.right = self.insertIntoBST(root.right, val)
        return root
# https://leetcode.cn/submissions/detail/380135492/
```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```py
class Solution:
    def search(self, nums: List[int], target: int) -> int:
        lo, hi = 0, len(nums) - 1
        while lo <= hi:
            mid = lo + (hi - lo) // 2
            if target < nums[mid]:
                hi = mid - 1
            elif nums[mid] < target:
                lo = mid + 1
            else:
                return mid
        return -1
# https://leetcode.cn/submissions/detail/380214333/
```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```py
class Solution:
    def __init__(self):
        self.memo = {}
        self.sum1 = None
        self.sum2 = None

    def minimumDeleteSum(self, s1: str, s2: str) -> int:
        self.sum1 = self.prefixSum(s1)
        self.sum2 = self.prefixSum(s2)
        return self._minDistance(s1, len(s1) - 1, s2, len(s2) - 1)

    # 子串 s1[0..i] s2[0..j] 的最小 ASCII 删除和
    def _minDistance(self, s1: str, i: int, s2: str, j: int) -> int:
        if i < 0 and j < 0:
            return 0
        # 删除 s2[0..j]
        # s1""
        # s2[0..j]
        if i < 0:
            return self.sum2[j]
        # 删除 s1[0..i]
        # s1[0..i]
        # s2""
        if j < 0:
            return self.sum1[i]
        if (i, j) not in self.memo:
            if s1[i] == s2[j]:
                # s1[0..i-1][i]
                # s2[0..j-1][j]
                self.memo[(i, j)] = self._minDistance(s1, i - 1, s2, j - 1)
            else:
                # 删除 s1[i] s2[j]
                # s1[0..i-1][i]
                # s2[0..j-1][j]
                sp1 = self._minDistance(s1, i - 1, s2, j - 1) + ord(s1[i]) + ord(s2[j])
                # 删除 s2[j]
                # s1[0..i]
                # s2[0..j-1][j]
                sp2 = self._minDistance(s1, i, s2, j - 1) + ord(s2[j])
                # 删除 s1[i]
                # s1[0..i-1][i]
                # s2[0..j]
                sp3 = self._minDistance(s1, i - 1, s2, j) + ord(s1[i])
                self.memo[(i, j)] = min(sp1, sp2, sp3)
        return self.memo[(i, j)]

    def prefixSum(self, s: str) -> List[int]:
        n = len(s)
        sum = [0] * n
        sum[0] = ord(s[0])
        for i in range(1, n):
            sum[i] = sum[i - 1] + ord(s[i])
        return sum
# https://leetcode.cn/submissions/detail/379340876/
```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```py
class Solution:
    def maxProfit(self, prices: List[int], fee: int) -> int:
        n = len(prices)
        # dp[i][0] = 第 i 天，空仓状态下的最大利润
        # dp[i][1] = 第 i 天，持仓状态下的最大利润
        dp = [[0] * 2 for _ in range(n)]
        dp[0][0] = 0
        dp[0][1] = -prices[0] - fee
        for i in range(1, n):
            # dp[i - 1][0]             >= dp[i - 1][0] - prices[i] - fee
            # dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            # => dp[i][0] >= dp[i][1]
            dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i])
            dp[i][1] = max(dp[i - 1][0] - prices[i] - fee, dp[i - 1][1])
        return dp[n - 1][0]
# https://leetcode.cn/submissions/detail/379365426/
```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```py
class Solution:
    def dailyTemperatures(self, temperatures: List[int]) -> List[int]:
        n = len(temperatures)
        ans = [0] * n
        minMonoStack = []
        for i in range(-1, -n - 1, -1):
            while len(minMonoStack) > 0 and temperatures[minMonoStack[-1]] <= temperatures[i]:
                minMonoStack.pop()
            ans[i] = 0 if len(minMonoStack) == 0 else minMonoStack[-1] - i
            minMonoStack.append(i)
        return ans
# https://leetcode.cn/submissions/detail/379193993/
```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```py
class DirectedEdge:
    def __init__(self, v: int, w: int, weight: int):
        self.__v = v
        self.__w = w
        self.__weight = weight

    def weight(self) -> int:
        return self.__weight

    def fromm(self) -> int:
        return self.__v

    def to(self) -> int:
        return self.__w


class EdgeWeightedDigraph:
    def __init__(self, V: int):
        self.__V = V
        self.__E = 0
        self.__adj = [[] for _ in range(V)]

    def V(self) -> int:
        return self.__V

    def E(self) -> int:
        return self.__E

    def addEdge(self, e: DirectedEdge):
        self.__adj[e.fromm()].append(e)
        self.__E += 1

    def adj(self, v: int) -> List[DirectedEdge]:
        return self.__adj[v]


class LazyDijkstraSP:
    def __init__(self, G: EdgeWeightedDigraph, s: int):
        self.__marked = [False] * G.V()
        self.__distTo = [math.inf] * G.V()
        self.__pq = []
        setattr(DirectedEdge, '__lt__',
                lambda e, f: self.__distTo[e.fromm()] + e.weight() < self.__distTo[f.fromm()] + f.weight())
        self.__distTo[s] = 0
        self.__relax(G, s)
        while len(self.__pq) > 0:
            e = heapq.heappop(self.__pq)
            self.__relax(G, e.to())

    def __relax(self, G: EdgeWeightedDigraph, v: int) -> None:
        self.__marked[v] = True
        for e in G.adj(v):
            w = e.to()
            if self.__distTo[w] > self.__distTo[v] + e.weight():
                self.__distTo[w] = self.__distTo[v] + e.weight()
                heapq.heappush(self.__pq, e)

    def distTo(self, v: int) -> int:
        return self.__distTo[v]


class Solution:
    def networkDelayTime(self, times: List[List[int]], n: int, k: int) -> int:
        graph = EdgeWeightedDigraph(n)
        for t in times:
            e = DirectedEdge(t[0] - 1, t[1] - 1, t[2])
            graph.addEdge(e)
        spt = LazyDijkstraSP(graph, k - 1)
        maxTime = 0
        for v in range(n):
            maxTime = max(maxTime, spt.distTo(v))
        return maxTime if maxTime < math.inf else -1
# https://leetcode.cn/submissions/detail/380575332/
```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```py
class Solution:
    ZERO = ord('0')
    NINE = ord('9')

    def openLock(self, deadends: List[str], target: str) -> int:
        marked = set(deadends)
        q = deque()
        source = '0000'
        if source not in marked:
            marked.add(source)
            q.append(source)
        count = 0
        while len(q) > 0:
            n = len(q)
            for _ in range(n):
                s = q.popleft()
                if s == target:
                    return count
                for j in range(4):
                    plus = self.plusOne(s, j)
                    if plus not in marked:
                        marked.add(plus)
                        q.append(plus)
                    minus = self.minusOne(s, j)
                    if minus not in marked:
                        marked.add(minus)
                        q.append(minus)
            count += 1
        return -1

    def plusOne(self, s: str, j: int) -> str:
        a = bytearray(s, encoding='utf-8')
        if a[j] == Solution.NINE:
            a[j] = Solution.ZERO
        else:
            a[j] += 1
        return a.decode(encoding='utf-8')

    def minusOne(self, s: str, j: int) -> str:
        a = bytearray(s, encoding='utf-8')
        if a[j] == Solution.ZERO:
            a[j] = Solution.NINE
        else:
            a[j] -= 1
        return a.decode(encoding='utf-8')
# https://leetcode.cn/submissions/detail/380089249/
```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```py
class Solution:
    def __init__(self):
        self.marked = None
        self.color = None
        self.bipartite = True

    def isBipartite(self, graph: List[List[int]]) -> bool:
        n = len(graph)
        self.marked = [False] * n
        self.color = [False] * n
        for v in range(n):
            if not self.marked[v]:
                self.dfs(graph, v)
                if not self.bipartite:
                    break
        return self.bipartite

    def dfs(self, graph: List[List[int]], v: int) -> None:
        self.marked[v] = True
        for w in graph[v]:
            if not self.marked[w]:
                self.color[w] = not self.color[v]
                self.dfs(graph, w)
            elif self.color[w] == self.color[v]:
                self.bipartite = False
                return
# https://leetcode.cn/submissions/detail/380401902/
```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```py
class Solution:
    def __init__(self):
        self.path = []
        self.ans = []

    def allPathsSourceTarget(self, graph: List[List[int]]) -> List[List[int]]:
        self.dfs(graph, 0)
        return self.ans

    def dfs(self, graph: List[List[int]], v: int) -> None:
        self.path.append(v)
        if v == len(graph) - 1:
            self.ans.append(self.path.copy())
        else:
            for w in graph[v]:
                self.dfs(graph, w)
        self.path.pop()
# https://leetcode.cn/submissions/detail/380585184/
```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```py
class Solution:
    def isNStraightHand(self, hand: List[int], groupSize: int) -> bool:
        if len(hand) % groupSize != 0:
            return False
        heapq.heapify(hand)
        counter = Counter(hand)
        while len(hand) > 0:
            x = heapq.heappop(hand)
            if counter[x] > 0:
                for y in range(x, x + groupSize):
                    if counter[y] == 0:
                        return False
                    counter[y] -= 1
        return True
# https://leetcode.cn/submissions/detail/380180673/
```

```py
class Solution:
    def isNStraightHand(self, hand: List[int], groupSize: int) -> bool:
        if len(hand) % groupSize != 0:
            return False
        hand.sort()
        counter = Counter()
        for x in hand:
            counter[x] += 1
        for x in hand:
            if counter[x] > 0:
                for y in range(x, x + groupSize):
                    if counter[y] == 0:
                        return False
                    counter[y] -= 1
        return True
# https://leetcode.cn/submissions/detail/380178356/
```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```py
class Solution:
    def minEatingSpeed(self, piles: List[int], h: int) -> int:
        lo, hi = 1, max(piles)
        ans = lo
        while lo <= hi:
            mid = lo + (hi - lo) // 2
            if self.canFinish(piles, h, mid):
                ans = mid
                hi = mid - 1
            else:
                lo = mid + 1
        return ans

    # 当吃香蕉的速度为 k 时，是否能在 h 小时内吃完
    def canFinish(self, piles: List[int], h: int, k: int) -> bool:
        hours = 0
        for p in piles:
            hours += math.ceil(p / k)
        return hours <= h
# https://leetcode.cn/submissions/detail/380292403/
```

## 876. 链表的中间结点

<https://leetcode.cn/problems/middle-of-the-linked-list/>

```py
class Solution:
    def middleNode(self, head: Optional[ListNode]) -> Optional[ListNode]:
        slow = head
        fast = head
        while fast is not None and fast.next is not None:
            slow = slow.next
            fast = fast.next.next
        return slow
# https://leetcode.cn/submissions/detail/378712078/
```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```py
class Solution:
    def __init__(self):
        self.marked = None
        self.color = None
        self.bipartite = True

    def possibleBipartition(self, n: int, dislikes: List[List[int]]) -> bool:
        graph = [[] for _ in range(n)]
        for d in dislikes:
            v = d[0] - 1
            w = d[1] - 1
            graph[v].append(w)
            graph[w].append(v)
        return self.isBipartite(graph)

    def isBipartite(self, graph: List[List[int]]) -> bool:
        n = len(graph)
        self.marked = [False] * n
        self.color = [False] * n
        for v in range(n):
            if not self.marked[v]:
                self.dfs(graph, v)
                if not self.bipartite:
                    break
        return self.bipartite

    def dfs(self, graph: List[List[int]], v: int) -> None:
        self.marked[v] = True
        for w in graph[v]:
            if not self.marked[w]:
                self.color[w] = not self.color[v]
                self.dfs(graph, w)
            elif self.color[w] == self.color[v]:
                self.bipartite = False
                return
# https://leetcode.cn/submissions/detail/380403190/
```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```py
class Solution:
    def __init__(self):
        self.valToIndex = {}

    def constructFromPrePost(self, preorder: List[int], postorder: List[int]) -> Optional[TreeNode]:
        for i in range(len(postorder)):
            self.valToIndex[postorder[i]] = i
        return self._constructFromPrePost(preorder, 0, len(preorder) - 1, postorder, 0, len(postorder) - 1)

    def _constructFromPrePost(self, preorder: List[int], preStart: int, preEnd: int, postorder: List[int],
                              postStart: int,
                              postEnd: int) -> Optional[TreeNode]:
        if preStart > preEnd:
            return None
        rootVal = preorder[preStart]
        root = TreeNode(rootVal)
        if preStart < preEnd:
            leftRootVal = preorder[preStart + 1]
            index = self.valToIndex[leftRootVal]
            leftSize = index - postStart + 1
            root.left = self._constructFromPrePost(preorder, preStart + 1, preStart + leftSize, postorder, postStart,
                                                   index)
            root.right = self._constructFromPrePost(preorder, preStart + leftSize + 1, preEnd, postorder, index + 1,
                                                    postEnd - 1)
        return root
# https://leetcode.cn/submissions/detail/380027837/
```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```py
class Solution:
    def sortArrayByParity(self, nums: List[int]) -> List[int]:
        # nums[0..i-1]     Even
        # nums[i..j]       Scanning
        # nums[j+1..n - 1] Odd
        i = 0
        j = len(nums) - 1
        while i < j:
            while i < j and nums[i] % 2 == 0:
                i += 1
            while i < j and nums[j] % 2 == 1:
                j -= 1
            nums[i], nums[j] = nums[j], nums[i]
        return nums
# https://leetcode.cn/submissions/detail/378703512/
```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```py
class Solution:
    def sortArray(self, nums: List[int]) -> List[int]:
        random.shuffle(nums)
        self.quickSort(nums, 0, len(nums) - 1)
        return nums

    def quickSort(self, nums: List[int], lo: int, hi: int) -> None:
        if lo >= hi:
            return
        j = self.partition(nums, lo, hi)
        self.quickSort(nums, lo, j - 1)
        self.quickSort(nums, j + 1, hi)

    def partition(self, nums: List[int], lo: int, hi: int) -> int:
        v = nums[lo]
        i, j = lo, hi + 1
        while True:
            i += 1
            while nums[i] < v:
                if i == hi:
                    break
                i += 1
            j -= 1
            while nums[j] > v:
                if j == lo:
                    break
                j -= 1
            if i >= j:
                break
            nums[i], nums[j] = nums[j], nums[i]
        nums[lo], nums[j] = nums[j], nums[lo]
        return j
# https://leetcode.cn/submissions/detail/380342510/
```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```py
# 性质一 一个「合法」括号组合的左括号数量一定等于右括号数量
# 性质二 对于一个「合法」的括号字符串组合 p，必然对于
# 任何 0 <= i < len(p) 都有：子串 p[0..i] 中
# 左括号的数量都大于或等于右括号的数量
class Solution:
    def minAddToMakeValid(self, s: str) -> int:
        insertLeft = 0  # 已插入左括号的数量
        needRight = 0  # 待插入右括号的数量
        for ch in s:
            if ch == '(':
                needRight += 1
            elif ch == ')':
                needRight -= 1
                # 性质二
                if needRight == -1:
                    # A).. -> A()..
                    # 『必须立即』在位置 i 前插入 1 个左括号
                    # 否则，后续任何插入都不能使区间 [0..i] 的匹配有效
                    insertLeft += 1
                    needRight = 0
        return insertLeft + needRight
# https://leetcode.cn/submissions/detail/378936860/
```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```py
class Solution:
    def sortArrayByParityII(self, nums: List[int]) -> List[int]:
        n = len(nums)
        i = 0
        j = 1
        while True:
            while i <= n - 2 and nums[i] % 2 == 0:
                i += 2
            while j <= n - 1 and nums[j] % 2 == 1:
                j += 2
            if i > n - 2 or j > n - 1:
                break
            nums[i], nums[j] = nums[j], nums[i]
        return nums
# https://leetcode.cn/submissions/detail/378706602/
```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```py
class Solution:
    def __init__(self):
        self.memo = {}

    def minFallingPathSum(self, matrix: List[List[int]]) -> int:
        n = len(matrix)
        ans = math.inf
        for col in range(n):
            ans = min(ans, self._minFallingPathSum(matrix, n - 1, col))
        return ans

    # 从 matrix[0][0..n-1] 到 matrix[row][col] 的最小下降路径和
    def _minFallingPathSum(self, matrix: List[List[int]], row: int, col: int) -> int:
        if col < 0 or col >= len(matrix[0]):
            return math.inf
        if row == 0:
            return matrix[row][col]
        key = (row, col)
        if key not in self.memo:
            sp1 = self._minFallingPathSum(matrix, row - 1, col - 1)
            sp2 = self._minFallingPathSum(matrix, row - 1, col)
            sp3 = self._minFallingPathSum(matrix, row - 1, col + 1)
            self.memo[key] = min(sp1, sp2, sp3) + matrix[row][col]
        return self.memo[key]
# https://leetcode.cn/submissions/detail/379624642/
```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```py
class Solution:
    def intervalIntersection(self, firstList: List[List[int]], secondList: List[List[int]]) -> List[List[int]]:
        ans = []
        i = j = 0
        while i < len(firstList) and j < len(secondList):
            start1, end1 = firstList[i]
            start2, end2 = secondList[j]
            if end1 < start2:
                # 不相交
                i += 1
            elif end2 < start1:
                # 不相交
                j += 1
            else:
                # 相交
                ans.append([max(start1, start2), min(end1, end2)])
                if end1 < end2:
                    i += 1
                else:
                    j += 1
        return ans
# https://leetcode.cn/submissions/detail/379029957/
```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```py
class UF:
    def __init__(self, n: int):
        self.parent = [i for i in range(n)]
        self.rank = [0] * n
        self.count = n

    def find(self, p: int) -> int:
        while p != self.parent[p]:
            self.parent[p] = self.parent[self.parent[p]]
            p = self.parent[p]
        return p

    def union(self, p: int, q: int) -> None:
        rootP = self.find(p)
        rootQ = self.find(q)
        if rootP != rootQ:
            if self.rank[rootP] < self.rank[rootQ]:
                self.parent[rootP] = rootQ
            elif self.rank[rootQ] < self.rank[rootP]:
                self.parent[rootQ] = rootP
            else:
                self.parent[rootP] = rootQ
                self.rank[rootQ] += 1
            self.count -= 1

    def connected(self, p: int, q: int) -> bool:
        return self.find(p) == self.find(q)


class Solution:
    def equationsPossible(self, equations: List[str]) -> bool:
        uf = UF(26)
        for e in equations:
            if e[1] == '=':
                p = ord(e[0]) - ord('a')
                q = ord(e[3]) - ord('a')
                uf.union(p, q)
        for e in equations:
            if e[1] == '!':
                p = ord(e[0]) - ord('a')
                q = ord(e[3]) - ord('a')
                if uf.connected(p, q):
                    return False
        return True
# https://leetcode.cn/submissions/detail/380399201/
```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```py
class Solution:
    def shipWithinDays(self, weights: List[int], days: int) -> int:
        lo, hi = max(weights), sum(weights)
        ans = lo
        while lo <= hi:
            mid = lo + (hi - lo) // 2
            if self.canFinish(weights, days, mid):
                ans = mid
                hi = mid - 1
            else:
                lo = mid + 1
        return ans

    # 当船的运载能力为 capacity 时，是否能在 days 天内送完
    def canFinish(self, weights: List[int], days: int, capacity: int) -> bool:
        minDays = 0
        i, n = 0, len(weights)
        while i < n:
            total = 0
            while i < n and total + weights[i] <= capacity:
                total += weights[i]
                i += 1
            minDays += 1
        return minDays <= days
# https://leetcode.cn/submissions/detail/380294837/
```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```py
class Solution:
    LAND = 1
    WATER = 0

    def numEnclaves(self, grid: List[List[int]]) -> int:
        m = len(grid)
        n = len(grid[0])
        # 淹没与左右边界的陆地相连的岛屿
        for row in range(m):
            self.floodFill(grid, row, 0)
            self.floodFill(grid, row, n - 1)
        # 淹没与上下边界的陆地相连的岛屿
        for col in range(n):
            self.floodFill(grid, 0, col)
            self.floodFill(grid, m - 1, col)
        count = 0
        for row in range(m):
            for col in range(n):
                if grid[row][col] == Solution.LAND:
                    count += 1
        return count

    def floodFill(self, grid: List[List[int]], row: int, col: int) -> None:
        if row < 0 or row >= len(grid) or col < 0 or col >= len(grid[0]) or grid[row][col] == Solution.WATER:
            return
        grid[row][col] = Solution.WATER
        self.floodFill(grid, row - 1, col)
        self.floodFill(grid, row + 1, col)
        self.floodFill(grid, row, col - 1)
        self.floodFill(grid, row, col + 1)
# https://leetcode.cn/submissions/detail/380254982/
```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```py
class Solution:
    def videoStitching(self, clips: List[List[int]], time: int) -> int:
        clips.sort(key=lambda clip: (clip[0], -clip[1]))
        count = 0
        cover_end = 0
        i, n = 0, len(clips)
        # 当 clips[i] 与 [0, cover_end] 重叠（相交或被覆盖）时
        while i < n and clips[i][0] <= cover_end:
            # 记录与 [0, cover_end] 重叠的所有区间中最大的 end
            max_end = 0
            while i < n and clips[i][0] <= cover_end:
                max_end = max(max_end, clips[i][1])
                i += 1
            count += 1
            cover_end = max_end
            if cover_end >= time:
                return count
        return -1
# https://leetcode.cn/submissions/detail/416600787/
```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```py
class Solution:
    def longestCommonSubsequence(self, text1: str, text2: str) -> int:
        n1 = len(text1)
        n2 = len(text2)
        # text1[0..i-1] = text1 的长度为 i 的前缀
        # text2[0..j-1] = text2 的长度为 j 的前缀
        # dp[i][j] = LCS(text1[0..i-1], text2[0..j-1]) 的长度
        dp = [[0] * (n2 + 1) for _ in range(n1 + 1)]
        for i in range(1, n1 + 1):
            for j in range(1, n2 + 1):
                if text1[i - 1] == text2[j - 1]:
                    dp[i][j] = dp[i - 1][j - 1] + 1
                else:
                    dp[i][j] = max(dp[i][j - 1], dp[i - 1][j])
        return dp[n1][n2]
# https://leetcode.cn/submissions/detail/379244153/
```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```py
class Solution:
    LAND = 0
    WATER = 1

    def closedIsland(self, grid: List[List[int]]) -> int:
        m = len(grid)
        n = len(grid[0])
        # 淹没与左右边界的陆地相连的岛屿
        for row in range(m):
            self.floodFill(grid, row, 0)
            self.floodFill(grid, row, n - 1)
        # 淹没与上下边界的陆地相连的岛屿
        for col in range(n):
            self.floodFill(grid, 0, col)
            self.floodFill(grid, m - 1, col)
        count = 0
        for row in range(m):
            for col in range(n):
                if grid[row][col] == Solution.LAND:
                    self.floodFill(grid, row, col)
                    count += 1
        return count

    def floodFill(self, grid: List[List[int]], row: int, col: int) -> None:
        if row < 0 or row >= len(grid) or col < 0 or col >= len(grid[0]) or grid[row][col] == Solution.WATER:
            return
        grid[row][col] = Solution.WATER
        self.floodFill(grid, row - 1, col)
        self.floodFill(grid, row + 1, col)
        self.floodFill(grid, row, col - 1)
        self.floodFill(grid, row, col + 1)
# https://leetcode.cn/submissions/detail/380254008/
```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```py
class Solution:
    def removeCoveredIntervals(self, intervals: List[List[int]]) -> int:
        intervals.sort(key=lambda interval: (interval[0], -interval[1]))
        count = len(intervals)
        maxEnd = 0
        for interval in intervals:
            end = interval[1]
            if end <= maxEnd:
                count -= 1
            else:
                maxEnd = end
        return count
# https://leetcode.cn/submissions/detail/379136870/
```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```py
class Solution:
    def __init__(self):
        self.nums = []

    def balanceBST(self, root: TreeNode) -> TreeNode:
        self.dfs(root)
        return self._sortedArrayToBST(self.nums, 0, len(self.nums) - 1)

    # 深度优先搜索，获取中序遍历结果
    def dfs(self, root: Optional[TreeNode]) -> None:
        if root is None:
            return
        self.dfs(root.left)
        self.nums.append(root.val)
        self.dfs(root.right)

    # 将有序子数组 nums[lo..hi] 转换为二叉搜索树
    def _sortedArrayToBST(self, nums: List[int], lo: int, hi: int) -> Optional[TreeNode]:
        if lo > hi:
            return None
        mid = lo + (hi - lo) // 2
        root = TreeNode(nums[mid])
        root.left = self._sortedArrayToBST(nums, lo, mid - 1)
        root.right = self._sortedArrayToBST(nums, mid + 1, hi)
        return root
# https://leetcode.cn/submissions/detail/380044521/
```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```py
class DirectedEdge:
    def __init__(self, v: int, w: int, weight: float):
        self.__v = v
        self.__w = w
        self.__weight = weight

    def weight(self) -> float:
        return self.__weight

    def fromm(self) -> int:
        return self.__v

    def to(self) -> int:
        return self.__w


class EdgeWeightedDigraph:
    def __init__(self, V: int):
        self.__V = V
        self.__E = 0
        self.__adj = [[] for _ in range(V)]

    def V(self) -> int:
        return self.__V

    def E(self) -> int:
        return self.__E

    def addEdge(self, e: DirectedEdge):
        self.__adj[e.fromm()].append(e)
        self.__E += 1

    def adj(self, v: int) -> List[DirectedEdge]:
        return self.__adj[v]


class LazyDijkstraLP:
    def __init__(self, G: EdgeWeightedDigraph, s: int):
        self.__marked = [False] * G.V()
        self.__distTo = [-math.inf] * G.V()
        self.__pq = []
        setattr(DirectedEdge, '__lt__',
                lambda e, f: self.__distToEdge(e) > self.__distToEdge(f))
        self.__distTo[s] = 1.0
        self.__relax(G, s)
        while len(self.__pq) > 0:
            e = heapq.heappop(self.__pq)
            self.__relax(G, e.to())

    def __relax(self, G: EdgeWeightedDigraph, v: int) -> None:
        self.__marked[v] = True
        for e in G.adj(v):
            w = e.to()
            d = self.__distToEdge(e)
            if self.__distTo[w] < d:
                self.__distTo[w] = d
                heapq.heappush(self.__pq, e)

    def __distToEdge(self, e: DirectedEdge) -> float:
        return self.__distTo[e.fromm()] * e.weight()

    def hasPathTo(self, v: int) -> bool:
        return self.__marked[v]

    def distTo(self, v: int) -> float:
        return self.__distTo[v]


class Solution:
    def maxProbability(self, n: int, edges: List[List[int]], succProb: List[float], start: int, end: int) -> float:
        graph = EdgeWeightedDigraph(n)
        for i in range(len(edges)):
            v = edges[i][0]
            w = edges[i][1]
            weight = succProb[i]
            graph.addEdge(DirectedEdge(v, w, weight))
            graph.addEdge(DirectedEdge(w, v, weight))
        lpt = LazyDijkstraLP(graph, start)
        if lpt.hasPathTo(end):
            return lpt.distTo(end)
        return 0.0
# https://leetcode.cn/submissions/detail/380580360/
```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```py
class Solution:
    def minInsertions(self, s: str) -> int:
        insertLeft = 0  # 已插入左括号的数量
        insertRight = 0  # 已插入右括号的数量
        needRight = 0  # 待插入右括号的数量
        for ch in s:
            if ch == '(':
                # A((B)(.. -> A((B))(..
                if needRight % 2 == 1:
                    # 『必须立即』在位置 i 前插入 1 个右括号
                    # 否则，后续任何插入都不能使区间 [0..i-1] 的匹配有效
                    insertRight += 1
                    needRight -= 1
                needRight += 2
            elif ch == ')':
                needRight -= 1
                # A).. -> A()..
                if needRight == -1:
                    # 『必须立即』在位置 i 前插入 1 个左括号
                    # 否则，后续任何插入都不能使区间 [0..i] 的匹配有效
                    insertLeft += 1
                    needRight = 1
        return insertLeft + insertRight + needRight
# https://leetcode.cn/submissions/detail/378937875/
```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```py
@total_ordering
class Edge:
    def __init__(self, v: int, w: int, weight: int):
        self.__v = v
        self.__w = w
        self.__weight = weight

    def weight(self) -> int:
        return self.__weight

    def either(self) -> int:
        return self.__v

    def other(self, vertex: int) -> int:
        return self.__w if vertex == self.__v else self.__v

    def __lt__(self, other):
        return self.__weight < other.__weight

    def __eq__(self, other):
        return self.__weight == other.__weight


class EdgeWeightedGraph:
    def __init__(self, V: int):
        self.__V = V
        self.__E = 0
        self.__adj = [[] for _ in range(V)]

    def V(self) -> int:
        return self.__V

    def E(self) -> int:
        return self.__E

    def addEdge(self, e: Edge):
        v = e.either()
        w = e.other(v)
        self.__adj[v].append(e)
        self.__adj[w].append(e)
        self.__E += 1

    def adj(self, v: int) -> List[Edge]:
        return self.__adj[v]


class LazyPrimMST:
    def __init__(self, G: EdgeWeightedGraph):
        self.__weight = 0
        self.__marked = [False] * G.V()
        self.__pq = []
        for v in range(G.V()):
            if not self.__marked[v]:
                self.__prim(G, v)

    def __prim(self, G: EdgeWeightedGraph, s: int) -> None:
        self.__scan(G, s)
        while len(self.__pq) > 0:
            e = heapq.heappop(self.__pq)
            v = e.either()
            w = e.other(v)
            if self.__marked[v] and self.__marked[w]:
                continue
            self.__weight += e.weight()
            if not self.__marked[v]:
                self.__scan(G, v)
            if not self.__marked[w]:
                self.__scan(G, w)

    def __scan(self, G: EdgeWeightedGraph, v: int) -> None:
        self.__marked[v] = True
        for e in G.adj(v):
            w = e.other(v)
            if not self.__marked[w]:
                heapq.heappush(self.__pq, e)

    def weight(self) -> int:
        return self.__weight


class Solution:
    def minCostConnectPoints(self, points: List[List[int]]) -> int:
        n = len(points)
        graph = EdgeWeightedGraph(n)
        for v in range(n):
            for w in range(v + 1, n):
                weight = abs(points[v][0] - points[w][0]) + abs(points[v][1] - points[w][1])
                graph.addEdge(Edge(v, w, weight))
        mst = LazyPrimMST(graph)
        return mst.weight()
# https://leetcode.cn/submissions/detail/380602875/
```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```py
class DirectedEdge:
    def __init__(self, v: int, w: int, weight: int):
        self.__v = v
        self.__w = w
        self.__weight = weight

    def weight(self) -> int:
        return self.__weight

    def fromm(self) -> int:
        return self.__v

    def to(self) -> int:
        return self.__w


class EdgeWeightedDigraph:
    def __init__(self, V: int):
        self.__V = V
        self.__E = 0
        self.__adj = [[] for _ in range(V)]

    def V(self) -> int:
        return self.__V

    def E(self) -> int:
        return self.__E

    def addEdge(self, e: DirectedEdge):
        self.__adj[e.fromm()].append(e)
        self.__E += 1

    def adj(self, v: int) -> List[DirectedEdge]:
        return self.__adj[v]


class LazyDijkstraSP:
    def __init__(self, G: EdgeWeightedDigraph, s: int):
        self.__marked = [False] * G.V()
        self.__distTo = [math.inf] * G.V()
        self.__pq = []
        setattr(DirectedEdge, '__lt__',
                lambda e, f: max(self.__distTo[e.fromm()], e.weight()) < max(self.__distTo[f.fromm()], f.weight()))
        self.__distTo[s] = 0
        self.__relax(G, s)
        while len(self.__pq) > 0:
            e = heapq.heappop(self.__pq)
            self.__relax(G, e.to())

    def __relax(self, G: EdgeWeightedDigraph, v: int) -> None:
        self.__marked[v] = True
        for e in G.adj(v):
            w = e.to()
            if self.__distTo[w] > max(self.__distTo[v], e.weight()):
                self.__distTo[w] = max(self.__distTo[v], e.weight())
                heapq.heappush(self.__pq, e)

    def distTo(self, v: int) -> int:
        return self.__distTo[v]


class Solution:
    def minimumEffortPath(self, heights: List[List[int]]) -> int:
        m = len(heights)
        n = len(heights[0])
        graph = EdgeWeightedDigraph(m * n)
        directions = ((0, 1), (0, -1), (1, 0), (-1, 0))
        for i in range(m):
            for j in range(n):
                for d in directions:
                    x = i + d[0]
                    y = j + d[1]
                    if 0 <= x <= m - 1 and 0 <= y <= n - 1:
                        v = i * n + j
                        w = x * n + y
                        weight = abs(heights[i][j] - heights[x][y])
                        graph.addEdge(DirectedEdge(v, w, weight))
        spt = LazyDijkstraSP(graph, 0)
        return spt.distTo((m - 1) * n + n - 1)
# https://leetcode.cn/submissions/detail/380573776/
```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```py
class Solution:
    LAND = 1
    WATER = 0

    def countSubIslands(self, grid1: List[List[int]], grid2: List[List[int]]) -> int:
        m = len(grid2)
        n = len(grid2[0])
        for row in range(m):
            for col in range(n):
                if grid2[row][col] == Solution.LAND and grid1[row][col] == Solution.WATER:
                    # 淹没『非子岛屿』
                    self.floodFill(grid2, row, col)
        count = 0
        for row in range(m):
            for col in range(n):
                if grid2[row][col] == Solution.LAND:
                    self.floodFill(grid2, row, col)
                    count += 1
        return count

    def floodFill(self, grid: List[List[int]], row: int, col: int) -> None:
        if row < 0 or row >= len(grid) or col < 0 or col >= len(grid[0]) or grid[row][col] == Solution.WATER:
            return
        grid[row][col] = Solution.WATER
        self.floodFill(grid, row - 1, col)
        self.floodFill(grid, row + 1, col)
        self.floodFill(grid, row, col - 1)
        self.floodFill(grid, row, col + 1)
# https://leetcode.cn/submissions/detail/380256907/
```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode.cn/problems/kth-node-from-end-of-list-lcci/>

```py
class Solution:
    def kthToLast(self, head: ListNode, k: int) -> int:
        slow = head
        fast = head
        for i in range(k):
            fast = fast.next
        while fast is not None:
            slow = slow.next
            fast = fast.next
        return slow.val
# https://leetcode.cn/submissions/detail/378714127/
```
