---
title: MailStorageConverter
second_title: Aspose.Email for Android via Java API Reference
description:  Mail storage converter provides services for storage conversion operations.
type: docs
weight: 200
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
| [mboxToPst(String mboxFileName, String pstFileName)](#mboxToPst-java.lang.String-java.lang.String-) | Converts an mboxrd message store to PST. |
| [mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.lang.String-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | Converts an mboxrd message store to PST. |
| [mboxToPst(InputStream mboxrdDataStream, String pstFileName)](#mboxToPst-java.io.InputStream-java.lang.String-) | Converts an mboxrd message store to PST. |
| [mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.io.InputStream-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | Converts an mboxrd message store to PST. |
### MailStorageConverter() {#MailStorageConverter--}
```
public MailStorageConverter()
```


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
