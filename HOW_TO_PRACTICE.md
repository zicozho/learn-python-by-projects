# How To Practice

## 1. 先从项目开始，不要先看答案

例如你要做质数检查器：

```text
projects/p03_prime_checker/
```

先打开：

```text
README.md
test_solution.py
starter.py
```

## 2. 把测试目标看懂

测试会告诉你：

```python
assert is_prime(17) is True
assert is_prime(18) is False
```

这比看一大段理论更直接。

## 3. 改测试导入

把：

```python
from .solution import is_prime
```

改成：

```python
from .starter import is_prime
```

## 4. 写 starter.py

只要让测试通过即可。

## 5. 跑测试

```bash
pytest projects/p03_prime_checker -q
```

## 6. 再看 solution.py

看它和你的写法有什么差别。

## 7. 做变体

比如质数检查器可以扩展成：

- 输出 100 以内所有质数
- 统计 1 到 n 有多少质数
- 找出两个数之间的所有质数

这才是真正吸收。
