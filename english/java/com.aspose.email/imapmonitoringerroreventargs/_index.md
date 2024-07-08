---
title: ImapMonitoringErrorEventArgs
second_title: Aspose.Email for Java API Reference
description: Class contains monitoring error event data.
type: docs
weight: 321
url: /java/com.aspose.email/imapmonitoringerroreventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ImapMonitoringErrorEventArgs extends System.EventArgs
```

Class contains monitoring error event data.
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getError()](#getError--) | IMAP monitoring error. |
| [getFolderName()](#getFolderName--) | Specified folder for monitoring operation. |
| [getMonitoringState()](#getMonitoringState--) | Holds folder monitoring state. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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


IMAP monitoring error.

**Returns:**
java.lang.Throwable
### getFolderName() {#getFolderName--}
```
public final String getFolderName()
```


Specified folder for monitoring operation.

**Returns:**
java.lang.String
### getMonitoringState() {#getMonitoringState--}
```
public final IImapMonitoringState getMonitoringState()
```


Holds folder monitoring state. This object can be used to resume folder monitoring from place where it stopped when error occured. Use ImapClient.resumeMonitoring method.

**Returns:**
[IImapMonitoringState](../../com.aspose.email/iimapmonitoringstate)
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

