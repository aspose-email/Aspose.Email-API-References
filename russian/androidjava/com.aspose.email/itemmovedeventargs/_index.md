---
title: ItemMovedEventArgs
second_title: Aspose.Email for Android via Java API Reference
description: Предоставляет данные для события
type: docs
weight: 169
url: /ru/androidjava/com.aspose.email/itemmovedeventargs/
---

**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ItemMovedEventArgs extends System.EventArgs
```

Provides data for the [FolderInfo.ItemMovedDelegate](../../com.aspose.email/folderinfo\#ItemMovedDelegate) event
## Constructors

| Constructor | Описание |
| --- | --- |
| [ItemMovedEventArgs(MessageInfo message)](#ItemMovedEventArgs-com.aspose.email.MessageInfo-) | Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class. |
| [ItemMovedEventArgs(FolderInfo folder)](#ItemMovedEventArgs-com.aspose.email.FolderInfo-) | Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class. |
| [ItemMovedEventArgs(String entryId, MapiPropertyCollection properties)](#ItemMovedEventArgs-java.lang.String-com.aspose.email.MapiPropertyCollection-) | Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class. |
## Поля

| Поле | Описание |
| --- | --- |
| [Empty](#Empty) |  |
## Methods

| Method | Описание |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDestinationFolder()](#getDestinationFolder--) | Gets the destination folder. |
| [getEntryId()](#getEntryId--) | Gets the string that represents the EntryId of the moved message. |
| [getItemProperties()](#getItemProperties--) | Gets the item properties that has been moved. |
| [hashCode()](#hashCode--) |  |
| [isFolder()](#isFolder--) | Return true, if entry refers to a Folder |
| [isMessage()](#isMessage--) | Return true, if entry refers to a Message |
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


Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| message | [MessageInfo](../../com.aspose.email/messageinfo) | Сообщение. |

### ItemMovedEventArgs(FolderInfo folder) {#ItemMovedEventArgs-com.aspose.email.FolderInfo-}
```
public ItemMovedEventArgs(FolderInfo folder)
```


Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| folder | [FolderInfo](../../com.aspose.email/folderinfo) | The folder. |

### ItemMovedEventArgs(String entryId, MapiPropertyCollection properties) {#ItemMovedEventArgs-java.lang.String-com.aspose.email.MapiPropertyCollection-}
```
public ItemMovedEventArgs(String entryId, MapiPropertyCollection properties)
```


Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class.

**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| entryId | java.lang.String | The entry identifier. |
| properties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | The properties. |

### Empty {#Empty}
```
public static final System.EventArgs Empty
```


### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Описание |
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


Gets the destination folder.

Значение: Папка назначения.

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo)
### getEntryId() {#getEntryId--}
```
public final String getEntryId()
```


Gets the string that represents the EntryId of the moved message.

Значение: Идентификатор записи.

**Returns:**
java.lang.String
### getItemProperties() {#getItemProperties--}
```
public final MapiPropertyCollection getItemProperties()
```


Gets the item properties that has been moved.

Значение: Сообщение.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
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


Return true, if entry refers to a Folder

**Returns:**
boolean
### isMessage() {#isMessage--}
```
public final boolean isMessage()
```


Return true, if entry refers to a Message

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
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Описание |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

