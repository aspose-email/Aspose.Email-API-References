---
title: VCardContact
second_title: Aspose.Email for Java API Reference
description:  Represents a vCard contact
type: docs
weight: 691
url: /java/com.aspose.email/vcardcontact/
---
**Inheritance:**
java.lang.Object
```
public final class VCardContact
```

Represents a vCard contact
## Constructors

| Constructor | Description |
| --- | --- |
| [VCardContact()](#VCardContact--) | Initializes a new instance of the [VCardContact](../../com.aspose.email/vcardcontact) class |
## Methods

| Method | Description |
| --- | --- |
| [getIdentificationInfo()](#getIdentificationInfo--) | Gets or sets an identification properties |
| [setIdentificationInfo(VCardIdentificationInfo value)](#setIdentificationInfo-com.aspose.email.VCardIdentificationInfo-) | Gets or sets an identification properties |
| [getDeliveryAddresses()](#getDeliveryAddresses--) | Gets or sets a delivery addresses |
| [setDeliveryAddresses(VCardDeliveryAddressCollection value)](#setDeliveryAddresses-com.aspose.email.VCardDeliveryAddressCollection-) | Gets or sets a delivery addresses |
| [getLabels()](#getLabels--) | Gets or sets a delivery addresses |
| [setLabels(VCardLabelCollection value)](#setLabels-com.aspose.email.VCardLabelCollection-) | Gets or sets a delivery addresses |
| [getTelephoneNumbers()](#getTelephoneNumbers--) | Gets or sets a contact's telephone numbers |
| [setTelephoneNumbers(VCardTelephoneNumberCollection value)](#setTelephoneNumbers-com.aspose.email.VCardTelephoneNumberCollection-) | Gets or sets a contact's telephone numbers |
| [getEmails()](#getEmails--) | Gets or sets a contact's email addresses |
| [setEmails(VCardEmailCollection value)](#setEmails-com.aspose.email.VCardEmailCollection-) | Gets or sets a contact's email addresses |
| [getMailer()](#getMailer--) | Gets or sets a mailer |
| [setMailer(String value)](#setMailer-java.lang.String-) | Gets or sets a mailer |
| [getTimeZone()](#getTimeZone--) | Gets or sets a timeZone |
| [setTimeZone(String value)](#setTimeZone-java.lang.String-) | Gets or sets a timeZone |
| [getGeo()](#getGeo--) | Gets or sets a global positioning |
| [setGeo(VCardGeo value)](#setGeo-com.aspose.email.VCardGeo-) | Gets or sets a global positioning |
| [getOrganization()](#getOrganization--) | Gets or sets an organization information |
| [setOrganization(VCardOrganization value)](#setOrganization-com.aspose.email.VCardOrganization-) | Gets or sets an organization information |
| [getExplanatoryInfo()](#getExplanatoryInfo--) | Gets or sets a vCard explanatory information |
| [setExplanatoryInfo(VCardExplanatoryInfo value)](#setExplanatoryInfo-com.aspose.email.VCardExplanatoryInfo-) | Gets or sets a vCard explanatory information |
| [getSecurity()](#getSecurity--) | Gets or sets a security properites |
| [setSecurity(VCardSecurity value)](#setSecurity-com.aspose.email.VCardSecurity-) | Gets or sets a security properites |
| [getExtendedProperties()](#getExtendedProperties--) | Gets or sets an extended properties |
| [setExtendedProperties(System.Collections.Specialized.StringCollection value)](#setExtendedProperties-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets an extended properties |
| [load(String filePath)](#load-java.lang.String-) | Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| [load(String filePath, Charset encoding)](#load-java.lang.String-java.nio.charset.Charset-) | Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| [load(InputStream stream)](#load-java.io.InputStream-) | Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified stream containing vCard. |
| [load(InputStream stream, Charset encoding)](#load-java.io.InputStream-java.nio.charset.Charset-) | Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified stream containing vCard. |
| [isMultiContacts(InputStream stream)](#isMultiContacts-java.io.InputStream-) | Checks whether source stream contains multi contacts. |
| [loadAsMultiple(InputStream stream, Charset encoding)](#loadAsMultiple-java.io.InputStream-java.nio.charset.Charset-) | Loads list of contacts from multi contact stream. |
| [loadAsMultiple(String filePath, Charset encoding)](#loadAsMultiple-java.lang.String-java.nio.charset.Charset-) | Loads list of contacts from multi contact file. |
| [save(String filePath)](#save-java.lang.String-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the vCard file with a default options. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the specified file with a format using the default options. |
| [save(String filePath, ContactSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.ContactSaveOptions-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) into file using specified save options. |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) into the given stream with vCard format. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the given stream with a format using the default options. |
| [save(OutputStream stream, ContactSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.ContactSaveOptions-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the given stream using specified save options. |
### VCardContact() {#VCardContact--}
```
public VCardContact()
```


Initializes a new instance of the [VCardContact](../../com.aspose.email/vcardcontact) class

### getIdentificationInfo() {#getIdentificationInfo--}
```
public final VCardIdentificationInfo getIdentificationInfo()
```


Gets or sets an identification properties

**Returns:**
[VCardIdentificationInfo](../../com.aspose.email/vcardidentificationinfo)
### setIdentificationInfo(VCardIdentificationInfo value) {#setIdentificationInfo-com.aspose.email.VCardIdentificationInfo-}
```
public final void setIdentificationInfo(VCardIdentificationInfo value)
```


Gets or sets an identification properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardIdentificationInfo](../../com.aspose.email/vcardidentificationinfo) |  |

### getDeliveryAddresses() {#getDeliveryAddresses--}
```
public final VCardDeliveryAddressCollection getDeliveryAddresses()
```


Gets or sets a delivery addresses

**Returns:**
[VCardDeliveryAddressCollection](../../com.aspose.email/vcarddeliveryaddresscollection)
### setDeliveryAddresses(VCardDeliveryAddressCollection value) {#setDeliveryAddresses-com.aspose.email.VCardDeliveryAddressCollection-}
```
public final void setDeliveryAddresses(VCardDeliveryAddressCollection value)
```


Gets or sets a delivery addresses

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardDeliveryAddressCollection](../../com.aspose.email/vcarddeliveryaddresscollection) |  |

### getLabels() {#getLabels--}
```
public final VCardLabelCollection getLabels()
```


Gets or sets a delivery addresses

**Returns:**
[VCardLabelCollection](../../com.aspose.email/vcardlabelcollection)
### setLabels(VCardLabelCollection value) {#setLabels-com.aspose.email.VCardLabelCollection-}
```
public final void setLabels(VCardLabelCollection value)
```


Gets or sets a delivery addresses

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardLabelCollection](../../com.aspose.email/vcardlabelcollection) |  |

### getTelephoneNumbers() {#getTelephoneNumbers--}
```
public final VCardTelephoneNumberCollection getTelephoneNumbers()
```


Gets or sets a contact's telephone numbers

**Returns:**
[VCardTelephoneNumberCollection](../../com.aspose.email/vcardtelephonenumbercollection)
### setTelephoneNumbers(VCardTelephoneNumberCollection value) {#setTelephoneNumbers-com.aspose.email.VCardTelephoneNumberCollection-}
```
public final void setTelephoneNumbers(VCardTelephoneNumberCollection value)
```


Gets or sets a contact's telephone numbers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardTelephoneNumberCollection](../../com.aspose.email/vcardtelephonenumbercollection) |  |

### getEmails() {#getEmails--}
```
public final VCardEmailCollection getEmails()
```


Gets or sets a contact's email addresses

**Returns:**
[VCardEmailCollection](../../com.aspose.email/vcardemailcollection)
### setEmails(VCardEmailCollection value) {#setEmails-com.aspose.email.VCardEmailCollection-}
```
public final void setEmails(VCardEmailCollection value)
```


Gets or sets a contact's email addresses

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardEmailCollection](../../com.aspose.email/vcardemailcollection) |  |

### getMailer() {#getMailer--}
```
public final String getMailer()
```


Gets or sets a mailer

**Returns:**
java.lang.String
### setMailer(String value) {#setMailer-java.lang.String-}
```
public final void setMailer(String value)
```


Gets or sets a mailer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTimeZone() {#getTimeZone--}
```
public final String getTimeZone()
```


Gets or sets a timeZone

**Returns:**
java.lang.String
### setTimeZone(String value) {#setTimeZone-java.lang.String-}
```
public final void setTimeZone(String value)
```


Gets or sets a timeZone

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getGeo() {#getGeo--}
```
public final VCardGeo getGeo()
```


Gets or sets a global positioning

**Returns:**
[VCardGeo](../../com.aspose.email/vcardgeo)
### setGeo(VCardGeo value) {#setGeo-com.aspose.email.VCardGeo-}
```
public final void setGeo(VCardGeo value)
```


Gets or sets a global positioning

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardGeo](../../com.aspose.email/vcardgeo) |  |

### getOrganization() {#getOrganization--}
```
public final VCardOrganization getOrganization()
```


Gets or sets an organization information

**Returns:**
[VCardOrganization](../../com.aspose.email/vcardorganization)
### setOrganization(VCardOrganization value) {#setOrganization-com.aspose.email.VCardOrganization-}
```
public final void setOrganization(VCardOrganization value)
```


Gets or sets an organization information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardOrganization](../../com.aspose.email/vcardorganization) |  |

### getExplanatoryInfo() {#getExplanatoryInfo--}
```
public final VCardExplanatoryInfo getExplanatoryInfo()
```


Gets or sets a vCard explanatory information

**Returns:**
[VCardExplanatoryInfo](../../com.aspose.email/vcardexplanatoryinfo)
### setExplanatoryInfo(VCardExplanatoryInfo value) {#setExplanatoryInfo-com.aspose.email.VCardExplanatoryInfo-}
```
public final void setExplanatoryInfo(VCardExplanatoryInfo value)
```


Gets or sets a vCard explanatory information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardExplanatoryInfo](../../com.aspose.email/vcardexplanatoryinfo) |  |

### getSecurity() {#getSecurity--}
```
public final VCardSecurity getSecurity()
```


Gets or sets a security properites

**Returns:**
[VCardSecurity](../../com.aspose.email/vcardsecurity)
### setSecurity(VCardSecurity value) {#setSecurity-com.aspose.email.VCardSecurity-}
```
public final void setSecurity(VCardSecurity value)
```


Gets or sets a security properites

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardSecurity](../../com.aspose.email/vcardsecurity) |  |

### getExtendedProperties() {#getExtendedProperties--}
```
public final System.Collections.Specialized.StringCollection getExtendedProperties()
```


Gets or sets an extended properties

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### setExtendedProperties(System.Collections.Specialized.StringCollection value) {#setExtendedProperties-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setExtendedProperties(System.Collections.Specialized.StringCollection value)
```


Gets or sets an extended properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### load(String filePath) {#load-java.lang.String-}
```
public static VCardContact load(String filePath)
```


Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file name to read from |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### load(String filePath, Charset encoding) {#load-java.lang.String-java.nio.charset.Charset-}
```
public static VCardContact load(String filePath, Charset encoding)
```


Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | A file name to read from |
| encoding | java.nio.charset.Charset | File encoding |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### load(InputStream stream) {#load-java.io.InputStream-}
```
public static VCardContact load(InputStream stream)
```


Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream to read from |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### load(InputStream stream, Charset encoding) {#load-java.io.InputStream-java.nio.charset.Charset-}
```
public static VCardContact load(InputStream stream, Charset encoding)
```


Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | A stream to read from |
| encoding | java.nio.charset.Charset | Stream data encoding |

**Returns:**
[VCardContact](../../com.aspose.email/vcardcontact) - A read [VCardContact](../../com.aspose.email/vcardcontact)
### isMultiContacts(InputStream stream) {#isMultiContacts-java.io.InputStream-}
```
public static boolean isMultiContacts(InputStream stream)
```


Checks whether source stream contains multi contacts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source stream |

**Returns:**
boolean - True if multi contacts, otherwise false.
### loadAsMultiple(InputStream stream, Charset encoding) {#loadAsMultiple-java.io.InputStream-java.nio.charset.Charset-}
```
public static List<VCardContact> loadAsMultiple(InputStream stream, Charset encoding)
```


Loads list of contacts from multi contact stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source stream |
| encoding | java.nio.charset.Charset | Stream data encoding,if null then UTF8 will be used. |

**Returns:**
java.util.List<com.aspose.email.VCardContact> - List of contacs
### loadAsMultiple(String filePath, Charset encoding) {#loadAsMultiple-java.lang.String-java.nio.charset.Charset-}
```
public static List<VCardContact> loadAsMultiple(String filePath, Charset encoding)
```


Loads list of contacts from multi contact file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Source file |
| encoding | java.nio.charset.Charset | File data encoding,if null then UTF8 will be used. |

**Returns:**
java.util.List<com.aspose.email.VCardContact> - 
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

