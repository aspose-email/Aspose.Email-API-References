---
title: Contact
second_title: Aspose.Email for .NET API Reference
description: Represents contact information.
type: docs
weight: 19340
url: /net/aspose.email.personalinfo/contact/
---
## Contact class

Represents contact information.

```csharp
public class Contact : IPreferredTextEncodingProvider
```

## Constructors

| Name | Description |
| --- | --- |
| [Contact](contact)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [Account](../../aspose.email.personalinfo/contact/account) { get; set; } | Contains the alias of an Address Book object, which is an alternative name by which the object can be identified. |
| [AssociatedPersons](../../aspose.email.personalinfo/contact/associatedpersons) { get; } | Gets list of associated persons |
| [Attachments](../../aspose.email.personalinfo/contact/attachments) { get; } | Gets attachments collection |
| [CompanyName](../../aspose.email.personalinfo/contact/companyname) { get; set; } | Gets or sets a company name. |
| [ComputerNetworkName](../../aspose.email.personalinfo/contact/computernetworkname) { get; set; } | Gets or sets a name of the mail user's computer network. |
| [CustomerId](../../aspose.email.personalinfo/contact/customerid) { get; set; } | Gets or sets a customer id |
| [DepartmentName](../../aspose.email.personalinfo/contact/departmentname) { get; set; } | Gets or sets a department name. |
| [DisplayName](../../aspose.email.personalinfo/contact/displayname) { get; set; } | Gets or sets a display name |
| [EmailAddresses](../../aspose.email.personalinfo/contact/emailaddresses) { get; } | Gets list of email addresses |
| [Events](../../aspose.email.personalinfo/contact/events) { get; } | Gets list of events |
| [FileAs](../../aspose.email.personalinfo/contact/fileas) { get; set; } | Gets or sets a name used for sorting. |
| [FileAsMapping](../../aspose.email.personalinfo/contact/fileasmapping) { get; set; } | Gets or sets a value which specifies how to generate and recompute the value of the FileAs property when other contact name properties change. |
| [FreeBusyLocation](../../aspose.email.personalinfo/contact/freebusylocation) { get; set; } | Gets or sets URL path from which a client can retrieve free/busy information for the contact as an iCal file |
| [Gender](../../aspose.email.personalinfo/contact/gender) { get; set; } | Gets or sets gender of a person. |
| [GivenName](../../aspose.email.personalinfo/contact/givenname) { get; set; } | Gets or sets a given name that is a part of a person's full name. A given name is also known as a personal name, first name, forename, or Christian name. |
| [GovernmentIdNumber](../../aspose.email.personalinfo/contact/governmentidnumber) { get; set; } | Gets or sets a government id number |
| [Hobbies](../../aspose.email.personalinfo/contact/hobbies) { get; set; } | Gets or sets a hobbies |
| [Id](../../aspose.email.personalinfo/contact/id) { get; } | Gets object identification information |
| [Initials](../../aspose.email.personalinfo/contact/initials) { get; set; } | Gets or sets an initials |
| [InstantMessengers](../../aspose.email.personalinfo/contact/instantmessengers) { get; } | Gets list of instant messenger addresses |
| [JobTitle](../../aspose.email.personalinfo/contact/jobtitle) { get; set; } | Gets or sets a job title. |
| [Language](../../aspose.email.personalinfo/contact/language) { get; set; } | Gets or sets a language |
| [Location](../../aspose.email.personalinfo/contact/location) { get; set; } | Gets or sets location |
| [MiddleName](../../aspose.email.personalinfo/contact/middlename) { get; set; } | Gets or sets a middle name that is a part of a person's full name. In some countries people have an additional (middle) name. |
| [Nickname](../../aspose.email.personalinfo/contact/nickname) { get; set; } | Gets or sets a nickname of a person. |
| [Notes](../../aspose.email.personalinfo/contact/notes) { get; set; } | Gets or sets a notes |
| [NotesFormat](../../aspose.email.personalinfo/contact/notesformat) { get; set; } | Gets or sets a format of a notes field. |
| [OfficeLocation](../../aspose.email.personalinfo/contact/officelocation) { get; set; } | Gets or sets office location |
| [OrganizationalIdNumber](../../aspose.email.personalinfo/contact/organizationalidnumber) { get; set; } | Contains an identifier for the mail user used within the mail user's organization. |
| [PhoneNumbers](../../aspose.email.personalinfo/contact/phonenumbers) { get; } | Gets list of phone numbers |
| [Photo](../../aspose.email.personalinfo/contact/photo) { get; set; } | Gets or sets an image of contact |
| [PhysicalAddresses](../../aspose.email.personalinfo/contact/physicaladdresses) { get; } | Gets list of postal addresses |
| [PreferredTextEncoding](../../aspose.email.personalinfo/contact/preferredtextencoding) { get; set; } | Gets or sets preferred encoding for all text properties |
| [Prefix](../../aspose.email.personalinfo/contact/prefix) { get; set; } | Gets or sets a prefix of a full name such like Mr.(mister), Dr.(doctor) and so on. |
| [Profession](../../aspose.email.personalinfo/contact/profession) { get; set; } | Gets or sets a job position of a person in a company. |
| [Suffix](../../aspose.email.personalinfo/contact/suffix) { get; set; } | Gets or sets a suffix of a full name such like Jr.(junior), Sr.(senior) and so on. |
| [Surname](../../aspose.email.personalinfo/contact/surname) { get; set; } | Gets or sets a surname that is a part of a person's full name. Surname is also known as family name or last name. |
| [Urls](../../aspose.email.personalinfo/contact/urls) { get; } | Gets list of urls |

## Methods

| Name | Description |
| --- | --- |
| static [Load](../../aspose.email.personalinfo/contact/load#load)(Stream) | Loads contact data |
| static [Load](../../aspose.email.personalinfo/contact/load#load_2)(string) | Loads contact data |
| static [Load](../../aspose.email.personalinfo/contact/load#load_1)(Stream, ContactLoadFormat) | Loads contact data |
| static [Load](../../aspose.email.personalinfo/contact/load#load_3)(string, ContactLoadFormat) | Loads contact data |
| [Save](../../aspose.email.personalinfo/contact/save#save)(Stream) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) into the given stream with vCard format. The supported vCard version is 2.1 |
| [Save](../../aspose.email.personalinfo/contact/save#save_3)(string) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) to the vCard file with a default options. The supported vCard version is 2.1 |
| [Save](../../aspose.email.personalinfo/contact/save#save_1)(Stream, ContactSaveFormat) | Saves this [`Contact`](../contact) to the given stream with a format using the default options. |
| [Save](../../aspose.email.personalinfo/contact/save#save_2)(Stream, ContactSaveOptions) | Saves this [`Contact`](../contact) to the given stream using specified save options. |
| [Save](../../aspose.email.personalinfo/contact/save#save_4)(string, ContactSaveFormat) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) to the specified file with a format using the default options. The supported save format is vCard. |
| [Save](../../aspose.email.personalinfo/contact/save#save_5)(string, ContactSaveOptions) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) into file using specified save options. The supported save options is [`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| override [ToString](../../aspose.email.personalinfo/contact/tostring)() | Returns a string that represents the current object. |
| [implicit operator](../../aspose.email.personalinfo/contact/op_implicit#op_implicit) | Converts [`Contact`](../contact) to [`MapiContact`](../../aspose.email.mapi/mapicontact) object (2 operators) |

### See Also

* interface [IPreferredTextEncodingProvider](../../aspose.email/ipreferredtextencodingprovider)
* namespace [Aspose.Email.PersonalInfo](../../aspose.email.personalinfo)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
