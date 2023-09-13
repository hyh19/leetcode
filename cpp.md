<!-- omit in toc -->
# LeetCode 题解：C++ 实现

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

```cpp
class Solution {
public:
    vector<int> twoSum(const vector<int> &nums, int target) {
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
// https://leetcode.cn/submissions/detail/392320997/
```

## 2. 两数相加

<https://leetcode.cn/problems/add-two-numbers/>

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

<https://leetcode.cn/problems/longest-substring-without-repeating-characters/>

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
                while (left < right) {
                    char del = s[left++];
                    window.erase(del);
                    if (del == add) {
                        break;
                    }
                }
            }
            ans = max(ans, right - left);
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/392737787/
```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```cpp
class Solution {
public:
    double findMedianSortedArrays(const vector<int> &nums1, const vector<int> &nums2) {
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
// https://leetcode.cn/submissions/detail/393252886/
```

```cpp
class Solution {
public:
    double findMedianSortedArrays(const vector<int> &nums1, const vector<int> &nums2) {
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
        int n1 = nums1.size(), n2 = nums2.size();
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
            return getKthElement(nums1, i + 1, nums2, start2, k - (i - start1 + 1));
        } else {
            // 排除 nums2[start2..j] 共 j-start2+1 个元素
            return getKthElement(nums1, start1, nums2, j + 1, k - (j - start2 + 1));
        }
    }
};
// https://leetcode.cn/submissions/detail/393258693/
```

## 5. 最长回文子串

<https://leetcode.cn/problems/longest-palindromic-substring/>

```cpp
class Solution {
public:
    string longestPalindrome(const string &s) {
        string ans;
        for (int i = 0; i < s.size(); ++i) {
            string s1 = longestPalindrome(s, i, i);
            if (s1.size() > ans.size()) {
                ans = s1;
            }
            string s2 = longestPalindrome(s, i, i + 1);
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
// https://leetcode.cn/submissions/detail/394194306/
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
    int maxArea(const vector<int> &height) {
        int ans = 0;
        int i = 0, j = height.size() - 1;
        while (i < j) {
            int area = (j - i) * min(height[i], height[j]);
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
// https://leetcode.cn/submissions/detail/395984630/
```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```cpp
class Solution {
public:
    string longestCommonPrefix(const vector<string> &strs) {
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
// https://leetcode.cn/submissions/detail/398710143/
```

```cpp
class Solution {
public:
    string longestCommonPrefix(const vector<string> &strs) {
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
// https://leetcode.cn/submissions/detail/398710916/
```

## 15. 三数之和

<https://leetcode.cn/problems/3sum/>

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

<https://leetcode.cn/problems/remove-nth-node-from-end-of-list/>

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
        while (fast->next != nullptr) {
            slow = slow->next;
            fast = fast->next;
        }
        ListNode *delNode = slow->next;
        if (delNode == head) { // 删除的是头结点
            head = head->next;
        } else {
            slow->next = delNode->next;
        }
        delete delNode;
        delete dummyHead;
        return head;
    }
};
// https://leetcode.cn/submissions/detail/399270541/
```

## 20. 有效的括号

<https://leetcode.cn/problems/valid-parentheses/>

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

<https://leetcode.cn/problems/merge-two-sorted-lists/>

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

<https://leetcode.cn/problems/merge-k-sorted-lists/>

```cpp
class Solution {
public:
    ListNode *mergeKLists(vector<ListNode *> &lists) {
        return mergeKLists(lists, 0, lists.size() - 1);
    }

private:
    ListNode *mergeKLists(vector<ListNode *> &lists, int lo, int hi) {
        if (lo > hi) {
            return nullptr;
        }
        if (lo == hi) {
            return lists[lo];
        }
        int mid = lo + (hi - lo) / 2;
        ListNode *left = mergeKLists(lists, lo, mid);
        ListNode *right = mergeKLists(lists, mid + 1, hi);
        return mergeTwoLists(left, right);
    }

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
// https://leetcode.cn/submissions/detail/391583443/
```

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

## 24. 两两交换链表中的节点

<https://leetcode.cn/problems/swap-nodes-in-pairs/>

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
    vector<int> searchRange(const vector<int> &nums, int target) {
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
// https://leetcode.cn/submissions/detail/429780068/
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
class Solution {
public:
    vector<vector<int>> merge(vector<vector<int>> &intervals) {
        sort(intervals.begin(), intervals.end(),
             [](const vector<int> &a, const vector<int> &b) {
                 if (a[0] == b[0]) {
                     return a[1] > b[1];
                 }
                 return a[0] < b[0];
             });
        int mStart = intervals[0][0];
        int mEnd = intervals[0][1];
        vector<vector<int>> ans;
        for (int i = 1; i < intervals.size(); ++i) {
            int start = intervals[i][0];
            int end = intervals[i][1];
            if (start <= mEnd) { // 重叠
                mEnd = max(mEnd, end);
            } else { // 不重叠
                ans.push_back({mStart, mEnd});
                mStart = start;
                mEnd = end;
            }
        }
        ans.push_back({mStart, mEnd});
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391666589/
```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```cpp
class Solution {
public:
    int minPathSum(vector<vector<int>> &grid) {
        int m = grid.size(), n = grid[0].size();
        memo = vector<vector<int>>(m, vector<int>(n, -1));
        return minPathSum(grid, m - 1, n - 1);
    }

private:
    // 从 grid[0][0] 到 grid[row][col] 的最小路径和
    int minPathSum(const vector<vector<int>> &grid, int row, int col) {
        if (row < 0 || col < 0) {
            return INT_MAX;
        }
        if (row == 0 && col == 0) {
            return grid[row][col];
        }
        if (memo[row][col] == -1) {
            int sp1 = minPathSum(grid, row - 1, col);
            int sp2 = minPathSum(grid, row, col - 1);
            memo[row][col] = min(sp1, sp2) + grid[row][col];
        }
        return memo[row][col];
    }

    vector<vector<int>> memo;
};
// https://leetcode.cn/submissions/detail/391536250/
```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```cpp
class Solution {
public:
    int mySqrt(int x) {
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
};
// https://leetcode.cn/submissions/detail/366031058/
```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```cpp
class Solution {
public:
    int climbStairs(int n) {
        if (n == 1) {
            return 1;
        }
        if (n == 2) {
            return 2;
        }
        // dp[i] = 楼梯有 i 阶时，有几种不同的方法
        vector<int> dp(n + 1);
        dp[1] = 1;
        dp[2] = 2;
        for (int i = 3; i <= n; i++) {
            dp[i] = dp[i - 1] + dp[i - 2];
        }
        return dp[n];
    }
};
// https://leetcode.cn/submissions/detail/360166413/
```

```cpp
class Solution {
public:
    int climbStairs(int n) {
        if (n == 1) {
            return 1;
        }
        if (n == 2) {
            return 2;
        }
        if (memo.count(n) == 0) {
            memo[n] = climbStairs(n - 1) + climbStairs(n - 2);
        }
        return memo[n];
    }

private:
    unordered_map<int, int> memo;
};
// https://leetcode.cn/submissions/detail/375080651/
```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```cpp
class Solution {
public:
    int minDistance(const string &word1, const string &word2) {
        int n1 = word1.size(), n2 = word2.size();
        memo = vector<vector<int >>(n1, vector<int>(n2, -1));
        return minDistance(word1, n1 - 1, word2, n2 - 1);
    }

private:
    // 子串 s1[0..i] s2[0..j] 的最小编辑距离
    int minDistance(const string &s1, int i, const string &s2, int j) {
        if (i < 0) {
            // 插入 s2[0..j] 到 s1
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
        if (memo[i][j] == -1) {
            if (s1[i] == s2[j]) {
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
                memo[i][j] = min(min(sp1, sp2), sp3);
            }
        }
        return memo[i][j];
    }

    vector<vector<int>> memo;
};
// https://leetcode.cn/submissions/detail/391609426/
```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```cpp
class Solution {
public:
    void sortColors(vector<int> &nums) {
        int v = 1;
        int i = 0, lt = 0, gt = nums.size() - 1;
        while (i <= gt) {
            int x = nums[i];
            if (x < v) {
                swap(nums[lt++], nums[i++]);
            } else if (x > v) {
                swap(nums[i], nums[gt--]);
            } else {
                ++i;
            }
        }
    }
};
// https://leetcode.cn/submissions/detail/391461308/
```

```cpp
class Solution {
public:
    void sortColors(vector<int> &nums) {
        vector<int> count(R + 1);
        vector<int> aux(nums);
        for (const auto &x: nums) {
            ++count[x + 1];
        }
        for (int r = 0; r < R; ++r) {
            count[r + 1] += count[r];
        }
        for (const auto &x: nums) {
            aux[count[x]++] = x;
        }
        nums.assign(aux.begin(), aux.end());
    }

private:
    static const int R = 3;
};
// https://leetcode.cn/submissions/detail/391463767/
```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```cpp
class Solution {
public:
    string minWindow(string s, string t) {
        unordered_map<char, int> need, window;
        for (const auto &c: t) {
            ++need[c];
        }
        int valid = 0;
        int start = 0, len = INT_MAX;
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        int left = 0, right = 0;
        while (right < s.size()) {
            char add = s[right++];
            if (need.count(add) == 1) {
                if (++window[add] == need[add]) {
                    ++valid;
                }
            }
            if (valid == need.size()) {
                while (left <= right) {
                    char del = s[left];
                    if (need.count(del) == 1 && window[del] == need[del]) {
                        break;
                    } else {
                        if (need.count(del) == 1) {
                            --window[del];
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
        return len == INT_MAX ? "" : s.substr(start, len);
    }
};
// https://leetcode.cn/submissions/detail/391685140/
```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```cpp
class Solution {
public:
    vector<vector<int>> combine(int n, int k) {
        backtrack(n, k, 0);
        return ans;
    }

private:
    // edge = 取 [1..n] 为值
    void backtrack(int n, int k, int edge) {
        if (path.size() == k) {
            ans.push_back(path);
            return;
        }
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge <= n) {
            path.push_back(edge);
            backtrack(n, k, edge);
            path.pop_back();
        }
    }

    vector<int> path; // 取 [1..n] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391644862/
```

```cpp
class Solution {
public:
    vector<vector<int>> combine(int n, int k) {
        dfs(n, k, 0);
        return ans;
    }

private:
    // vertex = 取 [1..n] 为值
    void dfs(int n, int k, int vertex) {
        if (vertex > 0) {
            path.push_back(vertex);
        }
        if (path.size() == k) {
            ans.push_back(path);
        } else {
            // 避免重复，从 vertex + 1 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            int v = vertex;
            while (++v <= n) {
                dfs(n, k, v);
            }
        }
        if (vertex > 0) {
            path.pop_back();
        }
    }

    vector<int> path; // 取 [1..n] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391645252/
```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```cpp
class Solution {
public:
    vector<vector<int>> subsets(vector<int> &nums) {
        backtrack(nums, -1);
        return ans;
    }

private:
    // edge = 取数组 nums 的索引为值
    void backtrack(vector<int> &nums, int edge) {
        ans.push_back(path);
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge < nums.size()) {
            path.push_back(nums[edge]);
            backtrack(nums, edge);
            path.pop_back();
        }
    }

    vector<int> path; // 取 nums[edge] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391612275/
```

```cpp
class Solution {
public:
    vector<vector<int>> subsets(vector<int> &nums) {
        dfs(nums, -1);
        return ans;
    }

private:
    // vertex = 取数组 nums 的索引为值
    void dfs(vector<int> &nums, int vertex) {
        if (vertex >= 0) {
            path.push_back(nums[vertex]);
        }
        ans.push_back(path);
        // 避免重复，从 vertex + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        int v = vertex;
        while (++v < nums.size()) {
            dfs(nums, v);
        }
        if (vertex >= 0) {
            path.pop_back();
        }
    }

    vector<int> path; // 取 nums[vertex] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391612536/
```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```cpp
class Solution {
public:
    bool search(vector<int> &nums, int target) {
        int lo = 0, hi = nums.size() - 1;
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
};
// https://leetcode.cn/submissions/detail/357592092/
```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```cpp
class Solution {
public:
    ListNode *deleteDuplicates(ListNode *head) {
        ListNode *ptr = head;
        while (ptr != nullptr && ptr->next != nullptr) {
            if (ptr->val == ptr->next->val) {
                ListNode *x = ptr->next;
                ptr->next = ptr->next->next;
                delete x;
            } else {
                ptr = ptr->next;
            }
        }
        return head;
    }
};
// https://leetcode.cn/submissions/detail/391472481/
```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```cpp
class Solution {
public:
    ListNode *partition(ListNode *head, int x) {
        auto *lessDummyHead = new ListNode();
        ListNode *lessPtr = lessDummyHead;
        auto *greaterDummyHead = new ListNode();
        ListNode *greaterPtr = greaterDummyHead;
        while (head != nullptr) {
            if (head->val < x) {
                lessPtr->next = head;
                lessPtr = lessPtr->next;
            } else {
                greaterPtr->next = head;
                greaterPtr = greaterPtr->next;
            }
            head = head->next;
        }
        greaterPtr->next = nullptr;
        lessPtr->next = greaterDummyHead->next;
        head = lessDummyHead->next;
        delete lessDummyHead;
        delete greaterDummyHead;
        return head;
    }
};
// https://leetcode.cn/submissions/detail/391532150/
```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```cpp
class Solution {
public:
    vector<vector<int>> subsetsWithDup(vector<int> &nums) {
        sort(nums.begin(), nums.end());
        backtrack(nums, -1);
        return ans;
    }

private:
    // edge = 取数组 nums 的索引为值
    void backtrack(vector<int> &nums, int edge) {
        ans.push_back(path);
        int prev = INT_MIN;
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge < nums.size()) {
            int x = nums[edge];
            if (x != prev) {
                prev = x;
                path.push_back(x);
                backtrack(nums, edge);
                path.pop_back();
            }
        }
    }

    vector<int> path; // 取 nums[edge] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391612849/
```

```cpp
class Solution {
public:
    vector<vector<int>> subsetsWithDup(vector<int> &nums) {
        sort(nums.begin(), nums.end());
        dfs(nums, -1);
        return ans;
    }

private:
    // vertex = 取数组 nums 的索引为值
    void dfs(vector<int> &nums, int vertex) {
        if (vertex >= 0) {
            path.push_back(nums[vertex]);
        }
        ans.push_back(path);
        int prev = INT_MIN;
        // 避免重复，从 vertex + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        int v = vertex;
        while (++v < nums.size()) {
            int x = nums[v];
            if (x != prev) {
                prev = x;
                dfs(nums, v);
            }
        }
        if (vertex >= 0) {
            path.pop_back();
        }
    }

    vector<int> path; // 取 nums[vertex] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391613089/
```

## 92. 反转链表 II

<https://leetcode.cn/problems/reverse-linked-list-ii/>

```cpp
class Solution {
public:
    ListNode *reverseBetween(ListNode *head, int left, int right) {
        if (head == nullptr || head->next == nullptr) {
            return head;
        }
        if (left == 1) {
            return reverseList(head, right);
        }
        ListNode *ptr = head;
        for (int i = 1; i <= left - 2; ++i) {
            ptr = ptr->next;
        }
        ptr->next = reverseList(ptr->next, right - left + 1);
        return head;
    }

private:
    // 翻转链表的前 n 个节点，返回翻转后的头节点
    ListNode *reverseList(ListNode *head, int n) {
        if (head == nullptr || head->next == nullptr || n <= 1) {
            return head;
        }
        ListNode *reverseHead = nullptr;
        ListNode *ptr = head;
        while (ptr != nullptr && n > 0) {
            ListNode *next = ptr->next;
            ptr->next = reverseHead;
            reverseHead = ptr;
            ptr = next;
            --n;
        }
        head->next = ptr;
        return reverseHead;
    }
};
// https://leetcode.cn/submissions/detail/357968610/
```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```cpp
class Solution {
public:
    vector<int> inorderTraversal(TreeNode *root) {
        vector<int> res;
        if (root == nullptr) {
            return res;
        }
        vector<int> left = inorderTraversal(root->left);
        res.insert(end(res), begin(left), end(left));
        res.push_back(root->val);
        vector<int> right = inorderTraversal(root->right);
        res.insert(end(res), begin(right), end(right));
        return res;
    }
};
// https://leetcode.cn/submissions/detail/355143984/
```

```cpp
class Solution {
public:
    vector<int> inorderTraversal(TreeNode *root) {
        dfs(root);
        return ans;
    }

private:
    void dfs(const TreeNode *root) {
        if (root == nullptr) {
            return;
        }
        dfs(root->left);
        ans.push_back(root->val);
        dfs(root->right);
    }

    vector<int> ans;
};
// https://leetcode.cn/submissions/detail/366425763/
```

```cpp
class Solution {
public:
    vector<int> inorderTraversal(TreeNode *root) {
        vector<int> inorder;
        unordered_set<TreeNode *> marked;
        stack<TreeNode *> stack;
        if (root != nullptr) {
            stack.push(root);
        }
        while (!stack.empty()) {
            TreeNode *x = stack.top();
            TreeNode *left = x->left;
            if (left != nullptr && marked.count(left) == 0) {
                stack.push(left);
                continue;
            }
            if (marked.count(x) == 0) {
                inorder.push_back(x->val);
                marked.insert(x);
            }
            TreeNode *right = x->right;
            if (right != nullptr && marked.count(right) == 0) {
                stack.push(right);
                continue;
            }
            stack.pop();
        }
        return inorder;
    }
};
// https://leetcode.cn/submissions/detail/391586618/
```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```cpp
class Solution {
public:
    vector<TreeNode *> generateTrees(int n) {
        return generateTrees(1, n);
    }

private:
    // 返回所有由 [lo..hi] 组成的节点值互不相同的不同二叉搜索树
    vector<TreeNode *> generateTrees(int lo, int hi) {
        if (lo > hi) {
            return {nullptr};
        }
        vector<TreeNode *> res;
        // 根节点为 i
        for (int i = lo; i <= hi; ++i) {
            // 左子树由 [lo..i-1] 组成
            vector<TreeNode *> leftTrees = generateTrees(lo, i - 1);
            // 右子树由 [i+1..hi] 组成
            vector<TreeNode *> rightTrees = generateTrees(i + 1, hi);
            for (const auto &left: leftTrees) {
                for (const auto &right: rightTrees) {
                    res.push_back(new TreeNode(i, left, right));
                }
            }
        }
        return res;
    }
};
// https://leetcode.cn/submissions/detail/391589267/
```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```cpp
class Solution {
public:
    // 由 n 个不同数字 x_1 < x_2 < ... < x_n 组成的节点值互不相同的二叉搜索树的种数
    int numTrees(int n) {
        if (n == 0) {
            return 1;
        }
        if (memo.count(n) == 0) {
            // 根节点为 x_i
            for (int i = 1; i <= n; ++i) {
                // 左子树由 i-1 个数字 x1 < x2 < ... < x_i-1 组成
                int left = numTrees(i - 1);
                // 右子树由 n-i 个数字 x_i+1 < x_i+2 < ... < x_n 组成
                int right = numTrees(n - i);
                memo[n] += left * right;
            }
        }
        return memo[n];
    }

private:
    unordered_map<int, int> memo;
};
// https://leetcode.cn/submissions/detail/391591454/
```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```cpp
class Solution {
public:
    bool isValidBST(TreeNode *root) {
        lowerUpper(root, LONG_MIN, LONG_MAX);
        return bst;
    }

private:
    // 检查二叉树是否在区间 (lower, upper) 内，递归过程中确定是否满足二叉搜索树的性质。
    bool lowerUpper(TreeNode *root, long lower, long upper) {
        if (root == nullptr) {
            return true;
        }
        if (root->val <= lower || root->val >= upper) {
            bst = false;
            return false;
        }
        return lowerUpper(root->left, lower, root->val) &&
               lowerUpper(root->right, root->val, upper);
    }

    bool bst = true;
};
// https://leetcode.cn/submissions/detail/391599582/
```

```cpp
class Solution {
public:
    bool isValidBST(TreeNode *root) {
        minMax(root);
        return bst;
    }

private:
    // 二叉树的最小值和最大值
    pair<long, long> minMax(TreeNode *root) {
        if (root == nullptr) {
            return {LONG_MAX, LONG_MIN};
        }
        auto leftPair = minMax(root->left);
        auto rightPair = minMax(root->right);
        long leftMinVal = leftPair.first;
        long leftMaxVal = leftPair.second;
        long rightMinVal = rightPair.first;
        long rightMaxVal = rightPair.second;
        // max(root.left) < root.val < min(root.right)
        if (!(leftMaxVal < root->val && root->val < rightMinVal)) {
            bst = false;
        }
        long minVal = min<long>(root->val, min<long>(leftMinVal, rightMinVal));
        long maxVal = max<long>(root->val, max<long>(leftMaxVal, rightMaxVal));
        return {minVal, maxVal};
    }

    bool bst = true;
};
// https://leetcode.cn/submissions/detail/391601494/
```

```cpp
class Solution {
public:
    bool isValidBST(TreeNode *root) {
        inorderTraversal(root);
        return bst;
    }

private:
    void inorderTraversal(TreeNode *root) {
        if (root == nullptr) {
            return;
        }
        inorderTraversal(root->left);
        if (ptr != nullptr && ptr->val >= root->val) {
            bst = false;
            return;
        }
        ptr = root;
        inorderTraversal(root->right);
    }

    TreeNode *ptr = nullptr;
    bool bst = true;
};
// https://leetcode.cn/submissions/detail/391602211/
```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```cpp
class Solution {
public:
    bool isSameTree(const TreeNode *p, const TreeNode *q) {
        if (p == nullptr && q == nullptr) {
            return true;
        }
        if (p == nullptr || q == nullptr ||
            p->val != q->val) {
            return false;
        }
        return isSameTree(p->left, q->left) &&
               isSameTree(p->right, q->right);
    }
};
// https://leetcode.cn/submissions/detail/436410511/
```

```cpp
class Solution {
public:
    bool isSameTree(TreeNode *p, TreeNode *q) {
        dfs(p, q);
        return ans;
    }

private:
    void dfs(TreeNode *p, TreeNode *q) {
        if (p == nullptr && q == nullptr) {
            return;
        }
        if (p == nullptr || q == nullptr ||
            p->val != q->val) {
            ans = false;
            return;
        }
        dfs(p->left, q->left);
        dfs(p->right, q->right);
    }

    bool ans = true;
};
// https://leetcode.cn/submissions/detail/391588785/
```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```cpp
class Solution {
public:
    vector<vector<int>> levelOrder(TreeNode *root) {
        vector<vector<int>> ans;
        deque<TreeNode *> q;
        if (root != nullptr) {
            q.push_back(root);
        }
        while (!q.empty()) {
            vector<int> level;
            size_t n = q.size();
            for (int i = 0; i < n; ++i) {
                TreeNode *x = q.front();
                level.push_back(x->val);
                q.pop_front();
                TreeNode *left = x->left;
                if (left != nullptr) {
                    q.push_back(left);
                }
                TreeNode *right = x->right;
                if (right != nullptr) {
                    q.push_back(right);
                }
            }
            ans.push_back(level);
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391692206/
```

```cpp
class Solution {
public:
    vector<vector<int>> levelOrder(TreeNode *root) {
        dfs(root, 0);
        return ans;
    }

private:
    void dfs(const TreeNode *root, int depth) {
        if (root == nullptr) {
            return;
        }
        if (ans.size() == depth) {
            ans.emplace_back();
        }
        ans[depth].push_back(root->val);
        dfs(root->left, depth + 1);
        dfs(root->right, depth + 1);
    }

    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391692519/
```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode.cn/problems/binary-tree-zigzag-level-order-traversal/>

```cpp
class Solution {
public:
    vector<vector<int>> zigzagLevelOrder(TreeNode *root) {
        vector<vector<int>> ans;
        deque<TreeNode *> q;
        if (root != nullptr) {
            q.push_back(root);
        }
        bool rev = false;
        while (!q.empty()) {
            size_t n = q.size();
            vector<int> level;
            for (int i = 0; i < n; ++i) {
                TreeNode *x = q.front();
                level.push_back(x->val);
                q.pop_front();
                TreeNode *left = x->left;
                if (left != nullptr) {
                    q.push_back(left);
                }
                TreeNode *right = x->right;
                if (right != nullptr) {
                    q.push_back(right);
                }
            }
            if (rev) {
                reverse(level.begin(), level.end());
            }
            rev = !rev;
            ans.push_back(level);
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391692893/
```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```cpp
class Solution {
public:
    int maxDepth(TreeNode *root) {
        if (root == nullptr) {
            return 0;
        }
        return 1 + max(maxDepth(root->left), maxDepth(root->right));
    }
};
// https://leetcode.cn/submissions/detail/365913594/
```

```cpp
class Solution {
public:
    int maxDepth(TreeNode *root) {
        int depth = 0;
        deque<TreeNode *> q;
        if (root != nullptr) {
            q.push_back(root);
        }
        while (!q.empty()) {
            ++depth;
            size_t n = q.size();
            for (int i = 0; i < n; ++i) {
                TreeNode *x = q.front();
                q.pop_front();
                TreeNode *left = x->left;
                if (left != nullptr) {
                    q.push_back(left);
                }
                TreeNode *right = x->right;
                if (right != nullptr) {
                    q.push_back(right);
                }
            }
        }
        return depth;
    }
};
// https://leetcode.cn/submissions/detail/391473405/
```

```cpp
class Solution {
public:
    int maxDepth(TreeNode *root) {
        if (root == nullptr) {
            return 0;
        }
        ++depth;
        backtrack(root);
        --depth;
        return ans;
    }

private:
    void backtrack(const TreeNode *root) {
        TreeNode *left = root->left;
        TreeNode *right = root->right;
        if (left == nullptr && right == nullptr) {
            ans = max(ans, depth);
            return;
        }
        if (left != nullptr) {
            ++depth;
            backtrack(left);
            --depth;
        }
        if (right != nullptr) {
            ++depth;
            backtrack(right);
            --depth;
        }
    }

    int depth = 0;
    int ans = 0;
};
// https://leetcode.cn/submissions/detail/365915460/
```

```cpp
class Solution {
public:
    int maxDepth(TreeNode *root) {
        dfs(root, 1);
        return ans;
    }

private:
    void dfs(const TreeNode *root, int depth) {
        if (root == nullptr) {
            return;
        }
        if (root->left == nullptr && root->right == nullptr) {
            ans = max(ans, depth);
        }
        dfs(root->left, depth + 1);
        dfs(root->right, depth + 1);
    }

    int ans = 0;
};
// https://leetcode.cn/submissions/detail/365913302/
```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```cpp
class Solution {
public:
    TreeNode *buildTree(vector<int> &preorder, vector<int> &inorder) {
        for (int i = 0; i < inorder.size(); ++i) {
            valToIndex[inorder[i]] = i;
        }
        return buildTree(preorder, 0, preorder.size() - 1,
                         inorder, 0, inorder.size() - 1);
    }

private:
    TreeNode *buildTree(const vector<int> &preorder, int preStart, int preEnd,
                        const vector<int> &inorder, int inStart, int inEnd) {
        if (preStart > preEnd) {
            return nullptr;
        }
        int rootVal = preorder[preStart];
        auto *root = new TreeNode(rootVal);
        int inRoot = valToIndex[rootVal];
        int leftSize = inRoot - inStart;
        root->left = buildTree(preorder, preStart + 1, preStart + leftSize,
                               inorder, inStart, inRoot - 1);
        root->right = buildTree(preorder, preStart + leftSize + 1, preEnd,
                                inorder, inRoot + 1, inEnd);
        return root;
    }

    unordered_map<int, int> valToIndex;
};
// https://leetcode.cn/submissions/detail/391591107/
```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```cpp
class Solution {
public:
    TreeNode *buildTree(vector<int> &inorder, vector<int> &postorder) {
        for (int i = 0; i < inorder.size(); ++i) {
            valToIndex[inorder[i]] = i;
        }
        return buildTree(inorder, 0, inorder.size() - 1,
                         postorder, 0, postorder.size() - 1);
    }

private:
    TreeNode *buildTree(const vector<int> &inorder, int inStart, int inEnd,
                        const vector<int> &postorder, int postStart, int postEnd) {
        if (inStart > inEnd) {
            return nullptr;
        }
        int rootVal = postorder[postEnd];
        auto *root = new TreeNode(rootVal);
        int inRoot = valToIndex[rootVal];
        int leftSize = inRoot - inStart;
        root->left = buildTree(inorder, inStart, inRoot - 1,
                               postorder, postStart, postStart + leftSize - 1);
        root->right = buildTree(inorder, inRoot + 1, inEnd,
                                postorder, postStart + leftSize, postEnd - 1);
        return root;
    }

    unordered_map<int, int> valToIndex;
};
// https://leetcode.cn/submissions/detail/391590030/
```

## 107. 二叉树的层序遍历 II

<https://leetcode.cn/problems/binary-tree-level-order-traversal-ii/>

```cpp
class Solution {
public:
    vector<vector<int>> levelOrderBottom(TreeNode *root) {
        vector<vector<int>> ans;
        deque<TreeNode *> q;
        if (root != nullptr) {
            q.push_back(root);
        }
        while (!q.empty()) {
            vector<int> level;
            size_t n = q.size();
            for (int i = 0; i < n; ++i) {
                TreeNode *x = q.front();
                q.pop_front();
                level.push_back(x->val);
                TreeNode *left = x->left;
                if (left != nullptr) {
                    q.push_back(left);
                }
                TreeNode *right = x->right;
                if (right != nullptr) {
                    q.push_back(right);
                }
            }
            ans.push_back(level);
        }
        reverse(ans.begin(), ans.end());
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391693473/
```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```cpp
class Solution {
public:
    TreeNode *sortedArrayToBST(const vector<int> &nums) {
        return sortedArrayToBST(nums, 0, nums.size() - 1);
    }

private:
    // 将有序数组 nums[lo..hi] 转换为二叉搜索树
    TreeNode *sortedArrayToBST(const vector<int> &nums, int lo, int hi) {
        if (lo > hi) {
            return nullptr;
        }
        int mid = lo + (hi - lo) / 2;
        auto *root = new TreeNode(nums[mid]);
        root->left = sortedArrayToBST(nums, lo, mid - 1);
        root->right = sortedArrayToBST(nums, mid + 1, hi);
        return root;
    }
};
// https://leetcode.cn/submissions/detail/437317019/
```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```cpp
class Solution {
public:
    bool isBalanced(TreeNode *root) {
        height(root);
        return balanced;
    }

private:
    int height(const TreeNode *root) {
        if (root == nullptr) {
            return -1;
        }
        int left = height(root->left);
        int right = height(root->right);
        if (abs(left - right) > 1) {
            balanced = false;
        }
        return 1 + max(left, right);
    }

    bool balanced = true;
};
// https://leetcode.cn/submissions/detail/391593214/
```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```cpp
class Solution {
public:
    int minDepth(TreeNode *root) {
        int depth = 0;
        deque<TreeNode *> q;
        if (root != nullptr) {
            q.push_back(root);
        }
        while (!q.empty()) {
            ++depth;
            size_t n = q.size();
            for (int i = 0; i < n; ++i) {
                TreeNode *x = q.front();
                q.pop_front();
                TreeNode *left = x->left;
                TreeNode *right = x->right;
                if (left == nullptr && right == nullptr) {
                    return depth;
                }
                if (left != nullptr) {
                    q.push_back(left);
                }
                if (right != nullptr) {
                    q.push_back(right);
                }
            }
        }
        return depth;
    }
};
// https://leetcode.cn/submissions/detail/391693923/
```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```cpp
class Solution {
public:
    bool hasPathSum(TreeNode *root, int targetSum) {
        if (root == nullptr) {
            return false;
        }
        if (root->left == nullptr && root->right == nullptr) {
            return root->val == targetSum;
        }
        return hasPathSum(root->left, targetSum - root->val) ||
               hasPathSum(root->right, targetSum - root->val);
    }
};
// https://leetcode.cn/submissions/detail/391520996/
```

```cpp
class Solution {
public:
    bool hasPathSum(TreeNode *root, int targetSum) {
        if (root != nullptr) {
            pathSum += root->val;
            backtrack(root, targetSum);
            pathSum -= root->val;
        }
        return ans;
    }

private:
    void backtrack(const TreeNode *root, int targetSum) {
        TreeNode *left = root->left;
        TreeNode *right = root->right;
        if (left == nullptr && right == nullptr &&
            pathSum == targetSum) {
            ans = true;
        }
        if (left != nullptr) {
            pathSum += left->val;
            backtrack(left, targetSum);
            pathSum -= left->val;
        }
        if (right != nullptr) {
            pathSum += right->val;
            backtrack(right, targetSum);
            pathSum -= right->val;
        }
    }

    int pathSum = 0;
    bool ans = false;
};
// https://leetcode.cn/submissions/detail/391522539/
```

```cpp
class Solution {
public:
    bool hasPathSum(TreeNode *root, int targetSum) {
        dfs(root, targetSum);
        return ans;
    }

private:
    void dfs(const TreeNode *root, int targetSum) {
        if (root == nullptr) {
            return;
        }
        pathSum += root->val;
        if (root->left == nullptr && root->right == nullptr &&
            pathSum == targetSum) {
            ans = true;
        }
        dfs(root->left, targetSum);
        dfs(root->right, targetSum);
        pathSum -= root->val;
    }

    int pathSum = 0;
    bool ans = false;
};
// https://leetcode.cn/submissions/detail/391523436/
```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```cpp
class Solution {
public:
    void flatten(TreeNode *root) {
        if (root == nullptr) {
            return;
        }
        flatten(root->left);
        flatten(root->right);
        TreeNode *left = root->left;
        TreeNode *right = root->right;
        root->left = nullptr;
        root->right = left;
        TreeNode *ptr = root;
        while (ptr->right != nullptr) {
            ptr = ptr->right;
        }
        ptr->right = right;
    }
};
// https://leetcode.cn/submissions/detail/391476610/
```

```cpp
class Solution {
public:
    void flatten(TreeNode *root) {
        auto *dummyHead = new TreeNode();
        ptr = dummyHead;
        dfs(root);
        delete dummyHead;
    }

private:
    void dfs(TreeNode *root) {
        if (root == nullptr) {
            return;
        }
        ptr->right = root;
        ptr = ptr->right;
        TreeNode *left = root->left;
        TreeNode *right = root->right;
        root->left = nullptr;
        root->right = nullptr;
        dfs(left);
        dfs(right);
    }

    TreeNode *ptr;
};
// https://leetcode.cn/submissions/detail/391476852/
```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```cpp
class Solution {
public:
    Node *connect(Node *root) {
        if (root != nullptr) {
            connect(root->left, root->right);
        }
        return root;
    }

private:
    void connect(Node *first, Node *second) {
        if (first == nullptr && second == nullptr) {
            return;
        }
        first->next = second;
        connect(first->left, first->right);
        connect(first->right, second->left);
        connect(second->left, second->right);
    }
};
// https://leetcode.cn/submissions/detail/370600862/
```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```cpp
class Solution {
public:
    int maxProfit(vector<int> &prices) {
        size_t n = prices.size();
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        vector<vector<int>> dp(n, vector<int>(2));
        dp[0][0] = 0;
        dp[0][1] = -prices[0];
        for (int i = 1; i < n; ++i) {
            // dp[i - 1][0]             >= -prices[i]
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = max(-prices[i], dp[i - 1][1]);
        }
        return dp[n - 1][0];
    }
};
// https://leetcode.cn/submissions/detail/391485310/
```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```cpp
class Solution {
public:
    int maxProfit(vector<int> &prices) {
        size_t n = prices.size();
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        vector<vector<int>> dp(n, vector<int>(2));
        dp[0][0] = 0;
        dp[0][1] = -prices[0];
        for (int i = 1; i < n; ++i) {
            // dp[i - 1][0]             >= dp[i - 1][0] - prices[i]
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = max(dp[i - 1][0] - prices[i], dp[i - 1][1]);
        }
        return dp[n - 1][0];
    }
};
// https://leetcode.cn/submissions/detail/391485564/
```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```cpp
class Solution {
public:
    int maxProfit(vector<int> &prices) {
        return maxProfit(2, prices);
    }

private:
    int maxProfit(int k, vector<int> &prices) {
        size_t n = prices.size();
        if (k <= 0 || n <= 1) {
            return 0;
        }
        // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
        // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
        vector<vector<vector<int>>> dp(k + 1, vector<vector<int>>(n, vector<int>(2)));
        // 交易次数限制为 0 时
        // 填写第 0 个 n x 2 矩阵
        for (int i = 0; i < n; ++i) {
            dp[0][i][0] = 0;
            dp[0][i][1] = INT_MIN;
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
                dp[t][i][0] = max(dp[t][i - 1][0], dp[t][i - 1][1] + prices[i]);
                dp[t][i][1] = max(dp[t - 1][i - 1][0] - prices[i], dp[t][i - 1][1]);
            }
        }
        return dp[k][n - 1][0];
    }
};
// https://leetcode.cn/submissions/detail/391543692/
```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```cpp
class Solution {
public:
    bool isPalindrome(string s) {
        int n = s.size();
        int i = -1, j = n;
        while (true) {
            while (!isalnum(s[++i])) {
                if (i == n - 1) {
                    break;
                }
            }
            while (!isalnum(s[--j])) {
                if (j == 0) {
                    break;
                }
            }
            if (i >= j) {
                break;
            }
            if (tolower(s[i]) != tolower(s[j])) {
                return false;
            }
        }
        return true;
    }
};
// https://leetcode.cn/submissions/detail/363595389/
```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```cpp
class Solution {
public:
    int longestConsecutive(vector<int> &nums) {
        int ans = 0;
        unordered_set<int> set(nums.begin(), nums.end());
        for (const auto &x: nums) {
            if (set.count(x) == 1) {
                set.erase(x);
                int lo = x - 1;
                while (set.count(lo) == 1) {
                    set.erase(lo--);
                }
                int hi = x + 1;
                while (set.count(hi) == 1) {
                    set.erase(hi++);
                }
                ans = max(ans, hi - lo - 1);
            }
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391662422/
```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```cpp
class Solution {
public:
    void solve(vector<vector<char>> &grid) {
        int m = grid.size(), n = grid[0].size();
        mark = true;
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
        mark = false;
        for (int row = 0; row < m; ++row) {
            for (int col = 0; col < n; ++col) {
                if (grid[row][col] == LAND) {
                    floodFill(grid, row, col);
                }
            }
        }
        for (const auto &x: recovery) {
            int row = x / n;
            int col = x % n;
            grid[row][col] = LAND;
        }
    }

private:
    void floodFill(vector<vector<char>> &grid, int row, int col) {
        if (row < 0 || row >= grid.size() || col < 0 || col >= grid[0].size() || grid[row][col] == WATER) {
            return;
        }
        if (mark) {
            recovery.insert(row * grid[0].size() + col);
        }
        grid[row][col] = WATER;
        floodFill(grid, row, col + 1);
        floodFill(grid, row, col - 1);
        floodFill(grid, row + 1, col);
        floodFill(grid, row - 1, col);
    }

    bool mark;
    unordered_set<int> recovery;
    static const char LAND = 'O';
    static const char WATER = 'X';
};
// https://leetcode.cn/submissions/detail/391718492/
```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```cpp
class Solution {
public:
    int singleNumber(vector<int> &nums) {
        int ans = 0;
        for (const auto &x: nums) {
            ans ^= x;
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391455813/
```

```cpp
class Solution {
public:
    int singleNumber(vector<int> &nums) {
        unordered_map<int, int> map;
        for (const auto &x: nums) {
            map[x] += 1;
        }
        for (const auto &it: map) {
            if (it.second == 1) {
                return it.first;
            }
        }
        return -1;
    }
};
// https://leetcode.cn/submissions/detail/391456296/
```

```cpp
class Solution {
public:
    int singleNumber(vector<int> &nums) {
        unordered_set<int> set;
        for (const auto &x: nums) {
            if (set.count(x) == 1) {
                set.erase(x);
            } else {
                set.insert(x);
            }
        }
        return *set.begin();
    }
};
// https://leetcode.cn/submissions/detail/391456600/
```

```cpp
class Solution {
public:
    int singleNumber(vector<int> &nums) {
        unordered_set<int> set;
        int sumOfSet = 0, sumOfArray = 0;
        for (const auto &x: nums) {
            sumOfArray += x;
            if (set.count(x) == 0) {
                sumOfSet += x;
                set.insert(x);
            }
        }
        return 2 * sumOfSet - sumOfArray;
    }
};
// https://leetcode.cn/submissions/detail/391458687/
```

```cpp
class Solution {
public:
    int singleNumber(vector<int> &nums) {
        unordered_set<int> set(nums.begin(), nums.end());
        int sumOfSet = accumulate(set.begin(), set.end(), 0);
        int sumOfArray = accumulate(nums.begin(), nums.end(), 0);
        return 2 * sumOfSet - sumOfArray;
    }
};
// https://leetcode.cn/submissions/detail/391460518/
```

## 141. 环形链表

<https://leetcode.cn/problems/linked-list-cycle/>

```cpp
class Solution {
public:
    bool hasCycle(ListNode *head) {
        ListNode *slow = head;
        ListNode *fast = head;
        while (fast != nullptr && fast->next != nullptr) {
            slow = slow->next;
            fast = fast->next->next;
            if (slow == fast) {
                return true;
            }
        }
        return false;
    }
};
// https://leetcode.cn/submissions/detail/361358054/
```

```cpp
class Solution {
public:
    bool hasCycle(ListNode *head) {
        unordered_set<ListNode *> set;
        while (head != nullptr) {
            if (set.count(head) > 0) {
                return true;
            }
            set.insert(head);
            head = head->next;
        }
        return false;
    }
};
// https://leetcode.cn/submissions/detail/391470007/
```

## 142. 环形链表 II

<https://leetcode.cn/problems/linked-list-cycle-ii/>

```cpp
class Solution {
public:
    ListNode *detectCycle(ListNode *head) {
        ListNode *slow = head;
        ListNode *fast = head;
        while (fast != nullptr && fast->next != nullptr) {
            slow = slow->next;
            fast = fast->next->next;
            if (slow == fast) {
                fast = head;
                while (slow != fast) {
                    slow = slow->next;
                    fast = fast->next;
                }
                return slow;
            }
        }
        return nullptr;
    }
};
// https://leetcode.cn/submissions/detail/340604036/
```

```cpp
class Solution {
public:
    ListNode *detectCycle(ListNode *head) {
        unordered_set<ListNode *> set;
        while (head != nullptr) {
            if (set.count(head) > 0) {
                return head;
            }
            set.insert(head);
            head = head->next;
        }
        return nullptr;
    }
};
// https://leetcode.cn/submissions/detail/391470392/
```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```cpp
class Solution {
public:
    void reorderList(ListNode *head) {
        ListNode *slow = head;
        ListNode *fast = head;
        while (fast->next != nullptr && fast->next->next != nullptr) {
            slow = slow->next;
            fast = fast->next->next;
        }
        ListNode *x = slow->next;
        slow->next = nullptr;
        ListNode *reverseHead = reverseList(x);
        auto *dummyHead = new ListNode();
        ListNode *ptr = dummyHead;
        while (head != nullptr) {
            ptr->next = head;
            ptr = ptr->next;
            head = head->next;
            if (reverseHead != nullptr) {
                ptr->next = reverseHead;
                ptr = ptr->next;
                reverseHead = reverseHead->next;
            }
        }
        delete dummyHead;
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
// https://leetcode.cn/submissions/detail/391528149/
```

```cpp
class Solution {
public:
    void reorderList(ListNode *head) {
        vector<ListNode *> v;
        while (head != nullptr) {
            ListNode *next = head->next;
            head->next = nullptr;
            v.push_back(head);
            head = next;
        }
        auto *dummyHead = new ListNode();
        head = dummyHead;
        int left = 0, right = v.size() - 1;
        while (left <= right) {
            head->next = v[left];
            head = head->next;
            if (left == right) {
                break;
            }
            head->next = v[right];
            head = head->next;
            ++left;
            --right;
        }
        delete dummyHead;
    }
};
// https://leetcode.cn/submissions/detail/391526672/
```

```cpp
class Solution {
public:
    void reorderList(ListNode *head) {
        deque<ListNode *> q;
        while (head != nullptr) {
            ListNode *next = head->next;
            head->next = nullptr;
            q.push_back(head);
            head = next;
        }
        auto *dummyHead = new ListNode();
        head = dummyHead;
        while (!q.empty()) {
            head->next = q.front();
            q.pop_front();
            head = head->next;
            if (!q.empty()) {
                head->next = q.back();
                q.pop_back();
                head = head->next;
            }
        }
        delete dummyHead;
    }
};
// https://leetcode.cn/submissions/detail/391527269/
```

```cpp
class Solution {
public:
    void reorderList(ListNode *head) {
        ListNode *slow = head;
        ListNode *fast = head;
        while (fast->next != nullptr && fast->next->next != nullptr) {
            slow = slow->next;
            fast = fast->next->next;
        }
        ListNode *ptr = slow->next;
        slow->next = nullptr;
        stack<ListNode *> s;
        while (ptr != nullptr) {
            ListNode *next = ptr->next;
            ptr->next = nullptr;
            s.push(ptr);
            ptr = next;
        }
        auto *dummyHead = new ListNode();
        ptr = dummyHead;
        while (head != nullptr) {
            ptr->next = head;
            ptr = ptr->next;
            head = head->next;
            if (!s.empty()) {
                ptr->next = s.top();
                s.pop();
                ptr = ptr->next;
            }
        }
        delete dummyHead;
    }
};
// https://leetcode.cn/submissions/detail/391531396/
```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```cpp
class Solution {
public:
    vector<int> preorderTraversal(TreeNode *root) {
        dfs(root);
        return ans;
    }

private:
    void dfs(const TreeNode *root) {
        if (root == nullptr) {
            return;
        }
        ans.push_back(root->val);
        dfs(root->left);
        dfs(root->right);
    }

    vector<int> ans;
};
// https://leetcode.cn/submissions/detail/366426509/
```

```cpp
class Solution {
public:
    vector<int> inorderTraversal(TreeNode *root) {
        if (root == nullptr) {
            return {};
        }
        vector<int> res;
        vector<int> left = inorderTraversal(root->left);
        res.insert(res.end(), left.begin(), left.end());
        res.push_back(root->val);
        vector<int> right = inorderTraversal(root->right);
        res.insert(res.end(), right.begin(), right.end());
        return res;
    }
};
// https://leetcode.cn/submissions/detail/391586100/
```

```cpp
class Solution {
public:
    vector<int> preorderTraversal(TreeNode *root) {
        vector<int> preorder;
        stack<TreeNode *> s;
        if (root != nullptr) {
            s.push(root);
        }
        while (!s.empty()) {
            TreeNode *x = s.top();
            s.pop();
            preorder.push_back(x->val);
            TreeNode *right = x->right;
            if (right != nullptr) {
                s.push(right);
            }
            TreeNode *left = x->left;
            if (left != nullptr) {
                s.push(left);
            }
        }
        return preorder;
    }
};
// https://leetcode.cn/submissions/detail/391585407/
```

```cpp
class Solution {
public:
    vector<int> preorderTraversal(TreeNode *root) {
        vector<int> preorder;
        unordered_set<TreeNode *> marked;
        stack<TreeNode *> stack;
        if (root != nullptr) {
            stack.push(root);
        }
        while (!stack.empty()) {
            TreeNode *x = stack.top();
            if (marked.count(x) == 0) {
                preorder.push_back(x->val);
                marked.insert(x);
            }
            TreeNode *left = x->left;
            if (left != nullptr && marked.count(left) == 0) {
                stack.push(left);
                continue;
            }
            TreeNode *right = x->right;
            if (right != nullptr && marked.count(right) == 0) {
                stack.push(right);
                continue;
            }
            stack.pop();
        }
        return preorder;
    }
};
// https://leetcode.cn/submissions/detail/391585628/
```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```cpp
class Solution {
public:
    vector<int> postorderTraversal(TreeNode *root) {
        dfs(root);
        return ans;
    }

private:
    void dfs(const TreeNode *root) {
        if (root == nullptr) {
            return;
        }
        dfs(root->left);
        dfs(root->right);
        ans.push_back(root->val);
    }

    vector<int> ans;
};
// https://leetcode.cn/submissions/detail/366427798/
```

```cpp
class Solution {
public:
    vector<int> postorderTraversal(TreeNode *root) {
        if (root == nullptr) {
            return {};
        }
        vector<int> res;
        vector<int> left = postorderTraversal(root->left);
        res.insert(res.end(), left.begin(), left.end());
        vector<int> right = postorderTraversal(root->right);
        res.insert(res.end(), right.begin(), right.end());
        res.push_back(root->val);
        return res;
    }
};
// https://leetcode.cn/submissions/detail/391587103/
```

```cpp
class Solution {
public:
    vector<int> postorderTraversal(TreeNode *root) {
        vector<int> postorder;
        unordered_set<TreeNode *> marked;
        stack<TreeNode *> stack;
        if (root != nullptr) {
            stack.push(root);
        }
        while (!stack.empty()) {
            TreeNode *x = stack.top();
            TreeNode *left = x->left;
            if (left != nullptr && marked.count(left) == 0) {
                stack.push(left);
                continue;
            }
            TreeNode *right = x->right;
            if (right != nullptr && marked.count(right) == 0) {
                stack.push(right);
                continue;
            }
            if (marked.count(x) == 0) {
                postorder.push_back(x->val);
                marked.insert(x);
            }
            stack.pop();
        }
        return postorder;
    }
};
// https://leetcode.cn/submissions/detail/391587438/
```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```cpp
struct MyListNode {
    int key, val;
    MyListNode *prev;
    MyListNode *next;

    MyListNode(int k, int v) : key{k}, val{v}, prev{nullptr}, next{nullptr} {}
};

class MyDoublyLinkedList {
public:
    MyDoublyLinkedList() : first{nullptr}, last{nullptr}, n{0} {}

    ~MyDoublyLinkedList() {
        while (!empty()) {
            removeFirst();
        }
    }

    void addLast(MyListNode *newNode) {
        if (n == 0) {
            first = newNode;
            last = newNode;
        } else {
            last->next = newNode;
            newNode->prev = last;
            last = newNode;
        }
        ++n;
    }

    void removeFirst() {
        MyListNode *oldFirst = first;
        if (n == 1) {
            first = nullptr;
            last = nullptr;
        } else {
            first = first->next;
            first->prev = nullptr;
        }
        delete oldFirst;
        --n;
    }

    void removeLast() {
        MyListNode *oldLast = last;
        if (n == 1) {
            first = nullptr;
            last = nullptr;
        } else {
            last = last->prev;
            last->next = nullptr;
        }
        delete oldLast;
        --n;
    }

    void remove(MyListNode *delNode) {
        if (delNode == first) {
            removeFirst();
        } else if (delNode == last) {
            removeLast();
        } else {
            delNode->prev->next = delNode->next;
            delNode->next->prev = delNode->prev;
            delete delNode;
            --n;
        }
    }

    const MyListNode *getFirst() const {
        return first;
    }

    bool empty() const {
        return first == nullptr;
    }

private:
    MyListNode *first;
    MyListNode *last;
    int n;
};

class LRUCache {
public:
    explicit LRUCache(int capacity) {
        this->capacity = capacity;
    }

    int get(int key) {
        if (contains(key)) {
            return touchCache(key, INT_MIN);
        }
        return -1;
    }

    void put(int key, int value) {
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

private:
    bool contains(int key) {
        return keyToNode.count(key) == 1;
    }

    bool full() {
        return keyToNode.size() == capacity;
    }

    void addCache(int key, int val) {
        auto *newNode = new MyListNode(key, val);
        list.addLast(newNode);
        keyToNode[key] = newNode;
    }

    void removeCache() {
        int delKey = list.getFirst()->key;
        list.removeFirst();
        keyToNode.erase(delKey);
    }

    int touchCache(int key, int val) {
        MyListNode *oldNode = keyToNode[key];
        int newVal = oldNode->val;
        if (val != INT_MIN) {
            newVal = val;
        }
        list.remove(oldNode);
        auto *newNode = new MyListNode(key, newVal);
        list.addLast(newNode);
        keyToNode[key] = newNode;
        return newVal;
    }

private:
    int capacity;
    MyDoublyLinkedList list;
    unordered_map<int, MyListNode *> keyToNode;
};
// https://leetcode.cn/submissions/detail/441746007/
```

```cpp
class LRUCache {
public:
    explicit LRUCache(int capacity) {
        this->capacity = capacity;
    }

    int get(int key) {
        if (contains(key)) {
            return touchCache(key, INT_MIN);
        }
        return -1;
    }

    void put(int key, int value) {
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

private:
    bool contains(int key) {
        return keyToIter.count(key) == 1;
    }

    bool full() {
        return keyToIter.size() == capacity;
    }

    void addCache(int key, int val) {
        list.emplace_back(key, val);
        keyToIter[key] = prev(list.end());
    }

    void removeCache() {
        int delKey = list.front().first;
        list.pop_front();
        keyToIter.erase(delKey);
    }

    int touchCache(int key, int val) {
        auto oldIter = keyToIter[key];
        int newVal = oldIter->second;
        if (val != INT_MIN) {
            newVal = val;
        }
        list.erase(oldIter);
        list.emplace_back(key, newVal);
        auto newIter = prev(list.end());
        keyToIter[key] = newIter;
        return newIter->second;
    }

    int capacity;
    std::list<pair<int, int>> list;
    unordered_map<int, std::list<pair<int, int>>::iterator> keyToIter;
};
// https://leetcode.cn/submissions/detail/441748772/
```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```cpp
class Solution {
public:
    int findMin(vector<int> &nums) {
        int lo = 0, hi = nums.size() - 1;
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
};
// https://leetcode.cn/submissions/detail/348420700/
```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```cpp
class MinStack {
public:
    MinStack() = default;

    void push(int val) {
        int minVal = (s.empty() ? val : min(getMin(), val));
        s.emplace(val, minVal);
    }

    void pop() {
        s.pop();
    }

    int top() {
        return s.top().first;
    }

    int getMin() {
        return s.top().second;
    }

private:
    stack<pair<int, int>> s;
};
// https://leetcode.cn/submissions/detail/391689608/
```

```cpp
class MinStack {
public:
    MinStack() = default;

    void push(int val) {
        stack1.push(val);
        if (stack2.empty() || val <= getMin()) {
            stack2.push(val);
        }
    }

    void pop() {
        if (stack1.top() == getMin()) {
            stack2.pop();
        }
        stack1.pop();
    }

    int top() {
        return stack1.top();
    }

    int getMin() {
        return stack2.top();
    }

private:
    stack<int> stack1;
    stack<int> stack2;
};
// https://leetcode.cn/submissions/detail/391690189/
```

```cpp
class MinStack {
public:
    MinStack() = default;

    void push(int val) {
        if (val <= getMin()) {
            stack.push(minVal);
            minVal = val;
        }
        stack.push(val);
    }

    void pop() {
        int val = stack.top();
        stack.pop();
        if (val == getMin()) {
            minVal = stack.top();
            stack.pop();
        }
    }

    int top() {
        return stack.top();
    }

    int getMin() {
        return minVal;
    }

private:
    int minVal = INT_MAX;
    stack<int> stack;
};
// https://leetcode.cn/submissions/detail/391690531/
```

## 160. 相交链表

<https://leetcode.cn/problems/intersection-of-two-linked-lists/>

```cpp
class Solution {
public:
    ListNode *getIntersectionNode(ListNode *headA, ListNode *headB) {
        ListNode *ptrA = headA;
        ListNode *ptrB = headB;
        while (ptrA != ptrB) {
            ptrA = (ptrA == nullptr ? headB : ptrA->next);
            ptrB = (ptrB == nullptr ? headA : ptrB->next);
        }
        return ptrA;
    }
};
// https://leetcode.cn/submissions/detail/366013752/
```

```cpp
class Solution {
public:
    ListNode *getIntersectionNode(ListNode *headA, ListNode *headB) {
        unordered_set<ListNode *> set;
        ListNode *ptr = headA;
        while (ptr != nullptr) {
            set.insert(ptr);
            ptr = ptr->next;
        }
        ptr = headB;
        while (ptr != nullptr) {
            if (set.count(ptr) > 0) {
                return ptr;
            }
            ptr = ptr->next;
        }
        return nullptr;
    }
};
// https://leetcode.cn/submissions/detail/391469467/
```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```cpp
class Solution {
public:
    int compareVersion(string version1, string version2) {
        size_t n1 = version1.size();
        size_t n2 = version2.size();
        int i = 0, j = 0;
        while (i < n1 || j < n2) {
            int r1 = 0;
            while (i < n1) {
                char ch = version1[i++];
                if (ch == '.') {
                    break;
                }
                r1 = r1 * 10 + (ch - '0');
            }
            int r2 = 0;
            while (j < n2) {
                char ch = version2[j++];
                if (ch == '.') {
                    break;
                }
                r2 = r2 * 10 + (ch - '0');
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
};
// https://leetcode.cn/submissions/detail/391708367/
```

```cpp
class Solution {
public:
    int compareVersion(string version1, string version2) {
        size_t n1 = version1.size();
        size_t n2 = version2.size();
        int i = 0, j = 0;
        string revision1, revision2;
        while (i < n1 || j < n2) {
            revision1 = "0";
            while (i < n1) {
                char ch = version1[i++];
                if (ch == '.') {
                    break;
                }
                revision1 += ch;
            }
            revision2 = "0";
            while (j < n2) {
                char ch = version2[j++];
                if (ch == '.') {
                    break;
                }
                revision2 += ch;
            }
            int r1 = stoi(revision1);
            int r2 = stoi(revision2);
            if (r1 > r2) {
                return 1;
            }
            if (r1 < r2) {
                return -1;
            }
        }
        return 0;
    }
};
// https://leetcode.cn/submissions/detail/391707807/
```

## 167. 两数之和 II - 输入有序数组

<https://leetcode.cn/problems/two-sum-ii-input-array-is-sorted/>

```cpp
class Solution {
public:
    vector<int> twoSum(const vector<int> &numbers, int target) {
        int i = 0, j = numbers.size() - 1;
        while (i < j) {
            int sum = numbers[i] + numbers[j];
            if (sum < target) {
                ++i;
            } else if (sum > target) {
                --j;
            } else {
                return {i + 1, j + 1};
            }
        }
        return {-1, -1};
    }
};
// https://leetcode.cn/submissions/detail/440258850/
```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```cpp
class Solution {
public:
    int majorityElement(vector<int> &nums) {
        int candidate = INT_MIN;
        int count = 0;
        for (const auto &x: nums) {
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
};
// https://leetcode.cn/submissions/detail/391523913/
```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```cpp
class Solution {
public:
    string largestNumber(vector<int> &nums) {
        size_t n = nums.size();
        vector<string> strs(n);
        for (int i = 0; i < n; ++i) {
            strs[i] = to_string(nums[i]);
        }
        sort(strs.begin(), strs.end(),
             [](const string &s1, const string &s2) {
                 return (s1 + s2) > (s2 + s1);
             });
        string ans;
        for (const auto &s: strs) {
            ans += s;
        }
        return ans[0] == '0' ? "0" : ans;
    }
};
// https://leetcode.cn/submissions/detail/391679835/
```

```cpp
class Solution {
public:
    string largestNumber(vector<int> &nums) {
        vector<string> strs(nums.size());
        transform(nums.cbegin(), nums.cend(),
                  strs.begin(),
                  [](const int &a) { return to_string(a); });
        sort(strs.begin(), strs.end(),
             [](const string &s1, const string &s2) {
                 return (s1 + s2) > (s2 + s1);
             });
        string ans;
        for (const auto &s: strs) {
            ans += s;
        }
        return ans[0] == '0' ? "0" : ans;
    }
};
// https://leetcode.cn/submissions/detail/391681091/
```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```cpp
class Solution {
public:
    int maxProfit(int k, const vector<int> &prices) {
        size_t n = prices.size();
        if (k <= 0 || n <= 1) {
            return 0;
        }
        // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
        // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
        vector<vector<vector<int>>> dp(k + 1, vector<vector<int>>(n, vector<int>(2)));
        // 交易次数限制为 0 时
        // 填写第 0 个 n x 2 矩阵
        for (int i = 0; i < n; ++i) {
            dp[0][i][0] = 0;
            dp[0][i][1] = INT_MIN;
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
                dp[t][i][0] = max(dp[t][i - 1][0], dp[t][i - 1][1] + prices[i]);
                dp[t][i][1] = max(dp[t - 1][i - 1][0] - prices[i], dp[t][i - 1][1]);
            }
        }
        return dp[k][n - 1][0];
    }
};
// https://leetcode.cn/submissions/detail/441210880/
```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```cpp
class Solution {
public:
    void rotate(vector<int> &nums, int k) {
        int n = nums.size();
        k %= n;
        if (k > 0) {
            reverse(nums, 0, n - 1);
            reverse(nums, 0, k - 1);
            reverse(nums, k, n - 1);
        }
    }

private:
    void reverse(vector<int> &nums, int lo, int hi) {
        while (lo < hi) {
            swap(nums[lo++], nums[hi--]);
        }
    }
};
// https://leetcode.cn/submissions/detail/366660409/
```

```cpp
class Solution {
public:
    void rotate(vector<int> &nums, int k) {
        k %= nums.size();
        if (k > 0) {
            reverse(nums.begin(), nums.end());
            reverse(nums.begin(), nums.begin() + k);
            reverse(nums.begin() + k, nums.end());
        }
    }
};
// https://leetcode.cn/submissions/detail/364366695/
```

```cpp
class Solution {
public:
    void rotate(vector<int> &nums, int k) {
        int n = nums.size();
        k %= n;
        if (k > 0) {
            vector<int> aux(n);
            for (int i = 0; i < n; ++i) {
                aux[(i + k) % n] = nums[i];
            }
            nums.assign(aux.begin(), aux.end());
        }
    }
};
// https://leetcode.cn/submissions/detail/391450615/
```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```cpp
class Solution {
public:
    int rob(vector<int> &nums) {
        return subseqSum(nums);
    }

private:
    // max({sum(subseq) | subseq 是数组 nums 的不连续子序列})
    int subseqSum(const vector<int> &nums) {
        size_t n = nums.size();
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return nums[0];
        }
        if (n == 2) {
            return max(nums[0], nums[1]);
        }
        // dp[i] = max({sum(subseq) | subseq 是子数组 nums[0..i] 的不连续子序列})
        vector<int> dp(n);
        dp[0] = nums[0];
        dp[1] = max(nums[0], nums[1]);
        for (int i = 2; i < n; ++i) {
            // 包含 nums[i]
            int sp1 = dp[i - 2] + nums[i];
            // 不包含 nums[i]
            int sp2 = dp[i - 1];
            dp[i] = max(sp1, sp2);
        }
        return dp[n - 1];
    }
};
// https://leetcode.cn/submissions/detail/391484761/
```

```cpp
class Solution {
public:
    int rob(vector<int> &nums) {
        return subsequenceSum(nums);
    }

private:
    // 返回 max({sum(subsequence) | subsequence 是 nums 的不连续子序列})
    int subsequenceSum(const vector<int> &nums) {
        size_t n = nums.size();
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return nums[0];
        }
        if (n == 2) {
            return max(nums[0], nums[1]);
        }
        // dp[i] = max({sum(subsequence) | subsequence 是以 nums[i] 结尾的不连续子序列})
        vector<int> dp(n);
        dp[0] = nums[0];
        dp[1] = max(nums[0], nums[1]);
        int ans = max(dp[0], dp[1]);
        for (int i = 2; i < n; ++i) {
            int res = nums[i];
            for (int j = i - 2; j >= 0; --j) {
                res = max(res, dp[j] + nums[i]);
            }
            dp[i] = res;
            ans = max(ans, dp[i]);
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391485031/
```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```cpp
class Solution {
public:
    vector<int> rightSideView(TreeNode *root) {
        vector<int> ans;
        deque<TreeNode *> q;
        if (root != nullptr) {
            q.push_back(root);
        }
        while (!q.empty()) {
            ans.push_back(q.back()->val);
            size_t n = q.size();
            for (int i = 0; i < n; ++i) {
                TreeNode *x = q.front();
                q.pop_front();
                TreeNode *left = x->left;
                if (left != nullptr) {
                    q.push_back(left);
                }
                TreeNode *right = x->right;
                if (right != nullptr) {
                    q.push_back(right);
                }
            }
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391695336/
```

```cpp
class Solution {
public:
    vector<int> rightSideView(TreeNode *root) {
        vector<int> ans;
        queue<TreeNode *> q;
        if (root != nullptr) {
            q.push(root);
        }
        while (!q.empty()) {
            ans.push_back(q.front()->val);
            size_t n = q.size();
            for (int i = 0; i < n; ++i) {
                TreeNode *x = q.front();
                q.pop();
                if (x->right != nullptr) {
                    q.push(x->right);
                }
                if (x->left != nullptr) {
                    q.push(x->left);
                }
            }
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391695558/
```

```cpp
class Solution {
public:
    vector<int> rightSideView(const TreeNode *root) {
        dfs(root, 0);
        return ans;
    }

private:
    void dfs(const TreeNode *root, int depth) {
        if (root == nullptr) {
            return;
        }
        if (ans.size() == depth) {
            ans.push_back(root->val);
        }
        dfs(root->right, depth + 1);
        dfs(root->left, depth + 1);
    }

    vector<int> ans;
};
// https://leetcode.cn/submissions/detail/404386387/
```

```cpp
class Solution {
public:
    vector<int> rightSideView(const TreeNode *root) {
        dfs(root, 0);
        size_t n = map.size();
        vector<int> ans(n);
        for (int i = 0; i < n; ++i) {
            ans[i] = map[i];
        }
        return ans;
    }

private:
    void dfs(const TreeNode *root, int depth) {
        if (root == nullptr) {
            return;
        }
        map[depth] = root->val;
        dfs(root->left, depth + 1);
        dfs(root->right, depth + 1);
    }

    unordered_map<int, int> map;
};
// https://leetcode.cn/submissions/detail/441816935/
```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```cpp
class Solution {
public:
    int numIslands(vector<vector<char>> &grid) {
        int count = 0;
        for (int row = 0; row < grid.size(); ++row) {
            for (int col = 0; col < grid[0].size(); ++col) {
                if (grid[row][col] == LAND) {
                    floodFill(grid, row, col);
                    ++count;
                }
            }
        }
        return count;
    }

private:
    void floodFill(vector<vector<char>> &grid, int row, int col) {
        if (row < 0 || row >= grid.size() || col < 0 || col >= grid[0].size() || grid[row][col] == WATER) {
            return;
        }
        grid[row][col] = WATER;
        floodFill(grid, row, col + 1);
        floodFill(grid, row, col - 1);
        floodFill(grid, row + 1, col);
        floodFill(grid, row - 1, col);
    }

    static const char LAND = '1';
    static const char WATER = '0';
};
// https://leetcode.cn/submissions/detail/391539839/
```

## 203. 移除链表元素

<https://leetcode.cn/problems/remove-linked-list-elements/>

```cpp
class Solution {
public:
    ListNode *removeElements(ListNode *head, int val) {
        auto *dummyHead = new ListNode(-1, head);
        ListNode *ptr = dummyHead;
        while (ptr != nullptr && ptr->next != nullptr) {
            if (ptr->next->val == val) {
                ListNode *x = ptr->next;
                ptr->next = ptr->next->next;
                delete x;
            } else {
                ptr = ptr->next;
            }
        }
        head = dummyHead->next;
        delete dummyHead;
        return head;
    }
};
// https://leetcode.cn/submissions/detail/391584118/
```

## 206. 反转链表

<https://leetcode.cn/problems/reverse-linked-list/>

```cpp
class Solution {
public:
    ListNode *reverseList(ListNode *head) {
        ListNode *reverseHead = nullptr;
        while (head != nullptr) {
            ListNode *x = head->next;
            head->next = reverseHead;
            reverseHead = head;
            head = x;
        }
        return reverseHead;
    }
};
// https://leetcode.cn/submissions/detail/368458029/
```

```cpp
class Solution {
public:
    ListNode *reverseList(ListNode *head) {
        if (head == nullptr || head->next == nullptr) {
            return head;
        }
        ListNode *x = head->next;
        head->next = nullptr;
        ListNode *reverseHead = reverseList(x);
        x->next = head;
        return reverseHead;
    }
};
// https://leetcode.cn/submissions/detail/368457253/
```

```cpp
class Solution {
public:
    ListNode *reverseList(ListNode *head) {
        if (head == nullptr || head->next == nullptr) {
            return head;
        }
        stack<ListNode *> s;
        while (head != nullptr) {
            ListNode *next = head->next;
            head->next = nullptr;
            s.push(head);
            head = next;
        }
        ListNode *reverseHead = s.top();
        s.pop();
        ListNode *ptr = reverseHead;
        while (!s.empty()) {
            ptr->next = s.top();
            s.pop();
            ptr = ptr->next;
        }
        return reverseHead;
    }
};
// https://leetcode.cn/submissions/detail/391471805/
```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```cpp
class Solution {
public:
    bool canFinish(int numCourses, vector<vector<int>> &prerequisites) {
        vector<vector<int>> graph(numCourses);
        for (const auto &p: prerequisites) {
            int v = p[1], w = p[0];
            graph[v].push_back(w);
        }
        size_t n = graph.size();
        marked = vector<bool>(n);
        onStack = vector<bool>(n);
        for (int v = 0; v < n; ++v) {
            if (!marked[v]) {
                dfs(graph, v);
                if (hasCycle) {
                    break;
                }
            }
        }
        return !hasCycle;
    }

private:
    void dfs(const vector<vector<int>> &graph, int v) {
        onStack[v] = true;
        marked[v] = true;
        for (const auto &w: graph[v]) {
            if (!marked[w]) {
                dfs(graph, w);
            } else if (onStack[w]) {
                hasCycle = true;
                return;
            }
        }
        onStack[v] = false;
    }

    vector<bool> marked;
    vector<bool> onStack;
    bool hasCycle = false;
};
// https://leetcode.cn/submissions/detail/391447038/
```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```cpp
class Solution {
public:
    vector<int> findOrder(int numCourses, vector<vector<int>> &prerequisites) {
        if (canFinish(numCourses, prerequisites)) {
            return {postorder.rbegin(), postorder.rend()};
        }
        return {};
    }

private:
    bool canFinish(int numCourses, vector<vector<int>> &prerequisites) {
        vector<vector<int>> graph(numCourses);
        for (const auto &p: prerequisites) {
            int v = p[1], w = p[0];
            graph[v].push_back(w);
        }
        size_t n = graph.size();
        marked = vector<bool>(n);
        onStack = vector<bool>(n);
        for (int v = 0; v < n; ++v) {
            if (!marked[v]) {
                dfs(graph, v);
                if (hasCycle) {
                    break;
                }
            }
        }
        return !hasCycle;
    }

    void dfs(const vector<vector<int>> &graph, int v) {
        onStack[v] = true;
        marked[v] = true;
        for (const auto &w: graph[v]) {
            if (!marked[w]) {
                dfs(graph, w);
            } else if (onStack[w]) {
                hasCycle = true;
                return;
            }
        }
        postorder.push_back(v);
        onStack[v] = false;
    }

    vector<bool> marked;
    vector<bool> onStack;
    vector<int> postorder;
    bool hasCycle = false;
};
// https://leetcode.cn/submissions/detail/391445752/
```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```cpp
class Solution {
public:
    int rob(const vector<int> &nums) {
        int n = nums.size();
        if (n == 1) {
            return nums[0];
        }
        return max(subseqSum(nums, 0, n - 2), subseqSum(nums, 1, n - 1));
    }

private:
    // 返回 max({sum(subseq) | subseq 是子数组 nums[lo..hi] 的不连续子序列})
    int subseqSum(const vector<int> &nums, int lo, int hi) {
        int n = hi - lo + 1;
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return nums[lo];
        }
        if (n == 2) {
            return max(nums[lo], nums[lo + 1]);
        }
        // dp[i] = max({sum(subseq) | subseq 是子数组 nums[lo..lo+i] 的不连续子序列})
        vector<int> dp(n);
        dp[0] = nums[lo];
        dp[1] = max(nums[lo], nums[lo + 1]);
        for (int i = 2; i < n; ++i) {
            // 包含 nums[lo+i]
            int sp1 = dp[i - 2] + nums[lo + i];
            // 不包含 nums[lo+i]
            int sp2 = dp[i - 1];
            dp[i] = max(sp1, sp2);
        }
        return dp[n - 1];
    }
};
// https://leetcode.cn/submissions/detail/452708767/
```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```cpp
class Solution {
public:
    int findKthLargest(vector<int> &nums, int k) {
        return select(nums, nums.size() - k);
    }

private:
    // 数组 nums 从小到大排在第 rank 位的元素，排位从 0 开始计算，
    // 相当于有 rank 个元素小于该元素。
    int select(vector<int> &nums, int rank) {
        int lo = 0, hi = nums.size() - 1;
        while (lo < hi) {
            int j = partition(nums, lo, hi);
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

    int partition(vector<int> &nums, int lo, int hi) {
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
            swap(nums[i], nums[j]);
        }
        swap(nums[lo], nums[j]);
        return j;
    }
};
// https://leetcode.cn/submissions/detail/391552631/
```

```cpp
class Solution {
public:
    int findKthLargest(vector<int> &nums, int k) {
        priority_queue<int> max_pq(nums.begin(), nums.end());
        for (int i = 1; i <= k - 1; ++i) {
            max_pq.pop();
        }
        return max_pq.top();
    }
};
// https://leetcode.cn/submissions/detail/391551967/
```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```cpp
class Solution {
public:
    vector<vector<int>> combinationSum3(int k, int n) {
        backtrack(k, n, 0);
        return ans;
    }

private:
    // edge = 取 [1..9] 为值
    void backtrack(int k, int n, int edge) {
        if (path.size() == k && pathSum == n) {
            ans.push_back(path);
        } else if (path.size() < k && pathSum < n) {
            // 避免重复，从 edge + 1 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            while (++edge <= 9) {
                if (pathSum + edge <= n) {
                    pathSum += edge;
                    path.push_back(edge);
                    backtrack(k, n, edge);
                    pathSum -= edge;
                    path.pop_back();
                }
            }
        }
    }

    int pathSum = 0;
    vector<int> path; // 取 [1..9] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391648230/
```

```cpp
class Solution {
public:
    vector<vector<int>> combinationSum3(int k, int n) {
        dfs(k, n, 0);
        return ans;
    }

private:
    // vertex = 取 [1..9] 为值
    void dfs(int k, int n, int vertex) {
        if (vertex > 0) {
            pathSum += vertex;
            path.push_back(vertex);
        }
        if (path.size() == k && pathSum == n) {
            ans.push_back(path);
        } else if (path.size() < k && pathSum < n) {
            // 避免重复，从 vertex + 1 开始选择
            // 例如 [1->2] 和 [2->1] 是重复的
            int v = vertex;
            while (++v <= 9) {
                if (pathSum + v <= n) {
                    dfs(k, n, v);
                }
            }
        }
        if (vertex > 0) {
            pathSum -= vertex;
            path.pop_back();
        }
    }

    int pathSum = 0;
    vector<int> path; // 取 [1..9] 为元素
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391648558/
```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```cpp
class Solution {
public:
    int countNodes(TreeNode *root) {
        if (root == nullptr) {
            return 0;
        }
        int leftHeight = 0;
        TreeNode *ptr = root;
        while (ptr != nullptr) {
            ++leftHeight;
            ptr = ptr->left;
        }
        int rightHeight = 0;
        ptr = root;
        while (ptr != nullptr) {
            ++rightHeight;
            ptr = ptr->right;
        }
        if (leftHeight == rightHeight) {
            return (1 << leftHeight) - 1;
        }
        return 1 + countNodes(root->left) + countNodes(root->right);
    }
};
// https://leetcode.cn/submissions/detail/394183375/
```

```cpp
class Solution {
public:
    int countNodes(TreeNode *root) {
        if (root == nullptr) {
            return 0;
        }
        int leftHeight = 0;
        TreeNode *ptr = root;
        while (ptr != nullptr) {
            ++leftHeight;
            ptr = ptr->left;
        }
        int rightHeight = 0;
        ptr = root;
        while (ptr != nullptr) {
            ++rightHeight;
            ptr = ptr->right;
        }
        if (leftHeight == rightHeight) {
            return pow(2, leftHeight) - 1;
        }
        return 1 + countNodes(root->left) + countNodes(root->right);
    }
};
// https://leetcode.cn/submissions/detail/394184877/
```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```cpp
class MyStack {
public:
    MyStack() = default;

    void push(int x) {
        q.push(x);
        for (int i = 1; i < q.size(); ++i) {
            q.push(pop());
        }
    }

    int pop() {
        int x = q.front();
        q.pop();
        return x;
    }

    int top() {
        return q.front();
    }

    bool empty() {
        return q.empty();
    }

private:
    queue<int> q;
};
// https://leetcode.cn/submissions/detail/391689349/
```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```cpp
class Solution {
public:
    TreeNode *invertTree(TreeNode *root) {
        if (root == nullptr) {
            return nullptr;
        }
        TreeNode *left = invertTree(root->left);
        TreeNode *right = invertTree(root->right);
        root->left = right;
        root->right = left;
        return root;
    }
};
// https://leetcode.cn/submissions/detail/368818458/
```

```cpp
class Solution {
public:
    TreeNode *invertTree(TreeNode *root) {
        if (root == nullptr) {
            return root;
        }
        TreeNode *left = root->left;
        TreeNode *right = root->right;
        root->left = right;
        root->right = left;
        invertTree(left);
        invertTree(right);
        return root;
    }
};
// https://leetcode.cn/submissions/detail/391476173/
```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```cpp
class Solution {
public:
    int kthSmallest(TreeNode *root, int k) {
        return select(root, k - 1);
    }

private:
    int select(const TreeNode *root, int rank) {
        if (root == nullptr) {
            return -1;
        }
        int leftSize = size(root->left);
        if (rank < leftSize) {
            return select(root->left, rank);
        }
        if (leftSize < rank) {
            return select(root->right, rank - leftSize - 1);
        }
        return root->val;
    }

    int size(TreeNode *root) {
        if (root == nullptr) {
            return 0;
        }
        if (memo.count(root) == 0) {
            memo[root] = 1 + size(root->left) + size(root->right);
        }
        return memo[root];
    }

    unordered_map<TreeNode *, int> memo;
};
// https://leetcode.cn/submissions/detail/391659318/
```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```cpp
/**
 * -----------------------------| |-------------------------------
 * pop <- top Left Stack bottom | | bottom Right Stack top <- push
 * -----------------------------| |-------------------------------
 */
class MyQueue {
public:
    MyQueue() = default;

    void push(int x) {
        rightStack.push(x);
    }

    int pop() {
        if (leftStack.empty()) {
            move();
        }
        int x = leftStack.top();
        leftStack.pop();
        return x;
    }

    int peek() {
        if (leftStack.empty()) {
            move();
        }
        return leftStack.top();
    }

    bool empty() {
        return leftStack.empty() && rightStack.empty();
    }

private:
    void move() {
        while (!rightStack.empty()) {
            leftStack.push(rightStack.top());
            rightStack.pop();
        }
    }

    stack<int> leftStack;
    stack<int> rightStack;
};
// https://leetcode.cn/submissions/detail/391690927/
```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```cpp
class Solution {
public:
    bool isPalindrome(ListNode *head) {
        // 寻找链表的中点（偶数个节点时选择左侧），即前半部分链表的尾节点
        ListNode *slow = head;
        ListNode *fast = head;
        while (fast->next != nullptr && fast->next->next != nullptr) {
            slow = slow->next;
            fast = fast->next->next;
        }
        // 翻转后半部分链表
        ListNode *reverseHead = reverseList(slow->next);
        slow->next = nullptr;
        // 判断是否回文链表
        ListNode *left = head;
        ListNode *right = reverseHead;
        while (right != nullptr) {
            if (left->val != right->val) {
                return false;
            }
            left = left->next;
            right = right->next;
        }
        // 还原链表
        slow->next = reverseList(reverseHead);
        return true;
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
// https://leetcode.cn/submissions/detail/391561066/
```

```cpp
class Solution {
public:
    bool isPalindrome(ListNode *head) {
        stack<ListNode *> s;
        ListNode *ptr = head;
        while (ptr != nullptr) {
            s.push(ptr);
            ptr = ptr->next;
        }
        ptr = head;
        while (!s.empty()) {
            ListNode *x = s.top();
            s.pop();
            if (ptr->val != x->val) {
                return false;
            }
            ptr = ptr->next;
        }
        return true;
    }
};
// https://leetcode.cn/submissions/detail/391561549/
```

```cpp
class Solution {
public:
    bool isPalindrome(ListNode *head) {
        ptr = head;
        dfs(head);
        return ans;
    }

private:
    void dfs(const ListNode *head) {
        if (head == nullptr) {
            return;
        }
        dfs(head->next);
        if (head->val != ptr->val) {
            ans = false;
        }
        ptr = ptr->next;
    }

    bool ans = true;
    ListNode *ptr = nullptr;
};
// https://leetcode.cn/submissions/detail/366671977/
```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```cpp
class Solution {
public:
    TreeNode *lowestCommonAncestor(TreeNode *root, TreeNode *p, TreeNode *q) {
        // 保持 p < q
        if (p->val > q->val) {
            return lowestCommonAncestor(root, q, p);
        }
        if (p->val <= root->val && root->val <= q->val) {
            return root;
        }
        if (q->val < root->val) {
            return lowestCommonAncestor(root->left, p, q);
        }
        if (root->val < p->val) {
            return lowestCommonAncestor(root->right, p, q);
        }
        return nullptr;
    }
};
// https://leetcode.cn/submissions/detail/368725146/
```

```cpp
class Solution {
public:
    TreeNode *lowestCommonAncestor(TreeNode *root, TreeNode *p, TreeNode *q) {
        int minVal = min(p->val, q->val);
        int maxVal = max(p->val, q->val);
        int rootVal = root->val;
        if (minVal <= rootVal && rootVal <= maxVal) {
            return root;
        }
        if (maxVal < rootVal) {
            return lowestCommonAncestor(root->left, p, q);
        }
        if (rootVal < minVal) {
            return lowestCommonAncestor(root->right, p, q);
        }
        return nullptr;
    }
};
// https://leetcode.cn/submissions/detail/368724252/
```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```cpp
class Solution {
public:
    TreeNode *lowestCommonAncestor(TreeNode *root, TreeNode *p, TreeNode *q) {
        find(root, p, q);
        return lca;
    }

private:
    // 在子树中查找节点 p 或 q，递归过程中确定『最近公共祖先』。
    bool find(TreeNode *root, TreeNode *p, TreeNode *q) {
        if (root == nullptr) {
            return false;
        }
        if (root == p || root == q) {
            // 如果 lca(p,q) = p 或 q，则此处的 lca = root 是最终答案
            lca = root;
            return true;
        }
        bool left = find(root->left, p, q);
        bool right = find(root->right, p, q);
        // 否则返回到某祖先节点处的 lca = root 才是最终答案
        if (left && right) {
            lca = root;
        }
        return left || right;
    }

    TreeNode *lca = nullptr;
};
// https://leetcode.cn/submissions/detail/391605653/
```

```cpp
class Solution {
public:
    TreeNode *lowestCommonAncestor(TreeNode *root, TreeNode *p, TreeNode *q) {
        dfs(root);
        unordered_set<TreeNode *> visited;
        while (p != nullptr) {
            visited.insert(p);
            p = parent[p];
        }
        while (q != nullptr) {
            if (visited.count(q) == 1) {
                return q;
            }
            q = parent[q];
        }
        return root;
    }

private:
    void dfs(TreeNode *root) {
        TreeNode *left = root->left;
        if (left != nullptr) {
            parent[left] = root;
            dfs(left);
        }
        TreeNode *right = root->right;
        if (right != nullptr) {
            parent[right] = root;
            dfs(right);
        }
    }

    unordered_map<TreeNode *, TreeNode *> parent;
};
// https://leetcode.cn/submissions/detail/391606054/
```

## 237. 删除链表中的节点

<https://leetcode.cn/problems/delete-node-in-a-linked-list/>

```cpp
class Solution {
public:
    void deleteNode(ListNode *node) {
        node->val = node->next->val;
        ListNode *x = node->next;
        node->next = node->next->next;
        delete x;
    }
};
// https://leetcode.cn/submissions/detail/391472853/
```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```cpp
class Solution {
public:
    vector<int> maxSlidingWindow(vector<int> &nums, int k) {
        vector<int> ans;
        deque<int> q;
        for (int i = 0; i < nums.size(); ++i) {
            // nums[i] = 进入窗口的数字
            int x = nums[i];
            while (!q.empty() && q.back() < x) {
                q.pop_back();
            }
            q.push_back(x);
            if (i < k - 1) {
                continue;
            }
            // nums[i-k] = 退出窗口的数字
            if (i >= k && nums[i - k] == q.front()) {
                q.pop_front();
            }
            ans.push_back(q.front());
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/374204841/
```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```cpp
class Solution {
public:
    int minMeetingRooms(vector <vector<int>> &intervals) {
        int n = intervals.size();
        vector<int> begin(n);
        vector<int> end(n);
        for (int i = 0; i < n; i++) {
            begin[i] = intervals[i][0];
            end[i] = intervals[i][1];
        }
        std::sort(begin.begin(), begin.end());
        std::sort(end.begin(), end.end());
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
            ans = std::max(ans, count);
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/333896194/
```

## 283. 移动零

<https://leetcode.cn/problems/move-zeroes/>

```cpp
class Solution {
public:
    void moveZeroes(vector<int> &nums) {
        // [0..i-1] != 0
        // [i..j-1] == 0
        // [j..n-1] Scanning
        int i = 0, j = 0;
        size_t n = nums.size();
        while (j < n) {
            while (j < n && nums[j] == 0) {
                ++j;
            }
            if (j < n) {
                swap(nums[i++], nums[j++]);
            }
        }
    }
};
// https://leetcode.cn/submissions/detail/391447842/
```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```cpp
class Codec {
public:
    // Encodes a tree to a single string.
    string serialize(const TreeNode *root) {
        if (root == nullptr) {
            return "#";
        }
        string left = serialize(root->left);
        string right = serialize(root->right);
        return to_string(root->val) + "," + left + "," + right;
    }

    // Decodes your encoded data to tree.
    TreeNode *deserialize(const string &data) {
        deque<string> q;
        size_t n = data.size();
        int i = 0;
        while (i < n) {
            string str;
            while (i < n) {
                char ch = data[i++];
                if (ch == ',') {
                    break;
                }
                str += ch;
            }
            if (!str.empty()) {
                q.push_back(str);
            }
        }
        return buildTree(q);
    }

private:
    TreeNode *buildTree(deque<string> &q) {
        string s = q.front();
        q.pop_front();
        if (s == "#") {
            return nullptr;
        }
        auto *root = new TreeNode(stoi(s));
        root->left = buildTree(q);
        root->right = buildTree(q);
        return root;
    }
};
// https://leetcode.cn/submissions/detail/391713763/
```

```cpp
class Codec {
public:
    // Encodes a tree to a single string.
    string serialize(const TreeNode *root) {
        string data;
        dfs(root, data);
        return data;
    }

    // Decodes your encoded data to tree.
    TreeNode *deserialize(const string &data) {
        deque<string> q;
        size_t n = data.size();
        int i = 0;
        while (i < n) {
            string str;
            while (i < n) {
                char ch = data[i++];
                if (ch == ',') {
                    break;
                }
                str += ch;
            }
            if (!str.empty()) {
                q.push_back(str);
            }
        }
        return buildTree(q);
    }

private:
    void dfs(const TreeNode *root, string &data) {
        if (root == nullptr) {
            data += "#,";
            return;
        }
        data += (to_string(root->val) + ",");
        dfs(root->left, data);
        dfs(root->right, data);
    }

    TreeNode *buildTree(deque<string> &q) {
        string s = q.front();
        q.pop_front();
        if (s == "#") {
            return nullptr;
        }
        auto *root = new TreeNode(stoi(s));
        root->left = buildTree(q);
        root->right = buildTree(q);
        return root;
    }
};
// https://leetcode.cn/submissions/detail/391714681/
```

```cpp
class Codec {
public:
    // Encodes a tree to a single string.
    string serialize(const TreeNode *root) {
        ostringstream oss;
        dfs(root, oss);
        return oss.str();
    }

    // Decodes your encoded data to tree.
    TreeNode *deserialize(const string &data) {
        istringstream iss(data);
        return buildTree(iss);
    }

private:
    void dfs(const TreeNode *root, ostringstream &oss) {
        if (root == nullptr) {
            oss << '#' << ' ';
            return;
        }
        oss << root->val << ' ';
        dfs(root->left, oss);
        dfs(root->right, oss);
    }

    TreeNode *buildTree(istringstream &iss) {
        string val;
        iss >> val;
        if (val == "#") {
            return nullptr;
        }
        auto *root = new TreeNode(stoi(val));
        root->left = buildTree(iss);
        root->right = buildTree(iss);
        return root;
    }
};
// https://leetcode.cn/submissions/detail/391715648/
```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```cpp
class Solution {
public:
    int lengthOfLIS(vector<int> &nums) {
        size_t n = nums.size();
        // dp[i] = max({length(subseq) | subseq 是以 nums[i] 结尾的严格递增子序列})
        vector<int> dp(n, 1);
        int ans = dp[0];
        for (int i = 1; i < n; ++i) {
            int res = 1;
            for (int j = i - 1; j >= 0; --j) {
                if (nums[j] < nums[i]) {
                    res = max(res, dp[j] + 1);
                }
            }
            dp[i] = res;
            ans = max(ans, dp[i]);
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391532945/
```

```cpp
class Solution {
public:
    int lengthOfLIS(vector<int> &nums) {
        size_t n = nums.size();
        memo = vector<int>(n, -1);
        int ans = 0;
        for (int i = 0; i < n; ++i) {
            ans = max(ans, lengthOfLIS(nums, i));
        }
        return ans;
    }

private:
    // max({length(subseq) | subseq 是以 nums[i] 结尾的严格递增子序列})
    int lengthOfLIS(const vector<int> &nums, int i) {
        if (memo[i] == -1) {
            int res = 1;
            for (int j = i - 1; j >= 0; --j) {
                int sp = lengthOfLIS(nums, j);
                if (nums[j] < nums[i]) {
                    res = max(res, sp + 1);
                }
            }
            memo[i] = res;
        }
        return memo[i];
    }

    vector<int> memo;
};
// https://leetcode.cn/submissions/detail/391533856/
```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```cpp
class NumArray {
public:
    explicit NumArray(const vector<int> &nums) {
        sums = vector<int>(nums);
        for (int i = 1; i < nums.size(); ++i) {
            sums[i] = sums[i - 1] + nums[i];
        }
    }

    int sumRange(int left, int right) {
        if (left == 0) {
            return sums[right];
        }
        return sums[right] - sums[left - 1];
    }

private:
    vector<int> sums;
};
// https://leetcode.cn/submissions/detail/406982246/
```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```cpp
class Solution {
public:
    int maxProfit(vector<int> &prices) {
        size_t n = prices.size();
        if (n <= 1) {
            return 0;
        }
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        vector<vector<int>> dp(n, vector<int>(2));
        dp[0][0] = 0;
        dp[0][1] = -prices[0];
        dp[1][0] = max(dp[0][0], dp[0][1] + prices[1]);
        dp[1][1] = max(dp[0][0] - prices[1], dp[0][1]);
        for (int i = 2; i < n; ++i) {
            // dp[i - 1][0]             >= dp[i - 2][0] >= p[i - 2][0] - prices[i]
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = max(dp[i - 2][0] - prices[i], dp[i - 1][1]);
        }
        return dp[n - 1][0];
    }
};
// https://leetcode.cn/submissions/detail/391486031/
```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```cpp
struct Pair {
    int val;
    int idx;

    Pair(int v, int i) : val{v}, idx{i} {}
};

class Solution {
public:
    vector<int> countSmaller(vector<int> &nums) {
        int n = nums.size();
        counts = vector<int>(n);
        vector<Pair> pairs;
        for (int i = 0; i < n; ++i) {
            pairs.emplace_back(nums[i], i);
        }
        vector<Pair> aux(pairs);
        sort(pairs, aux, 0, n - 1);
        return counts;
    }

private:
    void sort(vector<Pair> &pairs, vector<Pair> &aux, int lo, int hi) {
        if (lo >= hi) {
            return;
        }
        int mid = lo + (hi - lo) / 2;
        sort(pairs, aux, lo, mid);
        sort(pairs, aux, mid + 1, hi);
        merge(pairs, aux, lo, mid, hi);
    }

    void merge(vector<Pair> &paris, vector<Pair> &aux, int lo, int mid, int hi) {
        for (int k = lo; k <= hi; ++k) {
            aux[k] = paris[k];
        }
        int i = lo, j = mid + 1;
        for (int k = lo; k <= hi; ++k) {
            if (i > mid || (j <= hi && aux[j].val < aux[i].val)) {
                paris[k] = aux[j++];
            } else {
                // aux[mid+1..j) < aux[i]
                counts[aux[i].idx] += (j - mid - 1);
                paris[k] = aux[i++];
            }
        }
    }

    vector<int> counts;
};
// https://leetcode.cn/submissions/detail/391686642/
```

```cpp
struct Pair {
    int val;
    int idx;

    Pair(int v, int i) : val{v}, idx{i} {}
};

class Solution {
public:
    vector<int> countSmaller(vector<int> &nums) {
        int n = nums.size();
        counts = vector<int>(n);
        vector<Pair> pairs;
        int idx = 0;
        transform(nums.cbegin(), nums.cend(),
                  back_inserter(pairs),
                  [&idx](const int &val) { return Pair(val, idx++); });
        vector<Pair> aux(pairs);
        sort(pairs, aux, 0, n - 1);
        return counts;
    }

private:
    void sort(vector<Pair> &pairs, vector<Pair> &aux, int lo, int hi) {
        if (lo >= hi) {
            return;
        }
        int mid = lo + (hi - lo) / 2;
        sort(pairs, aux, lo, mid);
        sort(pairs, aux, mid + 1, hi);
        merge(pairs, aux, lo, mid, hi);
    }

    void merge(vector<Pair> &paris, vector<Pair> &aux, int lo, int mid, int hi) {
        for (int k = lo; k <= hi; ++k) {
            aux[k] = paris[k];
        }
        int i = lo, j = mid + 1;
        for (int k = lo; k <= hi; ++k) {
            if (i > mid || (j <= hi && aux[j].val < aux[i].val)) {
                paris[k] = aux[j++];
            } else {
                // aux[mid+1..j) < aux[i]
                counts[aux[i].idx] += (j - mid - 1);
                paris[k] = aux[i++];
            }
        }
    }

    vector<int> counts;
};
// https://leetcode.cn/submissions/detail/391687437/
```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```cpp
class Solution {
public:
    int coinChange(vector<int> &coins, int amount) {
        // dp[i] = 凑成总金额 i 所需的最少的硬币个数
        vector<int> dp(amount + 1);
        for (int i = 1; i <= amount; ++i) {
            int res = INT_MAX;
            // c       = 选择放入的硬币
            // i-c     = 剩余总金额
            // dp[i-c] = 凑成剩余总金额所需的最少的硬币个数
            for (const auto &c: coins) {
                int x = i - c;
                if (x >= 0 && dp[x] != -1) {
                    res = min(res, dp[x] + 1);
                }
            }
            dp[i] = (res == INT_MAX ? -1 : res);
        }
        return dp[amount];
    }
};
// https://leetcode.cn/submissions/detail/391483145/
```

```cpp
class Solution {
public:
    int coinChange(vector<int> &coins, int amount) {
        if (amount < 0) {
            return -1;
        }
        if (amount == 0) {
            return 0;
        }
        if (memo.count(amount) == 0) {
            int res = INT_MAX;
            // c = 选择放入的硬币
            for (const auto &c: coins) {
                // amount-c = 剩余总金额
                // sp       = 凑成剩余总金额所需的最少的硬币个数
                int sp = coinChange(coins, amount - c);
                if (sp != -1) {
                    res = min(res, sp + 1);
                }
            }
            memo[amount] = (res == INT_MAX ? -1 : res);
        }
        return memo[amount];
    }

private:
    unordered_map<int, int> memo;
};
// https://leetcode.cn/submissions/detail/391483772/
```

```cpp
class Solution {
public:
    int coinChange(vector<int> &coins, int amount) {
        size_t n = coins.size();
        // dp[i][j] = 使用硬币 coins[0..i-1] 凑成总金额 j 所需的最少的硬币个数
        vector<vector<int>> dp(n + 1, vector<int>(amount + 1));
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
                    int res = INT_MAX;
                    if (sp1 != -1) {
                        res = min(res, sp1);
                    }
                    if (sp2 != -1) {
                        res = min(res, sp2 + 1);
                    }
                    dp[i][j] = (res == INT_MAX ? -1 : res);
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
};
// https://leetcode.cn/submissions/detail/391483435/
```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```cpp
class Solution {
public:
    // 在二叉树 root，能盗取的最高金额
    int rob(TreeNode *root) {
        if (root == nullptr) {
            return 0;
        }
        if (memo.count(root) == 0) {
            // 不偷 root
            int sp1 = rob(root->left) + rob(root->right);
            // 偷 root
            int sp2 = root->val;
            if (root->left != nullptr) {
                sp2 += rob(root->left->left) + rob(root->left->right);
            }
            if (root->right != nullptr) {
                sp2 += rob(root->right->left) + rob(root->right->right);
            }
            memo[root] = max(sp1, sp2);
        }
        return memo[root];
    }

private:
    unordered_map<TreeNode *, int> memo;
};
// https://leetcode.cn/submissions/detail/374765084/
```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```cpp
class Solution {
public:
    void reverseString(vector<char> &s) {
        int i = 0, j = s.size() - 1;
        while (i < j) {
            swap(s[i++], s[j--]);
        }
    }
};
// https://leetcode.cn/submissions/detail/368847230/
```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```cpp
// TODO
```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```cpp
class Solution {
public:
    string decodeString(const string &s) {
        stack<string> stk;
        int i = 0;
        size_t n = s.size();
        while (i < n) {
            string digits;
            while (i < n && isdigit(s[i])) {
                digits += s[i++];
            }
            if (!digits.empty()) {
                stk.push(digits);
            }
            while (i < n && s[i] == '[') {
                stk.emplace("[");
                ++i;
            }
            string letters;
            while (i < n && isalpha(s[i])) {
                letters += s[i++];
            }
            if (!letters.empty()) {
                stk.push(letters);
            }
            while (i < n && s[i] == ']') {
                letters = "";
                while (!stk.empty()) {
                    string str = stk.top();
                    stk.pop();
                    if (str == "[") {
                        break;
                    }
                    letters.insert(0, str);
                }
                digits = stk.top();
                stk.pop();
                string rep = repeatedString(letters, stoi(digits));
                stk.push(rep);
                ++i;
            }
        }
        string ans;
        while (!stk.empty()) {
            ans.insert(0, stk.top());
            stk.pop();
        }
        return ans;
    }

private:
    string repeatedString(const string &s, int k) {
        string res;
        for (int i = 1; i <= k; ++i) {
            res += s;
        }
        return res;
    }
};
// https://leetcode.cn/submissions/detail/391709901/
```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```cpp
class Solution {
public:
    bool canPartition(vector<int> &nums) {
        int sum = 0;
        for (const auto &x: nums) {
            sum += x;
        }
        if (sum % 2 == 1) {
            return false;
        }
        return hasSubsetSum(nums, sum / 2);
    }

private:
    // 数组 nums 是否存在和为 sum 的子集
    bool hasSubsetSum(const vector<int> &nums, int sum) {
        size_t n = nums.size();
        // dp[i][j] = 子数组 nums[0..i-1] 是否存在和为 j 的子集
        vector<vector<bool>> dp(n + 1, vector<bool>(sum + 1));
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
                    bool sp1 = dp[i - 1][j];
                    // 包含 x
                    // 当 i >= 1, j = x 时，dp[i - 1][j - x] = dp[i - 1][0]
                    // 因为存在子集 {x} 的和为 j，
                    // 所以定义 dp[i][0] = true (i >= 0)
                    bool sp2 = dp[i - 1][j - x];
                    dp[i][j] = sp1 || sp2;
                } else {
                    dp[i][j] = dp[i - 1][j];
                }
            }
        }
        return dp[n][sum];
    }
};
// https://leetcode.cn/submissions/detail/391548959/
```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```cpp
class Solution {
public:
    int eraseOverlapIntervals(vector<vector<int>> &intervals) {
        return intervals.size() - maxNonOverlappingIntervals(intervals);
    }

private:
    // 返回区间数组 intervals 无重叠区间的最大数量
    static int maxNonOverlappingIntervals(vector<vector<int>> &intervals) {
        // 按区间终点升序排列
        sort(intervals.begin(), intervals.end(),
             [](const vector<int> &a, const vector<int> &b) {
                 return a[1] < b[1];
             });
        // 最后一个不重叠区间的终点
        long lastEnd = intervals[0][1];
        int count = 1;
        for (int i = 1; i < intervals.size(); ++i) {
            int start = intervals[i][0];
            int end = intervals[i][1];
            if (start >= lastEnd) {
                ++count;
                lastEnd = end;
            }
        }
        return count;
    }
};
// https://leetcode.cn/submissions/detail/456430545/
```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```cpp
class Solution {
public:
    vector<int> findAnagrams(string s, string p) {
        unordered_map<char, int> need, window;
        for (const auto &c: p) {
            ++need[c];
        }
        vector<int> ans;
        int valid = 0;
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        int left = 0, right = 0;
        while (right < s.size()) {
            char add = s[right++];
            if (need.count(add) == 1) {
                if (++window[add] == need[add]) {
                    ++valid;
                }
            }
            if (valid == need.size()) {
                while (left < right - p.size()) {
                    char del = s[left++];
                    if (need.count(del) == 1) {
                        if (window[del] == need[del]) {
                            --valid;
                        }
                        --window[del];
                    }
                }
            }
            if (valid == need.size()) {
                ans.push_back(left);
            }
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391685413/
```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```cpp
class Solution {
public:
    ListNode *addTwoNumbers(ListNode *l1, ListNode *l2) {
        l1 = reverseList(l1);
        l2 = reverseList(l2);
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
        reverseList(l1);
        reverseList(l2);
        return reverseList(head);
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
// https://leetcode.cn/submissions/detail/391582373/
```

```cpp
class Solution {
public:
    ListNode *addTwoNumbers(ListNode *l1, ListNode *l2) {
        stack<ListNode *> s1;
        stack<ListNode *> s2;
        while (l1 != nullptr || l2 != nullptr) {
            if (l1 != nullptr) {
                s1.push(l1);
                l1 = l1->next;
            }
            if (l2 != nullptr) {
                s2.push(l2);
                l2 = l2->next;
            }
        }
        int carry = 0;
        ListNode *first = nullptr;
        while (!s1.empty() || !s2.empty() || carry > 0) {
            int sum = carry;
            if (!s1.empty()) {
                sum += s1.top()->val;
                s1.pop();
            }
            if (!s2.empty()) {
                sum += s2.top()->val;
                s2.pop();
            }
            ListNode *x = first;
            first = new ListNode(sum % 10);
            first->next = x;
            carry = sum / 10;
        }
        return first;
    }
};
// https://leetcode.cn/submissions/detail/391582767/
```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```cpp
class Solution {
public:
    TreeNode *deleteNode(TreeNode *root, int key) {
        if (root == nullptr) {
            return nullptr;
        }
        if (key < root->val) {
            root->left = deleteNode(root->left, key);
        } else if (root->val < key) {
            root->right = deleteNode(root->right, key);
        } else {
            if (root->left == nullptr) {
                TreeNode *right = root->right;
                delete root;
                return right;
            }
            if (root->right == nullptr) {
                TreeNode *left = root->left;
                delete root;
                return left;
            }
            TreeNode *x = root;
            root = deleteMin(x->right);
            root->right = x->right;
            root->left = x->left;
            delete x;
        }
        return root;
    }

private:
    // 删除并返回二叉搜索树 root 的最小节点
    TreeNode *deleteMin(TreeNode *&root) {
        if (root->left == nullptr) {
            TreeNode *x = root;
            root = root->right;
            return x;
        }
        return deleteMin(root->left);
    }
};
// https://leetcode.cn/submissions/detail/391482648/
```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```cpp
class Solution {
public:
    int findMinArrowShots(vector<vector<int>> &points) {
        return maxNonOverlappingIntervals(points);
    }

private:
    // 返回区间数组 intervals 无重叠区间的最大数量
    static int maxNonOverlappingIntervals(vector<vector<int>> &intervals) {
        // 按区间终点升序排列
        sort(intervals.begin(), intervals.end(),
             [](const vector<int> &a, const vector<int> &b) {
                 return a[1] < b[1];
             });
        // 最后一个不重叠区间的终点
        long lastEnd = intervals[0][1];
        int count = 1;
        for (int i = 1; i < intervals.size(); ++i) {
            int start = intervals[i][0];
            int end = intervals[i][1];
            if (start > lastEnd) {
                ++count;
                lastEnd = end;
            }
        }
        return count;
    }
};
// https://leetcode.cn/submissions/detail/456429717/
```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```cpp
struct MyListNode {
    int key, val, freq;
    MyListNode *prev;
    MyListNode *next;

    MyListNode(int k, int v, int f) : key{k}, val{v}, freq{f}, prev{nullptr}, next{nullptr} {}
};

class MyDoublyLinkedList {
public:
    MyDoublyLinkedList() : first{nullptr}, last{nullptr}, n{0} {}

    ~MyDoublyLinkedList() {
        while (!empty()) {
            removeFirst();
        }
    }

    void addLast(MyListNode *newNode) {
        if (n == 0) {
            first = newNode;
            last = newNode;
        } else {
            last->next = newNode;
            newNode->prev = last;
            last = newNode;
        }
        ++n;
    }

    void removeFirst() {
        MyListNode *oldFirst = first;
        if (n == 1) {
            first = nullptr;
            last = nullptr;
        } else {
            first = first->next;
            first->prev = nullptr;
        }
        delete oldFirst;
        --n;
    }

    void removeLast() {
        MyListNode *oldLast = last;
        if (n == 1) {
            first = nullptr;
            last = nullptr;
        } else {
            last = last->prev;
            last->next = nullptr;
        }
        delete oldLast;
        --n;
    }

    void remove(MyListNode *delNode) {
        if (delNode == first) {
            removeFirst();
        } else if (delNode == last) {
            removeLast();
        } else {
            delNode->prev->next = delNode->next;
            delNode->next->prev = delNode->prev;
            delete delNode;
            --n;
        }
    }

    const MyListNode *getFirst() const {
        return first;
    }

    bool empty() const {
        return first == nullptr;
    }

private:
    MyListNode *first;
    MyListNode *last;
    int n;
};

class LFUCache {
public:
    explicit LFUCache(int capacity) {
        this->capacity = capacity;
    }

    int get(int key) {
        if (contains(key)) {
            return touchCache(key, INT_MIN);
        }
        return -1;
    }

    void put(int key, int value) {
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

private:
    bool contains(int key) const {
        return keyToNode.count(key) == 1;
    }

    bool full() const {
        return keyToNode.size() == capacity;
    }

    void addCache(int key, int val) {
        auto *newNode = new MyListNode(key, val, 1);
        keyToNode[key] = newNode;
        freqToList[1].addLast(newNode);
        minFreq = 1;
    }

    void removeCache() {
        auto &minFreqList = freqToList[minFreq];
        int delKey = minFreqList.getFirst()->key;
        keyToNode.erase(delKey);
        minFreqList.removeFirst();
        if (minFreqList.empty()) {
            freqToList.erase(minFreq);
        }
    }

    int touchCache(int key, int val) {
        MyListNode *oldNode = keyToNode[key];
        int newVal = oldNode->val;
        if (val != INT_MIN) {
            newVal = val;
        }
        int oldFreq = oldNode->freq;
        int newFreq = oldFreq + 1;
        keyToNode.erase(key);
        auto &oldFreqList = freqToList[oldFreq];
        oldFreqList.remove(oldNode);
        if (oldFreqList.empty()) {
            freqToList.erase(oldFreq);
            if (minFreq == oldFreq) {
                minFreq = newFreq;
            }
        }
        auto *newNode = new MyListNode(key, newVal, newFreq);
        keyToNode[key] = newNode;
        auto &newFreqList = freqToList[newFreq];
        newFreqList.addLast(newNode);
        return newVal;
    }

    int capacity;
    int minFreq{};
    unordered_map<int, MyListNode *> keyToNode;
    unordered_map<int, MyDoublyLinkedList> freqToList;
};
// https://leetcode.cn/submissions/detail/441743799/
```

```cpp
class LFUCache {
public:
    explicit LFUCache(int capacity) {
        this->capacity = capacity;
    }

    int get(int key) {
        if (contains(key)) {
            return touchCache(key, INT_MIN);
        }
        return -1;
    }

    void put(int key, int value) {
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

private:
    bool contains(int key) {
        return keyToVal.count(key) == 1;
    }

    bool full() {
        return keyToVal.size() == capacity;
    }

    void addCache(int key, int val) {
        keyToVal[key] = val;
        keyToFreq[key] = 1;
        auto &list = freqToKeyList[1];
        list.push_back(key);
        keyToListIter[key] = prev(list.end());
        minFreq = 1;
    }

    void removeCache() {
        auto &list = freqToKeyList[minFreq];
        int key = list.front();
        keyToVal.erase(key);
        keyToFreq.erase(key);
        keyToListIter.erase(key);
        list.pop_front();
        if (list.empty()) {
            freqToKeyList.erase(minFreq);
        }
    }

    int touchCache(int key, int val) {
        if (val != INT_MIN) {
            keyToVal[key] = val;
        }
        int oldFreq = keyToFreq[key];
        int newFreq = oldFreq + 1;
        keyToFreq[key] = newFreq;
        auto oldListIter = keyToListIter[key];
        auto &oldFreqList = freqToKeyList[oldFreq];
        oldFreqList.erase(oldListIter);
        if (oldFreqList.empty()) {
            freqToKeyList.erase(oldFreq);
            if (minFreq == oldFreq) {
                minFreq = newFreq;
            }
        }
        auto &newFreqList = freqToKeyList[newFreq];
        newFreqList.push_back(key);
        auto newListIter = prev(newFreqList.end());
        keyToListIter[key] = newListIter;
        return keyToVal[key];
    }

    int capacity;
    int minFreq{};
    unordered_map<int, int> keyToVal;
    unordered_map<int, int> keyToFreq;
    unordered_map<int, list<int>> freqToKeyList;
    unordered_map<int, list<int>::iterator> keyToListIter;
};
// https://leetcode.cn/submissions/detail/391599098/
```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```cpp
class Solution {
public:
    int reversePairs(vector<int> &nums) {
        vector<int> aux(nums);
        sort(nums, 0, nums.size() - 1, aux);
        return ans;
    }

private:
    void sort(vector<int> &nums, int lo, int hi, vector<int> &aux) {
        if (lo >= hi) {
            return;
        }
        int mid = lo + (hi - lo) / 2;
        sort(nums, lo, mid, aux);
        sort(nums, mid + 1, hi, aux);
        merge(nums, lo, mid, hi, aux);
    }

    void merge(vector<int> &nums, int lo, int mid, int hi, vector<int> &aux) {
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

    int countReversePairs(const vector<int> &nums, int lo, int mid, int hi) {
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

    bool isReversePair(const vector<int> &nums, int i, int j) {
        return i < j && (long) nums[i] > (long) 2 * nums[j];
    }

    int ans = 0;
};
// https://leetcode.cn/submissions/detail/391554378/
```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```cpp
class Solution {
public:
    int findTargetSumWays(vector<int> &nums, int target) {
        // sum(A) - sum(B) = target
        // sum(A) = target + sum(B)
        // sum(A) + sum(A) = target + sum(B) + sum(A)
        // 2 * sum(A) = target + sum(nums)
        // sum(A) = (target + sum(nums)) / 2
        // 问题转化为：数组 nums 中存在几个子集 A
        // 使得 A 中元素的和为 (target + sum(nums)) / 2
        int sum = accumulate(nums.begin(), nums.end(), 0);
        if (abs(target) > sum || (sum + target) % 2 == 1) {
            return 0;
        }
        return numSubsetSum(nums, (sum + target) / 2);
    }

private:
    // 数组 nums 和为 sum 的子集的数目，其中 nums[i] >= 0, sum >= 0
    int numSubsetSum(const vector<int> &nums, int sum) {
        size_t n = nums.size();
        // dp[i][j] = 子数组 nums[0..i-1] 和为 j 的子集的数目
        vector<vector<int>> dp(n + 1, vector<int>(sum + 1));
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
};
// https://leetcode.cn/submissions/detail/391606926/
```

```cpp
class Solution {
public:
    int findTargetSumWays(vector<int> &nums, int target) {
        int sum = accumulate(nums.begin(), nums.end(), 0);
        if (abs(target) > sum) {
            return 0;
        }
        return findTargetSumWays(nums, nums.size() - 1, target);
    }

private:
    // 子数组 nums[0..i] 目标和为 target 的不同表达式的数目
    int findTargetSumWays(const vector<int> &nums, int i, int target) {
        if (i < 0) {
            return target == 0 ? 1 : 0;
        }
        string key = to_string(i) + "," + to_string(target);
        if (memo.count(key) == 0) {
            int x = nums[i];
            // x 前添加 + 号
            // sum(nums[0..i-1]) = target - x
            int sp1 = findTargetSumWays(nums, i - 1, target - x);
            // x 前添加 - 号
            // sum(nums[0..i-1]) = target + x
            int sp2 = findTargetSumWays(nums, i - 1, target + x);
            memo[key] = sp1 + sp2;
        }
        return memo[key];
    }

    unordered_map<string, int> memo;
};
// https://leetcode.cn/submissions/detail/391608658/
```

```cpp
class Solution {
public:
    int findTargetSumWays(vector<int> &nums, int target) {
        int sum = accumulate(nums.begin(), nums.end(), 0);
        if (abs(target) > sum) {
            return 0;
        }
        return findTargetSumWays(nums, 0, target);
    }

private:
    // 子数组 nums[i..n-1] 目标和为 target 的不同表达式的数目
    int findTargetSumWays(const vector<int> &nums, int i, int target) {
        if (i == nums.size()) {
            return target == 0 ? 1 : 0;
        }
        string key = to_string(i) + "," + to_string(target);
        if (memo.count(key) == 0) {
            int x = nums[i];
            // x 前添加 + 号
            // sum(nums[i+1..n-1]) = target - x
            int sp1 = findTargetSumWays(nums, i + 1, target - x);
            // x 前添加 - 号
            // sum(nums[i+1..n-1]) = target + x
            int sp2 = findTargetSumWays(nums, i + 1, target + x);
            memo[key] = sp1 + sp2;
        }
        return memo[key];
    }

    unordered_map<string, int> memo;
};
// https://leetcode.cn/submissions/detail/391608964/
```

```cpp
class Solution {
public:
    int findTargetSumWays(vector<int> &nums, int target) {
        int sum = accumulate(nums.begin(), nums.end(), 0);
        if (abs(target) > sum) {
            return 0;
        }
        backtrack(nums, target, -1);
        return ans;
    }

private:
    // level = 取数组 nums 的索引为值
    void backtrack(vector<int> &nums, int target, int level) {
        if (level == nums.size() - 1) {
            if (pathSum == target) {
                ++ans;
            }
            return;
        }
        int x = nums[level + 1];
        // edge = +, -
        // 添加 + 号
        pathSum += x;
        backtrack(nums, target, level + 1);
        pathSum -= x;
        // 添加 - 号
        pathSum -= x;
        backtrack(nums, target, level + 1);
        pathSum += x;
    }

    int pathSum = 0;
    int ans = 0;
};
// https://leetcode.cn/submissions/detail/391607747/
```

```cpp
class Solution {
public:
    int findTargetSumWays(vector<int> &nums, int target) {
        int sum = accumulate(nums.begin(), nums.end(), 0);
        if (abs(target) > sum) {
            return 0;
        }
        dfs(nums, target, -1, 0);
        return ans;
    }

private:
    // level  = 取数组 nums 的索引为值
    // vertex = 1, -1
    void dfs(vector<int> &nums, int target, int level, int vertex) {
        if (level >= 0) {
            pathSum += nums[level] * vertex;
        }
        if (level == nums.size() - 1) {
            if (pathSum == target) {
                ++ans;
            }
        } else {
            dfs(nums, target, level + 1, 1);
            dfs(nums, target, level + 1, -1);
        }
        if (level >= 0) {
            pathSum -= nums[level] * vertex;
        }
    }

    int pathSum = 0;
    int ans = 0;
};
// 超出时间限制
```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```cpp
class Solution {
public:
    vector<int> nextGreaterElement(vector<int> &nums1, vector<int> &nums2) {
        vector<int> greater = nextGreaterElement(nums2);
        unordered_map<int, int> valToGreater;
        for (int i = 0; i < nums2.size(); ++i) {
            valToGreater[nums2[i]] = greater[i];
        }
        size_t n1 = nums1.size();
        vector<int> ans(n1);
        for (int i = 0; i < n1; ++i) {
            ans[i] = valToGreater[nums1[i]];
        }
        return ans;
    }

private:
    vector<int> nextGreaterElement(const vector<int> &nums) {
        int n = nums.size();
        vector<int> res(n);
        stack<int> s;
        for (int i = n - 1; i >= 0; --i) {
            int x = nums[i];
            while (!s.empty() && s.top() < x) {
                s.pop();
            }
            res[i] = s.empty() ? -1 : s.top();
            s.push(x);
        }
        return res;
    }
};
// https://leetcode.cn/submissions/detail/391664168/
```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```cpp
class Solution {
public:
    vector<int> nextGreaterElements(vector<int> &nums) {
        int n = nums.size();
        vector<int> ans(n);
        stack<int> s;
        for (int i = 2 * n - 1; i >= 0; --i) {
            int k = i % n;
            int x = nums[k];
            while (!s.empty() && s.top() <= x) {
                s.pop();
            }
            ans[k] = s.empty() ? -1 : s.top();
            s.push(x);
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391694869/
```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```cpp
class Solution {
public:
    int fib(int n) {
        if (n == 0) {
            return 0;
        }
        if (n == 1) {
            return 1;
        }
        vector<int> dp(n + 1);
        dp[0] = 0;
        dp[1] = 1;
        for (int i = 2; i <= n; ++i) {
            dp[i] = dp[i - 1] + dp[i - 2];
        }
        return dp[n];
    }
};
// https://leetcode.cn/submissions/detail/391560406/
```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```cpp
class Solution {
public:
    int longestPalindromeSubseq(const string &s) {
        int n = s.size();
        // dp[i][j] = 子串 s[i..j] 的最长回文子序列的长度
        vector<vector<int>> dp(n, vector<int>(n));
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
        // 遍历上三角形
        for (int i = n - 2; i >= 0; --i) {
            for (int j = i + 1; j < n; ++j) {
                if (s[i] == s[j]) {
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
                    dp[i][j] = max(sp1, sp2);
                }
            }
        }
        return dp[0][n - 1];
    }
};
// https://leetcode.cn/submissions/detail/391711096/
```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```cpp
class Solution {
public:
    int change(int amount, vector<int> &coins) {
        size_t n = coins.size();
        // dp[i][j] = 使用硬币 coins[0..i-1] 凑成总金额 j 的组合数
        vector<vector<int>> dp(n + 1, vector<int>(amount + 1));
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
};
// https://leetcode.cn/submissions/detail/391484077/
```

```cpp
class Solution {
public:
    int change(int amount, vector<int> &coins) {
        int n = coins.size();
        memo = vector<vector<int>>(amount + 1, vector<int>(n + 1, -1));
        return change(amount, coins, n - 1);
    }

private:
    // 使用硬币 coins[0..i] 凑成总金额 amount 的组合数
    int change(int amount, const vector<int> &coins, int i) {
        if (amount < 0 || i < 0) {
            return 0;
        }
        if (amount == 0) {
            return 1;
        }
        if (memo[amount][i] == -1) {
            // 包含 >= 1 个硬币 coins[i]
            int sp1 = change(amount - coins[i], coins, i);
            // 包含 0 个硬币 coins[i]
            int sp2 = change(amount, coins, i - 1);
            memo[amount][i] = sp1 + sp2;
        }
        return memo[amount][i];
    }

    vector<vector<int>> memo;
};
// https://leetcode.cn/submissions/detail/391544723/
```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```cpp
class Solution {
public:
    TreeNode *convertBST(TreeNode *root) {
        dfs(root);
        return root;
    }

private:
    void dfs(TreeNode *root) {
        if (root == nullptr) {
            return;
        }
        dfs(root->right);
        sum += root->val;
        root->val = sum;
        dfs(root->left);
    }

    int sum = 0;
};
// https://leetcode.cn/submissions/detail/368559929/
```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```cpp
// rootLP = 穿过根节点的最长路径（左右子树的最大深度之和）
// rootLP(root) = maxDepth(root.left) + maxDepth(root.right)
// diameter = 所有子树的 rootLP 的最大值
// diameter(root) = max({ rootLP(subtree) | subtree 是 root 的任意子树 })
class Solution {
public:
    int diameterOfBinaryTree(TreeNode *root) {
        maxDepth(root);
        return diameter;
    }

private:
    int maxDepth(TreeNode *root) {
        if (root == nullptr) {
            return 0;
        }
        int left = maxDepth(root->left);
        int right = maxDepth(root->right);
        int rootLP = left + right;
        diameter = max(diameter, rootLP);
        return 1 + max(left, right);
    }

    int diameter = 0;
};
// https://leetcode.cn/submissions/detail/391588086/
```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```cpp
class Solution {
public:
    bool checkInclusion(string s1, string s2) {
        unordered_map<char, int> need, window;
        for (const auto &c: s1) {
            ++need[c];
        }
        int valid = 0;
        // s[left..right) = Window Substring
        // s[right..n-1]  = Scanning
        int left = 0, right = 0;
        while (right < s2.size()) {
            char add = s2[right++];
            if (need.count(add) == 1) {
                if (++window[add] == need[add]) {
                    ++valid;
                }
            }
            if (valid == need.size()) {
                while (left < right - s1.size()) {
                    char del = s2[left++];
                    if (need.count(del) == 1) {
                        if (window[del] == need[del]) {
                            --valid;
                        }
                        --window[del];
                    }
                }
            }
            if (valid == need.size()) {
                return true;
            }
        }
        return false;
    }
};
// https://leetcode.cn/submissions/detail/391685602/
```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```cpp
class Solution {
public:
    int minDistance(const string &word1, const string &word2) {
        int n1 = word1.size(), n2 = word2.size();
        memo = vector<vector<int >>(n1, vector<int>(n2, -1));
        return minDistance(word1, n1 - 1, word2, n2 - 1);
    }

private:
    // 返回子串 s1[0..i] s2[0..j] 的最小删除步数
    int minDistance(const string &s1, int i, const string &s2, int j) {
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
        if (memo[i][j] == -1) {
            if (s1[i] == s2[j]) {
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
                memo[i][j] = min(min(sp1, sp2), sp3);
            }
        }
        return memo[i][j];
    }

    vector<vector<int>> memo;
};
// https://leetcode.cn/submissions/detail/448357793/
```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```cpp
class Solution {
public:
    TreeNode *mergeTrees(TreeNode *root1, TreeNode *root2) {
        if (root1 == nullptr) {
            return root2;
        }
        if (root2 == nullptr) {
            return root1;
        }
        auto *mRoot = new TreeNode(root1->val + root2->val);
        mRoot->left = mergeTrees(root1->left, root2->left);
        mRoot->right = mergeTrees(root1->right, root2->right);
        return mRoot;
    }
};
// https://leetcode.cn/submissions/detail/391479419/
```

```cpp
class Solution {
public:
    TreeNode *mergeTrees(TreeNode *root1, TreeNode *root2) {
        queue<TreeNode *> q1, q2, mq;
        TreeNode *mRoot = merge(root1, root2);
        if (root1 != nullptr && root2 != nullptr) {
            q1.push(root1);
            q2.push(root2);
            mq.push(mRoot);
        }
        while (!mq.empty()) {
            TreeNode *node1 = q1.front();
            TreeNode *node2 = q2.front();
            TreeNode *mNode = mq.front();
            q1.pop();
            q2.pop();
            mq.pop();
            // left
            TreeNode *left1 = node1->left;
            TreeNode *left2 = node2->left;
            mNode->left = merge(left1, left2);
            if (left1 != nullptr && left2 != nullptr) {
                q1.push(left1);
                q2.push(left2);
                mq.push(mNode->left);
            }
            // right
            TreeNode *right1 = node1->right;
            TreeNode *right2 = node2->right;
            mNode->right = merge(right1, right2);
            if (right1 != nullptr && right2 != nullptr) {
                q1.push(right1);
                q2.push(right2);
                mq.push(mNode->right);
            }
        }
        return mRoot;
    }

private:
    TreeNode *merge(TreeNode *node1, TreeNode *node2) {
        if (node1 == nullptr) {
            return node2;
        }
        if (node2 == nullptr) {
            return node1;
        }
        return new TreeNode(node1->val + node2->val);
    }
};
// https://leetcode.cn/submissions/detail/391479988/
```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```cpp
class Solution {
public:
    vector<TreeNode *> findDuplicateSubtrees(TreeNode *root) {
        postorder(root);
        return ans;
    }

private:
    string postorder(TreeNode *root) {
        if (root == nullptr) {
            return "#";
        }
        string left = postorder(root->left);
        string right = postorder(root->right);
        string res = left + "," + right + "," + to_string(root->val);
        if (++counter[res] == 2) {
            ans.push_back(root);
        }
        return res;
    }
    
    vector<TreeNode *> ans;
    unordered_map<string, int> counter;
};
// https://leetcode.cn/submissions/detail/391592721/
```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```cpp
class Solution {
public:
    TreeNode *constructMaximumBinaryTree(vector<int> &nums) {
        return constructMaximumBinaryTree(nums, 0, nums.size() - 1);
    }

private:
    TreeNode *constructMaximumBinaryTree(const vector<int> &nums, int lo, int hi) {
        if (lo > hi) {
            return nullptr;
        }
        int maxIndex = lo;
        for (int i = lo + 1; i <= hi; ++i) {
            if (nums[i] > nums[maxIndex]) {
                maxIndex = i;
            }
        }
        auto *root = new TreeNode(nums[maxIndex]);
        root->left = constructMaximumBinaryTree(nums, lo, maxIndex - 1);
        root->right = constructMaximumBinaryTree(nums, maxIndex + 1, hi);
        return root;
    }
};
// https://leetcode.cn/submissions/detail/391474764/
```

```cpp
class Solution {
public:
    TreeNode *constructMaximumBinaryTree(vector<int> &nums) {
        return constructMaximumBinaryTree(nums, 0, nums.size() - 1);
    }

private:
    TreeNode *constructMaximumBinaryTree(const vector<int> &nums, int lo, int hi) {
        if (lo > hi) {
            return nullptr;
        }
        auto maxIter = max_element(nums.begin() + lo, nums.begin() + hi + 1);
        int maxIndex = distance(nums.begin(), maxIter);
        auto *root = new TreeNode(nums[maxIndex]);
        root->left = constructMaximumBinaryTree(nums, lo, maxIndex - 1);
        root->right = constructMaximumBinaryTree(nums, maxIndex + 1, hi);
        return root;
    }
};
// https://leetcode.cn/submissions/detail/391560045/
```

```cpp
class Solution {
public:
    TreeNode *constructMaximumBinaryTree(vector<int> &nums) {
        vector<TreeNode *> stack;
        for (int x: nums) {
            auto *cur = new TreeNode(x);
            while (!stack.empty() && stack.back()->val < x) {
                cur->left = stack.back();
                stack.pop_back();
            }
            if (!stack.empty()) {
                stack.back()->right = cur;
            }
            stack.push_back(cur);
        }
        return stack.front();
    }
};
// https://leetcode.cn/submissions/detail/391475493/
```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```cpp
class Solution {
public:
    int maxAreaOfIsland(vector<vector<int>> &grid) {
        int ans = 0;
        for (int row = 0; row < grid.size(); ++row) {
            for (int col = 0; col < grid[0].size(); ++col) {
                if (grid[row][col] == LAND) {
                    area = 0;
                    floodFill(grid, row, col);
                    ans = max(ans, area);
                }
            }
        }
        return ans;
    }

private:
    void floodFill(vector<vector<int>> &grid, int row, int col) {
        if (row < 0 || row >= grid.size() || col < 0 || col >= grid[0].size() || grid[row][col] == WATER) {
            return;
        }
        ++area;
        grid[row][col] = WATER;
        floodFill(grid, row, col + 1);
        floodFill(grid, row, col - 1);
        floodFill(grid, row + 1, col);
        floodFill(grid, row - 1, col);
    }

    int area = 0;
    static const int LAND = 1;
    static const int WATER = 0;
};
// https://leetcode.cn/submissions/detail/391610657/
```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```cpp
class Solution {
public:
    bool canPartitionKSubsets(vector<int> &nums, int k) {
        if (k > nums.size()) {
            return false;
        }
        int sum = accumulate(nums.begin(), nums.end(), 0);
        if (sum % k != 0) {
            return false;
        }
        this->target = sum / k;
        this->used = 0;
        this->pathSums = vector<int>(k);
        return backtrack(nums, k, 0, -1);
    }

private:
    // 遍历『决策森林』的 k 棵『决策树』
    // 一棵『决策树』的『路径』代表一个『等和子集』
    // tree = 第几棵『决策树』，取 [0..k-1] 为值
    // edge =『决策树』的『边』，取数组 nums 的索引为值
    // pathSums[tree] = 第几棵『决策树』的『路径和』
    bool backtrack(vector<int> &nums, int k, int tree, int edge) {
        bool res = false;
        if (tree == k) {
            res = true;
        } else if (pathSums[tree] == target) {
            // 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            // 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            // 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            // 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            // 因为 C 的可选『边』是一样的
            if (memo.count(used) == 0) {
                // 遍历下一棵『决策树』
                memo[used] = backtrack(nums, k, tree + 1, -1);
            }
            res = memo[used];
        } else {
            // 通过去重，对同一棵树，优化『边』的遍历，避免『边+边』重复
            // 例如 1 和 2 分别是两条『边』，[1->2] 和 [2->1] 是重复的
            while (++edge < nums.size()) {
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
                res = backtrack(nums, k, tree, edge);
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

    int target;
    int used;
    vector<int> pathSums;
    unordered_map<int, bool> memo;
};
// https://leetcode.cn/submissions/detail/391673705/
```

```cpp
class Solution {
public:
    bool canPartitionKSubsets(vector<int> &nums, int k) {
        if (k > nums.size()) {
            return false;
        }
        int sum = accumulate(nums.begin(), nums.end(), 0);
        if (sum % k != 0) {
            return false;
        }
        this->target = sum / k;
        this->used = 0;
        this->pathSums = vector<int>(k);
        return dfs(nums, k, 0, -1);
    }

private:
    // 遍历『决策森林』的 k 棵『决策树』
    // 一棵『决策树』的『路径』代表一个『等和子集』
    // tree = 第几棵『决策树』，取 [0..k-1] 为值
    // vertex =『决策树』的『顶点』，取数组 nums 的索引为值
    // pathSums[tree] = 第几棵『决策树』的『路径和』
    bool dfs(vector<int> &nums, int k, int tree, int vertex) {
        int x = (vertex == -1 ? 0 : nums[vertex]);
        if (vertex >= 0) {
            pathSums[tree] += x;
            //『或』运算，将第 vertex 位修改为 1
            used |= 1 << vertex;
        }
        bool res = false;
        if (tree == k) {
            res = true;
        } else if (pathSums[tree] == target) {
            // 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            // 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            // 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            // 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            // 因为 C 的可选『边』是一样的
            if (memo.count(used) == 0) {
                // 遍历下一棵『决策树』
                memo[used] = dfs(nums, k, tree + 1, -1);
            }
            res = memo[used];
        } else {
            // 通过去重，对同一棵树，优化『边』的遍历，避免『边+边』重复
            // 例如 1 和 2 分别是两条『边』，[1->2] 和 [2->1] 是重复的
            int v = vertex;
            while (++v < nums.size()) {
                // 检查第 vertex 位是否为 1
                // 即 nums[vertex] 是否已经被其他『树』使用
                if (((used >> v) & 1) == 1) {
                    continue;
                }
                if (pathSums[tree] + nums[v] > target) {
                    continue;
                }
                res = dfs(nums, k, tree, v);
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

    int used;
    int target;
    vector<int> pathSums;
    unordered_map<int, bool> memo;
};
// https://leetcode.cn/submissions/detail/391672477/
```

```cpp
class Solution {
public:
    bool canPartitionKSubsets(vector<int> &nums, int k) {
        if (k > nums.size()) {
            return false;
        }
        int sum = accumulate(nums.begin(), nums.end(), 0);
        if (sum % k != 0) {
            return false;
        }
        this->target = sum / k;
        this->used = string(16, '0');
        this->pathSums = vector<int>(k);
        return backtrack(nums, k, 0, -1);
    }

private:
    // 遍历『决策森林』的 k 棵『决策树』
    // 一棵『决策树』的『路径』代表一个『等和子集』
    // tree = 第几棵『决策树』，取 [0..k-1] 为值
    // edge =『决策树』的『边』，取数组 nums 的索引为值
    // pathSums[tree] = 第几棵『决策树』的『路径和』
    bool backtrack(vector<int> &nums, int k, int tree, int edge) {
        bool res = false;
        if (tree == k) {
            res = true;
        } else if (pathSums[tree] == target) {
            // 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            // 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            // 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            // 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            // 因为 C 的可选『边』是一样的
            if (memo.count(used) == 0) {
                // 遍历下一棵『决策树』
                memo[used] = backtrack(nums, k, tree + 1, -1);
            }
            res = memo[used];
        } else {
            // 通过去重，对同一棵树，优化『边』的遍历，避免『边+边』重复
            // 例如 1 和 2 分别是两条『边』，[1->2] 和 [2->1] 是重复的
            while (++edge < nums.size()) {
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
                res = backtrack(nums, k, tree, edge);
                if (res) {
                    break;
                }
                pathSums[tree] -= x;
                used[edge] = '0';
            }
        }
        return res;
    }

    int target;
    string used;
    vector<int> pathSums;
    unordered_map<string, bool> memo;
};
// https://leetcode.cn/submissions/detail/391674688/
```

```cpp
class Solution {
public:
    bool canPartitionKSubsets(vector<int> &nums, int k) {
        if (k > nums.size()) {
            return false;
        }
        int sum = accumulate(nums.begin(), nums.end(), 0);
        if (sum % k != 0) {
            return false;
        }
        this->target = sum / k;
        this->used = string(16, '0');
        this->pathSums = vector<int>(k);
        return dfs(nums, k, 0, -1);
    }

private:
    // 遍历『决策森林』的 k 棵『决策树』
    // 一棵『决策树』的『路径』代表一个『等和子集』
    // tree = 第几棵『决策树』，取 [0..k-1] 为值
    // vertex =『决策树』的『顶点』，取数组 nums 的索引为值
    // pathSums[tree] = 第几棵『决策树』的『路径和』
    bool dfs(vector<int> &nums, int k, int tree, int vertex) {
        int x = (vertex == -1 ? 0 : nums[vertex]);
        if (vertex >= 0) {
            pathSums[tree] += x;
            used[vertex] = '1';
        }
        bool res = false;
        if (tree == k) {
            res = true;
        } else if (pathSums[tree] == target) {
            // 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
            // 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
            // 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
            // 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
            // 因为 C 的可选『边』是一样的
            if (memo.count(used) == 0) {
                // 遍历下一棵『决策树』
                memo[used] = dfs(nums, k, tree + 1, -1);
            }
            res = memo[used];
        } else {
            // 通过去重，对同一棵树，优化『边』的遍历，避免『边+边』重复
            // 例如 1 和 2 分别是两条『边』，[1->2] 和 [2->1] 是重复的
            int v = vertex;
            while (++v < nums.size()) {
                // 检查第 vertex 位是否为 1
                // 即 nums[vertex] 是否已经被其他『树』使用
                if (used[v] == '1') {
                    continue;
                }
                if (pathSums[tree] + nums[v] > target) {
                    continue;
                }
                res = dfs(nums, k, tree, v);
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

    int target;
    string used;
    vector<int> pathSums;
    unordered_map<string, bool> memo;
};
// https://leetcode.cn/submissions/detail/391673056/
```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```cpp
class Solution {
public:
    TreeNode *searchBST(TreeNode *root, int val) {
        if (root == nullptr) {
            return nullptr;
        }
        if (val < root->val) {
            return searchBST(root->left, val);
        }
        if (root->val < val) {
            return searchBST(root->right, val);
        }
        return root;
    }
};
// https://leetcode.cn/submissions/detail/391480458/
```

```cpp
class Solution {
public:
    TreeNode *searchBST(TreeNode *root, int val) {
        TreeNode *ptr = root;
        while (ptr != nullptr) {
            if (val < ptr->val) {
                ptr = ptr->left;
            } else if (ptr->val < val) {
                ptr = ptr->right;
            } else {
                return ptr;
            }
        }
        return nullptr;
    }
};
// https://leetcode.cn/submissions/detail/391480302/
```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```cpp
class Solution {
public:
    TreeNode *insertIntoBST(TreeNode *root, int val) {
        if (root == nullptr) {
            return new TreeNode(val);
        }
        if (val < root->val) {
            root->left = insertIntoBST(root->left, val);
        }
        if (root->val < val) {
            root->right = insertIntoBST(root->right, val);
        }
        return root;
    }
};
// https://leetcode.cn/submissions/detail/391480771/
```

```cpp
class Solution {
public:
    TreeNode *insertIntoBST(TreeNode *root, int val) {
        auto *x = new TreeNode(val);;
        if (root == nullptr) {
            return x;
        }
        TreeNode *ptr = root;
        while (true) {
            if (val < ptr->val) {
                if (ptr->left == nullptr) {
                    ptr->left = x;
                    break;
                }
                ptr = ptr->left;
            } else {
                if (ptr->right == nullptr) {
                    ptr->right = x;
                    break;
                }
                ptr = ptr->right;
            }
        }
        return root;
    }
};
// https://leetcode.cn/submissions/detail/391481734/
```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```cpp
class Solution {
public:
    int search(vector<int> &nums, int target) {
        int lo = 0, hi = nums.size() - 1;
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
// https://leetcode.cn/submissions/detail/391555844/
```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```cpp
class Solution {
public:
    int minimumDeleteSum(const string &s1, const string &s2) {
        int n1 = s1.size(), n2 = s2.size();
        memo = vector<vector<int >>(n1, vector<int>(n2, -1));
        sum1 = prefixSum(s1);
        sum2 = prefixSum(s2);
        return minimumDeleteSum(s1, n1 - 1, s2, n2 - 1);
    }

private:
    // 子串 s1[0..i] s2[0..j] 的最小 ASCII 删除和
    int minimumDeleteSum(const string &s1, int i, const string &s2, int j) {
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
        if (memo[i][j] == -1) {
            if (s1[i] == s2[j]) {
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                memo[i][j] = minimumDeleteSum(s1, i - 1, s2, j - 1);
            } else {
                // 删除 s1[i] s2[j]
                // s1[0..i-1][i]
                // s2[0..j-1][j]
                int sp1 = minimumDeleteSum(s1, i - 1, s2, j - 1) + s1[i] + s2[j];
                // 删除 s2[j]
                // s1[0..i]
                // s2[0..j-1][j]
                int sp2 = minimumDeleteSum(s1, i, s2, j - 1) + s2[j];
                // 删除 s1[i]
                // s1[0..i-1][i]
                // s2[0..j]
                int sp3 = minimumDeleteSum(s1, i - 1, s2, j) + s1[i];
                memo[i][j] = min(min(sp1, sp2), sp3);
            }
        }
        return memo[i][j];
    }

    vector<int> prefixSum(const string &s) {
        size_t n = s.size();
        vector<int> sum(n);
        sum[0] = s[0];
        for (int i = 1; i < n; ++i) {
            sum[i] = sum[i - 1] + s[i];
        }
        return sum;
    }

    vector<int> sum1;
    vector<int> sum2;
    vector<vector<int>> memo;
};
// https://leetcode.cn/submissions/detail/391610248/
```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```cpp
class Solution {
public:
    int maxProfit(vector<int> &prices, int fee) {
        size_t n = prices.size();
        // dp[i][0] = 第 i 天，空仓状态下的最大利润
        // dp[i][1] = 第 i 天，持仓状态下的最大利润
        vector<vector<int>> dp(n, vector<int>(2));
        dp[0][0] = 0;
        dp[0][1] = -prices[0] - fee;
        for (int i = 1; i < n; ++i) {
            // dp[i - 1][0]             >= dp[i - 1][0] - prices[i] - fee
            // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
            // => dp[i][0] >= dp[i][1]
            dp[i][0] = max(dp[i - 1][0], dp[i - 1][1] + prices[i]);
            dp[i][1] = max(dp[i - 1][0] - prices[i] - fee, dp[i - 1][1]);
        }
        return dp[n - 1][0];
    }
};
// https://leetcode.cn/submissions/detail/391485800/
```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```cpp
class Solution {
public:
    vector<int> dailyTemperatures(vector<int> &temperatures) {
        int n = temperatures.size();
        vector<int> ans(n);
        stack<int> s;
        for (int i = n - 1; i >= 0; --i) {
            while (!s.empty() && temperatures[s.top()] <= temperatures[i]) {
                s.pop();
            }
            ans[i] = s.empty() ? 0 : s.top() - i;
            s.push(i);
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/374196946/
```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```cpp
// TODO
```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```cpp
class Solution {
public:
    int openLock(vector<string> &deadends, const string &target) {
        unordered_set<string> marked(deadends.begin(), deadends.end());
        deque<string> q;
        string source = "0000";
        if (marked.count(source) == 0) {
            marked.insert(source);
            q.push_back(source);
        }
        int count = 0;
        while (!q.empty()) {
            size_t n = q.size();
            for (int i = 0; i < n; ++i) {
                string s = q.front();
                q.pop_front();
                if (s == target) {
                    return count;
                }
                for (int j = 0; j < 4; ++j) {
                    string plus = plusOne(s, j);
                    if (marked.count(plus) == 0) {
                        marked.insert(plus);
                        q.push_back(plus);
                    }
                    string minus = minusOne(s, j);
                    if (marked.count(minus) == 0) {
                        marked.insert(minus);
                        q.push_back(minus);
                    }
                }
            }
            ++count;
        }
        return -1;
    }

private:
    string plusOne(string s, int j) {
        if (s[j] == '9') {
            s[j] = '0';
        } else {
            s[j] += 1;
        }
        return s;
    }

    string minusOne(string s, int j) {
        if (s[j] == '0') {
            s[j] = '9';
        } else {
            s[j] -= 1;
        }
        return s;
    }
};
// https://leetcode.cn/submissions/detail/391691915/
```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```cpp
class Solution {
public:
    bool isBipartite(vector<vector<int>> &graph) {
        size_t n = graph.size();
        marked = vector<bool>(n);
        color = vector<bool>(n);
        for (int v = 0; v < n; ++v) {
            if (!marked[v]) {
                dfs(graph, v);
                if (!bipartite) {
                    break;
                }
            }
        }
        return bipartite;
    }

private:
    void dfs(const vector<vector<int>> &graph, int v) {
        marked[v] = true;
        for (const auto &w: graph[v]) {
            if (!marked[w]) {
                color[w] = !color[v];
                dfs(graph, w);
            } else if (color[w] == color[v]) {
                bipartite = false;
                return;
            }
        }
    }

    vector<bool> marked;
    vector<bool> color;
    bool bipartite = true;
};
// https://leetcode.cn/submissions/detail/391658390/
```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```cpp
class Solution {
public:
    vector<vector<int>> allPathsSourceTarget(vector<vector<int>> &graph) {
        target = graph.size() - 1;
        path.push_back(0);
        backtrack(graph, 0);
        path.pop_back();
        return ans;
    }

private:
    void backtrack(const vector<vector<int>> &graph, int v) {
        if (v == target) {
            ans.push_back(path);
        }
        for (const auto &w: graph[v]) {
            path.push_back(w);
            backtrack(graph, w);
            path.pop_back();
        }
    }

    int target;
    vector<int> path;
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391682733/
```

```cpp
class Solution {
public:
    vector<vector<int>> allPathsSourceTarget(vector<vector<int>> &graph) {
        target = graph.size() - 1;
        dfs(graph, 0);
        return ans;
    }

private:
    void dfs(const vector<vector<int>> &graph, int v) {
        path.push_back(v);
        if (v == target) {
            ans.push_back(path);
        }
        for (const auto &w: graph[v]) {
            dfs(graph, w);
        }
        path.pop_back();
    }

    int target;
    vector<int> path;
    vector<vector<int>> ans;
};
// https://leetcode.cn/submissions/detail/391682898/
```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```cpp
class Solution {
public:
    bool isNStraightHand(vector<int> &hand, int groupSize) {
        if (hand.size() % groupSize != 0) {
            return false;
        }
        unordered_map<int, int> counter;
        for (const auto &card: hand) {
            ++counter[card];
        }
        priority_queue<int, vector<int>, greater<>> min_pq(hand.begin(), hand.end());
        while (!min_pq.empty()) {
            int smallest = min_pq.top();
            min_pq.pop();
            if (counter[smallest] > 0) {
                for (int i = 0; i < groupSize; ++i) {
                    int card = smallest + i;
                    if (counter[card] == 0) {
                        return false;
                    }
                    --counter[card];
                }
            }
        }
        return true;
    }
};
// https://leetcode.cn/submissions/detail/391661877/
```

```cpp
class Solution {
public:
    bool isNStraightHand(vector<int> &hand, int groupSize) {
        if (hand.size() % groupSize != 0) {
            return false;
        }
        sort(hand.begin(), hand.end());
        unordered_map<int, int> counter;
        for (const auto &card: hand) {
            ++counter[card];
        }
        for (const auto &card: hand) {
            if (counter[card] > 0) {
                for (int i = 0; i < groupSize; ++i) {
                    int d = card + i;
                    if (counter[d] == 0) {
                        return false;
                    }
                    --counter[d];
                }
            }
        }
        return true;
    }
};
// https://leetcode.cn/submissions/detail/391661565/
```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```cpp
class Solution {
public:
    int minEatingSpeed(vector<int> &piles, int h) {
        int lo = 1;
        int hi = *max_element(piles.begin(), piles.end());
        int ans = lo;
        while (lo <= hi) {
            int mid = lo + (hi - lo) / 2;
            if (canFinish(piles, h, mid)) {
                ans = mid;
                hi = mid - 1;
            } else {
                lo = mid + 1;
            }
        }
        return ans;
    }

private:
    // 当吃香蕉的速度为 k 时，是否能在 h 小时内吃完
    bool canFinish(const vector<int> &piles, int h, int k) {
        long hours = 0;
        for (const auto &p: piles) {
            hours += (p - 1) / k + 1;
        }
        return hours <= h;
    }
};
// https://leetcode.cn/submissions/detail/391558423/
```

## 876. 链表的中间结点

<https://leetcode.cn/problems/middle-of-the-linked-list/>

```cpp
class Solution {
public:
    ListNode *middleNode(ListNode *head) {
        ListNode *slow = head;
        ListNode *fast = head;
        while (fast != nullptr && fast->next != nullptr) {
            slow = slow->next;
            fast = fast->next->next;
        }
        return slow;
    }
};
// https://leetcode.cn/submissions/detail/341374792/
```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```cpp
class Solution {
public:
    bool possibleBipartition(int n, vector<vector<int>> &dislikes) {
        vector<vector<int>> graph(n);
        for (const auto &d: dislikes) {
            int v = d[0] - 1, w = d[1] - 1;
            graph[v].push_back(w);
            graph[w].push_back(v);
        }
        return isBipartite(graph);
    }

private:
    bool isBipartite(vector<vector<int>> &graph) {
        size_t n = graph.size();
        marked = vector<bool>(n);
        color = vector<bool>(n);
        for (int v = 0; v < n; ++v) {
            if (!marked[v]) {
                dfs(graph, v);
                if (!bipartite) {
                    break;
                }
            }
        }
        return bipartite;
    }

    void dfs(const vector<vector<int>> &graph, int v) {
        marked[v] = true;
        for (const auto &w: graph[v]) {
            if (!marked[w]) {
                color[w] = !color[v];
                dfs(graph, w);
            } else if (color[w] == color[v]) {
                bipartite = false;
                return;
            }
        }
    }

    vector<bool> marked;
    vector<bool> color;
    bool bipartite = true;
};
// https://leetcode.cn/submissions/detail/391446702/
```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```cpp
class Solution {
public:
    TreeNode *constructFromPrePost(vector<int> &preorder, vector<int> &postorder) {
        for (int i = 0; i < postorder.size(); ++i) {
            valToIndex[postorder[i]] = i;
        }
        return buildTree(preorder, 0, preorder.size() - 1,
                         postorder, 0, postorder.size() - 1);
    }

private:
    TreeNode *buildTree(const vector<int> &preorder, int preStart, int preEnd,
                        const vector<int> &postorder, int postStart, int postEnd) {
        if (preStart > preEnd) {
            return nullptr;
        }
        int rootVal = preorder[preStart];
        auto *root = new TreeNode(rootVal);
        if (preStart < preEnd) {
            int leftRootVal = preorder[preStart + 1];
            int postLeftRoot = valToIndex[leftRootVal];
            int leftSize = postLeftRoot - postStart + 1;
            root->left = buildTree(preorder, preStart + 1, preStart + leftSize,
                                   postorder, postStart, postLeftRoot);
            root->right = buildTree(preorder, preStart + leftSize + 1, preEnd,
                                    postorder, postLeftRoot + 1, postEnd);
        }
        return root;
    }

    unordered_map<int, int> valToIndex;
};
// https://leetcode.cn/submissions/detail/391590416/
```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```cpp
class Solution {
public:
    vector<int> sortArrayByParity(vector<int> &nums) {
        int n = nums.size();
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
            swap(nums[i], nums[j]);
        }
        return nums;
    }
};
// https://leetcode.cn/submissions/detail/362462181/
```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```cpp
class Solution {
public:
    vector<int> sortArray(vector<int> &nums) {
        random_device rd;
        mt19937 g(rd());
        shuffle(nums.begin(), nums.end(), g);
        sort(nums, 0, nums.size() - 1);
        return nums;
    }

private:
    void sort(vector<int> &nums, int lo, int hi) {
        if (lo >= hi) {
            return;
        }
        int j = partition(nums, lo, hi);
        sort(nums, lo, j - 1);
        sort(nums, j + 1, hi);
    }

    int partition(vector<int> &nums, int lo, int hi) {
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
            swap(nums[i], nums[j]);
        }
        swap(nums[lo], nums[j]);
        return j;
    }
};
// https://leetcode.cn/submissions/detail/366420620/
```

```cpp
class Solution {
public:
    vector<int> sortArray(vector<int> &nums) {
        random_device rd;
        mt19937 g(rd());
        shuffle(nums.begin(), nums.end(), g);
        stack<pair<int, int>> s;
        s.emplace(0, nums.size() - 1);
        while (!s.empty()) {
            pair<int, int> p = s.top();
            s.pop();
            int lo = p.first;
            int hi = p.second;
            if (lo < hi) {
                int j = partition(nums, lo, hi);
                s.emplace(j + 1, hi);
                s.emplace(lo, j - 1);
            }
        }
        return nums;
    }

private:
    int partition(vector<int> &nums, int lo, int hi) {
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
            swap(nums[i], nums[j]);
        }
        swap(nums[lo], nums[j]);
        return j;
    }
};
// https://leetcode.cn/submissions/detail/391553984/
```

```cpp
class Solution {
public:
    vector<int> sortArray(vector<int> &nums) {
        random_device rd;
        mt19937 g(rd());
        shuffle(nums.begin(), nums.end(), g);
        int n = nums.size();
        // k = 1..n
        for (int k = n / 2; k >= 1; --k) {
            sink(nums, k, n);
        }
        int k = n;
        while (k > 1) {
            exch(nums, 1, k--);
            sink(nums, 1, k);
        }
        return nums;
    }

private:
    // i, j = 1..n
    bool less(const vector<int> &nums, int i, int j) {
        return nums[i - 1] < nums[j - 1];
    }

    // i, j = 1..n
    void exch(vector<int> &nums, int i, int j) {
        swap(nums[i - 1], nums[j - 1]);
    }

    // k = 1..n
    void sink(vector<int> &nums, int k, int n) {
        while (k <= n / 2) {
            int j = 2 * k;
            if (j + 1 <= n && less(nums, j, j + 1)) {
                ++j;
            }
            if (less(nums, j, k)) {
                break;
            }
            exch(nums, j, k);
            k = j;
        }
    }
};
// https://leetcode.cn/submissions/detail/364251319/
```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```cpp
// 性质一 一个「合法」括号组合的左括号数量一定等于右括号数量
// 性质二 对于一个「合法」的括号字符串组合 p，必然对于
// 任何 0 <= i < len(p) 都有：子串 p[0..i] 中
// 左括号的数量都大于或等于右括号的数量
class Solution {
public:
    int minAddToMakeValid(const string &s) {
        int insertLeft = 0; // 已插入左括号的数量
        int needRight = 0;  // 待插入右括号的数量
        for (const auto &ch: s) {
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
};
// https://leetcode.cn/submissions/detail/391711538/
```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```cpp
class Solution {
public:
    vector<int> sortArrayByParityII(vector<int> &nums) {
        size_t n = nums.size();
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
            swap(nums[i], nums[j]);
        }
        return nums;
    }
};
// https://leetcode.cn/submissions/detail/391453490/
```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```cpp
class Solution {
public:
    int minFallingPathSum(vector<vector<int>> &matrix) {
        int n = matrix.size();
        memo = vector<vector<int>>(n, vector<int>(n, INT_MIN));
        int ans = INT_MAX;
        for (int col = 0; col < n; ++col) {
            ans = min(ans, minFallingPathSum(matrix, n - 1, col));
        }
        return ans;
    }

private:
    // 从 matrix[0][0..n-1] 到 matrix[row][col] 的最小下降路径和
    int minFallingPathSum(const vector<vector<int>> &matrix, int row, int col) {
        if (col < 0 || col >= matrix[0].size()) {
            return INT_MAX;
        }
        if (row == 0) {
            return matrix[row][col];
        }
        if (memo[row][col] == INT_MIN) {
            int sp1 = minFallingPathSum(matrix, row - 1, col - 1);
            int sp2 = minFallingPathSum(matrix, row - 1, col);
            int sp3 = minFallingPathSum(matrix, row - 1, col + 1);
            memo[row][col] = min(min(sp1, sp2), sp3) + matrix[row][col];
        }
        return memo[row][col];
    }

    vector<vector<int>> memo;
};
// https://leetcode.cn/submissions/detail/391536809/
```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```cpp
class Solution {
public:
    vector<vector<int>> intervalIntersection(vector<vector<int>> &firstList, vector<vector<int>> &secondList) {
        vector<vector<int>> ans;
        int i = 0, j = 0;
        while (i < firstList.size() && j < secondList.size()) {
            int start1 = firstList[i][0], end1 = firstList[i][1];
            int start2 = secondList[j][0], end2 = secondList[j][1];
            if (end1 < start2) { // 不相交
                ++i;
            } else if (end2 < start1) { // 不相交
                ++j;
            } else { // 相交
                ans.push_back({max(start1, start2), min(end1, end2)});
                if (end1 < end2) {
                    ++i;
                } else {
                    ++j;
                }
            }
        }
        return ans;
    }
};
// https://leetcode.cn/submissions/detail/391665219/
```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```cpp
class UF {
public:
    explicit UF(int n) {
        parent = vector<int>(n);
        rank = vector<int>(n);
        for (int i = 0; i < n; ++i) {
            parent[i] = i;
        }
        sz = n;
    }

    int find(int p) {
        while (p != parent[p]) {
            parent[p] = parent[parent[p]];
            p = parent[p];
        }
        return p;
    }

    void unionn(int p, int q) {
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
            --sz;
        }
    }

    bool connected(int p, int q) {
        return find(p) == find(q);
    }

    int size() {
        return sz;
    }

private:
    vector<int> parent;
    vector<int> rank;
    int sz;
};

class Solution {
public:
    bool equationsPossible(vector<string> &equations) {
        UF uf(26);
        for (const auto &s: equations) {
            if (s[1] == '=') {
                int p = s[0] - 'a';
                int q = s[3] - 'a';
                uf.unionn(p, q);
            }
        }
        for (const auto &s: equations) {
            if (s[1] == '!') {
                int p = s[0] - 'a';
                int q = s[3] - 'a';
                if (uf.connected(p, q)) {
                    return false;
                }
            }
        }
        return true;
    }
};
// https://leetcode.cn/submissions/detail/391555130/
```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```cpp
class Solution {
public:
    int shipWithinDays(const vector<int> &weights, int days) {
        int lo = 0, hi = 0;
        for (const auto &w: weights) {
            lo = max(lo, w);
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

private:
    // 当船的运载能力为 capacity 时，是否能在 days 天内送完。
    bool canFinish(const vector<int> &weights, int days, int capacity) {
        size_t n = weights.size();
        int i = 0, minDays = 0;
        while (i < n) {
            int sum = 0;
            while (i < n && sum + weights[i] <= capacity) {
                sum += weights[i++];
            }
            ++minDays;
        }
        return minDays <= days;
    }
};
// https://leetcode.cn/submissions/detail/416187282/
```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```cpp
class Solution {
public:
    int numEnclaves(vector<vector<int>> &grid) {
        int m = grid.size(), n = grid[0].size();
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

private:
    void floodFill(vector<vector<int>> &grid, int row, int col) {
        if (row < 0 || row >= grid.size() || col < 0 || col >= grid[0].size() || grid[row][col] == WATER) {
            return;
        }
        grid[row][col] = WATER;
        floodFill(grid, row, col + 1);
        floodFill(grid, row, col - 1);
        floodFill(grid, row + 1, col);
        floodFill(grid, row - 1, col);
    }

    static const int LAND = 1;
    static const int WATER = 0;
};
// https://leetcode.cn/submissions/detail/391547657/
```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```cpp
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
public:
    int videoStitching(vector<vector<int>> &clips, int time) {
        sort(clips.begin(), clips.end(),
             [](const vector<int> &a, const vector<int> &b) {
                 if (a[0] == b[0]) {
                     return a[1] > b[1];
                 }
                 return a[0] < b[0];
             });
        size_t n = clips.size();
        int i = 0, maxEnd = 0, count = 0;
        // 当 clips[i] 与 [0, maxEnd] 重叠（相交或被覆盖）时
        while (i < n && clips[i][0] <= maxEnd) {
            // 记录与 [0, maxEnd] 重叠的所有区间中最大的 end
            int nextEnd = clips[i][1];
            while (++i < n && clips[i][0] <= maxEnd) {
                nextEnd = max(nextEnd, clips[i][1]);
            }
            maxEnd = nextEnd;
            ++count;
            if (maxEnd >= time) {
                return count;
            }
        }
        return -1;
    }
};
// https://leetcode.cn/submissions/detail/391550144/
```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```cpp
class Solution {
public:
    int longestCommonSubsequence(string text1, string text2) {
        size_t n1 = text1.size();
        size_t n2 = text2.size();
        // text1[0..i-1] = text1 的长度为 i 的前缀
        // text2[0..j-1] = text2 的长度为 j 的前缀
        // dp[i][j] = LCS(text1[0..i-1], text2[0..j-1]) 的长度
        vector<vector<int>> dp(n1 + 1, vector<int>(n2 + 1, 0));
        for (int i = 1; i <= n1; ++i) {
            for (int j = 1; j <= n2; ++j) {
                // text1[i-1] = text2[j-1]
                if (text1[i - 1] == text2[j - 1]) {
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
                    dp[i][j] = max(dp[i][j - 1], dp[i - 1][j]);
                }
            }
        }
        return dp[n1][n2];
    }
};
// https://leetcode.cn/submissions/detail/391705625/
```

```cpp
class Solution {
public:
    int longestCommonSubsequence(const string &text1, const string &text2) {
        int n1 = text1.size();
        int n2 = text2.size();
        memo = vector<vector<int >>(n1, vector<int>(n2, -1));
        return longestCommonSubsequence(text1, n1 - 1, text2, n2 - 1);
    }

private:
    // LCS(text1[0..i], text2[0..j]) 的长度
    int longestCommonSubsequence(const string &text1, int i, const string &text2, int j) {
        if (i < 0 || j < 0) {
            return 0;
        }
        if (memo[i][j] == -1) {
            if (text1[i] == text2[j]) {
                memo[i][j] = longestCommonSubsequence(text1, i - 1, text2, j - 1) + 1;
            } else {
                int sp1 = longestCommonSubsequence(text1, i, text2, j - 1);
                int sp2 = longestCommonSubsequence(text1, i - 1, text2, j);
                memo[i][j] = max(sp1, sp2);
            }
        }
        return memo[i][j];
    }

    vector<vector<int>> memo;
};
// https://leetcode.cn/submissions/detail/391706010/
```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```cpp
class Solution {
public:
    int closedIsland(vector<vector<int>> &grid) {
        int m = grid.size(), n = grid[0].size();
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
                    floodFill(grid, row, col);
                    ++count;
                }
            }
        }
        return count;
    }

private:
    void floodFill(vector<vector<int>> &grid, int row, int col) {
        if (row < 0 || row >= grid.size() || col < 0 || col >= grid[0].size() || grid[row][col] == WATER) {
            return;
        }
        grid[row][col] = WATER;
        floodFill(grid, row, col + 1);
        floodFill(grid, row, col - 1);
        floodFill(grid, row + 1, col);
        floodFill(grid, row - 1, col);
    }

    static const int LAND = 0;
    static const int WATER = 1;
};
// https://leetcode.cn/submissions/detail/391545466/
```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```cpp
class Solution {
public:
    int removeCoveredIntervals(vector<vector<int>> &intervals) {
        sort(intervals.begin(), intervals.end(),
             [](const vector<int> &a, const vector<int> &b) {
                 if (a[0] == b[0]) {
                     return a[1] > b[1];
                 }
                 return a[0] < b[0];
             });
        int n = intervals.size();
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
};
// https://leetcode.cn/submissions/detail/391549454/
```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```cpp
class Solution {
public:
    TreeNode *balanceBST(TreeNode *root) {
        dfs(root);
        return sortedArrayToBST(inorder, 0, inorder.size() - 1);
    }

private:
    // 深度优先搜索，获取中序遍历结果 inorder
    void dfs(const TreeNode *root) {
        if (root == nullptr) {
            return;
        }
        dfs(root->left);
        inorder.push_back(root->val);
        dfs(root->right);
    }

    // 将有序数组 nums[lo..hi] 转换为二叉搜索树
    TreeNode *sortedArrayToBST(const vector<int> &nums, int lo, int hi) {
        if (lo > hi) {
            return nullptr;
        }
        int mid = lo + (hi - lo) / 2;
        auto *root = new TreeNode(nums[mid]);
        root->left = sortedArrayToBST(nums, lo, mid - 1);
        root->right = sortedArrayToBST(nums, mid + 1, hi);
        return root;
    }

    vector<int> inorder;
};
// https://leetcode.cn/submissions/detail/391591931/
```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```cpp
// TODO
```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```cpp
class Solution {
public:
    int minInsertions(const string &s) {
        int insertLeft = 0;  // 已插入左括号的数量
        int insertRight = 0; // 已插入右括号的数量
        int needRight = 0;   // 待插入右括号的数量
        for (const auto &ch: s) {
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
};
// https://leetcode.cn/submissions/detail/391706454/
```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```cpp
// TODO
```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```cpp
// TODO
```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```cpp
class Solution {
public:
    int countSubIslands(vector<vector<int>> &grid1, vector<vector<int>> &grid2) {
        int rowSize = grid2.size(), colSize = grid2[0].size();
        for (int row = 0; row < rowSize; ++row) {
            for (int col = 0; col < colSize; ++col) {
                // 淹没『非子岛屿』
                if (grid2[row][col] == LAND && grid1[row][col] == WATER) {
                    floodFill(grid2, row, col);
                }
            }
        }
        int count = 0;
        for (int row = 0; row < rowSize; ++row) {
            for (int col = 0; col < colSize; ++col) {
                if (grid2[row][col] == LAND) {
                    floodFill(grid2, row, col);
                    ++count;
                }
            }
        }
        return count;
    }

private:
    void floodFill(vector<vector<int>> &grid, int row, int col) {
        if (row < 0 || row >= grid.size() || col < 0 || col >= grid[0].size() || grid[row][col] == WATER) {
            return;
        }
        grid[row][col] = WATER;
        floodFill(grid, row, col + 1);
        floodFill(grid, row, col - 1);
        floodFill(grid, row + 1, col);
        floodFill(grid, row - 1, col);
    }

    static const int LAND = 1;
    static const int WATER = 0;
};
// https://leetcode.cn/submissions/detail/418812833/
```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode.cn/problems/kth-node-from-end-of-list-lcci/>

```cpp
class Solution {
public:
    int kthToLast(ListNode *head, int k) {
        ListNode *slow = head;
        ListNode *fast = head;
        for (int i = 1; i <= k; ++i) {
            fast = fast->next;
        }
        while (fast != nullptr) {
            slow = slow->next;
            fast = fast->next;
        }
        return slow->val;
    }
};
// https://leetcode.cn/submissions/detail/368845869/
```
