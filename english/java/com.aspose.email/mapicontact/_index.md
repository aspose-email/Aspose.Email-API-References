---
title: MapiContact
second_title: Aspose.Email for Java API Reference
description: Represents outlook contact information
type: docs
weight: 416
url: /java/com.aspose.email/mapicontact/
---

**Inheritance:**
java.lang.Object, [com.aspose.email.MapiPropertyContainer](../../com.aspose.email/mapipropertycontainer), [com.aspose.email.MapiMessageItemBase](../../com.aspose.email/mapimessageitembase)
```
public final class MapiContact extends MapiMessageItemBase
```

Represents outlook contact information
## Constructors

| Constructor | Description |
| --- | --- |
| [MapiContact()](#MapiContact--) | Initializes a new instance of the [MapiContact](../../com.aspose.email/mapicontact) class |
| [MapiContact(String displayName, String electonicAddress)](#MapiContact-java.lang.String-java.lang.String-) | Initializes a new instance of the [MapiContact](../../com.aspose.email/mapicontact) class. |
| [MapiContact(String displayName, String electonicAddress, String companyName)](#MapiContact-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [MapiContact](../../com.aspose.email/mapicontact) class. |
| [MapiContact(String displayName, String electonicAddress, String companyName, String primaryTelephoneNumber)](#MapiContact-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | Initializes a new instance of the [MapiContact](../../com.aspose.email/mapicontact) class. |
## Methods

| Method | Description |
| --- | --- |
| [close()](#close--) |  |
| [createMapiNode(String key)](#createMapiNode-java.lang.String-) | Creates the mapi node. |
| [dispose()](#dispose--) | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromVCard(InputStream stream)](#fromVCard-java.io.InputStream-) | Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified stream containing vCard. |
| [fromVCard(InputStream stream, Charset encoding)](#fromVCard-java.io.InputStream-java.nio.charset.Charset-) | Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified stream containing vCard. |
| [fromVCard(String filePath)](#fromVCard-java.lang.String-) | Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| [fromVCard(String filePath, Charset encoding)](#fromVCard-java.lang.String-java.nio.charset.Charset-) | Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| [getAttachments()](#getAttachments--) | Gets the attachments in the message. |
| [getBilling()](#getBilling--) | Contains the billing information associated with an item. |
| [getBody()](#getBody--) | Gets the message text. |
| [getBodyHtml()](#getBodyHtml--) | Gets the  BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) of the message converted to HTML, if present, otherwise an empty string. |
| [getBodyRtf()](#getBodyRtf--) | Gets or sets the RTF formatted message text. |
| [getBodyType()](#getBodyType--) | Gets the type of the body. |
| [getCategories()](#getCategories--) | Contains keywords or categories for the message object. |
| [getClass()](#getClass--) |  |
| [getCodePage()](#getCodePage--) | Gets the code page. |
| [getCompanies()](#getCompanies--) | Contains the names of the companies that are associated with an item. |
| [getElectronicAddresses()](#getElectronicAddresses--) | Specify properties for up to three different e-mail addresses and three different fax addresses |
| [getEvents()](#getEvents--) | Specify events associated with a contact |
| [getItemId()](#getItemId--) | Uses to specify the server id of the contact EWS only |
| [getMessageClass()](#getMessageClass--) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. |
| [getMileage()](#getMileage--) | Contains the mileage information that is associated with an item. |
| [getNameInfo()](#getNameInfo--) | The properties are used to specify the name of the person represented by the contact |
| [getNamedProperties()](#getNamedProperties--) | Gets the named properties of message. |
| [getNamedPropertyMapping()](#getNamedPropertyMapping--) | Gets the named property mapping. |
| [getOtherFields()](#getOtherFields--) | Specify other fields of conhtact. |
| [getPersonalInfo()](#getPersonalInfo--) | Specify other additional contact information |
| [getPhoto()](#getPhoto--) | Contains contact photo[MapiContactPhoto](../../com.aspose.email/mapicontactphoto). |
| [getPhysicalAddresses()](#getPhysicalAddresses--) | Specify three physical addresses: Home Address, Work Address, and Other Address. |
| [getProfessionalInfo()](#getProfessionalInfo--) | Properties are used to store professional details for the person represented by the contact |
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
| [getRecipients()](#getRecipients--) | Gets the recipients of the message. |
| [getSensitivity()](#getSensitivity--) | Gets the Sensitivity. |
| [getSubStorages()](#getSubStorages--) | Gets the sub storages. |
| [getSubject()](#getSubject--) | Gets or sets the subject of the message. |
| [getSubjectPrefix()](#getSubjectPrefix--) | Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding. |
| [getSupportedType()](#getSupportedType--) | Gets the supported item type. |
| [getTelephones()](#getTelephones--) | Specify telephone numbers for the contact |
| [getUnderlyingMessage()](#getUnderlyingMessage--) | Retrieves the underlying MapiMessage object. |
| [hashCode()](#hashCode--) |  |
| [isStoreUnicodeOk()](#isStoreUnicodeOk--) | Determines if string properties are Unicode encoded or not. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(long tag)](#removeProperty-long-) | Provides correctly removing property from all collections. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) into the given stream with vCard format. |
| [save(OutputStream stream, ContactSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.ContactSaveOptions-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the given stream using specified save options. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the given stream with a format using the default options. |
| [save(String filePath)](#save-java.lang.String-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the vCard file with a default options. |
| [save(String filePath, ContactSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.ContactSaveOptions-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) into file using specified save options. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the specified file with a format using the default options. |
| [setBilling(String value)](#setBilling-java.lang.String-) | Contains the billing information associated with an item. |
| [setBody(String value)](#setBody-java.lang.String-) | Gets the message text. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Sets the content of the body. |
| [setBodyContent(String content, int contentType, boolean compression)](#setBodyContent-java.lang.String-int-boolean-) | Sets the content of the body. |
| [setBodyRtf(String value)](#setBodyRtf-java.lang.String-) | Gets or sets the RTF formatted message text. |
| [setBodyRtf(String value, boolean compression)](#setBodyRtf-java.lang.String-boolean-) | Gets or sets the RTF formatted message text. |
| [setCategories(String[] value)](#setCategories-java.lang.String---) | Contains keywords or categories for the message object. |
| [setCompanies(String[] value)](#setCompanies-java.lang.String---) | Contains the names of the companies that are associated with an item. |
| [setElectronicAddresses(MapiContactElectronicAddressPropertySet value)](#setElectronicAddresses-com.aspose.email.MapiContactElectronicAddressPropertySet-) | Specify properties for up to three different e-mail addresses and three different fax addresses |
| [setEvents(MapiContactEventPropertySet value)](#setEvents-com.aspose.email.MapiContactEventPropertySet-) | Specify events associated with a contact |
| [setMessageClass(String value)](#setMessageClass-java.lang.String-) | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. |
| [setMessageFlags(long flags)](#setMessageFlags-long-) | Sets the message flags. |
| [setMileage(String value)](#setMileage-java.lang.String-) | Contains the mileage information that is associated with an item. |
| [setNameInfo(MapiContactNamePropertySet value)](#setNameInfo-com.aspose.email.MapiContactNamePropertySet-) | The properties are used to specify the name of the person represented by the contact |
| [setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)](#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-) | Sets the named property mapping. |
| [setOtherFields(MapiContactOtherPropertySet value)](#setOtherFields-com.aspose.email.MapiContactOtherPropertySet-) | Specify other fields of conhtact. |
| [setPersonalInfo(MapiContactPersonalInfoPropertySet value)](#setPersonalInfo-com.aspose.email.MapiContactPersonalInfoPropertySet-) | Specify other additional contact information |
| [setPhoto(MapiContactPhoto value)](#setPhoto-com.aspose.email.MapiContactPhoto-) | Contains contact photo[MapiContactPhoto](../../com.aspose.email/mapicontactphoto). |
| [setPhysicalAddresses(MapiContactPhysicalAddressPropertySet value)](#setPhysicalAddresses-com.aspose.email.MapiContactPhysicalAddressPropertySet-) | Specify three physical addresses: Home Address, Work Address, and Other Address. |
| [setProfessionalInfo(MapiContactProfessionalPropertySet value)](#setProfessionalInfo-com.aspose.email.MapiContactProfessionalPropertySet-) | Properties are used to store professional details for the person represented by the contact |
| [setProperty(MapiProperty value)](#setProperty-com.aspose.email.MapiProperty-) | Sets the property. |
| [setProperty(PropertyDescriptor pd, Object value)](#setProperty-com.aspose.email.PropertyDescriptor-java.lang.Object-) | Sets MAPI property. |
| [setRecipients(MapiRecipientCollection value)](#setRecipients-com.aspose.email.MapiRecipientCollection-) | Gets the recipients of the message. |
| [setSensitivity(int value)](#setSensitivity-int-) | Gets the Sensitivity. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Gets or sets the subject of the message. |
| [setTelephones(MapiContactTelephonePropertySet value)](#setTelephones-com.aspose.email.MapiContactTelephonePropertySet-) | Specify telephone numbers for the contact |
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
### MapiContact() {#MapiContact--}
```
public MapiContact()
```


Initializes a new instance of the [MapiContact](../../com.aspose.email/mapicontact) class

### MapiContact(String displayName, String electonicAddress) {#MapiContact-java.lang.String-java.lang.String-}
```
public MapiContact(String displayName, String electonicAddress)
```


Initializes a new instance of the [MapiContact](../../com.aspose.email/mapicontact) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| displayName | java.lang.String | The display name. |
| electonicAddress | java.lang.String | The electonic address. |

### MapiContact(String displayName, String electonicAddress, String companyName) {#MapiContact-java.lang.String-java.lang.String-java.lang.String-}
```
public MapiContact(String displayName, String electonicAddress, String companyName)
```


Initializes a new instance of the [MapiContact](../../com.aspose.email/mapicontact) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| displayName | java.lang.String | The display name. |
| electonicAddress | java.lang.String | The electonic address. |
| companyName | java.lang.String | Name of the company. |

### MapiContact(String displayName, String electonicAddress, String companyName, String primaryTelephoneNumber) {#MapiContact-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public MapiContact(String displayName, String electonicAddress, String companyName, String primaryTelephoneNumber)
```


Initializes a new instance of the [MapiContact](../../com.aspose.email/mapicontact) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| displayName | java.lang.String | The display name. |
| electonicAddress | java.lang.String | The electonic address. |
| companyName | java.lang.String | Name of the company. |
| primaryTelephoneNumber | java.lang.String | The telephone number. |

### close() {#close--}
```
public void close()
```




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
### fromVCard(InputStream stream) {#fromVCard-java.io.InputStream-}
```
public static MapiContact fromVCard(InputStream stream)
```


Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream to read from |

**Returns:**
[MapiContact](../../com.aspose.email/mapicontact) - A read [MapiContact](../../com.aspose.email/mapicontact)
### fromVCard(InputStream stream, Charset encoding) {#fromVCard-java.io.InputStream-java.nio.charset.Charset-}
```
public static MapiContact fromVCard(InputStream stream, Charset encoding)
```


Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream to read from |
| encoding | java.nio.charset.Charset | Stream data encoding |

**Returns:**
[MapiContact](../../com.aspose.email/mapicontact) - A read [MapiContact](../../com.aspose.email/mapicontact)
### fromVCard(String filePath) {#fromVCard-java.lang.String-}
```
public static MapiContact fromVCard(String filePath)
```


Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file name to read from |

**Returns:**
[MapiContact](../../com.aspose.email/mapicontact) - A read [MapiContact](../../com.aspose.email/mapicontact)
### fromVCard(String filePath, Charset encoding) {#fromVCard-java.lang.String-java.nio.charset.Charset-}
```
public static MapiContact fromVCard(String filePath, Charset encoding)
```


Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file name to read from |
| encoding | java.nio.charset.Charset | File data encoding |

**Returns:**
[MapiContact](../../com.aspose.email/mapicontact) - A read [MapiContact](../../com.aspose.email/mapicontact)
### getAttachments() {#getAttachments--}
```
public final MapiAttachmentCollection getAttachments()
```


Gets the attachments in the message.

Value: The attachment collection.

**Returns:**
[MapiAttachmentCollection](../../com.aspose.email/mapiattachmentcollection)
### getBilling() {#getBilling--}
```
public final String getBilling()
```


Contains the billing information associated with an item.

**Returns:**
java.lang.String
### getBody() {#getBody--}
```
public String getBody()
```


Gets the message text.

Value: The string that represents message body.

**Returns:**
java.lang.String
### getBodyHtml() {#getBodyHtml--}
```
public final String getBodyHtml()
```


Gets the  BodyRtf (\#getBodyRtf.getBodyRtf/\#setBodyRtf(String).setBodyRtf(String)) of the message converted to HTML, if present, otherwise an empty string.

**Returns:**
java.lang.String
### getBodyRtf() {#getBodyRtf--}
```
public final String getBodyRtf()
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Returns:**
java.lang.String
### getBodyType() {#getBodyType--}
```
public final int getBodyType()
```


Gets the type of the body.

Value: The type of the body.

**Returns:**
int
### getCategories() {#getCategories--}
```
public final String[] getCategories()
```


Contains keywords or categories for the message object.

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


Gets the code page.

Value: The code page.

**Returns:**
int
### getCompanies() {#getCompanies--}
```
public final String[] getCompanies()
```


Contains the names of the companies that are associated with an item.

**Returns:**
java.lang.String[]
### getElectronicAddresses() {#getElectronicAddresses--}
```
public final MapiContactElectronicAddressPropertySet getElectronicAddresses()
```


Specify properties for up to three different e-mail addresses and three different fax addresses

**Returns:**
[MapiContactElectronicAddressPropertySet](../../com.aspose.email/mapicontactelectronicaddresspropertyset)
### getEvents() {#getEvents--}
```
public final MapiContactEventPropertySet getEvents()
```


Specify events associated with a contact

**Returns:**
[MapiContactEventPropertySet](../../com.aspose.email/mapicontacteventpropertyset)
### getItemId() {#getItemId--}
```
public final String getItemId()
```


Uses to specify the server id of the contact EWS only

**Returns:**
java.lang.String
### getMessageClass() {#getMessageClass--}
```
public final String getMessageClass()
```


Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message.

Value: The string that represents message class.

**Returns:**
java.lang.String
### getMileage() {#getMileage--}
```
public final String getMileage()
```


Contains the mileage information that is associated with an item.

**Returns:**
java.lang.String
### getNameInfo() {#getNameInfo--}
```
public final MapiContactNamePropertySet getNameInfo()
```


The properties are used to specify the name of the person represented by the contact

**Returns:**
[MapiContactNamePropertySet](../../com.aspose.email/mapicontactnamepropertyset)
### getNamedProperties() {#getNamedProperties--}
```
public final MapiPropertyCollection getNamedProperties()
```


Gets the named properties of message.

Value: The collection of named properties.

**Returns:**
[MapiPropertyCollection](../../com.aspose.email/mapipropertycollection)
### getNamedPropertyMapping() {#getNamedPropertyMapping--}
```
public final MapiNamedPropertyMappingStorage getNamedPropertyMapping()
```


Gets the named property mapping.

Value: The named property mapping.

**Returns:**
[MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage)
### getOtherFields() {#getOtherFields--}
```
public final MapiContactOtherPropertySet getOtherFields()
```


Specify other fields of conhtact.

**Returns:**
[MapiContactOtherPropertySet](../../com.aspose.email/mapicontactotherpropertyset)
### getPersonalInfo() {#getPersonalInfo--}
```
public final MapiContactPersonalInfoPropertySet getPersonalInfo()
```


Specify other additional contact information

**Returns:**
[MapiContactPersonalInfoPropertySet](../../com.aspose.email/mapicontactpersonalinfopropertyset)
### getPhoto() {#getPhoto--}
```
public final MapiContactPhoto getPhoto()
```


Contains contact photo[MapiContactPhoto](../../com.aspose.email/mapicontactphoto).

**Returns:**
[MapiContactPhoto](../../com.aspose.email/mapicontactphoto)
### getPhysicalAddresses() {#getPhysicalAddresses--}
```
public final MapiContactPhysicalAddressPropertySet getPhysicalAddresses()
```


Specify three physical addresses: Home Address, Work Address, and Other Address. One of the addresses can be marked as the Mailing Address

**Returns:**
[MapiContactPhysicalAddressPropertySet](../../com.aspose.email/mapicontactphysicaladdresspropertyset)
### getProfessionalInfo() {#getProfessionalInfo--}
```
public final MapiContactProfessionalPropertySet getProfessionalInfo()
```


Properties are used to store professional details for the person represented by the contact

**Returns:**
[MapiContactProfessionalPropertySet](../../com.aspose.email/mapicontactprofessionalpropertyset)
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
### getRecipients() {#getRecipients--}
```
public final MapiRecipientCollection getRecipients()
```


Gets the recipients of the message.

Value: The collection of recipients.

**Returns:**
[MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection)
### getSensitivity() {#getSensitivity--}
```
public final int getSensitivity()
```


Gets the Sensitivity.

Value: The sensitivity.

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
### getSubject() {#getSubject--}
```
public final String getSubject()
```


Gets or sets the subject of the message.

Value: The string that represents message subject.

--------------------

When setting a value, the values of SubjectPrefix(PR\_SUBJECT\_PREFIX) and NormalizedSubject(PR\_NORMALIZED\_SUBJECT) properties are updated as well. If Subject has no prefix, the value of SubjectPrefix property is set null. When setting a null value or empty string, the values of Subject, SubjectPrefix, NormalizedSubject properties are set null.

**Returns:**
java.lang.String
### getSubjectPrefix() {#getSubjectPrefix--}
```
public final String getSubjectPrefix()
```


Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding.

Value: The string that represents subject prefix.

**Returns:**
java.lang.String
### getSupportedType() {#getSupportedType--}
```
public final int getSupportedType()
```


Gets the supported item type.

Value: The [MapiItemType](../../com.aspose.email/mapiitemtype).

**Returns:**
int
### getTelephones() {#getTelephones--}
```
public final MapiContactTelephonePropertySet getTelephones()
```


Specify telephone numbers for the contact

**Returns:**
[MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset)
### getUnderlyingMessage() {#getUnderlyingMessage--}
```
public final MapiMessage getUnderlyingMessage()
```


Retrieves the underlying MapiMessage object.

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




### removeProperty(long tag) {#removeProperty-long-}
```
public final void removeProperty(long tag)
```


Provides correctly removing property from all collections.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tag | long | The tag of MapiProperty. |

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves this [MapiContact](../../com.aspose.email/mapicontact) into the given stream with vCard format. The supported vCard version is 2.1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |

### save(OutputStream stream, ContactSaveOptions saveOptions) {#save-java.io.OutputStream-com.aspose.email.ContactSaveOptions-}
```
public final void save(OutputStream stream, ContactSaveOptions saveOptions)
```


Saves this [MapiContact](../../com.aspose.email/mapicontact) to the given stream using specified save options. The supported save options is [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |
| saveOptions | [ContactSaveOptions](../../com.aspose.email/contactsaveoptions) | A save options |

### save(OutputStream stream, int saveFormat) {#save-java.io.OutputStream-int-}
```
public final void save(OutputStream stream, int saveFormat)
```


Saves this [MapiContact](../../com.aspose.email/mapicontact) to the given stream with a format using the default options. The supported save format is vCard

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |
| saveFormat | int | A save format |

### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Saves this [MapiContact](../../com.aspose.email/mapicontact) to the vCard file with a default options. The supported vCard version is 2.1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A vCard file name |

### save(String filePath, ContactSaveOptions saveOptions) {#save-java.lang.String-com.aspose.email.ContactSaveOptions-}
```
public final void save(String filePath, ContactSaveOptions saveOptions)
```


Saves this [MapiContact](../../com.aspose.email/mapicontact) into file using specified save options. The supported save options is [VCardSaveOptions](../../com.aspose.email/vcardsaveoptions)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A vCard file name |
| saveOptions | [ContactSaveOptions](../../com.aspose.email/contactsaveoptions) | A save options |

### save(String filePath, int saveFormat) {#save-java.lang.String-int-}
```
public final void save(String filePath, int saveFormat)
```


Saves this [MapiContact](../../com.aspose.email/mapicontact) to the specified file with a format using the default options. The supported save format is vCard.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A vCard file name |
| saveFormat | int | A save format |

### setBilling(String value) {#setBilling-java.lang.String-}
```
public final void setBilling(String value)
```


Contains the billing information associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBody(String value) {#setBody-java.lang.String-}
```
public void setBody(String value)
```


Gets the message text.

Value: The string that represents message body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyContent(String content, int contentType) {#setBodyContent-java.lang.String-int-}
```
public void setBodyContent(String content, int contentType)
```


Sets the content of the body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content. |
| contentType | int | Type of the content.

--------------------

It is provided for setting of the content of the body message in RTF, HTML or Plain Text formats. When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated as well. Note, after the value in HTML format is set, BodyRtf property returns the value which is encoded within RTF. |

### setBodyContent(String content, int contentType, boolean compression) {#setBodyContent-java.lang.String-int-boolean-}
```
public void setBodyContent(String content, int contentType, boolean compression)
```


Sets the content of the body.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| content | java.lang.String | The content. |
| contentType | int | Type of the content. |
| compression | boolean | Specify that the content should be compressed.

--------------------

It is provided for setting of the content of the body message in RTF, HTML or Plain Text formats. When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated as well. Note, after the value in HTML format is set, BodyRtf property returns the value which is encoded within RTF. |

### setBodyRtf(String value) {#setBodyRtf-java.lang.String-}
```
public final void setBodyRtf(String value)
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setBodyRtf(String value, boolean compression) {#setBodyRtf-java.lang.String-boolean-}
```
public final void setBodyRtf(String value, boolean compression)
```


Gets or sets the RTF formatted message text.

Value: The string that represents message body rtf.

--------------------

When setting a value, the values of PR\_RTF\_COMPRESSED, PR\_RTF\_DECOMPRESSES, PR\_BODY properties are updated. A string value being set must have RTF format. Thus, if it is necessary to set a value in HTML format, the value must be first to encoded within RTF, according to RTF Extensions Specification. To set the content of the body message in HTML or Plain Text formats quickly, please, use SetBodyContent method. When setting a null value or empty string, the values of BodyRtf and Body properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
| compression | boolean | Specify that the content should be compressed. |

### setCategories(String[] value) {#setCategories-java.lang.String---}
```
public final void setCategories(String[] value)
```


Contains keywords or categories for the message object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setCompanies(String[] value) {#setCompanies-java.lang.String---}
```
public final void setCompanies(String[] value)
```


Contains the names of the companies that are associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String[] |  |

### setElectronicAddresses(MapiContactElectronicAddressPropertySet value) {#setElectronicAddresses-com.aspose.email.MapiContactElectronicAddressPropertySet-}
```
public final void setElectronicAddresses(MapiContactElectronicAddressPropertySet value)
```


Specify properties for up to three different e-mail addresses and three different fax addresses

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactElectronicAddressPropertySet](../../com.aspose.email/mapicontactelectronicaddresspropertyset) |  |

### setEvents(MapiContactEventPropertySet value) {#setEvents-com.aspose.email.MapiContactEventPropertySet-}
```
public final void setEvents(MapiContactEventPropertySet value)
```


Specify events associated with a contact

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactEventPropertySet](../../com.aspose.email/mapicontacteventpropertyset) |  |

### setMessageClass(String value) {#setMessageClass-java.lang.String-}
```
public final void setMessageClass(String value)
```


Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message.

Value: The string that represents message class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setMessageFlags(long flags) {#setMessageFlags-long-}
```
public final void setMessageFlags(long flags)
```


Sets the message flags.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| flags | long | The message flags. |

### setMileage(String value) {#setMileage-java.lang.String-}
```
public final void setMileage(String value)
```


Contains the mileage information that is associated with an item.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setNameInfo(MapiContactNamePropertySet value) {#setNameInfo-com.aspose.email.MapiContactNamePropertySet-}
```
public final void setNameInfo(MapiContactNamePropertySet value)
```


The properties are used to specify the name of the person represented by the contact

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactNamePropertySet](../../com.aspose.email/mapicontactnamepropertyset) |  |

### setNamedPropertyMapping(MapiNamedPropertyMappingStorage value) {#setNamedPropertyMapping-com.aspose.email.MapiNamedPropertyMappingStorage-}
```
public final void setNamedPropertyMapping(MapiNamedPropertyMappingStorage value)
```


Sets the named property mapping.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiNamedPropertyMappingStorage](../../com.aspose.email/mapinamedpropertymappingstorage) | The MapiNamedPropertyMappingStorage. |

### setOtherFields(MapiContactOtherPropertySet value) {#setOtherFields-com.aspose.email.MapiContactOtherPropertySet-}
```
public final void setOtherFields(MapiContactOtherPropertySet value)
```


Specify other fields of conhtact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactOtherPropertySet](../../com.aspose.email/mapicontactotherpropertyset) |  |

### setPersonalInfo(MapiContactPersonalInfoPropertySet value) {#setPersonalInfo-com.aspose.email.MapiContactPersonalInfoPropertySet-}
```
public final void setPersonalInfo(MapiContactPersonalInfoPropertySet value)
```


Specify other additional contact information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactPersonalInfoPropertySet](../../com.aspose.email/mapicontactpersonalinfopropertyset) |  |

### setPhoto(MapiContactPhoto value) {#setPhoto-com.aspose.email.MapiContactPhoto-}
```
public final void setPhoto(MapiContactPhoto value)
```


Contains contact photo[MapiContactPhoto](../../com.aspose.email/mapicontactphoto).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactPhoto](../../com.aspose.email/mapicontactphoto) |  |

### setPhysicalAddresses(MapiContactPhysicalAddressPropertySet value) {#setPhysicalAddresses-com.aspose.email.MapiContactPhysicalAddressPropertySet-}
```
public final void setPhysicalAddresses(MapiContactPhysicalAddressPropertySet value)
```


Specify three physical addresses: Home Address, Work Address, and Other Address. One of the addresses can be marked as the Mailing Address

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactPhysicalAddressPropertySet](../../com.aspose.email/mapicontactphysicaladdresspropertyset) |  |

### setProfessionalInfo(MapiContactProfessionalPropertySet value) {#setProfessionalInfo-com.aspose.email.MapiContactProfessionalPropertySet-}
```
public final void setProfessionalInfo(MapiContactProfessionalPropertySet value)
```


Properties are used to store professional details for the person represented by the contact

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactProfessionalPropertySet](../../com.aspose.email/mapicontactprofessionalpropertyset) |  |

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

### setRecipients(MapiRecipientCollection value) {#setRecipients-com.aspose.email.MapiRecipientCollection-}
```
public final void setRecipients(MapiRecipientCollection value)
```


Gets the recipients of the message.

Value: The collection of recipients.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiRecipientCollection](../../com.aspose.email/mapirecipientcollection) |  |

### setSensitivity(int value) {#setSensitivity-int-}
```
public final void setSensitivity(int value)
```


Gets the Sensitivity.

Value: The sensitivity.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Gets or sets the subject of the message.

Value: The string that represents message subject.

--------------------

When setting a value, the values of SubjectPrefix(PR\_SUBJECT\_PREFIX) and NormalizedSubject(PR\_NORMALIZED\_SUBJECT) properties are updated as well. If Subject has no prefix, the value of SubjectPrefix property is set null. When setting a null value or empty string, the values of Subject, SubjectPrefix, NormalizedSubject properties are set null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setTelephones(MapiContactTelephonePropertySet value) {#setTelephones-com.aspose.email.MapiContactTelephonePropertySet-}
```
public final void setTelephones(MapiContactTelephonePropertySet value)
```


Specify telephone numbers for the contact

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset) |  |

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

