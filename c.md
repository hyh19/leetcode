<!-- omit in toc -->
# LeetCode 题解：C

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

```c
typedef struct {
    int key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *twoSum(const int *nums, int numsSize, int target, int *returnSize) {
    *returnSize = 2;
    int *ans = malloc(sizeof(int[*returnSize]));
    ans[0] = -1;
    ans[1] = -1;
    HashMapItem *valToIndex = NULL;
    for (int i = 0; i < numsSize; ++i) {
        int x = nums[i];
        int need = target - x;
        HashMapItem *item;
        HASH_FIND_INT(valToIndex, &need, item);
        if (item != NULL) {
            ans[0] = item->val;
            ans[1] = i;
            break;
        }
        item = malloc(sizeof(HashMapItem));
        item->key = x;
        item->val = i;
        HASH_ADD_INT(valToIndex, key, item);
    }
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, valToIndex, cur, tmp) {
        HASH_DEL(valToIndex, cur);
        free(cur);
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391303012/
```

## 2. 两数相加

<https://leetcode-cn.com/problems/add-two-numbers/>

```c
struct ListNode *addTwoNumbers(const struct ListNode *l1, const struct ListNode *l2) {
    struct ListNode *dummyHead = malloc(sizeof(struct ListNode));
    dummyHead->val = -1;
    dummyHead->next = NULL;
    struct ListNode *ptr = dummyHead;
    int carry = 0;
    while (l1 != NULL || l2 != NULL || carry > 0) {
        int sum = carry;
        if (l1 != NULL) {
            sum += l1->val;
            l1 = l1->next;
        }
        if (l2 != NULL) {
            sum += l2->val;
            l2 = l2->next;
        }
        struct ListNode *x = malloc(sizeof(struct ListNode));
        x->val = sum % 10;
        x->next = NULL;
        ptr->next = x;
        ptr = ptr->next;
        carry = sum / 10;
    }
    struct ListNode *head = dummyHead->next;
    free(dummyHead);
    return head;
}
// https://leetcode.cn/submissions/detail/392362961/
```

## 3. 无重复字符的最长子串

<https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/>

```c
typedef struct {
    int key;
    UT_hash_handle hh;
} HashSetItem;

int lengthOfLongestSubstring(char *s) {
    int ans = 0;
    HashSetItem *window = NULL;
    // s[left..right) = Window Substring
    // s[right..n-1]  = Scanning
    int left = 0, right = 0;
    size_t n = strlen(s);
    while (right < n) {
        int add = s[right];
        HashSetItem *item;
        HASH_FIND_INT(window, &add, item);
        if (item == NULL) {
            item = malloc(sizeof(HashSetItem));
            item->key = add;
            HASH_ADD_INT(window, key, item);
            ++right;
        } else {
            while (left < right) {
                int del = s[left++];
                HASH_FIND_INT(window, &del, item);
                HASH_DEL(window, item);
                if (del == add) {
                    break;
                }
            }
        }
        ans = fmax(ans, right - left);
    }
    HashSetItem *cur, *tmp;
    HASH_ITER(hh, window, cur, tmp) {
        HASH_DEL(window, cur);
        free(cur);
    }
    HASH_CLEAR(hh, window);
    return ans;
}
// https://leetcode.cn/submissions/detail/392737260/
```

## 4. 寻找两个正序数组的中位数

<https://leetcode.cn/problems/median-of-two-sorted-arrays/>

```c
// 寻找两个正序数组 nums1 和 nums2 从小到大排列的第 k 个数
int getKthElement(const int *nums1, int nums1Size, int start1, const int *nums2, int nums2Size, int start2, int k) {
    if (start1 == nums1Size) {
        return nums2[start2 + k - 1];
    }
    if (start2 == nums2Size) {
        return nums1[start1 + k - 1];
    }
    if (k == 1) {
        return fmin(nums1[start1], nums2[start2]);
    }
    int half = k / 2;
    int i = fmin(nums1Size - 1, start1 + half - 1);
    int j = fmin(nums2Size - 1, start2 + half - 1);
    if (nums1[i] < nums2[j]) {
        // 排除 nums1[start1..i] 共 i-start1+1 个元素
        return getKthElement(nums1, nums1Size, i + 1, nums2, nums2Size, start2, k - (i - start1 + 1));
    } else {
        // 排除 nums2[start2..j] 共 j-start2+1 个元素
        return getKthElement(nums1, nums1Size, start1, nums2, nums2Size, j + 1, k - (j - start2 + 1));
    }
}

double findMedianSortedArrays(const int *nums1, int nums1Size, const int *nums2, int nums2Size) {
    int total = nums1Size + nums2Size;
    int half = total / 2;
    if (total % 2 == 0) {
        int k1 = getKthElement(nums1, nums1Size, 0, nums2, nums2Size, 0, half);
        int k2 = getKthElement(nums1, nums1Size, 0, nums2, nums2Size, 0, half + 1);
        return (k1 + k2) / 2.0;
    }
    return getKthElement(nums1, nums1Size, 0, nums2, nums2Size, 0, half + 1);
}
// https://leetcode.cn/submissions/detail/388294156/
```

## 5. 最长回文子串

<https://leetcode.cn/problems/longest-palindromic-substring/>

```c
// 返回字符串 s 中以 s[i] 和 s[j] 为中心的最长回文子串
char *longestPalindromeCenter(const char *s, int i, int j, size_t *len) {
    size_t n = strlen(s);
    while (i >= 0 && j < n && s[i] == s[j]) {
        --i;
        ++j;
    }
    char *res = calloc(j - i, sizeof(char));
    *len = j - i - 1;
    return strncpy(res, s + i + 1, j - i - 1);
}

char *longestPalindrome(char *s) {
    size_t len = 0;
    char *ans = malloc(0);
    size_t n = strlen(s);
    for (int i = 0; i < n; ++i) {
        size_t len1;
        char *s1 = longestPalindromeCenter(s, i, i, &len1);
        if (len1 > len) {
            free(ans);
            ans = s1;
            len = len1;
        } else {
            free(s1);
        }
        size_t len2;
        char *s2 = longestPalindromeCenter(s, i, i + 1, &len2);
        if (len2 > len) {
            free(ans);
            ans = s2;
            len = len2;
        } else {
            free(s2);
        }
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391338749/
```

## 7. 整数反转

<https://leetcode.cn/problems/reverse-integer/>

```c
// TODO
```

## 11. 盛最多水的容器

<https://leetcode.cn/problems/container-with-most-water/>

```c
int maxArea(const int *height, int heightSize) {
    int i = 0, j = heightSize - 1;
    int ans = 0;
    while (i < j) {
        int w = j - i;
        int h = fmin(height[i], height[j]);
        ans = fmax(ans, w * h);
        if (height[i] < height[j]) {
            ++i;
        } else {
            --j;
        }
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/388261355/
```

## 14. 最长公共前缀

<https://leetcode.cn/problems/longest-common-prefix/>

```c
char *longestCommonPrefixTwo(char *s1, char *s2) {
    int len = fmin(strlen(s1), strlen(s2));
    int i = 0;
    while (i < len && s1[i] == s2[i]) {
        ++i;
    }
    char *res = calloc(i + 1, sizeof(char));
    strncpy(res, s1, i);
    return res;
}

char *longestCommonPrefixRange(char **strs, int lo, int hi) {
    if (lo == hi) {
        return strs[lo];
    }
    int mid = lo + (hi - lo) / 2;
    char *left = longestCommonPrefixRange(strs, lo, mid);
    char *right = longestCommonPrefixRange(strs, mid + 1, hi);
    char *res = longestCommonPrefixTwo(left, right);
    free(left);
    free(right);
    return res;
}

char *longestCommonPrefix(char **strs, int strsSize) {
    return longestCommonPrefixRange(strs, 0, strsSize - 1);
}
// https://leetcode.cn/submissions/detail/391332707/
```

## 15. 三数之和

<https://leetcode-cn.com/problems/3sum/>

```c
int cmp(const void *a, const void *b) {
    int arg1 = *(const int *) a;
    int arg2 = *(const int *) b;
    return arg1 - arg2;
}

// 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的二元组
int **twoSum(const int *nums, int numsSize, int lo, int hi, long target, int *returnSize) {
    int capacity = 4;
    int **res = malloc(sizeof(int *) * capacity);
    *returnSize = 0;
    while (lo < hi) {
        int first = nums[lo], second = nums[hi];
        int sum = first + second;
        if (sum < target) {
            while (++lo < hi && nums[lo] == first) {}
        } else if (sum > target) {
            while (lo < --hi && nums[hi] == second) {}
        } else {
            int *t = malloc(sizeof(int[2]));
            t[0] = first;
            t[1] = second;
            if (*returnSize == capacity) {
                capacity *= 2;
                res = realloc(res, sizeof(int *) * capacity);
            }
            res[(*returnSize)++] = t;
            while (++lo < hi && nums[lo] == first) {}
            while (lo < --hi && nums[hi] == second) {}
        }
    }
    return res;
}

// 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
int **kSum(int k, const int *nums, int numsSize, int lo, int hi, long target, int *returnSize) {
    *returnSize = 0;
    if (hi - lo + 1 < k) {
        return NULL;
    }
    if (k == 2) {
        return twoSum(nums, numsSize, lo, hi, target, returnSize);
    }
    int capacity = 4;
    int **res = malloc(sizeof(int *) * capacity);
    int i = lo;
    while (i <= hi) {
        int curNum = nums[i];
        int size;
        int **sub = kSum(k - 1, nums, numsSize, i + 1, hi, target - curNum, &size);
        for (int j = 0; j < size; ++j) {
            sub[j] = realloc(sub[j], sizeof(int[k]));
            sub[j][k - 1] = curNum;
            if (*returnSize == capacity) {
                capacity *= 2;
                res = realloc(res, sizeof(int *) * capacity);
            }
            res[(*returnSize)++] = sub[j];
        }
        while (++i <= hi && nums[i] == curNum) {}
    }
    return res;
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **threeSum(int *nums, int numsSize, int *returnSize, int **returnColumnSizes) {
    qsort(nums, numsSize, sizeof(int), cmp);
    int **ans = kSum(3, nums, numsSize, 0, numsSize - 1, 0, returnSize);
    *returnColumnSizes = malloc(sizeof(int[*returnSize]));
    for (int i = 0; i < *returnSize; ++i) {
        (*returnColumnSizes)[i] = 3;
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391331223/
```

## 18. 四数之和

<https://leetcode.cn/problems/4sum/>

```c
int cmp(const void *a, const void *b) {
    int arg1 = *(const int *) a;
    int arg2 = *(const int *) b;
    return arg1 - arg2;
}

// 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的二元组
int **twoSum(const int *nums, int numsSize, int lo, int hi, long target, int *returnSize) {
    int capacity = 4;
    int **res = malloc(sizeof(int *) * capacity);
    *returnSize = 0;
    while (lo < hi) {
        int first = nums[lo], second = nums[hi];
        int sum = first + second;
        if (sum < target) {
            while (++lo < hi && nums[lo] == first) {}
        } else if (sum > target) {
            while (lo < --hi && nums[hi] == second) {}
        } else {
            int *t = malloc(sizeof(int[2]));
            t[0] = first;
            t[1] = second;
            if (*returnSize == capacity) {
                capacity *= 2;
                res = realloc(res, sizeof(int *) * capacity);
            }
            res[(*returnSize)++] = t;
            while (++lo < hi && nums[lo] == first) {}
            while (lo < --hi && nums[hi] == second) {}
        }
    }
    return res;
}

// 返回升序数组 nums[lo..hi] 中所有和为 target 且不重复的 k 元组
int **kSum(int k, const int *nums, int numsSize, int lo, int hi, long target, int *returnSize) {
    *returnSize = 0;
    if (hi - lo + 1 < k) {
        return NULL;
    }
    if (k == 2) {
        return twoSum(nums, numsSize, lo, hi, target, returnSize);
    }
    int capacity = 4;
    int **res = malloc(sizeof(int *) * capacity);
    int i = lo;
    while (i <= hi) {
        int curNum = nums[i];
        int size;
        int **sub = kSum(k - 1, nums, numsSize, i + 1, hi, target - curNum, &size);
        for (int j = 0; j < size; ++j) {
            sub[j] = realloc(sub[j], sizeof(int[k]));
            sub[j][k - 1] = curNum;
            if (*returnSize == capacity) {
                capacity *= 2;
                res = realloc(res, sizeof(int *) * capacity);
            }
            res[(*returnSize)++] = sub[j];
        }
        while (++i <= hi && nums[i] == curNum) {}
    }
    return res;
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **fourSum(int *nums, int numsSize, int target, int *returnSize, int **returnColumnSizes) {
    qsort(nums, numsSize, sizeof(int), cmp);
    int **ans = kSum(4, nums, numsSize, 0, numsSize - 1, target, returnSize);
    *returnColumnSizes = malloc(sizeof(int[*returnSize]));
    for (int i = 0; i < *returnSize; ++i) {
        (*returnColumnSizes)[i] = 4;
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391331753/
```

## 19. 删除链表的倒数第 N 个结点

<https://leetcode-cn.com/problems/remove-nth-node-from-end-of-list/>

```c
struct ListNode *removeNthFromEnd(struct ListNode *head, int n) {
    struct ListNode *dummyHead = malloc(sizeof(struct ListNode));
    dummyHead->val = -1;
    dummyHead->next = head;
    struct ListNode *slow = dummyHead;
    struct ListNode *fast = dummyHead;
    for (int i = 1; i <= n; ++i) {
        fast = fast->next;
    }
    while (fast != NULL && fast->next != NULL) {
        slow = slow->next;
        fast = fast->next;
    }
    struct ListNode *x = slow->next;
    if (x == head) { // 删除的是头结点
        head = head->next;
    } else {
        slow->next = x->next;
    }
    free(x);
    free(dummyHead);
    return head;
}
// https://leetcode.cn/submissions/detail/391143669/
```

## 20. 有效的括号

<https://leetcode-cn.com/problems/valid-parentheses/>

```c
typedef char Value;

struct MyListNode {
    Value val;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    int size;
} MyLinkedListStack;

MyLinkedListStack *myStackCreate() {
    MyLinkedListStack *obj = malloc(sizeof(MyLinkedListStack));
    obj->first = NULL;
    obj->size = 0;
    return obj;
}

void myStackPush(MyLinkedListStack *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
    } else {
        x->next = obj->first;
        obj->first = x;
    }
    obj->size++;
}

Value myStackPop(MyLinkedListStack *obj) {
    Value val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
    } else {
        obj->first = obj->first->next;
    }
    free(x);
    obj->size--;
    return val;
}

Value myStackPeek(MyLinkedListStack *obj) {
    return obj->first->val;
}

int myStackSize(MyLinkedListStack *obj) {
    return obj->size;
}

bool myStackEmpty(MyLinkedListStack *obj) {
    return obj->size == 0;
}

void myStackFree(MyLinkedListStack *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

bool isValid(char *s) {
    size_t n = strlen(s);
    if (n % 2 == 1) {
        return false;
    }
    MyLinkedListStack *stack = myStackCreate();
    for (int i = 0; i < n; ++i) {
        char c = s[i];
        switch (c) {
            case '(': {
                myStackPush(stack, ')');
                break;
            }
            case '[': {
                myStackPush(stack, ']');
                break;
            }
            case '{': {
                myStackPush(stack, '}');
                break;
            }
            default: {
                if (myStackEmpty(stack) || myStackPop(stack) != c) {
                    myStackFree(stack);
                    return false;
                }
            }
        }
    }
    bool ans = myStackEmpty(stack);
    myStackFree(stack);
    return ans;
}
// https://leetcode.cn/submissions/detail/391408357/
```

```c
typedef char Value;

typedef struct {
    Value *array;
    int capacity;
    int size;
} MyResizingArrayStack;

MyResizingArrayStack *myStackCreate() {
    MyResizingArrayStack *obj = malloc(sizeof(MyResizingArrayStack));
    obj->size = 0;
    obj->capacity = 8;
    obj->array = malloc(sizeof(Value) * obj->capacity);
    return obj;
}

void myStackResize(MyResizingArrayStack *obj, int capacity) {
    obj->array = realloc(obj->array, sizeof(Value) * capacity);
    obj->capacity = capacity;
}

void myStackPush(MyResizingArrayStack *obj, Value val) {
    if (obj->size == obj->capacity) {
        myStackResize(obj, obj->capacity * 2);
    }
    obj->array[obj->size++] = val;
}

Value myStackPop(MyResizingArrayStack *obj) {
    Value val = obj->array[obj->size - 1];
    obj->size--;
    if (obj->size > 0 && obj->size == obj->capacity / 4) {
        myStackResize(obj, obj->capacity / 2);
    }
    return val;
}

Value myStackPeek(MyResizingArrayStack *obj) {
    return obj->array[obj->size - 1];
}

int myStackSize(MyResizingArrayStack *obj) {
    return obj->size;
}

bool myStackEmpty(MyResizingArrayStack *obj) {
    return obj->size == 0;
}

void myStackFree(MyResizingArrayStack *obj) {
    free(obj->array);
    free(obj);
}

bool isValid(char *s) {
    size_t n = strlen(s);
    if (n % 2 == 1) {
        return false;
    }
    MyResizingArrayStack *stack = myStackCreate();
    for (int i = 0; i < n; ++i) {
        char c = s[i];
        switch (c) {
            case '(': {
                myStackPush(stack, ')');
                break;
            }
            case '[': {
                myStackPush(stack, ']');
                break;
            }
            case '{': {
                myStackPush(stack, '}');
                break;
            }
            default: {
                if (myStackEmpty(stack) || myStackPop(stack) != c) {
                    myStackFree(stack);
                    return false;
                }
            }
        }
    }
    bool ans = myStackEmpty(stack);
    myStackFree(stack);
    return ans;
}
// https://leetcode.cn/submissions/detail/391363710/
```

## 21. 合并两个有序链表

<https://leetcode-cn.com/problems/merge-two-sorted-lists/>

```c
struct ListNode *mergeTwoLists(struct ListNode *list1, struct ListNode *list2) {
    struct ListNode *dummyHead = malloc(sizeof(struct ListNode));
    dummyHead->val = 0;
    dummyHead->next = NULL;
    struct ListNode *ptr = dummyHead;
    while (list1 != NULL && list2 != NULL) {
        if (list1->val < list2->val) {
            ptr->next = list1;
            list1 = list1->next;
        } else {
            ptr->next = list2;
            list2 = list2->next;
        }
        ptr = ptr->next;
    }
    ptr->next = (list1 == NULL ? list2 : list1);
    struct ListNode *head = dummyHead->next;
    free(dummyHead);
    return head;
}
// https://leetcode.cn/submissions/detail/391146231/
```

## 22. 括号生成

<https://leetcode.cn/problems/generate-parentheses/>

```c
int left;  // 已使用的『左括号』数量
int right; // 已使用的『右括号』数量
char *path;   // 取 '(', ')' 为元素
int pathSize;
char **ans;
int ansSize;
int ansCapacity;

void backtrack(int n) {
    // 对于一个「合法」的括号字符串组合 p，必然对于任何 0 <= i < len(p) 都有：
    // 子串 p[0..i] 中左括号的数量都大于或等于右括号的数量
    if (left < right || left > n) {
        return;
    }
    // 一个「合法」括号组合的左括号数量一定等于右括号数量
    if (left == n && right == n) {
        char *res = calloc(2 * n + 1, sizeof(char));
        strcpy(res, path);
        if (ansSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(char *) * ansCapacity);

        }
        ans[ansSize++] = res;
        return;
    }
    // edge = 取 '(', ')' 为值
    // 使用『左括号』
    path[pathSize++] = '(';
    ++left;
    backtrack(n);
    --pathSize;
    --left;
    // 使用『右括号』
    path[pathSize++] = ')';
    ++right;
    backtrack(n);
    --pathSize;
    --right;
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
char **generateParenthesis(int n, int *returnSize) {
    path = calloc(2 * n + 1, sizeof(char));
    ansCapacity = 8;
    ans = malloc(sizeof(char *) * ansCapacity);
    ansSize = pathSize = 0;
    left = 0, right = 0;
    backtrack(n);
    *returnSize = ansSize;
    free(path);
    return ans;
}
// https://leetcode.cn/submissions/detail/391307976/
```

## 23. 合并 K 个升序链表

<https://leetcode-cn.com/problems/merge-k-sorted-lists/>

```c
struct ListNode *mergeTwoLists(struct ListNode *list1, struct ListNode *list2) {
    struct ListNode *dummyHead = malloc(sizeof(struct ListNode));
    dummyHead->val = 0;
    dummyHead->next = NULL;
    struct ListNode *ptr = dummyHead;
    while (list1 != NULL && list2 != NULL) {
        if (list1->val < list2->val) {
            ptr->next = list1;
            list1 = list1->next;
        } else {
            ptr->next = list2;
            list2 = list2->next;
        }
        ptr = ptr->next;
    }
    ptr->next = (list1 == NULL ? list2 : list1);
    struct ListNode *head = dummyHead->next;
    free(dummyHead);
    return head;
}

struct ListNode *mergeKListsRange(struct ListNode **lists, int lo, int hi) {
    if (lo > hi) {
        return NULL;
    }
    if (lo == hi) {
        return lists[lo];
    }
    int mid = lo + (hi - lo) / 2;
    struct ListNode *left = mergeKListsRange(lists, lo, mid);
    struct ListNode *right = mergeKListsRange(lists, mid + 1, hi);
    return mergeTwoLists(left, right);
}

struct ListNode *mergeKLists(struct ListNode **lists, int listsSize) {
    return mergeKListsRange(lists, 0, listsSize - 1);
}
// https://leetcode.cn/submissions/detail/391146811/
```

## 24. 两两交换链表中的节点

<https://leetcode-cn.com/problems/swap-nodes-in-pairs/>

```c
struct ListNode *swapPairs(struct ListNode *head) {
    if (head == NULL || head->next == NULL) {
        return head;
    }
    struct ListNode *x = head;
    struct ListNode *y = head->next;
    struct ListNode *z = head->next->next;
    y->next = x;
    x->next = swapPairs(z);
    return y;
}
// https://leetcode.cn/submissions/detail/388499130/
```

## 25. K 个一组翻转链表

<https://leetcode.cn/problems/reverse-nodes-in-k-group/>

```c
struct ListNode *reverseList(struct ListNode *head) {
    struct ListNode *reverseHead = NULL;
    while (head != NULL) {
        struct ListNode *x = head->next;
        head->next = reverseHead;
        reverseHead = head;
        head = x;
    }
    return reverseHead;
}

struct ListNode *reverseKGroup(struct ListNode *head, int k) {
    struct ListNode *ptr = head;
    for (int i = 1; i <= k - 1 && ptr != NULL; ++i) {
        ptr = ptr->next;
    }
    if (ptr == NULL) {
        return head;
    }
    struct ListNode *nextGroup = ptr->next;
    ptr->next = NULL;
    struct ListNode *reverseHead = reverseList(head);
    head->next = reverseKGroup(nextGroup, k);
    return reverseHead;
}
// https://leetcode.cn/submissions/detail/390357194/
```

## 26. 删除有序数组中的重复项

<https://leetcode.cn/problems/remove-duplicates-from-sorted-array/>

```c
void swap(int *a, int *b) {
    int t = *a;
    *a = *b;
    *b = t;
}

int removeDuplicates(int *nums, int numsSize) {
    // [0..i-1] 不重复元素区间
    // [i..j-1] 重复元素区间
    // [j..n-1] 扫描区间
    int i = 0, j = 0;
    while (j < numsSize) {
        while (j + 1 < numsSize && nums[j] == nums[j + 1]) {
            ++j;
        }
        swap(&nums[i++], &nums[j++]);
    }
    return i;
}
// https://leetcode.cn/submissions/detail/388245066/
```

## 27. 移除元素

<https://leetcode.cn/problems/remove-element/>

```c
void swap(int *a, int *b) {
    int t = *a;
    *a = *b;
    *b = t;
}

int removeElement(int *nums, int numsSize, int val) {
    // nums[0..i-1]   != val
    // nums[i..j]     Scanning
    // nums[j+1..n-1] == val
    int i = 0, j = numsSize - 1;
    while (i <= j) {
        while (i <= j && nums[i] != val) {
            ++i;
        }
        while (i <= j && nums[j] == val) {
            --j;
        }
        if (i <= j) {
            swap(&nums[i++], &nums[j--]);
        }
    }
    return i;
}
// https://leetcode.cn/submissions/detail/388242647/
```

## 28. 实现 strStr()

<https://leetcode.cn/problems/implement-strstr/>

```c
static const int R = 256;

int strStr(char *haystack, char *needle) {
    size_t n = strlen(haystack);
    size_t m = strlen(needle);
    int right[R];
    memset(right, -1, sizeof(right));
    for (int j = 0; j < m; ++j) {
        right[needle[j]] = j;
    }
    int skip;
    for (int i = 0; i + m <= n; i += skip) {
        skip = 0;
        for (int j = m - 1; j >= 0; --j) {
            if (needle[j] != haystack[i + j]) {
                skip = fmax(1, j - right[haystack[i + j]]);
                break;
            }
        }
        if (skip == 0) {
            return i;
        }
    }
    return -1;
}
// https://leetcode.cn/submissions/detail/391414985/
```

```c
static const int R = 256;

int strStr(char *haystack, char *needle) {
    size_t n = strlen(haystack);
    size_t m = strlen(needle);
    int dfa[R][m];
    memset(dfa, 0, sizeof(dfa));
    dfa[needle[0]][0] = 1;
    for (int x = 0, j = 1; j < m; ++j) {
        for (int c = 0; c < R; ++c) {
            dfa[c][j] = dfa[c][x];
        }
        dfa[needle[j]][j] = j + 1;
        x = dfa[needle[j]][x];
    }
    int i, j;
    for (i = 0, j = 0; i < n && j < m; ++i) {
        j = dfa[haystack[i]][j];
    }
    if (j == m) {
        return i - m;
    }
    return -1;
}
// https://leetcode.cn/submissions/detail/391414571/
```

## 33. 搜索旋转排序数组

<https://leetcode.cn/problems/search-in-rotated-sorted-array/>

```c
int search(const int *nums, int numsSize, int target) {
    int lo = 0, hi = numsSize - 1;
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
// https://leetcode.cn/submissions/detail/391135962/
```

## 34. 在排序数组中查找元素的第一个和最后一个位置

<https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/>

```c
int binarySearch(const int *nums, int numsSize, int target, bool lower) {
    int res = -1;
    int lo = 0, hi = numsSize - 1;
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

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *searchRange(const int *nums, int numsSize, int target, int *returnSize) {
    *returnSize = 2;
    int *ans = malloc(sizeof(int[*returnSize]));
    ans[0] = binarySearch(nums, numsSize, target, true);
    ans[1] = binarySearch(nums, numsSize, target, false);
    return ans;
}
// https://leetcode.cn/submissions/detail/391139603/
```

## 37. 解数独

<https://leetcode.cn/problems/sudoku-solver/>

```c
// board[row][col] 填入数字 ch 是否有效
bool isValid(char **board, int boardSize, int row, int col, char ch) {
    for (int i = 0; i < boardSize; ++i) {
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

// 遍历『决策森林』
// tree  = row
// level = (row, col)
bool backtrack(char **board, int boardSize, int row, int col) {
    bool res = false;
    if (row == boardSize - 1 && col == boardSize - 1) {
        res = true;
    } else if (row < boardSize - 1 && col == boardSize - 1) {
        // 遍历下一棵『决策树』
        res = backtrack(board, boardSize, row + 1, -1);
    } else if (board[row][col + 1] != '.') {
        res = backtrack(board, boardSize, row, col + 1);
    } else {
        // edge = ['1'..'9']
        for (char ch = '1'; ch <= '9'; ++ch) {
            if (isValid(board, boardSize, row, col + 1, ch)) {
                board[row][col + 1] = ch;
                res = backtrack(board, boardSize, row, col + 1);
                if (res) {
                    break;
                }
                board[row][col + 1] = '.';
            }
        }
    }
    return res;
}

void solveSudoku(char **board, int boardSize, int *boardColSize) {
    backtrack(board, boardSize, 0, -1);
}
// https://leetcode.cn/submissions/detail/390328577/
```

