---
title: MsgSaveOptions
second_title: Aspose.Email for Java API Reference
description:  This class allows the user to specify additional settings when saving a MailMessage in the MsgASCII and MsgUnicode format.
type: docs
weight: 518
url: /java/com.aspose.email/msgsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.SaveOptions](../../com.aspose.email/saveoptions)
```
public class MsgSaveOptions extends SaveOptions
```

This class allows the user to specify additional settings when saving a MailMessage in the Msg(ASCII) and Msg(Unicode) format.
## Constructors

| Constructor | Description |
| --- | --- |
| [MsgSaveOptions(MailMessageSaveType saveType)](#MsgSaveOptions-com.aspose.email.MailMessageSaveType-) | Initializes a new instance of this class that can be used to save a MailMessage in the Msg(ASCII) and Msg(Unicode) format. |
## Methods

| Method | Description |
| --- | --- |
| [getPreserveOriginalDates()](#getPreserveOriginalDates--) | Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when saving a message. |
| [setPreserveOriginalDates(boolean value)](#setPreserveOriginalDates-boolean-) | Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when saving a message. |
| [getPreserveSignature()](#getPreserveSignature--) | Set to true, if signature is to be preserved. |
| [setPreserveSignature(boolean value)](#setPreserveSignature-boolean-) | Set to true, if signature is to be preserved. |
| [getSaveAsTemplate()](#getSaveAsTemplate--) | Set to true, if need to be saved as Outlook File Template(OFT format). |
| [setSaveAsTemplate(boolean value)](#setSaveAsTemplate-boolean-) | Set to true, if need to be saved as Outlook File Template(OFT format). |
### MsgSaveOptions(MailMessageSaveType saveType) {#MsgSaveOptions-com.aspose.email.MailMessageSaveType-}
```
public MsgSaveOptions(MailMessageSaveType saveType)
```


Initializes a new instance of this class that can be used to save a MailMessage in the Msg(ASCII) and Msg(Unicode) format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveType | [MailMessageSaveType](../../com.aspose.email/mailmessagesavetype) |  |

### getPreserveOriginalDates() {#getPreserveOriginalDates--}
```
public final boolean getPreserveOriginalDates()
```


Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when saving a message.

**Returns:**
boolean
### setPreserveOriginalDates(boolean value) {#setPreserveOriginalDates-boolean-}
```
public final void setPreserveOriginalDates(boolean value)
```


Gets or sets a value indicating whether it is necessary to generate new saving and modification dates when saving a message.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPreserveSignature() {#getPreserveSignature--}
```
public final boolean getPreserveSignature()
```


Set to true, if signature is to be preserved.

**Returns:**
boolean
### setPreserveSignature(boolean value) {#setPreserveSignature-boolean-}
```
public final void setPreserveSignature(boolean value)
```


Set to true, if signature is to be preserved.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSaveAsTemplate() {#getSaveAsTemplate--}
```
public final boolean getSaveAsTemplate()
```


Set to true, if need to be saved as Outlook File Template(OFT format).

**Returns:**
boolean
### setSaveAsTemplate(boolean value) {#setSaveAsTemplate-boolean-}
```
public final void setSaveAsTemplate(boolean value)
```


Set to true, if need to be saved as Outlook File Template(OFT format).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

