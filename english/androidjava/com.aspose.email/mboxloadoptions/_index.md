---
title: MboxLoadOptions
second_title: Aspose.Email for Android via Java API Reference
description:  Specifies additional options when loading a Mbox storage.
type: docs
weight: 291
url: /java/com.aspose.email/mboxloadoptions/
---
**Inheritance:**
java.lang.Object
```
public class MboxLoadOptions
```

Specifies additional options when loading a Mbox storage.
## Constructors

| Constructor | Description |
| --- | --- |
| [MboxLoadOptions()](#MboxLoadOptions--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getLeaveOpen()](#getLeaveOpen--) | Gets or sets a value indicating whether to keep the underlying stream open after disposing. |
| [setLeaveOpen(boolean value)](#setLeaveOpen-boolean-) | Gets or sets a value indicating whether to keep the underlying stream open after disposing. |
| [getPreferredTextEncoding()](#getPreferredTextEncoding--) | Gets or sets preferred encoding for messages. |
| [setPreferredTextEncoding(Charset value)](#setPreferredTextEncoding-java.nio.charset.Charset-) | Gets or sets preferred encoding for messages. |
### MboxLoadOptions() {#MboxLoadOptions--}
```
public MboxLoadOptions()
```


### getLeaveOpen() {#getLeaveOpen--}
```
public final boolean getLeaveOpen()
```


Gets or sets a value indicating whether to keep the underlying stream open after disposing. Default value is false.

**Returns:**
boolean
### setLeaveOpen(boolean value) {#setLeaveOpen-boolean-}
```
public final void setLeaveOpen(boolean value)
```


Gets or sets a value indicating whether to keep the underlying stream open after disposing. Default value is false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPreferredTextEncoding() {#getPreferredTextEncoding--}
```
public final Charset getPreferredTextEncoding()
```


Gets or sets preferred encoding for messages. The default value is null.

**Returns:**
java.nio.charset.Charset
### setPreferredTextEncoding(Charset value) {#setPreferredTextEncoding-java.nio.charset.Charset-}
```
public final void setPreferredTextEncoding(Charset value)
```


Gets or sets preferred encoding for messages. The default value is null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.nio.charset.Charset |  |

