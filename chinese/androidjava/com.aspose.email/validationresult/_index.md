---
title: ValidationResult
second_title: Aspose.Email for Android via Java API 参考
description: 呈现电子邮件验证过程的结果。
type: docs
weight: 444
url: /zh/androidjava/com.aspose.email/validationresult/
---

**Inheritance:**
java.lang.Object
```
public class ValidationResult
```

呈现电子邮件验证过程的结果。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [ValidationResult()](#ValidationResult--) | 创建 ValidationResult 类的实例 |
| [ValidationResult(int responseCode)](#ValidationResult-int-) | 创建 ValidationResult 类的实例，使用指定的 |
| [ValidationResult(int responseCode, RuntimeException lastException)](#ValidationResult-int-java.lang.RuntimeException-) | 创建 ValidationResult 类的实例，使用指定的 , 以及最后的异常。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getLastException()](#getLastException--) | 验证过程中遇到的最后一个错误。 |
| [getMessage()](#getMessage--) | 获取结果的详细信息。 |
| [getReturnCode()](#getReturnCode--) | 获取或设置验证过程的响应代码。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLastException(RuntimeException value)](#setLastException-java.lang.RuntimeException-) | 验证过程中遇到的最后一个错误。 |
| [setReturnCode(int value)](#setReturnCode-int-) | 获取或设置验证过程的响应代码。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ValidationResult() {#ValidationResult--}
```
public ValidationResult()
```


创建 ValidationResult 类的实例

### ValidationResult(int responseCode) {#ValidationResult-int-}
```
public ValidationResult(int responseCode)
```


创建 ValidationResult 类的实例，使用指定的

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| responseCode | int | 验证过程的响应代码。 |

### ValidationResult(int responseCode, RuntimeException lastException) {#ValidationResult-int-java.lang.RuntimeException-}
```
public ValidationResult(int responseCode, RuntimeException lastException)
```


创建 ValidationResult 类的实例，使用指定的 , 以及最后的异常。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| responseCode | int | 验证过程的响应代码。 |
| lastException | java.lang.RuntimeException | 验证过程中遇到的最后一个异常。 |

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
### getLastException() {#getLastException--}
```
public final RuntimeException getLastException()
```


验证过程中遇到的最后一个错误。

**Returns:**
java.lang.RuntimeException
### getMessage() {#getMessage--}
```
public final String getMessage()
```


获取结果的详细信息。

**Returns:**
java.lang.String
### getReturnCode() {#getReturnCode--}
```
public final int getReturnCode()
```


获取或设置验证过程的响应代码。

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




### setLastException(RuntimeException value) {#setLastException-java.lang.RuntimeException-}
```
public final void setLastException(RuntimeException value)
```


验证过程中遇到的最后一个错误。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.RuntimeException |  |

### setReturnCode(int value) {#setReturnCode-int-}
```
public final void setReturnCode(int value)
```


获取或设置验证过程的响应代码。

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

