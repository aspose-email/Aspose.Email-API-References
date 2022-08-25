---
title: MapiNamedProperty
second_title: Aspose.Email for Java API Reference
description:  Represents the data type of Named Property.
type: docs
weight: 449
url: /java/com.aspose.email/mapinamedproperty/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.MapiProperty](../../com.aspose.email/mapiproperty)
```
public final class MapiNamedProperty extends MapiProperty
```

Represents the data type of Named Property.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiNamedProperty()](#MapiNamedProperty--) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class. |
| [MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue)](#MapiNamedProperty-long-java.lang.String-java.util.UUID-byte---) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class. |
| [MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue)](#MapiNamedProperty-long-long-java.util.UUID-byte---) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class. |
| [MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data)](#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class. |
| [MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data)](#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidNamePropertyDescriptor-java.lang.Object-) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class. |
## Methods

| Method | Description |
| --- | --- |
| [getNameId()](#getNameId--) | gets named property ID |
| [getKind()](#getKind--) | gets named property kind |
| [getOom()](#getOom--) | gets OOM value |
| [getGuid()](#getGuid--) | gets named property GUID |
### MapiNamedProperty() {#MapiNamedProperty--}
```
public MapiNamedProperty()
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class.

### MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue) {#MapiNamedProperty-long-java.lang.String-java.util.UUID-byte---}
```
public MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | long | The property tag represented a 32-bit value that contains a property type and a property ID. The low-order 16 bits represent the property type. The high-order 16 bits represent the property ID. |
| nameIdentifier | java.lang.String | The name identifier that is used to refer to a named property. |
| propertyGuid | java.util.UUID | The property unique identifier. |
| propertyValue | byte[] | A property value. |

### MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue) {#MapiNamedProperty-long-long-java.util.UUID-byte---}
```
public MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | long | The property tag represented a 32-bit value that contains a property type and a property ID. The low-order 16 bits represent the property type. The high-order 16 bits represent the property ID. |
| nameIdentifier | long | The name identifier that is used to refer to a named property. |
| propertyGuid | java.util.UUID | The property unique identifier. |
| propertyValue | byte[] | A property value. |

### MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data) {#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-}
```
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagProvider | [INamedPropertyTagProvider](../../com.aspose.email/inamedpropertytagprovider) | Property storage that can provide tag for named property |
| pd | [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) | Property descriptor |
| data | java.lang.Object | A property value. |

### MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data) {#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidNamePropertyDescriptor-java.lang.Object-}
```
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagProvider | [INamedPropertyTagProvider](../../com.aspose.email/inamedpropertytagprovider) | Property storage that can provide tag for named property |
| pd | [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) | Property descriptor |
| data | java.lang.Object | A property value. |

### getNameId() {#getNameId--}
```
public final String getNameId()
```


gets named property ID

**Returns:**
java.lang.String
### getKind() {#getKind--}
```
public final int getKind()
```


gets named property kind

**Returns:**
int
### getOom() {#getOom--}
```
public final String getOom()
```


gets OOM value

**Returns:**
java.lang.String
### getGuid() {#getGuid--}
```
public final UUID getGuid()
```


gets named property GUID

**Returns:**
java.util.UUID
