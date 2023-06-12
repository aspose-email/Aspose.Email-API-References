---
title: INamedPropertyTagProvider
second_title: Aspose.Email for Java API Reference
description: Interface of named mapi property tag provider.
type: docs
weight: 753
url: /java/com.aspose.email/inamedpropertytagprovider/
---
```
public interface INamedPropertyTagProvider
```

Interface of named mapi property tag provider.
## Methods

| Method | Description |
| --- | --- |
| [generateNamedPropertyTag(long dataType)](#generateNamedPropertyTag-long-) | Generates named property tag |
| [getTagFromNamedProperty(String name)](#getTagFromNamedProperty-java.lang.String-) | Gets the tag from named property. |
| [getTagFromNamedProperty(long LId)](#getTagFromNamedProperty-long-) | Gets the tag from named property. |
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


Gets the tag from named property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The property name |

**Returns:**
long - The property tag value.
### getTagFromNamedProperty(long LId) {#getTagFromNamedProperty-long-}
```
public abstract long getTagFromNamedProperty(long LId)
```


Gets the tag from named property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| LId | long | The property id. |

**Returns:**
long - The property tag value.
