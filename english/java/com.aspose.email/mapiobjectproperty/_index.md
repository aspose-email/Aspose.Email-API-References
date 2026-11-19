---
title: MapiObjectProperty
second_title: Aspose.Email for Java API Reference
description: An object embedded in an attachment such as an attached Outlook message or an OLE document.
type: docs
weight: 478
url: /java/com.aspose.email/mapiobjectproperty/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiProperty](../../com.aspose.email/mapiproperty)
```
public class MapiObjectProperty extends MapiProperty
```

An object embedded in an attachment, such as an attached Outlook message or an OLE document.

Returned by [MapiAttachment.getObjectData()](../../com.aspose.email/mapiattachment\#getObjectData--). For an attached message \#isOutlookMessage().isOutlookMessage() is  true  and \#toMapiMessage().toMapiMessage() returns it.
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
| [getDocumentName()](#getDocumentName--) | Gets the name of the embedded document. |
| [getDouble()](#getDouble--) | Gets the value as a 64-bit floating-point number. |
| [getFloat()](#getFloat--) | Gets the value as a 32-bit floating-point number. |
| [getFloatingDate()](#getFloatingDate--) | Gets the value of a floating date (PT\_APPTIME) property: a number of days since December 30, 1899. |
| [getGuidValue()](#getGuidValue--) | Gets the value as a GUID. |
| [getIdentifier()](#getIdentifier--) | Gets the property ID: the high-order 16 bits of \#getTag().getTag(). |
| [getInt32()](#getInt32--) | Gets the value as a 32-bit integer. |
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
| [getOleDocumentFormat()](#getOleDocumentFormat--) | Gets the format of the embedded OLE document, such as a Word document or an Excel worksheet. |
| [getProperties()](#getProperties--) | Gets the MAPI properties of the embedded object. |
| [getPropertyTagName()](#getPropertyTagName--) | Gets the name of the tag of the property, such as  PR\_SUBJECT , if it is known. |
| [getShort()](#getShort--) | Gets the value as a 16-bit integer. |
| [getString()](#getString--) | Gets the value as a string. |
| [getString(int codepage)](#getString-int-) | Gets the value as a string, decoding an ANSI string with the specified code page. |
| [getTag()](#getTag--) | Gets the tag of the property: the property ID in the high-order 16 bits and the data type in the low-order 16 bits. |
| [getValue()](#getValue--) | Gets the value as an object of the .NET type that matches the data type. |
| [hashCode()](#hashCode--) |  |
| [isNamed()](#isNamed--) | Gets a value indicating whether the property is a named property. |
| [isOutlookMessage()](#isOutlookMessage--) | Gets a value indicating whether the object is an Outlook message. |
| [isSigned()](#isSigned--) | Gets a value indicating whether the value is a signed number. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setSigned(boolean value)](#setSigned-boolean-) | Sets a value indicating whether the value is a signed number. |
| [toMapiMessage()](#toMapiMessage--) | Gets the embedded Outlook message. |
| [toString()](#toString--) | Returns a string that represents the property. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getDocumentName() {#getDocumentName--}
```
public final String getDocumentName()
```


Gets the name of the embedded document.

**Returns:**
java.lang.String
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
### getOleDocumentFormat() {#getOleDocumentFormat--}
```
public final OleDocumentFormat getOleDocumentFormat()
```


Gets the format of the embedded OLE document, such as a Word document or an Excel worksheet.

**Returns:**
[OleDocumentFormat](../../com.aspose.email/oledocumentformat)
### getProperties() {#getProperties--}
```
public final MapiPropertyCollection getProperties()
```


Gets the MAPI properties of the embedded object.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
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
### isOutlookMessage() {#isOutlookMessage--}
```
public final boolean isOutlookMessage()
```


Gets a value indicating whether the object is an Outlook message.

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

### toMapiMessage() {#toMapiMessage--}
```
public final MapiMessage toMapiMessage()
```


Gets the embedded Outlook message.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The embedded message.
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

