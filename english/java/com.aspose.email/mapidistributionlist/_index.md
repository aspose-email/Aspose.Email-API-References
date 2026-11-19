---
title: MapiDistributionList
second_title: Aspose.Email for Java API Reference
description: Represents a MAPI distribution list item.
type: docs
weight: 456
url: /java/com.aspose.email/mapidistributionlist/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiDistributionList extends MapiMessageItemBase
```

Represents a MAPI distribution list item.

This class serves as a wrapper for [MapiMessage](../../com.aspose.email/mapimessage) to simplify the process of handling distribution list information from MAPI properties. It provides a more intuitive interface for accessing and manipulating distribution list data within the MAPI message.

The following example demonstrates how to get a [MapiDistributionList](../../com.aspose.email/mapidistributionlist) object from a [MapiMessage](../../com.aspose.email/mapimessage).

```

 MapiMessage msg = MapiMessage.load("distributionList.msg");

 // Check if the loaded message is a supported distribution list type
 if (msg.getSupportedType() == MapiItemType.DistList) {
     // Convert the MAPI message to a MapiDistributionList object
     MapiDistributionList mapiDistributionList = (MapiDistributionList) msg.toMapiMessageItem();

     // Display some distribution list info
     System.out.println(mapiDistributionList.getDisplayName());
     System.out.println(mapiDistributionList.getMembers().size());
 }
 
