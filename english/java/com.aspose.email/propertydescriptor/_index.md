---
title: PropertyDescriptor
second_title: Aspose.Email for Java API Reference
description: The base class of property descriptors the identity and data type of a MAPI property.
type: docs
weight: 615
url: /java/com.aspose.email/propertydescriptor/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IEquatable
```
public abstract class PropertyDescriptor implements System.IEquatable<PropertyDescriptor>
```

The base class of property descriptors: the identity and data type of a MAPI property.

Use [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) for tagged properties, and [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) or [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) for named properties. Descriptors of the known properties are defined in [KnownPropertyList](../../com.aspose.email/knownpropertylist).
## Methods

| Method | Description |
| --- | --- |
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | Determines whether the specified descriptor describes the same property. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCanonicalName()](#getCanonicalName--) | Gets the canonical name of the property, as in [MS-OXPROPS]. |
| [getClass()](#getClass--) |  |
| [getDataType()](#getDataType--) | Gets the data type of the property value. |
| [getInstance(MapiProperty property)](#getInstance-com.aspose.email.MapiProperty-) | Gets the descriptor of a MAPI property. |
| [getInstance(int id, int dataType)](#getInstance-int-int-) | Gets the descriptor of a tagged property by its ID and data type. |
| [getInstance(String name, int dataType, UUID propertySet)](#getInstance-java.lang.String-int-java.util.UUID-) | Gets the descriptor of a named property by its name. |
| [getInstance(long tag)](#getInstance-long-) | Gets the descriptor of a tagged property by its tag. |
| [getInstance(long lid, int dataType, UUID propertySet)](#getInstance-long-int-java.util.UUID-) | Gets the descriptor of a named property by its numeric ID (LID). |
| [getMultipleValuesDataType()](#getMultipleValuesDataType--) | Gets a value indicating whether the property is multi-valued. |
| [getName()](#getName--) | Gets the alternate name of the property, such as  PR\_SUBJECT , or the name of a named property. |
| [getUse8BitStringAsUnicode()](#getUse8BitStringAsUnicode--) | Gets a value indicating whether  String8  (ANSI) values are read as  String  (Unicode). |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [parse(String data)](#parse-java.lang.String-) | Creates a descriptor from its string form, as returned by  toString() , for example  Tag:'PidTagSubject':0x37:String . |
| [setUse8BitStringAsUnicode(boolean value)](#setUse8BitStringAsUnicode-boolean-) | Sets a value indicating whether  String8  (ANSI) values are read as  String  (Unicode). |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### equals(PropertyDescriptor other) {#equals-com.aspose.email.PropertyDescriptor-}
```
public abstract boolean equals(PropertyDescriptor other)
```


Determines whether the specified descriptor describes the same property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| other | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor to compare with. |

**Returns:**
boolean -  true  if  other  describes the same property; otherwise,  false .
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
### getUse8BitStringAsUnicode() {#getUse8BitStringAsUnicode--}
```
public static boolean getUse8BitStringAsUnicode()
```


Gets a value indicating whether  String8  (ANSI) values are read as  String  (Unicode). The default is  true .

**Returns:**
boolean
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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




**Returns:**
java.lang.String
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

