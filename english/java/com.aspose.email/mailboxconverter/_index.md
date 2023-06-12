---
title: MailboxConverter
second_title: Aspose.Email for Java API Reference
description: Provides mailbox conversion routines.
type: docs
weight: 380
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
| [convertPersonalStorageToMbox(PersonalStorage personalStorage, MboxStorageWriter mboxStorageWriter, MessageAcceptanceCallback acceptanceCallback)](#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-com.aspose.email.MboxStorageWriter-com.aspose.email.MessageAcceptanceCallback-) | Converts the [PersonalStorage](../../com.aspose.email/personalstorage) to mbox format using given [MboxStorageWriter](../../com.aspose.email/mboxstoragewriter). |
| [convertPersonalStorageToMbox(PersonalStorage personalStorage, String storagePath, MessageAcceptanceCallback acceptanceCallback)](#convertPersonalStorageToMbox-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MessageAcceptanceCallback-) | Converts the [PersonalStorage](../../com.aspose.email/personalstorage) to mbox format using given path. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailboxConverter() {#MailboxConverter--}
```
public MailboxConverter()
```


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

