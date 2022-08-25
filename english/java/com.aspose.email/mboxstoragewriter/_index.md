---
title: MboxStorageWriter
second_title: Aspose.Email for Java API Reference
description:  A base class for any mbox-based mail storage writer.
type: docs
weight: 480
url: /java/com.aspose.email/mboxstoragewriter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public abstract class MboxStorageWriter implements System.IDisposable, Closeable
```

A base class for any mbox-based mail storage writer.
## Methods

| Method | Description |
| --- | --- |
| [getBaseStream()](#getBaseStream--) | Gets the base stream. |
| [writeMessage(MailMessage message)](#writeMessage-com.aspose.email.MailMessage-) | Writes the message to underlying storage stream. |
| [writeMessage(MailMessage message, String[] fromMarker)](#writeMessage-com.aspose.email.MailMessage-java.lang.String---) | Writes the message to underlying storage stream. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [close()](#close--) |  |
| [flush()](#flush--) | flush. |
### getBaseStream() {#getBaseStream--}
```
public InputStream getBaseStream()
```


Gets the base stream.

Value: The base stream.

**Returns:**
java.io.InputStream
### writeMessage(MailMessage message) {#writeMessage-com.aspose.email.MailMessage-}
```
public abstract void writeMessage(MailMessage message)
```


Writes the message to underlying storage stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message to write to. |

### writeMessage(MailMessage message, String[] fromMarker) {#writeMessage-com.aspose.email.MailMessage-java.lang.String---}
```
public abstract void writeMessage(MailMessage message, String[] fromMarker)
```


Writes the message to underlying storage stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message to write to. |
| fromMarker | java.lang.String[] | Gets the From Marker while writing the MBox Storage file. |

### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### close() {#close--}
```
public void close()
```




### flush() {#flush--}
```
public void flush()
```


flush.

