---
title: ContentDisposition
second_title: Aspose.Email for Java API Reference
description: Represents a Content-Disposition header.
type: docs
weight: 129
url: /java/com.aspose.email/contentdisposition/
---

**Inheritance:**
java.lang.Object
```
public class ContentDisposition
```

Represents a Content-Disposition header.
## Constructors

| Constructor | Description |
| --- | --- |
| [ContentDisposition()](#ContentDisposition--) | Initializes a new instance of the [ContentDisposition](../../com.aspose.email/contentdisposition) class. |
| [ContentDisposition(String disposition)](#ContentDisposition-java.lang.String-) | Initializes a new instance of the [ContentDisposition](../../com.aspose.email/contentdisposition) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to this instance. |
| [getClass()](#getClass--) |  |
| [getCreationDate()](#getCreationDate--) | Gets the creation date. |
| [getDispositionType()](#getDispositionType--) | Gets the type of the disposition. |
| [getFileName()](#getFileName--) | Gets the file name for an attachment. |
| [getInline()](#getInline--) | Gets a value that determines the disposition type. |
| [getModificationDate()](#getModificationDate--) | Gets the modification date. |
| [getParameters()](#getParameters--) | Gets the parameters. |
| [getReadDate()](#getReadDate--) | Gets the read date. |
| [getSize()](#getSize--) | Gets the size of a file attachment. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Sets the creation date. |
| [setDispositionType(String value)](#setDispositionType-java.lang.String-) | Sets the type of the disposition. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Sets the file name for an attachment. |
| [setInline(boolean value)](#setInline-boolean-) | Sets a value that determines the disposition type. |
| [setModificationDate(Date value)](#setModificationDate-java.util.Date-) | Sets the modification date. |
| [setReadDate(Date value)](#setReadDate-java.util.Date-) | Sets the read date. |
| [setSize(long value)](#setSize-long-) | Sets the size of a file attachment. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ContentDisposition() {#ContentDisposition--}
```
public ContentDisposition()
```


Initializes a new instance of the [ContentDisposition](../../com.aspose.email/contentdisposition) class.

### ContentDisposition(String disposition) {#ContentDisposition-java.lang.String-}
```
public ContentDisposition(String disposition)
```


Initializes a new instance of the [ContentDisposition](../../com.aspose.email/contentdisposition) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| disposition | java.lang.String | A value that contains the disposition. |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines whether the specified Object is equal to this instance.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The Object to compare with this instance. |

**Returns:**
boolean -  true  if the specified Object is equal to this instance; otherwise,  false .
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreationDate() {#getCreationDate--}
```
public final Date getCreationDate()
```


Gets the creation date.

**Returns:**
java.util.Date - A java.util.Date value that indicates the file creation date; otherwise, MinValue if no date was specified.
### getDispositionType() {#getDispositionType--}
```
public final String getDispositionType()
```


Gets the type of the disposition.

**Returns:**
java.lang.String - The  String  that contains the disposition type.
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Gets the file name for an attachment.

**Returns:**
java.lang.String - The name of the file.
### getInline() {#getInline--}
```
public final boolean getInline()
```


Gets a value that determines the disposition type.

**Returns:**
boolean -  true  if content in the attachment is presented inline; otherwise,  false .
### getModificationDate() {#getModificationDate--}
```
public final Date getModificationDate()
```


Gets the modification date.

**Returns:**
java.util.Date - A java.util.Date value that indicates the file modification date; otherwise, MinValue if no date was specified.
### getParameters() {#getParameters--}
```
public final TrackingStringDictionary getParameters()
```


Gets the parameters.

**Returns:**
[TrackingStringDictionary](../../com.aspose.email/trackingstringdictionary) - A [TrackingStringDictionary](../../com.aspose.email/trackingstringdictionary) that contains parameter name/value pairs.
### getReadDate() {#getReadDate--}
```
public final Date getReadDate()
```


Gets the read date.

**Returns:**
java.util.Date - A java.util.Date value that indicates the file read date; otherwise, MinValue if no date was specified.
### getSize() {#getSize--}
```
public final long getSize()
```


Gets the size of a file attachment.

**Returns:**
long - The number of bytes in the file attachment.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public final void setCreationDate(Date value)
```


Sets the creation date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | A java.util.Date value that indicates the file creation date; otherwise, MinValue if no date was specified. |

### setDispositionType(String value) {#setDispositionType-java.lang.String-}
```
public final void setDispositionType(String value)
```


Sets the type of the disposition.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The  String  that contains the disposition type. |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Sets the file name for an attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the file. |

### setInline(boolean value) {#setInline-boolean-}
```
public final void setInline(boolean value)
```


Sets a value that determines the disposition type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  true  if content in the attachment is presented inline; otherwise,  false . |

### setModificationDate(Date value) {#setModificationDate-java.util.Date-}
```
public final void setModificationDate(Date value)
```


Sets the modification date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | A java.util.Date value that indicates the file modification date; otherwise, MinValue if no date was specified. |

### setReadDate(Date value) {#setReadDate-java.util.Date-}
```
public final void setReadDate(Date value)
```


Sets the read date.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | A java.util.Date value that indicates the file read date; otherwise, MinValue if no date was specified. |

### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Sets the size of a file attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The number of bytes in the file attachment. |

### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
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

