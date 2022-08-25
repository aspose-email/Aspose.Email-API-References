---
title: ContentType
second_title: Aspose.Email for Android via Java API Reference
description:  Represents a Content-Type header.
type: docs
weight: 86
url: /java/com.aspose.email/contenttype/
---
**Inheritance:**
java.lang.Object
```
public class ContentType
```

Represents a Content-Type header.
## Constructors

| Constructor | Description |
| --- | --- |
| [ContentType()](#ContentType--) | Initializes a new instance of the [ContentType](../../com.aspose.email/contenttype) class. |
| [ContentType(String contentType)](#ContentType-java.lang.String-) | Initializes a new instance of the [ContentType](../../com.aspose.email/contenttype) class. |
## Methods

| Method | Description |
| --- | --- |
| [getBoundary()](#getBoundary--) | Gets or sets the value of the boundary parameter included in the Content-Type header. |
| [setBoundary(String value)](#setBoundary-java.lang.String-) | Gets or sets the value of the boundary parameter included in the Content-Type header. |
| [getCharSet()](#getCharSet--) | Gets or sets the value of the charset parameter. |
| [setCharSet(String value)](#setCharSet-java.lang.String-) | Gets or sets the value of the charset parameter. |
| [getMediaType()](#getMediaType--) | Gets or sets the internet media type. |
| [setMediaType(String value)](#setMediaType-java.lang.String-) | Gets or sets the internet media type. |
| [getName()](#getName--) | Gets or sets the value of the name parameter. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the value of the name parameter. |
| [getParameters()](#getParameters--) | Gets the dictionary that contains the parameters. |
| [toString()](#toString--) | Returns a String that represents this instance. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified Object is equal to this instance. |
| [hashCode()](#hashCode--) | Returns a hash code for this instance. |
### ContentType() {#ContentType--}
```
public ContentType()
```


Initializes a new instance of the [ContentType](../../com.aspose.email/contenttype) class.

### ContentType(String contentType) {#ContentType-java.lang.String-}
```
public ContentType(String contentType)
```


Initializes a new instance of the [ContentType](../../com.aspose.email/contenttype) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| contentType | java.lang.String | Type of the content. |

### getBoundary() {#getBoundary--}
```
public final String getBoundary()
```


Gets or sets the value of the boundary parameter included in the Content-Type header.

Value: A string that contains the value of boundary parameter.

**Returns:**
java.lang.String
### setBoundary(String value) {#setBoundary-java.lang.String-}
```
public final void setBoundary(String value)
```


Gets or sets the value of the boundary parameter included in the Content-Type header.

Value: A string that contains the value of boundary parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getCharSet() {#getCharSet--}
```
public final String getCharSet()
```


Gets or sets the value of the charset parameter.

Value: A string that contains the value of charset parameter.

**Returns:**
java.lang.String
### setCharSet(String value) {#setCharSet-java.lang.String-}
```
public final void setCharSet(String value)
```


Gets or sets the value of the charset parameter.

Value: A string that contains the value of charset parameter.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getMediaType() {#getMediaType--}
```
public final String getMediaType()
```


Gets or sets the internet media type.

Value: A String that contains the media type.

**Returns:**
java.lang.String
### setMediaType(String value) {#setMediaType-java.lang.String-}
```
public final void setMediaType(String value)
```


Gets or sets the internet media type.

Value: A String that contains the media type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getName() {#getName--}
```
public final String getName()
```


Gets or sets the value of the name parameter.

Value: A String that contains the name.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gets or sets the value of the name parameter.

Value: A String that contains the name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getParameters() {#getParameters--}
```
public final TrackingStringDictionary getParameters()
```


Gets the dictionary that contains the parameters.

Value: A StringDictionary that contains name and value pairs.

**Returns:**
[TrackingStringDictionary](../../com.aspose.email/trackingstringdictionary)
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
boolean - \`\`\` true \`\`\` if the specified Object is equal to this instance; otherwise, \`\`\` false \`\`\`.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns a hash code for this instance.

**Returns:**
int - A hash code for this instance, suitable for use in hashing algorithms and data structures like a hash table.
