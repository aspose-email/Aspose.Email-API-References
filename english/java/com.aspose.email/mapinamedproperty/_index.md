---
title: MapiNamedProperty
second_title: Aspose.Email for Java API Reference
description: A named property a MAPI property identified by a property set GUID and a name or numeric ID rather than by a fixed tag.
type: docs
weight: 475
url: /java/com.aspose.email/mapinamedproperty/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiProperty](../../com.aspose.email/mapiproperty)
```
public final class MapiNamedProperty extends MapiProperty
```

A named property: a MAPI property identified by a property set GUID and a name or numeric ID rather than by a fixed tag.

Inside a message a named property is stored under a tag that the message assigns. Read the identity of the property with \#getGuid().getGuid(), \#getKind().getKind() and \#getNameId().getNameId().
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiNamedProperty()](#MapiNamedProperty--) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class. |
| [MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue)](#MapiNamedProperty-long-java.lang.String-java.util.UUID-byte---) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class for a property identified by a string name. |
| [MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue)](#MapiNamedProperty-long-long-java.util.UUID-byte---) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class for a property identified by a numeric ID. |
| [MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data)](#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class from a descriptor of a property with a numeric ID. |
| [MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data)](#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidNamePropertyDescriptor-java.lang.Object-) | Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class from a descriptor of a property with a string name. |
## Methods

| Method | Description |
| --- | --- |
| [createMapiPropertyFromBytes(long tag, byte[] data)](#createMapiPropertyFromBytes-long-byte---) | Creates a property with a binary value. |
| [createMapiPropertyFromDateTime(long tag, Date data)](#createMapiPropertyFromDateTime-long-java.util.Date-) | Creates a property with a date and time value. |
| [createMapiPropertyFromLong(long tag, long data)](#createMapiPropertyFromLong-long-long-) | Creates a property with an integer value. |
| [createMapiPropertyFromLong(long tag, long data, long delimiter)](#createMapiPropertyFromLong-long-long-long-) | Creates a property with an integer value and a signed flag. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBoolean()](#getBoolean--) | Gets the value as a Boolean. |
| [getClass()](#getClass--) |  |
| [getCurrency()](#getCurrency--) | Gets the value of a currency property. |
| [getData()](#getData--) | Gets the value of the property as bytes. |
| [getDataType()](#getDataType--) | Gets the data type of the property: the low-order 16 bits of \#getTag().getTag(). |
| [getDateTime()](#getDateTime--) | Gets the value of a date and time (PT\_SYSTIME) property. |
| [getDescriptor()](#getDescriptor--) | Gets the descriptor of the property. |
| [getDouble()](#getDouble--) | Gets the value as a 64-bit floating-point number. |
| [getFloat()](#getFloat--) | Gets the value as a 32-bit floating-point number. |
| [getFloatingDate()](#getFloatingDate--) | Gets the value of a floating date (PT\_APPTIME) property: a number of days since December 30, 1899. |
| [getGuid()](#getGuid--) | Gets the GUID of the property set the property belongs to. |
| [getGuidValue()](#getGuidValue--) | Gets the value as a GUID. |
| [getIdentifier()](#getIdentifier--) | Gets the property ID: the high-order 16 bits of \#getTag().getTag(). |
| [getInt32()](#getInt32--) | Gets the value as a 32-bit integer. |
| [getKind()](#getKind--) | Gets how the property is identified within its property set: 0 by a numeric ID, 1 by a string name. |
| [getLong()](#getLong--) | Gets the value as a 64-bit integer. |
| [getMVEntries()](#getMVEntries--) | Gets the values of a multi-valued property. |
| [getMultipleBinary()](#getMultipleBinary--) | Gets the multyple binary data. |
| [getMultipleBoolean()](#getMultipleBoolean--) | Gets the multyple bool values. |
| [getMultipleCurrency()](#getMultipleCurrency--) | Gets the multyple decimal values. |
| [getMultipleFloating32()](#getMultipleFloating32--) | Gets the multyple float values. |
| [getMultipleFloating64()](#getMultipleFloating64--) | Gets the multyple double values. |
| [getMultipleFloatingTime()](#getMultipleFloatingTime--) | Gets the multyple DateTime values. |
| [getMultipleGuid()](#getMultipleGuid--) | Gets the multyple Guid values. |
| [getMultipleInteger16()](#getMultipleInteger16--) | Gets the multyple Int16 values. |
| [getMultipleInteger32()](#getMultipleInteger32--) | Gets the multyple Int32 values. |
| [getMultipleInteger64()](#getMultipleInteger64--) | Gets the multyple Int64 values. |
| [getMultipleString()](#getMultipleString--) | Gets the multyple strings data. |
| [getMultipleTime()](#getMultipleTime--) | Gets the multyple DateTime values. |
| [getName()](#getName--) | Gets the name of the property. |
| [getNameId()](#getNameId--) | Gets the name of the property, or its numeric ID in hexadecimal when \#getKind().getKind() is 0. |
| [getOom()](#getOom--) | Gets the name of the property in the Outlook Object Model, if it has one; otherwise an empty string. |
| [getPropertyTagName()](#getPropertyTagName--) | Gets the name of the tag of the property, such as  PR\_SUBJECT , if it is known. |
| [getShort()](#getShort--) | Gets the value as a 16-bit integer. |
| [getString()](#getString--) | Gets the value as a string. |
| [getString(int codepage)](#getString-int-) | Gets the value as a string, decoding an ANSI string with the specified code page. |
| [getTag()](#getTag--) | Gets the tag of the property: the property ID in the high-order 16 bits and the data type in the low-order 16 bits. |
| [getValue()](#getValue--) | Gets the value as an object of the .NET type that matches the data type. |
| [hashCode()](#hashCode--) |  |
| [isNamed()](#isNamed--) | Gets a value indicating whether the property is a named property. |
| [isSigned()](#isSigned--) | Gets a value indicating whether the value is a signed number. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setSigned(boolean value)](#setSigned-boolean-) | Sets a value indicating whether the value is a signed number. |
| [toString()](#toString--) | Returns a string that represents the property. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiNamedProperty() {#MapiNamedProperty--}
```
public MapiNamedProperty()
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class.

### MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue) {#MapiNamedProperty-long-java.lang.String-java.util.UUID-byte---}
```
public MapiNamedProperty(long propertyTag, String nameIdentifier, UUID propertyGuid, byte[] propertyValue)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class for a property identified by a string name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | long | The tag the property is stored under: the property ID in the high-order 16 bits and the data type in the low-order 16 bits. |
| nameIdentifier | java.lang.String | The name of the property. |
| propertyGuid | java.util.UUID | The GUID of the property set. |
| propertyValue | byte[] | The value, as bytes. |

### MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue) {#MapiNamedProperty-long-long-java.util.UUID-byte---}
```
public MapiNamedProperty(long propertyTag, long nameIdentifier, UUID propertyGuid, byte[] propertyValue)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class for a property identified by a numeric ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyTag | long | The tag the property is stored under: the property ID in the high-order 16 bits and the data type in the low-order 16 bits. |
| nameIdentifier | long | The numeric ID (LID) of the property. |
| propertyGuid | java.util.UUID | The GUID of the property set. |
| propertyValue | byte[] | The value, as bytes. |

### MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data) {#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidLidPropertyDescriptor-java.lang.Object-}
```
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidLidPropertyDescriptor pd, Object data)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class from a descriptor of a property with a numeric ID.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagProvider | [INamedPropertyTagProvider](../../com.aspose.email/inamedpropertytagprovider) | The property collection that assigns the tag, such as the properties of the message. |
| pd | [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) | The descriptor of the property. |
| data | java.lang.Object | The value. |

### MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data) {#MapiNamedProperty-com.aspose.email.INamedPropertyTagProvider-com.aspose.email.PidNamePropertyDescriptor-java.lang.Object-}
```
public MapiNamedProperty(INamedPropertyTagProvider tagProvider, PidNamePropertyDescriptor pd, Object data)
```


Initializes a new instance of the [MapiNamedProperty](../../com.aspose.email/mapinamedproperty) class from a descriptor of a property with a string name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tagProvider | [INamedPropertyTagProvider](../../com.aspose.email/inamedpropertytagprovider) | The property collection that assigns the tag, such as the properties of the message. |
| pd | [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) | The descriptor of the property. |
| data | java.lang.Object | The value. |

### createMapiPropertyFromBytes(long tag, byte[] data) {#createMapiPropertyFromBytes-long-byte---}
```
public static MapiProperty createMapiPropertyFromBytes(long tag, byte[] data)
```


Creates a property with a binary value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| data | byte[] | The value. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The new property.
### createMapiPropertyFromDateTime(long tag, Date data) {#createMapiPropertyFromDateTime-long-java.util.Date-}
```
public static MapiProperty createMapiPropertyFromDateTime(long tag, Date data)
```


Creates a property with a date and time value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| data | java.util.Date | The value. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The new property.
### createMapiPropertyFromLong(long tag, long data) {#createMapiPropertyFromLong-long-long-}
```
public static MapiProperty createMapiPropertyFromLong(long tag, long data)
```


Creates a property with an integer value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| data | long | The value. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The new property.
### createMapiPropertyFromLong(long tag, long data, long delimiter) {#createMapiPropertyFromLong-long-long-long-}
```
public static MapiProperty createMapiPropertyFromLong(long tag, long data, long delimiter)
```


Creates a property with an integer value and a signed flag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| data | long | The value. |
| delimiter | long | The signed flag of the property. |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The new property.
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
### getBoolean() {#getBoolean--}
```
public boolean getBoolean()
```


Gets the value as a Boolean.

**Returns:**
boolean - The value.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrency() {#getCurrency--}
```
public BigDecimal getCurrency()
```


Gets the value of a currency property.

**Returns:**
java.math.BigDecimal - The value as a decimal number with four decimal places.
### getData() {#getData--}
```
public byte[] getData()
```


Gets the value of the property as bytes.

**Returns:**
byte[]
### getDataType() {#getDataType--}
```
public int getDataType()
```


Gets the data type of the property: the low-order 16 bits of \#getTag().getTag().

**Returns:**
int
### getDateTime() {#getDateTime--}
```
public Date getDateTime()
```


Gets the value of a date and time (PT\_SYSTIME) property.

**Returns:**
java.util.Date - The value.
### getDescriptor() {#getDescriptor--}
```
public final PropertyDescriptor getDescriptor()
```


Gets the descriptor of the property.

**Returns:**
[PropertyDescriptor](../../com.aspose.email/propertydescriptor)
### getDouble() {#getDouble--}
```
public double getDouble()
```


Gets the value as a 64-bit floating-point number.

**Returns:**
double - The value.
### getFloat() {#getFloat--}
```
public float getFloat()
```


Gets the value as a 32-bit floating-point number.

**Returns:**
float - The value.
### getFloatingDate() {#getFloatingDate--}
```
public Date getFloatingDate()
```


Gets the value of a floating date (PT\_APPTIME) property: a number of days since December 30, 1899.

**Returns:**
java.util.Date - The value as a date and time.
### getGuid() {#getGuid--}
```
public final UUID getGuid()
```


Gets the GUID of the property set the property belongs to.

**Returns:**
java.util.UUID
### getGuidValue() {#getGuidValue--}
```
public UUID getGuidValue()
```


Gets the value as a GUID.

**Returns:**
java.util.UUID - The value.
### getIdentifier() {#getIdentifier--}
```
public long getIdentifier()
```


Gets the property ID: the high-order 16 bits of \#getTag().getTag().

**Returns:**
long
### getInt32() {#getInt32--}
```
public int getInt32()
```


Gets the value as a 32-bit integer.

**Returns:**
int - The value.
### getKind() {#getKind--}
```
public final int getKind()
```


Gets how the property is identified within its property set: 0 by a numeric ID, 1 by a string name.

**Returns:**
int
### getLong() {#getLong--}
```
public long getLong()
```


Gets the value as a 64-bit integer.

**Returns:**
long - The value.
### getMVEntries() {#getMVEntries--}
```
public final System.Collections.IList getMVEntries()
```


Gets the values of a multi-valued property.

**Returns:**
com.aspose.ms.System.Collections.IList
### getMultipleBinary() {#getMultipleBinary--}
```
public final byte[][] getMultipleBinary()
```


Gets the multyple binary data.

**Returns:**
byte[][] - A multyple byte arrays.
### getMultipleBoolean() {#getMultipleBoolean--}
```
public final boolean[] getMultipleBoolean()
```


Gets the multyple bool values.

**Returns:**
boolean[] - A bool array.
### getMultipleCurrency() {#getMultipleCurrency--}
```
public final BigDecimal[] getMultipleCurrency()
```


Gets the multyple decimal values.

**Returns:**
java.math.BigDecimal[] - A decimal array.
### getMultipleFloating32() {#getMultipleFloating32--}
```
public final float[] getMultipleFloating32()
```


Gets the multyple float values.

**Returns:**
float[] - A float array.
### getMultipleFloating64() {#getMultipleFloating64--}
```
public final double[] getMultipleFloating64()
```


Gets the multyple double values.

**Returns:**
double[] - A double array.
### getMultipleFloatingTime() {#getMultipleFloatingTime--}
```
public final Date[] getMultipleFloatingTime()
```


Gets the multyple DateTime values.

**Returns:**
java.util.Date[] - A DateTime array.
### getMultipleGuid() {#getMultipleGuid--}
```
public final UUID[] getMultipleGuid()
```


Gets the multyple Guid values.

**Returns:**
java.util.UUID[] - A Guid array.
### getMultipleInteger16() {#getMultipleInteger16--}
```
public final short[] getMultipleInteger16()
```


Gets the multyple Int16 values.

**Returns:**
short[] - A Int16 array.
### getMultipleInteger32() {#getMultipleInteger32--}
```
public final int[] getMultipleInteger32()
```


Gets the multyple Int32 values.

**Returns:**
int[] - A Int32 array.
### getMultipleInteger64() {#getMultipleInteger64--}
```
public final long[] getMultipleInteger64()
```


Gets the multyple Int64 values.

**Returns:**
long[] - A Int64 array.
### getMultipleString() {#getMultipleString--}
```
public final String[] getMultipleString()
```


Gets the multyple strings data.

**Returns:**
java.lang.String[] - A string array.
### getMultipleTime() {#getMultipleTime--}
```
public final Date[] getMultipleTime()
```


Gets the multyple DateTime values.

**Returns:**
java.util.Date[] - A DateTime array.
### getName() {#getName--}
```
public String getName()
```


Gets the name of the property.

**Returns:**
java.lang.String
### getNameId() {#getNameId--}
```
public final String getNameId()
```


Gets the name of the property, or its numeric ID in hexadecimal when \#getKind().getKind() is 0.

**Returns:**
java.lang.String
### getOom() {#getOom--}
```
public final String getOom()
```


Gets the name of the property in the Outlook Object Model, if it has one; otherwise an empty string.

**Returns:**
java.lang.String
### getPropertyTagName() {#getPropertyTagName--}
```
public String getPropertyTagName()
```


Gets the name of the tag of the property, such as  PR\_SUBJECT , if it is known.

**Returns:**
java.lang.String
### getShort() {#getShort--}
```
public short getShort()
```


Gets the value as a 16-bit integer.

**Returns:**
short - The value.
### getString() {#getString--}
```
public String getString()
```


Gets the value as a string.

**Returns:**
java.lang.String - The value.
### getString(int codepage) {#getString-int-}
```
public String getString(int codepage)
```


Gets the value as a string, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
java.lang.String - The value.
### getTag() {#getTag--}
```
public long getTag()
```


Gets the tag of the property: the property ID in the high-order 16 bits and the data type in the low-order 16 bits.

**Returns:**
long
### getValue() {#getValue--}
```
public final Object getValue()
```


Gets the value as an object of the .NET type that matches the data type.

**Returns:**
java.lang.Object - The value.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isNamed() {#isNamed--}
```
public final boolean isNamed()
```


Gets a value indicating whether the property is a named property.

**Returns:**
boolean
### isSigned() {#isSigned--}
```
public boolean isSigned()
```


Gets a value indicating whether the value is a signed number.

**Returns:**
boolean
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setSigned(boolean value) {#setSigned-boolean-}
```
public void setSigned(boolean value)
```


Sets a value indicating whether the value is a signed number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the property.

**Returns:**
java.lang.String - A string that represents the property.
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

