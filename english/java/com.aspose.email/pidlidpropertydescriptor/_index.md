---
title: PidLidPropertyDescriptor
second_title: Aspose.Email for Java API Reference
description: Describes a named property identified by a numeric ID LID within a property set.
type: docs
weight: 596
url: /java/com.aspose.email/pidlidpropertydescriptor/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.PropertyDescriptor](../../com.aspose.email/propertydescriptor)
```
public class PidLidPropertyDescriptor extends PropertyDescriptor
```

Describes a named property identified by a numeric ID (LID) within a property set.

A named property has no fixed tag: it is identified by the GUID of its property set, such as  PSETID\_Appointment , and an ID within it. Pass the descriptor to [MapiPropertyContainer.setProperty(PropertyDescriptor, Object)](../../com.aspose.email/mapipropertycontainer\#setProperty-PropertyDescriptor--Object-) or [MapiPropertyContainer.getProperty(PropertyDescriptor)](../../com.aspose.email/mapipropertycontainer\#getProperty-PropertyDescriptor-) and the tag is resolved for you. For properties identified by a string name use [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor), for tagged properties [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor). Descriptors of the known properties are defined in [KnownPropertyList](../../com.aspose.email/knownpropertylist).
## Constructors

| Constructor | Description |
| --- | --- |
| [PidLidPropertyDescriptor(long longId, int type, UUID propertySet)](#PidLidPropertyDescriptor-long-int-java.util.UUID-) | Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class. |
| [PidLidPropertyDescriptor(String canonicalName, long longId, int type, UUID propertySet)](#PidLidPropertyDescriptor-java.lang.String-long-int-java.util.UUID-) | Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class. |
| [PidLidPropertyDescriptor(String canonicalName, String name, long longId, int type, UUID propertySet)](#PidLidPropertyDescriptor-java.lang.String-java.lang.String-long-int-java.util.UUID-) | Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | Determines whether the specified descriptor describes the same property. |
| [equals(Object other)](#equals-java.lang.Object-) | Determines whether the specified object is equal to this descriptor. |
| [getCanonicalName()](#getCanonicalName--) | Gets the canonical name of the property, as in [MS-OXPROPS]. |
| [getClass()](#getClass--) |  |
| [getDataType()](#getDataType--) | Gets the data type of the property value. |
| [getInstance(MapiProperty property)](#getInstance-com.aspose.email.MapiProperty-) | Gets the descriptor of a MAPI property. |
| [getInstance(int id, int dataType)](#getInstance-int-int-) | Gets the descriptor of a tagged property by its ID and data type. |
| [getInstance(String name, int dataType, UUID propertySet)](#getInstance-java.lang.String-int-java.util.UUID-) | Gets the descriptor of a named property by its name. |
| [getInstance(long tag)](#getInstance-long-) | Gets the descriptor of a tagged property by its tag. |
| [getInstance(long lid, int dataType, UUID propertySet)](#getInstance-long-int-java.util.UUID-) | Gets the descriptor of a named property by its numeric ID (LID). |
| [getLongId()](#getLongId--) | Gets the numeric ID (LID) of the property within its property set. |
| [getMultipleValuesDataType()](#getMultipleValuesDataType--) | Gets a value indicating whether the property is multi-valued. |
| [getName()](#getName--) | Gets the alternate name of the property, such as  PR\_SUBJECT , or the name of a named property. |
| [getPropertySet()](#getPropertySet--) | Gets the GUID of the property set the property belongs to. |
| [getUse8BitStringAsUnicode()](#getUse8BitStringAsUnicode--) | Gets a value indicating whether  String8  (ANSI) values are read as  String  (Unicode). |
| [hashCode()](#hashCode--) | Returns the hash code of the descriptor. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PidLidPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PidLidPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [op_Inequality(PidLidPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PidLidPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [parse(String data)](#parse-java.lang.String-) | Creates a descriptor from its string form, as returned by  toString() , for example  Tag:'PidTagSubject':0x37:String . |
| [setUse8BitStringAsUnicode(boolean value)](#setUse8BitStringAsUnicode-boolean-) | Sets a value indicating whether  String8  (ANSI) values are read as  String  (Unicode). |
| [toString()](#toString--) | Returns a string that describes the property, in the form that [PropertyDescriptor.parse(String)](../../com.aspose.email/propertydescriptor\#parse-String-) accepts. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PidLidPropertyDescriptor(long longId, int type, UUID propertySet) {#PidLidPropertyDescriptor-long-int-java.util.UUID-}
```
public PidLidPropertyDescriptor(long longId, int type, UUID propertySet)
```


Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| longId | long | The numeric ID (LID) of the property within its property set. |
| type | int | The data type of the property. |
| propertySet | java.util.UUID | The GUID of the property set, for example one from [KnownPropertySets](../../com.aspose.email/knownpropertysets). |

### PidLidPropertyDescriptor(String canonicalName, long longId, int type, UUID propertySet) {#PidLidPropertyDescriptor-java.lang.String-long-int-java.util.UUID-}
```
public PidLidPropertyDescriptor(String canonicalName, long longId, int type, UUID propertySet)
```


Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canonicalName | java.lang.String | The canonical name of the property, such as  PidLidLocation . |
| longId | long | The numeric ID (LID) of the property within its property set. |
| type | int | The data type of the property. |
| propertySet | java.util.UUID | The GUID of the property set, for example one from [KnownPropertySets](../../com.aspose.email/knownpropertysets). |

### PidLidPropertyDescriptor(String canonicalName, String name, long longId, int type, UUID propertySet) {#PidLidPropertyDescriptor-java.lang.String-java.lang.String-long-int-java.util.UUID-}
```
public PidLidPropertyDescriptor(String canonicalName, String name, long longId, int type, UUID propertySet)
```


Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canonicalName | java.lang.String | The canonical name of the property, such as  PidLidLocation . |
| name | java.lang.String | The alternate (MAPI) name of the property, such as  dispidLocation . |
| longId | long | The numeric ID (LID) of the property within its property set. |
| type | int | The data type of the property. |
| propertySet | java.util.UUID | The GUID of the property set, for example one from [KnownPropertySets](../../com.aspose.email/knownpropertysets). |

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
### getLongId() {#getLongId--}
```
public final long getLongId()
```


Gets the numeric ID (LID) of the property within its property set.

**Returns:**
long
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
### getPropertySet() {#getPropertySet--}
```
public final UUID getPropertySet()
```


Gets the GUID of the property set the property belongs to.

**Returns:**
java.util.UUID
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




### op_Equality(PidLidPropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Equality-com.aspose.email.PidLidPropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Equality(PidLidPropertyDescriptor pd1, PropertyDescriptor pd2)
```


Determines whether the specified objects are equal to each another.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd1 | [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) | The object to compare with another object. |
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
### op_Inequality(PidLidPropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Inequality-com.aspose.email.PidLidPropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Inequality(PidLidPropertyDescriptor pd1, PropertyDescriptor pd2)
```


Determines whether the specified objects are not equal to each another.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd1 | [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) | The object to compare with another object. |
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

