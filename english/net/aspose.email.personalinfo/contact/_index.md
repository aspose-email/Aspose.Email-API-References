---
title: Contact
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 19120
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
| [Account](account) { get; set; } | Contains the alias of an Address Book object, which is an alternative name by which the object can be identified. |
| [AssociatedPersons](associatedpersons) { get; } | Gets list of associated persons |
| [Attachments](attachments) { get; } | Gets attachments collection |
| [CompanyName](companyname) { get; set; } | Gets or sets a company name. |
| [ComputerNetworkName](computernetworkname) { get; set; } | Gets or sets a name of the mail user's computer network. |
| [CustomerId](customerid) { get; set; } | Gets or sets a customer id |
| [DepartmentName](departmentname) { get; set; } | Gets or sets a department name. |
| [DisplayName](displayname) { get; set; } | Gets or sets a display name |
| [EmailAddresses](emailaddresses) { get; } | Gets list of email addresses |
| [Events](events) { get; } | Gets list of events |
| [FileAs](fileas) { get; set; } | Gets or sets a name used for sorting. |
| [FileAsMapping](fileasmapping) { get; set; } | Gets or sets a value which specifies how to generate and recompute the value of the FileAs property when other contact name properties change. |
| [FreeBusyLocation](freebusylocation) { get; set; } | Gets or sets URL path from which a client can retrieve free/busy information for the contact as an iCal file |
| [Gender](gender) { get; set; } | Gets or sets gender of a person. |
| [GivenName](givenname) { get; set; } | Gets or sets a given name that is a part of a person's full name. A given name is also known as a personal name, first name, forename, or Christian name. |
| [GovernmentIdNumber](governmentidnumber) { get; set; } | Gets or sets a government id number |
| [Hobbies](hobbies) { get; set; } | Gets or sets a hobbies |
| [Id](id) { get; } | Gets object identification information |
| [Initials](initials) { get; set; } | Gets or sets an initials |
| [InstantMessengers](instantmessengers) { get; } | Gets list of instant messenger addresses |
| [JobTitle](jobtitle) { get; set; } | Gets or sets a job title. |
| [Language](language) { get; set; } | Gets or sets a language |
| [Location](location) { get; set; } | Gets or sets location |
| [MiddleName](middlename) { get; set; } | Gets or sets a middle name that is a part of a person's full name. In some countries people have an additional (middle) name. |
| [Nickname](nickname) { get; set; } | Gets or sets a nickname of a person. |
| [Notes](notes) { get; set; } | Gets or sets a notes |
| [NotesFormat](notesformat) { get; set; } | Gets or sets a format of a notes field. |
| [OfficeLocation](officelocation) { get; set; } | Gets or sets office location |
| [OrganizationalIdNumber](organizationalidnumber) { get; set; } | Contains an identifier for the mail user used within the mail user's organization. |
| [PhoneNumbers](phonenumbers) { get; } | Gets list of phone numbers |
| [Photo](photo) { get; set; } | Gets or sets an image of contact |
| [PhysicalAddresses](physicaladdresses) { get; } | Gets list of postal addresses |
| [PreferredTextEncoding](preferredtextencoding) { get; set; } | Gets or sets preferred encoding for all text properties |
| [Prefix](prefix) { get; set; } | Gets or sets a prefix of a full name such like Mr.(mister), Dr.(doctor) and so on. |
| [Profession](profession) { get; set; } | Gets or sets a job position of a person in a company. |
| [Suffix](suffix) { get; set; } | Gets or sets a suffix of a full name such like Jr.(junior), Sr.(senior) and so on. |
| [Surname](surname) { get; set; } | Gets or sets a surname that is a part of a person's full name. Surname is also known as family name or last name. |
| [Urls](urls) { get; } | Gets list of urls |

## Methods

| Name | Description |
| --- | --- |
| static [Load](load)(Stream) | Loads contact data |
| static [Load](load)(string) | Loads contact data |
| static [Load](load)(Stream, ContactLoadFormat) | Loads contact data |
| static [Load](load)(string, ContactLoadFormat) | Loads contact data |
| [Save](save)(Stream) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) into the given stream with vCard format. The supported vCard version is 2.1 |
| [Save](save)(string) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) to the vCard file with a default options. The supported vCard version is 2.1 |
| [Save](save)(Stream, ContactSaveFormat) | Saves this [`Contact`](../contact) to the given stream with a format using the default options. |
| [Save](save)(Stream, ContactSaveOptions) | Saves this [`Contact`](../contact) to the given stream using specified save options. |
| [Save](save)(string, ContactSaveFormat) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) to the specified file with a format using the default options. The supported save format is vCard. |
| [Save](save)(string, ContactSaveOptions) | Saves this [`MapiContact`](../../aspose.email.mapi/mapicontact) into file using specified save options. The supported save options is [`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions) |
| override [ToString](tostring)() | Returns a string that represents the current object. |
| [implicit operator](op_implicit) | Converts [`Contact`](../contact) to [`MapiContact`](../../aspose.email.mapi/mapicontact) object (2 operators) |

### See Also

* interface [IPreferredTextEncodingProvider](../../aspose.email/ipreferredtextencodingprovider)
* namespace [Aspose.Email.PersonalInfo](../../aspose.email.personalinfo)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
