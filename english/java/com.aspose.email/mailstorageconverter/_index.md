---
title: MailStorageConverter
second_title: Aspose.Email for Java API Reference
description:  Mail storage converter provides services for storage conversion operations.
type: docs
weight: 376
url: /java/com.aspose.email/mailstorageconverter/
---
**Inheritance:**
java.lang.Object
```
public class MailStorageConverter
```

Mail storage converter provides services for storage conversion operations.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailStorageConverter()](#MailStorageConverter--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getMboxMessageOptions()](#getMboxMessageOptions--) | Gets or sets email load options when parsing an Mbox storage. |
| [setMboxMessageOptions(EmlLoadOptions value)](#setMboxMessageOptions-com.aspose.email.EmlLoadOptions-) | Gets or sets email load options when parsing an Mbox storage. |
| [mboxToPst(String mboxFileName, String pstFileName)](#mboxToPst-java.lang.String-java.lang.String-) | Converts an mboxrd message store to PST. |
| [mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.lang.String-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | Converts an mboxrd message store to PST. |
| [mboxToPst(InputStream mboxrdDataStream, String pstFileName)](#mboxToPst-java.io.InputStream-java.lang.String-) | Converts an mboxrd message store to PST. |
| [mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.io.InputStream-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | Converts an mboxrd message store to PST. |
### MailStorageConverter() {#MailStorageConverter--}
```
public MailStorageConverter()
```


### getMboxMessageOptions() {#getMboxMessageOptions--}
```
public static EmlLoadOptions getMboxMessageOptions()
```


Gets or sets email load options when parsing an Mbox storage.

Value: The [EmlLoadOptions](../../com.aspose.email/emlloadoptions) that specifies load options.

**Returns:**
[EmlLoadOptions](../../com.aspose.email/emlloadoptions)
### setMboxMessageOptions(EmlLoadOptions value) {#setMboxMessageOptions-com.aspose.email.EmlLoadOptions-}
```
public static void setMboxMessageOptions(EmlLoadOptions value)
```


Gets or sets email load options when parsing an Mbox storage.

Value: The [EmlLoadOptions](../../com.aspose.email/emlloadoptions) that specifies load options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmlLoadOptions](../../com.aspose.email/emlloadoptions) |  |

### mboxToPst(String mboxFileName, String pstFileName) {#mboxToPst-java.lang.String-java.lang.String-}
```
public static PersonalStorage mboxToPst(String mboxFileName, String pstFileName)
```


Converts an mboxrd message store to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | java.lang.String | Name of the mbox file. |
| pstFileName | java.lang.String | Name of the PST file.

--------------------

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - Personal storage object that represents the converted storage.
### mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.lang.String-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler)
```


Converts an mboxrd message store to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | java.lang.String | Name of the mbox file. |
| pstFileName | java.lang.String | Name of the PST file. |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | The delegate called on each message

--------------------

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - Personal storage object that represents the converted storage.
### mboxToPst(InputStream mboxrdDataStream, String pstFileName) {#mboxToPst-java.io.InputStream-java.lang.String-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, String pstFileName)
```


Converts an mboxrd message store to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | The mboxrd data stream. |
| pstFileName | java.lang.String | Name of the PST file. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - Personal storage object that represents the converted storage.
### mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.io.InputStream-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler)
```


Converts an mboxrd message store to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | The mboxrd data stream. |
| pstFileName | java.lang.String | Name of the PST file. |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | The delegate called on each message |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - Personal storage object that represents the converted storage.
