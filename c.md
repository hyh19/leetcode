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
struct ListNode *addTwoNumbers(struct ListNode *l1, struct ListNode *l2) {
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
// https://leetcode.cn/submissions/detail/391145173/
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
            while (left <= right) {
                int del = s[left++];
                HASH_FIND_INT(window, &del, item);
                HASH_DEL(window, item);
                if (add == del) {
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
// https://leetcode.cn/submissions/detail/391410268/
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

```

## 34. 在排序数组中查找元素的第一个和最后一个位置

<https://leetcode.cn/problems/find-first-and-last-position-of-element-in-sorted-array/>

```c

```

## 37. 解数独

<https://leetcode.cn/problems/sudoku-solver/>

```c

```

## 39. 组合总和

<https://leetcode.cn/problems/combination-sum/>

```c

```

## 40. 组合总和 II

<https://leetcode.cn/problems/combination-sum-ii/>

```c

```

## 42. 接雨水

<https://leetcode.cn/problems/trapping-rain-water/>

```c

```

## 46. 全排列

<https://leetcode.cn/problems/permutations/>

```c

```

## 47. 全排列 II

<https://leetcode.cn/problems/permutations-ii/>

```c

```

## 51. N 皇后

<https://leetcode.cn/problems/n-queens/>

```c

```

## 52. N 皇后 II

<https://leetcode.cn/problems/n-queens-ii/>

```c

```

## 53. 最大子数组和

<https://leetcode.cn/problems/maximum-subarray/>

```c

```

## 56. 合并区间

<https://leetcode.cn/problems/merge-intervals/>

```c

```

## 64. 最小路径和

<https://leetcode.cn/problems/minimum-path-sum/>

```c

```

## 69. x 的平方根

<https://leetcode.cn/problems/sqrtx/>

```c

```

## 70. 爬楼梯

<https://leetcode.cn/problems/climbing-stairs/>

```c

```

## 72. 编辑距离

<https://leetcode.cn/problems/edit-distance/>

```c

```

## 75. 颜色分类

<https://leetcode.cn/problems/sort-colors/>

```c

```

## 76. 最小覆盖子串

<https://leetcode.cn/problems/minimum-window-substring/>

```c

```

## 77. 组合

<https://leetcode.cn/problems/combinations/>

```c

```

## 78. 子集

<https://leetcode.cn/problems/subsets/>

```c

```

## 81. 搜索旋转排序数组 II

<https://leetcode.cn/problems/search-in-rotated-sorted-array-ii/>

```c

```

## 83. 删除排序链表中的重复元素

<https://leetcode.cn/problems/remove-duplicates-from-sorted-list/>

```c

```

## 86. 分隔链表

<https://leetcode.cn/problems/partition-list/>

```c

```

## 90. 子集 II

<https://leetcode.cn/problems/subsets-ii/>

```c

```

## 92. 反转链表 II

<https://leetcode-cn.com/problems/reverse-linked-list-ii/>

```c

```

## 94. 二叉树的中序遍历

<https://leetcode.cn/problems/binary-tree-inorder-traversal/>

```c

```

## 95. 不同的二叉搜索树 II

<https://leetcode.cn/problems/unique-binary-search-trees-ii/>

```c

```

## 96. 不同的二叉搜索树

<https://leetcode.cn/problems/unique-binary-search-trees/>

```c

```

## 98. 验证二叉搜索树

<https://leetcode.cn/problems/validate-binary-search-tree/>

```c

```

## 100. 相同的树

<https://leetcode.cn/problems/same-tree/>

```c

```

## 102. 二叉树的层序遍历

<https://leetcode.cn/problems/binary-tree-level-order-traversal/>

```c

```

## 103. 二叉树的锯齿形层序遍历

<https://leetcode-cn.com/problems/binary-tree-zigzag-level-order-traversal/>

```c

```

## 104. 二叉树的最大深度

<https://leetcode.cn/problems/maximum-depth-of-binary-tree/>

```c

```

## 105. 从前序与中序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-inorder-traversal/>

```c

```

## 106. 从中序与后序遍历序列构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-inorder-and-postorder-traversal/>

```c

```

## 107. 二叉树的层序遍历 II

<https://leetcode-cn.com/problems/binary-tree-level-order-traversal-ii/>

```c

```

## 108. 将有序数组转换为二叉搜索树

<https://leetcode.cn/problems/convert-sorted-array-to-binary-search-tree/>

```c

```

## 110. 平衡二叉树

<https://leetcode.cn/problems/balanced-binary-tree/>

```c

```

## 111. 二叉树的最小深度

<https://leetcode.cn/problems/minimum-depth-of-binary-tree/>

```c

```

## 112. 路径总和

<https://leetcode.cn/problems/path-sum/>

```c

```

## 114. 二叉树展开为链表

<https://leetcode.cn/problems/flatten-binary-tree-to-linked-list/>

```c

```

## 116. 填充每个节点的下一个右侧节点指针

<https://leetcode.cn/problems/populating-next-right-pointers-in-each-node/>

```c

```

## 121. 买卖股票的最佳时机

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock/>

```c

```

## 122. 买卖股票的最佳时机 II

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-ii/>

```c

```

## 123. 买卖股票的最佳时机 III

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iii/>

```c

```

## 125. 验证回文串

<https://leetcode.cn/problems/valid-palindrome/>

```c

```

## 128. 最长连续序列

<https://leetcode.cn/problems/longest-consecutive-sequence/>

```c

```

## 130. 被围绕的区域

<https://leetcode.cn/problems/surrounded-regions/>

```c

```

## 136. 只出现一次的数字

<https://leetcode.cn/problems/single-number/>

```c

```

## 141. 环形链表

<https://leetcode-cn.com/problems/linked-list-cycle/>

```c

```

## 142. 环形链表 II

<https://leetcode-cn.com/problems/linked-list-cycle-ii/>

```c

```

## 143. 重排链表

<https://leetcode.cn/problems/reorder-list/>

```c

```

## 144. 二叉树的前序遍历

<https://leetcode.cn/problems/binary-tree-preorder-traversal/>

```c

```

## 145. 二叉树的后序遍历

<https://leetcode.cn/problems/binary-tree-postorder-traversal/>

```c

```

## 146. LRU 缓存

<https://leetcode.cn/problems/lru-cache/>

```c

```

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

```c

```

## 155. 最小栈

<https://leetcode.cn/problems/min-stack/>

```c

```

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

```c

```

## 165. 比较版本号

<https://leetcode.cn/problems/compare-version-numbers/>

```c

```

## 167. 两数之和 II - 输入有序数组

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

```c

```

## 169. 多数元素

<https://leetcode.cn/problems/majority-element/>

```c

```

## 179. 最大数

<https://leetcode.cn/problems/largest-number/>

```c

```

## 188. 买卖股票的最佳时机 IV

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

```c

```

## 189. 轮转数组

<https://leetcode.cn/problems/rotate-array/>

```c

```

## 198. 打家劫舍

<https://leetcode.cn/problems/house-robber/>

```c

```

## 199. 二叉树的右视图

<https://leetcode.cn/problems/binary-tree-right-side-view/>

```c

```

## 200. 岛屿数量

<https://leetcode.cn/problems/number-of-islands/>

```c

```

## 203. 移除链表元素

<https://leetcode-cn.com/problems/remove-linked-list-elements/>

```c

```

## 206. 反转链表

<https://leetcode-cn.com/problems/reverse-linked-list/>

```c

```

## 207. 课程表

<https://leetcode.cn/problems/course-schedule/>

```c

```

## 210. 课程表 II

<https://leetcode.cn/problems/course-schedule-ii/>

```c

```

## 213. 打家劫舍 II

<https://leetcode.cn/problems/house-robber-ii/>

```c

```

## 215. 数组中的第 K 个最大元素

<https://leetcode.cn/problems/kth-largest-element-in-an-array/>

```c

```

## 216. 组合总和 III

<https://leetcode.cn/problems/combination-sum-iii/>

```c

```

## 222. 完全二叉树的节点个数

<https://leetcode.cn/problems/count-complete-tree-nodes/>

```c

```

## 225. 用队列实现栈

<https://leetcode.cn/problems/implement-stack-using-queues/>

```c

```

## 226. 翻转二叉树

<https://leetcode.cn/problems/invert-binary-tree/>

```c

```

## 230. 二叉搜索树中第 K 小的元素

<https://leetcode.cn/problems/kth-smallest-element-in-a-bst/>

```c

```

## 232. 用栈实现队列

<https://leetcode.cn/problems/implement-queue-using-stacks/>

```c

```

## 234. 回文链表

<https://leetcode.cn/problems/palindrome-linked-list/>

```c

```

## 235. 二叉搜索树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-search-tree/>

```c

```

## 236. 二叉树的最近公共祖先

<https://leetcode.cn/problems/lowest-common-ancestor-of-a-binary-tree/>

```c

```

## 237. 删除链表中的节点

<https://leetcode-cn.com/problems/delete-node-in-a-linked-list/>

```c

```

## 239. 滑动窗口最大值

<https://leetcode.cn/problems/sliding-window-maximum/>

```c

```

## 253. 会议室 II

<https://leetcode.cn/problems/meeting-rooms-ii/>

```c

```

## 283. 移动零

<https://leetcode-cn.com/problems/move-zeroes/>

```c

```

## 297. 二叉树的序列化与反序列化

<https://leetcode.cn/problems/serialize-and-deserialize-binary-tree/>

```c

```

## 300. 最长递增子序列

<https://leetcode.cn/problems/longest-increasing-subsequence/>

```c

```

## 303. 区域和检索 - 数组不可变

<https://leetcode.cn/problems/range-sum-query-immutable/>

```c

```

## 309. 最佳买卖股票时机含冷冻期

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-cooldown/>

```c

```

## 315. 计算右侧小于当前元素的个数

<https://leetcode.cn/problems/count-of-smaller-numbers-after-self/>

```c

```

## 322. 零钱兑换

<https://leetcode.cn/problems/coin-change/>

```c

```

## 337. 打家劫舍 III

<https://leetcode.cn/problems/house-robber-iii/>

```c

```

## 344. 反转字符串

<https://leetcode.cn/problems/reverse-string/>

```c

```

## 354. 俄罗斯套娃信封问题

<https://leetcode.cn/problems/russian-doll-envelopes/>

```c

```

## 394. 字符串解码

<https://leetcode.cn/problems/decode-string/>

```c

```

## 416. 分割等和子集

<https://leetcode.cn/problems/partition-equal-subset-sum/>

```c

```

## 435. 无重叠区间

<https://leetcode.cn/problems/non-overlapping-intervals/>

```c

```

## 438. 找到字符串中所有字母异位词

<https://leetcode.cn/problems/find-all-anagrams-in-a-string/>

```c

```

## 445. 两数相加 II

<https://leetcode.cn/problems/add-two-numbers-ii/>

```c

```

## 450. 删除二叉搜索树中的节点

<https://leetcode.cn/problems/delete-node-in-a-bst/>

```c

```

## 452. 用最少数量的箭引爆气球

<https://leetcode.cn/problems/minimum-number-of-arrows-to-burst-balloons/>

```c

```

## 460. LFU 缓存

<https://leetcode.cn/problems/lfu-cache/>

```c

```

## 493. 翻转对

<https://leetcode.cn/problems/reverse-pairs/>

```c

```

## 494. 目标和

<https://leetcode.cn/problems/target-sum/>

```c

```

## 496. 下一个更大元素 I

<https://leetcode.cn/problems/next-greater-element-i/>

```c

```

## 503. 下一个更大元素 II

<https://leetcode.cn/problems/next-greater-element-ii/>

```c

```

## 509. 斐波那契数

<https://leetcode.cn/problems/fibonacci-number/>

```c

```

## 516. 最长回文子序列

<https://leetcode.cn/problems/longest-palindromic-subsequence/>

```c

```

## 518. 零钱兑换 II

<https://leetcode.cn/problems/coin-change-2/>

```c

```

## 538. 把二叉搜索树转换为累加树

<https://leetcode.cn/problems/convert-bst-to-greater-tree/>

```c

```

## 543. 二叉树的直径

<https://leetcode.cn/problems/diameter-of-binary-tree/>

```c

```

## 567. 字符串的排列

<https://leetcode.cn/problems/permutation-in-string/>

```c

```

## 583. 两个字符串的删除操作

<https://leetcode.cn/problems/delete-operation-for-two-strings/>

```c

```

## 617. 合并二叉树

<https://leetcode.cn/problems/merge-two-binary-trees/>

```c

```

## 652. 寻找重复的子树

<https://leetcode.cn/problems/find-duplicate-subtrees/>

```c

```

## 654. 最大二叉树

<https://leetcode.cn/problems/maximum-binary-tree/>

```c

```

## 695. 岛屿的最大面积

<https://leetcode.cn/problems/max-area-of-island/>

```c

```

## 698. 划分为 K 个相等的子集

<https://leetcode.cn/problems/partition-to-k-equal-sum-subsets/>

```c

```

## 700. 二叉搜索树中的搜索

<https://leetcode.cn/problems/search-in-a-binary-search-tree/>

```c

```

## 701. 二叉搜索树中的插入操作

<https://leetcode.cn/problems/insert-into-a-binary-search-tree/>

```c

```

## 704. 二分查找

<https://leetcode.cn/problems/binary-search/>

```c

```

## 712. 两个字符串的最小 ASCII 删除和

<https://leetcode.cn/problems/minimum-ascii-delete-sum-for-two-strings/>

```c

```

## 714. 买卖股票的最佳时机含手续费

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-with-transaction-fee/>

```c

```

## 739. 每日温度

<https://leetcode.cn/problems/daily-temperatures/>

```c

```

## 743. 网络延迟时间

<https://leetcode.cn/problems/network-delay-time/>

```c

```

## 752. 打开转盘锁

<https://leetcode.cn/problems/open-the-lock/>

```c

```

## 785. 判断二分图

<https://leetcode.cn/problems/is-graph-bipartite/>

```c

```

## 797. 所有可能的路径

<https://leetcode.cn/problems/all-paths-from-source-to-target/>

```c

```

## 846. 一手顺子

<https://leetcode.cn/problems/hand-of-straights/>

```c

```

## 875. 爱吃香蕉的珂珂

<https://leetcode.cn/problems/koko-eating-bananas/>

```c

```

## 876. 链表的中间结点

<https://leetcode-cn.com/problems/middle-of-the-linked-list/>

```c

```

## 886. 可能的二分法

<https://leetcode.cn/problems/possible-bipartition/>

```c

```

## 889. 根据前序和后序遍历构造二叉树

<https://leetcode.cn/problems/construct-binary-tree-from-preorder-and-postorder-traversal/>

```c

```

## 905. 按奇偶排序数组

<https://leetcode.cn/problems/sort-array-by-parity/>

```c

```

## 912. 排序数组

<https://leetcode.cn/problems/sort-an-array/>

```c

```

## 921. 使括号有效的最少添加

<https://leetcode.cn/problems/minimum-add-to-make-parentheses-valid/>

```c

```

## 922. 按奇偶排序数组 II

<https://leetcode.cn/problems/sort-array-by-parity-ii/>

```c

```

## 931. 下降路径最小和

<https://leetcode.cn/problems/minimum-falling-path-sum/>

```c

```

## 986. 区间列表的交集

<https://leetcode.cn/problems/interval-list-intersections/>

```c

```

## 990. 等式方程的可满足性

<https://leetcode.cn/problems/satisfiability-of-equality-equations/>

```c

```

## 1011. 在 D 天内送达包裹的能力

<https://leetcode.cn/problems/capacity-to-ship-packages-within-d-days/>

```c

```

## 1020. 飞地的数量

<https://leetcode.cn/problems/number-of-enclaves/>

```c

```

## 1024. 视频拼接

<https://leetcode.cn/problems/video-stitching/>

```c

```

## 1143. 最长公共子序列

<https://leetcode.cn/problems/longest-common-subsequence/>

```c

```

## 1254. 统计封闭岛屿的数目

<https://leetcode.cn/problems/number-of-closed-islands/>

```c

```

## 1288. 删除被覆盖区间

<https://leetcode.cn/problems/remove-covered-intervals/>

```c

```

## 1382. 将二叉搜索树变平衡

<https://leetcode.cn/problems/balance-a-binary-search-tree/>

```c

```

## 1514. 概率最大的路径

<https://leetcode.cn/problems/path-with-maximum-probability/>

```c

```

## 1541. 平衡括号字符串的最少插入次数

<https://leetcode.cn/problems/minimum-insertions-to-balance-a-parentheses-string/>

```c

```

## 1584. 连接所有点的最小费用

<https://leetcode.cn/problems/min-cost-to-connect-all-points/>

```c

```

## 1631. 最小体力消耗路径

<https://leetcode.cn/problems/path-with-minimum-effort/>

```c

```

## 1905. 统计子岛屿

<https://leetcode.cn/problems/count-sub-islands/>

```c

```

## CtCI 02.02. 返回倒数第 K 个节点

<https://leetcode-cn.com/problems/kth-node-from-end-of-list-lcci/>

```c

```