## 39. 组合总和

<https://leetcode.cn/problems/combination-sum/>

```c
int *path;
int pathSum;
int pathSize;
int pathCapacity;

int **ans;
int ansSize;
int *ansColSize;
int ansCapacity;

void backtrack(int *candidates, int candidatesSize, int target, int edge) {
    if (pathSum == target) {
        size_t n = sizeof(int[pathSize]);
        int *res = malloc(n);
        memcpy(res, path, n);
        if (ansSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(int *) * ansCapacity);
            ansColSize = realloc(ansColSize, sizeof(int[ansCapacity]));
        }
        ans[ansSize] = res;
        ansColSize[ansSize++] = pathSize;
        return;
    }
    if (edge == -1) {
        edge = 0;
    }
    // 避免重复，从 edge 开始选择
    // 例如 [1->2] 和 [2->1] 是重复的
    while (edge < candidatesSize) {
        int x = candidates[edge];
        if (pathSum + x <= target) {
            pathSum += x;
            if (pathSize == pathCapacity) {
                pathCapacity *= 2;
                path = realloc(path, sizeof(int[pathCapacity]));
            }
            path[pathSize++] = x;
            backtrack(candidates, candidatesSize, target, edge);
            pathSum -= x;
            --pathSize;
        }
        ++edge;
    }
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **combinationSum(int *candidates, int candidatesSize, int target, int *returnSize, int **returnColumnSizes) {
    ansCapacity = 8;
    ans = malloc(sizeof(int *) * ansCapacity);
    ansColSize = malloc(sizeof(int[ansCapacity]));
    pathCapacity = 8;
    path = malloc(sizeof(int[pathCapacity]));
    ansSize = pathSize = pathSum = 0;
    backtrack(candidates, candidatesSize, target, -1);
    *returnSize = ansSize;
    *returnColumnSizes = ansColSize;
    free(path);
    return ans;
}
// https://leetcode.cn/submissions/detail/391266359/
```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```c
int *path;
int pathSum;
int pathSize;
int pathCapacity;

int **ans;
int ansSize;
int *ansColSize;
int ansCapacity;

void backtrack(int *candidates, int candidatesSize, int target, int edge) {
    if (pathSum == target) {
        size_t n = sizeof(int[pathSize]);
        int *res = malloc(n);
        memcpy(res, path, n);
        if (ansSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(int *) * ansCapacity);
            ansColSize = realloc(ansColSize, sizeof(int[ansCapacity]));
        }
        ans[ansSize] = res;
        ansColSize[ansSize++] = pathSize;
        return;
    }
    int prev = INT_MIN;
    // 避免重复，从 edge 开始选择
    // 例如 [1->2] 和 [2->1] 是重复的
    while (++edge < candidatesSize) {
        int x = candidates[edge];
        if (x != prev && pathSum + x <= target) {
            prev = x;
            pathSum += x;
            if (pathSize == pathCapacity) {
                pathCapacity *= 2;
                path = realloc(path, sizeof(int[pathCapacity]));
            }
            path[pathSize++] = x;
            backtrack(candidates, candidatesSize, target, edge);
            pathSum -= x;
            --pathSize;
        }
    }
}

int cmp(const void *a, const void *b) {
    int arg1 = *(const int *) a;
    int arg2 = *(const int *) b;
    return arg1 - arg2;
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **combinationSum2(int *candidates, int candidatesSize, int target, int *returnSize, int **returnColumnSizes) {
    qsort(candidates, candidatesSize, sizeof(int), cmp);
    ansCapacity = 8;
    ans = malloc(sizeof(int *) * ansCapacity);
    ansColSize = malloc(sizeof(int[ansCapacity]));
    pathCapacity = 8;
    path = malloc(sizeof(int[pathCapacity]));
    ansSize = pathSize = pathSum = 0;
    backtrack(candidates, candidatesSize, target, -1);
    *returnSize = ansSize;
    *returnColumnSizes = ansColSize;
    free(path);
    return ans;
}
// https://leetcode.cn/submissions/detail/391276138/
```

## 42. 接雨水

<https://leetcode.cn/problems/trapping-rain-water/>

```c
int trap(int *height, int heightSize) {
    // leftMax[i] = max(height[0..i])
    int leftMax[heightSize];
    leftMax[0] = height[0];
    for (int i = 1; i <= heightSize - 1; ++i) {
        leftMax[i] = fmax(height[i], leftMax[i - 1]);
    }
    // rightMax[i] = max(height[i..heightSize-1])
    int rightMax[heightSize];
    rightMax[heightSize - 1] = height[heightSize - 1];
    for (int i = heightSize - 2; i >= 0; --i) {
        rightMax[i] = fmax(height[i], rightMax[i + 1]);
    }
    int sum = 0;
    for (int i = 0; i < heightSize; ++i) {
        sum += fmin(leftMax[i], rightMax[i]) - height[i];
    }
    return sum;
}
// https://leetcode.cn/submissions/detail/390335614/
```

## 46. 全排列

<https://leetcode.cn/problems/permutations/>

```c
int *path;
int pathSize;
bool *marked;

int **ans;
int ansSize;
int *ansColSize;
int ansCapacity;

void backtrack(int *nums, int numsSize) {
    if (pathSize == numsSize) {
        size_t n = sizeof(int[pathSize]);
        int *res = malloc(n);
        memcpy(res, path, n);
        if (ansSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(int *) * ansCapacity);
            ansColSize = realloc(ansColSize, sizeof(int[ansCapacity]));
        }
        ans[ansSize] = res;
        ansColSize[ansSize++] = pathSize;
        return;
    }
    // edge = 取数组 nums 的索引为值
    for (int edge = 0; edge < numsSize; ++edge) {
        if (!marked[edge]) {
            marked[edge] = true;
            path[pathSize++] = nums[edge];
            backtrack(nums, numsSize);
            marked[edge] = false;
            --pathSize;
        }
    }
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **permute(int *nums, int numsSize, int *returnSize, int **returnColumnSizes) {
    ansCapacity = 8;
    ans = malloc(sizeof(int *) * ansCapacity);
    ansColSize = malloc(sizeof(int[ansCapacity]));
    path = malloc(sizeof(int[numsSize]));
    ansSize = pathSize = 0;
    marked = malloc(sizeof(bool[numsSize]));
    memset(marked, 0, sizeof(bool[numsSize]));
    backtrack(nums, numsSize);
    *returnSize = ansSize;
    *returnColumnSizes = ansColSize;
    free(path);
    free(marked);
    return ans;
}
// https://leetcode.cn/submissions/detail/391276999/
```

## 47. 全排列 II

<https://leetcode.cn/problems/permutations-ii/>

```c
int *path;
int pathSize;
bool *marked;

int **ans;
int ansSize;
int *ansColSize;
int ansCapacity;

void backtrack(int *nums, int numsSize) {
    if (pathSize == numsSize) {
        size_t n = sizeof(int[pathSize]);
        int *res = malloc(n);
        memcpy(res, path, n);
        if (ansSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(int *) * ansCapacity);
            ansColSize = realloc(ansColSize, sizeof(int[ansCapacity]));
        }
        ans[ansSize] = res;
        ansColSize[ansSize++] = pathSize;
        return;
    }
    int prev = INT_MIN;
    // edge = 取数组 nums 的索引为值
    for (int edge = 0; edge < numsSize; ++edge) {
        int x = nums[edge];
        if (!marked[edge] && x != prev) {
            prev = x;
            marked[edge] = true;
            path[pathSize++] = x;
            backtrack(nums, numsSize);
            marked[edge] = false;
            --pathSize;
        }
    }
}

int cmp(const void *a, const void *b) {
    int arg1 = *(const int *) a;
    int arg2 = *(const int *) b;
    return arg1 - arg2;
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **permuteUnique(int *nums, int numsSize, int *returnSize, int **returnColumnSizes) {
    qsort(nums, numsSize, sizeof(int), cmp);
    ansCapacity = 8;
    ans = malloc(sizeof(int *) * ansCapacity);
    ansColSize = malloc(sizeof(int[ansCapacity]));
    path = malloc(sizeof(int[numsSize]));
    ansSize = pathSize = 0;
    marked = malloc(sizeof(bool[numsSize]));
    memset(marked, 0, sizeof(bool[numsSize]));
    backtrack(nums, numsSize);
    *returnSize = ansSize;
    *returnColumnSizes = ansColSize;
    free(path);
    free(marked);
    return ans;
}
// https://leetcode.cn/submissions/detail/391277468/
```

## 51. N 皇后

<https://leetcode.cn/problems/n-queens/>

```c
char ***ans;
int ansSize;
int ansCapacity;
int *ansColSize;

// board[row][col] 放置 Q 是否有效
bool isValid(char **board, int n, int row, int col) {
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

// level = row
void backtrack(char **board, int n, int row) {
    if (row == n - 1) {
        char **sol = malloc(sizeof(char *) * n);
        for (int i = 0; i < n; ++i) {
            sol[i] = calloc(n + 1, sizeof(char));
            strcpy(sol[i], board[i]);
        }
        if (ansSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(char *) * ansCapacity);
            ansColSize = realloc(ansColSize, sizeof(int[ansCapacity]));
        }
        ans[ansSize] = sol;
        ansColSize[ansSize++] = n;
        return;
    }
    // edge = col
    for (int col = 0; col < n; ++col) {
        if (isValid(board, n, row + 1, col)) {
            board[row + 1][col] = 'Q';
            backtrack(board, n, row + 1);
            board[row + 1][col] = '.';
        }
    }
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
char ***solveNQueens(int n, int *returnSize, int **returnColumnSizes) {
    ansSize = 0;
    ansCapacity = 8;
    ans = malloc(sizeof(char **) * ansCapacity);
    ansColSize = malloc(sizeof(int[ansCapacity]));
    char **board = malloc(sizeof(char *) * n);
    for (int i = 0; i < n; ++i) {
        board[i] = calloc(n + 1, sizeof(char));
        memset(board[i], '.', sizeof(char[n]));
    }
    backtrack(board, n, -1);
    *returnSize = ansSize;
    *returnColumnSizes = ansColSize;
    for (int i = 0; i < n; ++i) {
        free(board[i]);
    }
    free(board);
    return ans;
}
// https://leetcode.cn/submissions/detail/391342236/
```

## 52. N 皇后 II

<https://leetcode.cn/problems/n-queens-ii/>

```c
int ans;

// board[row][col] 放置 Q 是否有效
bool isValid(char **board, int n, int row, int col) {
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

// level = row
void backtrack(char **board, int n, int row) {
    if (row == n - 1) {
        ++ans;
        return;
    }
    // edge = col
    for (int col = 0; col < n; ++col) {
        if (isValid(board, n, row + 1, col)) {
            board[row + 1][col] = 'Q';
            backtrack(board, n, row + 1);
            board[row + 1][col] = '.';
        }
    }
}

int totalNQueens(int n) {
    ans = 0;
    char **board = malloc(sizeof(char *) * n);
    for (int i = 0; i < n; ++i) {
        board[i] = calloc(n + 1, sizeof(char));
        memset(board[i], '.', sizeof(char[n]));
    }
    backtrack(board, n, -1);
    for (int i = 0; i < n; ++i) {
        free(board[i]);
    }
    free(board);
    return ans;
}
// https://leetcode.cn/submissions/detail/390810027/
```

## 53. 最大子数组和

<https://leetcode.cn/problems/maximum-subarray/>

```c
int maxSubArray(int *nums, int numsSize) {
    // dp[i] = max({sum(subarray) | subarray 是以 nums[i] 结尾的子数组})
    int dp[numsSize];
    dp[0] = nums[0];
    int ans = dp[0];
    for (int i = 1; i < numsSize; ++i) {
        dp[i] = fmax(nums[i], nums[i] + dp[i - 1]);
        ans = fmax(ans, dp[i]);
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/390340097/
```

## 56. 合并区间

<https://leetcode.cn/problems/merge-intervals/>

```c
int cmp(const void *a, const void *b) {
    const int *arg1 = *(const int **) a;
    const int *arg2 = *(const int **) b;
    if (arg1[0] == arg2[0]) {
        return arg2[1] - arg1[1];
    }
    return arg1[0] - arg2[0];
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **merge(int **intervals, int intervalsSize, int *intervalsColSize, int *returnSize, int **returnColumnSizes) {
    qsort(intervals, intervalsSize, sizeof(int *), cmp);
    int **ans = malloc(sizeof(int *) * intervalsSize);
    *returnColumnSizes = malloc(sizeof(int[intervalsSize]));
    *returnSize = 0;
    int mStart = intervals[0][0];
    int mEnd = intervals[0][1];
    for (int i = 1; i < intervalsSize; ++i) {
        int start = intervals[i][0];
        int end = intervals[i][1];
        if (start <= mEnd) { // 重叠
            mEnd = fmax(mEnd, end);
        } else { // 不重叠
            int *t = malloc(sizeof(int[2]));
            t[0] = mStart;
            t[1] = mEnd;
            ans[*returnSize] = t;
            (*returnColumnSizes)[(*returnSize)++] = 2;
            mStart = start;
            mEnd = end;
        }
    }
    int *t = malloc(sizeof(int[2]));
    t[0] = mStart;
    t[1] = mEnd;
    ans[*returnSize] = t;
    (*returnColumnSizes)[(*returnSize)++] = 2;
    return ans;
}
// https://leetcode.cn/submissions/detail/391304543/
```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```c
// 从 grid[0][0] 到 grid[row][col] 的最小路径和
int minPathSumMemo(int **grid, int gridColSize, int row, int col, int *memo) {
    if (row < 0 || col < 0) {
        return INT_MAX;
    }
    if (row == 0 && col == 0) {
        return grid[row][col];
    }
    int *p = memo + row * gridColSize + col;
    if (*p == -1) {
        int sp1 = minPathSumMemo(grid, gridColSize, row - 1, col, memo);
        int sp2 = minPathSumMemo(grid, gridColSize, row, col - 1, memo);
        *p = fmin(sp1, sp2) + grid[row][col];
    }
    return *p;
}

int minPathSum(int **grid, int gridSize, const int *gridColSize) {
    int memo[gridSize][*gridColSize];
    for (int i = 0; i < gridSize; ++i) {
        for (int j = 0; j < *gridColSize; ++j) {
            memo[i][j] = -1;
        }
    }
    return minPathSumMemo(grid, *gridColSize, gridSize - 1, *gridColSize - 1, memo[0]);
}
// https://leetcode.cn/submissions/detail/391222469/
```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```c
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
// https://leetcode.cn/submissions/detail/391140272/
```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```c
int climbStairs(int n) {
    if (n == 1) {
        return 1;
    }
    if (n == 2) {
        return 2;
    }
    // dp[i] = 楼梯有 i 阶时，有几种不同的方法
    int *dp = (int *) malloc((n + 1) * sizeof(int));
    dp[1] = 1;
    dp[2] = 2;
    for (int i = 3; i <= n; i++) {
        dp[i] = dp[i - 1] + dp[i - 2];
    }
    int ans = dp[n];
    free(dp);
    return ans;
}
// https://leetcode.cn/submissions/detail/388295323/
```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```c
// 子串 s1[0..i] s2[0..j] 的最小编辑距离
int minDistanceMemo(const char *s1, int i, const char *s2, int j, int *memo) {
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
    int *p = memo + i * strlen(s2) + j;
    if (*p == -1) {
        if (s1[i] == s2[j]) {
            // s1[0..i-1][i]
            // s2[0..j-1][j]
            *p = minDistanceMemo(s1, i - 1, s2, j - 1, memo);
        } else {
            // 替换 s1[i] 为 s2[j]
            // s1[0..i-1][i]
            // s2[0..j-1][j]
            int sp1 = minDistanceMemo(s1, i - 1, s2, j - 1, memo) + 1;
            // 插入 s2[j] 到 s1
            // s1[0..i]
            // s2[0..j-1][j]
            int sp2 = minDistanceMemo(s1, i, s2, j - 1, memo) + 1;
            // 删除 s1[i]
            // s1[0..i-1][i]
            // s2[0..j]
            int sp3 = minDistanceMemo(s1, i - 1, s2, j, memo) + 1;
            *p = fmin(fmin(sp1, sp2), sp3);
        }
    }
    return *p;
}

int minDistance(char *word1, char *word2) {
    int n1 = strlen(word1);
    int n2 = strlen(word2);
    if (n1 == 0) {
        return n2;
    }
    if (n2 == 0) {
        return n1;
    }
    int memo[n1][n2];
    for (int i = 0; i < n1; ++i) {
        for (int j = 0; j < n2; ++j) {
            memo[i][j] = -1;
        }
    }
    return minDistanceMemo(word1, n1 - 1, word2, n2 - 1, memo[0]);
}
// https://leetcode.cn/submissions/detail/391221572/
```

```c
int **memo;

// 子串 s1[0..i] s2[0..j] 的最小编辑距离
int minDistanceMemo(const char *s1, int i, const char *s2, int j) {
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
            memo[i][j] = minDistanceMemo(s1, i - 1, s2, j - 1);
        } else {
            // 替换 s1[i] 为 s2[j]
            // s1[0..i-1][i]
            // s2[0..j-1][j]
            int sp1 = minDistanceMemo(s1, i - 1, s2, j - 1) + 1;
            // 插入 s2[j] 到 s1
            // s1[0..i]
            // s2[0..j-1][j]
            int sp2 = minDistanceMemo(s1, i, s2, j - 1) + 1;
            // 删除 s1[i]
            // s1[0..i-1][i]
            // s2[0..j]
            int sp3 = minDistanceMemo(s1, i - 1, s2, j) + 1;
            memo[i][j] = fmin(fmin(sp1, sp2), sp3);
        }
    }
    return memo[i][j];
}

int minDistance(char *word1, char *word2) {
    int n1 = strlen(word1);
    int n2 = strlen(word2);
    memo = malloc(sizeof(int *) * n1);
    for (int i = 0; i < n1; ++i) {
        memo[i] = malloc(sizeof(int) * n2);
        memset(memo[i], -1, sizeof(int) * n2);
    }
    int ans = minDistanceMemo(word1, n1 - 1, word2, n2 - 1);
    for (int i = 0; i < n1; ++i) {
        free(memo[i]);
    }
    free(memo);
    return ans;
}
// https://leetcode.cn/submissions/detail/391221155/
```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```c
void swap(int *a, int *b) {
    int t = *a;
    *a = *b;
    *b = t;
}

void sortColors(int *nums, int numsSize) {
    int v = 1;
    int i = 0, lt = 0, gt = numsSize - 1;
    while (i <= gt) {
        int x = nums[i];
        if (x < v) {
            swap(&nums[lt++], &nums[i++]);
        } else if (x > v) {
            swap(&nums[i], &nums[gt--]);
        } else {
            ++i;
        }
    }
}
// https://leetcode.cn/submissions/detail/388293077/
```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```c
typedef struct {
    int key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

char *minWindow(char *s, char *t) {
    size_t sLength = strlen(s), tLength = strlen(t);
    HashMapItem *need = NULL;
    for (int i = 0; i < tLength; ++i) {
        int ch = t[i];
        HashMapItem *needItem;
        HASH_FIND_INT(need, &ch, needItem);
        if (needItem == NULL) {
            needItem = malloc(sizeof(HashMapItem));
            needItem->key = ch;
            needItem->val = 0;
            HASH_ADD_INT(need, key, needItem);
        }
        needItem->val++;
    }
    int valid = 0;
    int start = 0, len = INT_MAX;
    // s[left..right) = Window Substring
    // s[right..tLength-1]  = Scanning
    int left = 0, right = 0;
    HashMapItem *window = NULL;
    while (right < sLength) {
        int add = s[right++];
        HashMapItem *needItem;
        HASH_FIND_INT(need, &add, needItem);
        if (needItem != NULL) {
            HashMapItem *winItem;
            HASH_FIND_INT(window, &add, winItem);
            if (winItem == NULL) {
                winItem = malloc(sizeof(HashMapItem));
                winItem->key = add;
                winItem->val = 0;
                HASH_ADD_INT(window, key, winItem);
            }
            if (++winItem->val == needItem->val) {
                ++valid;
            }
        }
        if (valid == HASH_COUNT(need)) {
            while (left <= right) {
                int del = s[left];
                HASH_FIND_INT(need, &del, needItem);
                HashMapItem *winItem;
                HASH_FIND_INT(window, &del, winItem);
                if (needItem != NULL && winItem->val == needItem->val) {
                    break;
                }
                if (needItem != NULL) {
                    winItem->val--;
                }
                ++left;
            }
            if (right - left < len) {
                start = left;
                len = right - left;
            }
        }
    }
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, need, cur, tmp) {
        HASH_DEL(need, cur);
        free(cur);
    }
    HASH_ITER(hh, window, cur, tmp) {
        HASH_DEL(window, cur);
        free(cur);
    }
    HASH_CLEAR(hh, need);
    HASH_CLEAR(hh, window);
    if (len < INT_MAX) {
        char *ans = calloc(len + 1, sizeof(char));
        strncpy(ans, s + start, len);
        return ans;
    }
    return "";
}
// https://leetcode.cn/submissions/detail/391352061/
```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```c
int *path;
int pathSize;

int **ans;
int ansSize;
int *ansColSize;
int ansCapacity;

// edge = 取 [1..n] 为值
void backtrack(int n, int k, int edge) {
    if (pathSize == k) {
        size_t size = sizeof(int[pathSize]);
        int *res = malloc(size);
        memcpy(res, path, size);
        if (ansSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(int *) * ansCapacity);
            ansColSize = realloc(ansColSize, sizeof(int[ansCapacity]));
        }
        ans[ansSize] = res;
        ansColSize[ansSize++] = pathSize;
        return;
    }
    // 避免重复，从 edge + 1 开始选择
    // 例如 [1->2] 和 [2->1] 是重复的
    while (++edge <= n) {
        path[pathSize++] = edge;
        backtrack(n, k, edge);
        --pathSize;
    }
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **combine(int n, int k, int *returnSize, int **returnColumnSizes) {
    ansCapacity = 8;
    ans = malloc(sizeof(int *) * ansCapacity);
    ansColSize = malloc(sizeof(int[ansCapacity]));
    path = malloc(sizeof(int[k]));
    ansSize = pathSize = 0;
    backtrack(n, k, 0);
    *returnSize = ansSize;
    *returnColumnSizes = ansColSize;
    free(path);
    return ans;
}
// https://leetcode.cn/submissions/detail/391269316/
```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```c
int *path;
int pathSize;

int **ans;
int ansSize;
int *ansColSize;

// edge = 取数组 nums 的索引为值
void backtrack(int *nums, int numsSize, int edge) {
    size_t n = sizeof(int[pathSize]);
    int *res = malloc(n);
    memcpy(res, path, n);
    ans[ansSize] = res;
    ansColSize[ansSize++] = pathSize;
    // 避免重复，从 edge + 1 开始选择
    // 例如 [1->2] 和 [2->1] 是重复的
    while (++edge < numsSize) {
        path[pathSize++] = nums[edge];
        backtrack(nums, numsSize, edge);
        --pathSize;
    }
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **subsets(int *nums, int numsSize, int *returnSize, int **returnColumnSizes) {
    *returnSize = 1 << numsSize;
    ans = malloc(sizeof(int *) * (*returnSize));
    ansColSize = malloc(sizeof(int[*returnSize]));
    path = malloc(sizeof(int[numsSize]));
    ansSize = pathSize = 0;
    backtrack(nums, numsSize, -1);
    *returnColumnSizes = ansColSize;
    free(path);
    return ans;
}
// https://leetcode.cn/submissions/detail/391268181/
```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```c
bool search(const int *nums, int numsSize, int target) {
    int lo = 0, hi = numsSize - 1;
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
// https://leetcode.cn/submissions/detail/391136413/
```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```c
struct ListNode *deleteDuplicates(struct ListNode *head) {
    struct ListNode *ptr = head;
    while (ptr != NULL && ptr->next != NULL) {
        if (ptr->val == ptr->next->val) {
            struct ListNode *x = ptr->next;
            ptr->next = x->next;
            free(x);
        } else {
            ptr = ptr->next;
        }
    }
    return head;
}
// https://leetcode.cn/submissions/detail/388678148/
```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```c
struct ListNode *partition(struct ListNode *head, int x) {
    struct ListNode *lessDummyHead = malloc(sizeof(struct ListNode));
    lessDummyHead->val = 0;
    lessDummyHead->next = NULL;
    struct ListNode *lessPtr = lessDummyHead;
    struct ListNode *greaterDummyHead = malloc(sizeof(struct ListNode));
    greaterDummyHead->val = 0;
    greaterDummyHead->next = NULL;
    struct ListNode *greaterPtr = greaterDummyHead;
    while (head != NULL) {
        if (head->val < x) {
            lessPtr->next = head;
            lessPtr = lessPtr->next;
        } else {
            greaterPtr->next = head;
            greaterPtr = greaterPtr->next;
        }
        head = head->next;
    }
    lessPtr->next = NULL;
    greaterPtr->next = NULL;
    lessPtr->next = greaterDummyHead->next;
    head = lessDummyHead->next;
    free(lessDummyHead);
    free(greaterDummyHead);
    return head;
}
// https://leetcode.cn/submissions/detail/390337923/
```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```c
int *path;
int pathSize;

int **ans;
int ansSize;
int *ansColSize;

// edge = 取数组 nums 的索引为值
void backtrack(int *nums, int numsSize, int edge) {
    size_t n = sizeof(int[pathSize]);
    int *res = malloc(n);
    memcpy(res, path, n);
    ans[ansSize] = res;
    ansColSize[ansSize++] = pathSize;
    int prev = INT_MIN;
    // 避免重复，从 edge + 1 开始选择
    // 例如 [1->2] 和 [2->1] 是重复的
    while (++edge < numsSize) {
        int x = nums[edge];
        if (x != prev) {
            prev = x;
            path[pathSize++] = x;
            backtrack(nums, numsSize, edge);
            --pathSize;
        }
    }
}

int cmp(const void *a, const void *b) {
    int arg1 = *(const int *) a;
    int arg2 = *(const int *) b;
    return arg1 - arg2;
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **subsetsWithDup(int *nums, int numsSize, int *returnSize, int **returnColumnSizes) {
    qsort(nums, numsSize, sizeof(int), cmp);
    const int MAXSIZE = 1 << numsSize;
    ans = malloc(sizeof(int *) * MAXSIZE);
    ansColSize = malloc(sizeof(int[MAXSIZE]));
    path = malloc(sizeof(int[numsSize]));
    ansSize = pathSize = 0;
    backtrack(nums, numsSize, -1);
    *returnSize = ansSize;
    *returnColumnSizes = ansColSize;
    free(path);
    return ans;
}
// https://leetcode.cn/submissions/detail/391268588/
```

## 92. 反转链表 II

<https://leetcode-cn.com/problems/reverse-linked-list-ii/>