```
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiDistributionList()](#MapiDistributionList--) | Initializes a new instance of the [MapiDistributionList](../../com.aspose.email/mapidistributionlist) class. |
| [MapiDistributionList(String displayName, MapiDistributionListMemberCollection members)](#MapiDistributionList-java.lang.String-com.aspose.email.MapiDistributionListMemberCollection-) | Initializes a new instance of the [MapiDistributionList](../../com.aspose.email/mapidistributionlist) class with a name and members. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) | Releases the resources used by the item. |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromVCF(InputStream stream)](#fromVCF-java.io.InputStream-) | Loads a distribution list from a vCard stream that contains the contacts of its members. |
| [fromVCF(String filePath)](#fromVCF-java.lang.String-) | Loads a distribution list from a vCard (.vcf) file that contains the contacts of its members. |
| [getAttachments()](#getAttachments--) | Gets the attachments of the item. |
| [getBilling()](#getBilling--) | Gets the billing information of the item. |
| [getBody()](#getBody--) | Gets the plain-text body of the item. |
| [getBodyHtml()](#getBodyHtml--) | Gets the body of the item as HTML, converted from \#getBodyRtf().getBodyRtf(); an empty string when there is no RTF body. |
| [getBodyRtf()](#getBodyRtf--) | Gets the body of the item in RTF format. |
| [getBodyType()](#getBodyType--) | Gets the format of the body: plain text, HTML or RTF. |
| [getCategories()](#getCategories--) | Gets the categories of the item. |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Gets the code page of the ANSI strings of the object. |
| [getCompanies()](#getCompanies--) | Gets the names of the companies associated with the item. |
| [getDisplayName()](#getDisplayName--) | Gets the name of the distribution list. |
| [getItemId()](#getItemId--) | Gets the identifier of the item on the mail server, for items obtained from a server;  null  otherwise. |
| [getMembers()](#getMembers--) | Gets the members of the distribution list. |
| [getMessageClass()](#getMessageClass--) | Gets the message class of the item, such as  IPM.Note  for an e-mail message. |
| [getMileage()](#getMileage--) | Gets the mileage information of the item. |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of the item. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Gets the mapping between the named properties and the tags they are stored under. |
| [getProperties()](#getProperties--) | Gets all properties of the object. |
| [getProperty(PropertyDescriptor pd)](#getProperty-com.aspose.email.PropertyDescriptor-) | Gets a MAPI property of the item by its descriptor. |
| [getPropertyBoolean(long tag)](#getPropertyBoolean-long-) | Gets the value of a property as a Boolean. |
| [getPropertyBytes(long tag)](#getPropertyBytes-long-) | Gets the value of a property as bytes. |
| [getPropertyDateTime(long key)](#getPropertyDateTime-long-) | Gets the value of a property as a date and time. |
| [getPropertyInt32(long tag)](#getPropertyInt32-long-) | Gets the value of a property as a 32-bit integer. |
| [getPropertyLong(long tag)](#getPropertyLong-long-) | Gets the value of a property as a 64-bit integer. |
| [getPropertyShort(long tag)](#getPropertyShort-long-) | Gets the value of a property as a 16-bit integer. |
| [getPropertyStream()](#getPropertyStream--) | Gets the property stream of the item. |
| [getPropertyString(long tag)](#getPropertyString-long-) | Gets the value of a property as a string. |
| [getPropertyString(long tag, int codepage)](#getPropertyString-long-int-) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [getRecipients()](#getRecipients--) | Gets the recipients of the item. |
| [getSensitivity()](#getSensitivity--) | Gets the sensitivity of the item: normal, personal, private or confidential. |
| [getSubStorages()](#getSubStorages--) | Gets the sub-storages of the item. |
| [getSubject()](#getSubject--) | Gets the subject of the message. |
| [getSubjectPrefix()](#getSubjectPrefix--) | Gets the prefix of the subject, such as  RE:  or  FW: . |
| [getSupportedType()](#getSupportedType--) | Gets the type of the item, as determined by its message class. |
| [getUnderlyingMessage()](#getUnderlyingMessage--) | Retrieves the underlying MapiMessage object. |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Determines whether the string properties of the object are stored in Unicode. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Loads a [MapiDistributionList](../../com.aspose.email/mapidistributionlist) from the specified stream. |
| [load(String filePath)](#load-java.lang.String-) | Loads a [MapiDistributionList](../../com.aspose.email/mapidistributionlist) from the specified file. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(long tag)](#removeProperty-long-) | Removes a property from the item, including its named-property mapping. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves the distribution list to a stream in MSG format. |
| [save(OutputStream stream, MapiDistributionListSaveOptions options)](#save-java.io.OutputStream-com.aspose.email.MapiDistributionListSaveOptions-) | Saves the distribution list to a stream with the specified options. |
| [save(String fileName)](#save-java.lang.String-) | Saves the distribution list to a file in MSG format. |
| [save(String fileName, MapiDistributionListSaveOptions options)](#save-java.lang.String-com.aspose.email.MapiDistributionListSaveOptions-) | Saves the distribution list to a file with the specified options. |
| [setBilling(String value)](#setBilling-java.lang.String-) | Sets the billing information of the item. |
| [setBody(String value)](#setBody-java.lang.String-) | Sets the plain-text body of the item. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Sets the body of the item in the specified format. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Sets the body of the item in the specified format, optionally compressing it. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Sets the body of the item in RTF format. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Sets the body of the item in RTF format, optionally compressing it. |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Sets the categories of the item. |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Sets the names of the companies associated with the item. |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Sets the name of the distribution list. |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Sets the message class of the item, such as  IPM.Note  for an e-mail message. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Sets the flags of the message, such as read or unsent. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Sets the mileage information of the item. |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Sets the named property mapping. |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Adds the property, or replaces the property with the same tag. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets the value of a MAPI property of the item. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Sets the recipients of the item. |
| [setSensitivity(int value)](#setSensitivity-int-) | Sets the sensitivity of the item: normal, personal, private or confidential. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of the message. |
| [toMvPropertyList(Object obj)](#toMvPropertyList-java.lang.Object-) |  |
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
### MapiDistributionList() {#MapiDistributionList--}
```
public MapiDistributionList()
```


Initializes a new instance of the [MapiDistributionList](../../com.aspose.email/mapidistributionlist) class.

### MapiDistributionList(String displayName, MapiDistributionListMemberCollection members) {#MapiDistributionList-java.lang.String-com.aspose.email.MapiDistributionListMemberCollection-}
```
public MapiDistributionList(String displayName, MapiDistributionListMemberCollection members)
```


Initializes a new instance of the [MapiDistributionList](../../com.aspose.email/mapidistributionlist) class with a name and members.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| displayName | java.lang.String | The name of the list. |
| members | [MapiDistributionListMemberCollection](../../com.aspose.email/mapidistributionlistmembercollection) | The members of the list. |

### close() {#close--}
```
public void close()
```


Releases the resources used by the item.

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
### dispose() {#dispose--}
```
public void dispose()
```


Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources.

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
### fromVCF(InputStream stream) {#fromVCF-java.io.InputStream-}
```
public static MapiDistributionList fromVCF(InputStream stream)
```


Loads a distribution list from a vCard stream that contains the contacts of its members.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to read. |

**Returns:**
[MapiDistributionList](../../com.aspose.email/mapidistributionlist) - The loaded distribution list.
### fromVCF(String filePath) {#fromVCF-java.lang.String-}
```
public static MapiDistributionList fromVCF(String filePath)
```


Loads a distribution list from a vCard (.vcf) file that contains the contacts of its members.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path of the file. |

**Returns:**
[MapiDistributionList](../../com.aspose.email/mapidistributionlist) - The loaded distribution list.
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


Gets the attachments of the item.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection) - The attachments.
### getBilling() {#getBilling--}
```
public final String getBilling()
```


Gets the billing information of the item.

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public String getBody()
```


Gets the plain-text body of the item.

**Returns:**
java.lang.String - The body.
### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


Gets the body of the item as HTML, converted from \#getBodyRtf().getBodyRtf(); an empty string when there is no RTF body.

