# LeetCode Hot 100 学习项目上下文

## 项目目标

这个项目用于系统学习 LeetCode Hot 100，主要语言是 Python，目标是准备 2026 年秋招。

学习对象是计算机基础较弱、刚开始刷算法题的用户。因此所有学习材料都要默认从零基础视角编写，不能只给题解和代码。

## GitHub 仓库

本地项目已关联远程仓库：

- `origin`: `https://github.com/centuryz1/LEETCODE-HOT-100.git`

## 当前产物

- `day01_hash_and_two_pointers.ipynb`: Day 01 学习文件，主题是哈希表和双指针入门。
- `day01_practice.ipynb`: Day 01 练习题纯享版，只含题目和空代码框，不含提示、思路和答案。
- `零碎知识补充.ipynb`: 持续记录刷题和 Python 学习中不会、易忘、易混淆的细节知识。
- `day02_hash_set_and_sliding_window.ipynb`: Day 02 学习文件，主题是哈希集合与滑动窗口。
- `day02_practice.ipynb`: Day 02 练习题纯享版。
- `day03_prefix_sum_and_array.ipynb`: Day 03 学习文件，主题是前缀和与连续数组进阶。
- `day03_practice.ipynb`: Day 03 练习题纯享版。
- `专题_if和while怎么选.ipynb`: Python 条件分支与条件循环专题，重点讲解 `if`、`while` 和 `for` 的选择。
- `专题_ACM和LeetCode输入输出.ipynb`: 秋招笔试标准输入输出与 LeetCode 函数形式转换专题。
- `专题_双指针为什么用while_left小于right.ipynb`: 双指针搜索区间、循环条件和三数之和去重专题。
- `专题_Docker从入门到实践.ipynb`: 分层讲解 Docker 基础、Python 容器化、Web 服务与基础排错。
- `专题_时间复杂度和空间复杂度.ipynb`: 面向秋招的复杂度计算方法、常见算法分析与面试表达专题。
- `Python基础知识手册_算法与秋招版.ipynb`: 面向刷题和秋招笔试的模块化 Python 基础查阅手册。
- `day04_array_and_matrix.ipynb`: Day 04 学习文件，主题是数组与矩阵操作。
- `day04_practice.ipynb`: Day 04 练习题纯享版。

## 持久规范

生成新的每日学习 notebook 前，必须先阅读：

1. `PROJECT_CONTEXT.md`
2. `NOTEBOOK_SPEC.md`
3. `零碎知识补充.ipynb`
4. 最近一天的 `dayXX_*.ipynb`

每日 notebook 应保持统一风格：

- 适合计算机小白。
- 题目描述要完整，但用改写版，不机械照搬原题。
- 每题要包含输入、输出、限制、例子、思路拆解、动手练习、参考答案、面试表达。
- 用户动手写的代码块里，要用注释重复题目、输入、目标、输出、注意事项。
- 通用细节知识放进 `零碎知识补充.ipynb`，当天题解放进 Day notebook。

## 项目结构约定

- 每日学习文件命名：`dayXX_topic_name.ipynb`
- 每日练习题纯享版命名：`dayXX_practice.ipynb`
- 零碎知识文件：`零碎知识补充.ipynb`
- 项目规范文件：`NOTEBOOK_SPEC.md`
- 跨设备继续提示：`NEXT_SESSION_PROMPT.md`
- 项目日志：`PROJECT_LOG.md`
- 后续任务：`TODO.md`

## 当前学习进度

Day 01 已创建，主题是：

- 哈希表基础
- 双指针基础
- 两数之和
- 字母异位词分组
- 移动零
- 盛最多水的容器

## 验收标准

一个新的 Day notebook 合格，需要满足：

- `.ipynb` JSON 格式可被正常解析。
- 标题、学习目标、题单、前置知识、题目模块、复盘区完整。
- 每道题都有完整改写版题目描述。
- 每个练习代码块内都有题目注释。
- 参考答案能直接运行。
- 难度对零基础用户友好。
- 每个 Day notebook 完成后，必须附带生成对应的 `dayXX_practice.ipynb`，作为无提示练习版。

## 交接说明

换设备或换助手后，先让助手读取 `NEXT_SESSION_PROMPT.md`，再继续生成下一天学习文件。


## Day 02 学习进度

Day 02 已创建，主题是：

- 哈希集合 set
- 最长连续序列
- 排序 + 双指针 + 去重
- 三数之和
- 滑动窗口入门
- 无重复字符的最长子串
- 固定长度滑动窗口
- 找到字符串中所有字母异位词

## Day 03 学习进度

Day 03 已创建，主题是：

- 前缀和 + 哈希表
- 动态规划 / Kadane 算法
- 前缀积 + 后缀积
- 单调队列 + 双端队列
- 和为 K 的子数组
- 最大子数组和
- 除自身以外数组的乘积
- 滑动窗口最大值

## Day 04 学习进度

Day 04 已创建，主题是：

- 排序 + 区间合并
- 三次反转
- 边界模拟
- 行列标记集合
- 合并区间
- 轮转数组
- 螺旋矩阵
- 矩阵置零

Day 04 不包含困难题。
