---
title: Class MapiContact
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiContact class. Represents a MAPI contact item
type: docs
weight: 18370
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
| [MapiContact](mapicontact/#constructor)() | Initializes a new instance of the `MapiContact` class |
| [MapiContact](mapicontact/#constructor_1)(string, string) | Initializes a new instance of the `MapiContact` class. |
| [MapiContact](mapicontact/#constructor_2)(string, string, string) | Initializes a new instance of the `MapiContact` class. |
| [MapiContact](mapicontact/#constructor_3)(string, string, string, string) | Initializes a new instance of the `MapiContact` class. |

## Properties

| Name | Description |
| --- | --- |
| [Attachments](../../aspose.email.mapi/mapicontact/attachments/) { get; } | Gets the attachments in the contact. |
| [Billing](../../aspose.email.mapi/mapimessageitembase/billing/) { get; set; } | Contains the billing information associated with an item. |
| [Body](../../aspose.email.mapi/mapimessageitembase/body/) { get; set; } | Gets the message text. |
| [BodyHtml](../../aspose.email.mapi/mapimessageitembase/bodyhtml/) { get; } | Gets the [`BodyRtf`](../mapimessageitembase/bodyrtf/) of the message converted to HTML, if present, otherwise an empty string. |
| [BodyRtf](../../aspose.email.mapi/mapimessageitembase/bodyrtf/) { get; set; } | Gets or sets the RTF formatted message text. |
| [BodyType](../../aspose.email.mapi/mapimessageitembase/bodytype/) { get; } | Gets the type of the body. |
| [Categories](../../aspose.email.mapi/mapimessageitembase/categories/) { get; set; } | Contains keywords or categories for the message object. |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page. |
| [Companies](../../aspose.email.mapi/mapimessageitembase/companies/) { get; set; } | Contains the names of the companies that are associated with an item. |
| [ElectronicAddresses](../../aspose.email.mapi/mapicontact/electronicaddresses/) { get; set; } | Specify properties for up to three different e-mail addresses and three different fax addresses |
| [Events](../../aspose.email.mapi/mapicontact/events/) { get; set; } | Specify events associated with a contact |
| virtual [ItemId](../../aspose.email.mapi/mapimessageitembase/itemid/) { get; } | The item id, uses with a server |
| [MessageClass](../../aspose.email.mapi/mapimessageitembase/messageclass/) { get; set; } | Gets a case-sensitive string that identifies the sender-defined message class, such as IPM.Note. The message class specifies the type, purpose, or content of the message. |
| [Mileage](../../aspose.email.mapi/mapimessageitembase/mileage/) { get; set; } | Contains the mileage information that is associated with an item. |
| [NamedProperties](../../aspose.email.mapi/mapimessageitembase/namedproperties/) { get; } | Gets the named properties of message. |
| [NamedPropertyMapping](../../aspose.email.mapi/mapimessageitembase/namedpropertymapping/) { get; } | Gets the named property mapping. |
| [NameInfo](../../aspose.email.mapi/mapicontact/nameinfo/) { get; set; } | The properties are used to specify the name of the person represented by the contact |
| [OtherFields](../../aspose.email.mapi/mapicontact/otherfields/) { get; set; } | Specify other fields of conhtact. |
| [PersonalInfo](../../aspose.email.mapi/mapicontact/personalinfo/) { get; set; } | Specify other additional contact information |
| [Photo](../../aspose.email.mapi/mapicontact/photo/) { get; set; } | Contains contact photo[`MapiContactPhoto`](../mapicontactphoto/). |
| [PhysicalAddresses](../../aspose.email.mapi/mapicontact/physicaladdresses/) { get; set; } | Specify three physical addresses: Home Address, Work Address, and Other Address. One of the addresses can be marked as the Mailing Address |
| [ProfessionalInfo](../../aspose.email.mapi/mapicontact/professionalinfo/) { get; set; } | Properties are used to store professional details for the person represented by the contact |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets the collection of properties. |
| [PropertyStream](../../aspose.email.mapi/mapimessageitembase/propertystream/) { get; } | Gets the property stream. |
| [Recipients](../../aspose.email.mapi/mapimessageitembase/recipients/) { get; set; } | Gets the recipients of the message. |
| [Sensitivity](../../aspose.email.mapi/mapimessageitembase/sensitivity/) { get; set; } | Gets the Sensitivity. |
| [Subject](../../aspose.email.mapi/mapimessageitembase/subject/) { get; set; } | Gets or sets the subject of the message. |
| [SubjectPrefix](../../aspose.email.mapi/mapimessageitembase/subjectprefix/) { get; } | Gets a subject prefix that typically indicates some action on a message, such as "FW: " for forwarding. |
| [SubStorages](../../aspose.email.mapi/mapimessageitembase/substorages/) { get; } | Gets the sub storages. |
| [SupportedType](../../aspose.email.mapi/mapimessageitembase/supportedtype/) { get; } | Gets the supported item type. |
| [Telephones](../../aspose.email.mapi/mapicontact/telephones/) { get; set; } | Specify telephone numbers for the contact |

## Methods

| Name | Description |
| --- | --- |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard/#fromvcard)(Stream) | Reads `MapiContact` from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard/#fromvcard_2)(string) | Reads `MapiContact` from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard/#fromvcard_1)(Stream, Encoding) | Reads `MapiContact` from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0 |
| static [FromVCard](../../aspose.email.mapi/mapicontact/fromvcard/#fromvcard_3)(string, Encoding) | Reads `MapiContact` from the specified vCard file The supported vCard versions are 2.1 and 3.0 |
| virtual [Dispose](../../aspose.email.mapi/mapimessageitembase/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| override [GetProperty](../../aspose.email.mapi/mapimessageitembase/getproperty/)(PropertyDescriptor) | Gets MAPI property by property descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of the property specified by tag as Boolean type. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of the property specified by tag as DateTime type. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the int32 value of the property specified by tag. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of the property specified by tag as Long (int64) type. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of the property specified by tag as Short type. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long) | Gets the string value of the property specified by tag. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long, int) | Gets the string value of the property specified by tag. |
| [GetUnderlyingMessage](../../aspose.email.mapi/mapicontact/getunderlyingmessage/)() | Retrieves the underlying MapiMessage object. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines if string properties are Unicode encoded or not. |
| [RemoveProperty](../../aspose.email.mapi/mapimessageitembase/removeproperty/)(long) | Provides correctly removing property from all collections. |
| [Save](../../aspose.email.mapi/mapicontact/save/#save)(Stream) | Saves this `MapiContact` into the given stream with vCard format. The supported vCard version is 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save/#save_3)(string) | Saves this `MapiContact` to the vCard file with a default options. The supported vCard version is 2.1 |
| [Save](../../aspose.email.mapi/mapicontact/save/#save_1)(Stream, ContactSaveFormat) | Saves this `MapiContact` to the given stream with a format using the default options. The supported save format is vCard |
| [Save](../../aspose.email.mapi/mapicontact/save/#save_2)(Stream, ContactSaveOptions) | Saves this `MapiContact` to the given stream using specified save options. The supported save options is [`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions/) |
| [Save](../../aspose.email.mapi/mapicontact/save/#save_4)(string, ContactSaveFormat) | Saves this `MapiContact` to the specified file with a format using the default options. The supported save format is vCard. |
| [Save](../../aspose.email.mapi/mapicontact/save/#save_5)(string, ContactSaveOptions) | Saves this `MapiContact` into file using specified save options. The supported save options is [`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions/) |
| override [SetBodyContent](../../aspose.email.mapi/mapicontact/setbodycontent/#setbodycontent)(string, BodyContentType) | Sets the content of the body. |
| virtual [SetBodyContent](../../aspose.email.mapi/mapimessageitembase/setbodycontent/)(string, BodyContentType, bool) | Sets the content of the body. |
| [SetBodyRtf](../../aspose.email.mapi/mapimessageitembase/setbodyrtf/)(string, bool) | Gets or sets the RTF formatted message text. |
| [SetMessageFlags](../../aspose.email.mapi/mapimessageitembase/setmessageflags/)(MapiMessageFlags) | Sets the message flags. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(MapiProperty) | Sets the property. |
| override [SetProperty](../../aspose.email.mapi/mapimessageitembase/setproperty/)(PropertyDescriptor, object) | Sets MAPI property. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Try to get the property data with specified tag key. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of the specified property as DateTime type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of the specified property as Int32 type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of the specified property as Long type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long) | Try to get a property data as string with specified tag. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, int) | Try to get a property data as string with specified tag and code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string, int) | Gets the value of the specified property as String type. A return value indicates whether the operation succeeded. |

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


