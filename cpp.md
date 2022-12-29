<!-- omit in toc -->
# LeetCode 题解：C++

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

```cpp
class Solution {
public:
    vector<int> twoSum(vector<int> &nums, int target) {
        unordered_map<int, int> valToIndex;
        for (int i = 0; i < nums.size(); ++i) {
            int x = nums[i];
            int need = target - x;
            if (valToIndex.count(need) == 1) {
                return {valToIndex[need], i};
            }
            valToIndex[x] = i;
        }
        return {-1, -1};
    }
};
// https://leetcode.cn/submissions/detail/366686076/
```

## 2. 两数相加

<https://leetcode-cn.com/problems/add-two-numbers/>

```cpp
class Solution {
public:
    ListNode *addTwoNumbers(ListNode *l1, ListNode *l2) {
        auto *dummyHead = new ListNode();
        ListNode *ptr = dummyHead;
        int carry = 0;
        while (l1 != nullptr || l2 != nullptr || carry > 0) {
            int sum = carry;
            if (l1 != nullptr) {
                sum += l1->val;
                l1 = l1->next;
            }
            if (l2 != nullptr) {
                sum += l2->val;
                l2 = l2->next;
            }
            ptr->next = new ListNode(sum % 10);
            ptr = ptr->next;
            carry = sum / 10;
        }
        ListNode *head = dummyHead->next;
        delete dummyHead;
        return head;
    }
};
// https://leetcode.cn/submissions/detail/391581946/
```

## 3. 无重复字符的最长子串

<https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/>

```cpp
class Solution {
public:
    int lengthOfLongestSubstring(string s) {
        int ans = 0;
        unordered_set<char> window;
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        int left = 0, right = 0;
        while (right < s.size()) {
            char add = s[right];
            if (window.count(add) == 0) {
                window.insert(add);
                ++right;
            } else {
                while (left <= right) {
                    char del = s[left++];
                    window.erase(del);
                    if (add == del) {
                        break;
                    }
                }
            }
            ans = max(ans, right - left);
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391684221/
```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```cpp
class Solution {
public:
    double findMedianSortedArrays(vector<int> &nums1, vector<int> &nums2) {
        int total = nums1.size() + nums2.size();
        int half = total / 2;
        if (total % 2 == 0) {
            int k1 = getKthElement(nums1, nums2, half);
            int k2 = getKthElement(nums1, nums2, half + 1);
            return (k1 + k2) / 2.0;
        }
        return getKthElement(nums1, nums2, half + 1);
    }

private:
    // 寻找两个正序数组 nums1 和 nums2 从小到大排列的第 k 个数
    int getKthElement(const vector<int> &nums1, const vector<int> &nums2, int k) {
        int n1 = nums1.size(), n2 = nums2.size();
        int start1 = 0, start2 = 0;
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
            int half = k / 2;
            int i = min(n1 - 1, start1 + half - 1);
            int j = min(n2 - 1, start2 + half - 1);
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
};
// https://leetcode.cn/submissions/detail/365180070/
```

```cpp
class Solution {
public:
    double findMedianSortedArrays(vector<int> &nums1, vector<int> &nums2) {
        int total = nums1.size() + nums2.size();
        int half = total / 2;
        if (total % 2 == 0) {
            int k1 = getKthElement(nums1, 0, nums2, 0, half);
            int k2 = getKthElement(nums1, 0, nums2, 0, half + 1);
            return (k1 + k2) / 2.0;
        }
        return getKthElement(nums1, 0, nums2, 0, half + 1);
    }

private:
    // 寻找两个正序数组 nums1 和 nums2 从小到大排列的第 k 个数
    int getKthElement(const vector<int> &nums1, int start1, const vector<int> &nums2, int start2, int k) {
        int n1 = nums1.size();
        if (start1 == n1) {
            return nums2[start2 + k - 1];
        }
        int n2 = nums2.size();
        if (start2 == n2) {
            return nums1[start1 + k - 1];
        }
        if (k == 1) {
            return min(nums1[start1], nums2[start2]);
        }
        int half = k / 2;
        int i = min(n1 - 1, start1 + half - 1);
        int j = min(n2 - 1, start2 + half - 1);
        if (nums1[i] < nums2[j]) {
            // 排除 nums1[start1..i] 共 i-start1+1 个元素
            return getKthElement(nums1, i + 1, nums2, start2, k - (i - start1 + 1));
        } else {
            // 排除 nums2[start2..j] 共 j-start2+1 个元素
            return getKthElement(nums1, start1, nums2, j + 1, k - (j - start2 + 1));
        }
    }
};
// https://leetcode.cn/submissions/detail/365179063/
```

## 5. 最长回文子串

<https://leetcode.cn/problems/longest-palindromic-substring/>

```cpp
class Solution {
public:
    string longestPalindrome(string s) {
        string s1, s2, ans;
        for (int i = 0; i < s.size(); ++i) {
            s1 = longestPalindrome(s, i, i);
            if (s1.size() > ans.size()) {
                ans = s1;
            }
            s2 = longestPalindrome(s, i, i + 1);
            if (s2.size() > ans.size()) {
                ans = s2;
            }
        }
        return ans;
    }

private:
    // 返回字符串 s 中以 s[i] 和 s[j] 为中心的最长回文子串
    string longestPalindrome(const string &s, int i, int j) {
        if (i > j || j - i > 1) {
            return "";
        }
        while (i >= 0 && j < s.size() && s[i] == s[j]) {
            --i;
            ++j;
        }
        return s.substr(i + 1, j - i - 1);
    }
};
// https://leetcode.cn/submissions/detail/364086132/
```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```cpp
class Solution {
public:
    int reverse(int x) {
        int y = 0;
        while (x != 0) {
            if (abs(y) > INT_MAX / 10) {
                return 0;
            }
            y = y * 10 + x % 10;
            x = x / 10;
        }
        return y;
    }
};
// https://leetcode.cn/submissions/detail/368379961/
```

