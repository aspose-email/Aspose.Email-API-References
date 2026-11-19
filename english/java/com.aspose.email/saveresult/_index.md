---
title: SaveResult
second_title: Aspose.Email for Java API Reference
description: The result of saving a message with .
type: docs
weight: 655
url: /java/com.aspose.email/saveresult/
---

**Inheritance:**
java.lang.Object
```
public class SaveResult
```

The result of saving a message with [PersonalStorage.tryToSaveMessage(String, OutputStream)](../../com.aspose.email/personalstorage\#tryToSaveMessage-String--OutputStream-).
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttachments()](#getAttachments--) | Gets the results of saving the attachments of the message. |
| [getClass()](#getClass--) |  |
| [getMissedProperties()](#getMissedProperties--) | Gets the properties that could not be read. |
| [getStatus()](#getStatus--) | Gets whether the message was saved completely, partially or not at all. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
public final List<SaveResult> getAttachments()
```


Gets the results of saving the attachments of the message.

**Returns:**
java.util.List<com.aspose.email.SaveResult> - The list of [SaveResult](../../com.aspose.email/saveresult).
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getMissedProperties() {#getMissedProperties--}
```
public final List<PropertyDescriptor> getMissedProperties()
```


Gets the properties that could not be read.

**Returns:**
java.util.List<com.aspose.email.PropertyDescriptor> - The list of [PropertyDescriptor](../../com.aspose.email/propertydescriptor).
### getStatus() {#getStatus--}
```
public final int getStatus()
```


Gets whether the message was saved completely, partially or not at all.

**Returns:**
int - The [SaveStatus](../../com.aspose.email/savestatus).
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

