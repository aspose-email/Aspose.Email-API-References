---
title: PropertyDescriptor
second_title: Aspose.Email for Android via Java API Reference
description:  Class contains property description information.
type: docs
weight: 355
url: /java/com.aspose.email/propertydescriptor/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class PropertyDescriptor implements System.IEquatable<PropertyDescriptor>
```

Class contains property description information.
## Methods

| Method | Description |
| --- | --- |
| [getUse8BitStringAsUnicode()](#getUse8BitStringAsUnicode--) | Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String |
| [setUse8BitStringAsUnicode(boolean value)](#setUse8BitStringAsUnicode-boolean-) | Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String |
| [parse(String data)](#parse-java.lang.String-) | Initializes a new instance of the [PropertyDescriptor](../../com.aspose.email/propertydescriptor) class |
| [getDataType()](#getDataType--) | The property value type, as described in [MS-OXCDATA], that specifies the type of values allowed for the property. |
| [getMultipleValuesDataType()](#getMultipleValuesDataType--) | Indicates if data type contains of multiple values |
| [getCanonicalName()](#getCanonicalName--) | The name used to refer to the property in the documentation. |
| [getName()](#getName--) | Gets string that, identifies a property. |
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | Indicates whether the current object is equal to another object of the same type. |
| [op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [getInstance(int id, int dataType)](#getInstance-int-int-) | Retrieves [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object |
| [getInstance(long tag)](#getInstance-long-) | Retrieves [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object |
| [getInstance(long lid, int dataType, UUID propertySet)](#getInstance-long-int-java.util.UUID-) | Retrieves [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) object |
| [getInstance(String name, int dataType, UUID propertySet)](#getInstance-java.lang.String-int-java.util.UUID-) | Retrieves [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) object |
| [getInstance(MapiProperty property)](#getInstance-com.aspose.email.MapiProperty-) | Retrieves [PropertyDescriptor](../../com.aspose.email/propertydescriptor) object from MAPI property |
### getUse8BitStringAsUnicode() {#getUse8BitStringAsUnicode--}
```
public static boolean getUse8BitStringAsUnicode()
```


Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String

**Returns:**
boolean
### setUse8BitStringAsUnicode(boolean value) {#setUse8BitStringAsUnicode-boolean-}
```
public static void setUse8BitStringAsUnicode(boolean value)
```


Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### parse(String data) {#parse-java.lang.String-}
```
public static PropertyDescriptor parse(String data)
```


Initializes a new instance of the [PropertyDescriptor](../../com.aspose.email/propertydescriptor) class

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | java.lang.String | A string that represents the property description. |

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor)
### getDataType() {#getDataType--}
```
public final int getDataType()
```


The property value type, as described in [MS-OXCDATA], that specifies the type of values allowed for the property.

**Returns:**
int
### getMultipleValuesDataType() {#getMultipleValuesDataType--}
```
public final boolean getMultipleValuesDataType()
```


Indicates if data type contains of multiple values

**Returns:**
boolean
### getCanonicalName() {#getCanonicalName--}
```
public final String getCanonicalName()
```


The name used to refer to the property in the documentation. The prefix of the canonical name identifies the basic characteristics of a property to the implementer. The canonical naming structure uses three categories that are denoted by the following prefixes to the canonical property name: \* PidLid prefix: Properties identified by an unsigned 32-bit quantity along with a property set. \* PidName prefix: Properties identified by a string name along with a property set. \* PidTag prefix: Properties identified by an unsigned 16-bit quantity.

**Returns:**
java.lang.String
### getName() {#getName--}
```
public final String getName()
```


Gets string that, identifies a property.

**Returns:**
java.lang.String
### equals(PropertyDescriptor other) {#equals-com.aspose.email.PropertyDescriptor-}
```
public abstract boolean equals(PropertyDescriptor other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | An object to compare with this object. |

**Returns:**
boolean - true if the current object is equal to the other parameter; otherwise, false.
### op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)
```


Determines whether the specified objects are equal to each another.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd1 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The object to compare with another object. |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The object to compare with another object. |

**Returns:**
boolean - true if the specified PropertyDescriptor is equal to the another PropertyDescriptor; otherwise, false.
### op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)
```


Determines whether the specified objects are not equal to each another.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd1 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The object to compare with another object. |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The object to compare with another object. |

**Returns:**
boolean - true if the specified PropertyDescriptor is not equal to the another PropertyDescriptor; otherwise, false.
### getInstance(int id, int dataType) {#getInstance-int-int-}
```
public static PidTagPropertyDescriptor getInstance(int id, int dataType)
```


Retrieves [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | Id of a property |
| dataType | int | Data type of a property |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) - [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object
### getInstance(long tag) {#getInstance-long-}
```
public static PidTagPropertyDescriptor getInstance(long tag)
```


Retrieves [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | Tag of a property |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) - [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object
### getInstance(long lid, int dataType, UUID propertySet) {#getInstance-long-int-java.util.UUID-}
```
public static PidLidPropertyDescriptor getInstance(long lid, int dataType, UUID propertySet)
```


Retrieves [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lid | long | Long id of a property |
| dataType | int | Data type of a property |
| propertySet | java.util.UUID | PropertySet of a property |

**Returns:**
[PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) - [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) object
### getInstance(String name, int dataType, UUID propertySet) {#getInstance-java.lang.String-int-java.util.UUID-}
```
public static PidNamePropertyDescriptor getInstance(String name, int dataType, UUID propertySet)
```


Retrieves [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) object

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of a property |
| dataType | int | Data type of a property |
| propertySet | java.util.UUID | PropertySet of a property |

**Returns:**
[PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) - [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) object
### getInstance(MapiProperty property) {#getInstance-com.aspose.email.MapiProperty-}
```
public static PropertyDescriptor getInstance(MapiProperty property)
```


Retrieves [PropertyDescriptor](../../com.aspose.email/propertydescriptor) object from MAPI property

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | [MapiProperty](../../com.aspose.email/mapiproperty) object |

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor)