---
title: LogLevel
second_title: Aspose.Email for Java API Reference
description: Defines available log levels.
type: docs
weight: 374
url: /java/com.aspose.email/loglevel/
---

**Inheritance:**
java.lang.Object
```
public class LogLevel
```

Defines available log levels.
## Fields

| Field | Description |
| --- | --- |
| [Debug](#Debug) | The Debug level. |
| [Error](#Error) | The Error level. |
| [Fatal](#Fatal) | The Fatal level. |
| [Information](#Information) | The Info level. |
| [Trace](#Trace) | The Trace level. |
| [Warning](#Warning) | The Warn level. |
## Methods

| Method | Description |
| --- | --- |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Compares the level to the other [LogLevel](../../com.aspose.email/loglevel) object. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_GreaterThan(LogLevel l1, LogLevel l2)](#op-GreaterThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is greater than the second one. |
| [op_GreaterThanOrEqual(LogLevel l1, LogLevel l2)](#op-GreaterThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is greater than or equal to the second one. |
| [op_LessThan(LogLevel l1, LogLevel l2)](#op-LessThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is less than the second one. |
| [op_LessThanOrEqual(LogLevel l1, LogLevel l2)](#op-LessThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-) | Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is less than or equal to the second one. |
| [toString()](#toString--) | Returns a string representation of the log level. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Debug {#Debug}
```
public static final LogLevel Debug
```


The Debug level.

### Error {#Error}
```
public static final LogLevel Error
```


The Error level.

### Fatal {#Fatal}
```
public static final LogLevel Fatal
```


The Fatal level.

### Information {#Information}
```
public static final LogLevel Information
```


The Info level.

### Trace {#Trace}
```
public static final LogLevel Trace
```


The Trace level.

### Warning {#Warning}
```
public static final LogLevel Warning
```


The Warn level.

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Compares the level to the other [LogLevel](../../com.aspose.email/loglevel) object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | the object object |

**Returns:**
int - a value less than zero when this logger's  Ordinal (\#getOrdinal.getOrdinal) is less than the other logger's ordinal, 0 when they are equal and greater than zero when this ordinal is greater than the other ordinal.
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
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


Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is greater than the second one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | The first level. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | The second level. |

**Returns:**
boolean - The value of  l1.Ordinal > l2.Ordinal 
### op_GreaterThanOrEqual(LogLevel l1, LogLevel l2) {#op-GreaterThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_GreaterThanOrEqual(LogLevel l1, LogLevel l2)
```


Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is greater than or equal to the second one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | The first level. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | The second level. |

**Returns:**
boolean - The value of  l1.Ordinal >= l2.Ordinal 
### op_LessThan(LogLevel l1, LogLevel l2) {#op-LessThan-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_LessThan(LogLevel l1, LogLevel l2)
```


Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is less than the second one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | The first level. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | The second level. |

**Returns:**
boolean - The value of  l1.Ordinal < l2.Ordinal 
### op_LessThanOrEqual(LogLevel l1, LogLevel l2) {#op-LessThanOrEqual-com.aspose.email.LogLevel-com.aspose.email.LogLevel-}
```
public static boolean op_LessThanOrEqual(LogLevel l1, LogLevel l2)
```


Compares two [LogLevel](../../com.aspose.email/loglevel) objects and returns a value indicating whether the first one is less than or equal to the second one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| l1 | [LogLevel](../../com.aspose.email/loglevel) | The first level. |
| l2 | [LogLevel](../../com.aspose.email/loglevel) | The second level. |

**Returns:**
boolean - The value of  l1.Ordinal <= l2.Ordinal 
### toString() {#toString--}
```
public String toString()
```


Returns a string representation of the log level.

**Returns:**
java.lang.String - Log level name.
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

