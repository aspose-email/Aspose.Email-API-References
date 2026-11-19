---
title: ItemMovedEventArgs
second_title: Aspose.Email for Java API Reference
description: Provides data for the  event.
type: docs
weight: 362
url: /java/com.aspose.email/itemmovedeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ItemMovedEventArgs extends System.EventArgs
```

Provides data for the [FolderInfo.ItemMoved](../../com.aspose.email/folderinfo\#ItemMoved) event.
## Constructors

| Constructor | Description |
| --- | --- |
| [ItemMovedEventArgs(MessageInfo message)](#ItemMovedEventArgs-com.aspose.email.MessageInfo-) | Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class for a moved message. |
| [ItemMovedEventArgs(FolderInfo folder)](#ItemMovedEventArgs-com.aspose.email.FolderInfo-) | Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class for a moved folder. |
| [ItemMovedEventArgs(String entryId, MapiPropertyCollection properties)](#ItemMovedEventArgs-java.lang.String-com.aspose.email.MapiPropertyCollection-) | Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class for an item given by its entry ID and properties. |
## Fields

| Field | Description |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDestinationFolder()](#getDestinationFolder--) | Gets the folder the item was moved to. |
| [getEntryId()](#getEntryId--) | Gets the entry ID of the moved item. |
| [getItemProperties()](#getItemProperties--) | Gets the properties of the moved item. |
| [hashCode()](#hashCode--) |  |
| [isFolder()](#isFolder--) | Gets a value indicating whether the moved item is a folder. |
| [isMessage()](#isMessage--) | Gets a value indicating whether the moved item is a message. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ItemMovedEventArgs(MessageInfo message) {#ItemMovedEventArgs-com.aspose.email.MessageInfo-}
```
public ItemMovedEventArgs(MessageInfo message)
```


Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class for a moved message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MessageInfo](../../com.aspose.email/messageinfo) | The moved message. |

### ItemMovedEventArgs(FolderInfo folder) {#ItemMovedEventArgs-com.aspose.email.FolderInfo-}
```
public ItemMovedEventArgs(FolderInfo folder)
```


Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class for a moved folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | [FolderInfo](../../com.aspose.email/folderinfo) | The moved folder. |

### ItemMovedEventArgs(String entryId, MapiPropertyCollection properties) {#ItemMovedEventArgs-java.lang.String-com.aspose.email.MapiPropertyCollection-}
```
public ItemMovedEventArgs(String entryId, MapiPropertyCollection properties)
```


Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class for an item given by its entry ID and properties.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry ID of the moved item. |
| properties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | The properties of the moved item. |

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
### getDestinationFolder() {#getDestinationFolder--}
```
public final FolderInfo getDestinationFolder()
```


Gets the folder the item was moved to.

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo) - The destination folder.
### getEntryId() {#getEntryId--}
```
public final String getEntryId()
```


Gets the entry ID of the moved item.

**Returns:**
java.lang.String - The entry ID.
### getItemProperties() {#getItemProperties--}
```
public final MapiPropertyCollection getItemProperties()
```


Gets the properties of the moved item.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The MAPI properties of the item.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFolder() {#isFolder--}
```
public final boolean isFolder()
```


Gets a value indicating whether the moved item is a folder.

**Returns:**
boolean
### isMessage() {#isMessage--}
```
public final boolean isMessage()
```


Gets a value indicating whether the moved item is a message.

**Returns:**
boolean
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

