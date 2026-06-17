---
title: AsposeNotSupportedException
second_title: Aspose.Email for Android via Java API 参考
description: 当调用的方法或参数不受支持，或尝试对不支持所调用功能的流进行读取、定位或写入时抛出的异常。
type: docs
weight: 48
url: /zh/androidjava/com.aspose.email/asposenotsupportedexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception)
```
public class AsposeNotSupportedException extends AsposeException
```

当调用的方法或参数不受支持，或尝试对不支持该功能的流进行读取、定位或写入时抛出的异常。

1
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AsposeNotSupportedException()](#AsposeNotSupportedException--) | 初始化 [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) 类的新实例。 |
| [AsposeNotSupportedException(String message)](#AsposeNotSupportedException-java.lang.String-) | 使用指定的错误消息初始化 [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) 类的新实例。 |
| [AsposeNotSupportedException(String format, String parameter)](#AsposeNotSupportedException-java.lang.String-java.lang.String-) |  |
| [AsposeNotSupportedException(String format, Object[] parameters)](#AsposeNotSupportedException-java.lang.String-java.lang.Object...-) | 使用指定的错误消息初始化 [AsposeArgumentOutOfRangeException](../../com.aspose.email/asposeargumentoutofrangeexception) 类的新实例。 |
| [AsposeNotSupportedException(String message, System.Exception innerException)](#AsposeNotSupportedException-java.lang.String-com.aspose.ms.System.Exception-) | 使用指定的错误消息和指向导致此异常的内部异常的引用，初始化 [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) 类的新实例。 |
| [AsposeNotSupportedException(System.Exception innerException)](#AsposeNotSupportedException-com.aspose.ms.System.Exception-) | 使用指向导致此异常的内部异常的引用，初始化 [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [addSuppressed(Throwable arg0)](#addSuppressed-java.lang.Throwable-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fillInStackTrace()](#fillInStackTrace--) |  |
| [getCause()](#getCause--) |  |
| [getClass()](#getClass--) |  |
| [getErrorDetails()](#getErrorDetails--) | 获取有关错误的额外信息 |
| [getInnerException()](#getInnerException--) |  |
| [getLocalizedMessage()](#getLocalizedMessage--) |  |
| [getMessage()](#getMessage--) | 获取描述当前异常的消息。 |
| [getStackTrace()](#getStackTrace--) |  |
| [getSuppressed()](#getSuppressed--) |  |
| [getType()](#getType--) |  |
| [hashCode()](#hashCode--) |  |
| [initCause(Throwable arg0)](#initCause-java.lang.Throwable-) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [printStackTrace()](#printStackTrace--) |  |
| [printStackTrace(PrintStream arg0)](#printStackTrace-java.io.PrintStream-) |  |
| [printStackTrace(PrintWriter arg0)](#printStackTrace-java.io.PrintWriter-) |  |
| [setStackTrace(StackTraceElement[] arg0)](#setStackTrace-java.lang.StackTraceElement---) |  |
| [toString()](#toString--) | 返回表示当前对象的字符串。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AsposeNotSupportedException() {#AsposeNotSupportedException--}
```
public AsposeNotSupportedException()
```


初始化 [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) 类的新实例。

### AsposeNotSupportedException(String message) {#AsposeNotSupportedException-java.lang.String-}
```
public AsposeNotSupportedException(String message)
```


使用指定的错误消息初始化 [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 描述错误的消息。 |

### AsposeNotSupportedException(String format, String parameter) {#AsposeNotSupportedException-java.lang.String-java.lang.String-}
```
public AsposeNotSupportedException(String format, String parameter)
```


**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 格式 | java.lang.String |  |
| 参数 | java.lang.String |  |

### AsposeNotSupportedException(String format, Object[] parameters) {#AsposeNotSupportedException-java.lang.String-java.lang.Object...-}
```
public AsposeNotSupportedException(String format, Object[] parameters)
```


使用指定的错误消息初始化 [AsposeArgumentOutOfRangeException](../../com.aspose.email/asposeargumentoutofrangeexception) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 格式 | java.lang.String | 消息格式 |
| 参数 | java.lang.Object[] | 格式化参数 |

### AsposeNotSupportedException(String message, System.Exception innerException) {#AsposeNotSupportedException-java.lang.String-com.aspose.ms.System.Exception-}
```
public AsposeNotSupportedException(String message, System.Exception innerException)
```


使用指定的错误消息和指向导致此异常的内部异常的引用，初始化 [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 解释异常原因的错误信息。 |
| innerException | com.aspose.ms.System.Exception | 导致当前异常的异常，如果未指定内部异常，则为 null 引用（Visual Basic 中为 Nothing）。 |

### AsposeNotSupportedException(System.Exception innerException) {#AsposeNotSupportedException-com.aspose.ms.System.Exception-}
```
public AsposeNotSupportedException(System.Exception innerException)
```


使用指向导致此异常的内部异常的引用，初始化 [AsposeNotSupportedException](../../com.aspose.email/asposenotsupportedexception) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| innerException | com.aspose.ms.System.Exception | 导致当前异常的异常，如果未指定内部异常，则为 null 引用（Visual Basic 中为 Nothing）。 |

### addSuppressed(Throwable arg0) {#addSuppressed-java.lang.Throwable-}
```
public final synchronized void addSuppressed(Throwable arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

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
### fillInStackTrace() {#fillInStackTrace--}
```
public synchronized Throwable fillInStackTrace()
```




**Returns:**
java.lang.Throwable
### getCause() {#getCause--}
```
public synchronized Throwable getCause()
```




**Returns:**
java.lang.Throwable
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getErrorDetails() {#getErrorDetails--}
```
public final Object getErrorDetails()
```


获取有关错误的额外信息

**Returns:**
java.lang.Object
### getInnerException() {#getInnerException--}
```
public Throwable getInnerException()
```




**Returns:**
java.lang.Throwable
### getLocalizedMessage() {#getLocalizedMessage--}
```
public String getLocalizedMessage()
```




**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public String getMessage()
```


获取描述当前异常的消息。

**Returns:**
java.lang.String
### getStackTrace() {#getStackTrace--}
```
public StackTraceElement[] getStackTrace()
```




**Returns:**
java.lang.StackTraceElement[]
### getSuppressed() {#getSuppressed--}
```
public final synchronized Throwable[] getSuppressed()
```




**Returns:**
java.lang.Throwable[]
### getType() {#getType--}
```
public System.Type getType()
```




**Returns:**
com.aspose.ms.System.Type
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initCause(Throwable arg0) {#initCause-java.lang.Throwable-}
```
public synchronized Throwable initCause(Throwable arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Throwable |  |

**Returns:**
java.lang.Throwable
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### printStackTrace() {#printStackTrace--}
```
public void printStackTrace()
```




### printStackTrace(PrintStream arg0) {#printStackTrace-java.io.PrintStream-}
```
public void printStackTrace(PrintStream arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.io.PrintStream |  |

### printStackTrace(PrintWriter arg0) {#printStackTrace-java.io.PrintWriter-}
```
public void printStackTrace(PrintWriter arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.io.PrintWriter |  |

### setStackTrace(StackTraceElement[] arg0) {#setStackTrace-java.lang.StackTraceElement---}
```
public void setStackTrace(StackTraceElement[] arg0)
```




**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.StackTraceElement[] |  |

### toString() {#toString--}
```
public String toString()
```


返回表示当前对象的字符串。

**Returns:**
java.lang.String - 表示当前对象的字符串。
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