```c
// 翻转链表的前 n 个节点，返回翻转后的头节点
struct ListNode *reverseList(struct ListNode *head, int n) {
    if (head == NULL || head->next == NULL || n <= 1) {
        return head;
    }
    struct ListNode *reverseHead = NULL;
    struct ListNode *ptr = head;
    while (ptr != NULL && n > 0) {
        struct ListNode *next = ptr->next;
        ptr->next = reverseHead;
        reverseHead = ptr;
        ptr = next;
        --n;
    }
    head->next = ptr;
    return reverseHead;
}

struct ListNode *reverseBetween(struct ListNode *head, int left, int right) {
    if (head == NULL || head->next == NULL) {
        return head;
    }
    if (left == 1) {
        return reverseList(head, right);
    }
    struct ListNode *ptr = head;
    for (int i = 1; i <= left - 2; ++i) {
        ptr = ptr->next;
    }
    ptr->next = reverseList(ptr->next, right - left + 1);
    return head;
}
// https://leetcode.cn/submissions/detail/390357612/
```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```c
int *ans;
int ansSize;

void dfs(struct TreeNode *root) {
    if (root == NULL) {
        return;
    }
    dfs(root->left);
    ans[ansSize++] = root->val;
    dfs(root->right);
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *inorderTraversal(struct TreeNode *root, int *returnSize) {
    ans = malloc(sizeof(int[100]));
    ansSize = 0;
    dfs(root);
    *returnSize = ansSize;
    return ans;
}
// https://leetcode.cn/submissions/detail/391148748/
```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```c
// 返回所有由 [lo..hi] 组成的节点值互不相同的不同二叉搜索树
struct TreeNode **generateTreesRange(int lo, int hi, int *returnSize) {
    if (lo > hi) {
        struct TreeNode **res = malloc(sizeof(struct TreeNode *));
        res[0] = NULL;
        *returnSize = 1;
        return res;
    }
    int capacity = 8;
    struct TreeNode **res = malloc(sizeof(struct TreeNode *) * capacity);
    *returnSize = 0;
    // 根节点为 i
    for (int i = lo; i <= hi; ++i) {
        // 左子树由 [lo..i-1] 组成
        int leftSize;
        struct TreeNode **leftTrees = generateTreesRange(lo, i - 1, &leftSize);
        // 右子树由 [i+1..hi] 组成
        int rightSize;
        struct TreeNode **rightTrees = generateTreesRange(i + 1, hi, &rightSize);
        for (int l = 0; l < leftSize; ++l) {
            for (int r = 0; r < rightSize; ++r) {
                struct TreeNode *root = malloc(sizeof(struct TreeNode));
                root->val = i;
                root->left = leftTrees[l];
                root->right = rightTrees[r];
                if (*returnSize == capacity) {
                    capacity *= 2;
                    res = realloc(res, sizeof(struct TreeNode *) * capacity);
                }
                res[(*returnSize)++] = root;
            }
        }
        free(leftTrees);
        free(rightTrees);
    }
    return res;
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
struct TreeNode **generateTrees(int n, int *returnSize) {
    return generateTreesRange(1, n, returnSize);
}
// https://leetcode.cn/submissions/detail/391154235/
```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```c
typedef struct {
    int key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

HashMapItem *memo = NULL;

int numTreesMemo(int n) {
    if (n == 0) {
        return 1;
    }
    HashMapItem *item;
    HASH_FIND_INT(memo, &n, item);
    if (item == NULL) {
        item = malloc(sizeof(HashMapItem));
        item->key = n;
        item->val = 0;
        // 根节点为 x_i
        for (int i = 1; i <= n; ++i) {
            // 左子树由 i-1 个数字 x1 < x2 < ... < x_i-1 组成
            int left = numTreesMemo(i - 1);
            // 右子树由 n-i 个数字 x_i+1 < x_i+2 < ... < x_n 组成
            int right = numTreesMemo(n - i);
            item->val += left * right;
        }
        HASH_ADD_INT(memo, key, item);
    }
    return item->val;
}

int numTrees(int n) {
    int ans = numTreesMemo(n);
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, memo, cur, tmp) {
        HASH_DEL(memo, cur);
        free(cur);
    }
    HASH_CLEAR(hh, memo);
    return ans;
}
// https://leetcode.cn/submissions/detail/391159484/
```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```c
bool bst;

// 检查二叉树是否在区间 (lower, upper) 内，递归过程中确定是否满足二叉搜索树的性质
bool lowerUpper(struct TreeNode *root, long lower, long upper) {
    if (root == NULL) {
        return true;
    }
    if (root->val <= lower || root->val >= upper) {
        bst = false;
        return false;
    }
    return lowerUpper(root->left, lower, root->val) &&
           lowerUpper(root->right, root->val, upper);
}

bool isValidBST(struct TreeNode *root) {
    bst = true;
    lowerUpper(root, LONG_MIN, LONG_MAX);
    return bst;
}
// https://leetcode.cn/submissions/detail/391165182/
```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```c
bool isSameTree(struct TreeNode *p, struct TreeNode *q) {
    if (p == NULL && q == NULL) {
        return true;
    }
    if (p == NULL || q == NULL || p->val != q->val) {
        return false;
    }
    return isSameTree(p->left, q->left) &&
           isSameTree(p->right, q->right);
}
// https://leetcode.cn/submissions/detail/391150354/
```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```c
static const int MAXSIZE = 2000;

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **levelOrder(struct TreeNode *root, int *returnSize, int **returnColumnSizes) {
    *returnSize = 0;
    *returnColumnSizes = malloc(sizeof(int) * MAXSIZE);
    int **ans = malloc(sizeof(int *) * MAXSIZE);
    struct TreeNode **queue = malloc(sizeof(struct TreeNode *) * MAXSIZE);
    int first = 0, last = 0;
    if (root != NULL) {
        queue[last++] = root;
    }
    while (first < last) {
        int n = last - first;
        int *level = malloc(sizeof(int) * n);
        for (int i = 0; i < n; ++i) {
            struct TreeNode *x = queue[first++];
            level[i] = x->val;
            struct TreeNode *left = x->left;
            if (left != NULL) {
                queue[last++] = left;
            }
            struct TreeNode *right = x->right;
            if (right != NULL) {
                queue[last++] = right;
            }
        }
        ans[*returnSize] = level;
        (*returnColumnSizes)[(*returnSize)++] = n;
    }
    free(queue);
    return ans;
}
// https://leetcode.cn/submissions/detail/390966123/
```

```c
typedef struct TreeNode *Value;

struct MyListNode {
    Value val;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    struct MyListNode *last;
    int size;
} MyLinkedListQueue;

MyLinkedListQueue *myQueueCreate() {
    MyLinkedListQueue *obj = malloc(sizeof(MyLinkedListQueue));
    obj->first = NULL;
    obj->last = NULL;
    obj->size = 0;
    return obj;
}

void myQueuePush(MyLinkedListQueue *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        obj->last->next = x;
        obj->last = x;
    }
    obj->size++;
}

Value myQueuePop(MyLinkedListQueue *obj) {
    Value val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->first = obj->first->next;
    }
    free(x);
    obj->size--;
    return val;
}

Value myQueuePeek(MyLinkedListQueue *obj) {
    return obj->first->val;
}

int myQueueSize(MyLinkedListQueue *obj) {
    return obj->size;
}

bool myQueueEmpty(MyLinkedListQueue *obj) {
    return obj->size == 0;
}

void myQueueFree(MyLinkedListQueue *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **levelOrder(struct TreeNode *root, int *returnSize, int **returnColumnSizes) {
    *returnSize = 0;
    int capacity = 8;
    int **ans = malloc(sizeof(int *) * capacity);
    *returnColumnSizes = malloc(sizeof(int[capacity]));
    MyLinkedListQueue *queue = myQueueCreate();
    if (root != NULL) {
        myQueuePush(queue, root);
    }
    while (!myQueueEmpty(queue)) {
        int size = myQueueSize(queue);
        int *level = malloc(sizeof(int[size]));
        for (int i = 0; i < size; ++i) {
            struct TreeNode *x = myQueuePop(queue);
            level[i] = x->val;
            struct TreeNode *left = x->left;
            if (left != NULL) {
                myQueuePush(queue, left);
            }
            struct TreeNode *right = x->right;
            if (right != NULL) {
                myQueuePush(queue, right);
            }
        }
        if (*returnSize == capacity) {
            capacity *= 2;
            ans = realloc(ans, sizeof(int *) * capacity);
            *returnColumnSizes = realloc(*returnColumnSizes, sizeof(int[capacity]));
        }
        ans[*returnSize] = level;
        (*returnColumnSizes)[(*returnSize)++] = size;
    }
    myQueueFree(queue);
    return ans;
}
// https://leetcode.cn/submissions/detail/391406846/
```

```c
typedef struct TreeNode *Value;

typedef struct {
    Value *array;
    int capacity;
    int size;
    int first;
    int last;
} MyResizingArrayQueue;

MyResizingArrayQueue *myQueueCreate() {
    MyResizingArrayQueue *obj = malloc(sizeof(MyResizingArrayQueue));
    obj->first = 0;
    obj->last = 0;
    obj->size = 0;
    obj->capacity = 8;
    obj->array = malloc(sizeof(Value) * obj->capacity);
    return obj;
}

void myQueueResize(MyResizingArrayQueue *obj, int capacity) {
    Value *copy = malloc(sizeof(Value) * capacity);
    for (int i = 0; i < obj->size; ++i) {
        copy[i] = obj->array[(obj->first + i) % obj->capacity];
    }
    free(obj->array);
    obj->array = copy;
    obj->first = 0;
    obj->last = obj->size;
    obj->capacity = capacity;
}

void myQueuePush(MyResizingArrayQueue *obj, Value val) {
    if (obj->size == obj->capacity) {
        myQueueResize(obj, obj->capacity * 2);
    }
    obj->array[obj->last++] = val;
    if (obj->last == obj->capacity) {
        obj->last = 0;
    }
    obj->size++;
}

Value myQueuePop(MyResizingArrayQueue *obj) {
    Value val = obj->array[obj->first++];
    if (obj->first == obj->capacity) {
        obj->first = 0;
    }
    obj->size--;
    if (obj->size > 0 && obj->size == obj->capacity / 4) {
        myQueueResize(obj, obj->capacity / 2);
    }
    return val;
}

Value myQueuePeek(MyResizingArrayQueue *obj) {
    return obj->array[obj->first];
}

int myQueueSize(MyResizingArrayQueue *obj) {
    return obj->size;
}

bool myQueueEmpty(MyResizingArrayQueue *obj) {
    return obj->size == 0;
}

void myQueueFree(MyResizingArrayQueue *obj) {
    free(obj->array);
    free(obj);
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **levelOrder(struct TreeNode *root, int *returnSize, int **returnColumnSizes) {
    *returnSize = 0;
    int capacity = 8;
    int **ans = malloc(sizeof(int *) * capacity);
    *returnColumnSizes = malloc(sizeof(int[capacity]));
    MyResizingArrayQueue *queue = myQueueCreate();
    if (root != NULL) {
        myQueuePush(queue, root);
    }
    while (!myQueueEmpty(queue)) {
        int size = myQueueSize(queue);
        int *level = malloc(sizeof(int[size]));
        for (int i = 0; i < size; ++i) {
            struct TreeNode *x = myQueuePop(queue);
            level[i] = x->val;
            struct TreeNode *left = x->left;
            if (left != NULL) {
                myQueuePush(queue, left);
            }
            struct TreeNode *right = x->right;
            if (right != NULL) {
                myQueuePush(queue, right);
            }
        }
        if (*returnSize == capacity) {
            capacity *= 2;
            ans = realloc(ans, sizeof(int *) * capacity);
            *returnColumnSizes = realloc(*returnColumnSizes, sizeof(int[capacity]));
        }
        ans[*returnSize] = level;
        (*returnColumnSizes)[(*returnSize)++] = size;
    }
    myQueueFree(queue);
    return ans;
}
// https://leetcode.cn/submissions/detail/391362861/
```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```c
typedef struct TreeNode *Value;

struct MyListNode {
    Value val;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    struct MyListNode *last;
    int size;
} MyLinkedListQueue;

MyLinkedListQueue *myQueueCreate() {
    MyLinkedListQueue *obj = malloc(sizeof(MyLinkedListQueue));
    obj->first = NULL;
    obj->last = NULL;
    obj->size = 0;
    return obj;
}

void myQueuePush(MyLinkedListQueue *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        obj->last->next = x;
        obj->last = x;
    }
    obj->size++;
}

Value myQueuePop(MyLinkedListQueue *obj) {
    Value val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->first = obj->first->next;
    }
    free(x);
    obj->size--;
    return val;
}

Value myQueuePeek(MyLinkedListQueue *obj) {
    return obj->first->val;
}

int myQueueSize(MyLinkedListQueue *obj) {
    return obj->size;
}

bool myQueueEmpty(MyLinkedListQueue *obj) {
    return obj->size == 0;
}

void myQueueFree(MyLinkedListQueue *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **zigzagLevelOrder(struct TreeNode *root, int *returnSize, int **returnColumnSizes) {
    *returnSize = 0;
    int capacity = 8;
    int **ans = malloc(sizeof(int *) * capacity);
    *returnColumnSizes = malloc(sizeof(int[capacity]));
    MyLinkedListQueue *queue = myQueueCreate();
    if (root != NULL) {
        myQueuePush(queue, root);
    }
    bool reverse = false;
    while (!myQueueEmpty(queue)) {
        int size = myQueueSize(queue);
        int *level = malloc(sizeof(int[size]));
        for (int i = 0; i < size; ++i) {
            struct TreeNode *x = myQueuePop(queue);
            level[i] = x->val;
            struct TreeNode *left = x->left;
            if (left != NULL) {
                myQueuePush(queue, left);
            }
            struct TreeNode *right = x->right;
            if (right != NULL) {
                myQueuePush(queue, right);
            }
        }
        if (reverse) {
            for (int i = 0, j = size - 1; i < j; ++i, --j) {
                int temp = level[i];
                level[i] = level[j];
                level[j] = temp;
            }
        }
        reverse = !reverse;
        if (*returnSize == capacity) {
            capacity *= 2;
            ans = realloc(ans, sizeof(int *) * capacity);
            *returnColumnSizes = realloc(*returnColumnSizes, sizeof(int[capacity]));
        }
        ans[*returnSize] = level;
        (*returnColumnSizes)[(*returnSize)++] = size;
    }
    myQueueFree(queue);
    return ans;
}
// https://leetcode.cn/submissions/detail/391407128/
```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```c
int maxDepth(struct TreeNode *root) {
    if (root == NULL) {
        return 0;
    }
    return 1 + fmax(maxDepth(root->left), maxDepth(root->right));
}
// https://leetcode.cn/submissions/detail/388684196/
```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```c
typedef struct {
    int key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

HashMapItem *valueToIndex = NULL;

struct TreeNode *buildTreeRange(const int *preorder, int preStart, int preEnd,
                                const int *inorder, int inStart, int inEnd) {
    if (preStart > preEnd) {
        return NULL;
    }
    int rootVal = preorder[preStart];
    struct TreeNode *root = malloc(sizeof(struct TreeNode));
    root->val = rootVal;
    HashMapItem *item;
    HASH_FIND_INT(valueToIndex, &rootVal, item);
    int inRoot = item->val;
    int leftSize = inRoot - inStart;
    root->left = buildTreeRange(preorder, preStart + 1, preStart + leftSize,
                                inorder, inStart, inRoot - 1);
    root->right = buildTreeRange(preorder, preStart + leftSize + 1, preEnd,
                                 inorder, inRoot + 1, inEnd);
    return root;
}

struct TreeNode *buildTree(const int *preorder, int preorderSize, const int *inorder, int inorderSize) {
    for (int i = 0; i < inorderSize; ++i) {
        HashMapItem *item = malloc(sizeof(HashMapItem));
        item->key = inorder[i];
        item->val = i;
        HASH_ADD_INT(valueToIndex, key, item);
    }
    struct TreeNode *root = buildTreeRange(preorder, 0, preorderSize - 1,
                                           inorder, 0, inorderSize - 1);
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, valueToIndex, cur, tmp) {
        HASH_DEL(valueToIndex, cur);
        free(cur);
    }
    HASH_CLEAR(hh, valueToIndex);
    return root;
}
// https://leetcode.cn/submissions/detail/391158225/
```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```c
typedef struct {
    int key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

HashMapItem *valueToIndex = NULL;

struct TreeNode *buildTreeRange(const int *inorder, int inStart, int inEnd,
                                const int *postorder, int postStart, int postEnd) {
    if (inStart > inEnd) {
        return NULL;
    }
    int rootVal = postorder[postEnd];
    struct TreeNode *root = malloc(sizeof(struct TreeNode));
    root->val = rootVal;
    HashMapItem *item;
    HASH_FIND_INT(valueToIndex, &rootVal, item);
    int inRoot = item->val;
    int leftSize = inRoot - inStart;
    root->left = buildTreeRange(inorder, inStart, inRoot - 1,
                                postorder, postStart, postStart + leftSize - 1);
    root->right = buildTreeRange(inorder, inRoot + 1, inEnd,
                                 postorder, postStart + leftSize, postEnd - 1);
    return root;
}

struct TreeNode *buildTree(const int *inorder, int inorderSize, const int *postorder, int postorderSize) {
    for (int i = 0; i < inorderSize; ++i) {
        HashMapItem *item = malloc(sizeof(HashMapItem));
        item->key = inorder[i];
        item->val = i;
        HASH_ADD_INT(valueToIndex, key, item);
    }
    struct TreeNode *root = buildTreeRange(inorder, 0, inorderSize - 1,
                                           postorder, 0, postorderSize - 1);
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, valueToIndex, cur, tmp) {
        HASH_DEL(valueToIndex, cur);
        free(cur);
    }
    HASH_CLEAR(hh, valueToIndex);
    return root;
}
// https://leetcode.cn/submissions/detail/391158622/
```

## 107. 二叉树的层序遍历 II

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```c
typedef struct TreeNode *Value;

struct MyListNode {
    Value val;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    struct MyListNode *last;
    int size;
} MyLinkedListQueue;

MyLinkedListQueue *myQueueCreate() {
    MyLinkedListQueue *obj = malloc(sizeof(MyLinkedListQueue));
    obj->first = NULL;
    obj->last = NULL;
    obj->size = 0;
    return obj;
}

void myQueuePush(MyLinkedListQueue *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        obj->last->next = x;
        obj->last = x;
    }
    obj->size++;
}

Value myQueuePop(MyLinkedListQueue *obj) {
    Value val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->first = obj->first->next;
    }
    free(x);
    obj->size--;
    return val;
}

Value myQueuePeek(MyLinkedListQueue *obj) {
    return obj->first->val;
}

int myQueueSize(MyLinkedListQueue *obj) {
    return obj->size;
}

bool myQueueEmpty(MyLinkedListQueue *obj) {
    return obj->size == 0;
}

void myQueueFree(MyLinkedListQueue *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **levelOrderBottom(struct TreeNode *root, int *returnSize, int **returnColumnSizes) {
    *returnSize = 0;
    int capacity = 8;
    int **ans = malloc(sizeof(int *) * capacity);
    *returnColumnSizes = malloc(sizeof(int[capacity]));
    MyLinkedListQueue *queue = myQueueCreate();
    if (root != NULL) {
        myQueuePush(queue, root);
    }
    while (!myQueueEmpty(queue)) {
        int size = myQueueSize(queue);
        int *level = malloc(sizeof(int[size]));
        for (int i = 0; i < size; ++i) {
            struct TreeNode *x = myQueuePop(queue);
            level[i] = x->val;
            struct TreeNode *left = x->left;
            if (left != NULL) {
                myQueuePush(queue, left);
            }
            struct TreeNode *right = x->right;
            if (right != NULL) {
                myQueuePush(queue, right);
            }
        }
        if (*returnSize == capacity) {
            capacity *= 2;
            ans = realloc(ans, sizeof(int *) * capacity);
            *returnColumnSizes = realloc(*returnColumnSizes, sizeof(int[capacity]));
        }
        ans[*returnSize] = level;
        (*returnColumnSizes)[(*returnSize)++] = size;
    }
    myQueueFree(queue);
    for (int i = 0, j = *returnSize - 1; i < j; ++i, --j) {
        int *temp1 = ans[i];
        ans[i] = ans[j];
        ans[j] = temp1;
        int temp2 = (*returnColumnSizes)[i];
        (*returnColumnSizes)[i] = (*returnColumnSizes)[j];
        (*returnColumnSizes)[j] = temp2;
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391407366/
```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```c
// 将有序数组 nums[lo..hi] 转换为二叉搜索树
struct TreeNode *sortedArrayToBSTRange(const int *nums, int lo, int hi) {
    if (lo > hi) {
        return NULL;
    }
    int mid = lo + (hi - lo) / 2;
    struct TreeNode *root = malloc(sizeof(struct TreeNode));
    root->val = nums[mid];
    root->left = sortedArrayToBSTRange(nums, lo, mid - 1);
    root->right = sortedArrayToBSTRange(nums, mid + 1, hi);
    return root;
}

struct TreeNode *sortedArrayToBST(const int *nums, int numsSize) {
    return sortedArrayToBSTRange(nums, 0, numsSize - 1);
}
// https://leetcode.cn/submissions/detail/389152259/
```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```c
bool balanced;

int height(struct TreeNode *root) {
    if (root == NULL) {
        return -1;
    }
    int left = height(root->left);
    int right = height(root->right);
    if (abs(left - right) > 1) {
        balanced = false;
    }
    return 1 + fmax(left, right);
}

bool isBalanced(struct TreeNode *root) {
    balanced = true;
    height(root);
    return balanced;
}
// https://leetcode.cn/submissions/detail/391163480/
```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```c
static const int MAXSIZE = 100000;

int minDepth(struct TreeNode *root) {
    struct TreeNode **queue = malloc(sizeof(struct TreeNode *) * MAXSIZE);
    int first = 0, last = 0;
    if (root != NULL) {
        queue[last++] = root;
    }
    int depth = 0;
    while (first < last) {
        ++depth;
        int n = last - first;
        for (int i = 0; i < n; ++i) {
            struct TreeNode *x = queue[first++];
            struct TreeNode *left = x->left;
            struct TreeNode *right = x->right;
            if (left == NULL && right == NULL) {
                return depth;
            }
            if (left != NULL) {
                queue[last++] = left;
            }
            if (right != NULL) {
                queue[last++] = right;
            }
        }
    }
    free(queue);
    return depth;
}
// https://leetcode.cn/submissions/detail/391289096/
```

```c
typedef struct TreeNode *Value;

struct MyListNode {
    Value val;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    struct MyListNode *last;
    int size;
} MyLinkedListQueue;

MyLinkedListQueue *myQueueCreate() {
    MyLinkedListQueue *obj = malloc(sizeof(MyLinkedListQueue));
    obj->first = NULL;
    obj->last = NULL;
    obj->size = 0;
    return obj;
}

void myQueuePush(MyLinkedListQueue *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        obj->last->next = x;
        obj->last = x;
    }
    obj->size++;
}

Value myQueuePop(MyLinkedListQueue *obj) {
    Value val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->first = obj->first->next;
    }
    free(x);
    obj->size--;
    return val;
}

Value myQueuePeek(MyLinkedListQueue *obj) {
    return obj->first->val;
}

int myQueueSize(MyLinkedListQueue *obj) {
    return obj->size;
}

bool myQueueEmpty(MyLinkedListQueue *obj) {
    return obj->size == 0;
}

void myQueueFree(MyLinkedListQueue *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

int minDepth(struct TreeNode *root) {
    MyLinkedListQueue *queue = myQueueCreate();
    if (root != NULL) {
        myQueuePush(queue, root);
    }
    int depth = 0;
    while (!myQueueEmpty(queue)) {
        ++depth;
        int n = myQueueSize(queue);
        for (int i = 0; i < n; ++i) {
            struct TreeNode *x = myQueuePop(queue);
            struct TreeNode *left = x->left;
            struct TreeNode *right = x->right;
            if (left == NULL && right == NULL) {
                return depth;
            }
            if (left != NULL) {
                myQueuePush(queue, left);
            }
            if (right != NULL) {
                myQueuePush(queue, right);
            }
        }
    }
    myQueueFree(queue);
    return depth;
}
// https://leetcode.cn/submissions/detail/391407645/
```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```c
bool hasPathSum(struct TreeNode *root, int targetSum) {
    if (root == NULL) {
        return false;
    }
    if (root->left == NULL && root->right == NULL) {
        return root->val == targetSum;
    }
    return hasPathSum(root->left, targetSum - root->val) ||
           hasPathSum(root->right, targetSum - root->val);
}
// https://leetcode.cn/submissions/detail/390331714/
```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```c
void flatten(struct TreeNode *root) {
    if (root == NULL) {
        return;
    }
    flatten(root->left);
    flatten(root->right);
    struct TreeNode *left = root->left;
    struct TreeNode *right = root->right;
    root->left = NULL;
    root->right = left;
    struct TreeNode *ptr = root;
    while (ptr->right != NULL) {
        ptr = ptr->right;
    }
    ptr->right = right;
}
// https://leetcode.cn/submissions/detail/390002505/
```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```c
// TODO
```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```c
int maxProfit(int *prices, int pricesSize) {
    // dp[i][0] = 第 i 天，空仓状态下的最大利润
    // dp[i][1] = 第 i 天，持仓状态下的最大利润
    int dp[pricesSize][2];
    dp[0][0] = 0;
    dp[0][1] = -prices[0];
    for (int i = 1; i < pricesSize; ++i) {
        // dp[i - 1][0]             >= -prices[i]
        // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
        // => dp[i][0] >= dp[i][1]
        dp[i][0] = fmax(dp[i - 1][0], dp[i - 1][1] + prices[i]);
        dp[i][1] = fmax(-prices[i], dp[i - 1][1]);
    }
    return dp[pricesSize - 1][0];
}
// https://leetcode.cn/submissions/detail/390320586/
```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```c
int maxProfit(int *prices, int pricesSize) {
    // dp[i][0] = 第 i 天，空仓状态下的最大利润
    // dp[i][1] = 第 i 天，持仓状态下的最大利润
    int dp[pricesSize][2];
    dp[0][0] = 0;
    dp[0][1] = -prices[0];
    for (int i = 1; i < pricesSize; ++i) {
        // dp[i - 1][0]             >= dp[i - 1][0] - prices[i]
        // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
        // => dp[i][0] >= dp[i][1]
        dp[i][0] = fmax(dp[i - 1][0], dp[i - 1][1] + prices[i]);
        dp[i][1] = fmax(dp[i - 1][0] - prices[i], dp[i - 1][1]);
    }
    return dp[pricesSize - 1][0];
}
// https://leetcode.cn/submissions/detail/390321320/
```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```c
int maxProfitK(int k, int *prices, int pricesSize) {
    if (k <= 0 || pricesSize <= 1) {
        return 0;
    }
    // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
    // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
    int dp[k + 1][pricesSize][2];
    // 交易次数限制为 0 时
    // 填写第 0 个 pricesSize x 2 矩阵
    for (int i = 0; i < pricesSize; ++i) {
        dp[0][i][0] = 0;
        dp[0][i][1] = INT_MIN;
    }
    // 交易次数限制为 [1..k] 时
    for (int t = 1; t <= k; ++t) {
        // 填写第 t 个 pricesSize x 2 矩阵
        dp[t][0][0] = 0;
        dp[t][0][1] = -prices[0];
        for (int i = 1; i < pricesSize; ++i) {
            // dp[t][i - 1][0]             >= dp[t - 1][i - 1][0] - prices[i]
            // dp[t][i - 1][1] + prices[i] >= dp[t][i - 1][1]
            // => dp[t][i][0] >= dp[t][i][1]
            dp[t][i][0] = fmax(dp[t][i - 1][0], dp[t][i - 1][1] + prices[i]);
            dp[t][i][1] = fmax(dp[t - 1][i - 1][0] - prices[i], dp[t][i - 1][1]);
        }
    }
    return dp[k][pricesSize - 1][0];
}

int maxProfit(int *prices, int pricesSize) {
    return maxProfitK(2, prices, pricesSize);
}
// https://leetcode.cn/submissions/detail/390324243/
```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```c
bool isPalindrome(char *s) {
    int n = strlen(s);
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
// https://leetcode.cn/submissions/detail/390150971/
```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```c
typedef struct {
    int key;
    UT_hash_handle hh;
} HashSetItem;

int longestConsecutive(int *nums, int numsSize) {
    int ans = 0;
    HashSetItem *set = NULL;
    for (int i = 0; i < numsSize; ++i) {
        HashSetItem *item;
        HASH_FIND_INT(set, &nums[i], item);
        if (item == NULL) {
            item = malloc(sizeof(HashSetItem));
            item->key = nums[i];
            HASH_ADD_INT(set, key, item);
        }
    }
    for (int i = 0; i < numsSize; ++i) {
        HashSetItem *item;
        HASH_FIND_INT(set, &nums[i], item);
        if (item != NULL) {
            HASH_DEL(set, item);
            free(item);
            int lo = nums[i] - 1;
            HASH_FIND_INT(set, &lo, item);
            while (item != NULL) {
                HASH_DEL(set, item);
                free(item);
                --lo;
                HASH_FIND_INT(set, &lo, item);
            }
            int hi = nums[i] + 1;
            HASH_FIND_INT(set, &hi, item);
            while (item != NULL) {
                HASH_DEL(set, item);
                free(item);
                ++hi;
                HASH_FIND_INT(set, &hi, item);
            }
            ans = fmax(ans, hi - lo - 1);
        }
    }
    HashSetItem *cur, *tmp;
    HASH_ITER(hh, set, cur, tmp) {
        HASH_DEL(set, cur);
        free(cur);
    }
    HASH_CLEAR(hh, set);
    return ans;
}
// https://leetcode.cn/submissions/detail/391280643/
```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```c
static const char LAND = 'O';
static const char WATER = 'X';

bool mark;
int *recovery;
int recoverySize;
int recoveryCapacity;

void floodFill(char **grid, int gridSize, int *gridColSize, int row, int col) {
    if (row < 0 || row >= gridSize || col < 0 || col >= *gridColSize || grid[row][col] == WATER) {
        return;
    }
    if (mark) {
        if (recoverySize == recoveryCapacity) {
            recoveryCapacity *= 2;
            recovery = realloc(recovery, sizeof(int[recoveryCapacity]));
        }
        recovery[recoverySize++] = row * (*gridColSize) + col;
    }
    grid[row][col] = WATER;
    floodFill(grid, gridSize, gridColSize, row, col + 1);
    floodFill(grid, gridSize, gridColSize, row, col - 1);
    floodFill(grid, gridSize, gridColSize, row + 1, col);
    floodFill(grid, gridSize, gridColSize, row - 1, col);
}

void solve(char **grid, int gridSize, int *gridColSize) {
    int m = gridSize, n = *gridColSize;
    recoverySize = 0;
    recoveryCapacity = 8;
    recovery = malloc(sizeof(int[recoveryCapacity]));
    mark = true;
    // 淹没与左右边界的陆地相连的岛屿
    for (int row = 0; row < m; ++row) {
        floodFill(grid, gridSize, gridColSize, row, 0);
        floodFill(grid, gridSize, gridColSize, row, n - 1);
    }
    // 淹没与上下边界的陆地相连的岛屿
    for (int col = 0; col < n; ++col) {
        floodFill(grid, gridSize, gridColSize, 0, col);
        floodFill(grid, gridSize, gridColSize, m - 1, col);
    }
    mark = false;
    for (int row = 0; row < m; ++row) {
        for (int col = 0; col < n; ++col) {
            if (grid[row][col] == LAND) {
                floodFill(grid, gridSize, gridColSize, row, col);
            }
        }
    }
    for (int i = 0; i < recoverySize; ++i) {
        int row = recovery[i] / n;
        int col = recovery[i] % n;
        grid[row][col] = LAND;
    }
    free(recovery);
}
// https://leetcode.cn/submissions/detail/391344274/
```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```c
int singleNumber(const int *nums, int numsSize) {
    int ans = 0;
    for (int i = 0; i < numsSize; ++i) {
        ans ^= nums[i];
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/388266983/
```

