---
title: ReminderAttachment
second_title: Aspose.Email for Java API Reference
description: A file attached to a reminder such as the sound of an audio reminder given either as inline data or as a URI.
type: docs
weight: 630
url: /java/com.aspose.email/reminderattachment/
---

**Inheritance:**
java.lang.Object
```
public class ReminderAttachment
```

A file attached to a reminder, such as the sound of an audio reminder, given either as inline data or as a URI.
## Constructors

| Constructor | Description |
| --- | --- |
| [ReminderAttachment(byte[] binaryData)](#ReminderAttachment-byte---) | Initializes a new instance of the [ReminderAttachment](../../com.aspose.email/reminderattachment) class with inline content. |
| [ReminderAttachment(URI uri)](#ReminderAttachment-java.net.URI-) | Initializes a new instance of the [ReminderAttachment](../../com.aspose.email/reminderattachment) class that refers to its content by URI. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBinaryData()](#getBinaryData--) | Gets the content of the attachment, embedded in the calendar. |
| [getClass()](#getClass--) |  |
| [getUri()](#getUri--) | Gets the location of the attachment content. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBinaryData(byte[] value)](#setBinaryData-byte---) | Sets the content of the attachment, embedded in the calendar. |
| [setUri(URI value)](#setUri-java.net.URI-) | Sets the location of the attachment content. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ReminderAttachment(byte[] binaryData) {#ReminderAttachment-byte---}
```
public ReminderAttachment(byte[] binaryData)
```


Initializes a new instance of the [ReminderAttachment](../../com.aspose.email/reminderattachment) class with inline content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| binaryData | byte[] | The content of the attachment. |

### ReminderAttachment(URI uri) {#ReminderAttachment-java.net.URI-}
```
public ReminderAttachment(URI uri)
```


Initializes a new instance of the [ReminderAttachment](../../com.aspose.email/reminderattachment) class that refers to its content by URI.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| uri | java.net.URI | The location of the content. |

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
### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```


Gets the content of the attachment, embedded in the calendar. Setting it clears \#getUri().getUri().

**Returns:**
byte[]
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getUri() {#getUri--}
```
public final URI getUri()
```


Gets the location of the attachment content. Setting it clears \#getBinaryData().getBinaryData().

**Returns:**
java.net.URI
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




### setBinaryData(byte[] value) {#setBinaryData-byte---}
```
public final void setBinaryData(byte[] value)
```


Sets the content of the attachment, embedded in the calendar. Setting it clears \#getUri().getUri().

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### setUri(URI value) {#setUri-java.net.URI-}
```
public final void setUri(URI value)
```


Sets the location of the attachment content. Setting it clears \#getBinaryData().getBinaryData().

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.net.URI |  |

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

