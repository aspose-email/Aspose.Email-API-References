---
title: MapiNamedPropertyMappingStorage
second_title: Aspose.Email for Java API Reference
description: The mapping between the named properties of a message and the tags they are stored under.
type: docs
weight: 476
url: /java/com.aspose.email/mapinamedpropertymappingstorage/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer)
```
public final class MapiNamedPropertyMappingStorage extends MapiPropertyContainer
```

The mapping between the named properties of a message and the tags they are stored under.

Returned by [MapiMessageItemBase.getNamedPropertyMapping()](../../com.aspose.email/mapimessageitembase\#getNamedPropertyMapping--). To add a named property by hand, get a free ID with \#getNextAvailablePropertyId(int).getNextAvailablePropertyId(int), set the property under that tag and register it with \#addNamedPropertyMapping(MapiProperty, long, UUID).addNamedPropertyMapping(MapiProperty, long, UUID). Setting a property through a [PidLidPropertyDescriptor](../../com.aspose.email/pidlidpropertydescriptor) or [PidNamePropertyDescriptor](../../com.aspose.email/pidnamepropertydescriptor) does all of this for you.
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiNamedPropertyMappingStorage()](#MapiNamedPropertyMappingStorage--) | Initializes a new instance of the [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) class. |
## Methods

| Method | Description |
| --- | --- |
| [addNamedPropertyMapping(MapiProperty property, String nameId, UUID guid)](#addNamedPropertyMapping-com.aspose.email.MapiProperty-java.lang.String-java.util.UUID-) | Registers a property as a named property with a string name. |
| [addNamedPropertyMapping(MapiProperty property, long nameId, UUID guid)](#addNamedPropertyMapping-com.aspose.email.MapiProperty-long-java.util.UUID-) | Registers a property as a named property with a numeric ID. |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Gets the code page of the ANSI strings of the object. |
| [getContent()](#getContent--) | Gets the content of the storage. |
| [getName()](#getName--) | Gets the name of the storage. |
| [getNextAvailablePropertyId(int dataType)](#getNextAvailablePropertyId-int-) | Gets a free tag in the named property range for a new property of the specified type. |
| [getProperties()](#getProperties--) | Gets all properties of the object. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets a MAPI property by its descriptor. |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | Gets the value of a property as a Boolean. |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | Gets the value of a property as bytes. |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | Gets the value of a property as a date and time. |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | Gets the value of a property as a 32-bit integer. |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | Gets the value of a property as a 64-bit integer. |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | Gets the value of a property as a 16-bit integer. |
| [getPropertyString(long tag)](#getPropertyString-long-) | Gets the value of a property as a string. |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Determines whether the string properties of the object are stored in Unicode. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Adds the property, or replaces the property with the same tag. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets the value of a MAPI property, creating the property if needed. |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | Gets the value of a property as bytes. |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | Gets the value of a property as a date and time, if the property exists. |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | Gets the value of a property as a string. |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | Gets the value of a property as a string, if the property exists. |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### MapiNamedPropertyMappingStorage() {#MapiNamedPropertyMappingStorage--}
```
public MapiNamedPropertyMappingStorage()
```


Initializes a new instance of the [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) class.

### addNamedPropertyMapping(MapiProperty property, String nameId, UUID guid) {#addNamedPropertyMapping-com.aspose.email.MapiProperty-java.lang.String-java.util.UUID-}
```
public final void addNamedPropertyMapping(MapiProperty property, String nameId, UUID guid)
```


Registers a property as a named property with a string name.

 property  should have a valid id for named property, \#getNextAvailablePropertyId(int).getNextAvailablePropertyId(int) can be used to generate one. Otherwise an exception will be thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | The property; its tag must be in the named property range. |
| nameId | java.lang.String | The name of the named property. |
| guid | java.util.UUID | The GUID of the property set. |

### addNamedPropertyMapping(MapiProperty property, long nameId, UUID guid) {#addNamedPropertyMapping-com.aspose.email.MapiProperty-long-java.util.UUID-}
```
public final void addNamedPropertyMapping(MapiProperty property, long nameId, UUID guid)
```


Registers a property as a named property with a numeric ID.

 property  should have a valid id for named property, \#getNextAvailablePropertyId(int).getNextAvailablePropertyId(int) can be used to generate one. Otherwise an exception will be thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| property | [MapiProperty](../../com.aspose.email/mapiproperty) | The property; its tag must be in the named property range. |
| nameId | long | The numeric ID (LID) of the named property. |
| guid | java.util.UUID | The GUID of the property set. |

### createMapiNode(String key) {#createMapiNode-java.lang.String-}
```
public IMapiNode createMapiNode(String key)
```


Creates the mapi node.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | java.lang.String | The node key. |

**Returns:**
com.aspose.email.IMapiNode - The IMapiNode interface.
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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCodePage() {#getCodePage--}
```
public int getCodePage()
```


Gets the code page of the ANSI strings of the object.

**Returns:**
int - The code page.
### getContent() {#getContent--}
```
public final Object getContent()
```


Gets the content of the storage.

**Returns:**
java.lang.Object - The content.
### getName() {#getName--}
```
public final String getName()
```


Gets the name of the storage.

**Returns:**
java.lang.String - The name.
### getNextAvailablePropertyId(int dataType) {#getNextAvailablePropertyId-int-}
```
public final long getNextAvailablePropertyId(int dataType)
```


Gets a free tag in the named property range for a new property of the specified type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| dataType | int | The data type of the new property. |

**Returns:**
long - The tag to give the new property before it is registered with \#addNamedPropertyMapping(MapiProperty, long, UUID).addNamedPropertyMapping(MapiProperty, long, UUID).
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Gets all properties of the object.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The properties.
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Gets a MAPI property by its descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The property, or  null  if the object does not have it.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


Gets the value of a property as a Boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Boolean - The value, or  null  if the property does not exist.
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


Gets the value of a property as bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
byte[] - The value, or  null  if the property does not exist.
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


Gets the value of a property as a date and time.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The tag of the property. |

**Returns:**
java.util.Date - The value, or  null  if the property does not exist.
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


Gets the value of a property as a 32-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Integer - The value, or  null  if the property does not exist.
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


Gets the value of a property as a 64-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Long - The value, or  null  if the property does not exist.
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


Gets the value of a property as a 16-bit integer.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.Short - The value, or  null  if the property does not exist.
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


Gets the value of a property as a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


Gets the value of a property as a string, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isStoreUnicodeOk() {#isStoreUnicodeOk--}
```
public final boolean isStoreUnicodeOk()
```


Determines whether the string properties of the object are stored in Unicode.

**Returns:**
boolean -  true  if the strings are Unicode;  false  if they are ANSI.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


Adds the property, or replaces the property with the same tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | The property to set. |

### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


Sets the value of a MAPI property, creating the property if needed.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |
| value | java.lang.Object | The value, of a Java type that matches the data type of the property. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### tryGetPropertyData(long tag) {#tryGetPropertyData-long-}
```
public final byte[] tryGetPropertyData(long tag)
```


Gets the value of a property as bytes.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
byte[] - The value, or  null  if the property does not exist.
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


Gets the value of a property as a date and time, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.util.Date[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


Gets the value of a property as a 32-bit integer, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | int[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


Gets the value of a property as a 64-bit integer, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | long[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


Gets the value of a property as a string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


Gets the value of a property as a string, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
java.lang.String - The value, or  null  if the property does not exist.
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


Gets the value of a property as a string, if the property exists.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.lang.String[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property. |
| value | java.lang.String[] | When this method returns, the value of the property, if it exists; otherwise, the value is unchanged. |
| codepage | int | The code page of an ANSI (8-bit) string. |

**Returns:**
boolean -  true  if the property exists; otherwise,  false .
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