**Returns:**
java.lang.String
### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


Gets the body of the item in RTF format.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int), which encapsulates HTML in RTF as Outlook does. Setting  null  or an empty string clears both bodies.

**Returns:**
java.lang.String - The RTF body.
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Gets the format of the body: plain text, HTML or RTF.

**Returns:**
int - The format of the body.
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Gets the categories of the item.

**Returns:**
java.lang.String[]
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
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Gets the names of the companies associated with the item.

**Returns:**
java.lang.String[]
### getDisplayName() {#getDisplayName--}
```
public final String getDisplayName()
```


Gets the name of the distribution list.

**Returns:**
java.lang.String - The name of the list.
### getItemId() {#getItemId--}
```
public String getItemId()
```


Gets the identifier of the item on the mail server, for items obtained from a server;  null  otherwise.

**Returns:**
java.lang.String
### getMembers() {#getMembers--}
```
public final MapiDistributionListMemberCollection getMembers()
```


Gets the members of the distribution list.

**Returns:**
[MapiDistributionListMemberCollection](../../com.aspose.email/mapidistributionlistmembercollection) - The members.
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets the message class of the item, such as  IPM.Note  for an e-mail message. The class determines the type of the item.

**Returns:**
java.lang.String - The message class. It is case-sensitive.
### getMileage() {#getMileage--}
```
public final String getMileage()
```


Gets the mileage information of the item.

**Returns:**
java.lang.String
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of the item.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The named properties.
### getNamedPropertyMapping() {#getNamedPropertyMapping--}
```
public final MapiNamedPropertyMappingStorage getNamedPropertyMapping()
```


Gets the mapping between the named properties and the tags they are stored under.

**Returns:**
[MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) - The named property mapping.
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


Gets a MAPI property of the item by its descriptor.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |

**Returns:**
[MapiProperty](../../com.aspose.email/mapiproperty) - The property, or  null  if the item does not have it.
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
### getPropertyStream() {#getPropertyStream--}
```
public final MapiPropertyStream getPropertyStream()
```


Gets the property stream of the item.

**Returns:**
[MapiPropertyStream](../../com.aspose.email/mapipropertystream) - The property stream.
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
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


Gets the recipients of the item.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) - The recipients.
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the sensitivity of the item: normal, personal, private or confidential.

**Returns:**
int - The sensitivity.
### getSubStorages() {#getSubStorages--}
```
public final MapiPropertyCollection getSubStorages()
```


Gets the sub-storages of the item.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection) - The sub-storages.
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets the subject of the message.

Setting the subject also sets the subject prefix (such as  RE: ) and the normalized subject (the subject without the prefix). Setting  null  or an empty string clears all three.

**Returns:**
java.lang.String - The subject.
### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


Gets the prefix of the subject, such as  RE:  or  FW: .

**Returns:**
java.lang.String - The subject prefix.
### getSupportedType() {#getSupportedType--}
```
public final int getSupportedType()
```


Gets the type of the item, as determined by its message class.

**Returns:**
int - The item type.
### getUnderlyingMessage() {#getUnderlyingMessage--}
```
public final MapiMessage getUnderlyingMessage()
```


Retrieves the underlying MapiMessage object.

Retrieves the underlying MAPI message from a MapiDistributionList object and prints out its message class.

