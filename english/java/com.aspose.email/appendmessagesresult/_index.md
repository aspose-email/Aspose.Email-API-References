---
title: AppendMessagesResult
second_title: Aspose.Email for Java API Reference
description: Contains result of operation with messages
type: docs
weight: 28
url: /java/com.aspose.email/appendmessagesresult/
---

**Inheritance:**
java.lang.Object
```
public class AppendMessagesResult
```

Contains result of operation with messages
## Constructors

| Constructor | Description |
| --- | --- |
| [AppendMessagesResult()](#AppendMessagesResult--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFailed()](#getFailed--) | Gets mail messages that have been handled with errors |
| [getNotHandled()](#getNotHandled--) | Gets mail messages that have not been handled |
| [getSucceeded()](#getSucceeded--) | Gets mail messages that have been handled successfully |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AppendMessagesResult() {#AppendMessagesResult--}
```
public AppendMessagesResult()
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
### getFailed() {#getFailed--}
```
public final System.Collections.Generic.Dictionary<MailMessage,RuntimeException> getFailed()
```


Gets mail messages that have been handled with errors

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.email.MailMessage,java.lang.RuntimeException>
### getNotHandled() {#getNotHandled--}
```
public final List<MailMessage> getNotHandled()
```


Gets mail messages that have not been handled

**Returns:**
java.util.List<com.aspose.email.MailMessage>
### getSucceeded() {#getSucceeded--}
```
public final System.Collections.Generic.Dictionary<MailMessage,String> getSucceeded()
```


Gets mail messages that have been handled successfully

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<com.aspose.email.MailMessage,java.lang.String>
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