## 141. 环形链表

<https://leetcode-cn.com/problems/linked-list-cycle/>

```c
bool hasCycle(struct ListNode *head) {
    struct ListNode *slow = head;
    struct ListNode *fast = head;
    while (fast != NULL && fast->next != NULL) {
        slow = slow->next;
        fast = fast->next->next;
        if (slow == fast) {
            return true;
        }
    }
    return false;
}
// https://leetcode.cn/submissions/detail/388496398/
```

## 142. 环形链表 II

<https://leetcode-cn.com/problems/linked-list-cycle-ii/>

```c
struct ListNode *detectCycle(struct ListNode *head) {
    struct ListNode *slow = head;
    struct ListNode *fast = head;
    while (fast != NULL && fast->next != NULL) {
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
    return NULL;
}
// https://leetcode.cn/submissions/detail/388497010/
```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```c
struct ListNode *reverseList(struct ListNode *head) {
    struct ListNode *reverseHead = NULL;
    while (head != NULL) {
        struct ListNode *x = head->next;
        head->next = reverseHead;
        reverseHead = head;
        head = x;
    }
    return reverseHead;
}

void reorderList(struct ListNode *head) {
    struct ListNode *slow = head;
    struct ListNode *fast = head;
    while (fast->next != NULL && fast->next->next != NULL) {
        slow = slow->next;
        fast = fast->next->next;
    }
    struct ListNode *x = slow->next;
    slow->next = NULL;
    struct ListNode *reverseHead = reverseList(x);
    struct ListNode *dummyHead = malloc(sizeof(struct ListNode));
    dummyHead->val = 0;
    dummyHead->next = NULL;
    struct ListNode *ptr = dummyHead;
    while (head != NULL) {
        if (head != NULL) {
            ptr->next = head;
            ptr = ptr->next;
            head = head->next;
        }
        if (reverseHead != NULL) {
            ptr->next = reverseHead;
            ptr = ptr->next;
            reverseHead = reverseHead->next;
        }
    }
    free(dummyHead);
}
// https://leetcode.cn/submissions/detail/390337010/
```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```c
int *ans;
int ansSize;

void dfs(struct TreeNode *root) {
    if (root == NULL) {
        return;
    }
    ans[ansSize++] = root->val;
    dfs(root->left);
    dfs(root->right);
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *preorderTraversal(struct TreeNode *root, int *returnSize) {
    ans = malloc(sizeof(int[100]));
    ansSize = 0;
    dfs(root);
    *returnSize = ansSize;
    return ans;
}
// https://leetcode.cn/submissions/detail/391148343/
```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```c
int *ans;
int ansSize;

void dfs(struct TreeNode *root) {
    if (root == NULL) {
        return;
    }
    dfs(root->left);
    dfs(root->right);
    ans[ansSize++] = root->val;
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *postorderTraversal(struct TreeNode *root, int *returnSize) {
    ans = malloc(sizeof(int[100]));
    ansSize = 0;
    dfs(root);
    *returnSize = ansSize;
    return ans;
}
// https://leetcode.cn/submissions/detail/391149127/
```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```c
struct MyListNode {
    int key;
    int val;
    struct MyListNode *prev;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    struct MyListNode *last;
    int size;
} MyDoublyLinkedList;

MyDoublyLinkedList *myListCreate() {
    MyDoublyLinkedList *obj = malloc(sizeof(MyDoublyLinkedList));
    obj->first = NULL;
    obj->last = NULL;
    obj->size = 0;
    return obj;
}

void myListAddLast(MyDoublyLinkedList *obj, struct MyListNode *x) {
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        obj->last->next = x;
        x->prev = obj->last;
        obj->last = x;
    }
    obj->size++;
}

void myListRemoveFirst(MyDoublyLinkedList *obj) {
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->first = obj->first->next;
        obj->first->prev = NULL;
    }
    free(x);
    obj->size--;
}

void myListRemoveLast(MyDoublyLinkedList *obj) {
    struct MyListNode *x = obj->last;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->last = obj->last->prev;
        obj->last->next = NULL;
    }
    free(x);
    obj->size--;
}

void myListRemove(MyDoublyLinkedList *obj, struct MyListNode *x) {
    if (x == obj->first) {
        myListRemoveFirst(obj);
    } else if (x == obj->last) {
        myListRemoveLast(obj);
    } else {
        x->prev->next = x->next;
        x->next->prev = x->prev;
        free(x);
        obj->size--;
    }
}

struct MyListNode *myListGetFirst(MyDoublyLinkedList *obj) {
    return obj->first;
}

bool myListEmpty(MyDoublyLinkedList *obj) {
    return obj->first == NULL;
}

void myListFree(MyDoublyLinkedList *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

typedef struct {
    int key;
    struct MyListNode *val;
    UT_hash_handle hh;
} HashMapItem;

typedef struct {
    MyDoublyLinkedList *list;
    HashMapItem *keyToNode;
    int capacity;
} LRUCache;

LRUCache *lRUCacheCreate(int capacity) {
    LRUCache *obj = malloc(sizeof(LRUCache));
    obj->list = myListCreate();
    obj->keyToNode = NULL;
    obj->capacity = capacity;
    return obj;
}

bool lRUCacheContains(LRUCache *obj, int key) {
    HashMapItem *item;
    HASH_FIND_INT(obj->keyToNode, &key, item);
    return item != NULL;
}

bool lRUCacheFull(LRUCache *obj) {
    return HASH_COUNT(obj->keyToNode) == obj->capacity;
}

void lRUCacheAdd(LRUCache *obj, int key, int val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->key = key;
    x->val = val;
    x->prev = NULL;
    x->next = NULL;
    myListAddLast(obj->list, x);
    HashMapItem *item = malloc(sizeof(HashMapItem));
    item->key = key;
    item->val = x;
    HASH_ADD_INT(obj->keyToNode, key, item);
}

void lRUCacheRemove(LRUCache *obj) {
    int key = myListGetFirst(obj->list)->key;
    myListRemoveFirst(obj->list);
    HashMapItem *item;
    HASH_FIND_INT(obj->keyToNode, &key, item);
    HASH_DEL(obj->keyToNode, item);
    free(item);
}

int lRUCacheTouch(LRUCache *obj, int key, int val) {
    HashMapItem *item;
    HASH_FIND_INT(obj->keyToNode, &key, item);
    struct MyListNode *x = item->val;
    int newVal = x->val;
    if (val != INT_MIN) {
        newVal = val;
    }
    myListRemove(obj->list, x);
    x = malloc(sizeof(struct MyListNode));
    x->key = key;
    x->val = newVal;
    x->prev = NULL;
    x->next = NULL;
    myListAddLast(obj->list, x);
    item->val = x;
    return newVal;
}

int lRUCacheGet(LRUCache *obj, int key) {
    if (lRUCacheContains(obj, key)) {
        return lRUCacheTouch(obj, key, INT_MIN);
    }
    return -1;
}

void lRUCachePut(LRUCache *obj, int key, int val) {
    if (obj->capacity > 0) {
        if (lRUCacheContains(obj, key)) {
            lRUCacheTouch(obj, key, val);
        } else {
            if (lRUCacheFull(obj)) {
                lRUCacheRemove(obj);
            }
            lRUCacheAdd(obj, key, val);
        }
    }
}

void lRUCacheFree(LRUCache *obj) {
    myListFree(obj->list);
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, obj->keyToNode, cur, tmp) {
        HASH_DEL(obj->keyToNode, cur);
        free(cur);
    }
    HASH_CLEAR(hh, obj->keyToNode);
    free(obj);
}
// https://leetcode.cn/submissions/detail/391164207/
```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```c
int findMin(const int *nums, int numsSize) {
    int lo = 0, hi = numsSize - 1;
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
// https://leetcode.cn/submissions/detail/388261001/
```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```c
typedef struct {
    int **array;
    int capacity;
    int size;
} MinStack;

MinStack *minStackCreate() {
    MinStack *obj = malloc(sizeof(MinStack));
    obj->size = 0;
    obj->capacity = 8;
    obj->array = malloc(sizeof(int *) * obj->capacity);
    return obj;
}

void minStackPush(MinStack *obj, int val) {
    if (obj->size == obj->capacity) {
        obj->capacity *= 2;
        obj->array = realloc(obj->array, sizeof(int *) * obj->capacity);
    }
    int min;
    if (obj->size == 0) {
        min = val;
    } else {
        min = fmin(val, obj->array[obj->size - 1][1]);
    }
    int *x = malloc(sizeof(int[2]));
    x[0] = val;
    x[1] = min;
    obj->array[obj->size++] = x;
}

void minStackPop(MinStack *obj) {
    free(obj->array[obj->size - 1]);
    obj->size--;
    if (obj->size > 0 && obj->size == obj->capacity / 4) {
        obj->capacity /= 2;
        obj->array = realloc(obj->array, sizeof(int *) * obj->capacity);
    }
}

int minStackTop(MinStack *obj) {
    return obj->array[obj->size - 1][0];
}

int minStackGetMin(MinStack *obj) {
    return obj->array[obj->size - 1][1];
}

void minStackFree(MinStack *obj) {
    while (obj->size > 0) {
        free(obj->array[obj->size - 1]);
        obj->size--;
    }
    free(obj);
}
// https://leetcode.cn/submissions/detail/391358555/
```

```c
struct MyListNode {
    int val;
    int min;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
} MinStack;

MinStack *minStackCreate() {
    MinStack *obj = malloc(sizeof(MinStack));
    obj->first = NULL;
    return obj;
}

void minStackPush(MinStack *obj, int val) {
    int min;
    if (obj->first == NULL) {
        min = val;
    } else {
        min = fmin(val, obj->first->min);
    }
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->min = min;
    x->next = obj->first;
    obj->first = x;
}

void minStackPop(MinStack *obj) {
    struct MyListNode *x = obj->first;
    if (x->next == NULL) {
        obj->first = NULL;
    } else {
        obj->first = obj->first->next;
    }
    free(x);
}

int minStackTop(MinStack *obj) {
    return obj->first->val;
}

int minStackGetMin(MinStack *obj) {
    return obj->first->min;
}

void minStackFree(MinStack *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}
// https://leetcode.cn/submissions/detail/391358999/
```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```c
struct ListNode *getIntersectionNode(struct ListNode *headA, struct ListNode *headB) {
    struct ListNode *ptrA = headA;
    struct ListNode *ptrB = headB;
    while (ptrA != ptrB) {
        ptrA = (ptrA == NULL ? headB : ptrA->next);
        ptrB = (ptrB == NULL ? headA : ptrB->next);
    }
    return ptrA;
}
// https://leetcode.cn/submissions/detail/388496097/
```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```c
int compareVersion(char *version1, char *version2) {
    size_t n1 = strlen(version1);
    size_t n2 = strlen(version2);
    int i = 0, j = 0;
    while (i < n1 || j < n2) {
        int r1 = 0;
        while (i < n1) {
            char c = version1[i++];
            if (c == '.') {
                break;
            }
            r1 = r1 * 10 + (c - '0');
        }
        int r2 = 0;
        while (j < n2) {
            char c = version2[j++];
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
// https://leetcode.cn/submissions/detail/391412644/
```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```c
/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *twoSum(const int *numbers, int numbersSize, int target, int *returnSize) {
    *returnSize = 2;
    int *ans = malloc(sizeof(int[*returnSize]));
    ans[0] = -1;
    ans[1] = -1;
    int i = 0, j = numbersSize - 1;
    while (i < j) {
        int sum = numbers[i] + numbers[j];
        if (sum < target) {
            ++i;
        } else if (sum > target) {
            --j;
        } else {
            ans[0] = i + 1;
            ans[1] = j + 1;
            break;
        }
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391137863/
```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```c
int majorityElement(const int *nums, int numsSize) {
    int candidate = INT_MIN;
    int count = 0;
    for (int i = 0; i < numsSize; ++i) {
        int x = nums[i];
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
// https://leetcode.cn/submissions/detail/390334818/
```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```c
int cmp(const void *a, const void *b) {
    const int arg1 = *(const int *) a;
    const int arg2 = *(const int *) b;
    char *str1 = malloc(sizeof(char[20]));
    sprintf(str1, "%d%d", arg1, arg2);
    char *str2 = malloc(sizeof(char[20]));
    sprintf(str2, "%d%d", arg2, arg1);
    int res = strcmp(str2, str1);
    free(str1);
    free(str2);
    return res;
}

char *largestNumber(int *nums, int numsSize) {
    qsort(nums, numsSize, sizeof(int), cmp);
    if (nums[0] == 0) {
        return "0";
    }
    char *ans = calloc(1000, sizeof(char));
    char *p = ans;
    for (int i = 0; i < numsSize; i++) {
        sprintf(p, "%d", nums[i]);
        p += strlen(p);
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391328967/
```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```c
int maxProfit(int k, int *prices, int pricesSize) {
    if (k <= 0 || pricesSize <= 1) {
        return 0;
    }
    // dp[t][i][0] = 交易次数限制为 t 时，第 i 天，空仓状态下的最大利润
    // dp[t][i][1] = 交易次数限制为 t 时，第 i 天，持仓状态下的最大利润
    int dp[k + 1][pricesSize][2];
    // 交易次数限制为 0 时
    // 填写第 0 个 pricesSize x 2 矩阵
    for (int i = 0; i < pricesSize; ++i) {
        dp[0][i][0] = 0;
        dp[0][i][1] = INT_MIN;
    }
    // 交易次数限制为 [1..k] 时
    for (int t = 1; t <= k; ++t) {
        // 填写第 t 个 pricesSize x 2 矩阵
        dp[t][0][0] = 0;
        dp[t][0][1] = -prices[0];
        for (int i = 1; i < pricesSize; ++i) {
            // dp[t][i - 1][0]             >= dp[t - 1][i - 1][0] - prices[i]
            // dp[t][i - 1][1] + prices[i] >= dp[t][i - 1][1]
            // => dp[t][i][0] >= dp[t][i][1]
            dp[t][i][0] = fmax(dp[t][i - 1][0], dp[t][i - 1][1] + prices[i]);
            dp[t][i][1] = fmax(dp[t - 1][i - 1][0] - prices[i], dp[t][i - 1][1]);
        }
    }
    return dp[k][pricesSize - 1][0];
}
// https://leetcode.cn/submissions/detail/390323619/
```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```c
void swap(int *a, int *b) {
    int t = *a;
    *a = *b;
    *b = t;
}

void reverse(int *nums, int lo, int hi) {
    while (lo < hi) {
        swap(&nums[lo++], &nums[hi--]);
    }
}

void rotate(int *nums, int numsSize, int k) {
    k %= numsSize;
    if (k > 0) {
        reverse(nums, 0, numsSize - 1);
        reverse(nums, 0, k - 1);
        reverse(nums, k, numsSize - 1);
    }
}
// https://leetcode.cn/submissions/detail/388259314/
```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```c
// max({sum(subseq) | subseq 是数组 nums 的不连续子序列})
int subseqSum(int *nums, int numsSize) {
    if (numsSize == 0) {
        return 0;
    }
    if (numsSize == 1) {
        return nums[0];
    }
    if (numsSize == 2) {
        return fmax(nums[0], nums[1]);
    }
    // dp[i] = max({sum(subseq) | subseq 是子数组 nums[0..i] 的不连续子序列})
    int dp[numsSize];
    dp[0] = nums[0];
    dp[1] = fmax(nums[0], nums[1]);
    for (int i = 2; i < numsSize; ++i) {
        // 包含 nums[i]
        int sp1 = dp[i - 2] + nums[i];
        // 不包含 nums[i]
        int sp2 = dp[i - 1];
        dp[i] = fmax(sp1, sp2);
    }
    return dp[numsSize - 1];
}

int rob(int *nums, int numsSize) {
    return subseqSum(nums, numsSize);
}
// https://leetcode.cn/submissions/detail/390318894/
```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```c
static const int MAXSIZE = 100;

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *rightSideView(struct TreeNode *root, int *returnSize) {
    int *ans = malloc(sizeof(int[MAXSIZE]));
    *returnSize = 0;
    struct TreeNode **queue = malloc(sizeof(struct TreeNode *) * MAXSIZE);
    int first = 0, last = 0;
    if (root != NULL) {
        queue[last++] = root;
    }
    while (first < last) {
        ans[(*returnSize)++] = queue[last - 1]->val;
        int n = last - first;
        for (int i = 0; i < n; ++i) {
            struct TreeNode *x = queue[first++];
            struct TreeNode *left = x->left;
            if (left != NULL) {
                queue[last++] = left;
            }
            struct TreeNode *right = x->right;
            if (right != NULL) {
                queue[last++] = right;
            }
        }
    }
    free(queue);
    return ans;
}
// https://leetcode.cn/submissions/detail/391290281/
```

```c
typedef struct TreeNode *Value;

struct MyListNode {
    Value val;
    struct MyListNode *prev;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    struct MyListNode *last;
    int size;
} MyLinkedListDeque;

MyLinkedListDeque *myDequeCreate() {
    MyLinkedListDeque *obj = malloc(sizeof(MyLinkedListDeque));
    obj->first = NULL;
    obj->last = NULL;
    obj->size = 0;
    return obj;
}

void myDequePushFront(MyLinkedListDeque *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->prev = NULL;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        x->next = obj->first;
        obj->first->prev = x;
        obj->first = x;
    }
    obj->size++;
}

void myDequePushBack(MyLinkedListDeque *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->prev = NULL;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        obj->last->next = x;
        x->prev = obj->last;
        obj->last = x;
    }
    obj->size++;
}

Value myDequePopFront(MyLinkedListDeque *obj) {
    Value val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->first = obj->first->next;
        obj->first->prev = NULL;
    }
    free(x);
    obj->size--;
    return val;
}

Value myDequePopBack(MyLinkedListDeque *obj) {
    Value val = obj->last->val;
    struct MyListNode *x = obj->last;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->last = obj->last->prev;
        obj->last->next = NULL;
    }
    free(x);
    obj->size--;
    return val;
}

Value myDequePeekFront(MyLinkedListDeque *obj) {
    return obj->first->val;
}

Value myDequePeekBack(MyLinkedListDeque *obj) {
    return obj->last->val;
}

int myDequeSize(MyLinkedListDeque *obj) {
    return obj->size;
}

bool myDequeEmpty(MyLinkedListDeque *obj) {
    return obj->size == 0;
}

void myDequeFree(MyLinkedListDeque *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *rightSideView(struct TreeNode *root, int *returnSize) {
    *returnSize = 0;
    int ansCapacity = 8;
    int *ans = malloc(sizeof(int[ansCapacity]));
    MyLinkedListDeque *deque = myDequeCreate();
    if (root != NULL) {
        myDequePushBack(deque, root);
    }
    while (!myDequeEmpty(deque)) {
        if (*returnSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(int[ansCapacity]));
        }
        ans[(*returnSize)++] = myDequePeekBack(deque)->val;
        int n = myDequeSize(deque);
        for (int i = 0; i < n; ++i) {
            struct TreeNode *x = myDequePopFront(deque);
            struct TreeNode *left = x->left;
            if (left != NULL) {
                myDequePushBack(deque, left);
            }
            struct TreeNode *right = x->right;
            if (right != NULL) {
                myDequePushBack(deque, right);
            }
        }
    }
    myDequeFree(deque);
    return ans;
}
// https://leetcode.cn/submissions/detail/391409700/
```

```c
typedef struct TreeNode *Value;

struct MyListNode {
    Value val;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    struct MyListNode *last;
    int size;
} MyLinkedListQueue;

MyLinkedListQueue *myQueueCreate() {
    MyLinkedListQueue *obj = malloc(sizeof(MyLinkedListQueue));
    obj->first = NULL;
    obj->last = NULL;
    obj->size = 0;
    return obj;
}

void myQueuePush(MyLinkedListQueue *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        obj->last->next = x;
        obj->last = x;
    }
    obj->size++;
}

Value myQueuePop(MyLinkedListQueue *obj) {
    Value val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->first = obj->first->next;
    }
    free(x);
    obj->size--;
    return val;
}

Value myQueuePeek(MyLinkedListQueue *obj) {
    return obj->first->val;
}

int myQueueSize(MyLinkedListQueue *obj) {
    return obj->size;
}

bool myQueueEmpty(MyLinkedListQueue *obj) {
    return obj->size == 0;
}

void myQueueFree(MyLinkedListQueue *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *rightSideView(struct TreeNode *root, int *returnSize) {
    *returnSize = 0;
    int ansCapacity = 8;
    int *ans = malloc(sizeof(int[ansCapacity]));
    MyLinkedListQueue *queue = myQueueCreate();
    if (root != NULL) {
        myQueuePush(queue, root);
    }
    while (!myQueueEmpty(queue)) {
        if (*returnSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(int[ansCapacity]));
        }
        ans[(*returnSize)++] = myQueuePeek(queue)->val;
        int n = myQueueSize(queue);
        for (int i = 0; i < n; ++i) {
            struct TreeNode *x = myQueuePop(queue);
            struct TreeNode *right = x->right;
            if (right != NULL) {
                myQueuePush(queue, right);
            }
            struct TreeNode *left = x->left;
            if (left != NULL) {
                myQueuePush(queue, left);
            }
        }
    }
    myQueueFree(queue);
    return ans;
}
// https://leetcode.cn/submissions/detail/391407911/
```

