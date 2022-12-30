<!-- omit in toc -->
# LeetCode 题解：Python

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

```python
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

<https://leetcode-cn.com/problems/add-two-numbers/>

```python
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

<https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/>

```python
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
                    if c == d:
                        break
            ans = max(ans, right - left)
        return ans
# https://leetcode.cn/submissions/detail/379005811/
```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```python
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

```python
class Solution:
    def longestPalindrome(self, s: str) -> str:
        ans = ''
        for i in range(len(s)):
            s1 = self._longestPalindrome(s, i, i)
            if len(s1) > len(ans):
                ans = s1
            s2 = self._longestPalindrome(s, i, i + 1)
            if len(s2) > len(ans):
                ans = s2
        return ans

    # 字符串 s 中以 s[i] 和 s[j] 为中心的最长回文子串
    def _longestPalindrome(self, s: str, i: int, j: int) -> str:
        if i > j or j - i > 1:
            return ''
        while i >= 0 and j < len(s) and s[i] == s[j]:
            i -= 1
            j += 1
        return s[i + 1:j]
# https://leetcode.cn/submissions/detail/378867226/
```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```python

```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```python
class Solution:
    def maxArea(self, height: List[int]) -> int:
        ans = 0
        i = 0
        j = len(height) - 1
        while i < j:
            area = min(height[i], height[j]) * (j - i)
            ans = max(ans, area)
            if height[i] < height[j]:
                i += 1
            else:
                j -= 1
        return ans
# https://leetcode.cn/submissions/detail/378728904/
```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```python
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

<https://leetcode-cn.com/problems/3sum/>

```python
class Solution:
    def threeSum(self, nums: List[int]) -> List[List[int]]:
        nums.sort()
        return self.kSum(3, nums, 0, len(nums) - 1, 0)

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
# https://leetcode.cn/submissions/detail/378734279/
```

## 18. 四数之和

<https://leetcode.cn/problems/4sum/>

```python
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

<https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/>

```python
class Solution:
    def removeNthFromEnd(self, head: Optional[ListNode], n: int) -> Optional[ListNode]:
        slow = fast = ListNode(-1, head)
        for i in range(n):
            fast = fast.next
        while fast.next is not None:
            slow = slow.next
            fast = fast.next
        delNode = slow.next
        if delNode is head:
            head = head.next
        else:
            slow.next = delNode.next
        return head
# https://leetcode.cn/submissions/detail/378724721/
```

## 20. 有效的括号

<https://leetcode-cn.com/problems/valid-parentheses/>

```python
class Solution:
    def isValid(self, s: str) -> bool:
        n = len(s)
        if n % 2 == 1:
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
# https://leetcode.cn/submissions/detail/378932972/
```

## 21. 合并两个有序链表

<https://leetcode-cn.com/problems/merge-two-sorted-lists/>

```python
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

```python
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

<https://leetcode-cn.com/problems/merge-k-sorted-lists/>

```python
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

<https://leetcode-cn.com/problems/swap-nodes-in-pairs/>

```python
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

```python
class Solution:
    def reverseKGroup(self, head: Optional[ListNode], k: int) -> Optional[ListNode]:
        if head is None or head.next is None:
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
# https://leetcode.cn/submissions/detail/378895898/
```

## 26. 删除有序数组中的重复项

<https://leetcode.cn/problems/remove-duplicates-from-sorted-array/>

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
class Solution:
    def __init__(self):
        self.nums = None
        self.target = None
        self.pathSum = 0
        self.path = []  # 取 nums[edge] 为元素
        self.ans = []

    def combinationSum(self, candidates: List[int], target: int) -> List[List[int]]:
        self.nums = candidates
        self.target = target
        self.backtrack(-1)
        return self.ans

    # edge = 取数组 nums 的索引为值
    def backtrack(self, edge: int) -> None:
        if self.pathSum == self.target:
            self.ans.append(self.path.copy())
            return
        if edge == -1:
            edge = 0
        # 避免重复，从 edge 开始选择
        # 例如 [1->2] 和 [2->1] 是重复的
        for e in range(edge, len(self.nums)):
            x = self.nums[e]
            if self.pathSum + x <= self.target:
                self.pathSum += x
                self.path.append(x)
                self.backtrack(e)
                self.pathSum -= x
                self.path.pop()
# https://leetcode.cn/submissions/detail/379640591/
```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
class Solution:
    def __init__(self):
        self.memo = {}

    def minDistance(self, s1: str, s2: str) -> int:
        return self._minDistance(s1, len(s1) - 1, s2, len(s2) - 1)

    # 子串 s1[0..i] s2[0..j] 的最小编辑距离
    def _minDistance(self, s1: str, i: int, s2: str, j: int) -> int:
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
                self.memo[(i, j)] = self._minDistance(s1, i - 1, s2, j - 1)
            else:
                # 替换 s1[i] 为 s2[j]
                # s1[0..i-1][i]
                # s2[0..j-1][j]
                sp1 = self._minDistance(s1, i - 1, s2, j - 1) + 1
                # 插入 s2[j] 到 s1
                # s1[0..i]
                # s2[0..j-1][j]
                sp2 = self._minDistance(s1, i, s2, j - 1) + 1
                # 删除 s1[i]
                # s1[0..i-1][i]
                # s2[0..j]
                sp3 = self._minDistance(s1, i - 1, s2, j) + 1
                self.memo[(i, j)] = min(sp1, sp2, sp3)
        return self.memo[(i, j)]
