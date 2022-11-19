---
title: SyncFolderResult
second_title: Aspose.Email for Java API Reference
description: Result for SyncFolder operation
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getChangedFolders()](#getChangedFolders--) | Collection of changed subfolders in the specified folder. |
| [getChangedItems()](#getChangedItems--) | Collection of changed items in the specified folder. |
| [getClass()](#getClass--) |  |
| [getDeletedFolders()](#getDeletedFolders--) | The array of subfolders in the specified folder that have been deleted. |
| [getDeletedItems()](#getDeletedItems--) | The array of items that have been deleted. |
| [getNewFolders()](#getNewFolders--) | Collection of new subfolders in the specified folder. |
| [getNewItems()](#getNewItems--) | Collection of new items in the specified folder. |
| [getReadFlagChanged()](#getReadFlagChanged--) | Collection of pairs of item uri and read-flag for items whose 'read' flag has been changed. |
| [getSyncObject()](#getSyncObject--) | Synchronization object for next synchronization operation. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getChangedFolders() {#getChangedFolders--}
```
public final ExchangeFolderInfoCollection getChangedFolders()
```


Collection of changed subfolders in the specified folder.

**Returns:**
[ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection)
### getChangedItems() {#getChangedItems--}
```
public final ExchangeMessageInfoCollection getChangedItems()
```


Collection of changed items in the specified folder.

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDeletedFolders() {#getDeletedFolders--}
```
public final String[] getDeletedFolders()
```


The array of subfolders in the specified folder that have been deleted.

**Returns:**
java.lang.String[]
### getDeletedItems() {#getDeletedItems--}
```
public final String[] getDeletedItems()
```


The array of items that have been deleted.

**Returns:**
java.lang.String[]
### getNewFolders() {#getNewFolders--}
```
public final ExchangeFolderInfoCollection getNewFolders()
```


Collection of new subfolders in the specified folder.

**Returns:**
[ExchangeFolderInfoCollection](../../com.aspose.email/exchangefolderinfocollection)
### getNewItems() {#getNewItems--}
```
public final ExchangeMessageInfoCollection getNewItems()
```


Collection of new items in the specified folder.

**Returns:**
[ExchangeMessageInfoCollection](../../com.aspose.email/exchangemessageinfocollection)
### getReadFlagChanged() {#getReadFlagChanged--}
```
public final System.Collections.Generic.Dictionary<String,Boolean> getReadFlagChanged()
```


Collection of pairs of item uri and read-flag for items whose 'read' flag has been changed.

**Returns:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.Boolean>
### getSyncObject() {#getSyncObject--}
```
public final SyncState getSyncObject()
```


Synchronization object for next synchronization operation.

**Returns:**
[SyncState](../../com.aspose.email/syncstate)
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

