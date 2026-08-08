---
title: SyntaxValidatingEventArgs
second_title: Aspose.Email for Android via Java API 参考
description: 提供 SyntaxValidating 事件的数据。
type: docs
weight: 394
url: /zh/androidjava/com.aspose.email/syntaxvalidatingeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class SyntaxValidatingEventArgs extends System.EventArgs
```

提供 SyntaxValidating 事件的数据。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [SyntaxValidatingEventArgs(String mail)](#SyntaxValidatingEventArgs-java.lang.String-) | 初始化 SyntaxValidatingEventArgs 类的新实例。 |
## 字段

| 字段 | 描述 |
| --- | --- |
| [Empty](#Empty) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMail()](#getMail--) | 获取正在验证的邮件地址。 |
| [getResult()](#getResult--) | 获取或设置验证结果。 |
| [getSkip()](#getSkip--) | 指示是否忽略检查。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setResult(ValidationResult value)](#setResult-com.aspose.email.ValidationResult-) | 获取或设置验证结果。 |
| [setSkip(boolean value)](#setSkip-boolean-) | 指示是否忽略检查。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### SyntaxValidatingEventArgs(String mail) {#SyntaxValidatingEventArgs-java.lang.String-}
```
public SyntaxValidatingEventArgs(String mail)
```


初始化 SyntaxValidatingEventArgs 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| mail | java.lang.String | 邮件地址。 |

### Empty {#Empty}
```
public static final System.EventArgs Empty
```


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
### getMail() {#getMail--}
```
public final String getMail()
```


获取正在验证的邮件地址。

**Returns:**
java.lang.String
### getResult() {#getResult--}
```
public final ValidationResult getResult()
```


获取或设置验证结果。

**Returns:**
[ValidationResult](../../com.aspose.email/validationresult)
### getSkip() {#getSkip--}
```
public final boolean getSkip()
```


指示是否忽略检查。

**Returns:**
boolean
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




### setResult(ValidationResult value) {#setResult-com.aspose.email.ValidationResult-}
```
public final void setResult(ValidationResult value)
```


获取或设置验证结果。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ValidationResult](../../com.aspose.email/validationresult) |  |

### setSkip(boolean value) {#setSkip-boolean-}
```
public final void setSkip(boolean value)
```


指示是否忽略检查。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

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