```cpp
class Solution {
public:
    int reverse(int x) {
        if (x == 0) {
            return 0;
        }
        string original = to_string(abs(x));
        string reverse = string(original.rbegin(), original.rend());
        string maxint = to_string(INT_MAX);
        if (reverse.size() < maxint.size() || reverse < maxint) {
            return stoi(reverse) * (x / abs(x));
        }
        return 0;
    }
};
// https://leetcode.cn/submissions/detail/368382146/
```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```cpp
class Solution {
public:
    int maxArea(vector<int> &height) {
        int ans = 0;
        int i = 0, j = height.size() - 1;
        while (i < j) {
            int area = min(height[i], height[j]) * (j - i);
            ans = max(ans, area);
            if (height[i] < height[j]) {
                ++i;
            } else {
                --j;
            }
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391453039/
```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```cpp
class Solution {
public:
    string longestCommonPrefix(vector<string> &strs) {
        return longestCommonPrefix(strs, 0, strs.size() - 1);
    }

private:
    string longestCommonPrefix(const vector<string> &strs, int lo, int hi) {
        if (lo == hi) {
            return strs[lo];
        }
        int mid = lo + (hi - lo) / 2;
        string left = longestCommonPrefix(strs, lo, mid);
        string right = longestCommonPrefix(strs, mid + 1, hi);
        return longestCommonPrefix(left, right);
    }

    string longestCommonPrefix(const string &s1, const string &s2) {
        int n = min(s1.size(), s2.size());
        int i = 0;
        while (i < n && s1[i] == s2[i]) {
            ++i;
        }
        return s1.substr(0, i);
    }
};
// https://leetcode.cn/submissions/detail/391682154/
```

```cpp
class Solution {
public:
    string longestCommonPrefix(vector<string> &strs) {
        string ans = strs[0];
        for (int i = 1; i < strs.size(); ++i) {
            ans = longestCommonPrefix(ans, strs[i]);
        }
        return ans;
    }

private:
    string longestCommonPrefix(const string &s1, const string &s2) {
        int n = min(s1.size(), s2.size());
        int i = 0;
        while (i < n && s1[i] == s2[i]) {
            ++i;
        }
        return s1.substr(0, i);
    }
};
// https://leetcode.cn/submissions/detail/391682316/
```

## 15. 三数之和

<https://leetcode-cn.com/problems/3sum/>

```cpp
class Solution {
public:
    vector<vector<int>> threeSum(vector<int> &nums) {
        sort(nums.begin(), nums.end());
        return kSum(3, nums, 0, nums.size() - 1, 0);
    }

private:
    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
    vector<vector<int>> kSum(int k, const vector<int> &nums, int lo, int hi, long target) {
        if (k < 2 || hi - lo + 1 < k) {
            return {};
        }
        if (k == 2) {
            return twoSum(nums, lo, hi, target);
        }
        vector<vector<int>> res;
        int i = lo;
        while (i <= hi) {
            int curNum = nums[i];
            vector<vector<int>> sub = kSum(k - 1, nums, i + 1, hi, target - curNum);
            for (auto &v: sub) {
                v.push_back(curNum);
                res.push_back(v);
            }
            while (++i <= hi && nums[i] == curNum) {}
        }
        return res;
    }

    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的二元组
    vector<vector<int>> twoSum(const vector<int> &nums, int lo, int hi, long target) {
        vector<vector<int>> res;
        while (lo < hi) {
            int first = nums[lo], second = nums[hi];
            int sum = first + second;
            if (sum < target) {
                while (++lo < hi && nums[lo] == first) {}
            } else if (sum > target) {
                while (lo < --hi && nums[hi] == second) {}
            } else {
                res.push_back({first, second});
                while (++lo < hi && nums[lo] == first) {}
                while (lo < --hi && nums[hi] == second) {}
            }
        }
        return res;
    }
};
// https://leetcode.cn/submissions/detail/391681600/
```

## 18. 四数之和

<https://leetcode.cn/problems/4sum/>

```cpp
class Solution {
public:
    vector<vector<int>> fourSum(vector<int> &nums, int target) {
        sort(nums.begin(), nums.end());
        return kSum(4, nums, 0, nums.size() - 1, target);
    }

private:
    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
    vector<vector<int>> kSum(int k, const vector<int> &nums, int lo, int hi, long target) {
        if (k < 2 || hi - lo + 1 < k) {
            return {};
        }
        if (k == 2) {
            return twoSum(nums, lo, hi, target);
        }
        vector<vector<int>> res;
        int i = lo;
        while (i <= hi) {
            int curNum = nums[i];
            vector<vector<int>> sub = kSum(k - 1, nums, i + 1, hi, target - curNum);
            for (auto &v: sub) {
                v.push_back(curNum);
                res.push_back(v);
            }
            while (++i <= hi && nums[i] == curNum) {}
        }
        return res;
    }

    // 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的二元组
    vector<vector<int>> twoSum(const vector<int> &nums, int lo, int hi, long target) {
        vector<vector<int>> res;
        while (lo < hi) {
            int first = nums[lo], second = nums[hi];
            int sum = first + second;
            if (sum < target) {
                while (++lo < hi && nums[lo] == first) {}
            } else if (sum > target) {
                while (lo < --hi && nums[hi] == second) {}
            } else {
                res.push_back({first, second});
                while (++lo < hi && nums[lo] == first) {}
                while (lo < --hi && nums[hi] == second) {}
            }
        }
        return res;
    }
};
// https://leetcode.cn/submissions/detail/391681857/
```

## 19. 删除链表的倒数第 N 个结点

<https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/>

```cpp
class Solution {
public:
    ListNode *removeNthFromEnd(ListNode *head, int n) {
        auto *dummyHead = new ListNode(-1, head);
        ListNode *slow = dummyHead;
        ListNode *fast = dummyHead;
        for (int i = 1; i <= n; ++i) {
            fast = fast->next;
        }
        while (fast != nullptr && fast->next != nullptr) {
            slow = slow->next;
            fast = fast->next;
        }
        ListNode *x = slow->next;
        if (x == head) { // 删除的是头结点
            head = head->next;
        } else {
            slow->next = slow->next->next;
        }
        delete x;
        delete dummyHead;
        return head;
    }
};
// https://leetcode.cn/submissions/detail/391560727/
```

