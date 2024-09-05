---
title: AsyncCommandResultEventArgs
second_title: Aspose.Email for Java API Reference
description: is containing event data.
type: docs
weight: 64
url: /java/com.aspose.email/asynccommandresulteventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class AsyncCommandResultEventArgs extends System.EventArgs
```

[AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) is containing event data.
## Constructors

| Constructor | Description |
| --- | --- |
| [AsyncCommandResultEventArgs()](#AsyncCommandResultEventArgs--) | Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class. |
| [AsyncCommandResultEventArgs(int result)](#AsyncCommandResultEventArgs-int-) | Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class. |
| [AsyncCommandResultEventArgs(int result, Throwable error)](#AsyncCommandResultEventArgs-int-java.lang.Throwable-) | Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class. |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getError()](#getError--) | Operation error |
| [getResult()](#getResult--) | Operation state |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AsyncCommandResultEventArgs() {#AsyncCommandResultEventArgs--}
```
public AsyncCommandResultEventArgs()
```


Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class.

### AsyncCommandResultEventArgs(int result) {#AsyncCommandResultEventArgs-int-}
```
public AsyncCommandResultEventArgs(int result)
```


Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | int | Contains operation result |

### AsyncCommandResultEventArgs(int result, Throwable error) {#AsyncCommandResultEventArgs-int-java.lang.Throwable-}
```
public AsyncCommandResultEventArgs(int result, Throwable error)
```


Initializes a new instance of the [AsyncCommandResultEventArgs](../../com.aspose.email/asynccommandresulteventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| result | int | Contains operation state |
| error | java.lang.Throwable | Contains operation error |

### Empty {#Empty}
```
public static final System.EventArgs Empty
```


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
### getError() {#getError--}
```
public final Throwable getError()
```


Operation error

**Returns:**
java.lang.Throwable
### getResult() {#getResult--}
```
public final int getResult()
```


Operation state

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

