---
title: MessageObjectProperty
second_title: Aspose.Email for Java API Reference
description: Represents a property on a .
type: docs
weight: 529
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
| [getGuid()](#getGuid--) | Gets the GUID for the named property. |
| [getId()](#getId--) | Gets the id of the property. |
| [getName()](#getName--) | Gets the name of the property if it's named. |
| [getNameId()](#getNameId--) | Gets the name id of the property if it's named. |
| [getNamed()](#getNamed--) | Gets a value indicating whether this [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) is a named property. |
| [getPropertyKind()](#getPropertyKind--) | Gets the kind of the property if it's named. |
| [getPropertyTag()](#getPropertyTag--) | Gets the property tag, a combined value which contains \#getId().getId() and \#getPropertyType().getPropertyType() |
| [getPropertyType()](#getPropertyType--) | Gets the type of the property. |
| [getValue()](#getValue--) | Gets the value of the property. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setGuid(UUID value)](#setGuid-java.util.UUID-) | Sets the GUID for the named property. |
| [setName(String value)](#setName-java.lang.String-) | Sets the name of the property if it's named. |
| [setNameId(long value)](#setNameId-long-) | Sets the name id of the property if it's named. |
| [setPropertyKind(int value)](#setPropertyKind-int-) | Sets the kind of the property if it's named. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Sets the value of the property. |
| [toDateTime()](#toDateTime--) | Converts the value of the property to DateTime. |
| [toGuid()](#toGuid--) | Converts the value of the property to  java.util.UUID . |
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

**Returns:**
boolean -  true  if atomic; otherwise,  false .
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

**Returns:**
int - The flags.
### getGuid() {#getGuid--}
```
public final UUID getGuid()
```


Gets the GUID for the named property.

**Returns:**
java.util.UUID - The GUID.
### getId() {#getId--}
```
public final int getId()
```


Gets the id of the property.

**Returns:**
int - The id if the property.
### getName() {#getName--}
```
public final String getName()
```


Gets the name of the property if it's named.

**Returns:**
java.lang.String - The name.
### getNameId() {#getNameId--}
```
public final long getNameId()
```


Gets the name id of the property if it's named.

**Returns:**
long - The name id.
### getNamed() {#getNamed--}
```
public final boolean getNamed()
```


Gets a value indicating whether this [MessageObjectProperty](../../com.aspose.email/messageobjectproperty) is a named property.

A named property is determined by its ID, the range for such ids is [0x8000,0xfffe].

**Returns:**
boolean -  true  if named; otherwise,  false .
### getPropertyKind() {#getPropertyKind--}
```
public final int getPropertyKind()
```


Gets the kind of the property if it's named.

**Returns:**
int - The kind of the property.
### getPropertyTag() {#getPropertyTag--}
```
public final long getPropertyTag()
```


Gets the property tag, a combined value which contains \#getId().getId() and \#getPropertyType().getPropertyType()

**Returns:**
long - The property tag.
### getPropertyType() {#getPropertyType--}
```
public final int getPropertyType()
```


Gets the type of the property.

**Returns:**
int - The type of the property.
### getValue() {#getValue--}
```
public final Object getValue()
```


Gets the value of the property.

**Returns:**
java.lang.Object - The value.
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


Sets the GUID for the named property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.UUID | The GUID. |

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


Sets the name of the property if it's named.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name. |

### setNameId(long value) {#setNameId-long-}
```
public final void setNameId(long value)
```


Sets the name id of the property if it's named.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long | The name id. |

### setPropertyKind(int value) {#setPropertyKind-int-}
```
public final void setPropertyKind(int value)
```


Sets the kind of the property if it's named.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The kind of the property. |

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Sets the value of the property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value. |

### toDateTime() {#toDateTime--}
```
public final Date toDateTime()
```


Converts the value of the property to DateTime.

This method doesn't provide automatic conversion of the data types, e.g. if \#getValue().getValue() property is of type default value will be returned.

**Returns:**
java.util.Date - DateTime value, if type can't be converted to DateTime returns  DateTime.MinValue .
### toGuid() {#toGuid--}
```
public final UUID toGuid()
```


Converts the value of the property to  java.util.UUID .

This method doesn't provide automatic conversion of the data types, e.g. if \#getValue().getValue() property is of type default value will be returned.

**Returns:**
java.util.UUID -  UUID  object, if type can't be converted to  UUID  returns empty GUID.
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

This method doesn't provide automatic conversion of the data types, e.g. if \#getValue().getValue() property is of type default value will be returned.

**Returns:**
com.aspose.ms.System.Collections.IList - IList implementation, if type can't be converted to IList returns empty list implementation.
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

This method doesn't provide automatic conversion of the data types, e.g. if \#getValue().getValue() property is of type default value will be returned.

**Returns:**
java.lang.String - String value, if type can't be converted to string returns empty string.
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