```c
typedef struct TreeNode *Value;

typedef struct {
    Value *array;
    int capacity;
    int size;
    int first;
    int last;
} MyResizingArrayQueue;

MyResizingArrayQueue *myQueueCreate() {
    MyResizingArrayQueue *obj = malloc(sizeof(MyResizingArrayQueue));
    obj->first = 0;
    obj->last = 0;
    obj->size = 0;
    obj->capacity = 8;
    obj->array = malloc(sizeof(Value) * obj->capacity);
    return obj;
}

void myQueueResize(MyResizingArrayQueue *obj, int capacity) {
    Value *copy = malloc(sizeof(Value) * capacity);
    for (int i = 0; i < obj->size; ++i) {
        copy[i] = obj->array[(obj->first + i) % obj->capacity];
    }
    free(obj->array);
    obj->array = copy;
    obj->first = 0;
    obj->last = obj->size;
    obj->capacity = capacity;
}

void myQueuePush(MyResizingArrayQueue *obj, Value val) {
    if (obj->size == obj->capacity) {
        myQueueResize(obj, obj->capacity * 2);
    }
    obj->array[obj->last++] = val;
    if (obj->last == obj->capacity) {
        obj->last = 0;
    }
    obj->size++;
}

Value myQueuePop(MyResizingArrayQueue *obj) {
    Value val = obj->array[obj->first++];
    if (obj->first == obj->capacity) {
        obj->first = 0;
    }
    obj->size--;
    if (obj->size > 0 && obj->size == obj->capacity / 4) {
        myQueueResize(obj, obj->capacity / 2);
    }
    return val;
}

Value myQueuePeek(MyResizingArrayQueue *obj) {
    return obj->array[obj->first];
}

int myQueueSize(MyResizingArrayQueue *obj) {
    return obj->size;
}

bool myQueueEmpty(MyResizingArrayQueue *obj) {
    return obj->size == 0;
}

void myQueueFree(MyResizingArrayQueue *obj) {
    free(obj->array);
    free(obj);
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *rightSideView(struct TreeNode *root, int *returnSize) {
    *returnSize = 0;
    int ansCapacity = 8;
    int *ans = malloc(sizeof(int[ansCapacity]));
    MyResizingArrayQueue *queue = myQueueCreate();
    if (root != NULL) {
        myQueuePush(queue, root);
    }
    while (!myQueueEmpty(queue)) {
        if (*returnSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(int[ansCapacity]));
        }
        ans[(*returnSize)++] = myQueuePeek(queue)->val;
        int n = myQueueSize(queue);
        for (int i = 0; i < n; ++i) {
            struct TreeNode *x = myQueuePop(queue);
            struct TreeNode *right = x->right;
            if (right != NULL) {
                myQueuePush(queue, right);
            }
            struct TreeNode *left = x->left;
            if (left != NULL) {
                myQueuePush(queue, left);
            }
        }
    }
    myQueueFree(queue);
    return ans;
}
// https://leetcode.cn/submissions/detail/391292419/
```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```c
static const char LAND = '1';
static const char WATER = '0';

void floodFill(char **grid, int gridSize, int *gridColSize, int row, int col) {
    if (row < 0 || row >= gridSize || col < 0 || col >= *gridColSize || grid[row][col] == WATER) {
        return;
    }
    grid[row][col] = WATER;
    floodFill(grid, gridSize, gridColSize, row, col + 1);
    floodFill(grid, gridSize, gridColSize, row, col - 1);
    floodFill(grid, gridSize, gridColSize, row + 1, col);
    floodFill(grid, gridSize, gridColSize, row - 1, col);
}

int numIslands(char **grid, int gridSize, int *gridColSize) {
    int count = 0;
    for (int row = 0; row < gridSize; ++row) {
        for (int col = 0; col < *gridColSize; ++col) {
            if (grid[row][col] == LAND) {
                floodFill(grid, gridSize, gridColSize, row, col);
                ++count;
            }
        }
    }
    return count;
}
// https://leetcode.cn/submissions/detail/391254735/
```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```c
struct ListNode *removeElements(struct ListNode *head, int val) {
    struct ListNode *dummyHead = malloc(sizeof(struct ListNode));
    dummyHead->val = -1;
    dummyHead->next = head;
    struct ListNode *ptr = dummyHead;
    while (ptr != NULL && ptr->next != NULL) {
        if (ptr->next->val == val) {
            struct ListNode *x = ptr->next;
            ptr->next = ptr->next->next;
            free(x);
        } else {
            ptr = ptr->next;
        }
    }
    head = dummyHead->next;
    free(dummyHead);
    return head;
}
// https://leetcode.cn/submissions/detail/391147229/
```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```c
struct ListNode *reverseList(struct ListNode *head) {
    struct ListNode *reverseHead = NULL;
    while (head != NULL) {
        struct ListNode *x = head->next;
        head->next = reverseHead;
        reverseHead = head;
        head = x;
    }
    return reverseHead;
}
// https://leetcode.cn/submissions/detail/388498618/
```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```c
// TODO
```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```c
// TODO
```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```c
// max({sum(subseq) | subseq 是子数组 nums[lo..hi] 的不连续子序列})
int subseqSum(int *nums, int numsSize, int lo, int hi) {
    int n = hi - lo + 1;
    if (n == 0) {
        return 0;
    }
    if (n == 1) {
        return nums[lo];
    }
    if (n == 2) {
        return fmax(nums[lo], nums[lo + 1]);
    }
    // dp[i] = max({sum(subseq) | subseq 是子数组 nums[lo..lo+i] 的不连续子序列})
    int dp[n];
    dp[0] = nums[lo];
    dp[1] = fmax(nums[lo], nums[lo + 1]);
    for (int i = 2; i < n; ++i) {
        // 包含 nums[lo+i]
        int sp1 = dp[i - 2] + nums[lo + i];
        // 不包含 nums[lo+i]
        int sp2 = dp[i - 1];
        dp[i] = fmax(sp1, sp2);
    }
    return dp[n - 1];
}

int rob(int *nums, int numsSize) {
    if (numsSize == 1) {
        return nums[0];
    }
    int sp1 = subseqSum(nums, numsSize, 0, numsSize - 2);
    int sp2 = subseqSum(nums, numsSize, 1, numsSize - 1);
    return fmax(sp1, sp2);
}
// https://leetcode.cn/submissions/detail/391167123/
```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```c
void swap(int *a, int *b) {
    int t = *a;
    *a = *b;
    *b = t;
}

int partition(int *nums, int lo, int hi) {
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
        swap(&nums[i], &nums[j]);
    }
    swap(&nums[lo], &nums[j]);
    return j;
}

// 返回数组 nums 从小到大排在第 rank 位的元素，排位从 0 开始计算，
// 相当于有 rank 个元素小于该元素。
int qselect(int *nums, int numsSize, int rank) {
    int lo = 0, hi = numsSize - 1;
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

int findKthLargest(int *nums, int numsSize, int k) {
    return qselect(nums, numsSize, numsSize - k);
}
// https://leetcode.cn/submissions/detail/390816223/
```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```c
int *path;
int pathSum;
int pathSize;

int **ans;
int ansSize;
int *ansColSize;
int ansCapacity;

// edge = 取 [1..9] 为值
void backtrack(int k, int n, int edge) {
    if (pathSize == k && pathSum == n) {
        size_t size = sizeof(int[pathSize]);
        int *res = malloc(size);
        memcpy(res, path, size);
        if (ansSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(int *) * ansCapacity);
            ansColSize = realloc(ansColSize, sizeof(int[ansCapacity]));
        }
        ans[ansSize] = res;
        ansColSize[ansSize++] = pathSize;
    } else if (pathSize < k && pathSum < n) {
        // 避免重复，从 edge + 1 开始选择
        // 例如 [1->2] 和 [2->1] 是重复的
        while (++edge <= 9) {
            if (pathSum + edge <= n) {
                pathSum += edge;
                path[pathSize++] = edge;
                backtrack(k, n, edge);
                pathSum -= edge;
                --pathSize;
            }
        }
    }
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **combinationSum3(int k, int n, int *returnSize, int **returnColumnSizes) {
    ansCapacity = 8;
    ans = malloc(sizeof(int *) * ansCapacity);
    ansColSize = malloc(sizeof(int[ansCapacity]));
    path = malloc(sizeof(int[k]));
    ansSize = pathSum = pathSize = 0;
    backtrack(k, n, 0);
    *returnSize = ansSize;
    *returnColumnSizes = ansColSize;
    free(path);
    return ans;
}
// https://leetcode.cn/submissions/detail/391277988/
```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```c
int countNodes(struct TreeNode *root) {
    if (root == NULL) {
        return 0;
    }
    int leftHeight = 0;
    struct TreeNode *ptr = root;
    while (ptr != NULL) {
        ++leftHeight;
        ptr = ptr->left;
    }
    int rightHeight = 0;
    ptr = root->right;
    while (ptr != NULL) {
        ++rightHeight;
        ptr = ptr->right;
    }
    if (leftHeight == rightHeight) {
        return (1 << leftHeight) - 1;
    }
    return 1 + countNodes(root->left) + countNodes(root->right);
}
// https://leetcode.cn/submissions/detail/390008475/
```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```c
struct MyListNode {
    int val;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    struct MyListNode *last;
} MyStack;

MyStack *myStackCreate() {
    MyStack *obj = malloc(sizeof(MyStack));
    obj->first = NULL;
    obj->last = NULL;
    return obj;
}

void myStackPush(MyStack *obj, int val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->next = NULL;
    if (obj->first == NULL) {
        obj->first = x;
        obj->last = x;
    } else {
        // 入队
        obj->last->next = x;
        obj->last = x;
        struct MyListNode *last = obj->last;
        while (obj->first != last) {
            int temp = obj->first->val;
            // 出队
            struct MyListNode *dequeueNode = obj->first;
            obj->first = obj->first->next;
            free(dequeueNode);
            // 入队
            struct MyListNode *enqueueNode = malloc(sizeof(struct MyListNode));
            enqueueNode->val = temp;
            enqueueNode->next = NULL;
            obj->last->next = enqueueNode;
            obj->last = enqueueNode;
        }
    }
}

int myStackPop(MyStack *obj) {
    int val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (x->next == NULL) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->first = obj->first->next;
    }
    free(x);
    return val;
}

int myStackTop(MyStack *obj) {
    return obj->first->val;
}

bool myStackEmpty(MyStack *obj) {
    return obj->first == NULL;
}

void myStackFree(MyStack *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}
// https://leetcode.cn/submissions/detail/391359845/
```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```c
struct TreeNode *invertTree(struct TreeNode *root) {
    if (root == NULL) {
        return NULL;
    }
    struct TreeNode *left = invertTree(root->left);
    struct TreeNode *right = invertTree(root->right);
    root->left = right;
    root->right = left;
    return root;
}
// https://leetcode.cn/submissions/detail/390002049/
```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```c
typedef struct {
    struct TreeNode *key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

HashMapItem *memo = NULL;

int size(struct TreeNode *root) {
    if (root == NULL) {
        return 0;
    }
    HashMapItem *item;
    HASH_FIND_PTR(memo, &root, item);
    if (item == NULL) {
        item = malloc(sizeof(HashMapItem));
        item->key = root;
        item->val = 1 + size(root->left) + size(root->right);
        HASH_ADD_PTR(memo, key, item);
    }
    return item->val;
}

int qselect(struct TreeNode *root, int rank) {
    if (root == NULL) {
        return -1;
    }
    int leftSize = size(root->left);
    if (rank < leftSize) {
        return qselect(root->left, rank);
    }
    if (leftSize < rank) {
        return qselect(root->right, rank - leftSize - 1);
    }
    return root->val;
}

int kthSmallest(struct TreeNode *root, int k) {
    int ans = qselect(root, k - 1);
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, memo, cur, tmp) {
        HASH_DEL(memo, cur);
        free(cur);
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391279273/
```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```c
struct MyListNode {
    int val;
    struct MyListNode *next;
};

/**
 * -----------------------------| |-------------------------------
 * pop <- top Left Stack bottom | | bottom Right Stack top <- push
 * -----------------------------| |-------------------------------
 */
typedef struct {
    struct MyListNode *leftFirst;
    struct MyListNode *rightFirst;
} MyQueue;

MyQueue *myQueueCreate() {
    MyQueue *obj = malloc(sizeof(MyQueue));
    obj->leftFirst = NULL;
    obj->rightFirst = NULL;
    return obj;
}

void myQueuePush(MyQueue *obj, int val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->next = NULL;
    if (obj->rightFirst == NULL) {
        obj->rightFirst = x;
    } else {
        x->next = obj->rightFirst;
        obj->rightFirst = x;
    }
}

void myQueueMove(MyQueue *obj) {
    while (obj->rightFirst != NULL) {
        int temp = obj->rightFirst->val;
        // 出栈
        struct MyListNode *popNode = obj->rightFirst;
        if (popNode->next == NULL) {
            obj->rightFirst = NULL;
        } else {
            obj->rightFirst = obj->rightFirst->next;
        }
        free(popNode);
        // 入栈
        struct MyListNode *pushNode = malloc(sizeof(struct MyListNode));
        pushNode->val = temp;
        pushNode->next = NULL;
        if (obj->leftFirst == NULL) {
            obj->leftFirst = pushNode;
        } else {
            pushNode->next = obj->leftFirst;
            obj->leftFirst = pushNode;
        }
    }
}

int myQueuePop(MyQueue *obj) {
    if (obj->leftFirst == NULL) {
        myQueueMove(obj);
    }
    int val = obj->leftFirst->val;
    struct MyListNode *x = obj->leftFirst;
    if (x->next == NULL) {
        obj->leftFirst = NULL;
    } else {
        obj->leftFirst = obj->leftFirst->next;
    }
    free(x);
    return val;
}

int myQueuePeek(MyQueue *obj) {
    if (obj->leftFirst == NULL) {
        myQueueMove(obj);
    }
    return obj->leftFirst->val;
}

bool myQueueEmpty(MyQueue *obj) {
    return obj->leftFirst == NULL && obj->rightFirst == NULL;
}

void myQueueFree(MyQueue *obj) {
    struct MyListNode *p = obj->leftFirst;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    p = obj->rightFirst;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}
// https://leetcode.cn/submissions/detail/391359552/
```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```c
struct ListNode *reverseList(struct ListNode *head) {
    struct ListNode *reverseHead = NULL;
    while (head != NULL) {
        struct ListNode *x = head->next;
        head->next = reverseHead;
        reverseHead = head;
        head = x;
    }
    return reverseHead;
}

bool isPalindrome(struct ListNode *head) {
    // 寻找链表的中点（偶数个节点时选择左侧），即前半部分链表的尾节点
    struct ListNode *mid = head;
    struct ListNode *ptr = head;
    while (ptr->next != NULL && ptr->next->next != NULL) {
        mid = mid->next;
        ptr = ptr->next->next;
    }
    // 翻转后半部分链表
    struct ListNode *reverseHead = reverseList(mid->next);
    mid->next = NULL;
    // 判断是否回文链表
    struct ListNode *left = head;
    struct ListNode *right = reverseHead;
    while (right != NULL) {
        if (left->val != right->val) {
            // 还原链表
            mid->next = reverseList(reverseHead);
            return false;
        }
        left = left->next;
        right = right->next;
    }
    // 还原链表
    mid->next = reverseList(reverseHead);
    return true;
}
// https://leetcode.cn/submissions/detail/391144641/
```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```c
struct TreeNode *lowestCommonAncestor(struct TreeNode *root, struct TreeNode *p, struct TreeNode *q) {
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
    return NULL;
}
// https://leetcode.cn/submissions/detail/390008893/
```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```c
struct TreeNode *lca;

// 在子树中查找节点 p 或 q，递归过程中确定『最近公共祖先』
bool find(struct TreeNode *root, struct TreeNode *p, struct TreeNode *q) {
    if (root == NULL) {
        return false;
    }
    if (root == p || root == q) {
        // 如果 lca(p,q) = p 或 q，则此处的 lca = root 是最终答案
        lca = root;
        return true;
    }
    bool left = find(root->left, p, q);
    bool right = find(root->right, p, q);
    if (left && right) {
        // 否则返回到某祖先节点处的 lca = root 才是最终答案
        lca = root;
    }
    return left || right;
}

struct TreeNode *lowestCommonAncestor(struct TreeNode *root, struct TreeNode *p, struct TreeNode *q) {
    lca = root;
    find(root, p, q);
    return lca;
}
// https://leetcode.cn/submissions/detail/391165936/
```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```c
void deleteNode(struct ListNode *node) {
    node->val = node->next->val;
    struct ListNode *delNode = node->next;
    node->next = delNode->next;
    free(delNode);
}
// https://leetcode.cn/submissions/detail/388679220/
```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```c
/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *maxSlidingWindow(const int *nums, int numsSize, int k, int *returnSize) {
    int *ans = malloc(sizeof(int[numsSize]));
    int ansSize = 0;
    int queue[numsSize];
    int first = 0, last = 0;
    for (int i = 0; i < numsSize; ++i) {
        // nums[i] = 进入窗口的数字
        int x = nums[i];
        while (first < last && queue[last - 1] < x) {
            --last;
        }
        queue[last++] = x;
        if (i < k - 1) {
            continue;
        }
        // nums[i-k] = 退出窗口的数字
        if (i >= k && nums[i - k] == queue[first]) {
            ++first;
        }
        ans[ansSize++] = queue[first];
    }
    *returnSize = ansSize;
    return ans;
}
// https://leetcode.cn/submissions/detail/391282668/
```

```c
typedef int Value;

struct MyListNode {
    Value val;
    struct MyListNode *prev;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    struct MyListNode *last;
    int size;
} MyLinkedListDeque;

MyLinkedListDeque *myDequeCreate() {
    MyLinkedListDeque *obj = malloc(sizeof(MyLinkedListDeque));
    obj->first = NULL;
    obj->last = NULL;
    obj->size = 0;
    return obj;
}

void myDequePushFront(MyLinkedListDeque *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->prev = NULL;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        x->next = obj->first;
        obj->first->prev = x;
        obj->first = x;
    }
    obj->size++;
}

void myDequePushBack(MyLinkedListDeque *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->prev = NULL;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        obj->last->next = x;
        x->prev = obj->last;
        obj->last = x;
    }
    obj->size++;
}

Value myDequePopFront(MyLinkedListDeque *obj) {
    Value val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->first = obj->first->next;
        obj->first->prev = NULL;
    }
    free(x);
    obj->size--;
    return val;
}

Value myDequePopBack(MyLinkedListDeque *obj) {
    Value val = obj->last->val;
    struct MyListNode *x = obj->last;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->last = obj->last->prev;
        obj->last->next = NULL;
    }
    free(x);
    obj->size--;
    return val;
}

Value myDequePeekFront(MyLinkedListDeque *obj) {
    return obj->first->val;
}

Value myDequePeekBack(MyLinkedListDeque *obj) {
    return obj->last->val;
}

int myDequeSize(MyLinkedListDeque *obj) {
    return obj->size;
}

bool myDequeEmpty(MyLinkedListDeque *obj) {
    return obj->size == 0;
}

void myDequeFree(MyLinkedListDeque *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *maxSlidingWindow(const int *nums, int numsSize, int k, int *returnSize) {
    int *ans = malloc(sizeof(int[numsSize]));
    int ansSize = 0;
    MyLinkedListDeque *deque = myDequeCreate();
    for (int i = 0; i < numsSize; ++i) {
        // nums[i] = 进入窗口的数字
        int x = nums[i];
        while (!myDequeEmpty(deque) && myDequePeekBack(deque) < x) {
            myDequePopBack(deque);
        }
        myDequePushBack(deque, x);
        if (i < k - 1) {
            continue;
        }
        // nums[i-k] = 退出窗口的数字
        if (i >= k && nums[i - k] == myDequePeekFront(deque)) {
            myDequePopFront(deque);
        }
        ans[ansSize++] = myDequePeekFront(deque);
    }
    *returnSize = ansSize;
    myDequeFree(deque);
    return ans;
}
// https://leetcode.cn/submissions/detail/391409356/
```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```c
// TODO
```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```c
void swap(int *a, int *b) {
    int t = *a;
    *a = *b;
    *b = t;
}

void moveZeroes(int *nums, int numsSize) {
    // [0..i-1] != 0
    // [i..j-1] == 0
    // [j..n-1] Scanning
    int i = 0, j = 0;
    while (j < numsSize) {
        while (j < numsSize && nums[j] == 0) {
            ++j;
        }
        if (j < numsSize) {
            swap(&nums[i++], &nums[j++]);
        }
    }
}
// https://leetcode.cn/submissions/detail/388242252/
```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```c
/** Encodes a tree to a single string. */
char *serialize(struct TreeNode *root) {
    if (root == NULL) {
        char *res = calloc(2, sizeof(char));
        strcpy(res, "#");
        return res;
    }
    char *left = serialize(root->left);
    char *right = serialize(root->right);
    char *res = calloc(strlen(left) + strlen(right) + 8, sizeof(char));
    sprintf(res, "%d,%s,%s", root->val, left, right);
    free(left);
    free(right);
    return res;
}

struct TreeNode *buildTree(char **strs, int *index) {
    char *s = strs[(*index)++];
    if (strcmp(s, "#") == 0) {
        return NULL;
    }
    struct TreeNode *root = malloc(sizeof(struct TreeNode));
    root->val = atoi(s);
    root->left = buildTree(strs, index);
    root->right = buildTree(strs, index);
    return root;
}

/** Decodes your encoded data to tree. */
struct TreeNode *deserialize(char *data) {
    int size = 0, capacity = 8;
    char **strs = malloc(sizeof(char *) * capacity);
    int i = 0;
    size_t n = strlen(data);
    while (i < n) {
        int start = i, len = 0;
        while (i < n) {
            if (data[i++] == ',') {
                break;
            }
            ++len;
        }
        char *s = calloc(len + 1, sizeof(char));
        strncpy(s, data + start, len);
        if (len > 0) {
            if (size == capacity) {
                capacity *= 2;
                strs = realloc(strs, sizeof(char *) * capacity);
            }
            strs[size++] = s;
        }
    }
    int index = 0;
    struct TreeNode *root = buildTree(strs, &index);
    for (int j = 0; j < size; ++j) {
        free(strs[j]);
    }
    free(strs);
    return root;
}
// https://leetcode.cn/submissions/detail/391416610/
```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```c
int lengthOfLIS(const int *nums, int numsSize) {
    // dp[i] = max({length(subsequence) | subsequence 是以 nums[i] 结尾的严格递增子序列})
    int dp[numsSize];
    dp[0] = 1;
    int ans = dp[0];
    for (int i = 1; i < numsSize; ++i) {
        int res = 1;
        for (int j = i - 1; j >= 0; --j) {
            if (nums[j] < nums[i]) {
                res = fmax(res, dp[j] + 1);
            }
        }
        dp[i] = res;
        ans = fmax(ans, dp[i]);
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/390338661/
```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```c
typedef struct {
    int *sums;
} NumArray;

NumArray *numArrayCreate(const int *nums, int numsSize) {
    NumArray *obj = malloc(sizeof(NumArray));
    obj->sums = malloc(sizeof(int[numsSize]));
    obj->sums[0] = nums[0];
    for (int i = 1; i < numsSize; ++i) {
        obj->sums[i] = obj->sums[i - 1] + nums[i];
    }
    return obj;
}

int numArraySumRange(NumArray *obj, int left, int right) {
    if (left == 0) {
        return obj->sums[right];
    }
    return obj->sums[right] - obj->sums[left - 1];
}

void numArrayFree(NumArray *obj) {
    free(obj->sums);
    free(obj);
}
// https://leetcode.cn/submissions/detail/391360132/
```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```c
int maxProfit(int *prices, int pricesSize) {
    if (pricesSize <= 1) {
        return 0;
    }
    // dp[i][0] = 第 i 天，空仓状态下的最大利润
    // dp[i][1] = 第 i 天，持仓状态下的最大利润
    int dp[pricesSize][2];
    dp[0][0] = 0;
    dp[0][1] = -prices[0];
    dp[1][0] = fmax(dp[0][0], dp[0][1] + prices[1]);
    dp[1][1] = fmax(dp[0][0] - prices[1], dp[0][1]);
    for (int i = 2; i < pricesSize; ++i) {
        // dp[i - 1][0]             >= dp[i - 2][0] >= p[i - 2][0] - prices[i]
        // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
        // => dp[i][0] >= dp[i][1]
        dp[i][0] = fmax(dp[i - 1][0], dp[i - 1][1] + prices[i]);
        dp[i][1] = fmax(dp[i - 2][0] - prices[i], dp[i - 1][1]);
    }
    return dp[pricesSize - 1][0];
}
// https://leetcode.cn/submissions/detail/390322797/
```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```c
int *counts;

struct Pair {
    int val;
    int idx;
};

void merge(struct Pair *pairs, struct Pair *aux, int lo, int mid, int hi) {
    for (int k = lo; k <= hi; ++k) {
        aux[k] = pairs[k];
    }
    int i = lo, j = mid + 1;
    for (int k = lo; k <= hi; ++k) {
        if (i > mid || (j <= hi && aux[j].val < aux[i].val)) {
            pairs[k] = aux[j++];
        } else {
            // aux[mid+1..j) < aux[i]
            counts[aux[i].idx] += (j - mid - 1);
            pairs[k] = aux[i++];
        }
    }
}

void sort(struct Pair *pairs, struct Pair *aux, int lo, int hi) {
    if (lo >= hi) {
        return;
    }
    int mid = lo + (hi - lo) / 2;
    sort(pairs, aux, lo, mid);
    sort(pairs, aux, mid + 1, hi);
    merge(pairs, aux, lo, mid, hi);
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *countSmaller(const int *nums, int numsSize, int *returnSize) {
    *returnSize = numsSize;
    counts = calloc(numsSize, sizeof(int));
    struct Pair *pairs = malloc(sizeof(struct Pair) * numsSize);
    for (int i = 0; i < numsSize; ++i) {
        struct Pair p = {nums[i], i};
        pairs[i] = p;
    }
    struct Pair *aux = malloc(sizeof(struct Pair) * numsSize);
    sort(pairs, aux, 0, numsSize - 1);
    free(pairs);
    free(aux);
    return counts;
}
// https://leetcode.cn/submissions/detail/391357126/
```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```c
int coinChange(const int *coins, int coinsSize, int amount) {
    // dp[i] = 凑成总金额 i 所需的最少的硬币个数
    int dp[amount + 1];
    memset(dp, 0, sizeof(dp));
    for (int i = 1; i <= amount; ++i) {
        int res = INT_MAX;
        // c       = 选择放入的硬币
        // i-c     = 剩余总金额
        // dp[i-c] = 凑成剩余总金额所需的最少的硬币个数
        for (int j = 0; j < coinsSize; ++j) {
            int x = i - coins[j];
            if (x >= 0 && dp[x] != -1) {
                res = fmin(res, dp[x] + 1);
            }
        }
        dp[i] = (res == INT_MAX ? -1 : res);
    }
    return dp[amount];
}
// https://leetcode.cn/submissions/detail/390181811/
```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```c
typedef struct {
    struct TreeNode *key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

HashMapItem *memo = NULL;

// 在二叉树 root，能盗取的最高金额
int robMemo(struct TreeNode *root) {
    if (root == NULL) {
        return 0;
    }
    HashMapItem *item;
    HASH_FIND_PTR(memo, &root, item);
    if (item == NULL) {
        item = malloc(sizeof(HashMapItem));
        item->key = root;
        // 不偷 root
        int sp1 = robMemo(root->left) + robMemo(root->right);
        // 偷 root
        int sp2 = root->val;
        if (root->left != NULL) {
            sp2 += robMemo(root->left->left) + robMemo(root->left->right);
        }
        if (root->right != NULL) {
            sp2 += robMemo(root->right->left) + robMemo(root->right->right);
        }
        item->val = fmax(sp1, sp2);
        HASH_ADD_PTR(memo, key, item);
    }
    return item->val;
}

int rob(struct TreeNode *root) {
    int ans = robMemo(root);
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, memo, cur, tmp) {
        HASH_DEL(memo, cur);
        free(cur);
    }
    HASH_CLEAR(hh, memo);
    return ans;
}
// https://leetcode.cn/submissions/detail/391279016/
```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```c
void swap(char *a, char *b) {
    char t = *a;
    *a = *b;
    *b = t;
}

void reverseString(char *s, int sSize) {
    int i = 0, j = sSize - 1;
    while (i < j) {
        swap(&s[i++], &s[j--]);
    }
}
// https://leetcode.cn/submissions/detail/390151784/
```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```c
// TODO
```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```c
typedef char *Value;

struct MyListNode {
    Value val;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    int size;
} MyLinkedListStack;

MyLinkedListStack *myStackCreate() {
    MyLinkedListStack *obj = malloc(sizeof(MyLinkedListStack));
    obj->first = NULL;
    obj->size = 0;
    return obj;
}

void myStackPush(MyLinkedListStack *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
    } else {
        x->next = obj->first;
        obj->first = x;
    }
    obj->size++;
}

Value myStackPop(MyLinkedListStack *obj) {
    Value val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
    } else {
        obj->first = obj->first->next;
    }
    free(x);
    obj->size--;
    return val;
}

Value myStackPeek(MyLinkedListStack *obj) {
    return obj->first->val;
}

int myStackSize(MyLinkedListStack *obj) {
    return obj->size;
}

bool myStackEmpty(MyLinkedListStack *obj) {
    return obj->size == 0;
}

void myStackFree(MyLinkedListStack *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

char *repeatedString(char *s, int k) {
    char *res = calloc(k * strlen(s) + 1, sizeof(char));
    char *p = res;
    for (int i = 1; i <= k; ++i) {
        sprintf(p, "%s", s);
        p += strlen(p);
    }
    return res;
}

char *decodeString(char *s) {
    MyLinkedListStack *stack = myStackCreate();
    int i = 0;
    size_t n = strlen(s);
    while (i < n) {
        int start = i;
        size_t len = 0;
        while (i < n && isdigit(s[i])) {
            ++i;
            ++len;
        }
        if (len > 0) {
            char *digits = calloc(len + 1, sizeof(char));
            strncpy(digits, s + start, len);
            myStackPush(stack, digits);
        }
        while (i < n && s[i] == '[') {
            myStackPush(stack, "[");
            ++i;
        }
        start = i;
        len = 0;
        while (i < n && isalpha(s[i])) {
            ++i;
            ++len;
        }
        if (len > 0) {
            char *letters = calloc(len + 1, sizeof(char));
            strncpy(letters, s + start, len);
            myStackPush(stack, letters);
        }
        while (i < n && s[i] == ']') {
            char **strs = malloc(sizeof(char *) * myStackSize(stack));
            int count = 0;
            len = 0;
            while (!myStackEmpty(stack)) {
                char *str = myStackPop(stack);
                if (strcmp(str, "[") == 0) {
                    break;
                }
                len += strlen(str);
                strs[count++] = str;
            }
            char *letters = calloc(len + 1, sizeof(char));
            char *p = letters;
            for (int k = count - 1; k >= 0; --k) {
                sprintf(p, "%s", strs[k]);
                p += strlen(p);
            }
            char *digits = myStackPop(stack);
            char *rep = repeatedString(letters, atoi(digits));
            myStackPush(stack, rep);
            for (int k = 0; k < count; ++k) {
                free(strs[k]);
            }
            free(strs);
            ++i;
        }
    }
    char **strs = malloc(sizeof(char *) * myStackSize(stack));
    int count = 0;
    size_t len = 0;
    while (!myStackEmpty(stack)) {
        char *str = myStackPop(stack);
        len += strlen(str);
        strs[count++] = str;
    }
    char *ans = calloc(len + 1, sizeof(char));
    char *p = ans;
    for (int k = count - 1; k >= 0; --k) {
        sprintf(p, "%s", strs[k]);
        p += strlen(p);
    }
    for (int k = 0; k < count; ++k) {
        free(strs[k]);
    }
    free(strs);
    myStackFree(stack);
    return ans;
}
// https://leetcode.cn/submissions/detail/391413487/
```

