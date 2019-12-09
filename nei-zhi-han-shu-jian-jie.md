# python提供一系列基础函数

### id:查看对象在内存的标记

```py
>>> id(123)
45708400L
```

```py
>>>a = 'test'
>>>id(a)
60435408L
```

```
>>>a=[1,2,3]
>>>id(a)
41381832L
```

### help:查看对象的帮助说明

<img src="/assets/help_sysmodule.png"/>

```py
def testfunc():
    """
        this is something for help
    """
help(testfunc)
```

![](/assets/help_definition.png)

### isinstance: 查看对象是否是某一种类型

### type: 查看对象的类型

---



