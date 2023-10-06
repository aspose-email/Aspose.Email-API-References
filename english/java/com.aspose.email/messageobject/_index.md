---
title: MessageObject
second_title: Aspose.Email for Java API Reference
description: Represents an Outlook message object.
type: docs
weight: 501
url: /java/com.aspose.email/messageobject/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.email.IMessageObjectPropertyContainer](../../com.aspose.email/imessageobjectpropertycontainer)
```
public final class MessageObject implements IMessageObjectPropertyContainer
```

Represents an Outlook message object. Evaluation limits: only 1 attachment and 1 recipient are read when message is being loaded, watermark will be added when the message is being saved.
## Constructors

| Constructor | Description |
| --- | --- |
| [MessageObject(InputStream stream, int loadFormat)](#MessageObject-java.io.InputStream-int-) | Initializes a new instance of the [MessageObject](../../com.aspose.email/messageobject) class. |
| [MessageObject(String fileName, int loadFormat)](#MessageObject-java.lang.String-int-) | Initializes a new instance of the [MessageObject](../../com.aspose.email/messageobject) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | Gets the attachments of the [MessageObject](../../com.aspose.email/messageobject). |
| [getClass()](#getClass--) |  |
| [getCodepage()](#getCodepage--) | Gets the codepage used to encode/decode string properties in case [MapiType.PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8) type for them is used. |
| [getIdForNamedProperty()](#getIdForNamedProperty--) | Gets the id to be used for named property, named properties are special properties and should have their ids in range [0x8000,0xfffe] aligned starting from 0x8000 sequentally. |
| [getProperties()](#getProperties--) | Gets the properties of the [MessageObject](../../com.aspose.email/messageobject). |
| [getRecipients()](#getRecipients--) | Gets the recipients of the [MessageObject](../../com.aspose.email/messageobject). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Saves the current message object to the specified stream. |
| [save(String fileName, int format)](#save-java.lang.String-int-) | Saves the current message object to the specified file. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageObject(InputStream stream, int loadFormat) {#MessageObject-java.io.InputStream-int-}
```
public MessageObject(InputStream stream, int loadFormat)
```


Initializes a new instance of the [MessageObject](../../com.aspose.email/messageobject) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to initialize this object from. |
| loadFormat | int | The source format message object is stored with. |

### MessageObject(String fileName, int loadFormat) {#MessageObject-java.lang.String-int-}
```
public MessageObject(String fileName, int loadFormat)
```


Initializes a new instance of the [MessageObject](../../com.aspose.email/messageobject) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file to read from. |
| loadFormat | int | The source format message object is stored with.

--------------------

In addition same set of exceptions could be thrown as for the File\#open(String,int).open(String,int) call. |

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
### getAttachments() {#getAttachments--}
```
public final MessageObjectAttachmentsCollection getAttachments()
```


Gets the attachments of the [MessageObject](../../com.aspose.email/messageobject).

Value: The attachments.

**Returns:**
[MessageObjectAttachmentsCollection](../../com.aspose.email/messageobjectattachmentscollection)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodepage() {#getCodepage--}
```
public final int getCodepage()
```


Gets the codepage used to encode/decode string properties in case [MapiType.PT\_STRING8](../../com.aspose.email/mapitype\#PT-STRING8) type for them is used.

Value: The codepage.

**Returns:**
int
### getIdForNamedProperty() {#getIdForNamedProperty--}
```
public final int getIdForNamedProperty()
```


Gets the id to be used for named property, named properties are special properties and should have their ids in range [0x8000,0xfffe] aligned starting from 0x8000 sequentally. Use this method to find the available id cause it could be hard to calculate it yourself.

**Returns:**
int - Available id for the named property.
### getProperties() {#getProperties--}
```
public final MessageObjectPropertiesCollection getProperties()
```


Gets the properties of the [MessageObject](../../com.aspose.email/messageobject).

Value: The properties.

**Returns:**
[MessageObjectPropertiesCollection](../../com.aspose.email/messageobjectpropertiescollection)
### getRecipients() {#getRecipients--}
```
public final MessageObjectRecipientsCollection getRecipients()
```


Gets the recipients of the [MessageObject](../../com.aspose.email/messageobject).

Value: The recipients.

**Returns:**
[MessageObjectRecipientsCollection](../../com.aspose.email/messageobjectrecipientscollection)
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




### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int format)
```


Saves the current message object to the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |
| format | int | The format of the output data. |

### save(String fileName, int format) {#save-java.lang.String-int-}
```
public final void save(String fileName, int format)
```


Saves the current message object to the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Name of the file. |
| format | int | The format of the output data.

--------------------

In addition same set of exceptions could be thrown as for the File\#openWrite(String).openWrite(String) call. |

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

