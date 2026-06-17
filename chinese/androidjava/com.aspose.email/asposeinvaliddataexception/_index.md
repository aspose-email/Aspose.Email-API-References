---
title: AsposeInvalidDataException
second_title: Aspose.Email for Android via Java API 参考
description: 当方法提供的参数无效时抛出的异常。
type: docs
weight: 46
url: /zh/androidjava/com.aspose.email/asposeinvaliddataexception/
---

**Inheritance:**
java.lang.Object, java.lang.Throwable, java.lang.Exception, java.lang.RuntimeException, com.aspose.ms.System.Exception, [com.aspose.email.AsposeException](../../com.aspose.email/asposeexception)
```
public class AsposeInvalidDataException extends AsposeException
```

当方法提供的参数无效时抛出的异常。

1
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [AsposeInvalidDataException()](#AsposeInvalidDataException--) | 初始化 [AsposeInvalidDataException](../../com.aspose.email/asposeinvaliddataexception) 类的新实例。 |
| [AsposeInvalidDataException(String message)](#AsposeInvalidDataException-java.lang.String-) | 使用指定的错误消息初始化 [AsposeInvalidDataException](../../com.aspose.email/asposeinvaliddataexception) 类的新实例。 |
| [AsposeInvalidDataException(String format, Object[] parameters)](#AsposeInvalidDataException-java.lang.String-java.lang.Object...-) | 使用指定的错误消息初始化 [AsposeInvalidDataException](../../com.aspose.email/asposeinvaliddataexception) 类的新实例。 |
| [AsposeInvalidDataException(String message, Throwable innerException)](#AsposeInvalidDataException-java.lang.String-java.lang.Throwable-) | 使用指定的错误消息和指向导致此异常的内部异常的引用来初始化 [AsposeInvalidDataException](../../com.aspose.email/asposeinvaliddataexception) 类的新实例。 |
| [AsposeInvalidDataException(Throwable innerException)](#AsposeInvalidDataException-java.lang.Throwable-) | 使用指向导致此异常的内部异常的引用来初始化 [AsposeInvalidDataException](../../com.aspose.email/asposeinvaliddataexception) 类的新实例。 |
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
### AsposeInvalidDataException() {#AsposeInvalidDataException--}
```
public AsposeInvalidDataException()
```


初始化 [AsposeInvalidDataException](../../com.aspose.email/asposeinvaliddataexception) 类的新实例。

### AsposeInvalidDataException(String message) {#AsposeInvalidDataException-java.lang.String-}
```
public AsposeInvalidDataException(String message)
```


使用指定的错误消息初始化 [AsposeInvalidDataException](../../com.aspose.email/asposeinvaliddataexception) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 描述错误的消息。 |

### AsposeInvalidDataException(String format, Object[] parameters) {#AsposeInvalidDataException-java.lang.String-java.lang.Object...-}
```
public AsposeInvalidDataException(String format, Object[] parameters)
```


使用指定的错误消息初始化 [AsposeInvalidDataException](../../com.aspose.email/asposeinvaliddataexception) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 格式 | java.lang.String | 消息格式 |
| 参数 | java.lang.Object[] | 格式化参数 |

### AsposeInvalidDataException(String message, Throwable innerException) {#AsposeInvalidDataException-java.lang.String-java.lang.Throwable-}
```
public AsposeInvalidDataException(String message, Throwable innerException)
```


使用指定的错误消息和指向导致此异常的内部异常的引用来初始化 [AsposeInvalidDataException](../../com.aspose.email/asposeinvaliddataexception) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 消息 | java.lang.String | 解释异常原因的错误信息。 |
| innerException | java.lang.Throwable | 导致当前异常的异常，如果未指定内部异常，则为 null 引用（Visual Basic 中为 Nothing）。 |

### AsposeInvalidDataException(Throwable innerException) {#AsposeInvalidDataException-java.lang.Throwable-}
```
public AsposeInvalidDataException(Throwable innerException)
```


使用指向导致此异常的内部异常的引用来初始化 [AsposeInvalidDataException](../../com.aspose.email/asposeinvaliddataexception) 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| innerException | java.lang.Throwable | 导致当前异常的异常，如果未指定内部异常，则为 null 引用（Visual Basic 中为 Nothing）。 |

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

