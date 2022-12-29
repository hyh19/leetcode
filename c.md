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

## 1. 两数之和

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

## 7. 整数反转

## 11. 盛最多水的容器

## 14. 最长公共前缀

## 15. 三数之和

## 18. 四数之和

## 19. 删除链表的倒数第 N 个结点

## 20. 有效的括号

## 21. 合并两个有序链表

## 22. 括号生成

## 23. 合并 K 个升序链表

## 24. 两两交换链表中的节点

## 25. K 个一组翻转链表

## 26. 删除有序数组中的重复项

## 27. 移除元素

## 28. 实现 strStr()

## 33. 搜索旋转排序数组

## 34. 在排序数组中查找元素的第一个和最后一个位置

## 37. 解数独

## 39. 组合总和

## 40. 组合总和 II

## 42. 接雨水

## 46. 全排列

## 47. 全排列 II

## 51. N 皇后

## 52. N 皇后 II

## 53. 最大子数组和

## 56. 合并区间

## 64. 最小路径和

## 69. x 的平方根

## 70. 爬楼梯

## 72. 编辑距离

## 75. 颜色分类

## 76. 最小覆盖子串

## 77. 组合

## 78. 子集

## 81. 搜索旋转排序数组 II

## 83. 删除排序链表中的重复元素

## 86. 分隔链表

## 90. 子集 II

## 92. 反转链表 II

## 94. 二叉树的中序遍历

## 95. 不同的二叉搜索树 II

## 96. 不同的二叉搜索树

## 98. 验证二叉搜索树

## 100. 相同的树

## 102. 二叉树的层序遍历

## 103. 二叉树的锯齿形层序遍历

## 104. 二叉树的最大深度

## 105. 从前序与中序遍历序列构造二叉树

## 106. 从中序与后序遍历序列构造二叉树

## 107. 二叉树的层序遍历 II

## 108. 将有序数组转换为二叉搜索树

## 110. 平衡二叉树

## 111. 二叉树的最小深度

## 112. 路径总和

## 114. 二叉树展开为链表

## 116. 填充每个节点的下一个右侧节点指针

## 121. 买卖股票的最佳时机

## 122. 买卖股票的最佳时机 II

## 123. 买卖股票的最佳时机 III

## 125. 验证回文串

## 128. 最长连续序列

## 130. 被围绕的区域

## 136. 只出现一次的数字

## 141. 环形链表

## 142. 环形链表 II

## 143. 重排链表

## 144. 二叉树的前序遍历

## 145. 二叉树的后序遍历

## 146. LRU 缓存

## 153. 寻找旋转排序数组中的最小值

<https://leetcode.cn/problems/find-minimum-in-rotated-sorted-array/>

## 155. 最小栈

## 160. 相交链表

<https://leetcode-cn.com/problems/intersection-of-two-linked-lists/>

## 165. 比较版本号

> String

<https://leetcode.cn/problems/compare-version-numbers/>

## 167. 两数之和 II - 输入有序数组

> Array, TwoPointers

<https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/>

## 169. 多数元素

> Array, HashTable, Sorting

<https://leetcode.cn/problems/majority-element/>


## 179. 最大数

> String, Sorting

<https://leetcode.cn/problems/largest-number/>

## 188. 买卖股票的最佳时机 IV

> 2DArray, DP, Stock

<https://leetcode.cn/problems/best-time-to-buy-and-sell-stock-iv/>

## 189. 轮转数组

> Array

<https://leetcode.cn/problems/rotate-array/>

