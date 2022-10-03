---
title: ItemMovedEventArgs
second_title: Aspose.Email for Java API Reference
description: Provides data for the  event
type: docs
weight: 341
url: /java/com.aspose.email/itemmovedeventargs/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.EventArgs
```
public class ItemMovedEventArgs extends System.EventArgs
```

Provides data for the [FolderInfo.ItemMovedDelegate](../../com.aspose.email/folderinfo\#ItemMovedDelegate) event
## Constructors

| Constructor | Description |
| --- | --- |
| [ItemMovedEventArgs(MessageInfo message)](#ItemMovedEventArgs-com.aspose.email.MessageInfo-) | Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class. |
| [ItemMovedEventArgs(FolderInfo folder)](#ItemMovedEventArgs-com.aspose.email.FolderInfo-) | Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class. |
| [ItemMovedEventArgs(String entryId, MapiPropertyCollection properties)](#ItemMovedEventArgs-java.lang.String-com.aspose.email.MapiPropertyCollection-) | Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class. |
## Methods

| Method | Description |
| --- | --- |
| [getItemProperties()](#getItemProperties--) | Gets the item properties that has been moved. |
| [getEntryId()](#getEntryId--) | Gets the string that represents the EntryId of the moved message. |
| [getDestinationFolder()](#getDestinationFolder--) | Gets the destination folder. |
| [isMessage()](#isMessage--) | Return true, if entry refers to a Message |
| [isFolder()](#isFolder--) | Return true, if entry refers to a Folder |
### ItemMovedEventArgs(MessageInfo message) {#ItemMovedEventArgs-com.aspose.email.MessageInfo-}
```
public ItemMovedEventArgs(MessageInfo message)
```


Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MessageInfo](../../com.aspose.email/messageinfo) | The message. |

### ItemMovedEventArgs(FolderInfo folder) {#ItemMovedEventArgs-com.aspose.email.FolderInfo-}
```
public ItemMovedEventArgs(FolderInfo folder)
```


Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| folder | [FolderInfo](../../com.aspose.email/folderinfo) | The folder. |

### ItemMovedEventArgs(String entryId, MapiPropertyCollection properties) {#ItemMovedEventArgs-java.lang.String-com.aspose.email.MapiPropertyCollection-}
```
public ItemMovedEventArgs(String entryId, MapiPropertyCollection properties)
```


Initializes a new instance of the [ItemMovedEventArgs](../../com.aspose.email/itemmovedeventargs) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| entryId | java.lang.String | The entry identifier. |
| properties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | The properties. |

### getItemProperties() {#getItemProperties--}
```
public final MapiPropertyCollection getItemProperties()
```


Gets the item properties that has been moved.

Value: The message.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getEntryId() {#getEntryId--}
```
public final String getEntryId()
```


Gets the string that represents the EntryId of the moved message.

Value: The entry id.

**Returns:**
java.lang.String
### getDestinationFolder() {#getDestinationFolder--}
```
public final FolderInfo getDestinationFolder()
```


Gets the destination folder.

Value: The destination folder.

**Returns:**
[FolderInfo](../../com.aspose.email/folderinfo)
### isMessage() {#isMessage--}
```
public final boolean isMessage()
```


Return true, if entry refers to a Message

**Returns:**
boolean
### isFolder() {#isFolder--}
```
public final boolean isFolder()
```


Return true, if entry refers to a Folder

**Returns:**
boolean