## 20. 有效的括号

<https://leetcode-cn.com/problems/valid-parentheses/>

```cpp
class Solution {
public:
    bool isValid(const string &s) {
        if (s.size() % 2 == 1) {
            return false;
        }
        stack<char> stk;
        for (const auto &ch: s) {
            switch (ch) {
                case '(': {
                    stk.push(')');
                    break;
                }
                case '[': {
                    stk.push(']');
                    break;
                }
                case '{': {
                    stk.push('}');
                    break;
                }
                default: {
                    if (stk.empty() || stk.top() != ch) {
                        return false;
                    }
                    stk.pop();
                }
            }
        }
        return stk.empty();
    }
};
// https://leetcode.cn/submissions/detail/391694589/
```

## 21. 合并两个有序链表

<https://leetcode-cn.com/problems/merge-two-sorted-lists/>

```cpp
class Solution {
public:
    ListNode *mergeTwoLists(ListNode *list1, ListNode *list2) {
        auto *dummyHead = new ListNode();
        ListNode *ptr = dummyHead;
        while (list1 != nullptr && list2 != nullptr) {
            if (list1->val < list2->val) {
                ptr->next = list1;
                list1 = list1->next;
            } else {
                ptr->next = list2;
                list2 = list2->next;
            }
            ptr = ptr->next;
        }
        ptr->next = (list1 == nullptr ? list2 : list1);
        ListNode *head = dummyHead->next;
        delete dummyHead;
        return head;
    }
};
// https://leetcode.cn/submissions/detail/391583117/
```

## 22. 括号生成

<https://leetcode.cn/problems/generate-parentheses/>

```cpp
class Solution {
public:
    vector<string> generateParenthesis(int n) {
        backtrack(n);
        return ans;
    }

private:
    void backtrack(int n) {
        // 对于一个「合法」的括号字符串组合 p，必然对于任何 0 <= i < len(p) 都有：
        // 子串 p[0..i] 中左括号的数量都大于或等于右括号的数量
        if (left < right || left > n) {
            return;
        }
        // 一个「合法」括号组合的左括号数量一定等于右括号数量
        if (left == n && right == n) {
            ans.push_back(path);
            return;
        }
        // edge = 取 '(', ')' 为值
        // 使用『左括号』
        path.push_back('(');
        ++left;
        backtrack(n);
        path.pop_back();
        --left;
        // 使用『右括号』
        path.push_back(')');
        ++right;
        backtrack(n);
        path.pop_back();
        --right;
    }

    string path;   // 取 '(', ')' 为元素
    int left = 0;  // 已使用的『左括号』数量
    int right = 0; // 已使用的『右括号』数量
    vector<string> ans;
};
// https://leetcode.cn/submissions/detail/391670726/
```

```cpp
class Solution {
public:
    vector<string> generateParenthesis(int n) {
        dfs(n, '-');
        return ans;
    }

private:
    // vertex = 取 '(', ')' 为值
    void dfs(int n, char vertex) {
        if (vertex != '-') {
            path.push_back(vertex);
            if (vertex == '(') {        // 使用『左括号』
                ++left;
            } else if (vertex == ')') { // 使用『右括号』
                ++right;
            }
        }
        if (left < right || left > n) {
            // 对于一个「合法」的括号字符串组合 p，必然对于任何 0 <= i < len(p) 都有：
            // 子串 p[0..i] 中左括号的数量都大于或等于右括号的数量
        } else if (left == n && right == n) {
            // 一个「合法」括号组合的左括号数量一定等于右括号数量
            ans.push_back(path);
        } else {
            dfs(n, '(');
            dfs(n, ')');
        }
        if (vertex != '-') {
            path.pop_back();
            if (vertex == '(') {
                --left;
            } else if (vertex == ')') {
                --right;
            }
        }
    }

    string path;   // 取 '(', ')' 为元素
    int left = 0;  // 已使用的『左括号』数量
    int right = 0; // 已使用的『右括号』数量
    vector<string> ans;
};
// https://leetcode.cn/submissions/detail/391671261/
```

## 23. 合并 K 个升序链表

<https://leetcode-cn.com/problems/merge-k-sorted-lists/>

```cpp
class Solution {
public:
    ListNode *mergeKLists(vector<ListNode *> &lists) {
        ListNode *head = nullptr;
        for (auto &l: lists) {
            head = mergeTwoLists(head, l);
        }
        return head;
    }

private:
    ListNode *mergeTwoLists(ListNode *list1, ListNode *list2) {
        auto *dummyHead = new ListNode();
        ListNode *ptr = dummyHead;
        while (list1 != nullptr && list2 != nullptr) {
            if (list1->val < list2->val) {
                ptr->next = list1;
                list1 = list1->next;
            } else {
                ptr->next = list2;
                list2 = list2->next;
            }
            ptr = ptr->next;
        }
        ptr->next = (list1 == nullptr ? list2 : list1);
        ListNode *head = dummyHead->next;
        delete dummyHead;
        return head;
    }
};
// https://leetcode.cn/submissions/detail/391583801/
```

```cpp
class Solution {
public:
    ListNode *mergeKLists(vector<ListNode *> &lists) {
        ListNode *ans = nullptr;
        for (auto &l : lists) {
            ans = mergeTwoLists(ans, l);
        }
        return ans;
    }

private:
    ListNode *mergeTwoLists(ListNode *list1, ListNode *list2) {
        ListNode *dummyHead = new ListNode();
        ListNode *ptr = dummyHead;
        while (list1 != nullptr && list2 != nullptr) {
            if (list1->val < list2->val) {
                ptr->next = list1;
                list1 = list1->next;
            } else {
                ptr->next = list2;
                list2 = list2->next;
            }
            ptr = ptr->next;
        }
        ptr->next = (list1 == nullptr ? list2 : list1);
        ListNode *head = dummyHead->next;
        delete dummyHead;
        return head;
    }
};
// https://leetcode.cn/submissions/detail/361147035/
```

