---
title: PidTagPropertyDescriptor
second_title: Aspose.Email for Java API Reference
description:  Class contains property description information.
type: docs
weight: 561
url: /java/com.aspose.email/pidtagpropertydescriptor/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.PropertyDescriptor](../../com.aspose.email/propertydescriptor)
```
public class PidTagPropertyDescriptor extends PropertyDescriptor
```

Class contains property description information.
## Constructors

| Constructor | Description |
| --- | --- |
| [PidTagPropertyDescriptor(int id, int type)](#PidTagPropertyDescriptor-int-int-) | Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class A property that is defined by a 16-bit property ID and a 16-bit property type. |
| [PidTagPropertyDescriptor(String canonicalName, int id, int type)](#PidTagPropertyDescriptor-java.lang.String-int-int-) | Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class A property that is defined by a 16-bit property ID and a 16-bit property type. |
| [PidTagPropertyDescriptor(String canonicalName, String name, int id, int type)](#PidTagPropertyDescriptor-java.lang.String-java.lang.String-int-int-) | Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class A property that is defined by a 16-bit property ID and a 16-bit property type. |
| [PidTagPropertyDescriptor(long tag)](#PidTagPropertyDescriptor-long-) | Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class A property that is defined by a 16-bit property ID and a 16-bit property type. |
| [PidTagPropertyDescriptor(String canonicalName, String name, long tag)](#PidTagPropertyDescriptor-java.lang.String-java.lang.String-long-) | Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class A property that is defined by a 16-bit property ID and a 16-bit property type. |
## Methods

| Method | Description |
| --- | --- |
| [getId()](#getId--) | Gets an unsigned 16-bit quantity that identifies a tagged property. |
| [getTag()](#getTag--) | A property tag is a 32-bit number that contains a unique property identifier in bits 16 through 31 and a property type in bits 0 through 15. |
| [op_Equality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [to_PidTagPropertyDescriptor(long tag)](#to-PidTagPropertyDescriptor-long-) | Converts tag value to tagged property |
| [op_Inequality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [equals(Object other)](#equals-java.lang.Object-) | Determines whether the specified System.Object is equal to the current System.Object. |
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | Indicates whether the current object is equal to another object of the same type. |
| [hashCode()](#hashCode--) | Serves as a hash function for a type. |
| [toString()](#toString--) | Returns a string that represents the property description. |
### PidTagPropertyDescriptor(int id, int type) {#PidTagPropertyDescriptor-int-int-}
```
public PidTagPropertyDescriptor(int id, int type)
```


Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 \\u2013 0x7FFF. Property IDs in the range 0x8000 \\u2013 0x8FFF are reserved for assignment to named properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | Unsigned 16-bit quantity that identifies a tagged property. |
| type | int | Specifies the type of values allowed for the property. |

### PidTagPropertyDescriptor(String canonicalName, int id, int type) {#PidTagPropertyDescriptor-java.lang.String-int-int-}
```
public PidTagPropertyDescriptor(String canonicalName, int id, int type)
```


Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 \\u2013 0x7FFF. Property IDs in the range 0x8000 \\u2013 0x8FFF are reserved for assignment to named properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canonicalName | java.lang.String | The name used to refer to the property in the documentation. |
| id | int | Unsigned 16-bit quantity that identifies a tagged property. |
| type | int | Specifies the type of values allowed for the property. |

### PidTagPropertyDescriptor(String canonicalName, String name, int id, int type) {#PidTagPropertyDescriptor-java.lang.String-java.lang.String-int-int-}
```
public PidTagPropertyDescriptor(String canonicalName, String name, int id, int type)
```


Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 \\u2013 0x7FFF. Property IDs in the range 0x8000 \\u2013 0x8FFF are reserved for assignment to named properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canonicalName | java.lang.String | The name used to refer to the property in the documentation. |
| name | java.lang.String | The MAPI name used to refer to the property in the documentation. |
| id | int | Unsigned 16-bit quantity that identifies a tagged property. |
| type | int | Specifies the type of values allowed for the property. |

### PidTagPropertyDescriptor(long tag) {#PidTagPropertyDescriptor-long-}
```
public PidTagPropertyDescriptor(long tag)
```


Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 \\u2013 0x7FFF. Property IDs in the range 0x8000 \\u2013 0x8FFF are reserved for assignment to named properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | A tag is a 32-bit number that contains a unique property identifier in bits 16 through 31 and a property type in bits 0 through 15 |

### PidTagPropertyDescriptor(String canonicalName, String name, long tag) {#PidTagPropertyDescriptor-java.lang.String-java.lang.String-long-}
```
public PidTagPropertyDescriptor(String canonicalName, String name, long tag)
```


Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class A property that is defined by a 16-bit property ID and a 16-bit property type. The property ID for a tagged property is in the range 0x001 \\u2013 0x7FFF. Property IDs in the range 0x8000 \\u2013 0x8FFF are reserved for assignment to named properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canonicalName | java.lang.String | The name used to refer to the property in the documentation. |
| name | java.lang.String | The MAPI name used to refer to the property in the documentation. |
| tag | long | A tag is a 32-bit number that contains a unique property identifier in bits 16 through 31 and a property type in bits 0 through 15 |

### getId() {#getId--}
```
public final int getId()
```


Gets an unsigned 16-bit quantity that identifies a tagged property. Property IDs are not necessarily unique. With the exception of property IDs in the range from 0x6800 to 0x7BFF, the combination of property ID and data type are unique. Property IDs in the range from 0x6800 to 0x7BFF are defined by the message class.

**Returns:**
int
### getTag() {#getTag--}
```
public final long getTag()
```


A property tag is a 32-bit number that contains a unique property identifier in bits 16 through 31 and a property type in bits 0 through 15.

**Returns:**
long
### op_Equality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Equality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Equality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)
```


Determines whether the specified objects are equal to each another.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd1 | [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) | The object to compare with another object. |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The object to compare with another object. |

**Returns:**
boolean - true if the specified PropertyDescriptor is equal to the another PropertyDescriptor; otherwise, false.
### to_PidTagPropertyDescriptor(long tag) {#to-PidTagPropertyDescriptor-long-}
```
public static PidTagPropertyDescriptor to_PidTagPropertyDescriptor(long tag)
```


Converts tag value to tagged property

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | tag value of a tag property |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor)
### op_Inequality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Inequality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Inequality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)
```


Determines whether the specified objects are not equal to each another.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd1 | [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) | The object to compare with another object. |
| pd2 | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The object to compare with another object. |

**Returns:**
boolean - true if the specified PropertyDescriptor is not equal to the another PropertyDescriptor; otherwise, false.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Determines whether the specified System.Object is equal to the current System.Object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object |  |

**Returns:**
boolean - true if the specified System.Object is equal to the current System.Object; otherwise, false.
### equals(PropertyDescriptor other) {#equals-com.aspose.email.PropertyDescriptor-}
```
public boolean equals(PropertyDescriptor other)
```


Indicates whether the current object is equal to another object of the same type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | An object to compare with this object. |

**Returns:**
boolean - true if the current object is equal to the other parameter; otherwise, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a type.

**Returns:**
int - A hash code for the current object.
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the property description.

**Returns:**
java.lang.String - A string that represents the property description.
