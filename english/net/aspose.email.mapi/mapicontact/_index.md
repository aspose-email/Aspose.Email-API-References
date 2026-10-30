---
title: Class MapiContact
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiContact class. Represents a MAPI contact item
type: docs
weight: 16990
url: /net/aspose.email.mapi/mapicontact/
---
## MapiContact class

Represents a MAPI contact item.

```csharp
public sealed class MapiContact : MapiMessageItemBase
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiContact](mapicontact/#constructor)() | Initializes a new instance of the `MapiContact` class. |
| [MapiContact](mapicontact/#constructor_1)(string, string) | Initializes a new instance of the `MapiContact` class with the specified details. |
| [MapiContact](mapicontact/#constructor_2)(string, string, string) | Initializes a new instance of the `MapiContact` class with the specified details. |
| [MapiContact](mapicontact/#constructor_3)(string, string, string, string) | Initializes a new instance of the `MapiContact` class with the specified details. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapicontact/attachments/) { get; } | Gets the attachments of the contact. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing/) { get; set; } | Gets or sets the billing information of the item. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body/) { get; set; } | Gets or sets the plain-text body of the item. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml/) { get; } | Gets the body of the item as HTML, converted from [`BodyRtf`](../mapimessageitembase/bodyrtf/); an empty string when there is no RTF body. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf/) { get; set; } | Gets or sets the body of the item in RTF format. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype/) { get; } | Gets the format of the body: plain text, HTML or RTF. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories/) { get; set; } | Gets or sets the categories of the item. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page of the ANSI strings of the object. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies/) { get; set; } | Gets or sets the names of the companies associated with the item. |
| [ElectronicAddresses](../../aspose.email.mapi/mapicontact/electronicaddresses/) { get; set; } | Gets or sets the e-mail addresses (up to three) and fax numbers (up to three) of the contact. |
| [Events](../../aspose.email.mapi/mapicontact/events/) { get; set; } | Gets or sets the dates associated with the contact: birthday and anniversary. |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid/) { get; } | Gets the identifier of the item on the mail server, for items obtained from a server; `null` otherwise. |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass/) { get; set; } | Gets or sets the message class of the item, such as `IPM.Note` for an e-mail message. The class determines the type of the item. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage/) { get; set; } | Gets or sets the mileage information of the item. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties/) { get; } | Gets the named properties of the item. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping/) { get; } | Gets the mapping between the named properties and the tags they are stored under. |
| [NameInfo](../../aspose.email.mapi/mapicontact/nameinfo/) { get; set; } | Gets or sets the name of the contact: given name, surname, title and so on. |
| [OtherFields](../../aspose.email.mapi/mapicontact/otherfields/) { get; set; } | Gets or sets the other fields of the contact: reminder, privacy, journaling and the user-defined fields. |
| [PersonalInfo](../../aspose.email.mapi/mapicontact/personalinfo/) { get; set; } | Gets or sets the personal details of the contact, such as web pages, spouse, children, hobbies and notes. |
| [Photo](../../aspose.email.mapi/mapicontact/photo/) { get; set; } | Gets or sets the photo of the contact. |
| [PhysicalAddresses](../../aspose.email.mapi/mapicontact/physicaladdresses/) { get; set; } | Gets or sets the postal addresses of the contact: home, work and other. One of them can be marked as the mailing address. |
| [ProductId](../../aspose.email.mapi/mapicontact/productid/) { get; set; } | Gets or sets the identifier of the product that created the contact. |
| [ProfessionalInfo](../../aspose.email.mapi/mapicontact/professionalinfo/) { get; set; } | Gets or sets the professional details of the contact: company, job title, department, manager and so on. |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets all properties of the object. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream/) { get; } | Gets the property stream of the item. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients/) { get; set; } | Gets or sets the recipients of the item. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity/) { get; set; } | Gets or sets the sensitivity of the item: normal, personal, private or confidential. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject/) { get; set; } | Gets or sets the subject of the message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix/) { get; } | Gets the prefix of the subject, such as `RE: ` or `FW: `. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages/) { get; } | Gets the sub-storages of the item. |
| [SupportedType](../../aspose.email.mapi/mapimessageitembase/supportedtype/) { get; } | Gets the type of the item, as determined by its message class. |
| [Telephones](../../aspose.email.mapi/mapicontact/telephones/) { get; set; } | Gets or sets the telephone numbers of the contact. |

## Methods

| Name | Description |
| --- | --- |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard/#fromvcard)(Stream) | Loads a contact from a stream that contains a vCard. vCard versions 2.1 and 3.0 are supported. |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard/#fromvcard_3)(string) | Loads a contact from a vCard file. vCard versions 2.1 and 3.0 are supported. |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard/#fromvcard_1)(Stream, VCardLoadOptions) | Loads a contact from a stream that contains a vCard. vCard versions 2.1 and 3.0 are supported. |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard/#fromvcard_4)(string, VCardLoadOptions) | Loads a contact from a vCard file. vCard versions 2.1 and 3.0 are supported. |
| static [Load](../../aspose.email.mapi/mapicontact/load/#load)(Stream) | Loads a `MapiContact` from the specified stream. |
| static [Load](../../aspose.email.mapi/mapicontact/load/#load_1)(string) | Loads a `MapiContact` from the specified file. |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose/)() | Releases the resources used by the item. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty/)(PropertyDescriptor) | Gets a MAPI property of the item by its descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of a property as a Boolean. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the value of a property as bytes. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of a property as a date and time. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the value of a property as a 32-bit integer. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of a property as a 64-bit integer. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of a property as a 16-bit integer. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long) | Gets the value of a property as a string. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [GetUnderlyingMessage](../../aspose.email.mapi/mapicontact/getunderlyingmessage/)() | Retrieves the underlying MapiMessage object. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines whether the string properties of the object are stored in Unicode. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty/)(long) | Removes a property from the item, including its named-property mapping. |
| [Save](../../aspose.email.mapi/mapicontact/save/#save)(Stream) | Saves the contact to a stream in vCard 2.1 format. |
| [Save](../../aspose.email.mapi/mapicontact/save/#save_3)(string) | Saves the contact to a vCard 2.1 file. |
| [Save](../../aspose.email.mapi/mapicontact/save/#save_1)(Stream, ContactSaveFormat) | Saves the contact to a stream in the specified format with the default options. |
| [Save](../../aspose.email.mapi/mapicontact/save/#save_2)(Stream, ContactSaveOptions) | Saves the contact to a stream with the specified options. |
| [Save](../../aspose.email.mapi/mapicontact/save/#save_4)(string, ContactSaveFormat) | Saves the contact to a file in the specified format with the default options. |
| [Save](../../aspose.email.mapi/mapicontact/save/#save_5)(string, ContactSaveOptions) | Saves the contact to a file with the specified options. |
| [SaveAsync](../../aspose.email.mapi/mapicontact/saveasync/#saveasync_2)(Stream, CancellationToken) | Saves this `MapiContact` to the given stream asynchronously. The supported save format is vCard. |
| [SaveAsync](../../aspose.email.mapi/mapicontact/saveasync/#saveasync_5)(string, CancellationToken) | Saves this `MapiContact` to the vCard file with a default options asynchronously. The supported vCard version is 2.1 |
| [SaveAsync](../../aspose.email.mapi/mapicontact/saveasync/#saveasync)(Stream, ContactSaveFormat, CancellationToken) | Saves this `MapiContact` into the given stream with vCard format asynchronously. The supported vCard version is 2.1 |
| [SaveAsync](../../aspose.email.mapi/mapicontact/saveasync/#saveasync_1)(Stream, ContactSaveOptions, CancellationToken) | Saves this `MapiContact` to the given stream using specified save options asynchronously. The supported save options is [`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions/) |
| [SaveAsync](../../aspose.email.mapi/mapicontact/saveasync/#saveasync_3)(string, ContactSaveFormat, CancellationToken) | Saves this `MapiContact` to the specified file with a format using the default options asynchronously. The supported save format is vCard. |
| [SaveAsync](../../aspose.email.mapi/mapicontact/saveasync/#saveasync_4)(string, ContactSaveOptions, CancellationToken) | Saves this `MapiContact` into file using specified save options asynchronously. The supported save options is [`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions/) |
| override [SetBodyContent](../../aspose.email.mapi/mapicontact/setbodycontent/#setbodycontent)(string, BodyContentType) | Sets the content of the body. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType, bool) | Sets the body of the item in the specified format, optionally compressing it. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf/)(string, bool) | Sets the body of the item in RTF format, optionally compressing it. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags/)(MapiMessageFlags) | Sets the flags of the message, such as read or unsent. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(MapiProperty) | Adds the property, or replaces the property with the same tag. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty/)(PropertyDescriptor, object) | Sets the value of a MAPI property of the item. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Gets the value of a property as bytes. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of a property as a date and time, if the property exists. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long) | Gets the value of a property as a string. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string) | Gets the value of a property as a string, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string, int) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |
| static [FromVCardAsync](../../aspose.email.mapi/mapicontact/fromvcardasync/#fromvcardasync_2)(Stream, CancellationToken) | Reads `MapiContact` from the specified stream containing vCard asynchronously. The supported vCard versions are 2.1 and 3.0 |
| static [FromVCardAsync](../../aspose.email.mapi/mapicontact/fromvcardasync/#fromvcardasync_5)(string, CancellationToken) | Reads `MapiContact` from the specified vCard file asynchronously. The supported vCard versions are 2.1 and 3.0 |
| static [FromVCardAsync](../../aspose.email.mapi/mapicontact/fromvcardasync/#fromvcardasync)(Stream, VCardLoadOptions, CancellationToken) | Reads `MapiContact` from the specified stream containing vCard asynchronously. The supported vCard versions are 2.1 and 3.0 |
| static [FromVCardAsync](../../aspose.email.mapi/mapicontact/fromvcardasync/#fromvcardasync_3)(string, VCardLoadOptions, CancellationToken) | Reads `MapiContact` from the specified vCard file asynchronously. The supported vCard versions are 2.1 and 3.0 |
| static [LoadAsync](../../aspose.email.mapi/mapicontact/loadasync/#loadasync)(Stream, CancellationToken) | Loads a `MapiContact` from the specified stream asynchronously. |
| static [LoadAsync](../../aspose.email.mapi/mapicontact/loadasync/#loadasync_1)(string, CancellationToken) | Loads a `MapiContact` from the specified file asynchronously. |

## Remarks

This class serves as a wrapper for [`MapiMessage`](../mapimessage/) to simplify the process of handling contact information from MAPI properties. It provides a more intuitive interface for accessing and manipulating contact data within the MAPI message.

## Examples

The following exmaple demonstrates how to get MapiContact object from MapiMessage.

[C#]

```csharp
var msg = MapiMessage.Load("contact.msg");

// Check if the loaded message is a supported contact type
if (msg.SupportedType == MapiItemType.Contact)
{
    // Convert the MAPI message to a MapiContact object
    var mapiContact = (MapiContact)msg.ToMapiMessageItem();
    
    // Display some contact info
    Console.WriteLine(mapiContact.NameInfo.DisplayName);
    Console.WriteLine(mapiContact.ElectronicAddresses.Email1.EmailAddress);
}
```

[Visual Basic]

```csharp
Dim msg = MapiMessage.Load("contact.msg")

' Check if the loaded message is a supported contact type
If msg.SupportedType = MapiItemType.Contact Then
    ' Convert the MAPI message to a MapiContact object
    Dim mapiContact = DirectCast(msg.ToMapiMessageItem(), MapiContact)
    
    ' Display some contact info
    Console.WriteLine(mapiContact.NameInfo.DisplayName)
    Console.WriteLine(mapiContact.ElectronicAddresses.Email1.EmailAddress)
End If
```

### See Also

* class [MapiMessageItemBase](../mapimessageitembase/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


