[Uploading README.md…]()
# Python Core Project Drills

这是一个把 Python 100 Days 前 20 天内容压缩成 **45 个实战小项目** 的练习仓库。

它不是按“第几天”学习，而是按“能做出什么东西”学习。

你会通过这些项目高效覆盖：

- 变量、数据类型、输入输出
- 运算符、表达式、布尔值
- 分支结构
- 循环结构
- 列表、元组、字符串、集合、字典
- 函数、模块、默认参数、类型标注
- 高阶函数
- 装饰器
- 递归
- 面向对象编程
- 小型综合项目

## 学习方式

每个项目都是一个独立文件夹：

```text
projects/p01_leap_year_checker/
projects/p02_bmi_calculator/
...
projects/p45_mini_rule_engine/
```

每个项目包含：

```text
README.md          项目说明
starter.py         你自己写
solution.py        参考答案
test_solution.py   pytest 测试
```

默认测试导入的是 `solution.py`，所以仓库下载后可以直接跑通。

你真正练习时，把 `test_solution.py` 里的：

```python
from .solution import ...
```

改成：

```python
from .starter import ...
```

然后补完 `starter.py`，直到测试通过。

## 安装和运行

```bash
python -m venv .venv
```

Windows:

```bash
.venv\Scripts\activate
```

macOS / Linux:

```bash
source .venv/bin/activate
```

安装依赖：

```bash
pip install -r requirements.txt
```

运行全部测试：

```bash
pytest -q
```

## 为什么这样比按天学更高效

传统学习方式容易变成“我看懂了，但我不会写”。

这个仓库强迫你用项目吸收知识：

```text
需求 → 函数 → 测试 → 报错 → 修正 → 复用
```

你不需要把所有语法细节都学完才动手，而是在每个小项目中反复遇到核心语法。

## 项目总览

见 `PROJECT_MAP.md`。
