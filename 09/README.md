# 第 9 章　类

|本期版本|上期版本
|:---:|:---:
`Sat Oct 12 15:00:51 CST 2024` | `Sun Sep 24 19:28:19 CST 2023`


## 9.1 创建和使用类



**9.1.1 创建Dog类**

* 在 Python 中，首字母大写的名称指的是类
* `__init__()` 是一个特殊的方法
* 每个与类相关联的方法调用都自动传递实参 self, 它是一个指向实例本身的引用
* 以 self 为前缀的变量都可供类中所有的方法使用

## 9.3 继承


* 必须在括号内指定父类的名称

```python
  super().__init__()
```

## 9.4 导入类

```python
from car import Car
from car import Car, ElectricCar
```