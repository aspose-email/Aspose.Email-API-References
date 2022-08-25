---
title: MapiNamedPropertyMappingStorage
second_title: Aspose.Email for Android via Java API Reference
description:  Represents the named property mapping
type: docs
weight: 263
url: /java/com.aspose.email/mapinamedpropertymappingstorage/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer)
```
public final class MapiNamedPropertyMappingStorage extends MapiPropertyContainer
```

Represents the named property mapping
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiNamedPropertyMappingStorage()](#MapiNamedPropertyMappingStorage--) | Initializes a new instance of the [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) class. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets the name |
| [getContent()](#getContent--) | Gets the content |
| [getNextAvailablePropertyId(int dataType)](#getNextAvailablePropertyId-int-) | Gets the next available property id in entries stream based on property datatype. |
| [addNamedPropertyMapping(MapiProperty property, long nameId, UUID guid)](#addNamedPropertyMapping-com.aspose.email.MapiProperty-long-java.util.UUID-) | Adds the named property mapping for numeric named property. |
| [addNamedPropertyMapping(MapiProperty property, String nameId, UUID guid)](#addNamedPropertyMapping-com.aspose.email.MapiProperty-java.lang.String-java.util.UUID-) | Adds the named property mapping for string named property. |
### MapiNamedPropertyMappingStorage() {#MapiNamedPropertyMappingStorage--}
```
public MapiNamedPropertyMappingStorage()
```


Initializes a new instance of the [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) class.

### getName() {#getName--}
```
public final String getName()
```


Gets the name

Value: The name

**Returns:**
java.lang.String
### getContent() {#getContent--}
```
public final Object getContent()
```


Gets the content

Value: The content

**Returns:**
java.lang.Object
### getNextAvailablePropertyId(int dataType) {#getNextAvailablePropertyId-int-}
```
public final long getNextAvailablePropertyId(int dataType)
```


Gets the next available property id in entries stream based on property datatype.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataType | int | Type of the data for the property. |

**Returns:**
long - An id that can be lately used to add property mapping.
### addNamedPropertyMapping(MapiProperty property, long nameId, UUID guid) {#addNamedPropertyMapping-com.aspose.email.MapiProperty-long-java.util.UUID-}
```
public final void addNamedPropertyMapping(MapiProperty property, long nameId, UUID guid)
```


Adds the named property mapping for numeric named property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | The property to add mapping for. |
| nameId | long | The name id. |
| guid | java.util.UUID | The GUID identifying property set.

--------------------

\`\`\` property \`\`\` should have a valid id for named property, \#getNextAvailablePropertyId(int) can be used to generate one. Otherwise an exception will be thrown.

\`\`\`  \{@link ArgumentNullException\} if \{@code property\} is null. \{@link ArgumentException\} if \{@code MapiProperty.Tag\}(\{@link MapiProperty\#getTag\}) can'be used for named property mapping. The range for named property identifiers is between 0x8000 and 0xFFFE.  \`\`\` |

### addNamedPropertyMapping(MapiProperty property, String nameId, UUID guid) {#addNamedPropertyMapping-com.aspose.email.MapiProperty-java.lang.String-java.util.UUID-}
```
public final void addNamedPropertyMapping(MapiProperty property, String nameId, UUID guid)
```


Adds the named property mapping for string named property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | The property to add mapping for. |
| nameId | java.lang.String | The name id. |
| guid | java.util.UUID | The GUID identifying property set.

--------------------

\`\`\` property \`\`\` should have a valid id for named property, \#getNextAvailablePropertyId(int) can be used to generate one. Otherwise an exception will be thrown.

\`\`\`  \{@link ArgumentNullException\} if nameId is null. \{@link ArgumentNullException\} if \{@code property\} is null. \{@link ArgumentException\} if \{@code MapiProperty.Tag\}(\{@link MapiProperty\#getTag\}) can'be used for named property mapping. The range for named property identifiers is between 0x8000 and 0xFFFE.  \`\`\` |

