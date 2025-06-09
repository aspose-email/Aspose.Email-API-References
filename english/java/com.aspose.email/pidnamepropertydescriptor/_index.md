---
title: PidNamePropertyDescriptor
second_title: Aspose.Email for Java API Reference
description: Class contains property description information.
type: docs
weight: 593
url: /java/com.aspose.email/pidnamepropertydescriptor/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.PropertyDescriptor](../../com.aspose.email/propertydescriptor)
```
public class PidNamePropertyDescriptor extends PropertyDescriptor
```

Class contains property description information.
## Constructors

| Constructor | Description |
| --- | --- |
| [PidNamePropertyDescriptor(String name, int type, UUID propertySet)](#PidNamePropertyDescriptor-java.lang.String-int-java.util.UUID-) | Initializes a new instance of the [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) class Properties identified by a string name along with a property set. |
| [PidNamePropertyDescriptor(String canonicalName, String name, int type, UUID propertySet)](#PidNamePropertyDescriptor-java.lang.String-java.lang.String-int-java.util.UUID-) | Initializes a new instance of the [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) class Properties identified by a string name along with a property set. |
## Methods

| Method | Description |
| --- | --- |
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | Indicates whether the current object is equal to another object of the same type. |
| [equals(Object other)](#equals-java.lang.Object-) | Determines whether the specified System.Object is equal to the current System.Object. |
| [getCanonicalName()](#getCanonicalName--) | The name used to refer to the property in the documentation. |
| [getClass()](#getClass--) |  |
| [getDataType()](#getDataType--) | The property value type, as described in [MS-OXCDATA], that specifies the type of values allowed for the property. |
| [getInstance(MapiProperty property)](#getInstance-com.aspose.email.MapiProperty-) | Retrieves [PropertyDescriptor](../../com.aspose.email/propertydescriptor) object from MAPI property |
| [getInstance(int id, int dataType)](#getInstance-int-int-) | Retrieves [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object |
| [getInstance(String name, int dataType, UUID propertySet)](#getInstance-java.lang.String-int-java.util.UUID-) | Retrieves [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) object |
| [getInstance(long tag)](#getInstance-long-) | Retrieves [PidTagPropertyDescriptor](../../com.aspose.email/pidtagpropertydescriptor) object |
| [getInstance(long lid, int dataType, UUID propertySet)](#getInstance-long-int-java.util.UUID-) | Retrieves [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) object |
| [getMultipleValuesDataType()](#getMultipleValuesDataType--) | Indicates if data type contains of multiple values |
| [getName()](#getName--) | Gets string that, identifies a property. |
| [getPropertySet()](#getPropertySet--) | A GUID that identifies a group of properties with a similar purpose. |
| [getUse8BitStringAsUnicode()](#getUse8BitStringAsUnicode--) | Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String |
| [hashCode()](#hashCode--) | Serves as a hash function for a type. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(PidNamePropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PidNamePropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [op_Equality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [op_Inequality(PidNamePropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PidNamePropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [op_Inequality(PropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [parse(String data)](#parse-java.lang.String-) | Initializes a new instance of the [PropertyDescriptor](../../com.aspose.email/propertydescriptor) class |
| [setUse8BitStringAsUnicode(boolean value)](#setUse8BitStringAsUnicode-boolean-) | Specifies if PropertyDataType.String8 has to be interpreted as PropertyDataType.String |
| [toString()](#toString--) | Returns a string that represents the property description. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PidNamePropertyDescriptor(String name, int type, UUID propertySet) {#PidNamePropertyDescriptor-java.lang.String-int-java.util.UUID-}
```
public PidNamePropertyDescriptor(String name, int type, UUID propertySet)
```


Initializes a new instance of the [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) class Properties identified by a string name along with a property set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | A string that, along with the property set, identifies a named property. |
| type | int | Specifies the type of values allowed for the property. |
| propertySet | java.util.UUID | A GUID that identifies a group of properties with a similar purpose. |

### PidNamePropertyDescriptor(String canonicalName, String name, int type, UUID propertySet) {#PidNamePropertyDescriptor-java.lang.String-java.lang.String-int-java.util.UUID-}
```
public PidNamePropertyDescriptor(String canonicalName, String name, int type, UUID propertySet)
```


Initializes a new instance of the [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) class Properties identified by a string name along with a property set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canonicalName | java.lang.String | The name used to refer to the property in the documentation. |
| name | java.lang.String | A string that, along with the property set, identifies a named property. |
| type | int | Specifies the type of values allowed for the property. |
| propertySet | java.util.UUID | A GUID that identifies a group of properties with a similar purpose. |

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
### getPropertySet() {#getPropertySet--}
```
public final UUID getPropertySet()
```


A GUID that identifies a group of properties with a similar purpose.

**Returns:**
java.util.UUID
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




### op_Equality(PidNamePropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Equality-com.aspose.email.PidNamePropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Equality(PidNamePropertyDescriptor pd1, PropertyDescriptor pd2)
```


Determines whether the specified objects are equal to each another.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd1 | [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) | The object to compare with another object. |
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
### op_Inequality(PidNamePropertyDescriptor pd1, PropertyDescriptor pd2) {#op-Inequality-com.aspose.email.PidNamePropertyDescriptor-com.aspose.email.PropertyDescriptor-}
```
public static boolean op_Inequality(PidNamePropertyDescriptor pd1, PropertyDescriptor pd2)
```


Determines whether the specified objects are not equal to each another.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd1 | [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) | The object to compare with another object. |
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

