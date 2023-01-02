---
title: MboxStorageWriter
second_title: Aspose.Email for Java API Reference
description: A base class for any mbox-based mail storage writer.
type: docs
weight: 482
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
| [close()](#close--) |  |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flush()](#flush--) | flush. |
| [getBaseStream()](#getBaseStream--) | Gets the base stream. |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeMessage(MailMessage message)](#writeMessage-com.aspose.email.MailMessage-) | Writes the message to underlying storage stream. |
| [writeMessage(MailMessage message, String[] fromMarker)](#writeMessage-com.aspose.email.MailMessage-java.lang.String---) | Writes the message to underlying storage stream. |
### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

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
### flush() {#flush--}
```
public void flush()
```


flush.

### getBaseStream() {#getBaseStream--}
```
public InputStream getBaseStream()
```


Gets the base stream.

Value: The base stream.

**Returns:**
java.io.InputStream
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

### writeMessage(MailMessage message) {#writeMessage-com.aspose.email.MailMessage-}
```
public abstract String writeMessage(MailMessage message)
```


Writes the message to underlying storage stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message to write to. |

**Returns:**
java.lang.String
### writeMessage(MailMessage message, String[] fromMarker) {#writeMessage-com.aspose.email.MailMessage-java.lang.String---}
```
public abstract String writeMessage(MailMessage message, String[] fromMarker)
```


Writes the message to underlying storage stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| message | [MailMessage](../../com.aspose.email/mailmessage) | The message to write to. |
| fromMarker | java.lang.String[] | Gets the From Marker while writing the MBox Storage file. |

**Returns:**
java.lang.String
