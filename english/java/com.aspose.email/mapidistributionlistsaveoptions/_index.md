---
title: MapiDistributionListSaveOptions
second_title: Aspose.Email for Java API Reference
description: Options for saving a distribution list.
type: docs
weight: 461
url: /java/com.aspose.email/mapidistributionlistsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.ContactSaveOptions](../../com.aspose.email/contactsaveoptions)
```
public final class MapiDistributionListSaveOptions extends ContactSaveOptions
```

Options for saving a distribution list.

The format is set in the constructor: MSG or vCard. WebDAV is not supported for distribution lists.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiDistributionListSaveOptions(int saveFormat)](#MapiDistributionListSaveOptions-int-) | Initializes a new instance of the [MapiDistributionListSaveOptions](../../com.aspose.email/mapidistributionlistsaveoptions) class that saves to the specified format. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Gets new options that save to MSG format. |
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
### MapiDistributionListSaveOptions(int saveFormat) {#MapiDistributionListSaveOptions-int-}
```
public MapiDistributionListSaveOptions(int saveFormat)
```


Initializes a new instance of the [MapiDistributionListSaveOptions](../../com.aspose.email/mapidistributionlistsaveoptions) class that saves to the specified format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveFormat | int | The format: MSG or vCard. |

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
### getDefault() {#getDefault--}
```
public static MapiDistributionListSaveOptions getDefault()
```


Gets new options that save to MSG format.

**Returns:**
[MapiDistributionListSaveOptions](../../com.aspose.email/mapidistributionlistsaveoptions) - The default options.
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