## 24. 两两交换链表中的节点

<https://leetcode-cn.com/problems/swap-nodes-in-pairs/>

```cpp
class Solution {
public:
    ListNode *swapPairs(ListNode *head) {
        if (head == nullptr || head->next == nullptr) {
            return head;
        }
        ListNode *x = head;
        ListNode *y = head->next;
        ListNode *z = head->next->next;
        y->next = x;
        x->next = swapPairs(z);
        return y;
    }
};
// https://leetcode.cn/submissions/detail/368677178/
```

```cpp
class Solution {
public:
    ListNode *swapPairs(ListNode *head) {
        ListNode *reverseHead = nullptr;
        ListNode *reverseTail = nullptr;
        while (true) {
            if (head == nullptr || head->next == nullptr) {
                break;
            }
            ListNode *x = head;
            ListNode *y = head->next;
            ListNode *z = head->next->next;
            y->next = x;
            x->next = z;
            if (reverseHead == nullptr) {
                reverseHead = y;
            } else {
                reverseTail->next = y;
            }
            reverseTail = x;
            head = z;
        }
        return reverseHead == nullptr ? head : reverseHead;
    }
};
// https://leetcode.cn/submissions/detail/368676743/
```

## 25. K 个一组翻转链表

<https://leetcode.cn/problems/reverse-nodes-in-k-group/>

```cpp
class Solution {
public:
    ListNode *reverseKGroup(ListNode *head, int k) {
        if (head == nullptr || head->next == nullptr) {
            return head;
        }
        ListNode *ptr = head;
        for (int i = 1; i <= k - 1; ++i) {
            ptr = ptr->next;
            if (ptr == nullptr) {
                return head;
            }
        }
        ListNode *nextGroup = ptr->next;
        ptr->next = nullptr;
        ListNode *reverseHead = reverseList(head);
        head->next = reverseKGroup(nextGroup, k);
        return reverseHead;
    }

private:
    ListNode *reverseList(ListNode *head) {
        ListNode *reverseHead = nullptr;
        while (head != nullptr) {
            ListNode *next = head->next;
            head->next = reverseHead;
            reverseHead = head;
            head = next;
        }
        return reverseHead;
    }
};
// https://leetcode.cn/submissions/detail/391538293/
```

```cpp
class Solution {
public:
    ListNode *reverseKGroup(ListNode *head, int k) {
        ListNode *reverseHead = nullptr;
        ListNode *reverseTail = nullptr;
        while (true) {
            ListNode *ptr = head;
            for (int i = 1; i <= k - 1 && ptr != nullptr; ++i) {
                ptr = ptr->next;
            }
            if (ptr == nullptr) {
                break;
            }
            ListNode *nextGroup = ptr->next;
            ptr->next = nullptr;
            if (reverseHead == nullptr) {
                reverseHead = reverseList(head);
            } else {
                reverseTail->next = reverseList(head);
            }
            reverseTail = head;
            reverseTail->next = nextGroup;
            head = nextGroup;
        }
        return reverseHead == nullptr ? head : reverseHead;
    }

private:
    ListNode *reverseList(ListNode *head) {
        ListNode *reverseHead = nullptr;
        while (head != nullptr) {
            ListNode *next = head->next;
            head->next = reverseHead;
            reverseHead = head;
            head = next;
        }
        return reverseHead;
    }
};
// https://leetcode.cn/submissions/detail/368439742/
```

## 26. 删除有序数组中的重复项

<https://leetcode.cn/problems/remove-duplicates-from-sorted-array/>

```cpp
class Solution {
public:
    int removeDuplicates(vector<int> &nums) {
        // [0..i-1] 不重复元素区间
        // [i..j-1] 重复元素区间
        // [j..n-1] 遍历区间
        size_t n = nums.size();
        int i = 0, j = 0;
        while (j < n) {
            while (j + 1 < n && nums[j] == nums[j + 1]) {
                ++j;
            }
            swap(nums[i++], nums[j++]);
        }
        return i;
    }
};
// https://leetcode.cn/submissions/detail/391449758/
```

## 27. 移除元素

<https://leetcode.cn/problems/remove-element/>

```cpp
class Solution {
public:
    int removeElement(vector<int> &nums, int val) {
        // nums[0..i-1]   != val
        // nums[i..j]     Scanning
        // nums[j+1..n-1] == val
        int i = 0, j = nums.size() - 1;
        while (i <= j) {
            while (i <= j && nums[i] != val) {
                ++i;
            }
            while (i <= j && nums[j] == val) {
                --j;
            }
            if (i <= j) {
                swap(nums[i++], nums[j--]);
            }
        }
        return i;
    }
};
// https://leetcode.cn/submissions/detail/391448733/
```

```cpp
class Solution {
public:
    int removeElement(vector<int> &nums, int val) {
        // nums[0..i-1] != val
        // nums[i..j-1] == val
        // nums[j..n-1] Scanning
        int i = 0, j = 0;
        while (j < nums.size()) {
            if (nums[j] == val) {
                ++j;
            } else {
                swap(nums[i++], nums[j++]);
            }
        }
        return i;
    }
};
// https://leetcode.cn/submissions/detail/391449244/
```

## 28. 实现 strStr()

<https://leetcode.cn/problems/implement-strstr/>

```cpp
class KMP {
public:
    explicit KMP(const string &pat) {
        m = pat.size();
        dfa = vector<vector<int >>(R, vector<int>(m));
        dfa[pat[0]][0] = 1;
        for (int x = 0, j = 1; j < m; ++j) {
            for (int c = 0; c < R; ++c) {
                dfa[c][j] = dfa[c][x];
            }
            dfa[pat[j]][j] = j + 1;
            x = dfa[pat[j]][x];
        }
    }

    int search(string txt) {
        int i, j;
        for (i = 0, j = 0; i < txt.size() && j < m; ++i) {
            j = dfa[txt[i]][j];
        }
        if (j == m) {
            return i - m;
        }
        return -1;
    }

private:
    int m;
    static const int R = 256;
    vector<vector<int>> dfa;
};

class Solution {
public:
    int strStr(const string &haystack, const string &needle) {
        KMP kmp{needle};
        return kmp.search(haystack);
    }
};
// https://leetcode.cn/submissions/detail/391712382/
```

