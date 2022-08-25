---
title: ExchangeBasePermission
second_title: Aspose.Email for Java API Reference
description:  Provides abstract base class for permissions to folders on Exchange Server.
type: docs
weight: 189
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
| [getUserInfo()](#getUserInfo--) | Gets or sets a user or a delegate user who has folder access permissions |
| [setUserInfo(ExchangeFolderUserInfo value)](#setUserInfo-com.aspose.email.ExchangeFolderUserInfo-) | Gets or sets a user or a delegate user who has folder access permissions |
| [canCreateItems()](#canCreateItems--) | Gets or sets a value indicating whether a client can create items in a folder. |
| [canCreateItems(boolean value)](#canCreateItems-boolean-) | Gets or sets a value indicating whether a client can create items in a folder. |
| [canCreateSubFolders()](#canCreateSubFolders--) | Gets or sets a value indicating whether the client can create subfolders. |
| [canCreateSubFolders(boolean value)](#canCreateSubFolders-boolean-) | Gets or sets a value indicating whether the client can create subfolders. |
| [isFolderOwner()](#isFolderOwner--) | Gets or sets a value indicating whether the user is the owner of a folder. |
| [setFolderOwner(boolean value)](#setFolderOwner-boolean-) | Gets or sets a value indicating whether the user is the owner of a folder. |
| [isFolderVisible()](#isFolderVisible--) | Gets or sets a value indicating whether a user can view a folder. |
| [setFolderVisible(boolean value)](#setFolderVisible-boolean-) | Gets or sets a value indicating whether a user can view a folder. |
| [isFolderContact()](#isFolderContact--) | Gets or sets a value indicating whether a user is a contact for a folder. |
| [setFolderContact(boolean value)](#setFolderContact-boolean-) | Gets or sets a value indicating whether a user is a contact for a folder. |
| [getEditItems()](#getEditItems--) | Gets or sets a value indicating whether a client can edit items. |
| [setEditItems(int value)](#setEditItems-int-) | Gets or sets a value indicating whether a client can edit items. |
| [getDeleteItems()](#getDeleteItems--) | Gets or sets a value indicating whether the client can delete items. |
| [setDeleteItems(int value)](#setDeleteItems-int-) | Gets or sets a value indicating whether the client can delete items. |
### getUserInfo() {#getUserInfo--}
```
public final ExchangeFolderUserInfo getUserInfo()
```


Gets or sets a user or a delegate user who has folder access permissions

**Returns:**
[ExchangeFolderUserInfo](../../com.aspose.email/exchangefolderuserinfo)
### setUserInfo(ExchangeFolderUserInfo value) {#setUserInfo-com.aspose.email.ExchangeFolderUserInfo-}
```
public final void setUserInfo(ExchangeFolderUserInfo value)
```


Gets or sets a user or a delegate user who has folder access permissions

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ExchangeFolderUserInfo](../../com.aspose.email/exchangefolderuserinfo) |  |

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

### isFolderOwner() {#isFolderOwner--}
```
public final boolean isFolderOwner()
```


Gets or sets a value indicating whether the user is the owner of a folder.

**Returns:**
boolean
### setFolderOwner(boolean value) {#setFolderOwner-boolean-}
```
public final void setFolderOwner(boolean value)
```


Gets or sets a value indicating whether the user is the owner of a folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isFolderVisible() {#isFolderVisible--}
```
public final boolean isFolderVisible()
```


Gets or sets a value indicating whether a user can view a folder.

**Returns:**
boolean
### setFolderVisible(boolean value) {#setFolderVisible-boolean-}
```
public final void setFolderVisible(boolean value)
```


Gets or sets a value indicating whether a user can view a folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### isFolderContact() {#isFolderContact--}
```
public final boolean isFolderContact()
```


Gets or sets a value indicating whether a user is a contact for a folder.

**Returns:**
boolean
### setFolderContact(boolean value) {#setFolderContact-boolean-}
```
public final void setFolderContact(boolean value)
```


Gets or sets a value indicating whether a user is a contact for a folder.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getEditItems() {#getEditItems--}
```
public final int getEditItems()
```


Gets or sets a value indicating whether a client can edit items.

**Returns:**
int
### setEditItems(int value) {#setEditItems-int-}
```
public final void setEditItems(int value)
```


Gets or sets a value indicating whether a client can edit items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeleteItems() {#getDeleteItems--}
```
public final int getDeleteItems()
```


Gets or sets a value indicating whether the client can delete items.

**Returns:**
int
### setDeleteItems(int value) {#setDeleteItems-int-}
```
public final void setDeleteItems(int value)
```


Gets or sets a value indicating whether the client can delete items.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

