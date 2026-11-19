---
title: MessageStore
second_title: Aspose.Email for Java API Reference
description: The message store of a PST its top-level object which holds the display name password and other settings of the file.
type: docs
weight: 533
url: /java/com.aspose.email/messagestore/
---

**Inheritance:**
java.lang.Object
```
public class MessageStore
```

The message store of a PST: its top-level object, which holds the display name, password and other settings of the file.
## Methods

| Method | Description |
| --- | --- |
| [changeDisplayName(String newName)](#changeDisplayName-java.lang.String-) | Changes the display name of the PST. |
| [changePassword(String password)](#changePassword-java.lang.String-) | Sets or changes the password of the PST. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDisplayName()](#getDisplayName--) | Gets the display name of the PST, which Outlook shows as the name of the data file. |
| [getProperties()](#getProperties--) | Gets the MAPI properties of message store object. |
| [getTotalItemsCount()](#getTotalItemsCount--) | Gets the total number of message items in the PST. |
| [hashCode()](#hashCode--) |  |
| [isPasswordProtected()](#isPasswordProtected--) | Gets a value indicating whether the storage is password protected. |
| [isPasswordValid(String password)](#isPasswordValid-java.lang.String-) | Checks whether the specified password is the password of the PST. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setProperty(MapiProperty property)](#setProperty-com.aspose.email.MapiProperty-) | Sets a property of the message store. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### changeDisplayName(String newName) {#changeDisplayName-java.lang.String-}
```
public final void changeDisplayName(String newName)
```


Changes the display name of the PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| newName | java.lang.String | The new display name. |

### changePassword(String password) {#changePassword-java.lang.String-}
```
public final void changePassword(String password)
```


Sets or changes the password of the PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The new password. |

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


Gets the display name of the PST, which Outlook shows as the name of the data file.

**Returns:**
java.lang.String - The display name.
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


Gets the MAPI properties of message store object. The message store contains the top-level PST settings and metadata that are required to access and manage the PST contents.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The [MapiProperty](../../com.aspose.email/mapiproperty) collection.
### getTotalItemsCount() {#getTotalItemsCount--}
```
public final int getTotalItemsCount()
```


Gets the total number of message items in the PST.

**Returns:**
int - The number of message items in all folders.
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

**Returns:**
boolean -  true  if the storage is password protected; otherwise,  false .
### isPasswordValid(String password) {#isPasswordValid-java.lang.String-}
```
public final boolean isPasswordValid(String password)
```


Checks whether the specified password is the password of the PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password to check. |

**Returns:**
boolean -  true  if the PST is password protected and  password  matches; otherwise,  false .
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


Sets a property of the message store.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | The property to set. |

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

