---
title: MhtmlLoadOptions
second_title: Aspose.Email for Java API Reference
description:  Allows to specify additional options when loading MailMessage from Mhtml format.
type: docs
weight: 512
url: /java/com.aspose.email/mhtmlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.LoadOptions](../../com.aspose.email/loadoptions)
```
public class MhtmlLoadOptions extends LoadOptions
```

Allows to specify additional options when loading MailMessage from Mhtml format.
## Constructors

| Constructor | Description |
| --- | --- |
| [MhtmlLoadOptions()](#MhtmlLoadOptions--) | Initializes a new instance of this class that can be used to loading MailMessage from Mhtml format. |
## Methods

| Method | Description |
| --- | --- |
| [getPreserveTnefAttachments()](#getPreserveTnefAttachments--) | Controls loading TNEF attachment behaviour. |
| [setPreserveTnefAttachments(boolean value)](#setPreserveTnefAttachments-boolean-) | Controls loading TNEF attachment behaviour. |
### MhtmlLoadOptions() {#MhtmlLoadOptions--}
```
public MhtmlLoadOptions()
```


Initializes a new instance of this class that can be used to loading MailMessage from Mhtml format.

### getPreserveTnefAttachments() {#getPreserveTnefAttachments--}
```
public final boolean getPreserveTnefAttachments()
```


Controls loading TNEF attachment behaviour. By default the value is false.

--------------------

If a message contains a TNEF attachment (winmail.dat) and has the MIME type application/ms-tnef, then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

**Returns:**
boolean
### setPreserveTnefAttachments(boolean value) {#setPreserveTnefAttachments-boolean-}
```
public final void setPreserveTnefAttachments(boolean value)
```


Controls loading TNEF attachment behaviour. By default the value is false.

--------------------

If a message contains a TNEF attachment (winmail.dat) and has the MIME type application/ms-tnef, then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

