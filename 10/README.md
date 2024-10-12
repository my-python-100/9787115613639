# 第 10 章　文件和异常

|本期版本|上期版本
|:---:|:---:
`Sat Oct 12 15:33:43 CST 2024` | `Sun Sep 24 22:22:49 CST 2023`

## 10.1 从文件中读取数据

```python
open()
read()
readlines()
```



## 10.2　写入文件


```python
write()
```

## 10.3　异常

* 异常是使用 `try-except` 代码块处理的
* 只有 try 代码块成功执行才需要继续执行的代码，都应放到 else 代码块中

**10.3.8　静默失败**

* Python 有一个 pass 语句，可在代码块中使用它来让 Python 什么都不做

## 10.4　存储数据

**10.4.1　使用 json.dumps() 和 json.loads()**