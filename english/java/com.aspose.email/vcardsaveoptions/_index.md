---
title: VCardSaveOptions
second_title: Aspose.Email for Java API Reference
description: Represents vCard save options.
type: docs
weight: 760
url: /java/com.aspose.email/vcardsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.ContactSaveOptions](../../com.aspose.email/contactsaveoptions)
```
public final class VCardSaveOptions extends ContactSaveOptions
```

Represents vCard save options.
## Constructors

| Constructor | Description |
| --- | --- |
| [VCardSaveOptions()](#VCardSaveOptions--) | Initializes a new instance of the [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions) class. |
| [VCardSaveOptions(int version, boolean useExtensions)](#VCardSaveOptions-int-boolean-) | Initializes a new instance of the [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions) class. |
| [VCardSaveOptions(int version)](#VCardSaveOptions-int-) | Initializes a new instance of the [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDefault()](#getDefault--) | Gets default [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions) |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets Encoding that will be used to save Contact. |
| [getProductId()](#getProductId--) | Gets the identifier of the product that created the vCard, written to its  PRODID  property. |
| [getSaveFormat()](#getSaveFormat--) | Gets the format this options object saves to. |
| [getUseExtensions()](#getUseExtensions--) | Gets a value indicating whether the extended types can be used. |
| [getVersion()](#getVersion--) | Gets the vCard version to write. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Sets Encoding that will be used to save Contact. |
| [setProductId(String value)](#setProductId-java.lang.String-) | Sets the identifier of the product that created the vCard, written to its  PRODID  property. |
| [setUseExtensions(boolean value)](#setUseExtensions-boolean-) | Sets a value indicating whether the extended types can be used. |
| [setVersion(int value)](#setVersion-int-) | Sets the vCard version to write. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VCardSaveOptions() {#VCardSaveOptions--}
```
public VCardSaveOptions()
```


Initializes a new instance of the [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions) class.

### VCardSaveOptions(int version, boolean useExtensions) {#VCardSaveOptions-int-boolean-}
```
public VCardSaveOptions(int version, boolean useExtensions)
```


Initializes a new instance of the [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| version | int | a vCard version. |
| useExtensions | boolean | indicates whether extended types can be used. |

### VCardSaveOptions(int version) {#VCardSaveOptions-int-}
```
public VCardSaveOptions(int version)
```


Initializes a new instance of the [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| version | int | a vCard version. |

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
public static VCardSaveOptions getDefault()
```


Gets default [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions)

**Returns:**
[VCardSaveOptions](../../com.aspose.email/vcardsaveoptions)
### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Gets Encoding that will be used to save Contact.

**Returns:**
java.nio.charset.Charset
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
### getUseExtensions() {#getUseExtensions--}
```
public final boolean getUseExtensions()
```


Gets a value indicating whether the extended types can be used.

**Returns:**
boolean
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




### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Sets Encoding that will be used to save Contact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

### setProductId(String value) {#setProductId-java.lang.String-}
```
public final void setProductId(String value)
```


Sets the identifier of the product that created the vCard, written to its  PRODID  property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The product identifier. |

### setUseExtensions(boolean value) {#setUseExtensions-boolean-}
```
public final void setUseExtensions(boolean value)
```


Sets a value indicating whether the extended types can be used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

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

