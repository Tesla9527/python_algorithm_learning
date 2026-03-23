# Python 算法学习项目
- 基于《Hello Algo》的算法理论学习 + LeetCode 刷题实战，专注 Python 实现。
- 《Hello Algo》书籍：https://www.hello-algo.com/chapter_hello_algo/

## 项目结构
- algo_templates/: 核心算法模板（按知识点分类）
- leetcode_practice/: LeetCode 刷题代码（按题型分类）
- utils/: 通用工具类（二叉树/链表节点、测试辅助）
- notes/: 学习笔记

## 使用方式
1. 安装依赖：uv pip install -r requirements.txt
2. 查看算法模板：直接运行 algo_templates/ 下的文件，如 python algo_templates/binary_search.py
3. 刷题代码：每个文件包含题目描述、解题思路、Python 实现、测试用例


## 刷题文件命名规范（易检索）
严格遵循：leetcode_<题号>_<题目英文名>.py，比如：
- 两数之和 → leetcode_1_two_sum.py
- 最长无重复子串 → leetcode_3_longest_substring_without_repeating_characters.py
