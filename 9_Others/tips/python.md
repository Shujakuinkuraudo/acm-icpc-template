python科学计算不是没有依据的= =特别大型的数据需要好好计算一下, 但是一般的验证,生成测试数据神马的用python真是再方便不过了.

进制转换
---

使用Python内置函数：`bin()`、`oct()`、`int()`、`hex()`可实现进制转换。

其中`int([number | string[, base]])`可以转换其他进制.比如8进制转换到二进制,我们这样`bin(int(x,8))`.

着实有用.


Math库的使用
---

我们依据素数定理求素数个数 -- 一般要使用这个定理的时候int值会比较大.

```python
import math

# 求lnx的值
print math.log(x, math.e)

# 求pi
print math.pi
print math.acos(-1.0)
```

日后使用到的现在没有想到的,会陆续添加.

datetime日期库的使用
---

```python

# 1000天以后
import datetime
a = datetime.datetime(2015,02,19)
a += datetime.timedelta(1000)
print a
```
