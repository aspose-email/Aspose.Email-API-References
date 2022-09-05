---
title: GraphFolderInfo
second_title: Aspose.Email for Java API Reference
description:  Represents information about personal folder.
type: docs
weight: 281
url: /java/com.aspose.email/graphfolderinfo/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.BaseRestObject](../../com.aspose.email/baserestobject)
```
public class GraphFolderInfo extends BaseRestObject
```

Represents information about personal folder.
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphFolderInfo(MapiPropertyCollection properties)](#GraphFolderInfo-com.aspose.email.MapiPropertyCollection-) | Initializes a new instance of the [FolderInfo](../../com.aspose.email/folderinfo) class. |
## Methods

| Method | Description |
| --- | --- |
| [getDisplayName()](#getDisplayName--) | Gets the display name of folder. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Gets the display name of folder. |
| [getContentCount()](#getContentCount--) | Gets the total number of items in the folder. |
| [getContentUnreadCount()](#getContentUnreadCount--) | Gets the number of unread items in the folder. |
| [hasSubFolders()](#hasSubFolders--) | Gets a value indicating whether the Folder object has any subfolders. |
| [getContainerClass()](#getContainerClass--) | Gets container class of the folder object. |
| [getItemId()](#getItemId--) | Gets string representation of entry ID. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### GraphFolderInfo(MapiPropertyCollection properties) {#GraphFolderInfo-com.aspose.email.MapiPropertyCollection-}
```
public GraphFolderInfo(MapiPropertyCollection properties)
```


Initializes a new instance of the [FolderInfo](../../com.aspose.email/folderinfo) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| properties | [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) | MapiProperties for this folder |

### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


Gets the display name of folder.

Value: The display name.

**Returns:**
java.lang.String
### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


Gets the display name of folder.

Value: The display name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentCount() {#getContentCount--}
```
public int getContentCount()
```


Gets the total number of items in the folder.

Value: The content count.

**Returns:**
int
### getContentUnreadCount() {#getContentUnreadCount--}
```
public int getContentUnreadCount()
```


Gets the number of unread items in the folder.

Value: The content unread count.

**Returns:**
int
### hasSubFolders() {#hasSubFolders--}
```
public boolean hasSubFolders()
```


Gets a value indicating whether the Folder object has any subfolders.

Value: The has sub folders.

**Returns:**
boolean
### getContainerClass() {#getContainerClass--}
```
public String getContainerClass()
```


Gets container class of the folder object.

Value: The container class.

**Returns:**
java.lang.String
### getItemId() {#getItemId--}
```
public String getItemId()
```


Gets string representation of entry ID.

Value: The entry id string.

**Returns:**
java.lang.String
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - A string that represents the current object.
