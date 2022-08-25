---
title: BaseDataObject
second_title: Aspose.Email for Java API Reference
description:  Base class for google data objects.
type: docs
weight: 77
url: /java/com.aspose.email/basedataobject/
---
**Inheritance:**
java.lang.Object
```
public abstract class BaseDataObject
```

Base class for google data objects.
## Constructors

| Constructor | Description |
| --- | --- |
| [BaseDataObject(String kind)](#BaseDataObject-java.lang.String-) | Initializes a new instance of the class. |
| [BaseDataObject(String kind, String id)](#BaseDataObject-java.lang.String-java.lang.String-) | Initializes a new instance of the class. |
| [BaseDataObject(String kind, String id, String eTag)](#BaseDataObject-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the class. |
## Methods

| Method | Description |
| --- | --- |
| [getKind()](#getKind--) | Type of the resource |
| [getETag()](#getETag--) | An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. |
| [setETag(String value)](#setETag-java.lang.String-) | An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. |
| [getId()](#getId--) | Identifier of the resource. |
| [setId(String value)](#setId-java.lang.String-) | Identifier of the resource. |
### BaseDataObject(String kind) {#BaseDataObject-java.lang.String-}
```
public BaseDataObject(String kind)
```


Initializes a new instance of the class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kind | java.lang.String | Type of the resource |

### BaseDataObject(String kind, String id) {#BaseDataObject-java.lang.String-java.lang.String-}
```
public BaseDataObject(String kind, String id)
```


Initializes a new instance of the class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kind | java.lang.String | Type of the resource |
| id | java.lang.String | Identifier of the resource. |

### BaseDataObject(String kind, String id, String eTag) {#BaseDataObject-java.lang.String-java.lang.String-java.lang.String-}
```
public BaseDataObject(String kind, String id, String eTag)
```


Initializes a new instance of the class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| kind | java.lang.String | Type of the resource |
| id | java.lang.String | Identifier of the resource. |
| eTag | java.lang.String | An entity tag |

### getKind() {#getKind--}
```
public String getKind()
```


Type of the resource

**Returns:**
java.lang.String
### getETag() {#getETag--}
```
public String getETag()
```


An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. This allows caches to be more efficient, and saves bandwidth, as a web server does not need to send a full response if the content has not changed. ETags can also be used for optimistic concurrency control, as a way to help prevent simultaneous updates of a resource from overwriting each other.

**Returns:**
java.lang.String
### setETag(String value) {#setETag-java.lang.String-}
```
public void setETag(String value)
```


An ETag or entity tag is one of several mechanisms that HTTP provides for web cache validation, and which allows a client to make conditional requests. This allows caches to be more efficient, and saves bandwidth, as a web server does not need to send a full response if the content has not changed. ETags can also be used for optimistic concurrency control, as a way to help prevent simultaneous updates of a resource from overwriting each other.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getId() {#getId--}
```
public String getId()
```


Identifier of the resource.

**Returns:**
java.lang.String
### setId(String value) {#setId-java.lang.String-}
```
public void setId(String value)
```


Identifier of the resource.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

