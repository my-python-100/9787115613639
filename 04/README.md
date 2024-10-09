# 第 4 章 操作列表

|本期版本|上期版本
|:---:|:---:
`Wed Oct  9 23:42:29 CST 2024` | `Thu Sep 21 23:28:44 CST 2023`

## 4.1　遍历整个列表

```python
for magician in magicians:
	print(f"{magician.title()}, that was a great trick!")
```

## 4.2　避免缩进错误

* Python 根据缩进来判断代码行与程序其他部分的关系

## 4.3　创建数值列表

**4.3.2　使用 range() 创建数值列表**


* 可使用 list() 函数将 range() 的结果直接转换为列表

**4.3.4　列表推导式**

```python
squares = [value**2 for value in range(1, 11)]
```

* 将 for 循环和创建新元素的代码合并成一行，并自动追加新元素
* 并定义一个表达式，用于生成要存储到列表中的值
* 编写一个 for 循环，用于给表达式提供值

## 4.4　使用列表的一部分

* 你还可以处理列表的部分元素，在 Python 中称为切片（slice）

**4.4.1　切片**

```python
players[0:4]
```
* 要创建切片，可指定要使用的第一个元素和最后一个元素的索引
* 如果没有指定第一个索引，Python 将自动从列表开头开始
* 负数索引返回与列表末尾有相应距离的元素，因此可以输出列表末尾的任意切片

**4.4.3　复制列表**

* 要复制列表，可以创建一个包含整个列表的切片，方法是同时省略起始索引和终止索引（[:]）


## 4.5　元组

* Python 将不能修改的值称为不可变的，而不可变的列表称为元组（tuple）。

**4.5.1　定义元组**

* 使用圆括号而不是方括号
* 定义只包含一个元素的元祖，必须在这个元素后面加上逗号

## 4.6 设置代码格式

* Python 增强天(Python Enhancerment Proposal, PEP)
* <https://china-testing.github.io/python_pep8.html>