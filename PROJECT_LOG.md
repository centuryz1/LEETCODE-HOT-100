# 项目日志

## 2026-07-29

### 本次目标

建立 LeetCode Hot 100 学习项目的跨设备连续性规范，避免换设备后生成的学习文件风格不一致。

### 已完成

- 创建 `PROJECT_CONTEXT.md`，记录项目目标、当前产物、持久规范和交接说明。
- 创建 `NOTEBOOK_SPEC.md`，固化每日 notebook 的生成结构、题目模块结构、练习代码块规范和校验方式。
- 创建 `NEXT_SESSION_PROMPT.md`，提供换设备时可直接复制给助手的提示词。
- 创建 `TODO.md`，记录后续学习任务。
- 初始化本地 Git 仓库，并将 `origin` 关联到 `https://github.com/centuryz1/LEETCODE-HOT-100.git`。

### 当前状态

项目已经不依赖单个助手的聊天记忆。后续任何设备都可以通过读取项目规范文件继续生成同风格的学习 notebook。本地 Git 仓库已关联 GitHub 远程仓库。

### 验证

本次新增的是 Markdown 项目管理文件，不需要 notebook JSON 校验。已通过 `git remote -v` 检查远程仓库关联。

### 下一步

继续 Day 01 学习，完成或复盘前 2-4 道题；之后按 `NOTEBOOK_SPEC.md` 生成 Day 02。

## 2026-07-29

### 本次目标

根据用户建议，为每日题解补充专业解法名称，方便秋招面试表达。

### 已完成

- 在 `day01_hash_and_two_pointers.ipynb` 的 4 道题中补充解法名称。
- 在用户动手写的代码块注释中加入 `# 解法：...`。
- 更新 `NOTEBOOK_SPEC.md`，要求后续 Day notebook 都包含中文专业名和常见英文说法。

### 验证

- 已计划校验 `day01_hash_and_two_pointers.ipynb` 的 JSON 格式。

### 下一步

继续按新规范生成后续学习文件。

## 2026-07-29

### 本次目标

补充刷题常用 Python 字典知识，服务 Day 01 的哈希表学习。

### 已完成

- 在 `前置知识补充.ipynb` 中新增 `B03-1. dict 常用操作`。
- 在 `前置知识补充.ipynb` 中新增 `B03-2. defaultdict 常用操作`。
- 补充了创建、查询、`get`、`in`、新增、修改、删除、遍历、计数、分组和常见误区。

### 验证

- 已校验 `前置知识补充.ipynb` 为合法 ipynb JSON。

### 下一步

Day 01 学习两数之和、字母异位词分组时，可以先查阅这两个字典小节。

## 2026-07-29

### 本次目标

为 Day 01 创建无提示练习题纯享版，并将该产物固化为后续每日学习文件的配套要求。

### 已完成

- 创建 `day01_hash_and_two_pointers_practice.ipynb`，随后按用户偏好重命名为 `day01_practice.ipynb`。
- 纯享版只包含题目描述和空函数代码块，不包含提示、思路、测试、参考答案和面试表达。
- 更新 `PROJECT_CONTEXT.md`，记录练习题纯享版命名约定和验收要求。
- 更新 `NOTEBOOK_SPEC.md`，新增练习题纯享版 notebook 规范。
- 更新 `TODO.md`，记录后续每日都要生成配套练习题纯享版。

### 验证

- 已计划校验 `day01_hash_and_two_pointers_practice.ipynb` 的 JSON 格式。

### 下一步

后续生成 Day 02 时，同时生成 `day02_practice.ipynb`。

## 2026-07-29

### 本次目标

解释用户不理解的“双指针”概念，并补充到模块化前置知识库。

### 已完成

- 在 `前置知识补充.ipynb` 的模块 D 中新增 `D01. 双指针`。
- 补充双指针的概念、作用、左右指针、快慢指针、同向双指针、识别信号和常见误区。
- 加入最小 Python 示例，方便用户逐格运行观察。

### 验证

- 已校验 `前置知识补充.ipynb` 为合法 ipynb JSON。

### 下一步

Day 01 的“移动零”和“盛最多水的容器”可以结合 D01 双指针模块一起学习。