```c
typedef char *Value;

typedef struct {
    Value *array;
    int capacity;
    int size;
} MyResizingArrayStack;

MyResizingArrayStack *myStackCreate() {
    MyResizingArrayStack *obj = malloc(sizeof(MyResizingArrayStack));
    obj->size = 0;
    obj->capacity = 8;
    obj->array = malloc(sizeof(Value) * obj->capacity);
    return obj;
}

void myStackResize(MyResizingArrayStack *obj, int capacity) {
    obj->array = realloc(obj->array, sizeof(Value) * capacity);
    obj->capacity = capacity;
}

void myStackPush(MyResizingArrayStack *obj, Value val) {
    if (obj->size == obj->capacity) {
        myStackResize(obj, obj->capacity * 2);
    }
    obj->array[obj->size++] = val;
}

Value myStackPop(MyResizingArrayStack *obj) {
    Value val = obj->array[obj->size - 1];
    obj->size--;
    if (obj->size > 0 && obj->size == obj->capacity / 4) {
        myStackResize(obj, obj->capacity / 2);
    }
    return val;
}

Value myStackPeek(MyResizingArrayStack *obj) {
    return obj->array[obj->size - 1];
}

int myStackSize(MyResizingArrayStack *obj) {
    return obj->size;
}

bool myStackEmpty(MyResizingArrayStack *obj) {
    return obj->size == 0;
}

void myStackFree(MyResizingArrayStack *obj) {
    free(obj->array);
    free(obj);
}

char *repeatedString(char *s, int k) {
    char *res = calloc(k * strlen(s) + 1, sizeof(char));
    char *p = res;
    for (int i = 1; i <= k; ++i) {
        sprintf(p, "%s", s);
        p += strlen(p);
    }
    return res;
}

char *decodeString(char *s) {
    MyResizingArrayStack *stack = myStackCreate();
    int i = 0;
    size_t n = strlen(s);
    while (i < n) {
        int start = i;
        size_t len = 0;
        while (i < n && isdigit(s[i])) {
            ++i;
            ++len;
        }
        if (len > 0) {
            char *digits = calloc(len + 1, sizeof(char));
            strncpy(digits, s + start, len);
            myStackPush(stack, digits);
        }
        while (i < n && s[i] == '[') {
            myStackPush(stack, "[");
            ++i;
        }
        start = i;
        len = 0;
        while (i < n && isalpha(s[i])) {
            ++i;
            ++len;
        }
        if (len > 0) {
            char *letters = calloc(len + 1, sizeof(char));
            strncpy(letters, s + start, len);
            myStackPush(stack, letters);
        }
        while (i < n && s[i] == ']') {
            char **strs = malloc(sizeof(char *) * myStackSize(stack));
            int count = 0;
            len = 0;
            while (!myStackEmpty(stack)) {
                char *str = myStackPop(stack);
                if (strcmp(str, "[") == 0) {
                    break;
                }
                len += strlen(str);
                strs[count++] = str;
            }
            char *letters = calloc(len + 1, sizeof(char));
            char *p = letters;
            for (int k = count - 1; k >= 0; --k) {
                sprintf(p, "%s", strs[k]);
                p += strlen(p);
            }
            char *digits = myStackPop(stack);
            char *rep = repeatedString(letters, atoi(digits));
            myStackPush(stack, rep);
            for (int k = 0; k < count; ++k) {
                free(strs[k]);
            }
            free(strs);
            ++i;
        }
    }
    char **strs = malloc(sizeof(char *) * myStackSize(stack));
    int count = 0;
    size_t len = 0;
    while (!myStackEmpty(stack)) {
        char *str = myStackPop(stack);
        len += strlen(str);
        strs[count++] = str;
    }
    char *ans = calloc(len + 1, sizeof(char));
    char *p = ans;
    for (int k = count - 1; k >= 0; --k) {
        sprintf(p, "%s", strs[k]);
        p += strlen(p);
    }
    for (int k = 0; k < count; ++k) {
        free(strs[k]);
    }
    free(strs);
    myStackFree(stack);
    return ans;
}
// https://leetcode.cn/submissions/detail/391413256/
```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```c
// 数组 nums 是否存在和为 sum 的子集
bool hasSubsetSum(const int *nums, int numsSize, int sum) {
    int n = numsSize;
    // dp[i][j] = 子数组 nums[0..i-1] 是否存在和为 j 的子集
    bool dp[n + 1][sum + 1];
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
                bool sp1 = dp[i - 1][j];
                // 包含 x
                bool sp2 = dp[i - 1][j - x];
                dp[i][j] = sp1 || sp2;
            } else {
                dp[i][j] = dp[i - 1][j];
            }
        }
    }
    return dp[n][sum];
}

bool canPartition(int *nums, int numsSize) {
    int sum = 0;
    for (int i = 0; i < numsSize; ++i) {
        sum += nums[i];
    }
    if (sum % 2 == 1) {
        return false;
    }
    return hasSubsetSum(nums, numsSize, sum / 2);
}
// https://leetcode.cn/submissions/detail/390450156/
```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```c
int cmp(const void *a, const void *b) {
    const int *arg1 = *(const int **) a;
    const int *arg2 = *(const int **) b;
    return arg1[1] - arg2[1];
}

// 区间数组 intervals 无重叠区间的最大数量
int maxNonOverlappingIntervals(int **intervals, int intervalsSize) {
    qsort(intervals, intervalsSize, sizeof(int *), cmp);
    int count = 0;
    int minEnd = INT_MIN;
    for (int i = 0; i < intervalsSize; ++i) {
        int start = intervals[i][0];
        int end = intervals[i][1];
        if (start < minEnd) {
            continue;
        }
        ++count;
        minEnd = end;
    }
    return count;
}

int eraseOverlapIntervals(int **intervals, int intervalsSize, int *intervalsColSize) {
    return intervalsSize - maxNonOverlappingIntervals(intervals, intervalsSize);
}
// https://leetcode.cn/submissions/detail/391305215/
```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```c
typedef struct {
    int key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *findAnagrams(char *s, char *p, int *returnSize) {
    size_t sLength = strlen(s), pLength = strlen(p);
    HashMapItem *need = NULL;
    for (int i = 0; i < pLength; ++i) {
        int ch = p[i];
        HashMapItem *needItem;
        HASH_FIND_INT(need, &ch, needItem);
        if (needItem == NULL) {
            needItem = malloc(sizeof(HashMapItem));
            needItem->key = ch;
            needItem->val = 0;
            HASH_ADD_INT(need, key, needItem);
        }
        needItem->val++;
    }
    int *ans = malloc(sizeof(int[sLength]));
    *returnSize = 0;
    int valid = 0;
    // s[left..right) = Window Substring
    // s[right..n-1]  = Scanning
    int left = 0, right = 0;
    HashMapItem *window = NULL;
    while (right < sLength) {
        int add = s[right++];
        HashMapItem *needItem;
        HASH_FIND_INT(need, &add, needItem);
        if (needItem != NULL) {
            HashMapItem *winItem;
            HASH_FIND_INT(window, &add, winItem);
            if (winItem == NULL) {
                winItem = malloc(sizeof(HashMapItem));
                winItem->key = add;
                winItem->val = 0;
                HASH_ADD_INT(window, key, winItem);
            }
            if (++winItem->val == needItem->val) {
                ++valid;
            }
        }
        if (valid == HASH_COUNT(need)) {
            while (left < right - pLength) {
                int del = s[left++];
                HASH_FIND_INT(need, &del, needItem);
                if (needItem != NULL) {
                    HashMapItem *winItem;
                    HASH_FIND_INT(window, &del, winItem);
                    if (winItem->val == needItem->val) {
                        --valid;
                    }
                    winItem->val--;
                }
            }
        }
        if (valid == HASH_COUNT(need)) {
            ans[(*returnSize)++] = left;
        }
    }
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, need, cur, tmp) {
        HASH_DEL(need, cur);
        free(cur);
    }
    HASH_ITER(hh, window, cur, tmp) {
        HASH_DEL(window, cur);
        free(cur);
    }
    HASH_CLEAR(hh, need);
    HASH_CLEAR(hh, window);
    return ans;
}
// https://leetcode.cn/submissions/detail/391352490/
```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```c
struct ListNode *reverseList(struct ListNode *head) {
    struct ListNode *reverseHead = NULL;
    while (head != NULL) {
        struct ListNode *x = head->next;
        head->next = reverseHead;
        reverseHead = head;
        head = x;
    }
    return reverseHead;
}

struct ListNode *addTwoNumbers(struct ListNode *l1, struct ListNode *l2) {
    l1 = reverseList(l1), l2 = reverseList(l2);
    struct ListNode *dummyHead = malloc(sizeof(struct ListNode));
    dummyHead->val = -1;
    dummyHead->next = NULL;
    struct ListNode *ptr = dummyHead;
    int carry = 0;
    while (l1 != NULL || l2 != NULL || carry > 0) {
        int sum = carry;
        if (l1 != NULL) {
            sum += l1->val;
            l1 = l1->next;
        }
        if (l2 != NULL) {
            sum += l2->val;
            l2 = l2->next;
        }
        struct ListNode *x = malloc(sizeof(struct ListNode));
        x->val = sum % 10, x->next = NULL;
        ptr->next = x;
        ptr = ptr->next;
        carry = sum / 10;
    }
    struct ListNode *head = dummyHead->next;
    free(dummyHead);
    return reverseList(head);
}
// https://leetcode.cn/submissions/detail/391145715/
```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```c
// 删除并返回二叉搜索树 root 的最小节点
struct TreeNode *deleteMin(struct TreeNode **root) {
    if ((*root)->left == NULL) {
        struct TreeNode *x = *root;
        *root = (*root)->right;
        return x;
    }
    return deleteMin(&(*root)->left);
}

struct TreeNode *deleteNode(struct TreeNode *root, int key) {
    if (root == NULL) {
        return NULL;
    }
    if (key < root->val) {
        root->left = deleteNode(root->left, key);
    } else if (key > root->val) {
        root->right = deleteNode(root->right, key);
    } else {
        if (root->left == NULL) {
            struct TreeNode *right = root->right;
            free(root);
            return right;
        }
        if (root->right == NULL) {
            struct TreeNode *left = root->left;
            free(root);
            return left;
        }
        struct TreeNode *x = root;
        root = deleteMin(&x->right);
        root->right = x->right;
        root->left = x->left;
        free(x);
    }
    return root;
}
// https://leetcode.cn/submissions/detail/390011388/
```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```c
int cmp(const void *a, const void *b) {
    const int *arg1 = *(const int **) a;
    const int *arg2 = *(const int **) b;
    if (arg1[1] < arg2[1]) {
        return -1;
    } else if (arg1[1] > arg2[1]) {
        return 1;
    }
    return 0;
}

// 区间数组 intervals 无重叠区间的最大数量
int maxNonOverlappingIntervals(int **intervals, int intervalsSize) {
    qsort(intervals, intervalsSize, sizeof(int *), cmp);
    int count = 0;
    int minEnd = INT_MIN;
    for (int i = 0; i < intervalsSize; ++i) {
        int start = intervals[i][0];
        int end = intervals[i][1];
        if (start <= minEnd) {
            continue;
        }
        ++count;
        minEnd = end;
    }
    return count;
}

int findMinArrowShots(int **points, int pointsSize, int *pointsColSize) {
    if (pointsSize == 1) {
        return 1;
    }
    return maxNonOverlappingIntervals(points, pointsSize);
}
// https://leetcode.cn/submissions/detail/391305538/
```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```c
struct MyListNode {
    int key;
    int val;
    int freq;
    struct MyListNode *prev;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    struct MyListNode *last;
    int size;
} MyDoublyLinkedList;

MyDoublyLinkedList *myListCreate() {
    MyDoublyLinkedList *obj = malloc(sizeof(MyDoublyLinkedList));
    obj->first = NULL;
    obj->last = NULL;
    obj->size = 0;
    return obj;
}

void myListAddLast(MyDoublyLinkedList *obj, struct MyListNode *x) {
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        obj->last->next = x;
        x->prev = obj->last;
        obj->last = x;
    }
    obj->size++;
}

void myListRemoveFirst(MyDoublyLinkedList *obj) {
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->first = obj->first->next;
        obj->first->prev = NULL;
    }
    free(x);
    obj->size--;
}

void myListRemoveLast(MyDoublyLinkedList *obj) {
    struct MyListNode *x = obj->last;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->last = obj->last->prev;
        obj->last->next = NULL;
    }
    free(x);
    obj->size--;
}

void myListRemove(MyDoublyLinkedList *obj, struct MyListNode *x) {
    if (x == obj->first) {
        myListRemoveFirst(obj);
    } else if (x == obj->last) {
        myListRemoveLast(obj);
    } else {
        x->prev->next = x->next;
        x->next->prev = x->prev;
        free(x);
        obj->size--;
    }
}

struct MyListNode *myListGetFirst(MyDoublyLinkedList *obj) {
    return obj->first;
}

bool myListEmpty(MyDoublyLinkedList *obj) {
    return obj->first == NULL;
}

void myListFree(MyDoublyLinkedList *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

typedef struct {
    int key;
    void *val;
    UT_hash_handle hh;
} HashMapItem;

typedef struct {
    HashMapItem *keyToNode;
    HashMapItem *freqToList;
    int minFreq;
    int capacity;
} LFUCache;

LFUCache *lFUCacheCreate(int capacity) {
    LFUCache *obj = malloc(sizeof(LFUCache));
    obj->keyToNode = NULL;
    obj->freqToList = NULL;
    obj->minFreq = 0;
    obj->capacity = capacity;
    return obj;
}

bool lFUCacheContains(LFUCache *obj, int key) {
    HashMapItem *item;
    HASH_FIND_INT(obj->keyToNode, &key, item);
    return item != NULL;
}

bool lFUCacheFull(LFUCache *obj) {
    return HASH_COUNT(obj->keyToNode) == obj->capacity;
}

void lFUCacheAdd(LFUCache *obj, int key, int val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->key = key;
    x->val = val;
    x->freq = 1;
    x->prev = NULL;
    x->next = NULL;
    HashMapItem *addNodeItem = malloc(sizeof(HashMapItem));
    addNodeItem->key = key;
    addNodeItem->val = x;
    HASH_ADD_INT(obj->keyToNode, key, addNodeItem);
    int minFreq = 1;
    HashMapItem *minFreqItem;
    HASH_FIND_INT(obj->freqToList, &minFreq, minFreqItem);
    if (minFreqItem == NULL) {
        minFreqItem = malloc(sizeof(HashMapItem));
        minFreqItem->key = minFreq;
        minFreqItem->val = myListCreate();
        HASH_ADD_INT(obj->freqToList, key, minFreqItem);
    }
    MyDoublyLinkedList *list = (MyDoublyLinkedList *) minFreqItem->val;
    myListAddLast(list, x);
    obj->minFreq = 1;
}

void lFUCacheRemove(LFUCache *obj) {
    HashMapItem *minFreqItem;
    HASH_FIND_INT(obj->freqToList, &obj->minFreq, minFreqItem);
    MyDoublyLinkedList *minFreqList = (MyDoublyLinkedList *) minFreqItem->val;
    int delNodeKey = myListGetFirst(minFreqList)->key;
    HashMapItem *delNodeItem;
    HASH_FIND_INT(obj->keyToNode, &delNodeKey, delNodeItem);
    HASH_DEL(obj->keyToNode, delNodeItem);
    free(delNodeItem);
    myListRemoveFirst(minFreqList);
    if (myListEmpty(minFreqList)) {
        HASH_DEL(obj->freqToList, minFreqItem);
        free(minFreqItem);
    }
}

int lFUCacheTouch(LFUCache *obj, int key, int val) {
    HashMapItem *nodeItem;
    HASH_FIND_INT(obj->keyToNode, &key, nodeItem);
    struct MyListNode *x = (struct MyListNode *) nodeItem->val;
    int newVal = x->val;
    if (val != INT_MIN) {
        newVal = val;
    }
    int oldFreq = x->freq;
    int newFreq = oldFreq + 1;
    HashMapItem *oldFreqItem;
    HASH_FIND_INT(obj->freqToList, &oldFreq, oldFreqItem);
    MyDoublyLinkedList *oldFreqList = (MyDoublyLinkedList *) oldFreqItem->val;
    myListRemove(oldFreqList, x);
    if (myListEmpty(oldFreqList)) {
        HASH_DEL(obj->freqToList, oldFreqItem);
        free(oldFreqItem);
        if (obj->minFreq == oldFreq) {
            obj->minFreq = newFreq;
        }
    }
    x = malloc(sizeof(struct MyListNode));
    x->key = key;
    x->val = newVal;
    x->freq = newFreq;
    x->prev = NULL;
    x->next = NULL;
    nodeItem->val = x;
    HashMapItem *newFreqItem;
    HASH_FIND_INT(obj->freqToList, &newFreq, newFreqItem);
    if (newFreqItem == NULL) {
        newFreqItem = malloc(sizeof(HashMapItem));
        newFreqItem->key = newFreq;
        newFreqItem->val = myListCreate();
        HASH_ADD_INT(obj->freqToList, key, newFreqItem);
    }
    MyDoublyLinkedList *newFreqList = (MyDoublyLinkedList *) newFreqItem->val;
    myListAddLast(newFreqList, x);
    return newVal;
}

int lFUCacheGet(LFUCache *obj, int key) {
    if (lFUCacheContains(obj, key)) {
        return lFUCacheTouch(obj, key, INT_MIN);
    }
    return -1;
}

void lFUCachePut(LFUCache *obj, int key, int val) {
    if (obj->capacity > 0) {
        if (lFUCacheContains(obj, key)) {
            lFUCacheTouch(obj, key, val);
        } else {
            if (lFUCacheFull(obj)) {
                lFUCacheRemove(obj);
            }
            lFUCacheAdd(obj, key, val);
        }
    }
}

void lFUCacheFree(LFUCache *obj) {
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, obj->keyToNode, cur, tmp) {
        HASH_DEL(obj->keyToNode, cur);
        free(cur);
    }
    HASH_CLEAR(hh, obj->keyToNode);
    HASH_ITER(hh, obj->freqToList, cur, tmp) {
        myListFree(cur->val);
        HASH_DEL(obj->freqToList, cur);
        free(cur);
    }
    HASH_CLEAR(hh, obj->freqToList);
    free(obj);
}
// https://leetcode.cn/submissions/detail/391164820/
```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```c
int ans;

bool isReversePair(const int *nums, int i, int j) {
    return i < j && (long) nums[i] > (long) 2 * nums[j];
}

int countReversePairs(const int *nums, int lo, int mid, int hi) {
    int res = 0;
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

void merge(int *nums, int *aux, int lo, int mid, int hi) {
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

void sort(int *nums, int *aux, int lo, int hi) {
    if (lo >= hi) {
        return;
    }
    int mid = lo + (hi - lo) / 2;
    sort(nums, aux, lo, mid);
    sort(nums, aux, mid + 1, hi);
    merge(nums, aux, lo, mid, hi);
}

int reversePairs(int *nums, int numsSize) {
    ans = 0;
    int *aux = malloc(sizeof(int[numsSize]));
    sort(nums, aux, 0, numsSize - 1);
    free(aux);
    return ans;
}
// https://leetcode.cn/submissions/detail/390847923/
```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```c
typedef struct {
    char *key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

HashMapItem *memo = NULL;

// 子数组 nums[0..i] 目标和为 target 的不同表达式的数目
int findTargetSumWaysMemo(int *nums, int i, int target) {
    if (i < 0) {
        return target == 0 ? 1 : 0;
    }
    char *key = calloc(8, sizeof(char));
    sprintf(key, "%d,%d", i, target);
    HashMapItem *item;
    HASH_FIND_STR(memo, key, item);
    if (item == NULL) {
        item = malloc(sizeof(HashMapItem));
        item->key = key;

        int x = nums[i];
        // x 前添加 + 号
        // sum(nums[0..i-1]) = target - x
        int sp1 = findTargetSumWaysMemo(nums, i - 1, target - x);
        // x 前添加 - 号
        // sum(nums[0..i-1]) = target + x
        int sp2 = findTargetSumWaysMemo(nums, i - 1, target + x);
        item->val = sp1 + sp2;
        HASH_ADD_STR(memo, key, item);
    }
    return item->val;
}

int findTargetSumWays(int *nums, int numsSize, int target) {
    int sum = 0;
    for (int i = 0; i < numsSize; ++i) {
        sum += nums[i];
    }
    if (abs(target) > sum) {
        return 0;
    }
    int ans = findTargetSumWaysMemo(nums, numsSize - 1, target);
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, memo, cur, tmp) {
        HASH_DEL(memo, cur);
        free(cur);
    }
    HASH_CLEAR(hh, memo);
    return ans;
}
// https://leetcode.cn/submissions/detail/391219400/
```

```c
// 数组 nums 和为 sum 的子集的数目，其中 nums[i] >= 0, sum >= 0
int numSubsetSum(const int *nums, int numsSize, int sum) {
    int n = numsSize;
    // dp[i][j] = 子数组 nums[0..i-1] 和为 j 的子集的数目
    int dp[n + 1][sum + 1];
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
                int sp1 = dp[i - 1][j];
                // 包含 x
                int sp2 = dp[i - 1][j - x];
                dp[i][j] = sp1 + sp2;
            } else {
                dp[i][j] = dp[i - 1][j];
            }
        }
    }
    return dp[n][sum];
}

int findTargetSumWays(const int *nums, int numsSize, int target) {
    // sum(A) - sum(B) = target
    // sum(A) = target + sum(B)
    // sum(A) + sum(A) = target + sum(B) + sum(A)
    // 2 * sum(A) = target + sum(nums)
    // sum(A) = (target + sum(nums)) / 2
    // 问题转化为：数组 nums 中存在几个子集 A
    // 使得 A 中元素的和为 (target + sum(nums)) / 2
    int sum = 0;
    for (int i = 0; i < numsSize; ++i) {
        sum += nums[i];
    }
    if (abs(target) > sum || (sum + target) % 2 == 1) {
        return 0;
    }
    return numSubsetSum(nums, numsSize, (sum + target) / 2);
}
// https://leetcode.cn/submissions/detail/390326522/
```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```c
typedef struct {
    int key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *nextGreaterElementSP(const int *nums, int numsSize, int *returnSize) {
    *returnSize = numsSize;
    int *ans = malloc(sizeof(int[numsSize]));
    int stack[numsSize];
    int top = 0;
    for (int i = numsSize - 1; i >= 0; --i) {
        int x = nums[i];
        while (top > 0 && stack[top - 1] < x) {
            --top;
        }
        ans[i] = top == 0 ? -1 : stack[top - 1];
        stack[top++] = x;
    }
    return ans;
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *nextGreaterElement(int *nums1, int nums1Size, int *nums2, int nums2Size, int *returnSize) {
    int greaterSize = 0;
    int *greater = nextGreaterElementSP(nums2, nums2Size, &greaterSize);
    HashMapItem *valToGreater = NULL;
    for (int i = 0; i < nums2Size; ++i) {
        HashMapItem *item = malloc(sizeof(HashMapItem));
        item->key = nums2[i];
        item->val = greater[i];
        HASH_ADD_INT(valToGreater, key, item);
    }
    *returnSize = nums1Size;
    int *ans = malloc(sizeof(int[nums1Size]));
    for (int i = 0; i < nums1Size; ++i) {
        HashMapItem *item;
        HASH_FIND_INT(valToGreater, &nums1[i], item);
        ans[i] = item->val;
    }
    free(greater);
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, valToGreater, cur, tmp) {
        HASH_DEL(valToGreater, cur);
        free(cur);
    }
    HASH_CLEAR(hh, valToGreater);
    return ans;
}
// https://leetcode.cn/submissions/detail/391282019/
```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```c
/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *nextGreaterElements(const int *nums, int numsSize, int *returnSize) {
    *returnSize = numsSize;
    int *ans = malloc(sizeof(int[numsSize]));
    int stack[numsSize];
    int top = 0;
    for (int i = 2 * numsSize - 1; i >= 0; --i) {
        int k = i % numsSize;
        int x = nums[k];
        while (top > 0 && stack[top - 1] <= x) {
            --top;
        }
        ans[k] = top == 0 ? -1 : stack[top - 1];
        stack[top++] = x;
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391280974/
```

```c
typedef int Value;

struct MyListNode {
    Value val;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    int size;
} MyLinkedListStack;

MyLinkedListStack *myStackCreate() {
    MyLinkedListStack *obj = malloc(sizeof(MyLinkedListStack));
    obj->first = NULL;
    obj->size = 0;
    return obj;
}

void myStackPush(MyLinkedListStack *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
    } else {
        x->next = obj->first;
        obj->first = x;
    }
    obj->size++;
}

Value myStackPop(MyLinkedListStack *obj) {
    Value val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
    } else {
        obj->first = obj->first->next;
    }
    free(x);
    obj->size--;
    return val;
}

Value myStackPeek(MyLinkedListStack *obj) {
    return obj->first->val;
}

int myStackSize(MyLinkedListStack *obj) {
    return obj->size;
}

bool myStackEmpty(MyLinkedListStack *obj) {
    return obj->size == 0;
}

void myStackFree(MyLinkedListStack *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *nextGreaterElements(const int *nums, int numsSize, int *returnSize) {
    *returnSize = numsSize;
    int *ans = malloc(sizeof(int[numsSize]));
    MyLinkedListStack *stack = myStackCreate();
    for (int i = 2 * numsSize - 1; i >= 0; --i) {
        int k = i % numsSize;
        int x = nums[k];
        while (!myStackEmpty(stack) && myStackPeek(stack) <= x) {
            myStackPop(stack);
        }
        ans[k] = myStackEmpty(stack) ? -1 : myStackPeek(stack);
        myStackPush(stack, x);
    }
    myStackFree(stack);
    return ans;
}
// https://leetcode.cn/submissions/detail/391408566/
```