# https://leetcode.cn/submissions/detail/379341598/
```

```python
class Solution:
    def minDistance(self, s1: str, s2: str) -> int:
        return self._minDistance(s1, len(s1) - 1, s2, len(s2) - 1)

    # 子串 s1[0..i] s2[0..j] 的最小编辑距离
    @cache
    def _minDistance(self, s1: str, i: int, s2: str, j: int) -> int:
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
            return self._minDistance(s1, i - 1, s2, j - 1)
        else:
            # 替换 s1[i] 为 s2[j]
            # s1[0..i-1][i]
            # s2[0..j-1][j]
            sp1 = self._minDistance(s1, i - 1, s2, j - 1) + 1
            # 插入 s2[j] 到 s1
            # s1[0..i]
            # s2[0..j-1][j]
            sp2 = self._minDistance(s1, i, s2, j - 1) + 1
            # 删除 s1[i]
            # s1[0..i-1][i]
            # s2[0..j]
            sp3 = self._minDistance(s1, i - 1, s2, j) + 1
            return min(sp1, sp2, sp3)
# https://leetcode.cn/submissions/detail/379346358/
```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
class Solution:
    def __init__(self):
        self.nums = None
        self.path = []  # 取 nums[edge] 为元素
        self.ans = []

    def subsetsWithDup(self, nums: List[int]) -> List[List[int]]:
        nums.sort()
        self.nums = nums
        self.backtrack(-1)
        return self.ans

    # edge = 取数组 nums 的索引为值
    def backtrack(self, edge: int) -> None:
        self.ans.append(self.path.copy())
        prev = None
        # 避免重复，从 edge + 1 开始选择
        # 例如 [1->2] 和 [2->1] 是重复的
        for e in range(edge + 1, len(self.nums)):
            x = self.nums[e]
            if x != prev:
                prev = x
                self.path.append(x)
                self.backtrack(e)
                self.path.pop()
# https://leetcode.cn/submissions/detail/379633418/
```

## 92. 反转链表 II

<https://leetcode-cn.com/problems/reverse-linked-list-ii/>

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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

```python
class Solution:
    def levelOrder(self, root: Optional[TreeNode]) -> List[List[int]]:
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
        return ans
# https://leetcode.cn/submissions/detail/379986876/
```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```python
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

```python
class Solution:
    def maxDepth(self, root: Optional[TreeNode]) -> int:
        if root is None:
            return 0
        return 1 + max(self.maxDepth(root.left), self.maxDepth(root.right))
# https://leetcode.cn/submissions/detail/380117622/
```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```python
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

```python
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

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```python
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

```python
class Solution:
    def sortedArrayToBST(self, nums: List[int]) -> Optional[TreeNode]:
        return self._sortedArrayToBST(nums, 0, len(nums) - 1)

    # 将有序子数组 nums[lo..hi] 转换为二叉搜索树
    def _sortedArrayToBST(self, nums: List[int], lo: int, hi: int) -> Optional[TreeNode]:
        if lo > hi:
            return None
        mid = lo + (hi - lo) // 2
        root = TreeNode(nums[mid])
        root.left = self._sortedArrayToBST(nums, lo, mid - 1)
        root.right = self._sortedArrayToBST(nums, mid + 1, hi)
        return root
# https://leetcode.cn/submissions/detail/380041697/
```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```python
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

```python
class Solution:
    def minDepth(self, root: Optional[TreeNode]) -> int:
        depth = 0
        q = deque()
        if root is not None:
            q.append(root)
        while len(q) > 0:
            depth += 1
            n = len(q)
            for i in range(n):
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
# https://leetcode.cn/submissions/detail/380078550/
```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```python
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

