---
title: MailboxConverter
second_title: Aspose.Email for Java API Reference
description: Provides mailbox conversion routines.
type: docs
weight: 379
url: /java/com.aspose.email/mailboxconverter/
---
**Inheritance:**
java.lang.Object
```
public class MailboxConverter
```

Provides mailbox conversion routines.
## Constructors

| Constructor | Description |
| --- | --- |
| [MailboxConverter()](#MailboxConverter--) |  |
## Methods

| Method | Description |
| --- | --- |
| [convertPersonalStorageToMbox(PersonalStorage personalStorage, String storagePath, MessageAcceptanceCallback acceptanceCallback)](#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MessageAcceptanceCallback-) | Converts the [PersonalStorage](../../com.aspose.email/personalstorage) to mbox format using given path. |
| [convertPersonalStorageToMbox(PersonalStorage personalStorage, MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback)](#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-com.aspose.email.MboxStorageWriter-com.aspose.email.MessageAcceptanceCallback-) | Converts the [PersonalStorage](../../com.aspose.email/personalstorage) to mbox format using given [MboxStorageWriter](../../com.aspose.email/mboxstoragewriter). |
### MailboxConverter() {#MailboxConverter--}
```
public MailboxConverter()
```


### convertPersonalStorageToMbox(PersonalStorage personalStorage, String storagePath, MessageAcceptanceCallback acceptanceCallback) {#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MessageAcceptanceCallback-}
```
public static void convertPersonalStorageToMbox(PersonalStorage personalStorage, String storagePath, MessageAcceptanceCallback acceptanceCallback)
```


Converts the [PersonalStorage](../../com.aspose.email/personalstorage) to mbox format using given path.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| personalStorage | [PersonalStorage](../../com.aspose.email/personalstorage) | The personal storage. |
| storagePath | java.lang.String | The path to save  personalStorage  structure to. |
| acceptanceCallback | [MessageAcceptanceCallback](../../com.aspose.email/messageacceptancecallback) | The acceptance callback, can be null.

--------------------

Resulting folder will contain an exact copy of the  personalStorage  e.g. directory tree will be recreated on disk. |

### convertPersonalStorageToMbox(PersonalStorage personalStorage, MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback) {#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-com.aspose.email.MboxStorageWriter-com.aspose.email.MessageAcceptanceCallback-}
```
public static void convertPersonalStorageToMbox(PersonalStorage personalStorage, MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback)
```


Converts the [PersonalStorage](../../com.aspose.email/personalstorage) to mbox format using given [MboxStorageWriter](../../com.aspose.email/mboxstoragewriter).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| personalStorage | [PersonalStorage](../../com.aspose.email/personalstorage) | The personal storage. |
| mboxStorageWriter | [MboxStorageWriter](../../com.aspose.email/mboxstoragewriter) | The mbox storage writer. |
| acceptanceCallback | [MessageAcceptanceCallback](../../com.aspose.email/messageacceptancecallback) | The acceptance callback, can be null.

--------------------

Resulting mbox storage will contain only one plain inbox folder with all messages, if you have to preserve the original structure of the storage, use XXX\_method instead. |

