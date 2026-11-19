---
title: PidTagPropertyDescriptor
second_title: Aspose.Email for Java API Reference
description: Describes a tagged property a property with a fixed 16-bit ID and a 16-bit data type.
type: docs
weight: 598
url: /java/com.aspose.email/pidtagpropertydescriptor/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.PropertyDescriptor](../../com.aspose.email/propertydescriptor)
```
public class PidTagPropertyDescriptor extends PropertyDescriptor
```

Describes a tagged property: a property with a fixed 16-bit ID and a 16-bit data type.

Tagged properties have IDs from  0x0001  to  0x7FFF ; IDs from  0x8000  up are assigned to named properties, which are described by [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) and [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor). Descriptors of the known properties are defined in [KnownPropertyList](../../com.aspose.email/knownpropertylist).
## Constructors

| Constructor | Description |
| --- | --- |
| [PidTagPropertyDescriptor(int id, int type)](#PidTagPropertyDescriptor-int-int-) | Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class. |
| [PidTagPropertyDescriptor(String canonicalName, int id, int type)](#PidTagPropertyDescriptor-java.lang.String-int-int-) | Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class. |
| [PidTagPropertyDescriptor(String canonicalName, String name, int id, int type)](#PidTagPropertyDescriptor-java.lang.String-java.lang.String-int-int-) | Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class. |
| [PidTagPropertyDescriptor(long tag)](#PidTagPropertyDescriptor-long-) | Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class. |
| [PidTagPropertyDescriptor(String canonicalName, String name, long tag)](#PidTagPropertyDescriptor-java.lang.String-java.lang.String-long-) | Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | Determines whether the specified descriptor describes the same property. |
| [equals(Object other)](#equals-java.lang.Object-) | Determines whether the specified object is equal to this descriptor. |
| [getCanonicalName()](#getCanonicalName--) | Gets the canonical name of the property, as in [MS-OXPROPS]. |
| [getClass()](#getClass--) |  |
| [getDataType()](#getDataType--) | Gets the data type of the property value. |
| [getId()](#getId--) | Gets the 16-bit ID of the property. |
| [getInstance(MapiProperty property)](#getInstance-com.aspose.email.MapiProperty-) | Gets the descriptor of a MAPI property. |
| [getInstance(int id, int dataType)](#getInstance-int-int-) | Gets the descriptor of a tagged property by its ID and data type. |
| [getInstance(String name, int dataType, UUID propertySet)](#getInstance-java.lang.String-int-java.util.UUID-) | Gets the descriptor of a named property by its name. |
| [getInstance(long tag)](#getInstance-long-) | Gets the descriptor of a tagged property by its tag. |
| [getInstance(long lid, int dataType, UUID propertySet)](#getInstance-long-int-java.util.UUID-) | Gets the descriptor of a named property by its numeric ID (LID). |
| [getMultipleValuesDataType()](#getMultipleValuesDataType--) | Gets a value indicating whether the property is multi-valued. |
| [getName()](#getName--) | Gets the alternate name of the property, such as  PR\_SUBJECT , or the name of a named property. |
| [getTag()](#getTag--) | Gets the tag of the property: the ID in the high-order 16 bits and the data type in the low-order 16 bits. |
| [getUse8BitStringAsUnicode()](#getUse8BitStringAsUnicode--) | Gets a value indicating whether  String8  (ANSI) values are read as  String  (Unicode). |
| [hashCode()](#hashCode--) | Returns the hash code of the descriptor. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [op_Inequality(PidTagPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PidTagPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [parse(String data)](#parse-java.lang.String-) | Creates a descriptor from its string form, as returned by  toString() , for example  Tag:'PidTagSubject':0x37:String . |
| [setUse8BitStringAsUnicode(boolean value)](#setUse8BitStringAsUnicode-boolean-) | Sets a value indicating whether  String8  (ANSI) values are read as  String  (Unicode). |
| [toString()](#toString--) | Returns a string that describes the property, in the form that [PropertyDescriptor.parse(String)](../../com.aspose.email/propertydescriptor\#parse-String-) accepts. |
| [to_PidTagPropertyDescriptor(long tag)](#to-PidTagPropertyDescriptor-long-) | Converts tag value to tagged property. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PidTagPropertyDescriptor(int id, int type) {#PidTagPropertyDescriptor-int-int-}
```
public PidTagPropertyDescriptor(int id, int type)
```


Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | The 16-bit ID of the property. |
| type | int | The data type of the property. |

### PidTagPropertyDescriptor(String canonicalName, int id, int type) {#PidTagPropertyDescriptor-java.lang.String-int-int-}
```
public PidTagPropertyDescriptor(String canonicalName, int id, int type)
```


Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canonicalName | java.lang.String | The canonical name of the property, such as  PidTagSubject . |
| id | int | The 16-bit ID of the property. |
| type | int | The data type of the property. |

### PidTagPropertyDescriptor(String canonicalName, String name, int id, int type) {#PidTagPropertyDescriptor-java.lang.String-java.lang.String-int-int-}
```
public PidTagPropertyDescriptor(String canonicalName, String name, int id, int type)
```


Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canonicalName | java.lang.String | The canonical name of the property, such as  PidTagSubject . |
| name | java.lang.String | The alternate (MAPI) name of the property, such as  PR\_SUBJECT . |
| id | int | The 16-bit ID of the property. |
| type | int | The data type of the property. |

### PidTagPropertyDescriptor(long tag) {#PidTagPropertyDescriptor-long-}
```
public PidTagPropertyDescriptor(long tag)
```


Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property: the ID in the high-order 16 bits and the data type in the low-order 16 bits. |

### PidTagPropertyDescriptor(String canonicalName, String name, long tag) {#PidTagPropertyDescriptor-java.lang.String-java.lang.String-long-}
```
public PidTagPropertyDescriptor(String canonicalName, String name, long tag)
```


Initializes a new instance of the [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canonicalName | java.lang.String | The canonical name of the property, such as  PidTagSubject . |
| name | java.lang.String | The alternate (MAPI) name of the property, such as  PR\_SUBJECT . |
| tag | long | The tag of the property: the ID in the high-order 16 bits and the data type in the low-order 16 bits. |

### equals(PropertyDescriptor other) {#equals-com.aspose.email.PropertyDescriptor-}
```
public boolean equals(PropertyDescriptor other)
```


Determines whether the specified descriptor describes the same property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor to compare with. |

**Returns:**
boolean -  true  if  other  describes the same property; otherwise,  false .
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Determines whether the specified object is equal to this descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | java.lang.Object | The object to compare with. |

**Returns:**
boolean -  true  if  other  describes the same property; otherwise,  false .
### getCanonicalName() {#getCanonicalName--}
```
public final String getCanonicalName()
```


Gets the canonical name of the property, as in [MS-OXPROPS]. The prefix tells how the property is identified:  PidLid  by a numeric ID within a property set,  PidName  by a string name within a property set,  PidTag  by a fixed 16-bit ID.

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


Gets the data type of the property value.

**Returns:**
int
### getId() {#getId--}
```
public final int getId()
```


Gets the 16-bit ID of the property.

An ID is unique together with the data type, except for IDs from  0x6800  to  0x7BFF , whose meaning depends on the message class.

**Returns:**
int
### getInstance(MapiProperty property) {#getInstance-com.aspose.email.MapiProperty-}
```
public static PropertyDescriptor getInstance(MapiProperty property)
```


Gets the descriptor of a MAPI property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | The property. |

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor) - The descriptor of  property .
### getInstance(int id, int dataType) {#getInstance-int-int-}
```
public static PidTagPropertyDescriptor getInstance(int id, int dataType)
```


Gets the descriptor of a tagged property by its ID and data type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | The 16-bit ID of the property. |
| dataType | int | The data type of the property. |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) - The descriptor: the one from [KnownPropertyList](../../com.aspose.email/knownpropertylist) if the property is known; otherwise a new one.
### getInstance(String name, int dataType, UUID propertySet) {#getInstance-java.lang.String-int-java.util.UUID-}
```
public static PidNamePropertyDescriptor getInstance(String name, int dataType, UUID propertySet)
```


Gets the descriptor of a named property by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the property. |
| dataType | int | The data type of the property. |
| propertySet | java.util.UUID | The GUID of the property set. |

**Returns:**
[PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) - The descriptor: the one from [KnownPropertyList](../../com.aspose.email/knownpropertylist) if the property is known; otherwise a new one.
### getInstance(long tag) {#getInstance-long-}
```
public static PidTagPropertyDescriptor getInstance(long tag)
```


Gets the descriptor of a tagged property by its tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
[PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) - The descriptor: the one from [KnownPropertyList](../../com.aspose.email/knownpropertylist) if the property is known; otherwise a new one.
### getInstance(long lid, int dataType, UUID propertySet) {#getInstance-long-int-java.util.UUID-}
```
public static PidLidPropertyDescriptor getInstance(long lid, int dataType, UUID propertySet)
```


Gets the descriptor of a named property by its numeric ID (LID).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lid | long | The numeric ID of the property. |
| dataType | int | The data type of the property. |
| propertySet | java.util.UUID | The GUID of the property set. |

**Returns:**
[PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) - The descriptor: the one from [KnownPropertyList](../../com.aspose.email/knownpropertylist) if the property is known; otherwise a new one.
### getMultipleValuesDataType() {#getMultipleValuesDataType--}
```
public final boolean getMultipleValuesDataType()
```


Gets a value indicating whether the property is multi-valued.

**Returns:**
boolean
### getName() {#getName--}
```
public final String getName()
```


Gets the alternate name of the property, such as  PR\_SUBJECT , or the name of a named property.

**Returns:**
java.lang.String
### getTag() {#getTag--}
```
public final long getTag()
```


Gets the tag of the property: the ID in the high-order 16 bits and the data type in the low-order 16 bits.

**Returns:**
long
### getUse8BitStringAsUnicode() {#getUse8BitStringAsUnicode--}
```
public static boolean getUse8BitStringAsUnicode()
```


Gets a value indicating whether  String8  (ANSI) values are read as  String  (Unicode). The default is  true .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public int hashCode()
```


Returns the hash code of the descriptor.

**Returns:**
int - The hash code.
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
boolean -  true  if the specified PropertyDescriptor is equal to the another PropertyDescriptor; otherwise,  false .
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
boolean -  true  if the specified PropertyDescriptor is equal to the another PropertyDescriptor; otherwise,  false .
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
boolean -  true  if the specified PropertyDescriptor is not equal to the another PropertyDescriptor; otherwise,  false .
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
boolean -  true  if the specified PropertyDescriptor is not equal to the another PropertyDescriptor; otherwise,  false .
### parse(String data) {#parse-java.lang.String-}
```
public static PropertyDescriptor parse(String data)
```


Creates a descriptor from its string form, as returned by  toString() , for example  Tag:'PidTagSubject':0x37:String .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| data | java.lang.String | The string form of the descriptor. |

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor) - The descriptor: the one from [KnownPropertyList](../../com.aspose.email/knownpropertylist) if the property is known.
### setUse8BitStringAsUnicode(boolean value) {#setUse8BitStringAsUnicode-boolean-}
```
public static void setUse8BitStringAsUnicode(boolean value)
```


Sets a value indicating whether  String8  (ANSI) values are read as  String  (Unicode). The default is  true .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string that describes the property, in the form that [PropertyDescriptor.parse(String)](../../com.aspose.email/propertydescriptor\#parse-String-) accepts.

**Returns:**
java.lang.String - The description of the property.
### to_PidTagPropertyDescriptor(long tag) {#to-PidTagPropertyDescriptor-long-}
```
public static PidTagPropertyDescriptor to_PidTagPropertyDescriptor(long tag)
```


Converts tag value to tagged property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | tag value of a tag property. |

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