```c
typedef int Value;

typedef struct {
    Value *array;
    int capacity;
    int size;
} MyResizingArrayStack;

MyResizingArrayStack *myStackCreate() {
    MyResizingArrayStack *obj = malloc(sizeof(MyResizingArrayStack));
    obj->size = 0;
    obj->capacity = 8;
    obj->array = malloc(sizeof(Value) * obj->capacity);
    return obj;
}

void myStackResize(MyResizingArrayStack *obj, int capacity) {
    obj->array = realloc(obj->array, sizeof(Value) * capacity);
    obj->capacity = capacity;
}

void myStackPush(MyResizingArrayStack *obj, Value val) {
    if (obj->size == obj->capacity) {
        myStackResize(obj, obj->capacity * 2);
    }
    obj->array[obj->size++] = val;
}

Value myStackPop(MyResizingArrayStack *obj) {
    Value val = obj->array[obj->size - 1];
    obj->size--;
    if (obj->size > 0 && obj->size == obj->capacity / 4) {
        myStackResize(obj, obj->capacity / 2);
    }
    return val;
}

Value myStackPeek(MyResizingArrayStack *obj) {
    return obj->array[obj->size - 1];
}

int myStackSize(MyResizingArrayStack *obj) {
    return obj->size;
}

bool myStackEmpty(MyResizingArrayStack *obj) {
    return obj->size == 0;
}

void myStackFree(MyResizingArrayStack *obj) {
    free(obj->array);
    free(obj);
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *nextGreaterElements(const int *nums, int numsSize, int *returnSize) {
    *returnSize = numsSize;
    int *ans = malloc(sizeof(int[numsSize]));
    MyResizingArrayStack *stack = myStackCreate();
    for (int i = 2 * numsSize - 1; i >= 0; --i) {
        int k = i % numsSize;
        int x = nums[k];
        while (!myStackEmpty(stack) && myStackPeek(stack) <= x) {
            myStackPop(stack);
        }
        ans[k] = myStackEmpty(stack) ? -1 : myStackPeek(stack);
        myStackPush(stack, x);
    }
    myStackFree(stack);
    return ans;
}
// https://leetcode.cn/submissions/detail/391281544/
```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```c
int fib(int n) {
    if (n == 0) {
        return 0;
    }
    if (n == 1) {
        return 1;
    }
    int dp[n + 1];
    dp[0] = 0;
    dp[1] = 1;
    for (int i = 2; i <= n; ++i) {
        dp[i] = dp[i - 1] + dp[i - 2];
    }
    return dp[n];
}
// https://leetcode.cn/submissions/detail/391142045/
```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```c
int longestPalindromeSubseq(char *s) {
    size_t n = strlen(s);
    // dp[i][j] = 子串 s[i..j] 的最长回文子序列的长度
    int dp[n][n];
    // 遍历对角线
    for (int i = 0; i < n; ++i) {
        dp[i][i] = 1;
    }
    // 遍历下三角形
    for (int i = 0; i < n; ++i) {
        for (int j = 0; j < i; ++j) {
            dp[i][j] = 0;
        }
    }
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
                dp[i][j] = fmax(sp1, sp2);
            }
        }
    }
    return dp[0][n - 1];
}
// https://leetcode.cn/submissions/detail/391413629/
```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```c
int change(int amount, const int *coins, int coinsSize) {
    // dp[i][j] = 使用硬币 coins[0..i-1] 凑成总金额 j 的组合数
    int dp[coinsSize + 1][amount + 1];
    memset(dp, 0, sizeof(dp));
    // 总金额为 0
    for (int i = 1; i <= coinsSize; ++i) {
        dp[i][0] = 1;
    }
    // 硬币数为 0
    for (int j = 1; j <= amount; ++j) {
        dp[0][j] = 0;
    }
    dp[0][0] = 1;
    for (int i = 1; i <= coinsSize; ++i) {
        for (int j = 1; j <= amount; ++j) {
            int x = coins[i - 1];
            if (j < x) {
                // 不包含硬币 x
                dp[i][j] = dp[i - 1][j];
            } else {
                int sp1 = dp[i - 1][j]; // 包含    0 个硬币 x
                int sp2 = dp[i][j - x]; // 包含 >= 1 个硬币 x
                dp[i][j] = sp1 + sp2;
            }
        }
    }
    return dp[coinsSize][amount];
}
// https://leetcode.cn/submissions/detail/390183862/
```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```c
int sum;

void dfs(struct TreeNode *root) {
    if (root == NULL) {
        return;
    }
    dfs(root->right);
    sum += root->val;
    root->val = sum;
    dfs(root->left);
}

struct TreeNode *convertBST(struct TreeNode *root) {
    sum = 0;
    dfs(root);
    return root;
}
// https://leetcode.cn/submissions/detail/391165543/
```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```c
int diameter;

int maxDepth(struct TreeNode *root) {
    if (root == NULL) {
        return 0;
    }
    int left = maxDepth(root->left);
    int right = maxDepth(root->right);
    diameter = fmax(diameter, left + right);
    return 1 + fmax(left, right);
}

int diameterOfBinaryTree(struct TreeNode *root) {
    diameter = 0;
    maxDepth(root);
    return diameter;
}
// https://leetcode.cn/submissions/detail/391149966/
```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```c
typedef struct {
    int key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

bool checkInclusion(char *s1, char *s2) {
    size_t s1Length = strlen(s1), s2Length = strlen(s2);
    HashMapItem *need = NULL;
    for (int i = 0; i < s1Length; ++i) {
        int ch = s1[i];
        HashMapItem *needItem;
        HASH_FIND_INT(need, &ch, needItem);
        if (needItem == NULL) {
            needItem = malloc(sizeof(HashMapItem));
            needItem->key = ch;
            needItem->val = 0;
            HASH_ADD_INT(need, key, needItem);
        }
        needItem->val++;
    }
    bool ans = false;
    int valid = 0;
    // s2[left..right) = Window Substring
    // s2[right..n-1]  = Scanning
    int left = 0, right = 0;
    HashMapItem *window = NULL;
    while (right < s2Length) {
        int add = s2[right++];
        HashMapItem *needItem;
        HASH_FIND_INT(need, &add, needItem);
        if (needItem != NULL) {
            HashMapItem *winItem;
            HASH_FIND_INT(window, &add, winItem);
            if (winItem == NULL) {
                winItem = malloc(sizeof(HashMapItem));
                winItem->key = add;
                winItem->val = 0;
                HASH_ADD_INT(window, key, winItem);
            }
            if (++winItem->val == needItem->val) {
                ++valid;
            }
        }
        if (valid == HASH_COUNT(need)) {
            while (left < right - s1Length) {
                int del = s2[left++];
                HASH_FIND_INT(need, &del, needItem);
                if (needItem != NULL) {
                    HashMapItem *winItem;
                    HASH_FIND_INT(window, &del, winItem);
                    if (winItem->val == needItem->val) {
                        --valid;
                    }
                    winItem->val--;
                }
            }
        }
        if (valid == HASH_COUNT(need)) {
            ans = true;
            break;
        }
    }
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, need, cur, tmp) {
        HASH_DEL(need, cur);
        free(cur);
    }
    HASH_ITER(hh, window, cur, tmp) {
        HASH_DEL(window, cur);
        free(cur);
    }
    HASH_CLEAR(hh, need);
    HASH_CLEAR(hh, window);
    return ans;
}
// https://leetcode.cn/submissions/detail/391353543/
```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```c
// 子串 s1[0..i] s2[0..j] 的最小删除步数
int minDistanceMemo(const char *s1, int i, const char *s2, int j, int *memo) {
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
    int *p = memo + i * strlen(s2) + j;
    if (*p == -1) {
        if (s1[i] == s2[j]) {
            // s1[0..i-1][i]
            // s2[0..j-1][j]
            *p = minDistanceMemo(s1, i - 1, s2, j - 1, memo);
        } else {
            // 删除 s1[i] s2[j]
            // s1[0..i-1][i]
            // s2[0..j-1][j]
            int sp1 = minDistanceMemo(s1, i - 1, s2, j - 1, memo) + 2;
            // 删除 s2[j]
            // s1[0..i]
            // s2[0..j-1][j]
            int sp2 = minDistanceMemo(s1, i, s2, j - 1, memo) + 1;
            // 删除 s1[i]
            // s1[0..i-1][i]
            // s2[0..j]
            int sp3 = minDistanceMemo(s1, i - 1, s2, j, memo) + 1;
            *p = fmin(fmin(sp1, sp2), sp3);
        }
    }
    return *p;
}

int minDistance(char *word1, char *word2) {
    int n1 = strlen(word1);
    int n2 = strlen(word2);
    if (n1 == 0) {
        return n2;
    }
    if (n2 == 0) {
        return n1;
    }
    int memo[n1][n2];
    for (int i = 0; i < n1; ++i) {
        for (int j = 0; j < n2; ++j) {
            memo[i][j] = -1;
        }
    }
    return minDistanceMemo(word1, n1 - 1, word2, n2 - 1, memo[0]);
}
// https://leetcode.cn/submissions/detail/391221823/
```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```c
struct TreeNode *mergeTrees(struct TreeNode *root1, struct TreeNode *root2) {
    if (root1 == NULL) {
        return root2;
    }
    if (root2 == NULL) {
        return root1;
    }
    struct TreeNode *mRoot = malloc(sizeof(struct TreeNode));
    mRoot->val = root1->val + root2->val;
    mRoot->left = mergeTrees(root1->left, root2->left);
    mRoot->right = mergeTrees(root1->right, root2->right);
    return mRoot;
}
// https://leetcode.cn/submissions/detail/390003581/
```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```c
typedef struct {
    char *key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

HashMapItem *counter = NULL;

int ansSize;
int ansCapacity;
struct TreeNode **ans;

// 深度优先搜索二叉树 root，返回前序遍历结果的字符串表示
char *dfs(struct TreeNode *root) {
    if (root == NULL) {
        return "#";
    }
    char *left = dfs(root->left);
    char *right = dfs(root->right);
    char *res = calloc(strlen(left) + strlen(right) + 8, sizeof(char));
    sprintf(res, "%d,%s,%s", root->val, left, right);
    HashMapItem *item;
    HASH_FIND_STR(counter, res, item);
    if (item == NULL) {
        item = malloc(sizeof(HashMapItem));
        item->key = res;
        item->val = 1;
        HASH_ADD_STR(counter, key, item);
    } else {
        if (++item->val == 2) {
            if (ansSize == ansCapacity) {
                ansCapacity *= 2;
                ans = realloc(ans, sizeof(struct TreeNode *) * ansCapacity);
            }
            ans[ansSize++] = root;
        }
    }
    return res;
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
struct TreeNode **findDuplicateSubtrees(struct TreeNode *root, int *returnSize) {
    ansSize = 0;
    ansCapacity = 8;
    ans = malloc(sizeof(struct TreeNode *) * ansCapacity);
    dfs(root);
    *returnSize = ansSize;
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, counter, cur, tmp) {
        HASH_DEL(counter, cur);
        free(cur);
    }
    HASH_CLEAR(hh, counter);
    return ans;
}
// https://leetcode.cn/submissions/detail/391162980/
```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```c
struct TreeNode *constructMaximumBinaryTreeRange(const int *nums, int lo, int hi) {
    if (lo > hi) {
        return NULL;
    }
    int maxIndex = lo;
    for (int i = maxIndex + 1; i <= hi; ++i) {
        if (nums[i] > nums[maxIndex]) {
            maxIndex = i;
        }
    }
    struct TreeNode *root = malloc(sizeof(struct TreeNode));
    root->val = nums[maxIndex];
    root->left = constructMaximumBinaryTreeRange(nums, lo, maxIndex - 1);
    root->right = constructMaximumBinaryTreeRange(nums, maxIndex + 1, hi);
    return root;
}

struct TreeNode *constructMaximumBinaryTree(const int *nums, int numsSize) {
    return constructMaximumBinaryTreeRange(nums, 0, numsSize - 1);
}
// https://leetcode.cn/submissions/detail/389151358/
```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```c
static const int LAND = 1;
static const int WATER = 0;

int area;

void floodFill(int **grid, int gridSize, int *gridColSize, int row, int col) {
    if (row < 0 || row >= gridSize || col < 0 || col >= *gridColSize || grid[row][col] == WATER) {
        return;
    }
    ++area;
    grid[row][col] = WATER;
    floodFill(grid, gridSize, gridColSize, row, col + 1);
    floodFill(grid, gridSize, gridColSize, row, col - 1);
    floodFill(grid, gridSize, gridColSize, row + 1, col);
    floodFill(grid, gridSize, gridColSize, row - 1, col);
}

int maxAreaOfIsland(int **grid, int gridSize, int *gridColSize) {
    int ans = 0;
    for (int row = 0; row < gridSize; ++row) {
        for (int col = 0; col < *gridColSize; ++col) {
            if (grid[row][col] == LAND) {
                area = 0;
                floodFill(grid, gridSize, gridColSize, row, col);
                ans = fmax(ans, area);
            }
        }
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391255004/
```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```c
typedef struct {
    int key;
    bool val;
    UT_hash_handle hh;
} HashMapItem;

HashMapItem *memo = NULL;

int used;
int target;
int *pathSums;

// 遍历『决策森林』的 k 棵『决策树』
// 一棵『决策树』的『路径』代表一个『等和子集』
// tree = 第几棵『决策树』，取 [0..k-1] 为值
// edge =『决策树』的『边』，取数组 nums 的索引为值
// pathSums[tree] = 第几棵『决策树』的『路径和』
bool backtrack(int *nums, int numsSize, int k, int tree, int edge) {
    bool res = false;
    if (tree == k) {
        res = true;
    } else if (pathSums[tree] == target) {
        HashMapItem *item;
        HASH_FIND_INT(memo, &used, item);
        // 通过缓存，对同一个『森林』，优化『树』的遍历，避免『路径+路径』重复
        // 例如 [1->2->3] 和 [4->5->6] 分别是两条『路径』
        // 如果 A.[1->2->3] -> B.[4->5->6] -> C.[] 是不行的
        // 那么 A.[4->5->6] -> B.[1->2->3] -> C.[] 也是不行的
        // 因为 C 的可选『边』是一样的
        if (item == NULL) {
            item = malloc(sizeof(HashMapItem));
            item->key = used;
            // 遍历下一棵『决策树』
            item->val = backtrack(nums, numsSize, k, tree + 1, -1);
            HASH_ADD_INT(memo, key, item);
        }
        res = item->val;
    } else {
        // 通过去重，对同一棵树，优化『边』的遍历，避免『边+边』重复
        // 例如 1 和 2 分别是两条『边』，[1->2] 和 [2->1] 是重复的
        while (++edge < numsSize) {
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
            used |= (1 << edge);
            res = backtrack(nums, numsSize, k, tree, edge);
            if (res) {
                break;
            }
            pathSums[tree] -= x;
            //『异或』运算，将第 edge 位修改为 0
            used ^= (1 << edge);
        }
    }
    return res;
}

bool canPartitionKSubsets(int *nums, int numsSize, int k) {
    if (k > numsSize) {
        return false;
    }
    int sum = 0;
    for (int i = 0; i < numsSize; ++i) {
        sum += nums[i];
    }
    if (sum % k != 0) {
        return false;
    }
    used = 0;
    target = sum / k;
    pathSums = calloc(k, sizeof(int));
    bool ans = backtrack(nums, numsSize, k, 0, -1);
    free(pathSums);
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, memo, cur, tmp) {
        HASH_DEL(memo, cur);
        free(cur);
    }
    HASH_CLEAR(hh, memo);
    return ans;
}
// https://leetcode.cn/submissions/detail/391308942/
```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```c
struct TreeNode *searchBST(struct TreeNode *root, int val) {
    if (root == NULL) {
        return NULL;
    }
    if (val < root->val) {
        return searchBST(root->left, val);
    }
    if (root->val < val) {
        return searchBST(root->right, val);
    }
    return root;
}
// https://leetcode.cn/submissions/detail/390003878/
```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```c
struct TreeNode *insertIntoBST(struct TreeNode *root, int val) {
    if (root == NULL) {
        struct TreeNode *x = malloc(sizeof(struct TreeNode));
        x->val = val;
        x->left = NULL;
        x->right = NULL;
        return x;
    }
    if (val < root->val) {
        root->left = insertIntoBST(root->left, val);
    }
    if (root->val < val) {
        root->right = insertIntoBST(root->right, val);
    }
    return root;
}
// https://leetcode.cn/submissions/detail/390007405/
```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```c
int search(const int *nums, int numsSize, int target) {
    int lo = 0, hi = numsSize - 1;
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
// https://leetcode.cn/submissions/detail/391139034/
```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```c
int *sum1;
int *sum2;

int *prefixSum(const char *s) {
    int n = strlen(s);
    int *sum = malloc(sizeof(int[n]));
    sum[0] = s[0];
    for (int i = 1; i < n; ++i) {
        sum[i] = sum[i - 1] + s[i];
    }
    return sum;
}

// 子串 s1[0..i] s2[0..j] 的最小 ASCII 删除和
int minimumDeleteSumMemo(const char *s1, int i, const char *s2, int j, int *memo) {
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
    int *p = memo + i * strlen(s2) + j;
    if (*p == -1) {
        if (s1[i] == s2[j]) {
            // s1[0..i-1][i]
            // s2[0..j-1][j]
            *p = minimumDeleteSumMemo(s1, i - 1, s2, j - 1, memo);
        } else {
            // 删除 s1[i] s2[j]
            // s1[0..i-1][i]
            // s2[0..j-1][j]
            int sp1 = minimumDeleteSumMemo(s1, i - 1, s2, j - 1, memo) + s1[i] + s2[j];
            // 删除 s2[j]
            // s1[0..i]
            // s2[0..j-1][j]
            int sp2 = minimumDeleteSumMemo(s1, i, s2, j - 1, memo) + s2[j];
            // 删除 s1[i]
            // s1[0..i-1][i]
            // s2[0..j]
            int sp3 = minimumDeleteSumMemo(s1, i - 1, s2, j, memo) + s1[i];
            *p = fmin(fmin(sp1, sp2), sp3);
        }
    }
    return *p;
}

int minimumDeleteSum(char *s1, char *s2) {
    sum1 = prefixSum(s1);
    sum2 = prefixSum(s2);
    int n1 = strlen(s1);
    int n2 = strlen(s2);
    int memo[n1][n2];
    for (int i = 0; i < n1; ++i) {
        for (int j = 0; j < n2; ++j) {
            memo[i][j] = -1;
        }
    }
    int ans = minimumDeleteSumMemo(s1, n1 - 1, s2, n2 - 1, memo[0]);
    free(sum1);
    free(sum2);
    return ans;
}
// https://leetcode.cn/submissions/detail/391222316/
```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```c
int maxProfit(int *prices, int pricesSize, int fee) {
    // dp[i][0] = 第 i 天，空仓状态下的最大利润
    // dp[i][1] = 第 i 天，持仓状态下的最大利润
    int dp[pricesSize][2];
    dp[0][0] = 0;
    dp[0][1] = -prices[0] - fee;
    for (int i = 1; i < pricesSize; ++i) {
        // dp[i - 1][0]             >= dp[i - 1][0] - prices[i] - fee
        // dp[i - 1][1] + prices[i] >= dp[i - 1][1]
        // => dp[i][0] >= dp[i][1]
        dp[i][0] = fmax(dp[i - 1][0], dp[i - 1][1] + prices[i]);
        dp[i][1] = fmax(dp[i - 1][0] - prices[i] - fee, dp[i - 1][1]);
    }
    return dp[pricesSize - 1][0];
}
// https://leetcode.cn/submissions/detail/390322041/
```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```c
/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *dailyTemperatures(const int *temperatures, int temperaturesSize, int *returnSize) {
    *returnSize = temperaturesSize;
    int *ans = malloc(sizeof(int[temperaturesSize]));
    int stack[temperaturesSize];
    int top = 0;
    for (int i = temperaturesSize - 1; i >= 0; --i) {
        while (top > 0 && temperatures[stack[top - 1]] <= temperatures[i]) {
            --top;
        }
        ans[i] = top == 0 ? 0 : (stack[top - 1] - i);
        stack[top++] = i;
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391282252/
```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```c
// TODO
```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```c
typedef char *Value;

struct MyListNode {
    Value val;
    struct MyListNode *next;
};

typedef struct {
    struct MyListNode *first;
    struct MyListNode *last;
    int size;
} MyLinkedListQueue;

MyLinkedListQueue *myQueueCreate() {
    MyLinkedListQueue *obj = malloc(sizeof(MyLinkedListQueue));
    obj->first = NULL;
    obj->last = NULL;
    obj->size = 0;
    return obj;
}

void myQueuePush(MyLinkedListQueue *obj, Value val) {
    struct MyListNode *x = malloc(sizeof(struct MyListNode));
    x->val = val;
    x->next = NULL;
    if (obj->size == 0) {
        obj->first = x;
        obj->last = x;
    } else {
        obj->last->next = x;
        obj->last = x;
    }
    obj->size++;
}

Value myQueuePop(MyLinkedListQueue *obj) {
    Value val = obj->first->val;
    struct MyListNode *x = obj->first;
    if (obj->size == 1) {
        obj->first = NULL;
        obj->last = NULL;
    } else {
        obj->first = obj->first->next;
    }
    free(x);
    obj->size--;
    return val;
}

Value myQueuePeek(MyLinkedListQueue *obj) {
    return obj->first->val;
}

int myQueueSize(MyLinkedListQueue *obj) {
    return obj->size;
}

bool myQueueEmpty(MyLinkedListQueue *obj) {
    return obj->size == 0;
}

void myQueueFree(MyLinkedListQueue *obj) {
    struct MyListNode *p = obj->first;
    while (p != NULL) {
        struct MyListNode *x = p;
        p = p->next;
        free(x);
    }
    free(obj);
}

typedef struct {
    char *key;
    UT_hash_handle hh;
} HashSetItem;

char *plusOne(char *s, int j) {
    char *copy = calloc(strlen(s) + 1, sizeof(char));
    strcpy(copy, s);
    if (copy[j] == '9') {
        copy[j] = '0';
    } else {
        copy[j] += 1;
    }
    return copy;
}

char *minusOne(char *s, int j) {
    char *copy = calloc(strlen(s) + 1, sizeof(char));
    strcpy(copy, s);
    if (copy[j] == '0') {
        copy[j] = '9';
    } else {
        copy[j] -= 1;
    }
    return copy;
}

int openLock(char **deadends, int deadendsSize, char *target) {
    HashSetItem *marked = NULL;
    HashSetItem *item;
    for (int i = 0; i < deadendsSize; ++i) {
        HASH_FIND_STR(marked, deadends[i], item);
        if (item == NULL) {
            item = malloc(sizeof(HashSetItem));
            item->key = deadends[i];
            HASH_ADD_STR(marked, key, item);
        }
    }
    MyLinkedListQueue *queue = myQueueCreate();
    char *source = calloc(5, sizeof(char));
    strcpy(source, "0000");
    HASH_FIND_STR(marked, source, item);
    if (item == NULL) {
        item = malloc(sizeof(HashSetItem));
        item->key = source;
        HASH_ADD_STR(marked, key, item);
        myQueuePush(queue, source);
    }
    int step = 0;
    bool find = false;
    while (!myQueueEmpty(queue)) {
        int size = myQueueSize(queue);
        for (int i = 0; i < size; ++i) {
            char *s = myQueuePop(queue);
            if (strcmp(s, target) == 0) {
                find = true;
                break;
            }
            for (int j = 0; j < 4; ++j) {
                char *plus = plusOne(s, j);
                HASH_FIND_STR(marked, plus, item);
                if (item == NULL) {
                    item = malloc(sizeof(HashSetItem));
                    item->key = plus;
                    HASH_ADD_STR(marked, key, item);
                    myQueuePush(queue, plus);
                }
                char *minus = minusOne(s, j);
                HASH_FIND_STR(marked, minus, item);
                if (item == NULL) {
                    item = malloc(sizeof(HashSetItem));
                    item->key = minus;
                    HASH_ADD_STR(marked, key, item);
                    myQueuePush(queue, minus);
                }
            }
        }
        if (find) {
            break;
        }
        ++step;
    }
    myQueueFree(queue);
    HashSetItem *cur, *tmp;
    HASH_ITER(hh, marked, cur, tmp) {
        HASH_DEL(marked, cur);
        free(cur->key);
        free(cur);
    }
    HASH_CLEAR(hh, marked);
    return find ? step : -1;
}
// https://leetcode.cn/submissions/detail/391405703/
```

