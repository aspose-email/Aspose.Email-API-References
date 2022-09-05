---
title: VCardSecurity
second_title: Aspose.Email for Android via Java API Reference
description:  Represents a vCard security properties
type: docs
weight: 426
url: /java/com.aspose.email/vcardsecurity/
---
**Inheritance:**
java.lang.Object
```
public final class VCardSecurity
```

Represents a vCard security properties
## Constructors

| Constructor | Description |
| --- | --- |
| [VCardSecurity()](#VCardSecurity--) | Initializes a new instance of the [VCardSecurity](../../com.aspose.email/vcardsecurity) class |
## Methods

| Method | Description |
| --- | --- |
| [getKey()](#getKey--) | Gets or sets a public key(or authentication certificate) |
| [setKey(String value)](#setKey-java.lang.String-) | Gets or sets a public key(or authentication certificate) |
| [getAccessClass()](#getAccessClass--) | Gets or sets an access class |
| [setAccessClass(String value)](#setAccessClass-java.lang.String-) | Gets or sets an access class |
| [getEncoding()](#getEncoding--) | Gets or sets a ContentTransferEncoding |
| [setEncoding(int value)](#setEncoding-int-) | Gets or sets a ContentTransferEncoding |
| [saveToPEM(String path)](#saveToPEM-java.lang.String-) | Saves base64 key to PEM format. |
| [saveToPEM(OutputStream stream)](#saveToPEM-java.io.OutputStream-) | Saves base64 key in PEM format to the stream. |
### VCardSecurity() {#VCardSecurity--}
```
public VCardSecurity()
```


Initializes a new instance of the [VCardSecurity](../../com.aspose.email/vcardsecurity) class

### getKey() {#getKey--}
```
public final String getKey()
```


Gets or sets a public key(or authentication certificate)

**Returns:**
java.lang.String
### setKey(String value) {#setKey-java.lang.String-}
```
public final void setKey(String value)
```


Gets or sets a public key(or authentication certificate)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAccessClass() {#getAccessClass--}
```
public final String getAccessClass()
```


Gets or sets an access class

**Returns:**
java.lang.String
### setAccessClass(String value) {#setAccessClass-java.lang.String-}
```
public final void setAccessClass(String value)
```


Gets or sets an access class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getEncoding() {#getEncoding--}
```
public final int getEncoding()
```


Gets or sets a ContentTransferEncoding

**Returns:**
int
### setEncoding(int value) {#setEncoding-int-}
```
public final void setEncoding(int value)
```


Gets or sets a ContentTransferEncoding

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### saveToPEM(String path) {#saveToPEM-java.lang.String-}
```
public final void saveToPEM(String path)
```


Saves base64 key to PEM format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| path | java.lang.String | Path to file. |

### saveToPEM(OutputStream stream) {#saveToPEM-java.io.OutputStream-}
```
public final void saveToPEM(OutputStream stream)
```


Saves base64 key in PEM format to the stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Stream to save. |

