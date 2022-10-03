---
title: MsgLoadOptions
second_title: Aspose.Email for Java API Reference
description: Allows to specify additional options when loading MailMessage from Msg format.
type: docs
weight: 517
url: /java/com.aspose.email/msgloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.LoadOptions](../../com.aspose.email/loadoptions)
```
public class MsgLoadOptions extends LoadOptions
```

Allows to specify additional options when loading MailMessage from Msg format.
## Constructors

| Constructor | Description |
| --- | --- |
| [MsgLoadOptions()](#MsgLoadOptions--) | Initializes a new instance of this class that can be used to loading MailMessage from Msg format. |
## Methods

| Method | Description |
| --- | --- |
| [getPreserveTnefAttachments()](#getPreserveTnefAttachments--) | Controls loading TNEF attachment behaviour. |
| [setPreserveTnefAttachments(boolean value)](#setPreserveTnefAttachments-boolean-) | Controls loading TNEF attachment behaviour. |
| [getDecodeClearSignedContent()](#getDecodeClearSignedContent--) | Gets or sets a value indicating whether clear-signed message will be decoded. |
| [setDecodeClearSignedContent(boolean value)](#setDecodeClearSignedContent-boolean-) | Gets or sets a value indicating whether clear-signed message will be decoded. |
| [getDecodeSignedContent()](#getDecodeSignedContent--) | Gets or sets a value indicating whether signed message will be decoded. |
| [setDecodeSignedContent(boolean value)](#setDecodeSignedContent-boolean-) | Gets or sets a value indicating whether signed message will be decoded. |
| [getKeepOriginalEmailAddresses()](#getKeepOriginalEmailAddresses--) | Gets or sets a value indicating whether need keep original email address. |
| [setKeepOriginalEmailAddresses(boolean value)](#setKeepOriginalEmailAddresses-boolean-) | Gets or sets a value indicating whether need keep original email address. |
| [getPreserveRtfContent()](#getPreserveRtfContent--) | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
| [setPreserveRtfContent(boolean value)](#setPreserveRtfContent-boolean-) | Gets or sets a value indicating whether need keep rtf body in MailMessage. |
### MsgLoadOptions() {#MsgLoadOptions--}
```
public MsgLoadOptions()
```


Initializes a new instance of this class that can be used to loading MailMessage from Msg format.

### getPreserveTnefAttachments() {#getPreserveTnefAttachments--}
```
public final boolean getPreserveTnefAttachments()
```


Controls loading TNEF attachment behaviour. By default the value is false.

--------------------

If a message contains a TNEF attachment (winmail.dat), then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

**Returns:**
boolean
### setPreserveTnefAttachments(boolean value) {#setPreserveTnefAttachments-boolean-}
```
public final void setPreserveTnefAttachments(boolean value)
```


Controls loading TNEF attachment behaviour. By default the value is false.

--------------------

If a message contains a TNEF attachment (winmail.dat), then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDecodeClearSignedContent() {#getDecodeClearSignedContent--}
```
public final boolean getDecodeClearSignedContent()
```


Gets or sets a value indicating whether clear-signed message will be decoded.

Value:  true  if clear-signed message will be decoded; otherwise,  false .

**Returns:**
boolean
### setDecodeClearSignedContent(boolean value) {#setDecodeClearSignedContent-boolean-}
```
public final void setDecodeClearSignedContent(boolean value)
```


Gets or sets a value indicating whether clear-signed message will be decoded.

Value:  true  if clear-signed message will be decoded; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getDecodeSignedContent() {#getDecodeSignedContent--}
```
public final boolean getDecodeSignedContent()
```


Gets or sets a value indicating whether signed message will be decoded.

Value:  true  if signed message will be decoded; otherwise,  false .

**Returns:**
boolean
### setDecodeSignedContent(boolean value) {#setDecodeSignedContent-boolean-}
```
public final void setDecodeSignedContent(boolean value)
```


Gets or sets a value indicating whether signed message will be decoded.

Value:  true  if signed message will be decoded; otherwise,  false .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getKeepOriginalEmailAddresses() {#getKeepOriginalEmailAddresses--}
```
public final boolean getKeepOriginalEmailAddresses()
```


Gets or sets a value indicating whether need keep original email address.

**Returns:**
boolean
### setKeepOriginalEmailAddresses(boolean value) {#setKeepOriginalEmailAddresses-boolean-}
```
public final void setKeepOriginalEmailAddresses(boolean value)
```


Gets or sets a value indicating whether need keep original email address.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPreserveRtfContent() {#getPreserveRtfContent--}
```
public final boolean getPreserveRtfContent()
```


Gets or sets a value indicating whether need keep rtf body in MailMessage.

**Returns:**
boolean
### setPreserveRtfContent(boolean value) {#setPreserveRtfContent-boolean-}
```
public final void setPreserveRtfContent(boolean value)
```


Gets or sets a value indicating whether need keep rtf body in MailMessage.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

