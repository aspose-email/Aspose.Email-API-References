---
title: EmlLoadOptions
second_title: Aspose.Email for Java API Reference
description:  Allows to specify additional options when loading MailMessage from Eml format.
type: docs
weight: 170
url: /java/com.aspose.email/emlloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.LoadOptions](../../com.aspose.email/loadoptions)
```
public class EmlLoadOptions extends LoadOptions
```

Allows to specify additional options when loading MailMessage from Eml format.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmlLoadOptions()](#EmlLoadOptions--) | Initializes a new instance of this class that can be used to loading MailMessage from Eml format. |
## Methods

| Method | Description |
| --- | --- |
| [getPreserveTnefAttachments()](#getPreserveTnefAttachments--) | Controls TNEF attachment loading behaviour. |
| [setPreserveTnefAttachments(boolean value)](#setPreserveTnefAttachments-boolean-) | Controls TNEF attachment loading behaviour. |
### EmlLoadOptions() {#EmlLoadOptions--}
```
public EmlLoadOptions()
```


Initializes a new instance of this class that can be used to loading MailMessage from Eml format.

### getPreserveTnefAttachments() {#getPreserveTnefAttachments--}
```
public final boolean getPreserveTnefAttachments()
```


Controls TNEF attachment loading behaviour. By default the value is false.

--------------------

If a message contains a TNEF attachment (winmail.dat) and has the MIME type application/ms-tnef, then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

**Returns:**
boolean
### setPreserveTnefAttachments(boolean value) {#setPreserveTnefAttachments-boolean-}
```
public final void setPreserveTnefAttachments(boolean value)
```


Controls TNEF attachment loading behaviour. By default the value is false.

--------------------

If a message contains a TNEF attachment (winmail.dat) and has the MIME type application/ms-tnef, then this property defines whether files from TNEF will be decoded and extracted. The winmail.dat attachment remains as it is if the property value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