## 33. 搜索旋转排序数组

<https://leetcode.cn/problems/search-in-rotated-sorted-array/>

```cpp
class Solution {
public:
    int search(vector<int> &nums, int target) {
        int lo = 0, hi = nums.size() - 1;
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
};
// https://leetcode.cn/submissions/detail/367100336/
```

```cpp
class Solution {
public:
    int search(vector<int> &nums, int target) {
        int lo = 0, hi = nums.size() - 1;
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
};
// https://leetcode.cn/submissions/detail/367100665/
```

```cpp
class Solution {
public:
    int search(vector<int> &nums, int target) {
        int lo = 0, hi = nums.size() - 1;
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
            if (nums[mid] == target) {
                return mid;
            }
            if (nums[lo] <= nums[mid]) {
                if (nums[lo] <= target && target < nums[mid]) {
                    return binarySearch(nums, lo, mid, target);
                } else {
                    lo = mid + 1;
                }
            } else {
                if (nums[mid] < target && target <= nums[hi]) {
                    return binarySearch(nums, mid, hi, target);
                } else {
                    hi = mid - 1;
                }
            }
        }
        return -1;
    }

private:
    int binarySearch(const vector<int> &nums, int lo, int hi, int target) {
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
};
// https://leetcode.cn/submissions/detail/376145980/
```

```cpp
class Solution {
public:
    int search(vector<int> &nums, int target) {
        int min = findMin(nums);
        int ans = binarySearch(nums, 0, min - 1, target);
        if (ans == -1) {
            ans = binarySearch(nums, min, nums.size() - 1, target);
        }
        return ans;
    }

private:
    // 寻找旋转排序数组中的最小值的索引
    int findMin(const vector<int> &nums) {
        int lo = 0, hi = nums.size() - 1;
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

    int binarySearch(const vector<int> &nums, int lo, int hi, int target) {
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
};
// https://leetcode.cn/submissions/detail/376147711/
```

## 34. 在排序数组中查找元素的第一个和最后一个位置

<https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/>

```cpp
class Solution {
public:
    vector<int> searchRange(vector<int> &nums, int target) {
        return {binarySearch(nums, target, true), binarySearch(nums, target, false)};
    }

private:
    int binarySearch(const vector<int> &nums, int target, bool lower) {
        int res = -1;
        int lo = 0, hi = nums.size() - 1;
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
};
// https://leetcode.cn/submissions/detail/361626206/
```

## 37. 解数独

<https://leetcode.cn/problems/sudoku-solver/>

```cpp
class Solution {
public:
    void solveSudoku(vector<vector<char>> &board) {
        backtrack(board, 0, -1);
    }

private:
    // 遍历『决策森林』
    // tree  = row
    // level = (row, col)
    bool backtrack(vector<vector<char>> &board, int row, int col) {
        size_t n = board.size();
        bool res = false;
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
    bool isValid(const vector<vector<char>> &board, int row, int col, char ch) {
        size_t n = board.size();
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
};
// https://leetcode.cn/submissions/detail/391487129/
```

```cpp
class Solution {
public:
    void solveSudoku(vector<vector<char>> &board) {
        dfs(board, 0, -1, '#');
    }

private:
    // 遍历『决策森林』
    // tree  = row
    // level = (row, col)
    bool dfs(vector<vector<char>> &board, int row, int col, char ch) {
        if (col >= 0 && ch != '#') {
            board[row][col] = ch;
        }
        size_t n = board.size();
        bool res = false;
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
    bool isValid(const vector<vector<char>> &board, int row, int col, char ch) {
        size_t n = board.size();
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
};
// https://leetcode.cn/submissions/detail/391487374/
```

## 39. 组合总和

<https://leetcode.cn/problems/combination-sum/>

```cpp
class Solution {
public:
    vector<vector<int>> combinationSum(vector<int> &candidates, int target) {
        backtrack(candidates, target, -1);
        return ans;
    }

private:
    // edge = 取数组 nums 的索引为值
    void backtrack(vector<int> &candidates, int target, int edge) {
        if (pathSum == target) {
            ans.push_back(path);
            return;
        }
        if (edge == -1) {
            edge = 0;
        }
        // 避免重复，从 edge 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (edge < candidates.size()) {
            int x = candidates[edge];
            if (pathSum + x <= target) {
                pathSum += x;
                path.push_back(x);
                backtrack(candidates, target, edge);
                pathSum -= x;
                path.pop_back();
            }
            ++edge;
        }
    }


    int pathSum = 0;
    vector<int> path; // 取 nums[edge] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391611129/
```

```cpp
class Solution {
public:
    vector<vector<int>> combinationSum(vector<int> &candidates, int target) {
        dfs(candidates, target, -1);
        return ans;
    }

private:
    // vertex = 取数组 nums 的索引为值
    void dfs(vector<int> &candidates, int target, int vertex) {
        int x = (vertex == -1 ? 0 : candidates[vertex]);
        if (vertex >= 0) {
            pathSum += x;
            path.push_back(x);
        }
        if (pathSum == target) {
            ans.push_back(path);
        } else {
            // 避免重复，从 vertex 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            int v = (vertex == -1 ? 0 : vertex);
            while (v < candidates.size()) {
                if (pathSum + candidates[v] <= target) {
                    dfs(candidates, target, v);
                }
                ++v;
            }
        }
        if (vertex >= 0) {
            pathSum -= x;
            path.pop_back();
        }
    }

    int pathSum = 0;
    vector<int> path; // 取 nums[vertex] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391611523/
```

