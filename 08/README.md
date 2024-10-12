# 第 8 章　函数

|本期版本|上期版本
|:---:|:---:
`Sat Oct 12 14:33:57 CST 2024` | `Sun Sep 24 16:35:32 CST 2023`

## 8.4 传递列表


**8.4.2 禁止函数修改列表**

* 可向函数传递列表的副本而不是原件
* 切片表示法[:]创建列表的副本


## 8.5　传递任意数量的实参

* 形参名 `*toppings` 中的星号让 Python 创建一个名为 toppings 的元组，该元组包含函数收到的所有值

**8.5.2　使用任意数量的关键字实参**

* 形参 `**user_info` 中的两个星号让 Python 创建一个名为 user_info 的字典，该字典包含函数收到的其他所有名值对
* 你经常会看到形参名 `**kwargs`，它用于收集任意数量的关键字实参。


## 8.6 将函数存储在模块中

**8.6.1 导入整个模块**

```python
import pizza
```

**8.6.2 导入特定的函数**

```python
from module_name import function_name
from module_name import function_0, function1
```

**8.6.3 使用as给函数指定别名**

```python
from pizza import make_pizza as mp
```

**8.6.4 使用as给模块指定别名**

```python
import pizza as p
```

**8.6.5 导入模块中的所有函数**

```python
from pizza import *
```


