---
title: ImapMonitoringEventArgs
second_title: Aspose.Email for Java API Reference
description: Class contains monitoring event data.
type: docs
weight: 338
url: /java/com.aspose.email/imapmonitoringeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ImapMonitoringEventArgs extends System.EventArgs
```

Class contains monitoring event data.
## Constructors

| Constructor | Description |
| --- | --- |
| [ImapMonitoringEventArgs(String folderName, ImapMessageInfo[] newMessages, ImapMessageInfo[] deletedMessages)](#ImapMonitoringEventArgs-java.lang.String-com.aspose.email.ImapMessageInfo---com.aspose.email.ImapMessageInfo---) | Initializes a new instance of the [ImapMonitoringEventArgs](../../com.aspose.email/imapmonitoringeventargs) class |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeletedMessages()](#getDeletedMessages--) | Gets deleted messages |
| [getFolderName()](#getFolderName--) | Gets specified folder for monitoring operation. |
| [getNewMessages()](#getNewMessages--) | Gets new messages |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImapMonitoringEventArgs(String folderName, ImapMessageInfo[] newMessages, ImapMessageInfo[] deletedMessages) {#ImapMonitoringEventArgs-java.lang.String-com.aspose.email.ImapMessageInfo---com.aspose.email.ImapMessageInfo---}
```
public ImapMonitoringEventArgs(String folderName, ImapMessageInfo[] newMessages, ImapMessageInfo[] deletedMessages)
```


Initializes a new instance of the [ImapMonitoringEventArgs](../../com.aspose.email/imapmonitoringeventargs) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folderName | java.lang.String | specified folder for monitoring operation |
| newMessages | [ImapMessageInfo\[\]](../../com.aspose.email/imapmessageinfo) | Contains information about new messages |
| deletedMessages | [ImapMessageInfo\[\]](../../com.aspose.email/imapmessageinfo) | Contains information about deleted messages |

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
### getDeletedMessages() {#getDeletedMessages--}
```
public final ImapMessageInfo[] getDeletedMessages()
```


Gets deleted messages

**Returns:**
com.aspose.email.ImapMessageInfo[]
### getFolderName() {#getFolderName--}
```
public final String getFolderName()
```


Gets specified folder for monitoring operation.

**Returns:**
java.lang.String
### getNewMessages() {#getNewMessages--}
```
public final ImapMessageInfo[] getNewMessages()
```


Gets new messages

**Returns:**
com.aspose.email.ImapMessageInfo[]
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

