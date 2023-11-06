---
title: VCardContact
second_title: Aspose.Email for Java API Reference
description: Represents a vCard contact
type: docs
weight: 706
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
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeliveryAddresses()](#getDeliveryAddresses--) | Gets or sets a delivery addresses |
| [getEmails()](#getEmails--) | Gets or sets a contact's email addresses |
| [getExplanatoryInfo()](#getExplanatoryInfo--) | Gets or sets a vCard explanatory information |
| [getExtendedProperties()](#getExtendedProperties--) | Gets or sets an extended properties |
| [getGeo()](#getGeo--) | Gets or sets a global positioning |
| [getIdentificationInfo()](#getIdentificationInfo--) | Gets or sets an identification properties |
| [getLabels()](#getLabels--) | Gets or sets a delivery addresses |
| [getMailer()](#getMailer--) | Gets or sets a mailer |
| [getOrganization()](#getOrganization--) | Gets or sets an organization information |
| [getSecurity()](#getSecurity--) | Gets or sets a security properites |
| [getTelephoneNumbers()](#getTelephoneNumbers--) | Gets or sets a contact's telephone numbers |
| [getTimeZone()](#getTimeZone--) | Gets or sets a timeZone |
| [hashCode()](#hashCode--) |  |
| [isMultiContacts(InputStream stream)](#isMultiContacts-java.io.InputStream-) | Checks whether source stream contains multi contacts. |
| [isMultiContacts(String filePath)](#isMultiContacts-java.lang.String-) | Checks whether source file contains multi contacts. |
| [load(InputStream stream)](#load-java.io.InputStream-) | Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified stream containing vCard. |
| [load(InputStream stream, Charset encoding)](#load-java.io.InputStream-java.nio.charset.Charset-) | Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified stream containing vCard. |
| [load(String filePath)](#load-java.lang.String-) | Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| [load(String filePath, Charset encoding)](#load-java.lang.String-java.nio.charset.Charset-) | Reads [VCardContact](../../com.aspose.email/vcardcontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| [loadAsMultiple(InputStream stream)](#loadAsMultiple-java.io.InputStream-) | Loads list of contacts from multi contact stream. |
| [loadAsMultiple(InputStream stream, Charset encoding)](#loadAsMultiple-java.io.InputStream-java.nio.charset.Charset-) | Loads list of contacts from multi contact stream. |
| [loadAsMultiple(String filePath)](#loadAsMultiple-java.lang.String-) | Loads list of contacts from multi contact file. |
| [loadAsMultiple(String filePath, Charset encoding)](#loadAsMultiple-java.lang.String-java.nio.charset.Charset-) | Loads list of contacts from multi contact file. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [save(OutputStream stream)](#save-java.io.OutputStream-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) into the given stream with vCard format. |
| [save(OutputStream stream, ContactSaveOptions saveOptions)](#save-java.io.OutputStream-com.aspose.email.ContactSaveOptions-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the given stream using specified save options. |
| [save(OutputStream stream, int saveFormat)](#save-java.io.OutputStream-int-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the given stream with a format using the default options. |
| [save(String filePath)](#save-java.lang.String-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the vCard file with a default options. |
| [save(String filePath, ContactSaveOptions saveOptions)](#save-java.lang.String-com.aspose.email.ContactSaveOptions-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) into file using specified save options. |
| [save(String filePath, int saveFormat)](#save-java.lang.String-int-) | Saves this [MapiContact](../../com.aspose.email/mapicontact) to the specified file with a format using the default options. |
| [setDeliveryAddresses(VCardDeliveryAddressCollection value)](#setDeliveryAddresses-com.aspose.email.VCardDeliveryAddressCollection-) | Gets or sets a delivery addresses |
| [setEmails(VCardEmailCollection value)](#setEmails-com.aspose.email.VCardEmailCollection-) | Gets or sets a contact's email addresses |
| [setExplanatoryInfo(VCardExplanatoryInfo value)](#setExplanatoryInfo-com.aspose.email.VCardExplanatoryInfo-) | Gets or sets a vCard explanatory information |
| [setExtendedProperties(System.Collections.Specialized.StringCollection value)](#setExtendedProperties-com.aspose.ms.System.Collections.Specialized.StringCollection-) | Gets or sets an extended properties |
| [setGeo(VCardGeo value)](#setGeo-com.aspose.email.VCardGeo-) | Gets or sets a global positioning |
| [setIdentificationInfo(VCardIdentificationInfo value)](#setIdentificationInfo-com.aspose.email.VCardIdentificationInfo-) | Gets or sets an identification properties |
| [setLabels(VCardLabelCollection value)](#setLabels-com.aspose.email.VCardLabelCollection-) | Gets or sets a delivery addresses |
| [setMailer(String value)](#setMailer-java.lang.String-) | Gets or sets a mailer |
| [setOrganization(VCardOrganization value)](#setOrganization-com.aspose.email.VCardOrganization-) | Gets or sets an organization information |
| [setSecurity(VCardSecurity value)](#setSecurity-com.aspose.email.VCardSecurity-) | Gets or sets a security properites |
| [setTelephoneNumbers(VCardTelephoneNumberCollection value)](#setTelephoneNumbers-com.aspose.email.VCardTelephoneNumberCollection-) | Gets or sets a contact's telephone numbers |
| [setTimeZone(String value)](#setTimeZone-java.lang.String-) | Gets or sets a timeZone |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### VCardContact() {#VCardContact--}
```
public VCardContact()
```


Initializes a new instance of the [VCardContact](../../com.aspose.email/vcardcontact) class

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
### getDeliveryAddresses() {#getDeliveryAddresses--}
```
public final VCardDeliveryAddressCollection getDeliveryAddresses()
```


Gets or sets a delivery addresses

**Returns:**
[VCardDeliveryAddressCollection](../../com.aspose.email/vcarddeliveryaddresscollection)
### getEmails() {#getEmails--}
```
public final VCardEmailCollection getEmails()
```


Gets or sets a contact's email addresses

**Returns:**
[VCardEmailCollection](../../com.aspose.email/vcardemailcollection)
### getExplanatoryInfo() {#getExplanatoryInfo--}
```
public final VCardExplanatoryInfo getExplanatoryInfo()
```


Gets or sets a vCard explanatory information

**Returns:**
[VCardExplanatoryInfo](../../com.aspose.email/vcardexplanatoryinfo)
### getExtendedProperties() {#getExtendedProperties--}
```
public final System.Collections.Specialized.StringCollection getExtendedProperties()
```


Gets or sets an extended properties

**Returns:**
com.aspose.ms.System.Collections.Specialized.StringCollection
### getGeo() {#getGeo--}
```
public final VCardGeo getGeo()
```


Gets or sets a global positioning

**Returns:**
[VCardGeo](../../com.aspose.email/vcardgeo)
### getIdentificationInfo() {#getIdentificationInfo--}
```
public final VCardIdentificationInfo getIdentificationInfo()
```


Gets or sets an identification properties

**Returns:**
[VCardIdentificationInfo](../../com.aspose.email/vcardidentificationinfo)
### getLabels() {#getLabels--}
```
public final VCardLabelCollection getLabels()
```


Gets or sets a delivery addresses

**Returns:**
[VCardLabelCollection](../../com.aspose.email/vcardlabelcollection)
### getMailer() {#getMailer--}
```
public final String getMailer()
```


Gets or sets a mailer

**Returns:**
java.lang.String
### getOrganization() {#getOrganization--}
```
public final VCardOrganization getOrganization()
```


Gets or sets an organization information

**Returns:**
[VCardOrganization](../../com.aspose.email/vcardorganization)
### getSecurity() {#getSecurity--}
```
public final VCardSecurity getSecurity()
```


Gets or sets a security properites

**Returns:**
[VCardSecurity](../../com.aspose.email/vcardsecurity)
### getTelephoneNumbers() {#getTelephoneNumbers--}
```
public final VCardTelephoneNumberCollection getTelephoneNumbers()
```


Gets or sets a contact's telephone numbers

**Returns:**
[VCardTelephoneNumberCollection](../../com.aspose.email/vcardtelephonenumbercollection)
### getTimeZone() {#getTimeZone--}
```
public final String getTimeZone()
```


Gets or sets a timeZone

**Returns:**
java.lang.String
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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
### isMultiContacts(String filePath) {#isMultiContacts-java.lang.String-}
```
public static boolean isMultiContacts(String filePath)
```


Checks whether source file contains multi contacts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Path to source file |

**Returns:**
boolean - True if multi contacts, otherwise false.
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
### loadAsMultiple(InputStream stream) {#loadAsMultiple-java.io.InputStream-}
```
public static List<VCardContact> loadAsMultiple(InputStream stream)
```


Loads list of contacts from multi contact stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Source stream |

**Returns:**
java.util.List<com.aspose.email.VCardContact> - List of contacs
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
### loadAsMultiple(String filePath) {#loadAsMultiple-java.lang.String-}
```
public static List<VCardContact> loadAsMultiple(String filePath)
```


Loads list of contacts from multi contact file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| filePath | java.lang.String | Source file |

**Returns:**
java.util.List<com.aspose.email.VCardContact> - 
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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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

### setDeliveryAddresses(VCardDeliveryAddressCollection value) {#setDeliveryAddresses-com.aspose.email.VCardDeliveryAddressCollection-}
```
public final void setDeliveryAddresses(VCardDeliveryAddressCollection value)
```


Gets or sets a delivery addresses

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardDeliveryAddressCollection](../../com.aspose.email/vcarddeliveryaddresscollection) |  |

### setEmails(VCardEmailCollection value) {#setEmails-com.aspose.email.VCardEmailCollection-}
```
public final void setEmails(VCardEmailCollection value)
```


Gets or sets a contact's email addresses

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardEmailCollection](../../com.aspose.email/vcardemailcollection) |  |

### setExplanatoryInfo(VCardExplanatoryInfo value) {#setExplanatoryInfo-com.aspose.email.VCardExplanatoryInfo-}
```
public final void setExplanatoryInfo(VCardExplanatoryInfo value)
```


Gets or sets a vCard explanatory information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardExplanatoryInfo](../../com.aspose.email/vcardexplanatoryinfo) |  |

### setExtendedProperties(System.Collections.Specialized.StringCollection value) {#setExtendedProperties-com.aspose.ms.System.Collections.Specialized.StringCollection-}
```
public final void setExtendedProperties(System.Collections.Specialized.StringCollection value)
```


Gets or sets an extended properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | com.aspose.ms.System.Collections.Specialized.StringCollection |  |

### setGeo(VCardGeo value) {#setGeo-com.aspose.email.VCardGeo-}
```
public final void setGeo(VCardGeo value)
```


Gets or sets a global positioning

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardGeo](../../com.aspose.email/vcardgeo) |  |

### setIdentificationInfo(VCardIdentificationInfo value) {#setIdentificationInfo-com.aspose.email.VCardIdentificationInfo-}
```
public final void setIdentificationInfo(VCardIdentificationInfo value)
```


Gets or sets an identification properties

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardIdentificationInfo](../../com.aspose.email/vcardidentificationinfo) |  |

### setLabels(VCardLabelCollection value) {#setLabels-com.aspose.email.VCardLabelCollection-}
```
public final void setLabels(VCardLabelCollection value)
```


Gets or sets a delivery addresses

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardLabelCollection](../../com.aspose.email/vcardlabelcollection) |  |

### setMailer(String value) {#setMailer-java.lang.String-}
```
public final void setMailer(String value)
```


Gets or sets a mailer

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setOrganization(VCardOrganization value) {#setOrganization-com.aspose.email.VCardOrganization-}
```
public final void setOrganization(VCardOrganization value)
```


Gets or sets an organization information

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardOrganization](../../com.aspose.email/vcardorganization) |  |

### setSecurity(VCardSecurity value) {#setSecurity-com.aspose.email.VCardSecurity-}
```
public final void setSecurity(VCardSecurity value)
```


Gets or sets a security properites

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardSecurity](../../com.aspose.email/vcardsecurity) |  |

### setTelephoneNumbers(VCardTelephoneNumberCollection value) {#setTelephoneNumbers-com.aspose.email.VCardTelephoneNumberCollection-}
```
public final void setTelephoneNumbers(VCardTelephoneNumberCollection value)
```


Gets or sets a contact's telephone numbers

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [VCardTelephoneNumberCollection](../../com.aspose.email/vcardtelephonenumbercollection) |  |

### setTimeZone(String value) {#setTimeZone-java.lang.String-}
```
public final void setTimeZone(String value)
```


Gets or sets a timeZone

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

