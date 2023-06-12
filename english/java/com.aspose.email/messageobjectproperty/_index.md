---
title: MessageObjectProperty
second_title: Aspose.Email for Java API Reference
description: Represents a property on a .
type: docs
weight: 504
url: /java/com.aspose.email/messageobjectproperty/
---

**Inheritance:**
java.lang.Object
```
public final class MessageObjectProperty
```

Represents a property on a [MessageObject](../../com.aspose.email/messageobject).
## Constructors

| Constructor | Description |
| --- | --- |
| [MessageObjectProperty(long propertyTag, int flags, Object value)](#MessageObjectProperty-long-int-java.lang.Object-) | Initializes a new instance of the [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) class. |
| [MessageObjectProperty(int id, int type, int flags, Object value)](#MessageObjectProperty-int-int-int-java.lang.Object-) | Initializes a new instance of the [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAtomic()](#getAtomic--) | Gets a value indicating whether this [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) is atomic. |
| [getClass()](#getClass--) |  |
| [getFlags()](#getFlags--) | Gets the flags set on a property. |
| [getGuid()](#getGuid--) | Gets or sets the GUID for the named property. |
| [getId()](#getId--) | Gets the id of the property. |
| [getName()](#getName--) | Gets or sets the name of the property if it's named. |
| [getNameId()](#getNameId--) | Gets or sets the name id of the property if it's named. |
| [getNamed()](#getNamed--) | Gets a value indicating whether this [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) is a named property. |
| [getPropertyKind()](#getPropertyKind--) | Gets or sets the kind of the property if it's named. |
| [getPropertyTag()](#getPropertyTag--) | Gets the property tag, a combined value which contains  Id (\#getId.getId) and  PropertyType (\#getPropertyType.getPropertyType) |
| [getPropertyType()](#getPropertyType--) | Gets the type of the property. |
| [getValue()](#getValue--) | Gets or sets the value of the property. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(UUID value)](#setGuid-java.util.UUID-) | Gets or sets the GUID for the named property. |
| [setName(String value)](#setName-java.lang.String-) | Gets or sets the name of the property if it's named. |
| [setNameId(long value)](#setNameId-long-) | Gets or sets the name id of the property if it's named. |
| [setPropertyKind(int value)](#setPropertyKind-int-) | Gets or sets the kind of the property if it's named. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Gets or sets the value of the property. |
| [toDateTime()](#toDateTime--) | Converts the value of the property to DateTime. |
| [toGuid()](#toGuid--) | Converts the value of the property to  Guid (\#getGuid.getGuid/\#setGuid(Guid).setGuid(Guid)). |
| [toInt()](#toInt--) | Converts the value of the property to integer. |
| [toList()](#toList--) | Converts the value of the property to a list of values. |
| [toString()](#toString--) |  |
| [toStringRepresentation()](#toStringRepresentation--) | Converts the value of the property to string. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MessageObjectProperty(long propertyTag, int flags, Object value) {#MessageObjectProperty-long-int-java.lang.Object-}
```
public MessageObjectProperty(long propertyTag, int flags, Object value)
```


Initializes a new instance of the [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | long | The property tag. |
| flags | int | The flags to be set on. |
| value | java.lang.Object | The value of the property. |

### MessageObjectProperty(int id, int type, int flags, Object value) {#MessageObjectProperty-int-int-int-java.lang.Object-}
```
public MessageObjectProperty(int id, int type, int flags, Object value)
```


Initializes a new instance of the [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | int | The id. |
| type | int | The type of the property. |
| flags | int | The flags to be set on. |
| value | java.lang.Object | The value of the property. |

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
### getAtomic() {#getAtomic--}
```
public final boolean getAtomic()
```


Gets a value indicating whether this [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) is atomic.

Value:  true  if atomic; otherwise,  false .

**Returns:**
boolean
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getFlags() {#getFlags--}
```
public final int getFlags()
```


Gets the flags set on a property.

Value: The flags.

**Returns:**
int
### getGuid() {#getGuid--}
```
public final UUID getGuid()
```


Gets or sets the GUID for the named property.

Value: The GUID.

**Returns:**
java.util.UUID
### getId() {#getId--}
```
public final int getId()
```


Gets the id of the property.

Value: The id if the property.

**Returns:**
int
### getName() {#getName--}
```
public final String getName()
```


Gets or sets the name of the property if it's named.

Value: The name.

**Returns:**
java.lang.String
### getNameId() {#getNameId--}
```
public final long getNameId()
```


Gets or sets the name id of the property if it's named.

Value: The name id.

**Returns:**
long
### getNamed() {#getNamed--}
```
public final boolean getNamed()
```


Gets a value indicating whether this [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) is a named property.

Value:  true  if named; otherwise,  false .

--------------------

A named property is determined by its ID, the range for such ids is [0x8000,0xfffe].

**Returns:**
boolean
### getPropertyKind() {#getPropertyKind--}
```
public final int getPropertyKind()
```


Gets or sets the kind of the property if it's named.

Value: The kind of the property.

**Returns:**
int
### getPropertyTag() {#getPropertyTag--}
```
public final long getPropertyTag()
```


Gets the property tag, a combined value which contains  Id (\#getId.getId) and  PropertyType (\#getPropertyType.getPropertyType)

Value: The property tag.

**Returns:**
long
### getPropertyType() {#getPropertyType--}
```
public final int getPropertyType()
```


Gets the type of the property.

Value: The type of the property.

**Returns:**
int
### getValue() {#getValue--}
```
public final Object getValue()
```


Gets or sets the value of the property.

**Returns:**
java.lang.Object
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




### setGuid(UUID value) {#setGuid-java.util.UUID-}
```
public final void setGuid(UUID value)
```


Gets or sets the GUID for the named property.

Value: The GUID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID |  |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Gets or sets the name of the property if it's named.

Value: The name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameId(long value) {#setNameId-long-}
```
public final void setNameId(long value)
```


Gets or sets the name id of the property if it's named.

Value: The name id.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### setPropertyKind(int value) {#setPropertyKind-int-}
```
public final void setPropertyKind(int value)
```


Gets or sets the kind of the property if it's named.

Value: The kind of the property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Gets or sets the value of the property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### toDateTime() {#toDateTime--}
```
public final Date toDateTime()
```


Converts the value of the property to DateTime.

**Returns:**
java.util.Date - DateTime value, if type can't be converted to DateTime returns java.util.Date\#MinValue.MinValue.

--------------------

This method doesn't provide automatic conversion of the data types, e.g. if  MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) property is of type default value will be returned.
### toGuid() {#toGuid--}
```
public final UUID toGuid()
```


Converts the value of the property to  Guid (\#getGuid.getGuid/\#setGuid(Guid).setGuid(Guid)).

**Returns:**
java.util.UUID - Guid object, if type can't be converted to Guid returns empty GUID.

--------------------

This method doesn't provide automatic conversion of the data types, e.g. if  MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) property is of type default value will be returned.
### toInt() {#toInt--}
```
public final int toInt()
```


Converts the value of the property to integer.

**Returns:**
int - Integer value, if type can't be converted to integer returns 0.
### toList() {#toList--}
```
public System.Collections.IList toList()
```


Converts the value of the property to a list of values.

**Returns:**
com.aspose.ms.System.Collections.IList - IList implementation, if type can't be converted to IList returns empty list implementation.

--------------------

This method doesn't provide automatic conversion of the data types, e.g. if  MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) property is of type default value will be returned.
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### toStringRepresentation() {#toStringRepresentation--}
```
public final String toStringRepresentation()
```


Converts the value of the property to string.

**Returns:**
java.lang.String - String value, if type can't be converted to string returns empty string.

--------------------

This method doesn't provide automatic conversion of the data types, e.g. if  MessageObjectProperty.Value (\#getValue.getValue/\#setValue(Object).setValue(Object)) property is of type default value will be returned.
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

