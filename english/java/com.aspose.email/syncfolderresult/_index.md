---
title: SyncFolderResult
second_title: Aspose.Email for Java API Reference
description:  Result for SyncFolder operation
type: docs
weight: 651
url: /java/com.aspose.email/syncfolderresult/
---
**Inheritance:**
java.lang.Object
```
public class SyncFolderResult
```

Result for SyncFolder operation
## Methods

| Method | Description |
| --- | --- |
| [getNewFolders()](#getNewFolders--) | Collection of new subfolders in the specified folder. |
| [getChangedFolders()](#getChangedFolders--) | Collection of changed subfolders in the specified folder. |
| [getDeletedFolders()](#getDeletedFolders--) | The array of subfolders in the specified folder that have been deleted. |
| [getNewItems()](#getNewItems--) | Collection of new items in the specified folder. |
| [getChangedItems()](#getChangedItems--) | Collection of changed items in the specified folder. |
| [getReadFlagChanged()](#getReadFlagChanged--) | Collection of pairs of item uri and read-flag for items whose 'read' flag has been changed. |
| [getDeletedItems()](#getDeletedItems--) | The array of items that have been deleted. |
| [getSyncObject()](#getSyncObject--) | Synchronization object for next synchronization operation. |
### getNewFolders() {#getNewFolders--}
```
public final ExchangeFolderInfoCollection getNewFolders()
```


Collection of new subfolders in the specified folder.

**Returns:**
[ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection)
### getChangedFolders() {#getChangedFolders--}
```
public final ExchangeFolderInfoCollection getChangedFolders()
```


Collection of changed subfolders in the specified folder.

**Returns:**
[ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection)
### getDeletedFolders() {#getDeletedFolders--}
```
public final String[] getDeletedFolders()
```


The array of subfolders in the specified folder that have been deleted.

**Returns:**
java.lang.String[]
### getNewItems() {#getNewItems--}
```
public final ExchangeMessageInfoCollection getNewItems()
```


Collection of new items in the specified folder.

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection)
### getChangedItems() {#getChangedItems--}
```
public final ExchangeMessageInfoCollection getChangedItems()
```


Collection of changed items in the specified folder.

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection)
### getReadFlagChanged() {#getReadFlagChanged--}
```
public final System.Collections.Generic.Dictionary<String,Boolean> getReadFlagChanged()
```


Collection of pairs of item uri and read-flag for items whose 'read' flag has been changed.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Boolean>
### getDeletedItems() {#getDeletedItems--}
```
public final String[] getDeletedItems()
```


The array of items that have been deleted.

**Returns:**
java.lang.String[]
### getSyncObject() {#getSyncObject--}
```
public final SyncState getSyncObject()
```


Synchronization object for next synchronization operation.

**Returns:**
[SyncState](../../com.aspose.email/syncstate)
