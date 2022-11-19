---
title: MailStorageConverter
second_title: Aspose.Email for Android via Java API Reference
description: Mail storage converter provides services for storage conversion operations.
type: docs
weight: 200
url: /androidjava/com.aspose.email/mailstorageconverter/
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getMboxMessageOptions()](#getMboxMessageOptions--) | Gets or sets email load options when parsing an Mbox storage. |
| [hashCode()](#hashCode--) |  |
| [mboxToPst(MboxStorageReader mboxStorageReader, PersonalStorage pst, String pstFolderName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-com.aspose.email.MboxStorageReader-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | Converts an Mbox storage to PST. |
| [mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream)](#mboxToPst-java.io.InputStream-java.io.OutputStream-) | Converts an Mbox storage to PST. |
| [mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.io.InputStream-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-) | Converts an Mbox storage to PST. |
| [mboxToPst(InputStream mboxrdDataStream, String pstFileName)](#mboxToPst-java.io.InputStream-java.lang.String-) | Converts an Mbox storage to PST. |
| [mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.io.InputStream-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | Converts an Mbox storage to PST. |
| [mboxToPst(String mboxFileName, System.IO.Stream pstDataStream)](#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-) | Converts an Mbox storage to PST. |
| [mboxToPst(String mboxFileName, System.IO.Stream pstDataStream, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-com.aspose.email.MailStorageConverter.MailHandler-) | Converts an Mbox storage to PST. |
| [mboxToPst(String mboxFileName, OutputStream pstDataStream)](#mboxToPst-java.lang.String-java.io.OutputStream-) | Converts an Mbox storage to PST. |
| [mboxToPst(String mboxFileName, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.lang.String-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-) | Converts an Mbox storage to PST. |
| [mboxToPst(String mboxFileName, String pstFileName)](#mboxToPst-java.lang.String-java.lang.String-) | Converts an Mbox storage to PST. |
| [mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler)](#mboxToPst-java.lang.String-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-) | Converts an Mbox storage to PST. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMboxMessageOptions(EmlLoadOptions value)](#setMboxMessageOptions-com.aspose.email.EmlLoadOptions-) | Gets or sets email load options when parsing an Mbox storage. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MailStorageConverter() {#MailStorageConverter--}
```
public MailStorageConverter()
```


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
### getMboxMessageOptions() {#getMboxMessageOptions--}
```
public static EmlLoadOptions getMboxMessageOptions()
```


Gets or sets email load options when parsing an Mbox storage.

Value: The [EmlLoadOptions](../../com.aspose.email/emlloadoptions) that specifies load options.

**Returns:**
[EmlLoadOptions](../../com.aspose.email/emlloadoptions)
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mboxToPst(MboxStorageReader mboxStorageReader, PersonalStorage pst, String pstFolderName, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-com.aspose.email.MboxStorageReader-com.aspose.email.PersonalStorage-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static void mboxToPst(MboxStorageReader mboxStorageReader, PersonalStorage pst, String pstFolderName, MailStorageConverter.MailHandler mailHandler)
```


Converts an Mbox storage to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxStorageReader | [MboxStorageReader](../../com.aspose.email/mboxstoragereader) | An [MboxStorageReader](../../com.aspose.email/mboxstoragereader) that represents an mbox-based mail storage reader. |
| pst | [PersonalStorage](../../com.aspose.email/personalstorage) | A [PersonalStorage](../../com.aspose.email/personalstorage) that represents a pst storage. |
| pstFolderName | java.lang.String | The folder name, at the root of the pst, where Mbox messages will be added. If this folder doesn't exist, it will be created. If the folder exists and isn't empty, new messages will be added to the existing ones. |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | The [MailHandler](../../com.aspose.email/mailhandler) delegate is called for each message that is read from Mbox. |

### mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream) {#mboxToPst-java.io.InputStream-java.io.OutputStream-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream)
```


Converts an Mbox storage to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | A java.io.InputStream that represents data in Mbox format. |
| pstDataStream | java.io.OutputStream | A java.io.InputStream that represents data in Pst format. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.io.InputStream-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)
```


Converts an Mbox storage to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | A java.io.InputStream that represents data in Mbox format. |
| pstDataStream | java.io.OutputStream | A java.io.InputStream that represents data in Pst format. |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | The [MailHandler](../../com.aspose.email/mailhandler) delegate is called for each message that is read from Mbox. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(InputStream mboxrdDataStream, String pstFileName) {#mboxToPst-java.io.InputStream-java.lang.String-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, String pstFileName)
```


Converts an Mbox storage to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | A java.io.InputStream that represents data in Mbox format. |
| pstFileName | java.lang.String | PST file name.

--------------------

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.io.InputStream-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(InputStream mboxrdDataStream, String pstFileName, MailStorageConverter.MailHandler mailHandler)
```


Converts an Mbox storage to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxrdDataStream | java.io.InputStream | A java.io.InputStream that represents data in Mbox format. |
| pstFileName | java.lang.String | PST file name. |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | The [MailHandler](../../com.aspose.email/mailhandler) delegate is called for each message that is read from Mbox.

--------------------

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, System.IO.Stream pstDataStream) {#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-}
```
public static PersonalStorage mboxToPst(String mboxFileName, System.IO.Stream pstDataStream)
```


Converts an Mbox storage to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox file name. |
| pstDataStream | com.aspose.ms.System.IO.Stream | A Stream that represents data in Pst format.

--------------------

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, System.IO.Stream pstDataStream, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.lang.String-com.aspose.ms.System.IO.Stream-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(String mboxFileName, System.IO.Stream pstDataStream, MailStorageConverter.MailHandler mailHandler)
```


Converts an Mbox storage to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox file name. |
| pstDataStream | com.aspose.ms.System.IO.Stream | A Stream that represents data in Pst format. |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | The [MailHandler](../../com.aspose.email/mailhandler) delegate is called for each message that is read from Mbox.

--------------------

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, OutputStream pstDataStream) {#mboxToPst-java.lang.String-java.io.OutputStream-}
```
public static PersonalStorage mboxToPst(String mboxFileName, OutputStream pstDataStream)
```


Converts an Mbox storage to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox file name. |
| pstDataStream | java.io.OutputStream | A java.io.InputStream that represents data in Pst format.

--------------------

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.lang.String-java.io.OutputStream-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(String mboxFileName, OutputStream pstDataStream, MailStorageConverter.MailHandler mailHandler)
```


Converts an Mbox storage to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox file name. |
| pstDataStream | java.io.OutputStream | A java.io.InputStream that represents data in Pst format. |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | The [MailHandler](../../com.aspose.email/mailhandler) delegate is called for each message that is read from Mbox.

--------------------

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, String pstFileName) {#mboxToPst-java.lang.String-java.lang.String-}
```
public static PersonalStorage mboxToPst(String mboxFileName, String pstFileName)
```


Converts an Mbox storage to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox file name. |
| pstFileName | java.lang.String | PST file name.

--------------------

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler) {#mboxToPst-java.lang.String-java.lang.String-com.aspose.email.MailStorageConverter.MailHandler-}
```
public static PersonalStorage mboxToPst(String mboxFileName, String pstFileName, MailStorageConverter.MailHandler mailHandler)
```


Converts an Mbox storage to PST.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mboxFileName | java.lang.String | Mbox file name. |
| pstFileName | java.lang.String | PST file name. |
| mailHandler | [MailHandler](../../com.aspose.email/mailhandler) | The [MailHandler](../../com.aspose.email/mailhandler) delegate is called for each message that is read from Mbox.

--------------------

In addition the same set of exceptions can be thrown as for FileStream creation using the open/read, create/write mode. |

**Returns:**
[PersonalStorage](../../com.aspose.email/personalstorage) - A [PersonalStorage](../../com.aspose.email/personalstorage) object that represents the converted storage.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

