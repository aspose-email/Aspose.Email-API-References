---
title: MapiRecipient
second_title: Aspose.Email for Android via Java API Reference
description: Represents the recipient information in the Microsoft Outlook Message.
type: docs
weight: 278
url: /androidjava/com.aspose.email/mapirecipient/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer)
```
public class MapiRecipient extends MapiPropertyContainer
```

Represents the recipient information in the Microsoft Outlook Message.
## Methods

| Method | Description |
| --- | --- |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAddressType()](#getAddressType--) | Gets the type of the address of the message recipient or sender. |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Gets the code page. |
| [getContent()](#getContent--) | Gets the content. |
| [getDisplayName()](#getDisplayName--) | Gets or sets the display name of the message recipient or sender. |
| [getEmailAddress()](#getEmailAddress--) | Gets or sets the email address of the message recipient or sender. |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of message. |
| [getOrganizationEmailAddress()](#getOrganizationEmailAddress--) | Gets the organization email address. |
| [getProperties()](#getProperties--) | Gets the collection of properties. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets MAPI property by property descriptor. |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | Gets the value of the property specified by tag as Boolean type. |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | Gets the string value of the property specified by tag. |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | Gets the value of the property specified by tag as DateTime type. |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | Gets the int32 value of the property specified by tag. |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | Gets the value of the property specified by tag as Long (int64) type. |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | Gets the value of the property specified by tag as Short type. |
| [getPropertyStream()](#getPropertyStream--) | Gets the property stream. |
| [getPropertyString(long tag)](#getPropertyString-long-) | Gets the string value of the property specified by tag. |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | Gets the string value of the property specified by tag. |
| [getRecipientClass()](#getRecipientClass--) | Gets the type of recipent. |
| [getRecipientTrackStatus()](#getRecipientTrackStatus--) | Status of recipient\\u2019s response to a meeting request. |
| [getRecipientType()](#getRecipientType--) | Gets the type of the recipient or sender. |
| [getSubStorages()](#getSubStorages--) | Gets the sub storages. |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Determines if string properties are Unicode encoded or not. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Gets or sets the display name of the message recipient or sender. |
| [setEmailAddress(String value)](#setEmailAddress-java.lang.String-) | Gets or sets the email address of the message recipient or sender. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Sets the property. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets MAPI property. |
| [setRecipientTrackStatus(int value)](#setRecipientTrackStatus-int-) | Status of recipient\\u2019s response to a meeting request. |
| [toString()](#toString--) |  |
| [tryGetPropertyData(long tag)](#tryGetPropertyData-long-) | Try to get the property data with specified tag key. |
| [tryGetPropertyDateTime(long tag, Date[] value)](#tryGetPropertyDateTime-long-java.util.Date---) | Gets the value of the specified property as DateTime type. |
| [tryGetPropertyInt32(long tag, int[] value)](#tryGetPropertyInt32-long-int---) | Gets the value of the specified property as Int32 type. |
| [tryGetPropertyLong(long tag, long[] value)](#tryGetPropertyLong-long-long---) | Gets the value of the specified property as Long type. |
| [tryGetPropertyString(long tag)](#tryGetPropertyString-long-) | Try to get a property data as string with specified tag. |
| [tryGetPropertyString(long tag, int codepage)](#tryGetPropertyString-long-int-) | Try to get a property data as string with specified tag and code page. |
| [tryGetPropertyString(long tag, String[] value)](#tryGetPropertyString-long-java.lang.String---) | Gets the value of the specified property as String type. |
| [tryGetPropertyString(long tag, String[] value, int codepage)](#tryGetPropertyString-long-java.lang.String---int-) | Gets the value of the specified property as String type. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getAddressType() {#getAddressType--}
```
public final String getAddressType()
```


Gets the type of the address of the message recipient or sender.

Value: The address type.

--------------------

This property indicates the type for PR\_EMAIL\_ADDRESS mapi property.

**Returns:**
java.lang.String
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


Gets the code page.

Value: The code page.

**Returns:**
int
### getContent() {#getContent--}
```
public final Object getContent()
```


Gets the content.

Value: The content.

**Returns:**
java.lang.Object
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets or sets the display name of the message recipient or sender.

Value: The display name.

--------------------

When setting a value, the values of either MapiMessage.DisplayTo or MapiMessage.DisplayBcc or MapiMessage.DisplayCC are also updated depending on the type of recepient.

**Returns:**
java.lang.String
### getEmailAddress() {#getEmailAddress--}
```
public final String getEmailAddress()
```


Gets or sets the email address of the message recipient or sender.

**Returns:**
java.lang.String
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of message.

Value: The collection of named properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getOrganizationEmailAddress() {#getOrganizationEmailAddress--}
```
public final String getOrganizationEmailAddress()
```


Gets the organization email address.

Value: The organization email address.

**Returns:**
java.lang.String
### getProperties() {#getProperties--}
```
public MapiPropertyCollection getProperties()
```


Gets the collection of properties.

Value: The properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getProperty(PropertyDescriptor pd) {#getProperty-com.aspose.email.PropertyDescriptor-}
```
public MapiProperty getProperty(PropertyDescriptor pd)
```


Gets MAPI property by property descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | Property descriptor for looked property |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - Mapi property if it is found, otherwise null.
### getPropertyBoolean(long tag) {#getPropertyBoolean-long-}
```
public final Boolean getPropertyBoolean(long tag)
```


Gets the value of the property specified by tag as Boolean type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Boolean - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyBytes(long tag) {#getPropertyBytes-long-}
```
public final byte[] getPropertyBytes(long tag)
```


Gets the string value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
byte[] - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyDateTime(long key) {#getPropertyDateTime-long-}
```
public final Date getPropertyDateTime(long key)
```


Gets the value of the property specified by tag as DateTime type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| key | long | The MAPI property tag. |

**Returns:**
java.util.Date - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyInt32(long tag) {#getPropertyInt32-long-}
```
public final Integer getPropertyInt32(long tag)
```


Gets the int32 value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Integer - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyLong(long tag) {#getPropertyLong-long-}
```
public final Long getPropertyLong(long tag)
```


Gets the value of the property specified by tag as Long (int64) type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Long - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyShort(long tag) {#getPropertyShort-long-}
```
public final Short getPropertyShort(long tag)
```


Gets the value of the property specified by tag as Short type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.Short - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Gets the property stream.

Value: The property stream.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream)
### getPropertyString(long tag) {#getPropertyString-long-}
```
public final String getPropertyString(long tag)
```


Gets the string value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |

**Returns:**
java.lang.String - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getPropertyString(long tag, int codepage) {#getPropertyString-long-int-}
```
public final String getPropertyString(long tag, int codepage)
```


Gets the string value of the property specified by tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| codepage | int | The specified codepage used to get string value. |

**Returns:**
java.lang.String - The value of the property. If the property does not exist, returns NULL; otherwise, returns the value.
### getRecipientClass() {#getRecipientClass--}
```
public final int getRecipientClass()
```


Gets the type of recipent.

Value: The recipient class.

**Returns:**
int
### getRecipientTrackStatus() {#getRecipientTrackStatus--}
```
public final int getRecipientTrackStatus()
```


Status of recipient\\u2019s response to a meeting request.

**Returns:**
int
### getRecipientType() {#getRecipientType--}
```
public final int getRecipientType()
```


Gets the type of the recipient or sender.

Value: The recipient type.

**Returns:**
int
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Gets the sub storages.

Value: The sub storages.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
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


Determines if string properties are Unicode encoded or not.

**Returns:**
boolean - True, if string properties are Unicode encoded.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Gets or sets the display name of the message recipient or sender.

Value: The display name.

--------------------

When setting a value, the values of either MapiMessage.DisplayTo or MapiMessage.DisplayBcc or MapiMessage.DisplayCC are also updated depending on the type of recepient.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setEmailAddress(String value) {#setEmailAddress-java.lang.String-}
```
public final void setEmailAddress(String value)
```


Gets or sets the email address of the message recipient or sender.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setProperty(MapiProperty value) {#setProperty-com.aspose.email.MapiProperty-}
```
public void setProperty(MapiProperty value)
```


Sets the property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiProperty](../../com.aspose.email/mapiproperty) | The property. |

### setProperty(PropertyDescriptor pd, Object value) {#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-}
```
public void setProperty(PropertyDescriptor pd, Object value)
```


Sets MAPI property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The property descriptor. |
| value | java.lang.Object | The property data. |

### setRecipientTrackStatus(int value) {#setRecipientTrackStatus-int-}
```
public final void setRecipientTrackStatus(int value)
```


Status of recipient\\u2019s response to a meeting request.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

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


Try to get the property data with specified tag key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag key. |

**Returns:**
byte[] - The property data.
### tryGetPropertyDateTime(long tag, Date[] value) {#tryGetPropertyDateTime-long-java.util.Date---}
```
public final boolean tryGetPropertyDateTime(long tag, Date[] value)
```


Gets the value of the specified property as DateTime type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | java.util.Date[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyInt32(long tag, int[] value) {#tryGetPropertyInt32-long-int---}
```
public final boolean tryGetPropertyInt32(long tag, int[] value)
```


Gets the value of the specified property as Int32 type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | int[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyLong(long tag, long[] value) {#tryGetPropertyLong-long-long---}
```
public final boolean tryGetPropertyLong(long tag, long[] value)
```


Gets the value of the specified property as Long type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | long[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyString(long tag) {#tryGetPropertyString-long-}
```
public final String tryGetPropertyString(long tag)
```


Try to get a property data as string with specified tag.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The property tag key. |

**Returns:**
java.lang.String - String that contains the contents of property data.
### tryGetPropertyString(long tag, int codepage) {#tryGetPropertyString-long-int-}
```
public final String tryGetPropertyString(long tag, int codepage)
```


Try to get a property data as string with specified tag and code page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The property tag key. |
| codepage | int | The code page. |

**Returns:**
java.lang.String - String that contains the contents of property data.
### tryGetPropertyString(long tag, String[] value) {#tryGetPropertyString-long-java.lang.String---}
```
public final boolean tryGetPropertyString(long tag, String[] value)
```


Gets the value of the specified property as String type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | java.lang.String[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
### tryGetPropertyString(long tag, String[] value, int codepage) {#tryGetPropertyString-long-java.lang.String---int-}
```
public final boolean tryGetPropertyString(long tag, String[] value, int codepage)
```


Gets the value of the specified property as String type. A return value indicates whether the operation succeeded.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The MAPI property tag. |
| value | java.lang.String[] | When this method returns, contains the value of the specified property, if the property exists. This parameter is passed uninitialized. |
| codepage | int | The specified codepage used to get string value. |

**Returns:**
boolean - true if s was converted successfully; otherwise, false.
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

