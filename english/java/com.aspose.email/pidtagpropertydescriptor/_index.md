---
title: PidTagPropertyDescriptor
second_title: Aspose.Email for Java API Reference
description: Class contains property description information.
type: docs
weight: 568
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
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | Indicates whether the current object is equal to another object of the same type. |
| [equals(Object other)](#equals-java.lang.Object-) | Determines whether the specified System.Object is equal to the current System.Object. |
| [getCanonicalName()](#getCanonicalName--) | The name used to refer to the property in the documentation. |
| [getClass()](#getClass--) |  |
| [getDataType()](#getDataType--) | The property value type, as described in [MS-OXCDATA], that specifies the type of values allowed for the property. |
| [getId()](#getId--) | Gets an unsigned 16-bit quantity that identifies a tagged property. |
| [getInstance(MapiProperty property)](#getInstance-com.aspose.email.MapiProperty-) | Retrieves [PropertyDescriptor](../../com.aspose.email/propertydescriptor) object from MAPI property |
| [getInstance(int id, int dataType)](#getInstance-int-int-) | Retrieves [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object |
| [getInstance(String name, int dataType, UUID propertySet)](#getInstance-java.lang.String-int-java.util.UUID-) | Retrieves [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) object |
| [getInstance(long tag)](#getInstance-long-) | Retrieves [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object |
| [getInstance(long lid, int dataType, UUID propertySet)](#getInstance-long-int-java.util.UUID-) | Retrieves [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) object |
| [getMultipleValuesDataType()](#getMultipleValuesDataType--) | Indicates if data type contains of multiple values |
| [getName()](#getName--) | Gets string that, identifies a property. |
| [getTag()](#getTag--) | A property tag is a 32-bit number that contains a unique property identifier in bits 16 through 31 and a property type in bits 0 through 15. |
| [getUse8BitStringAsUnicode()](#getUse8BitStringAsUnicode--) | Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String |
| [hashCode()](#hashCode--) | Serves as a hash function for a type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [op_Inequality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [parse(String data)](#parse-java.lang.String-) | Initializes a new instance of the [PropertyDescriptor](../../com.aspose.email/propertydescriptor) class |
| [setUse8BitStringAsUnicode(boolean value)](#setUse8BitStringAsUnicode-boolean-) | Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String |
| [toString()](#toString--) | Returns a string that represents the property description. |
| [to_PidTagPropertyDescriptor(long tag)](#to-PidTagPropertyDescriptor-long-) | Converts tag value to tagged property |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getCanonicalName() {#getCanonicalName--}
```
public final String getCanonicalName()
```


The name used to refer to the property in the documentation. The prefix of the canonical name identifies the basic characteristics of a property to the implementer. The canonical naming structure uses three categories that are denoted by the following prefixes to the canonical property name: \* PidLid prefix: Properties identified by an unsigned 32-bit quantity along with a property set. \* PidName prefix: Properties identified by a string name along with a property set. \* PidTag prefix: Properties identified by an unsigned 16-bit quantity.

**Returns:**
java.lang.String
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDataType() {#getDataType--}
```
public final int getDataType()
```


The property value type, as described in [MS-OXCDATA], that specifies the type of values allowed for the property.

**Returns:**
int
### getId() {#getId--}
```
public final int getId()
```


Gets an unsigned 16-bit quantity that identifies a tagged property. Property IDs are not necessarily unique. With the exception of property IDs in the range from 0x6800 to 0x7BFF, the combination of property ID and data type are unique. Property IDs in the range from 0x6800 to 0x7BFF are defined by the message class.

**Returns:**
int
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
### getMultipleValuesDataType() {#getMultipleValuesDataType--}
```
public final boolean getMultipleValuesDataType()
```


Indicates if data type contains of multiple values

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


Gets string that, identifies a property.

**Returns:**
java.lang.String
### getTag() {#getTag--}
```
public final long getTag()
```


A property tag is a 32-bit number that contains a unique property identifier in bits 16 through 31 and a property type in bits 0 through 15.

**Returns:**
long
### getUse8BitStringAsUnicode() {#getUse8BitStringAsUnicode--}
```
public static boolean getUse8BitStringAsUnicode()
```


Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serves as a hash function for a type.

**Returns:**
int - A hash code for the current object.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
### setUse8BitStringAsUnicode(boolean value) {#setUse8BitStringAsUnicode-boolean-}
```
public static void setUse8BitStringAsUnicode(boolean value)
```


Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the property description.

**Returns:**
java.lang.String - A string that represents the property description.
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

