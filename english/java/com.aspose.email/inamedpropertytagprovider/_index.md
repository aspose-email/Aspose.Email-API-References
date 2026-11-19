---
title: INamedPropertyTagProvider
second_title: Aspose.Email for Java API Reference
description: Provides property tags for named properties so that a named property can be stored in a property collection.
type: docs
weight: 802
url: /java/com.aspose.email/inamedpropertytagprovider/
---
```
public interface INamedPropertyTagProvider
```

Provides property tags for named properties, so that a named property can be stored in a property collection.

A named property is identified by a property set GUID and a name or numeric ID; inside a message it is stored under a tag from the range  0x8000 \\u2013 0xFFFE , assigned by the message. [MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) implements this interface.
## Methods

| Method | Description |
| --- | --- |
| [generateNamedPropertyTag(long dataType)](#generateNamedPropertyTag-long-) | Generates named property tag |
| [getTagFromNamedProperty(String name)](#getTagFromNamedProperty-java.lang.String-) | Gets the tag under which a named property with a string name is stored. |
| [getTagFromNamedProperty(long LId)](#getTagFromNamedProperty-long-) | Gets the tag under which a named property with a numeric ID is stored. |
### generateNamedPropertyTag(long dataType) {#generateNamedPropertyTag-long-}
```
public abstract long generateNamedPropertyTag(long dataType)
```


Generates named property tag

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataType | long | Named property data type |

**Returns:**
long - Returns tag for named property for current tag provider
### getTagFromNamedProperty(String name) {#getTagFromNamedProperty-java.lang.String-}
```
public abstract long getTagFromNamedProperty(String name)
```


Gets the tag under which a named property with a string name is stored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the named property. |

**Returns:**
long - The property tag.
### getTagFromNamedProperty(long LId) {#getTagFromNamedProperty-long-}
```
public abstract long getTagFromNamedProperty(long LId)
```


Gets the tag under which a named property with a numeric ID is stored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| LId | long | The numeric ID (LID) of the named property. |

**Returns:**
long - The property tag.