```cpp
class Solution {
public:
    vector<vector<int>> combinationSum(vector<int> &candidates, int target) {
        return combinationSum(candidates, candidates.size() - 1, target);
    }

private:
    // 子数组 candidates[0..i] 和为 target 的不同组合
    vector<vector<int>> combinationSum(const vector<int> &candidates, int i, int target) {
        if (i < 0 || target <= 0) {
            return {};
        }
        // memo[i][target]
        string key = to_string(i) + "," + to_string(target);
        if (memo.count(key) == 0) {
            int x = candidates[i];
            vector<vector<int>> sp1 = combinationSum(candidates, i - 1, target); // 不包含 x
            vector<vector<int>> sp2 = combinationSum(candidates, i, target - x); // 包含 x
            vector<vector<int>> res;
            for (const auto &v: sp1) {
                res.push_back(v);
            }
            for (auto &v: sp2) {
                v.push_back(x);
                res.push_back(v);
            }
            if (target == x) {
                res.push_back({x});
            }
            memo[key] = res;
        }
        return memo[key];
    }

    unordered_map<string, vector<vector<int>>> memo;
};
// https://leetcode.cn/submissions/detail/391611871/
```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```cpp
class Solution {
public:
    vector<vector<int>> combinationSum2(vector<int> &candidates, int target) {
        sort(candidates.begin(), candidates.end());
        backtrack(candidates, target, -1);
        return ans;
    }

private:
    // edge = 取数组 nums 的索引为值
    void backtrack(vector<int> &candidates, int target, int edge) {
        if (pathSum == target) {
            ans.push_back(path);
            return;
        }
        int prev = INT_MIN;
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge < candidates.size()) {
            int x = candidates[edge];
            if (x != prev && pathSum + x <= target) {
                prev = x;
                pathSum += x;
                path.push_back(x);
                backtrack(candidates, target, edge);
                pathSum -= x;
                path.pop_back();
            }
        }
    }

    int pathSum = 0;
    vector<int> path; // 取 nums[edge] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391645813/
```

```cpp
class Solution {
public:
    vector<vector<int>> combinationSum2(vector<int> &candidates, int target) {
        sort(candidates.begin(), candidates.end());
        dfs(candidates, target, -1);
        return ans;
    }

private:
    // vertex = 取数组 nums 的索引为值
    void dfs(vector<int> &candidates, int target, int vertex) {
        int x = (vertex == -1 ? 0 : candidates[vertex]);
        if (vertex >= 0) {
            pathSum += x;
            path.push_back(x);
        }
        if (pathSum == target) {
            ans.push_back(path);
        } else {
            int prev = INT_MIN;
            // 避免重复，从 vertex + 1 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            int v = vertex;
            while (++v < candidates.size()) {
                int y = candidates[v];
                if (y != prev && pathSum + y <= target) {
                    prev = y;
                    dfs(candidates, target, v);
                }
            }
        }
        if (vertex >= 0) {
            pathSum -= x;
            path.pop_back();
        }
    }

    int pathSum = 0;
    vector<int> path; // 取 nums[vertex] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391646248/
```

## 42. 接雨水

<https://leetcode.cn/problems/trapping-rain-water/>

```cpp
class Solution {
public:
    int trap(vector<int> &height) {
        int n = height.size();
        // leftMax[i] = max(height[0..i])
        vector<int> leftMax(height);
        for (int i = 1; i <= n - 1; ++i) {
            leftMax[i] = max(height[i], leftMax[i - 1]);
        }
        // rightMax[i] = max(height[i..n-1])
        vector<int> rightMax(height);
        for (int i = n - 2; i >= 0; --i) {
            rightMax[i] = max(height[i], rightMax[i + 1]);
        }
        int sum = 0;
        for (int i = 0; i < n; ++i) {
            sum += min(leftMax[i], rightMax[i]) - height[i];
        }
        return sum;
    }
};
// https://leetcode.cn/submissions/detail/391524644/
```

```cpp
class Solution {
public:
    int trap(vector<int> &height) {
        int sum = 0;
        // [0..i-1]   Computed
        // [i..j]     Scanning
        // [j+1..n-1] Computed
        int i = 0, j = height.size() - 1;
        // leftMax = max(height[0..i])
        int leftMax = INT_MIN;
        // rightMax = max(height[j..n-1])
        int rightMax = INT_MIN;
        // When i = j, height[i] = height[j] = max(height[0..n-1])
        // height[i] = max(height[0..i]) = leftMax = rightMax = max(height[j..n-1]) = height[j]
        while (i <= j) {
            leftMax = max(leftMax, height[i]);
            rightMax = max(rightMax, height[j]);
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
};
// https://leetcode.cn/submissions/detail/391525299/
```

## 46. 全排列

<https://leetcode.cn/problems/permutations/>

```cpp
class Solution {
public:
    vector<vector<int>> permute(vector<int> &nums) {
        marked = vector<bool>(nums.size());
        backtrack(nums);
        return ans;
    }

private:
    void backtrack(vector<int> &nums) {
        size_t n = nums.size();
        if (path.size() == n) {
            ans.push_back(path);
            return;
        }
        // edge = 取数组 nums 的索引为值
        for (int edge = 0; edge < n; ++edge) {
            if (!marked[edge]) {
                marked[edge] = true;
                path.push_back(nums[edge]);
                backtrack(nums);
                marked[edge] = false;
                path.pop_back();
            }
        }
    }

    vector<bool> marked;
    vector<int> path; // 取 nums[edge] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391646741/
```

```cpp
class Solution {
public:
    vector<vector<int>> permute(vector<int> &nums) {
        marked = vector<bool>(nums.size());
        dfs(nums, -1);
        return ans;
    }

private:
    // vertex = 取数组 nums 的索引为值
    void dfs(vector<int> &nums, int vertex) {
        if (vertex >= 0) {
            marked[vertex] = true;
            path.push_back(nums[vertex]);
        }
        size_t n = nums.size();
        if (path.size() == n) {
            ans.push_back(path);
        } else {
            for (int v = 0; v < n; ++v) {
                if (!marked[v]) {
                    dfs(nums, v);
                }
            }
        }
        if (vertex >= 0) {
            marked[vertex] = false;
            path.pop_back();
        }
    }

    vector<bool> marked;
    vector<int> path; // 取 nums[vertex] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391647039/
```

## 47. 全排列 II

