---
title: MapiContact
second_title: Aspose.Email for Android via Java API Reference
description:  Represents outlook contact information
type: docs
weight: 229
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
| [getItemId()](#getItemId--) | Uses to specify the server id of the contact EWS only |
| [getNameInfo()](#getNameInfo--) | The properties are used to specify the name of the person represented by the contact |
| [setNameInfo(MapiContactNamePropertySet value)](#setNameInfo-com.aspose.email.MapiContactNamePropertySet-) | The properties are used to specify the name of the person represented by the contact |
| [getPersonalInfo()](#getPersonalInfo--) | Specify other additional contact information |
| [setPersonalInfo(MapiContactPersonalInfoPropertySet value)](#setPersonalInfo-com.aspose.email.MapiContactPersonalInfoPropertySet-) | Specify other additional contact information |
| [getProfessionalInfo()](#getProfessionalInfo--) | Properties are used to store professional details for the person represented by the contact |
| [setProfessionalInfo(MapiContactProfessionalPropertySet value)](#setProfessionalInfo-com.aspose.email.MapiContactProfessionalPropertySet-) | Properties are used to store professional details for the person represented by the contact |
| [getTelephones()](#getTelephones--) | Specify telephone numbers for the contact |
| [setTelephones(MapiContactTelephonePropertySet value)](#setTelephones-com.aspose.email.MapiContactTelephonePropertySet-) | Specify telephone numbers for the contact |
| [getElectronicAddresses()](#getElectronicAddresses--) | Specify properties for up to three different e-mail addresses and three different fax addresses |
| [setElectronicAddresses(MapiContactElectronicAddressPropertySet value)](#setElectronicAddresses-com.aspose.email.MapiContactElectronicAddressPropertySet-) | Specify properties for up to three different e-mail addresses and three different fax addresses |
| [getPhysicalAddresses()](#getPhysicalAddresses--) | Specify three physical addresses: Home Address, Work Address, and Other Address. |
| [setPhysicalAddresses(MapiContactPhysicalAddressPropertySet value)](#setPhysicalAddresses-com.aspose.email.MapiContactPhysicalAddressPropertySet-) | Specify three physical addresses: Home Address, Work Address, and Other Address. |
| [getEvents()](#getEvents--) | Specify events associated with a contact |
| [setEvents(MapiContactEventPropertySet value)](#setEvents-com.aspose.email.MapiContactEventPropertySet-) | Specify events associated with a contact |
| [getOtherFields()](#getOtherFields--) | Specify other fields of conhtact. |
| [setOtherFields(MapiContactOtherPropertySet value)](#setOtherFields-com.aspose.email.MapiContactOtherPropertySet-) | Specify other fields of conhtact. |
| [getPhoto()](#getPhoto--) | Contains contact photo[MapiContactPhoto](../../com.aspose.email/mapicontactphoto). |
| [setPhoto(MapiContactPhoto value)](#setPhoto-com.aspose.email.MapiContactPhoto-) | Contains contact photo[MapiContactPhoto](../../com.aspose.email/mapicontactphoto). |
| [fromVCard(String filePath)](#fromVCard-java.lang.String-) | Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| [fromVCard(String filePath, Charset encoding)](#fromVCard-java.lang.String-java.nio.charset.Charset-) | Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| [fromVCard(InputStream stream)](#fromVCard-java.io.InputStream-) | Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified stream containing vCard. |
| [fromVCard(InputStream stream, Charset encoding)](#fromVCard-java.io.InputStream-java.nio.charset.Charset-) | Reads [MapiContact](../../com.aspose.email/mapicontact) from the specified stream containing vCard. |
| [getUnderlyingMessage()](#getUnderlyingMessage--) | Get the MapiMessage that represent contact. |
| [save(String filePath)](#save-java.lang.String-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the vCard file with a default options. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the specified file with a format using the default options. |
| [save(String filePath, ContactSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.ContactSaveOptions-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) into file using specified save options. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) into the given stream with vCard format. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the given stream with a format using the default options. |
| [save(OutputStream stream, ContactSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.ContactSaveOptions-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the given stream using specified save options. |
| [setBodyContent(String content, int contentType)](#setBodyContent-java.lang.String-int-) | Sets the content of the body. |
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

### getItemId() {#getItemId--}
```
public final String getItemId()
```


Uses to specify the server id of the contact EWS only

**Returns:**
java.lang.String
### getNameInfo() {#getNameInfo--}
```
public final MapiContactNamePropertySet getNameInfo()
```


The properties are used to specify the name of the person represented by the contact

**Returns:**
[MapiContactNamePropertySet](../../com.aspose.email/mapicontactnamepropertyset)
### setNameInfo(MapiContactNamePropertySet value) {#setNameInfo-com.aspose.email.MapiContactNamePropertySet-}
```
public final void setNameInfo(MapiContactNamePropertySet value)
```


The properties are used to specify the name of the person represented by the contact

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactNamePropertySet](../../com.aspose.email/mapicontactnamepropertyset) |  |

### getPersonalInfo() {#getPersonalInfo--}
```
public final MapiContactPersonalInfoPropertySet getPersonalInfo()
```


Specify other additional contact information

**Returns:**
[MapiContactPersonalInfoPropertySet](../../com.aspose.email/mapicontactpersonalinfopropertyset)
### setPersonalInfo(MapiContactPersonalInfoPropertySet value) {#setPersonalInfo-com.aspose.email.MapiContactPersonalInfoPropertySet-}
```
public final void setPersonalInfo(MapiContactPersonalInfoPropertySet value)
```


Specify other additional contact information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactPersonalInfoPropertySet](../../com.aspose.email/mapicontactpersonalinfopropertyset) |  |

### getProfessionalInfo() {#getProfessionalInfo--}
```
public final MapiContactProfessionalPropertySet getProfessionalInfo()
```


Properties are used to store professional details for the person represented by the contact

**Returns:**
[MapiContactProfessionalPropertySet](../../com.aspose.email/mapicontactprofessionalpropertyset)
### setProfessionalInfo(MapiContactProfessionalPropertySet value) {#setProfessionalInfo-com.aspose.email.MapiContactProfessionalPropertySet-}
```
public final void setProfessionalInfo(MapiContactProfessionalPropertySet value)
```


Properties are used to store professional details for the person represented by the contact

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactProfessionalPropertySet](../../com.aspose.email/mapicontactprofessionalpropertyset) |  |

### getTelephones() {#getTelephones--}
```
public final MapiContactTelephonePropertySet getTelephones()
```


Specify telephone numbers for the contact

**Returns:**
[MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset)
### setTelephones(MapiContactTelephonePropertySet value) {#setTelephones-com.aspose.email.MapiContactTelephonePropertySet-}
```
public final void setTelephones(MapiContactTelephonePropertySet value)
```


Specify telephone numbers for the contact

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactTelephonePropertySet](../../com.aspose.email/mapicontacttelephonepropertyset) |  |

### getElectronicAddresses() {#getElectronicAddresses--}
```
public final MapiContactElectronicAddressPropertySet getElectronicAddresses()
```


Specify properties for up to three different e-mail addresses and three different fax addresses

**Returns:**
[MapiContactElectronicAddressPropertySet](../../com.aspose.email/mapicontactelectronicaddresspropertyset)
### setElectronicAddresses(MapiContactElectronicAddressPropertySet value) {#setElectronicAddresses-com.aspose.email.MapiContactElectronicAddressPropertySet-}
```
public final void setElectronicAddresses(MapiContactElectronicAddressPropertySet value)
```


Specify properties for up to three different e-mail addresses and three different fax addresses

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactElectronicAddressPropertySet](../../com.aspose.email/mapicontactelectronicaddresspropertyset) |  |

### getPhysicalAddresses() {#getPhysicalAddresses--}
```
public final MapiContactPhysicalAddressPropertySet getPhysicalAddresses()
```


Specify three physical addresses: Home Address, Work Address, and Other Address. One of the addresses can be marked as the Mailing Address

**Returns:**
[MapiContactPhysicalAddressPropertySet](../../com.aspose.email/mapicontactphysicaladdresspropertyset)
### setPhysicalAddresses(MapiContactPhysicalAddressPropertySet value) {#setPhysicalAddresses-com.aspose.email.MapiContactPhysicalAddressPropertySet-}
```
public final void setPhysicalAddresses(MapiContactPhysicalAddressPropertySet value)
```


Specify three physical addresses: Home Address, Work Address, and Other Address. One of the addresses can be marked as the Mailing Address

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactPhysicalAddressPropertySet](../../com.aspose.email/mapicontactphysicaladdresspropertyset) |  |

### getEvents() {#getEvents--}
```
public final MapiContactEventPropertySet getEvents()
```


Specify events associated with a contact

**Returns:**
[MapiContactEventPropertySet](../../com.aspose.email/mapicontacteventpropertyset)
### setEvents(MapiContactEventPropertySet value) {#setEvents-com.aspose.email.MapiContactEventPropertySet-}
```
public final void setEvents(MapiContactEventPropertySet value)
```


Specify events associated with a contact

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactEventPropertySet](../../com.aspose.email/mapicontacteventpropertyset) |  |

### getOtherFields() {#getOtherFields--}
```
public final MapiContactOtherPropertySet getOtherFields()
```


Specify other fields of conhtact.

**Returns:**
[MapiContactOtherPropertySet](../../com.aspose.email/mapicontactotherpropertyset)
### setOtherFields(MapiContactOtherPropertySet value) {#setOtherFields-com.aspose.email.MapiContactOtherPropertySet-}
```
public final void setOtherFields(MapiContactOtherPropertySet value)
```


Specify other fields of conhtact.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactOtherPropertySet](../../com.aspose.email/mapicontactotherpropertyset) |  |

### getPhoto() {#getPhoto--}
```
public final MapiContactPhoto getPhoto()
```


Contains contact photo[MapiContactPhoto](../../com.aspose.email/mapicontactphoto).

**Returns:**
[MapiContactPhoto](../../com.aspose.email/mapicontactphoto)
### setPhoto(MapiContactPhoto value) {#setPhoto-com.aspose.email.MapiContactPhoto-}
```
public final void setPhoto(MapiContactPhoto value)
```


Contains contact photo[MapiContactPhoto](../../com.aspose.email/mapicontactphoto).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [MapiContactPhoto](../../com.aspose.email/mapicontactphoto) |  |

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
### getUnderlyingMessage() {#getUnderlyingMessage--}
```
public final MapiMessage getUnderlyingMessage()
```


Get the MapiMessage that represent contact.

**Returns:**
[MapiMessage](../../com.aspose.email/mapimessage) - The [MapiMessage](../../com.aspose.email/mapimessage) object.
### save(String filePath) {#save-java.lang.String-}
```
public final void save(String filePath)
```


Saves this [MapiContact](../../com.aspose.email/mapicontact) to the vCard file with a default options. The supported vCard version is 2.1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A vCard file name |

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

### save(OutputStream stream) {#save-java.io.OutputStream-}
```
public final void save(OutputStream stream)
```


Saves this [MapiContact](../../com.aspose.email/mapicontact) into the given stream with vCard format. The supported vCard version is 2.1

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | A stream to save to |

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

