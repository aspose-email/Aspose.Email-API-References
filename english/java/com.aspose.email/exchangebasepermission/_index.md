---
title: ExchangeBasePermission
second_title: Aspose.Email for Java API Reference
description: Provides abstract base class for permissions to folders on Exchange Server.
type: docs
weight: 191
url: /java/com.aspose.email/exchangebasepermission/
---

**Inheritance:**
java.lang.Object
```
public abstract class ExchangeBasePermission
```

Provides abstract base class for permissions to folders on Exchange Server.
## Methods

| Method | Description |
| --- | --- |
| [canCreateItems()](#canCreateItems--) | Gets or sets a value indicating whether a client can create items in a folder. |
| [canCreateItems(boolean value)](#canCreateItems-boolean-) | Gets or sets a value indicating whether a client can create items in a folder. |
| [canCreateSubFolders()](#canCreateSubFolders--) | Gets or sets a value indicating whether the client can create subfolders. |
| [canCreateSubFolders(boolean value)](#canCreateSubFolders-boolean-) | Gets or sets a value indicating whether the client can create subfolders. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeleteItems()](#getDeleteItems--) | Gets or sets a value indicating whether the client can delete items. |
| [getEditItems()](#getEditItems--) | Gets or sets a value indicating whether a client can edit items. |
| [getUserInfo()](#getUserInfo--) | Gets or sets a user or a delegate user who has folder access permissions |
| [hashCode()](#hashCode--) |  |
| [isFolderContact()](#isFolderContact--) | Gets or sets a value indicating whether a user is a contact for a folder. |
| [isFolderOwner()](#isFolderOwner--) | Gets or sets a value indicating whether the user is the owner of a folder. |
| [isFolderVisible()](#isFolderVisible--) | Gets or sets a value indicating whether a user can view a folder. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDeleteItems(int value)](#setDeleteItems-int-) | Gets or sets a value indicating whether the client can delete items. |
| [setEditItems(int value)](#setEditItems-int-) | Gets or sets a value indicating whether a client can edit items. |
| [setFolderContact(boolean value)](#setFolderContact-boolean-) | Gets or sets a value indicating whether a user is a contact for a folder. |
| [setFolderOwner(boolean value)](#setFolderOwner-boolean-) | Gets or sets a value indicating whether the user is the owner of a folder. |
| [setFolderVisible(boolean value)](#setFolderVisible-boolean-) | Gets or sets a value indicating whether a user can view a folder. |
| [setUserInfo(ExchangeFolderUserInfo value)](#setUserInfo-com.aspose.email.ExchangeFolderUserInfo-) | Gets or sets a user or a delegate user who has folder access permissions |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### canCreateItems() {#canCreateItems--}
```
public final boolean canCreateItems()
```


Gets or sets a value indicating whether a client can create items in a folder.

**Returns:**
boolean
### canCreateItems(boolean value) {#canCreateItems-boolean-}
```
public final void canCreateItems(boolean value)
```


Gets or sets a value indicating whether a client can create items in a folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### canCreateSubFolders() {#canCreateSubFolders--}
```
public final boolean canCreateSubFolders()
```


Gets or sets a value indicating whether the client can create subfolders.

**Returns:**
boolean
### canCreateSubFolders(boolean value) {#canCreateSubFolders-boolean-}
```
public final void canCreateSubFolders(boolean value)
```


Gets or sets a value indicating whether the client can create subfolders.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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
### getDeleteItems() {#getDeleteItems--}
```
public final int getDeleteItems()
```


Gets or sets a value indicating whether the client can delete items.

**Returns:**
int
### getEditItems() {#getEditItems--}
```
public final int getEditItems()
```


Gets or sets a value indicating whether a client can edit items.

**Returns:**
int
### getUserInfo() {#getUserInfo--}
```
public final ExchangeFolderUserInfo getUserInfo()
```


Gets or sets a user or a delegate user who has folder access permissions

**Returns:**
[ExchangeFolderUserInfo](../../com.aspose.email/exchangefolderuserinfo)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isFolderContact() {#isFolderContact--}
```
public final boolean isFolderContact()
```


Gets or sets a value indicating whether a user is a contact for a folder.

**Returns:**
boolean
### isFolderOwner() {#isFolderOwner--}
```
public final boolean isFolderOwner()
```


Gets or sets a value indicating whether the user is the owner of a folder.

**Returns:**
boolean
### isFolderVisible() {#isFolderVisible--}
```
public final boolean isFolderVisible()
```


Gets or sets a value indicating whether a user can view a folder.

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




### setDeleteItems(int value) {#setDeleteItems-int-}
```
public final void setDeleteItems(int value)
```


Gets or sets a value indicating whether the client can delete items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setEditItems(int value) {#setEditItems-int-}
```
public final void setEditItems(int value)
```


Gets or sets a value indicating whether a client can edit items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setFolderContact(boolean value) {#setFolderContact-boolean-}
```
public final void setFolderContact(boolean value)
```


Gets or sets a value indicating whether a user is a contact for a folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFolderOwner(boolean value) {#setFolderOwner-boolean-}
```
public final void setFolderOwner(boolean value)
```


Gets or sets a value indicating whether the user is the owner of a folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFolderVisible(boolean value) {#setFolderVisible-boolean-}
```
public final void setFolderVisible(boolean value)
```


Gets or sets a value indicating whether a user can view a folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setUserInfo(ExchangeFolderUserInfo value) {#setUserInfo-com.aspose.email.ExchangeFolderUserInfo-}
```
public final void setUserInfo(ExchangeFolderUserInfo value)
```


Gets or sets a user or a delegate user who has folder access permissions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExchangeFolderUserInfo](../../com.aspose.email/exchangefolderuserinfo) |  |

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

