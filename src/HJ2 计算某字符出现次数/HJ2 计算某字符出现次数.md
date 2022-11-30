# HJ2 计算某字符出现次数

> 难易程度：简单

> 类型：字符串

### 题目描述

写出一个程序，接受一个由字母、数字和空格组成的字符串，和一个字符，然后输出输入字符串中该字符的出现次数。（不区分大小写字母）

数据范围： 1 ≤ n ≤1000 

> 输入描述：
第一行输入一个由字母和数字以及空格组成的字符串，第二行输入一个字符。

> 输出描述：
输出输入字符串中含有该字符的个数。（不区分大小写字母）

### 示例

```
输入：ABCabc
     A

输出：2
```

### 题目分析

1. 分别小写接手到的两个字符串
2. 用count()函数查询出现次数

### 代码实现

```python
word_source = input()
word_target = input()

word_source = word_source.lower()
word_target = word_target.lower()

print(word_source.count(word_target))
```