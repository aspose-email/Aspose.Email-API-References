---
title: ServerNotificationEventArgs
second_title: Aspose.Email for Java API Reference
description: Contains event data for server notification.
type: docs
weight: 655
url: /java/com.aspose.email/servernotificationeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ServerNotificationEventArgs extends System.EventArgs
```

Contains event data for server notification.
## Constructors

| Constructor | Description |
| --- | --- |
| [ServerNotificationEventArgs(int folder, int eventTypes)](#ServerNotificationEventArgs-int-int-) | Initializes a new instance of the [ServerNotificationEventArgs](../../com.aspose.email/servernotificationeventargs) class |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEventTypes()](#getEventTypes--) | Specifies event type |
| [getFolder()](#getFolder--) | Specifies the known Exchange server folder. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ServerNotificationEventArgs(int folder, int eventTypes) {#ServerNotificationEventArgs-int-int-}
```
public ServerNotificationEventArgs(int folder, int eventTypes)
```


Initializes a new instance of the [ServerNotificationEventArgs](../../com.aspose.email/servernotificationeventargs) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | int | Specifies the known Exchange server folders. |
| eventTypes | int | Specifies event type |

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
### getEventTypes() {#getEventTypes--}
```
public final int getEventTypes()
```


Specifies event type

**Returns:**
int
### getFolder() {#getFolder--}
```
public final int getFolder()
```


Specifies the known Exchange server folder.

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