```

 // Retrieve the underlying MAPI message from the MapiDistributionList object
 MapiMessage msg = mapiDistributionList.getUnderlyingMessage();

 // Print out the message class of the MAPI message
 // Will output "IPM.DistList"
 System.out.println(msg.getMessageClass());
 
```

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The [MapiMessage](../../com.aspose.email/mapimessage) object.
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
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static MapiDistributionList load(InputStream stream)
```


Loads a [MapiDistributionList](../../com.aspose.email/mapidistributionlist) from the specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | The stream to be loaded. |

**Returns:**
[MapiDistributionList](../../com.aspose.email/mapidistributionlist) - Returns a [MapiDistributionList](../../com.aspose.email/mapidistributionlist) instance loaded from the specified stream.
### load(String filePath) {#load-java.lang.String-}
```
public static MapiDistributionList load(String filePath)
```


Loads a [MapiDistributionList](../../com.aspose.email/mapidistributionlist) from the specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | The path to the file to be loaded. |

**Returns:**
[MapiDistributionList](../../com.aspose.email/mapidistributionlist) - Returns a [MapiDistributionList](../../com.aspose.email/mapidistributionlist) instance loaded from the specified file.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Removes a property from the item, including its named-property mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of the property to remove. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves the distribution list to a stream in MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |

### save(OutputStream stream, MapiDistributionListSaveOptions options) {#save-java.io.OutputStream-com.aspose.email.MapiDistributionListSaveOptions-}
```
public final void save(OutputStream stream, MapiDistributionListSaveOptions options)
```


Saves the distribution list to a stream with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream to write to. |
| options | [MapiDistributionListSaveOptions](../../com.aspose.email/mapidistributionlistsaveoptions) | The options; [ContactSaveOptions.getSaveFormat()](../../com.aspose.email/contactsaveoptions\#getSaveFormat--) selects MSG or vCard. In vCard format every member is written as a separate vCard. |

### save(String fileName) {#save-java.lang.String-}
```
public final void save(String fileName)
```


Saves the distribution list to a file in MSG format.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to write. |

### save(String fileName, MapiDistributionListSaveOptions options) {#save-java.lang.String-com.aspose.email.MapiDistributionListSaveOptions-}
```
public final void save(String fileName, MapiDistributionListSaveOptions options)
```


Saves the distribution list to a file with the specified options.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | The path of the file to write. |
| options | [MapiDistributionListSaveOptions](../../com.aspose.email/mapidistributionlistsaveoptions) | The options; [ContactSaveOptions.getSaveFormat()](../../com.aspose.email/contactsaveoptions\#getSaveFormat--) selects MSG or vCard. In vCard format every member is written as a separate vCard. |

### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


Sets the billing information of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


Sets the plain-text body of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The body. |

### setBodyContent(String content, int contentType) {#setBodyContent-java.lang.String-int-}
```
public void setBodyContent(String content, int contentType)
```


Sets the body of the item in the specified format.

The plain-text body, the RTF body and the compressed RTF property are all updated. After HTML content is set, \#getBodyRtf().getBodyRtf() returns that HTML encapsulated in RTF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The text of the body. |
| contentType | int | The format of  content . |

### setBodyContent(String content, int contentType, boolean compression) {#setBodyContent-java.lang.String-int-boolean-}
```
public void setBodyContent(String content, int contentType, boolean compression)
```


Sets the body of the item in the specified format, optionally compressing it.

The plain-text body, the RTF body and the compressed RTF property are all updated. After HTML content is set, \#getBodyRtf().getBodyRtf() returns that HTML encapsulated in RTF.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The text of the body. |
| contentType | int | The format of  content . |
| compression | boolean |  true  to store the RTF body compressed. |

### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


Sets the body of the item in RTF format.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int), which encapsulates HTML in RTF as Outlook does. Setting  null  or an empty string clears both bodies.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The RTF body. |

### setBodyRtf(String value, boolean compression) {#setBodyRtf-java.lang.String-boolean-}
```
public final void setBodyRtf(String value, boolean compression)
```


Sets the body of the item in RTF format, optionally compressing it.

Setting a value updates the plain-text body and the compressed RTF property as well. The value must be RTF; to set an HTML or plain-text body, use \#setBodyContent(String, int).setBodyContent(String, int). Setting  null  or an empty string clears both bodies.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The body in RTF. |
| compression | boolean |  true  to store the RTF body compressed. |

### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


Sets the categories of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Sets the names of the companies associated with the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public final void setDisplayName(String value)
```


Sets the name of the distribution list.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The name of the list. |

### setMessageClass(String value) {#setMessageClass-java.lang.String-}
```
public final void setMessageClass(String value)
```


Sets the message class of the item, such as  IPM.Note  for an e-mail message. The class determines the type of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The message class. It is case-sensitive. |

### setMessageFlags(long flags) {#setMessageFlags-long-}
```
public final void setMessageFlags(long flags)
```


Sets the flags of the message, such as read or unsent.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The flags to set. |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Sets the mileage information of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNamedPropertyMapping(MapiNamedPropertyMappingStorage value) {#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-}
```
public final void setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)
```


Sets the named property mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) | The MapiNamedPropertyMappingStorage. |

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


Sets the value of a MAPI property of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pd | [PropertyDescriptor](../../com.aspose.email/propertydescriptor) | The descriptor of the property, for example one from [KnownPropertyList](../../com.aspose.email/knownpropertylist). |
| value | java.lang.Object | The value, of a Java type that matches the data type of the property. |

### setRecipients(MapiRecipientCollection value) {#setRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setRecipients(MapiRecipientCollection value)
```


Sets the recipients of the item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) | The recipients. |

### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


Sets the sensitivity of the item: normal, personal, private or confidential.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The sensitivity. |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Sets the subject of the message.

Setting the subject also sets the subject prefix (such as  RE: ) and the normalized subject (the subject without the prefix). Setting  null  or an empty string clears all three.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The subject. |

### toMvPropertyList(Object obj) {#toMvPropertyList-java.lang.Object-}
```
public static System.Collections.Generic.IGenericList<Object> toMvPropertyList(Object obj)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericList<java.lang.Object>
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

