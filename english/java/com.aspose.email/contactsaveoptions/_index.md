---
title: ContactSaveOptions
second_title: Aspose.Email for Java API Reference
description: The base class for the options that control how a contact is saved.
type: docs
weight: 127
url: /java/com.aspose.email/contactsaveoptions/
---

**Inheritance:**
java.lang.Object
```
public abstract class ContactSaveOptions
```

The base class for the options that control how a contact is saved. The derived classes select the format: [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions) for vCard, [WebDavContactSaveOptions](../../com.aspose.email/webdavcontactsaveoptions) for WebDAV and [MapiContactSaveOptions](../../com.aspose.email/mapicontactsaveoptions) for MSG.

Pass an instance to [MapiContact.save(String)](../../com.aspose.email/mapicontact\#save-String-). \#getVersion().getVersion() applies only to vCard output; the other formats ignore it.
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getProductId()](#getProductId--) | Gets the identifier of the product that created the vCard, written to its  PRODID  property. |
| [getSaveFormat()](#getSaveFormat--) | Gets the format this options object saves to. |
| [getVersion()](#getVersion--) | Gets the vCard version to write. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setProductId(String value)](#setProductId-java.lang.String-) | Sets the identifier of the product that created the vCard, written to its  PRODID  property. |
| [setVersion(int value)](#setVersion-int-) | Sets the vCard version to write. |
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getProductId() {#getProductId--}
```
public final String getProductId()
```


Gets the identifier of the product that created the vCard, written to its  PRODID  property.

**Returns:**
java.lang.String - The product identifier.
### getSaveFormat() {#getSaveFormat--}
```
public final int getSaveFormat()
```


Gets the format this options object saves to.

**Returns:**
int
### getVersion() {#getVersion--}
```
public final int getVersion()
```


Gets the vCard version to write. Used only when the contact is saved to vCard.

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




### setProductId(String value) {#setProductId-java.lang.String-}
```
public final void setProductId(String value)
```


Sets the identifier of the product that created the vCard, written to its  PRODID  property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The product identifier. |

### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Sets the vCard version to write. Used only when the contact is saved to vCard.

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

