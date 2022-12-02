---
title: VCardContact
second_title: Aspose.Email for .NET API Reference
description: Represents a vCard contact
type: docs
weight: 19590
url: /net/aspose.email.personalinfo.vcard/vcardcontact/
---
## VCardContact class

Represents a vCard contact

```csharp
public sealed class VCardContact
```

## Constructors

| Name | Description |
| --- | --- |
| [VCardContact](vcardcontact)() | Initializes a new instance of the [`VCardContact`](../vcardcontact) class |

## Properties

| Name | Description |
| --- | --- |
| [DeliveryAddresses](../../aspose.email.personalinfo.vcard/vcardcontact/deliveryaddresses) { get; set; } | Gets or sets a delivery addresses |
| [Emails](../../aspose.email.personalinfo.vcard/vcardcontact/emails) { get; set; } | Gets or sets a contact's email addresses |
| [ExplanatoryInfo](../../aspose.email.personalinfo.vcard/vcardcontact/explanatoryinfo) { get; set; } | Gets or sets a vCard explanatory information |
| [ExtendedProperties](../../aspose.email.personalinfo.vcard/vcardcontact/extendedproperties) { get; set; } | Gets or sets an extended properties |
| [Geo](../../aspose.email.personalinfo.vcard/vcardcontact/geo) { get; set; } | Gets or sets a global positioning |
| [IdentificationInfo](../../aspose.email.personalinfo.vcard/vcardcontact/identificationinfo) { get; set; } | Gets or sets an identification properties |
| [Labels](../../aspose.email.personalinfo.vcard/vcardcontact/labels) { get; set; } | Gets or sets a delivery addresses |
| [Mailer](../../aspose.email.personalinfo.vcard/vcardcontact/mailer) { get; set; } | Gets or sets a mailer |
| [Organization](../../aspose.email.personalinfo.vcard/vcardcontact/organization) { get; set; } | Gets or sets an organization information |
| [Security](../../aspose.email.personalinfo.vcard/vcardcontact/security) { get; set; } | Gets or sets a security properites |
| [TelephoneNumbers](../../aspose.email.personalinfo.vcard/vcardcontact/telephonenumbers) { get; set; } | Gets or sets a contact's telephone numbers |
| [TimeZone](../../aspose.email.personalinfo.vcard/vcardcontact/timezone) { get; set; } | Gets or sets a timeZone |

## Methods

| Name | Description |
| --- | --- |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load)(Stream) | Reads [`VCardContact`](../vcardcontact) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_4)(string) | Reads [`VCardContact`](../vcardcontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_3)(Stream, CancellationToken) | Reads [`VCardContact`](../vcardcontact) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_1)(Stream, Encoding) | Reads [`VCardContact`](../vcardcontact) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_7)(string, CancellationToken) | Reads [`VCardContact`](../vcardcontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_5)(string, Encoding) | Reads [`VCardContact`](../vcardcontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_2)(Stream, Encoding, CancellationToken) | Reads [`VCardContact`](../vcardcontact) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0 |
| static [Load](../../aspose.email.personalinfo.vcard/vcardcontact/load#load_6)(string, Encoding, CancellationToken) | Reads [`VCardContact`](../vcardcontact) from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save)(Stream) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) into the given stream with vCard format. The supported vCard version is 2.1 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_3)(string) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) to the vCard file with a default options. The supported vCard version is 2.1 |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_1)(Stream, ContactSaveFormat) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) to the given stream with a format using the default options. The supported save format is vCard |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_2)(Stream, ContactSaveOptions) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) to the given stream using specified save options. The supported save options is [`VCardSaveOptions`](../vcardsaveoptions) |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_4)(string, ContactSaveFormat) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) to the specified file with a format using the default options. The supported save format is vCard. |
| [Save](../../aspose.email.personalinfo.vcard/vcardcontact/save#save_5)(string, ContactSaveOptions) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) into file using specified save options. The supported save options is [`VCardSaveOptions`](../vcardsaveoptions) |
| static [IsMultiContacts](../../aspose.email.personalinfo.vcard/vcardcontact/ismulticontacts)(Stream) | Checks whether source stream contains multi contacts. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple)(Stream, Encoding) | Loads list of contacts from multi contact stream. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_2)(string, Encoding) | Loads list of contacts from multi contact file. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_1)(Stream, Encoding, CancellationToken) | Loads list of contacts from multi contact stream. |
| static [LoadAsMultiple](../../aspose.email.personalinfo.vcard/vcardcontact/loadasmultiple#loadasmultiple_3)(string, Encoding, CancellationToken) | Loads list of contacts from multi contact stream. |

### See Also

* namespace [Aspose.Email.PersonalInfo.VCard](../../aspose.email.personalinfo.vcard)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
