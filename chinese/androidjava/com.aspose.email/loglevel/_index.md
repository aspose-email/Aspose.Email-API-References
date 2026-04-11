---
title: 日志级别
second_title: Aspose.Email for Android via Java API 参考
description: 定义可用的日志级别。
type: docs
weight: 183
url: /zh/androidjava/com.aspose.email/loglevel/
---

**Inheritance:**
java.lang.Object
```
public class LogLevel
```

定义可用的日志级别。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Debug](#Debug) | 调试级别。 |
| [Error](#Error) | 错误级别。 |
| [Fatal](#Fatal) | 致命级别。 |
| [Information](#Information) | 信息级别。 |
| [Trace](#Trace) | 跟踪级别。 |
| [Warning](#Warning) | 警告级别。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | 将该级别与另一个 [LogLevel](../../com.aspose.email/loglevel) 对象进行比较。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_GreaterThan(LogLevel l1, LogLevel l2)](#op-GreaterThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | 比较两个 [LogLevel](../../com.aspose.email/loglevel) 对象，并返回一个值，指示第一个是否大于第二个。 |
| [op_GreaterThanOrEqual(LogLevel l1, LogLevel l2)](#op-GreaterThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | 比较两个 [LogLevel](../../com.aspose.email/loglevel) 对象，并返回一个值，指示第一个是否大于或等于第二个。 |
| [op_LessThan(LogLevel l1, LogLevel l2)](#op-LessThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | 比较两个 [LogLevel](../../com.aspose.email/loglevel) 对象，并返回一个值，指示第一个是否小于第二个。 |
| [op_LessThanOrEqual(LogLevel l1, LogLevel l2)](#op-LessThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | 比较两个 [LogLevel](../../com.aspose.email/loglevel) 对象，并返回一个值，指示第一个是否小于或等于第二个。 |
| [toString()](#toString--) | 返回日志级别的字符串表示形式。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Debug {#Debug}
```
public static final LogLevel Debug
```


调试级别。

### Error {#Error}
```
public static final LogLevel Error
```


错误级别。

### Fatal {#Fatal}
```
public static final LogLevel Fatal
```


致命级别。

### Information {#Information}
```
public static final LogLevel Information
```


信息级别。

### Trace {#Trace}
```
public static final LogLevel Trace
```


跟踪级别。

### Warning {#Warning}
```
public static final LogLevel Warning
```


警告级别。

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


将该级别与另一个 [LogLevel](../../com.aspose.email/loglevel) 对象进行比较。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 对象对象 |

**Returns:**
int - 当此记录器的 Ordinal (\\#getOrdinal.getOrdinal) 小于另一个记录器的序数时，返回小于零的值；相等时返回 0；大于时返回大于零的值。
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_GreaterThan(LogLevel l1, LogLevel l2) {#op-GreaterThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_GreaterThan(LogLevel l1, LogLevel l2)
```


比较两个 [LogLevel](../../com.aspose.email/loglevel) 对象，并返回一个值，指示第一个是否大于第二个。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | 第一个级别。 |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | 第二个级别。 |

**Returns:**
boolean - l1.Ordinal > l2.Ordinal 的值
### op_GreaterThanOrEqual(LogLevel l1, LogLevel l2) {#op-GreaterThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_GreaterThanOrEqual(LogLevel l1, LogLevel l2)
```


比较两个 [LogLevel](../../com.aspose.email/loglevel) 对象，并返回一个值，指示第一个是否大于或等于第二个。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | 第一个级别。 |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | 第二个级别。 |

**Returns:**
boolean - l1.Ordinal >= l2.Ordinal 的值
### op_LessThan(LogLevel l1, LogLevel l2) {#op-LessThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_LessThan(LogLevel l1, LogLevel l2)
```


比较两个 [LogLevel](../../com.aspose.email/loglevel) 对象，并返回一个值，指示第一个是否小于第二个。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | 第一个级别。 |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | 第二个级别。 |

**Returns:**
boolean - l1.Ordinal < l2.Ordinal 的值
### op_LessThanOrEqual(LogLevel l1, LogLevel l2) {#op-LessThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_LessThanOrEqual(LogLevel l1, LogLevel l2)
```


比较两个 [LogLevel](../../com.aspose.email/loglevel) 对象，并返回一个值，指示第一个是否小于或等于第二个。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | 第一个级别。 |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | 第二个级别。 |

**Returns:**
boolean - l1.Ordinal <= l2.Ordinal 的值
### toString() {#toString--}
```
public String toString()
```


返回日志级别的字符串表示形式。

**Returns:**
java.lang.String - 日志级别名称。
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

