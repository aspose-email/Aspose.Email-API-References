---
title: MessageStore
second_title: Aspose.Email for Java API Reference
description: Message store is the root of the PST  which is the rough equivalent of the top of a Mailbox.
type: docs
weight: 505
url: /java/com.aspose.email/messagestore/
---

**Inheritance:**
java.lang.Object
```
public class MessageStore
```

Message store is the root of the PST, which is the rough equivalent of the top of a Mailbox.
## Methods

| Method | Description |
| --- | --- |
| [changeDisplayName(String newName)](#changeDisplayName-java.lang.String-) | Changes the pst display name. |
| [changePassword(String password)](#changePassword-java.lang.String-) | Sets the password. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisplayName()](#getDisplayName--) | Gets the display Name of PST. |
| [getProperties()](#getProperties--) | Gets the MAPI properties of message store object. |
| [getTotalItemsCount()](#getTotalItemsCount--) | Gets the total items count. |
| [hashCode()](#hashCode--) |  |
| [isPasswordProtected()](#isPasswordProtected--) | Gets a value indicating whether the storage is password protected. |
| [isPasswordValid(String password)](#isPasswordValid-java.lang.String-) | Determines whether the specified string is a valid password for the storage. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setProperty(MapiProperty property)](#setProperty-com.aspose.email.MapiProperty-) | Sets the property. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### changeDisplayName(String newName) {#changeDisplayName-java.lang.String-}
```
public final void changeDisplayName(String newName)
```


Changes the pst display name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newName | java.lang.String | The new display name of message store. |

### changePassword(String password) {#changePassword-java.lang.String-}
```
public final void changePassword(String password)
```


Sets the password.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The string that represents the password. |

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
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the display Name of PST.

Value: The string that represents display name.

**Returns:**
java.lang.String
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


Gets the MAPI properties of message store object. The message store contains the top-level PST settings and metadata that are required to access and manage the PST contents.

Value: The [MapiProperty](../../com.aspose.email/mapiproperty) collection.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getTotalItemsCount() {#getTotalItemsCount--}
```
public final int getTotalItemsCount()
```


Gets the total items count. Returns the total number of message items contained in the PST.

**Returns:**
int - Total message items count.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Gets a value indicating whether the storage is password protected.

Value:  true  if the storage is password protected; otherwise,  false .

**Returns:**
boolean
### isPasswordValid(String password) {#isPasswordValid-java.lang.String-}
```
public final boolean isPasswordValid(String password)
```


Determines whether the specified string is a valid password for the storage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password string. |

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




### setProperty(MapiProperty property) {#setProperty-com.aspose.email.MapiProperty-}
```
public final void setProperty(MapiProperty property)
```


Sets the property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | The property. |

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