<https://leetcode.cn/problems/permutations-ii/>

```cpp
class Solution {
public:
    vector<vector<int>> permuteUnique(vector<int> &nums) {
        marked = vector<bool>(nums.size());
        sort(nums.begin(), nums.end());
        backtrack(nums);
        return ans;
    }

private:
    void backtrack(vector<int> &nums) {
        size_t n = nums.size();
        if (path.size() == n) {
            ans.push_back(path);
            return;
        }
        int prev = INT_MIN;
        // edge = 取数组 nums 的索引为值
        for (int edge = 0; edge < n; ++edge) {
            int x = nums[edge];
            if (!marked[edge] && x != prev) {
                prev = x;
                marked[edge] = true;
                path.push_back(x);
                backtrack(nums);
                marked[edge] = false;
                path.pop_back();
            }
        }
    }

    vector<bool> marked;
    vector<int> path; // 取 nums[edge] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391647483/
```

```cpp
class Solution {
public:
    vector<vector<int>> permuteUnique(vector<int> &nums) {
        marked = vector<bool>(nums.size());
        sort(nums.begin(), nums.end());
        dfs(nums, -1);
        return ans;
    }

private:
    // vertex = 取数组 nums 的索引为值
    void dfs(vector<int> &nums, int vertex) {
        if (vertex >= 0) {
            marked[vertex] = true;
            path.push_back(nums[vertex]);
        }
        size_t n = nums.size();
        if (path.size() == n) {
            ans.push_back(path);
        } else {
            int prev = INT_MIN;
            for (int v = 0; v < n; ++v) {
                int x = nums[v];
                if (!marked[v] && x != prev) {
                    prev = x;
                    dfs(nums, v);
                }
            }
        }
        if (vertex >= 0) {
            marked[vertex] = false;
            path.pop_back();
        }
    }

    vector<bool> marked;
    vector<int> path; // 取 nums[vertex] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391647867/
```

## 51. N 皇后

<https://leetcode.cn/problems/n-queens/>

```cpp
class Solution {
public:
    vector<vector<string>> solveNQueens(int n) {
        vector<string> board(n, string(n, '.'));
        backtrack(board, -1);
        return ans;
    }

private:
    // level = row
    void backtrack(vector<string> &board, int row) {
        size_t n = board.size();
        if (row == n - 1) {
            ans.push_back(board);
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
    bool isValid(const vector<string> &board, int row, int col) {
        size_t n = board.size();
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

    vector<vector<string>> ans;
};
// https://leetcode.cn/submissions/detail/391683202/
```

```cpp
class Solution {
public:
    vector<vector<string>> solveNQueens(int n) {
        vector<string> board(n, string(n, '.'));
        dfs(board, -1, -1);
        return ans;
    }

private:
    // level  = row
    // vertex = col
    void dfs(vector<string> &board, int row, int col) {
        if (row >= 0) {
            board[row][col] = 'Q';
        }
        size_t n = board.size();
        if (row == n - 1) {
            ans.push_back(board);
        } else {
            for (int c = 0; c < n; ++c) {
                if (isValid(board, row + 1, c)) {
                    dfs(board, row + 1, c);
                }
            }
        }
        if (row >= 0) {
            board[row][col] = '.';
        }
    }

    // board[row][col] 放置 Q 是否有效
    bool isValid(const vector<string> &board, int row, int col) {
        size_t n = board.size();
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

    vector<vector<string>> ans;
};
// https://leetcode.cn/submissions/detail/391683597/
```

```cpp
class Solution {
public:
    vector<vector<string>> solveNQueens(int n) {
        vector<string> board(n, string(n, '.'));
        backtrack(board, 0, -1);
        return ans;
    }

private:
    // 遍历『决策森林』
    // tree  = row
    // level = (row, col)
    void backtrack(vector<string> &board, int row, int col) {
        size_t n = board.size();
        if (row == n) {
            ans.push_back(board);
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
    bool isValid(const vector<string> &board, int row, int col) {
        size_t n = board.size();
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

    vector<vector<string>> ans;
};
// https://leetcode.cn/submissions/detail/391683426/
```

```cpp
class Solution {
public:
    vector<vector<string>> solveNQueens(int n) {
        vector<string> board(n, string(n, '.'));
        dfs(board, 0, -1, '-');
        return ans;
    }

private:
    // 遍历『决策森林』
    // tree   = row
    // level  = (row, col)
    // vertex = 'Q', '.'
    void dfs(vector<string> &board, int row, int col, char ch) {
        if (col >= 0) {
            board[row][col] = ch;
        }
        size_t n = board.size();
        if (row == n) {
            ans.push_back(board);
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
    bool isValid(const vector<string> &board, int row, int col) {
        size_t n = board.size();
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

    vector<vector<string>> ans;
};
// https://leetcode.cn/submissions/detail/391683761/
```

## 52. N 皇后 II

<https://leetcode.cn/problems/n-queens-ii/>

```cpp
class Solution {
public:
    int totalNQueens(int n) {
        vector<string> board(n, string(n, '.'));
        backtrack(board, -1);
        return ans;
    }

private:
    // path  = 棋盘的放置方案 board
    // level = 棋盘的行 row
    void backtrack(vector<string> &board, int row) {
        size_t n = board.size();
        if (row == n - 1) {
            ++ans;
            return;
        }
        // edge = 棋盘的列 col
        for (int col = 0; col < n; ++col) {
            if (isValid(board, row + 1, col)) {
                board[row + 1][col] = 'Q';
                backtrack(board, row + 1);
                board[row + 1][col] = '.';
            }
        }
    }

    // 在 board[row][col] 放置 Q 是否合法
    bool isValid(const vector<string> &board, int row, int col) {
        size_t n = board.size();
        // 检查同一列
        for (int r = row - 1; r >= 0; --r) {
            if (board[r][col] == 'Q') {
                return false;
            }
        }
        // 检查右斜线
        for (int r = row - 1, c = col + 1; r >= 0 && c <= n - 1; --r, ++c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        // 检查左斜线
        for (int r = row - 1, c = col - 1; r >= 0 && c >= 0; --r, --c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        return true;
    }

    int ans;
};
// https://leetcode.cn/submissions/detail/391550847/
```

