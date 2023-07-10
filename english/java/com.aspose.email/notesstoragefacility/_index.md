---
title: NotesStorageFacility
second_title: Aspose.Email for Java API Reference
description: The Notes Storage Facility NSF database file  is used by IBM Lotus Notes and Domino  to store different kind of objects like e-mail  appointments and documents  but also application forms and views.
type: docs
weight: 534
url: /java/com.aspose.email/notesstoragefacility/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class NotesStorageFacility implements System.IDisposable, Closeable
```

The Notes Storage Facility (NSF) database file is used by (IBM) Lotus Notes and Domino to store different kind of objects like e-mail, appointments and documents, but also application forms and views.
## Constructors

| Constructor | Description |
| --- | --- |
| [NotesStorageFacility(String fileName)](#NotesStorageFacility-java.lang.String-) | Initializes a new instance of the [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) class. |
| [NotesStorageFacility(InputStream stream)](#NotesStorageFacility-java.io.InputStream-) | Initializes a new instance of the [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) class. |
| [NotesStorageFacility(String fileName, NsfLoadOptions options)](#NotesStorageFacility-java.lang.String-com.aspose.email.NsfLoadOptions-) | Initializes a new instance of the [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) class. |
| [NotesStorageFacility(InputStream stream, NsfLoadOptions options)](#NotesStorageFacility-java.io.InputStream-com.aspose.email.NsfLoadOptions-) | Initializes a new instance of the [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) class. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [enumerateMessages()](#enumerateMessages--) | Exposes the enumerator, which supports an iteration of messages in storage. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NotesStorageFacility(String fileName) {#NotesStorageFacility-java.lang.String-}
```
public NotesStorageFacility(String fileName)
```


Initializes a new instance of the [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |

### NotesStorageFacility(InputStream stream) {#NotesStorageFacility-java.io.InputStream-}
```
public NotesStorageFacility(InputStream stream)
```


Initializes a new instance of the [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |

### NotesStorageFacility(String fileName, NsfLoadOptions options) {#NotesStorageFacility-java.lang.String-com.aspose.email.NsfLoadOptions-}
```
public NotesStorageFacility(String fileName, NsfLoadOptions options)
```


Initializes a new instance of the [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| options | [NsfLoadOptions](../../com.aspose.email/nsfloadoptions) | Additional load options. |

### NotesStorageFacility(InputStream stream, NsfLoadOptions options) {#NotesStorageFacility-java.io.InputStream-com.aspose.email.NsfLoadOptions-}
```
public NotesStorageFacility(InputStream stream, NsfLoadOptions options)
```


Initializes a new instance of the [NotesStorageFacility](../../com.aspose.email/notesstoragefacility) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream. |
| options | [NsfLoadOptions](../../com.aspose.email/nsfloadoptions) | Additional load options. |

### close() {#close--}
```
public void close()
```




### dispose() {#dispose--}
```
public final void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

### enumerateMessages() {#enumerateMessages--}
```
public final System.Collections.Generic.IGenericEnumerable<MailMessage> enumerateMessages()
```


Exposes the enumerator, which supports an iteration of messages in storage.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.email.MailMessage> -  System.Collections.Generic.IEnumerableltTgt , that represents an enumerator that iterates through a messages in storage.
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

