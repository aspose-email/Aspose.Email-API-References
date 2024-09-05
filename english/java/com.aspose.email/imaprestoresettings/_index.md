---
title: ImapRestoreSettings
second_title: Aspose.Email for Java API Reference
description: The settings for the ImapClient.Restore method
type: docs
weight: 331
url: /java/com.aspose.email/imaprestoresettings/
---

**Inheritance:**
java.lang.Object
```
public class ImapRestoreSettings
```

The settings for the ImapClient.Restore method
## Constructors

| Constructor | Description |
| --- | --- |
| [ImapRestoreSettings()](#ImapRestoreSettings--) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBeforeItemCallback()](#getBeforeItemCallback--) | The callback called when the next item (message or folder) is processed. |
| [getClass()](#getClass--) |  |
| [getConnection()](#getConnection--) | Connection to a server. |
| [getFolders()](#getFolders--) | A folders to be restored. |
| [getNumberOfAttemptsToRrepeat()](#getNumberOfAttemptsToRrepeat--) | Gets or sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. |
| [getOptions()](#getOptions--) | Restore options. |
| [getRecursive()](#getRecursive--) | Indicates that nested folders should be also restored |
| [getRemoveNonexistentFolders()](#getRemoveNonexistentFolders--) | Indicates that mail folders, which do not have the equal folders in the personal storage, should be removed |
| [getRemoveNonexistentItems()](#getRemoveNonexistentItems--) | Indicates that mail items, which do not have the equal items in the personal storage, should be removed |
| [getRestoreConnection()](#getRestoreConnection--) | Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [getTimeoutBetweenAttempts()](#getTimeoutBetweenAttempts--) | Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBeforeItemCallback(BeforeItemCallback value)](#setBeforeItemCallback-com.aspose.email.BeforeItemCallback-) | The callback called when the next item (message or folder) is processed. |
| [setConnection(IConnection value)](#setConnection-com.aspose.email.IConnection-) | Connection to a server. |
| [setFolders(ImapFolderInfoCollection value)](#setFolders-com.aspose.email.ImapFolderInfoCollection-) | A folders to be restored. |
| [setNumberOfAttemptsToRrepeat(int value)](#setNumberOfAttemptsToRrepeat-int-) | Gets or sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. |
| [setOptions(int value)](#setOptions-int-) | Restore options. |
| [setRecursive(boolean value)](#setRecursive-boolean-) | Indicates that nested folders should be also restored |
| [setRemoveNonexistentFolders(boolean value)](#setRemoveNonexistentFolders-boolean-) | Indicates that mail folders, which do not have the equal folders in the personal storage, should be removed |
| [setRemoveNonexistentItems(boolean value)](#setRemoveNonexistentItems-boolean-) | Indicates that mail items, which do not have the equal items in the personal storage, should be removed |
| [setRestoreConnection(boolean value)](#setRestoreConnection-boolean-) | Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [setTimeoutBetweenAttempts(int value)](#setTimeoutBetweenAttempts-int-) | Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option. |
| [toString()](#toString--) |  |
| [to_RestoreSettings(int options)](#to-RestoreSettings-int-) | Converts enumerable options to class |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ImapRestoreSettings() {#ImapRestoreSettings--}
```
public ImapRestoreSettings()
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
### getBeforeItemCallback() {#getBeforeItemCallback--}
```
public final BeforeItemCallback getBeforeItemCallback()
```


The callback called when the next item (message or folder) is processed.

**Returns:**
[BeforeItemCallback](../../com.aspose.email/beforeitemcallback)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getConnection() {#getConnection--}
```
public final IConnection getConnection()
```


Connection to a server.

**Returns:**
[IConnection](../../com.aspose.email/iconnection)
### getFolders() {#getFolders--}
```
public final ImapFolderInfoCollection getFolders()
```


A folders to be restored.

**Returns:**
[ImapFolderInfoCollection](../../com.aspose.email/imapfolderinfocollection)
### getNumberOfAttemptsToRrepeat() {#getNumberOfAttemptsToRrepeat--}
```
public final int getNumberOfAttemptsToRrepeat()
```


Gets or sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE\_1\_1\_0243 FETCH 219 (BODY) AE\_1\_1\_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again.

**Returns:**
int
### getOptions() {#getOptions--}
```
public final int getOptions()
```


Restore options.

**Returns:**
int
### getRecursive() {#getRecursive--}
```
public final boolean getRecursive()
```


Indicates that nested folders should be also restored

**Returns:**
boolean
### getRemoveNonexistentFolders() {#getRemoveNonexistentFolders--}
```
public final boolean getRemoveNonexistentFolders()
```


Indicates that mail folders, which do not have the equal folders in the personal storage, should be removed

**Returns:**
boolean
### getRemoveNonexistentItems() {#getRemoveNonexistentItems--}
```
public final boolean getRemoveNonexistentItems()
```


Indicates that mail items, which do not have the equal items in the personal storage, should be removed

**Returns:**
boolean
### getRestoreConnection() {#getRestoreConnection--}
```
public final boolean getRestoreConnection()
```


Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option.

**Returns:**
boolean
### getTimeoutBetweenAttempts() {#getTimeoutBetweenAttempts--}
```
public final int getTimeoutBetweenAttempts()
```


Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option.

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




### setBeforeItemCallback(BeforeItemCallback value) {#setBeforeItemCallback-com.aspose.email.BeforeItemCallback-}
```
public final void setBeforeItemCallback(BeforeItemCallback value)
```


The callback called when the next item (message or folder) is processed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [BeforeItemCallback](../../com.aspose.email/beforeitemcallback) |  |

### setConnection(IConnection value) {#setConnection-com.aspose.email.IConnection-}
```
public final void setConnection(IConnection value)
```


Connection to a server.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IConnection](../../com.aspose.email/iconnection) |  |

### setFolders(ImapFolderInfoCollection value) {#setFolders-com.aspose.email.ImapFolderInfoCollection-}
```
public final void setFolders(ImapFolderInfoCollection value)
```


A folders to be restored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ImapFolderInfoCollection](../../com.aspose.email/imapfolderinfocollection) |  |

### setNumberOfAttemptsToRrepeat(int value) {#setNumberOfAttemptsToRrepeat-int-}
```
public final void setNumberOfAttemptsToRrepeat(int value)
```


Gets or sets value which defines number of attempts to repeat failed operation In case of some IMAP command inside backup operation returns failed result, IMAP client tries to repeat this operation again according to defined quantity of times. For instance if FETCH operation returns error AE\_1\_1\_0243 FETCH 219 (BODY) AE\_1\_1\_0243 NO[UNAVAILABLE] FETCH Service is temporarily not available Client tries to execute it again.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setOptions(int value) {#setOptions-int-}
```
public final void setOptions(int value)
```


Restore options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setRecursive(boolean value) {#setRecursive-boolean-}
```
public final void setRecursive(boolean value)
```


Indicates that nested folders should be also restored

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRemoveNonexistentFolders(boolean value) {#setRemoveNonexistentFolders-boolean-}
```
public final void setRemoveNonexistentFolders(boolean value)
```


Indicates that mail folders, which do not have the equal folders in the personal storage, should be removed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRemoveNonexistentItems(boolean value) {#setRemoveNonexistentItems-boolean-}
```
public final void setRemoveNonexistentItems(boolean value)
```


Indicates that mail items, which do not have the equal items in the personal storage, should be removed

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setRestoreConnection(boolean value) {#setRestoreConnection-boolean-}
```
public final void setRestoreConnection(boolean value)
```


Gets or sets value which defines if connection has to be restored in case if server closes connection forcibly This option has to be used together with NumberOfAttemptsToRrepeat option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setTimeoutBetweenAttempts(int value) {#setTimeoutBetweenAttempts-int-}
```
public final void setTimeoutBetweenAttempts(int value)
```


Gets or sets value which defines timeout (in milliseconds) between attemptions to execute operation again This option has to be used together with NumberOfAttemptsToRrepeat option.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### to_RestoreSettings(int options) {#to-RestoreSettings-int-}
```
public static ImapRestoreSettings to_RestoreSettings(int options)
```


Converts enumerable options to class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | int | Options to convert |

**Returns:**
[ImapRestoreSettings](../../com.aspose.email/imaprestoresettings)
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