```c
typedef char *Value;

typedef struct {
    Value *array;
    int capacity;
    int size;
    int first;
    int last;
} MyResizingArrayQueue;

MyResizingArrayQueue *myQueueCreate() {
    MyResizingArrayQueue *obj = malloc(sizeof(MyResizingArrayQueue));
    obj->first = 0;
    obj->last = 0;
    obj->size = 0;
    obj->capacity = 8;
    obj->array = malloc(sizeof(Value) * obj->capacity);
    return obj;
}

void myQueueResize(MyResizingArrayQueue *obj, int capacity) {
    Value *copy = malloc(sizeof(Value) * capacity);
    for (int i = 0; i < obj->size; ++i) {
        copy[i] = obj->array[(obj->first + i) % obj->capacity];
    }
    free(obj->array);
    obj->array = copy;
    obj->first = 0;
    obj->last = obj->size;
    obj->capacity = capacity;
}

void myQueuePush(MyResizingArrayQueue *obj, Value val) {
    if (obj->size == obj->capacity) {
        myQueueResize(obj, obj->capacity * 2);
    }
    obj->array[obj->last++] = val;
    if (obj->last == obj->capacity) {
        obj->last = 0;
    }
    obj->size++;
}

Value myQueuePop(MyResizingArrayQueue *obj) {
    Value val = obj->array[obj->first++];
    if (obj->first == obj->capacity) {
        obj->first = 0;
    }
    obj->size--;
    if (obj->size > 0 && obj->size == obj->capacity / 4) {
        myQueueResize(obj, obj->capacity / 2);
    }
    return val;
}

Value myQueuePeek(MyResizingArrayQueue *obj) {
    return obj->array[obj->first];
}

int myQueueSize(MyResizingArrayQueue *obj) {
    return obj->size;
}

bool myQueueEmpty(MyResizingArrayQueue *obj) {
    return obj->size == 0;
}

void myQueueFree(MyResizingArrayQueue *obj) {
    free(obj->array);
    free(obj);
}

typedef struct {
    char *key;
    UT_hash_handle hh;
} HashSetItem;

char *plusOne(char *s, int j) {
    char *copy = calloc(strlen(s) + 1, sizeof(char));
    strcpy(copy, s);
    if (copy[j] == '9') {
        copy[j] = '0';
    } else {
        copy[j] += 1;
    }
    return copy;
}

char *minusOne(char *s, int j) {
    char *copy = calloc(strlen(s) + 1, sizeof(char));
    strcpy(copy, s);
    if (copy[j] == '0') {
        copy[j] = '9';
    } else {
        copy[j] -= 1;
    }
    return copy;
}

int openLock(char **deadends, int deadendsSize, char *target) {
    HashSetItem *marked = NULL;
    HashSetItem *item;
    for (int i = 0; i < deadendsSize; ++i) {
        HASH_FIND_STR(marked, deadends[i], item);
        if (item == NULL) {
            item = malloc(sizeof(HashSetItem));
            item->key = deadends[i];
            HASH_ADD_STR(marked, key, item);
        }
    }
    MyResizingArrayQueue *queue = myQueueCreate();
    char *source = calloc(5, sizeof(char));
    strcpy(source, "0000");
    HASH_FIND_STR(marked, source, item);
    if (item == NULL) {
        item = malloc(sizeof(HashSetItem));
        item->key = source;
        HASH_ADD_STR(marked, key, item);
        myQueuePush(queue, source);
    }
    int step = 0;
    bool find = false;
    while (!myQueueEmpty(queue)) {
        int size = myQueueSize(queue);
        for (int i = 0; i < size; ++i) {
            char *s = myQueuePop(queue);
            if (strcmp(s, target) == 0) {
                find = true;
                break;
            }
            for (int j = 0; j < 4; ++j) {
                char *plus = plusOne(s, j);
                HASH_FIND_STR(marked, plus, item);
                if (item == NULL) {
                    item = malloc(sizeof(HashSetItem));
                    item->key = plus;
                    HASH_ADD_STR(marked, key, item);
                    myQueuePush(queue, plus);
                }
                char *minus = minusOne(s, j);
                HASH_FIND_STR(marked, minus, item);
                if (item == NULL) {
                    item = malloc(sizeof(HashSetItem));
                    item->key = minus;
                    HASH_ADD_STR(marked, key, item);
                    myQueuePush(queue, minus);
                }
            }
        }
        if (find) {
            break;
        }
        ++step;
    }
    myQueueFree(queue);
    HashSetItem *cur, *tmp;
    HASH_ITER(hh, marked, cur, tmp) {
        HASH_DEL(marked, cur);
        free(cur->key);
        free(cur);
    }
    HASH_CLEAR(hh, marked);
    return find ? step : -1;
}
// https://leetcode.cn/submissions/detail/391406185/
```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```c
bool *color;
bool *marked;
bool bipartite;

void dfs(int **graph, const int *graphColSize, int v) {
    marked[v] = true;
    for (int i = 0; i < graphColSize[v]; ++i) {
        int w = graph[v][i];
        if (!marked[w]) {
            color[w] = !color[v];
            dfs(graph, graphColSize, w);
        } else if (color[w] == color[v]) {
            bipartite = false;
            return;
        }
    }
}

bool isBipartite(int **graph, int graphSize, int *graphColSize) {
    bipartite = true;
    size_t n = sizeof(bool[graphSize]);
    color = malloc(n);
    memset(color, 0, n);
    marked = malloc(n);
    memset(marked, 0, n);
    for (int v = 0; v < graphSize; ++v) {
        if (!marked[v]) {
            dfs(graph, graphColSize, v);
            if (!bipartite) {
                break;
            }
        }
    }
    free(marked);
    free(color);
    return bipartite;
}
// https://leetcode.cn/submissions/detail/391278605/
```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```c
int *path;
int pathSize;

int **ans;
int ansSize;
int ansCapacity;
int *ansColSize;

void backtrack(int **graph, int graphSize, int *graphColSize, int v) {
    if (v == graphSize - 1) {
        size_t n = sizeof(int[pathSize]);
        int *res = malloc(n);
        memcpy(res, path, n);
        if (ansSize == ansCapacity) {
            ansCapacity *= 2;
            ans = realloc(ans, sizeof(int *) * ansCapacity);
            ansColSize = realloc(ansColSize, sizeof(int[ansCapacity]));
        }
        ans[ansSize] = res;
        ansColSize[ansSize++] = pathSize;
        return;
    }
    for (int col = 0; col < graphColSize[v]; ++col) {
        int w = graph[v][col];
        path[pathSize++] = w;
        backtrack(graph, graphSize, graphColSize, w);
        --pathSize;
    }
}

/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **allPathsSourceTarget(int **graph, int graphSize, int *graphColSize, int *returnSize, int **returnColumnSizes) {
    ansCapacity = 8;
    ans = malloc(sizeof(int *) * ansCapacity);
    ansColSize = malloc(sizeof(int[ansCapacity]));
    path = malloc(sizeof(int[graphSize]));
    pathSize = ansSize = 0;
    path[pathSize++] = 0;
    backtrack(graph, graphSize, graphColSize, 0);
    --pathSize;
    *returnSize = ansSize;
    *returnColumnSizes = ansColSize;
    free(path);
    return ans;
}
// https://leetcode.cn/submissions/detail/391340597/
```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```c
typedef struct {
    int key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

int cmp(const void *a, const void *b) {
    int arg1 = *(const int *) a;
    int arg2 = *(const int *) b;
    return arg1 - arg2;
}

bool isNStraightHand(int *hand, int handSize, int groupSize) {
    if (handSize % groupSize != 0) {
        return false;
    }
    qsort(hand, handSize, sizeof(int), cmp);
    HashMapItem *counter = NULL;
    for (int i = 0; i < handSize; ++i) {
        HashMapItem *item;
        HASH_FIND_INT(counter, &hand[i], item);
        if (item == NULL) {
            item = malloc(sizeof(HashMapItem));
            item->key = hand[i];
            item->val = 1;
            HASH_ADD_INT(counter, key, item);
        } else {
            item->val++;
        }
    }
    int ans = true;
    for (int i = 0; i < handSize; ++i) {
        HashMapItem *item;
        HASH_FIND_INT(counter, &hand[i], item);
        if (item->val > 0) {
            for (int g = 0; g < groupSize; ++g) {
                int need = hand[i] + g;
                HASH_FIND_INT(counter, &need, item);
                if (item == NULL || item->val == 0) {
                    ans = false;
                    break;
                }
                item->val--;
            }
            if (!ans) {
                break;
            }
        }
    }
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, counter, cur, tmp) {
        HASH_DEL(counter, cur);
        free(cur);
    }
    HASH_CLEAR(hh, counter);
    return ans;
}
// https://leetcode.cn/submissions/detail/391280261/
```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```c
// 当吃香蕉的速度为 k 时，是否能在 h 小时内吃完
bool canFinish(const int *piles, int pilesSize, int h, int k) {
    long hours = 0;
    for (int i = 0; i < pilesSize; ++i) {
        hours += (piles[i] - 1) / k + 1;
    }
    return hours <= h;
}

int minEatingSpeed(const int *piles, int pilesSize, int h) {
    int lo = 1, hi = 1;
    for (int i = 0; i < pilesSize; ++i) {
        hi = fmax(hi, piles[i]);
    }
    int ans = lo;
    while (lo <= hi) {
        int mid = lo + (hi - lo) / 2;
        if (canFinish(piles, pilesSize, h, mid)) {
            ans = mid;
            hi = mid - 1;
        } else {
            lo = mid + 1;
        }
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391140971/
```

## 876. 链表的中间结点

<https://leetcode-cn.com/problems/middle-of-the-linked-list/>

```c
struct ListNode *middleNode(struct ListNode *head) {
    struct ListNode *slow = head;
    struct ListNode *fast = head;
    while (fast != NULL && fast->next != NULL) {
        slow = slow->next;
        fast = fast->next->next;
    }
    return slow;
}
// https://leetcode.cn/submissions/detail/388495477/
```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```c
// TODO
```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```c
typedef struct {
    int key;
    int val;
    UT_hash_handle hh;
} HashMapItem;

HashMapItem *valueToIndex = NULL;

struct TreeNode *constructFromPrePostRange(const int *preorder, int preStart, int preEnd,
                                           const int *postorder, int postStart, int postEnd) {
    if (preStart > preEnd) {
        return NULL;
    }
    int rootVal = preorder[preStart];
    struct TreeNode *root = malloc(sizeof(struct TreeNode));
    root->val = rootVal;
    root->left = NULL;
    root->right = NULL;
    if (preStart < preEnd) {
        int leftRootVal = preorder[preStart + 1];
        HashMapItem *item;
        HASH_FIND_INT(valueToIndex, &leftRootVal, item);
        int postLeftRoot = item->val;
        int leftSize = postLeftRoot - postStart + 1;
        root->left = constructFromPrePostRange(preorder, preStart + 1, preStart + leftSize,
                                               postorder, postStart, postLeftRoot);
        root->right = constructFromPrePostRange(preorder, preStart + leftSize + 1, preEnd,
                                                postorder, postLeftRoot + 1, postEnd - 1);
    }
    return root;
}

struct TreeNode *constructFromPrePost(const int *preorder, int preorderSize, const int *postorder, int postorderSize) {
    for (int i = 0; i < postorderSize; ++i) {
        HashMapItem *item = malloc(sizeof(HashMapItem));
        item->key = postorder[i];
        item->val = i;
        HASH_ADD_INT(valueToIndex, key, item);
    }
    struct TreeNode *root = constructFromPrePostRange(preorder, 0, preorderSize - 1,
                                                      postorder, 0, postorderSize - 1);
    HashMapItem *cur, *tmp;
    HASH_ITER(hh, valueToIndex, cur, tmp) {
        HASH_DEL(valueToIndex, cur);
        free(cur);
    }
    HASH_CLEAR(hh, valueToIndex);
    return root;
}
// https://leetcode.cn/submissions/detail/391157224/
```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```c
void swap(int *a, int *b) {
    int t = *a;
    *a = *b;
    *b = t;
}

int *sortArrayByParity(int *nums, int numsSize, int *returnSize) {
    // nums[0..i]   Even
    // nums(i..j)   Scanning
    // nums[j..n-1] Odd
    int i = -1, j = numsSize;
    while (true) {
        while (nums[++i] % 2 == 0) {
            if (i == numsSize - 1) {
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
        swap(&nums[i], &nums[j]);
    }
    *returnSize = numsSize;
    return nums;
}
// https://leetcode.cn/submissions/detail/388244043/
```

```c
/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *sortArrayByParity(const int *nums, int numsSize, int *returnSize) {
    int *ans = (int *) malloc(sizeof(int) * numsSize);
    int left = 0, right = numsSize - 1;
    for (int i = 0; i < numsSize; ++i) {
        if (nums[i] % 2 == 0) {
            ans[left++] = nums[i];
        } else {
            ans[right--] = nums[i];
        }
    }
    *returnSize = numsSize;
    return ans;
}
// https://leetcode.cn/submissions/detail/388262248/
```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```c
void swap(int *a, int *b) {
    int t = *a;
    *a = *b;
    *b = t;
}

int partition(int *nums, int lo, int hi) {
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
        swap(&nums[i], &nums[j]);
    }
    swap(&nums[lo], &nums[j]);
    return j;
}

void sort(int *nums, int lo, int hi) {
    if (lo >= hi) {
        return;
    }
    int j = partition(nums, lo, hi);
    sort(nums, lo, j - 1);
    sort(nums, j + 1, hi);
}

void shuffle(int *array, size_t n) {
    if (n > 1) {
        size_t i;
        for (i = 0; i < n - 1; i++) {
            size_t j = i + rand() / (RAND_MAX / (n - i) + 1);
            int t = array[j];
            array[j] = array[i];
            array[i] = t;
        }
    }
}

/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *sortArray(int *nums, int numsSize, int *returnSize) {
    shuffle(nums, numsSize);
    sort(nums, 0, numsSize - 1);
    *returnSize = numsSize;
    return nums;
}
// https://leetcode.cn/submissions/detail/390818675/
```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```c
// 性质一 一个「合法」括号组合的左括号数量一定等于右括号数量
// 性质二 对于一个「合法」的括号字符串组合 p，必然对于
// 任何 0 <= i < len(p) 都有：子串 p[0..i] 中
// 左括号的数量都大于或等于右括号的数量
int minAddToMakeValid(char *s) {
    int insertLeft = 0; // 已插入左括号的数量
    int needRight = 0;  // 待插入右括号的数量
    size_t n = strlen(s);
    for (int i = 0; i < n; ++i) {
        char ch = s[i];
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
// https://leetcode.cn/submissions/detail/391413883/
```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```c
void swap(int *a, int *b) {
    int t = *a;
    *a = *b;
    *b = t;
}

int *sortArrayByParityII(int *nums, int numsSize, int *returnSize) {
    int i = 0, j = 1;
    while (true) {
        while (i <= numsSize - 2 && nums[i] % 2 == 0) {
            i += 2;
        }
        while (j <= numsSize - 1 && nums[j] % 2 == 1) {
            j += 2;
        }
        if (i > numsSize - 2 || j > numsSize - 1) {
            break;
        }
        swap(&nums[i], &nums[j]);
    }
    *returnSize = numsSize;
    return nums;
}
// https://leetcode.cn/submissions/detail/388245497/
```

```c
/**
 * Note: The returned array must be malloced, assume caller calls free().
 */
int *sortArrayByParityII(const int *nums, int numsSize, int *returnSize) {
    int *ans = (int *) malloc(sizeof(int) * numsSize);
    int left = 0, right = 1;
    for (int i = 0; i < numsSize; ++i) {
        if (nums[i] % 2 == 0) {
            ans[left] = nums[i];
            left += 2;
        } else {
            ans[right] = nums[i];
            right += 2;
        }
    }
    *returnSize = numsSize;
    return ans;
}
// https://leetcode.cn/submissions/detail/388261972/
```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```c
// 从 matrix[0][0..n-1] 到 matrix[row][col] 的最小下降路径和
int minFallingPathSumMemo(int **matrix, int matrixColSize, int row, int col, int *memo) {
    if (col < 0 || col >= matrixColSize) {
        return INT_MAX;
    }
    if (row == 0) {
        return matrix[row][col];
    }
    int *p = memo + row * matrixColSize + col;
    if (*p == INT_MIN) {
        int sp1 = minFallingPathSumMemo(matrix, matrixColSize, row - 1, col - 1, memo);
        int sp2 = minFallingPathSumMemo(matrix, matrixColSize, row - 1, col, memo);
        int sp3 = minFallingPathSumMemo(matrix, matrixColSize, row - 1, col + 1, memo);
        *p = fmin(fmin(sp1, sp2), sp3) + matrix[row][col];
    }
    return *p;
}

int minFallingPathSum(int **matrix, int matrixSize, const int *matrixColSize) {
    int memo[matrixSize][*matrixColSize];
    for (int i = 0; i < matrixSize; ++i) {
        for (int j = 0; j < *matrixColSize; ++j) {
            memo[i][j] = INT_MIN;
        }
    }
    int ans = INT_MAX;
    for (int col = 0; col < *matrixColSize; ++col) {
        ans = fmin(ans, minFallingPathSumMemo(matrix, *matrixColSize, matrixSize - 1, col, memo[0]));
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391222636/
```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```c
/**
 * Return an array of arrays of size *returnSize.
 * The sizes of the arrays are returned as *returnColumnSizes array.
 * Note: Both returned array and *columnSizes array must be malloced, assume caller calls free().
 */
int **
intervalIntersection(int **firstList, int firstListSize, int *firstListColSize, int **secondList, int secondListSize,
                     int *secondListColSize, int *returnSize, int **returnColumnSizes) {
    int n = firstListSize + secondListSize;
    int **ans = malloc(sizeof(int *) * n);
    *returnColumnSizes = malloc(sizeof(int *) * n);
    *returnSize = 0;
    int i = 0, j = 0;
    while (i < firstListSize && j < secondListSize) {
        int start1 = firstList[i][0], end1 = firstList[i][1];
        int start2 = secondList[j][0], end2 = secondList[j][1];
        if (end1 < start2) { // 不相交
            ++i;
        } else if (end2 < start1) { // 不相交
            ++j;
        } else { // 相交
            int *t = malloc(sizeof(int[2]));
            t[0] = fmax(start1, start2);
            t[1] = fmin(end1, end2);
            ans[*returnSize] = t;
            (*returnColumnSizes)[(*returnSize)++] = 2;
            if (end1 < end2) {
                ++i;
            } else {
                ++j;
            }
        }
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/391303654/
```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```c
typedef struct {
    int *parent;
    int *rank;
    int size;
} UF;

UF *UFCreate(int n) {
    UF *obj = malloc(sizeof(UF));
    obj->parent = malloc(sizeof(int[n]));
    obj->rank = malloc(sizeof(int[n]));
    obj->size = n;
    for (int i = 0; i < n; ++i) {
        obj->parent[i] = i;
        obj->rank[i] = 0;
    }
    return obj;
}

int UFFind(UF *obj, int p) {
    int *parent = obj->parent;
    while (p != parent[p]) {
        parent[p] = parent[parent[p]];
        p = parent[p];
    }
    return p;
}

void UFUnion(UF *obj, int p, int q) {
    int rootP = UFFind(obj, p);
    int rootQ = UFFind(obj, q);
    int *parent = obj->parent;
    int *rank = obj->rank;
    if (rootP != rootQ) {
        if (rank[rootP] < rank[rootQ]) {
            parent[rootP] = rootQ;
        } else if (rank[rootQ] < rank[rootP]) {
            parent[rootQ] = rootP;
        } else {
            parent[rootP] = rootQ;
            ++rank[rootQ];
        }
        obj->size--;
    }
}

bool UFConnected(UF *obj, int p, int q) {
    return UFFind(obj, p) == UFFind(obj, q);
}

int UFSize(UF *obj) {
    return obj->size;
}

void UFFree(UF *obj) {
    free(obj->parent);
    free(obj->rank);
    free(obj);
}

bool equationsPossible(char **equations, int equationsSize) {
    UF *uf = UFCreate(26);
    for (int i = 0; i < equationsSize; ++i) {
        char *s = equations[i];
        if (s[1] == '=') {
            int p = s[0] - 'a';
            int q = s[3] - 'a';
            UFUnion(uf, p, q);
        }
    }
    bool ans = true;
    for (int i = 0; i < equationsSize; ++i) {
        char *s = equations[i];
        if (s[1] == '!') {
            int p = s[0] - 'a';
            int q = s[3] - 'a';
            if (UFConnected(uf, p, q)) {
                ans = false;
                break;
            }
        }
    }
    UFFree(uf);
    return ans;
}
// https://leetcode.cn/submissions/detail/391074243/
```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```c
// 当船的运载能力为 capacity 时，是否能在 days 天内送完
bool canFinish(const int *weights, int weightsSize, int days, int capacity) {
    int i = 0, minDays = 0;
    while (i < weightsSize) {
        int sum = 0;
        while (i < weightsSize && sum + weights[i] <= capacity) {
            sum += weights[i++];
        }
        ++minDays;
    }
    return minDays <= days;
}

int shipWithinDays(const int *weights, int weightsSize, int days) {
    int lo = 0, hi = 0;
    for (int i = 0; i < weightsSize; ++i) {
        int w = weights[i];
        lo = fmax(lo, w);
        hi += w;
    }
    int ans = lo;
    while (lo <= hi) {
        int mid = lo + (hi - lo) / 2;
        if (canFinish(weights, weightsSize, days, mid)) {
            ans = mid;
            hi = mid - 1;
        } else {
            lo = mid + 1;
        }
    }
    return ans;
}
// https://leetcode.cn/submissions/detail/388266451/
```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```c
static const int LAND = 1;
static const int WATER = 0;

void floodFill(int **grid, int gridSize, int *gridColSize, int row, int col) {
    if (row < 0 || row >= gridSize || col < 0 || col >= *gridColSize || grid[row][col] == WATER) {
        return;
    }
    grid[row][col] = WATER;
    floodFill(grid, gridSize, gridColSize, row, col + 1);
    floodFill(grid, gridSize, gridColSize, row, col - 1);
    floodFill(grid, gridSize, gridColSize, row + 1, col);
    floodFill(grid, gridSize, gridColSize, row - 1, col);
}

int numEnclaves(int **grid, int gridSize, int *gridColSize) {
    int m = gridSize, n = *gridColSize;
    // 淹没与左右边界的陆地相连的岛屿
    for (int row = 0; row < m; ++row) {
        floodFill(grid, gridSize, gridColSize, row, 0);
        floodFill(grid, gridSize, gridColSize, row, n - 1);
    }
    // 淹没与上下边界的陆地相连的岛屿
    for (int col = 0; col < n; ++col) {
        floodFill(grid, gridSize, gridColSize, 0, col);
        floodFill(grid, gridSize, gridColSize, m - 1, col);
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
// https://leetcode.cn/submissions/detail/391255848/
```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```c
int cmp(const void *a, const void *b) {
    const int *arg1 = *(const int **) a;
    const int *arg2 = *(const int **) b;
    if (arg1[0] == arg2[0]) {
        return arg2[1] - arg1[1];
    }
    return arg1[0] - arg2[0];
}

int videoStitching(int **clips, int clipsSize, int *clipsColSize, int time) {
    qsort(clips, clipsSize, sizeof(int *), cmp);
    int maxEnd = 0;
    int count = 0;
    int i = 0, n = clipsSize;
    // 当 clips[i] 与 [0, maxEnd] 重叠（相交或被覆盖）时
    while (i < n && clips[i][0] <= maxEnd) {
        // 记录与 [0, maxEnd] 重叠的所有区间中最大的 end
        int nextEnd = clips[i][1];
        while (++i < n && clips[i][0] <= maxEnd) {
            nextEnd = fmax(nextEnd, clips[i][1]);
        }
        maxEnd = nextEnd;
        ++count;
        if (maxEnd >= time) {
            return count;
        }
    }
    return -1;
}
// https://leetcode.cn/submissions/detail/390604436/
```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```c
int longestCommonSubsequence(char *text1, char *text2) {
    size_t n1 = strlen(text1);
    size_t n2 = strlen(text2);
    // text1[0..i-1] = text1 的长度为 i 的前缀
    // text2[0..j-1] = text2 的长度为 j 的前缀
    // dp[i][j] = LCS(text1[0..i-1], text2[0..j-1]) 的长度
    int dp[n1 + 1][n2 + 1];
    memset(dp, 0, sizeof(dp));
    for (int i = 1; i <= n1; ++i) {
        for (int j = 1; j <= n2; ++j) {
            // text1[i-1] = text2[j-1]
            if (text1[i - 1] == text2[j - 1]) {
                dp[i][j] = dp[i - 1][j - 1] + 1;
            } else {
                dp[i][j] = fmax(dp[i][j - 1], dp[i - 1][j]);
            }
        }
    }
    return dp[n1][n2];
}
// https://leetcode.cn/submissions/detail/391412143/
```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```c
static const int LAND = 0;
static const int WATER = 1;

void floodFill(int **grid, int gridSize, int *gridColSize, int row, int col) {
    if (row < 0 || row >= gridSize || col < 0 || col >= *gridColSize || grid[row][col] == WATER) {
        return;
    }
    grid[row][col] = WATER;
    floodFill(grid, gridSize, gridColSize, row, col + 1);
    floodFill(grid, gridSize, gridColSize, row, col - 1);
    floodFill(grid, gridSize, gridColSize, row + 1, col);
    floodFill(grid, gridSize, gridColSize, row - 1, col);
}

int closedIsland(int **grid, int gridSize, int *gridColSize) {
    int m = gridSize, n = *gridColSize;
    // 淹没与左右边界的陆地相连的岛屿
    for (int row = 0; row < m; ++row) {
        floodFill(grid, gridSize, gridColSize, row, 0);
        floodFill(grid, gridSize, gridColSize, row, n - 1);
    }
    // 淹没与上下边界的陆地相连的岛屿
    for (int col = 0; col < n; ++col) {
        floodFill(grid, gridSize, gridColSize, 0, col);
        floodFill(grid, gridSize, gridColSize, m - 1, col);
    }
    int count = 0;
    for (int row = 0; row < m; ++row) {
        for (int col = 0; col < n; ++col) {
            if (grid[row][col] == LAND) {
                floodFill(grid, gridSize, gridColSize, row, col);
                ++count;
            }
        }
    }
    return count;
}
// https://leetcode.cn/submissions/detail/391255426/
```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```c
int cmp(const void *a, const void *b) {
    const int *arg1 = *(const int **) a;
    const int *arg2 = *(const int **) b;
    if (arg1[0] == arg2[0]) {
        return arg2[1] - arg1[1];
    }
    return arg1[0] - arg2[0];
}

int removeCoveredIntervals(int **intervals, int intervalsSize, int *intervalsColSize) {
    qsort(intervals, intervalsSize, sizeof(int *), cmp);
    int count = intervalsSize;
    int maxEnd = 0;
    for (int i = 0; i < intervalsSize; ++i) {
        int end = intervals[i][1];
        if (end <= maxEnd) {
            --count;
        } else {
            maxEnd = end;
        }
    }
    return count;
}
// https://leetcode.cn/submissions/detail/390603537/
```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```c
int *inorder;
int inorderSize;
int inorderCapacity;

// 深度优先搜索，获取中序遍历结果
void dfs(struct TreeNode *root) {
    if (root == NULL) {
        return;
    }
    dfs(root->left);
    if (inorderSize == inorderCapacity) {
        inorderCapacity *= 2;
        inorder = realloc(inorder, sizeof(int[inorderCapacity]));
    }
    inorder[inorderSize++] = root->val;
    dfs(root->right);
}

// 将有序数组 nums[lo..hi] 转换为二叉搜索树
struct TreeNode *sortedArrayToBSTRange(const int *nums, int lo, int hi) {
    if (lo > hi) {
        return NULL;
    }
    int mid = lo + (hi - lo) / 2;
    struct TreeNode *root = malloc(sizeof(struct TreeNode));
    root->val = nums[mid];
    root->left = sortedArrayToBSTRange(nums, lo, mid - 1);
    root->right = sortedArrayToBSTRange(nums, mid + 1, hi);
    return root;
}

struct TreeNode *sortedArrayToBST(const int *nums, int numsSize) {
    return sortedArrayToBSTRange(nums, 0, numsSize - 1);
}

struct TreeNode *balanceBST(struct TreeNode *root) {
    inorderSize = 0;
    inorderCapacity = 8;
    inorder = malloc(sizeof(int[inorderCapacity]));
    dfs(root);
    root = sortedArrayToBST(inorder, inorderSize);
    free(inorder);
    return root;
}
// https://leetcode.cn/submissions/detail/391160726/
```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```c
// TODO
```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```c
int minInsertions(char *s) {
    int insertLeft = 0;  // 已插入左括号的数量
    int insertRight = 0; // 已插入右括号的数量
    int needRight = 0;   // 待插入右括号的数量
    size_t n = strlen(s);
    for (int i = 0; i < n; ++i) {
        char ch = s[i];
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
// https://leetcode.cn/submissions/detail/391412447/
```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```c
// TODO
```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```c
// TODO
```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```c
static const int LAND = 1;
static const int WATER = 0;

void floodFill(int **grid, int gridSize, int *gridColSize, int row, int col) {
    if (row < 0 || row >= gridSize || col < 0 || col >= *gridColSize || grid[row][col] == WATER) {
        return;
    }
    grid[row][col] = WATER;
    floodFill(grid, gridSize, gridColSize, row, col + 1);
    floodFill(grid, gridSize, gridColSize, row, col - 1);
    floodFill(grid, gridSize, gridColSize, row + 1, col);
    floodFill(grid, gridSize, gridColSize, row - 1, col);
}

int countSubIslands(int **grid1, int grid1Size, int *grid1ColSize, int **grid2, int grid2Size, int *grid2ColSize) {
    int m = grid2Size, n = *grid2ColSize;
    for (int row = 0; row < m; ++row) {
        for (int col = 0; col < n; ++col) {
            // 淹没『非子岛屿』
            if (grid2[row][col] == LAND && grid1[row][col] == WATER) {
                floodFill(grid2, grid2Size, grid2ColSize, row, col);
            }
        }
    }
    int count = 0;
    for (int row = 0; row < m; ++row) {
        for (int col = 0; col < n; ++col) {
            if (grid2[row][col] == LAND) {
                floodFill(grid2, grid2Size, grid2ColSize, row, col);
                ++count;
            }
        }
    }
    return count;
}
// https://leetcode.cn/submissions/detail/391256238/
```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode-cn.com/problems/kth-node-from-end-of-list-lcci/>

```c
int kthToLast(struct ListNode *head, int k) {
    struct ListNode *slow = head;
    struct ListNode *fast = head;
    for (int i = 1; i <= k; ++i) {
        fast = fast->next;
    }
    while (fast != NULL) {
        slow = slow->next;
        fast = fast->next;
    }
    return slow->val;
}
// https://leetcode.cn/submissions/detail/388495817/
```
