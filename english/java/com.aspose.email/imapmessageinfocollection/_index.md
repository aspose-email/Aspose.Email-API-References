---
title: ImapMessageInfoCollection
second_title: Aspose.Email for Java API Reference
description:  Provides a container for a collection of  objects
type: docs
weight: 316
url: /java/com.aspose.email/imapmessageinfocollection/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.Collections.ObjectModel.Collection, [com.aspose.email.ImapMessageInfoCollectionBase](../../com.aspose.email/imapmessageinfocollectionbase)

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericList, com.aspose.ms.System.Collections.Generic.IGenericCollection, com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public final class ImapMessageInfoCollection extends ImapMessageInfoCollectionBase implements System.Collections.Generic.IGenericList<ImapMessageInfo>, System.Collections.Generic.IGenericCollection<ImapMessageInfo>, System.Collections.Generic.IGenericEnumerable<ImapMessageInfo>
```

Provides a container for a collection of [ImapMessageInfo](../../com.aspose.email/imapmessageinfo) objects
## Constructors

| Constructor | Description |
| --- | --- |
| [ImapMessageInfoCollection()](#ImapMessageInfoCollection--) | Initializes a new instance of the ImapMessageCollection class. |
| [ImapMessageInfoCollection(Iterable<ImapMessageInfo> messageInfoEn)](#ImapMessageInfoCollection-java.lang.Iterable-com.aspose.email.ImapMessageInfo--) | Initializes a new instance of the ImapMessageCollection class |
## Methods

| Method | Description |
| --- | --- |
| [add(ImapMessageInfo item)](#add-com.aspose.email.ImapMessageInfo-) | Adds the ImapMessageInfo to the ImapMessageCollection. |
| [addRange(Iterable<ImapMessageInfo> messageInfos)](#addRange-java.lang.Iterable-com.aspose.email.ImapMessageInfo--) | Adds the enumeration of ImapMessageInfo objects to the end of the collection |
| [remove(ImapMessageInfo item)](#remove-com.aspose.email.ImapMessageInfo-) | Remove specifed ImapMessageInfo object from this collection. |
| [removeAt(int index)](#removeAt-int-) | Remove a ImapMessageInfo in specified index from this collection. |
| [insert(int index, ImapMessageInfo item)](#insert-int-com.aspose.email.ImapMessageInfo-) | Insert the specified ImapMessagInfo object at the specified index. |
| [to_(ImapMessageInfoCollection messageInfoCol)](#to--com.aspose.email.ImapMessageInfoCollection-) | Converts collection of ImapMessageInfo to array |
| [to_ImapMessageInfoCollection(ImapMessageInfo[] messageInfoArr)](#to-ImapMessageInfoCollection-com.aspose.email.ImapMessageInfo---) | Converts array of ImapMessageInfo to collection |
| [to_List(ImapMessageInfoCollection messageInfoCol)](#to-List-com.aspose.email.ImapMessageInfoCollection-) | Converts collection of ImapMessageInfo to list |
| [to_ImapMessageInfoCollection(System.Collections.Generic.List<ImapMessageInfo> messageInfoLst)](#to-ImapMessageInfoCollection-com.aspose.ms.System.Collections.Generic.List-com.aspose.email.ImapMessageInfo--) | Converts list of ImapMessageInfo to collection |
| [getSyncRoot()](#getSyncRoot--) | Gets an object that can be used to synchronize access to the collection. |
| [getExceptions()](#getExceptions--) | Gets collection of exceptions, that occurred during message processing. |
### ImapMessageInfoCollection() {#ImapMessageInfoCollection--}
```
public ImapMessageInfoCollection()
```


Initializes a new instance of the ImapMessageCollection class.

### ImapMessageInfoCollection(Iterable<ImapMessageInfo> messageInfoEn) {#ImapMessageInfoCollection-java.lang.Iterable-com.aspose.email.ImapMessageInfo--}
```
public ImapMessageInfoCollection(Iterable<ImapMessageInfo> messageInfoEn)
```


Initializes a new instance of the ImapMessageCollection class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoEn | java.lang.Iterable<com.aspose.email.ImapMessageInfo> | initial value |

### add(ImapMessageInfo item) {#add-com.aspose.email.ImapMessageInfo-}
```
public final void add(ImapMessageInfo item)
```


Adds the ImapMessageInfo to the ImapMessageCollection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ImapMessageInfo](../../com.aspose.email/imapmessageinfo) | The ImapMessageInfo to be added. |

### addRange(Iterable<ImapMessageInfo> messageInfos) {#addRange-java.lang.Iterable-com.aspose.email.ImapMessageInfo--}
```
public final void addRange(Iterable<ImapMessageInfo> messageInfos)
```


Adds the enumeration of ImapMessageInfo objects to the end of the collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfos | java.lang.Iterable<com.aspose.email.ImapMessageInfo> |  |

### remove(ImapMessageInfo item) {#remove-com.aspose.email.ImapMessageInfo-}
```
public final boolean remove(ImapMessageInfo item)
```


Remove specifed ImapMessageInfo object from this collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [ImapMessageInfo](../../com.aspose.email/imapmessageinfo) | The ImapMessageInfo object to be remove. |

**Returns:**
boolean - False if this collection doesn't contains specified object.True if removed successfully.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Remove a ImapMessageInfo in specified index from this collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index of the message to be remove. |

### insert(int index, ImapMessageInfo item) {#insert-int-com.aspose.email.ImapMessageInfo-}
```
public final void insert(int index, ImapMessageInfo item)
```


Insert the specified ImapMessagInfo object at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | The index that the specified object will be inserted into. |
| item | [ImapMessageInfo](../../com.aspose.email/imapmessageinfo) | The ImapMessagInfo object to be inserted. |

### to_(ImapMessageInfoCollection messageInfoCol) {#to--com.aspose.email.ImapMessageInfoCollection-}
```
public static ImapMessageInfo[] to_(ImapMessageInfoCollection messageInfoCol)
```


Converts collection of ImapMessageInfo to array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoCol | [ImapMessageInfoCollection](../../com.aspose.email/imapmessageinfocollection) | Collection of ImapMessageInfo to convert |

**Returns:**
com.aspose.email.ImapMessageInfo[] - Array of ImapMessageInfo
### to_ImapMessageInfoCollection(ImapMessageInfo[] messageInfoArr) {#to-ImapMessageInfoCollection-com.aspose.email.ImapMessageInfo---}
```
public static ImapMessageInfoCollection to_ImapMessageInfoCollection(ImapMessageInfo[] messageInfoArr)
```


Converts array of ImapMessageInfo to collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoArr | com.aspose.email.ImapMessageInfo[] | Array of ImapMessageInfo to convert |

**Returns:**
[ImapMessageInfoCollection](../../com.aspose.email/imapmessageinfocollection) - Collection of ImapMessageInfo
### to_List(ImapMessageInfoCollection messageInfoCol) {#to-List-com.aspose.email.ImapMessageInfoCollection-}
```
public static System.Collections.Generic.List<ImapMessageInfo> to_List(ImapMessageInfoCollection messageInfoCol)
```


Converts collection of ImapMessageInfo to list

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoCol | [ImapMessageInfoCollection](../../com.aspose.email/imapmessageinfocollection) | Collection of ImapMessageInfo to convert |

**Returns:**
com.aspose.ms.System.Collections.Generic.List<com.aspose.email.ImapMessageInfo> - List of ImapMessageInfo
### to_ImapMessageInfoCollection(System.Collections.Generic.List<ImapMessageInfo> messageInfoLst) {#to-ImapMessageInfoCollection-com.aspose.ms.System.Collections.Generic.List-com.aspose.email.ImapMessageInfo--}
```
public static ImapMessageInfoCollection to_ImapMessageInfoCollection(System.Collections.Generic.List<ImapMessageInfo> messageInfoLst)
```


Converts list of ImapMessageInfo to collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| messageInfoLst | com.aspose.ms.System.Collections.Generic.List<com.aspose.email.ImapMessageInfo> | List of ImapMessageInfo to convert |

**Returns:**
[ImapMessageInfoCollection](../../com.aspose.email/imapmessageinfocollection) - Collection of ImapMessageInfo
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Gets an object that can be used to synchronize access to the collection.

**Returns:**
java.lang.Object
### getExceptions() {#getExceptions--}
```
public final List<ElementProcessingException> getExceptions()
```


Gets collection of exceptions, that occurred during message processing.

**Returns:**
java.util.List<com.aspose.email.ElementProcessingException>