```python
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

```python

```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```python
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

```python
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

```python
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

```python
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

```python
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

```python
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
                if grid[row][col] == Solution.LAND:
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
# https://leetcode.cn/submissions/detail/380264429/
```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```python
class Solution:
    def singleNumber(self, nums: List[int]) -> int:
        ans = 0
        for x in nums:
            ans ^= x
        return ans
# https://leetcode.cn/submissions/detail/380301369/
```

## 141. 环形链表

<https://leetcode-cn.com/problems/linked-list-cycle/>

```python
class Solution:
    def hasCycle(self, head: Optional[ListNode]) -> bool:
        slow = head
        fast = head
        while fast is not None and fast.next is not None:
            slow = slow.next
            fast = fast.next.next
            if slow is fast:
                return True
        return False
# https://leetcode.cn/submissions/detail/378719570/
```

## 142. 环形链表 II

<https://leetcode-cn.com/problems/linked-list-cycle-ii/>

```python
class Solution:
    def detectCycle(self, head: Optional[ListNode]) -> Optional[ListNode]:
        slow = head
        fast = head
        while fast is not None and fast.next is not None:
            slow = slow.next
            fast = fast.next.next
            if slow is fast:
                fast = head
                while slow is not fast:
                    slow = slow.next
                    fast = fast.next
                return slow
        return None
# https://leetcode.cn/submissions/detail/378721333/
```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```python
class Solution:
    def reorderList(self, head: Optional[ListNode]) -> None:
        slow = fast = head
        while fast.next is not None and fast.next.next is not None:
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
# https://leetcode.cn/submissions/detail/378898435/
```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```python
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

```python
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

```python
class Node:
    def __init__(self, key: int, val: int):
        self.key = key
        self.val = val
        self.prev = None
        self.next = None


class DoublyLinkedList:
    def __init__(self):
        self.__first = None
        self.__last = None
        self.__n = 0

    def addLast(self, x: Node) -> None:
        if self.__n == 0:
            self.__first = x
            self.__last = x
            self.__n = 1
        else:
            self.__last.next = x
            x.prev = self.__last
            self.__last = x
            self.__n += 1

    def removeFirst(self) -> Node:
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

    def removeLast(self) -> Node:
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

    def remove(self, x: Node) -> None:
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
        self.__list = DoublyLinkedList()
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
        x = Node(key, val)
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
# https://leetcode.cn/submissions/detail/380510819/
```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```python

```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```python

```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```python

```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```python

```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```python

```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```python

```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```python

```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```python

```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```python

```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```python

```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```python

```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```python

```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```python

```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```python

```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```python

```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```python

```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```python

```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```python

```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```python

```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```python

```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```python

```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```python

```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```python

```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```python

```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```python

```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```python

```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```python

```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```python

```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```python

```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```python

```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```python

```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```python

```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```python

```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```python

```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```python

```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```python

```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```python

```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```python

```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```python

```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```python

```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```python

```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```python

```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```python

```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```python

```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```python

```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```python

```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```python

```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```python

```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```python

```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```python

```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```python

```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```python

```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```python

```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```python

```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```python

```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```python

```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```python

```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```python

```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```python

```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```python

```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```python

```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```python

```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```python

```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```python

```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```python

```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```python

```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```python

```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```python

```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```python

```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```python

```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```python

```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```python

```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```python

```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```python

```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```python

```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```python

```

## 876. 链表的中间结点

<https://leetcode-cn.com/problems/middle-of-the-linked-list/>

```python

```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```python

```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```python

```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```python

```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```python

```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```python

```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```python

```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```python

```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```python

```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```python

```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```python

```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```python

```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```python

```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```python

```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```python

```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```python

```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```python

```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```python

```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```python

```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```python

```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```python

```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```python

```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode-cn.com/problems/kth-node-from-end-of-list-lcci/>

```python

```
