---
title: MessageAddedEventArgs
second_title: Aspose.Email for Java API Reference
description: Provides data for the  event
type: docs
weight: 492
url: /java/com.aspose.email/messageaddedeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class MessageAddedEventArgs extends System.EventArgs
```

Provides data for the [FolderInfo.MessageAddedDelegate](../../com.aspose.email/folderinfo\#MessageAddedDelegate) event
## Constructors

| Constructor | Description |
| --- | --- |
| [MessageAddedEventArgs(String entryId, MapiMessage message)](#MessageAddedEventArgs-java.lang.String-com.aspose.email.MapiMessage-) | Initializes a new instance of the [MessageAddedEventArgs](../../com.aspose.email/messageaddedeventargs) class. |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEntryId()](#getEntryId--) | Gets the string that represents the EntryId of the added message. |
| [getMessage()](#getMessage--) | Gets the message that has been added. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageAddedEventArgs(String entryId, MapiMessage message) {#MessageAddedEventArgs-java.lang.String-com.aspose.email.MapiMessage-}
```
public MessageAddedEventArgs(String entryId, MapiMessage message)
```


Initializes a new instance of the [MessageAddedEventArgs](../../com.aspose.email/messageaddedeventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry id. |
| message | [MapiMessage](../../com.aspose.email/mapimessage) | The message. |

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
### getEntryId() {#getEntryId--}
```
public final String getEntryId()
```


Gets the string that represents the EntryId of the added message.

Value: The entry id.

**Returns:**
java.lang.String
### getMessage() {#getMessage--}
```
public final MapiMessage getMessage()
```


Gets the message that has been added.

Value: The message.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage)
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

