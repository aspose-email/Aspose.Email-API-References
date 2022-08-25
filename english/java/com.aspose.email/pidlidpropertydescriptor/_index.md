---
title: PidLidPropertyDescriptor
second_title: Aspose.Email for Java API Reference
description:  Class contains property description information.
type: docs
weight: 559
url: /java/com.aspose.email/pidlidpropertydescriptor/
---
**Inheritance:**
java.lang.Object, [com.aspose.email.PropertyDescriptor](../../com.aspose.email/propertydescriptor)
```
public class PidLidPropertyDescriptor extends PropertyDescriptor
```

Class contains property description information.
## Constructors

| Constructor | Description |
| --- | --- |
| [PidLidPropertyDescriptor(long longId, int type, UUID propertySet)](#PidLidPropertyDescriptor-long-int-java.util.UUID-) | Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class Properties identified by an unsigned 32-bit quantity along with a property set. |
| [PidLidPropertyDescriptor(String canonicalName, long longId, int type, UUID propertySet)](#PidLidPropertyDescriptor-java.lang.String-long-int-java.util.UUID-) | Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class Properties identified by an unsigned 32-bit quantity along with a property set. |
| [PidLidPropertyDescriptor(String canonicalName, String name, long longId, int type, UUID propertySet)](#PidLidPropertyDescriptor-java.lang.String-java.lang.String-long-int-java.util.UUID-) | Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class Properties identified by an unsigned 32-bit quantity along with a property set. |
## Methods

| Method | Description |
| --- | --- |
| [getLongId()](#getLongId--) | Gets an unsigned 32-bit quantity that, along with the property set, identifies a named property. |
| [getPropertySet()](#getPropertySet--) | A GUID that identifies a group of properties with a similar purpose. |
| [op_Equality(PidLidPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Equality-com.aspose.email.PidLidPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are equal to each another. |
| [op_Inequality(PidLidPropertyDescriptor pd1, PropertyDescriptor pd2)](#op-Inequality-com.aspose.email.PidLidPropertyDescriptor-com.aspose.email.PropertyDescriptor-) | Determines whether the specified objects are not equal to each another. |
| [equals(Object other)](#equals-java.lang.Object-) | Determines whether the specified System.Object is equal to the current System.Object. |
| [equals(PropertyDescriptor other)](#equals-com.aspose.email.PropertyDescriptor-) | Indicates whether the current object is equal to another object of the same type. |
| [hashCode()](#hashCode--) | Serves as a hash function for a type. |
| [toString()](#toString--) | Returns a string that represents the property description. |
### PidLidPropertyDescriptor(long longId, int type, UUID propertySet) {#PidLidPropertyDescriptor-long-int-java.util.UUID-}
```
public PidLidPropertyDescriptor(long longId, int type, UUID propertySet)
```


Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class Properties identified by an unsigned 32-bit quantity along with a property set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| longId | long | long ID (LID): An unsigned 32-bit quantity that, in combination with a GUID, defines a named property. |
| type | int | Specifies the type of values allowed for the property. |
| propertySet | java.util.UUID | A GUID that identifies a group of properties with a similar purpose. |

### PidLidPropertyDescriptor(String canonicalName, long longId, int type, UUID propertySet) {#PidLidPropertyDescriptor-java.lang.String-long-int-java.util.UUID-}
```
public PidLidPropertyDescriptor(String canonicalName, long longId, int type, UUID propertySet)
```


Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class Properties identified by an unsigned 32-bit quantity along with a property set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canonicalName | java.lang.String | The name used to refer to the property in the documentation. |
| longId | long | long ID (LID): An unsigned 32-bit quantity that, in combination with a GUID, defines a named property. |
| type | int | Specifies the type of values allowed for the property. |
| propertySet | java.util.UUID | A GUID that identifies a group of properties with a similar purpose. |

### PidLidPropertyDescriptor(String canonicalName, String name, long longId, int type, UUID propertySet) {#PidLidPropertyDescriptor-java.lang.String-java.lang.String-long-int-java.util.UUID-}
```
public PidLidPropertyDescriptor(String canonicalName, String name, long longId, int type, UUID propertySet)
```


Initializes a new instance of the [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) class Properties identified by an unsigned 32-bit quantity along with a property set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| canonicalName | java.lang.String | The name used to refer to the property in the documentation. |
| name | java.lang.String | The MAPI name used to refer to the property in the documentation. |
| longId | long | long ID (LID): An unsigned 32-bit quantity that, in combination with a GUID, defines a named property. |
| type | int | Specifies the type of values allowed for the property. |
| propertySet | java.util.UUID | A GUID that identifies a group of properties with a similar purpose. |

### getLongId() {#getLongId--}
```
public final long getLongId()
```


Gets an unsigned 32-bit quantity that, along with the property set, identifies a named property.

**Returns:**
long
### getPropertySet() {#getPropertySet--}
```
public final UUID getPropertySet()
```


A GUID that identifies a group of properties with a similar purpose.

**Returns:**
java.util.UUID
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
boolean - true if the specified PropertyDescriptor is equal to the another PropertyDescriptor; otherwise, false.
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
