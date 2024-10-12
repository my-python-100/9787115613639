# 第 11 章　测试代码

|本期版本|上期版本
|:---:|:---:
`Sun Sep 24 22:53:10 CST 2023` | -

## 11.1 测试函数

**11.1.1 单元测试和测试用例**

* `unittest` 提供了代码测试工具

**11.1.2 可通过的测试**

```python
import unittest
class NameTestCase(unittest.TestCase):
  def test_():
    pass

unittest.main()
```

* 所有以 test 打头的方法都将自动运行


---

## 11.1　使用 pip 安装 pytest

**11.1.1　更新 pip**

先来更新 pip

```bash
python -m pip install --upgrade pip
```

可使用下面的命令更新系统中安装的任何包

```bash
python -m pip install --upgrade package_name
```

**11.1.2　安装 pytest**

```bash
python -m pip install --user pytest
```

## 11.2　测试函数

* 测试文件的名称很重要，必须以 `test_`打头。当你让 pytest 运行测试时，它将查找以 test_打头的文件
* 在测试过程中，pytest 将找出并运行所有以 `test_` 打头的函数

## 11.3　测试类

**11.3.4　使用夹具**

* 装饰器（decorator）是放在函数定义前面的指令
* 在运行函数前，Python 将该指令应用于函数，以修改函数代码的行为
* 当测试函数的一个形参与应用了装饰器 @pytest.fixture 的函数（夹具）同名时，将自动运行夹具，并将夹具返回的值传递给测试函数。


```python
import pytest

@pytest.fixture
```