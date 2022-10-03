---
title: ContentDisposition
second_title: Aspose.Email for Java API Reference
description: Represents a Content-Disposition header.
type: docs
weight: 126
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
| [getDispositionType()](#getDispositionType--) | Gets or sets the type of the disposition. |
| [setDispositionType(String value)](#setDispositionType-java.lang.String-) | Gets or sets the type of the disposition. |
| [getParameters()](#getParameters--) | Gets the parameters. |
| [getFileName()](#getFileName--) | Gets or sets the file name for an attachment. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Gets or sets the file name for an attachment. |
| [getCreationDate()](#getCreationDate--) | Gets or sets the creation date. |
| [setCreationDate(Date value)](#setCreationDate-java.util.Date-) | Gets or sets the creation date. |
| [getModificationDate()](#getModificationDate--) | Gets or sets the modification date. |
| [setModificationDate(Date value)](#setModificationDate-java.util.Date-) | Gets or sets the modification date. |
| [getInline()](#getInline--) | Gets or sets a value that determines the disposition type. |
| [setInline(boolean value)](#setInline-boolean-) | Gets or sets a value that determines the disposition type. |
| [getReadDate()](#getReadDate--) | Gets or sets the read date. |
| [setReadDate(Date value)](#setReadDate-java.util.Date-) | Gets or sets the read date. |
| [getSize()](#getSize--) | Gets or sets the size of a file attachment. |
| [setSize(long value)](#setSize-long-) | Gets or sets the size of a file attachment. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to this instance. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
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

### getDispositionType() {#getDispositionType--}
```
public final String getDispositionType()
```


Gets or sets the type of the disposition.

Value: The String that contains the disposition type.

**Returns:**
java.lang.String
### setDispositionType(String value) {#setDispositionType-java.lang.String-}
```
public final void setDispositionType(String value)
```


Gets or sets the type of the disposition.

Value: The String that contains the disposition type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getParameters() {#getParameters--}
```
public final TrackingStringDictionary getParameters()
```


Gets the parameters.

Value: A StringDictionary that contains parameter name/value pairs.

**Returns:**
[TrackingStringDictionary](../../com.aspose.email/trackingstringdictionary)
### getFileName() {#getFileName--}
```
public final String getFileName()
```


Gets or sets the file name for an attachment.

Value: The name of the file.

**Returns:**
java.lang.String
### setFileName(String value) {#setFileName-java.lang.String-}
```
public final void setFileName(String value)
```


Gets or sets the file name for an attachment.

Value: The name of the file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreationDate() {#getCreationDate--}
```
public final Date getCreationDate()
```


Gets or sets the creation date.

Value: A DateTime value that indicates the file creation date; otherwise, MinValue if no date was specified.

**Returns:**
java.util.Date
### setCreationDate(Date value) {#setCreationDate-java.util.Date-}
```
public final void setCreationDate(Date value)
```


Gets or sets the creation date.

Value: A DateTime value that indicates the file creation date; otherwise, MinValue if no date was specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getModificationDate() {#getModificationDate--}
```
public final Date getModificationDate()
```


Gets or sets the modification date.

Value: A DateTime value that indicates the file modification date; otherwise, MinValue if no date was specified.

**Returns:**
java.util.Date
### setModificationDate(Date value) {#setModificationDate-java.util.Date-}
```
public final void setModificationDate(Date value)
```


Gets or sets the modification date.

Value: A DateTime value that indicates the file modification date; otherwise, MinValue if no date was specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getInline() {#getInline--}
```
public final boolean getInline()
```


Gets or sets a value that determines the disposition type.

Value: true if content in the attachment is presented inline; otherwise, false.

**Returns:**
boolean
### setInline(boolean value) {#setInline-boolean-}
```
public final void setInline(boolean value)
```


Gets or sets a value that determines the disposition type.

Value: true if content in the attachment is presented inline; otherwise, false.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getReadDate() {#getReadDate--}
```
public final Date getReadDate()
```


Gets or sets the read date.

Value: A DateTime value that indicates the file read date; otherwise, MinValue if no date was specified.

**Returns:**
java.util.Date
### setReadDate(Date value) {#setReadDate-java.util.Date-}
```
public final void setReadDate(Date value)
```


Gets or sets the read date.

Value: A DateTime value that indicates the file read date; otherwise, MinValue if no date was specified.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |

### getSize() {#getSize--}
```
public final long getSize()
```


Gets or sets the size of a file attachment.

Value: A Int32 that specifies the number of bytes in the file attachment.

**Returns:**
long
### setSize(long value) {#setSize-long-}
```
public final void setSize(long value)
```


Gets or sets the size of a file attachment.

Value: A Int32 that specifies the number of bytes in the file attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### toString() {#toString--}
```
public String toString()
```


Returns a String that represents this instance.

**Returns:**
java.lang.String - A String that represents this instance.
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
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
