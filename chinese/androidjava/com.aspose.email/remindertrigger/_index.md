---
title: ReminderTrigger
second_title: Aspose.Email for Android via Java API 参考
description: 指定闹钟何时触发。
type: docs
weight: 372
url: /zh/androidjava/com.aspose.email/remindertrigger/
---

**Inheritance:**
java.lang.Object
```
public class ReminderTrigger
```

指定闹钟何时触发。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ReminderTrigger(Date dateTime)](#ReminderTrigger-java.util.Date-) | 初始化一个新的 [ReminderTrigger](../../com.aspose.email/remindertrigger) 类实例。 |
| [ReminderTrigger(ReminderDuration duration, int related)](#ReminderTrigger-com.aspose.email.ReminderDuration-int-) | 初始化一个新的 [ReminderTrigger](../../com.aspose.email/remindertrigger) 类实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDateTime()](#getDateTime--) | 一个设置为绝对日期/时间的触发器。 |
| [getDuration()](#getDuration--) | 指定警报触发器的相对时间。 |
| [getRelated()](#getRelated--) | 指定闹钟触发器相对于事件开始或结束的关系。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDateTime(Date value)](#setDateTime-java.util.Date-) | 一个设置为绝对日期/时间的触发器。 |
| [setDuration(ReminderDuration value)](#setDuration-com.aspose.email.ReminderDuration-) | 指定警报触发器的相对时间。 |
| [setRelated(int value)](#setRelated-int-) | 指定闹钟触发器相对于事件开始或结束的关系。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReminderTrigger(Date dateTime) {#ReminderTrigger-java.util.Date-}
```
public ReminderTrigger(Date dateTime)
```


初始化一个新的 [ReminderTrigger](../../com.aspose.email/remindertrigger) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| dateTime | java.util.Date | 绝对 DateTime 值。 |

### ReminderTrigger(ReminderDuration duration, int related) {#ReminderTrigger-com.aspose.email.ReminderDuration-int-}
```
public ReminderTrigger(ReminderDuration duration, int related)
```


初始化一个新的 [ReminderTrigger](../../com.aspose.email/remindertrigger) 类实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| duration | [ReminderDuration](../../com.aspose.email/reminderduration) | 用于指定警报触发器的相对时间。 |
| 相关 | int | 用于指定警报触发器相对于事件开始或结束的关系。 |

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
### getDateTime() {#getDateTime--}
```
public final Date getDateTime()
```


一个设置为绝对日期/时间的触发器。

**Returns:**
java.util.Date
### getDuration() {#getDuration--}
```
public final ReminderDuration getDuration()
```


指定警报触发器的相对时间。

**Returns:**
[ReminderDuration](../../com.aspose.email/reminderduration)
### getRelated() {#getRelated--}
```
public final int getRelated()
```


指定闹钟触发器相对于事件开始或结束的关系。

**Returns:**
int
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




### setDateTime(Date value) {#setDateTime-java.util.Date-}
```
public final void setDateTime(Date value)
```


一个设置为绝对日期/时间的触发器。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date |  |

### setDuration(ReminderDuration value) {#setDuration-com.aspose.email.ReminderDuration-}
```
public final void setDuration(ReminderDuration value)
```


指定警报触发器的相对时间。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ReminderDuration](../../com.aspose.email/reminderduration) |  |

### setRelated(int value) {#setRelated-int-}
```
public final void setRelated(int value)
```


指定闹钟触发器相对于事件开始或结束的关系。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