```cpp
class Solution {
public:
    int totalNQueens(int n) {
        vector<string> board(n, string(n, '.'));
        dfs(board, -1, -1);
        return ans;
    }

private:
    // path   = 棋盘的放置方案 board
    // level  = 棋盘的行 row
    // vertex = 棋盘的列 col
    void dfs(vector<string> &board, int row, int col) {
        if (row >= 0) {
            board[row][col] = 'Q';
        }
        size_t n = board.size();
        if (row == n - 1) {
            ++ans;
        } else {
            for (int c = 0; c < n; ++c) {
                if (isValid(board, row + 1, c)) {
                    dfs(board, row + 1, c);
                }
            }
        }
        if (row >= 0) {
            board[row][col] = '.';
        }
    }

    // 返回在 board[row][col] 放置 Q 是否合法
    bool isValid(const vector<string> &board, int row, int col) {
        size_t n = board.size();
        // 检查同一列
        for (int r = row - 1; r >= 0; --r) {
            if (board[r][col] == 'Q') {
                return false;
            }
        }
        // 检查右斜线
        for (int r = row - 1, c = col + 1; r >= 0 && c <= n - 1; --r, ++c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        // 检查左斜线
        for (int r = row - 1, c = col - 1; r >= 0 && c >= 0; --r, --c) {
            if (board[r][c] == 'Q') {
                return false;
            }
        }
        return true;
    }

    int ans;
};
// https://leetcode.cn/submissions/detail/391551222/
```

## 53. 最大子数组和

<https://leetcode.cn/problems/maximum-subarray/>

```cpp
class Solution {
public:
    int maxSubArray(vector<int> &nums) {
        // dp[i] = max({sum(subarray) | subarray 是以 nums[i] 结尾的子数组})
        vector<int> dp(nums);
        int ans = dp[0];
        for (int i = 1; i < nums.size(); ++i) {
            dp[i] = max(nums[i], nums[i] + dp[i - 1]);
            ans = max(ans, dp[i]);
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391534620/
```

```cpp
class Solution {
public:
    int maxSubArray(vector<int> &nums) {
        size_t n = nums.size();
        memo = vector<int>(n, INT_MIN);
        int ans = INT_MIN;
        for (int i = 0; i < n; ++i) {
            ans = max(ans, maxSubArray(nums, i));
        }
        return ans;
    }

private:
    // max({sum(subarray) | subarray 是以 nums[i] 结尾的子数组})
    int maxSubArray(const vector<int> &nums, int i) {
        if (i < 0) {
            return 0;
        }
        if (memo[i] == INT_MIN) {
            memo[i] = max(nums[i], maxSubArray(nums, i - 1) + nums[i]);
        }
        return memo[i];
    }

    vector<int> memo;
};
// https://leetcode.cn/submissions/detail/391535137/
```

## 56. 合并区间

<https://leetcode.cn/problems/merge-intervals/>

```cpp

```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```cpp

```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```cpp

```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```cpp

```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```cpp

```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```cpp

```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```cpp

```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```cpp

```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```cpp

```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```cpp

```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```cpp

```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```cpp

```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```cpp

```

## 92. 反转链表 II

<https://leetcode-cn.com/problems/reverse-linked-list-ii/>

```cpp

```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```cpp

```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```cpp

```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```cpp

```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```cpp

```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```cpp

```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```cpp

```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```cpp

```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```cpp

```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```cpp

```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```cpp

```

## 107. 二叉树的层序遍历 II

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```cpp

```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```cpp

```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```cpp

```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```cpp

```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```cpp

```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```cpp

```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```cpp

```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```cpp

```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```cpp

```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```cpp

```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```cpp

```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```cpp

```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```cpp

```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```cpp

```

## 141. 环形链表

<https://leetcode-cn.com/problems/linked-list-cycle/>

```cpp

```

## 142. 环形链表 II

<https://leetcode-cn.com/problems/linked-list-cycle-ii/>

```cpp

```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```cpp

```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```cpp

```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```cpp

```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```cpp

```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```cpp

```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```cpp

```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```cpp

```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```cpp

```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```cpp

```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```cpp

```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```cpp

```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```cpp

```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```cpp

```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```cpp

```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```cpp

```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```cpp

```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```cpp

```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```cpp

```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```cpp

```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```cpp

```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```cpp

```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```cpp

```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```cpp

```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```cpp

```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```cpp

```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```cpp

```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```cpp

```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```cpp

```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```cpp

```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```cpp

```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```cpp

```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```cpp

```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```cpp

```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```cpp

```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```cpp

```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```cpp

```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```cpp

```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```cpp

```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```cpp

```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```cpp

```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```cpp

```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```cpp

```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```cpp

```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```cpp

```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```cpp

```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```cpp

```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```cpp

```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```cpp

```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```cpp

```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```cpp

```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```cpp

```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```cpp

```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```cpp

```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```cpp

```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```cpp

```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```cpp

```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```cpp

```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```cpp

```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```cpp

```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```cpp

```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```cpp

```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```cpp

```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```cpp

```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```cpp

```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```cpp

```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```cpp

```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```cpp

```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```cpp

```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```cpp

```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```cpp

```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```cpp

```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```cpp

```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```cpp

```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```cpp

```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```cpp

```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```cpp

```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```cpp

```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```cpp

```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```cpp

```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```cpp

```

## 876. 链表的中间结点

<https://leetcode-cn.com/problems/middle-of-the-linked-list/>

```cpp

```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```cpp

```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```cpp

```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```cpp

```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```cpp

```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```cpp

```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```cpp

```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```cpp

```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```cpp

```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```cpp

```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```cpp

```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```cpp

```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```cpp

```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```cpp

```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```cpp

```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```cpp

```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```cpp

```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```cpp

```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```cpp

```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```cpp

```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```cpp

```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```cpp

```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode-cn.com/problems/kth-node-from-end-of-list-lcci/>

```cpp

```
