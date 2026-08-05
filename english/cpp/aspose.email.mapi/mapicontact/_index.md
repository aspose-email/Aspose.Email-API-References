---
title: "Aspose::Email::Mapi::MapiContact class"
linktitle: "MapiContact"
articleTitle: "MapiContact"
second_title: "Aspose.Email for C++"
description: "Represents a MAPI contact item."
type: docs
weight: 10
url: /cpp/aspose.email.mapi/mapicontact/
---

## MapiContact class

**Inherits:** Aspose::Email::Mapi::MapiMessageItemBase

Represents a MAPI contact item.

This class serves as a wrapper for MapiMessage to simplify the process of handling contact information from MAPI properties. It provides a more intuitive interface for accessing and manipulating contact data within the MAPI message.

The following exmaple demonstrates how to get MapiContact object from MapiMessage .

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

```vb
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

## Constructors

| Name | Description |
| --- | --- |
| [MapiContact (6 overloads)](./mapicontact/) | Initializes a new instance of the MapiContact class |

## Methods

| Name | Description |
| --- | --- |
| [ConvertToMapiMessage](./converttomapimessage/) | Converts contact object to mapi message |
| [FromVCard (6 overloads)](./fromvcard/) | Reads MapiContact from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0 |
| [get_Attachments](./get_attachments/) | Gets the attachments in the contact. |
| [get_ElectronicAddresses](./get_electronicaddresses/) | Specify properties for up to three different e-mail addresses and three different fax addresses |
| [get_Events](./get_events/) | Specify events associated with a contact |
| [get_GoogleId](./get_googleid/) | Uses to specify the server URI of the contact GmailClient only |
| [get_NameInfo](./get_nameinfo/) | The properties are used to specify the name of the person represented by the contact |
| [get_OtherFields](./get_otherfields/) | Specify other fields of conhtact. |
| [get_PersonalInfo](./get_personalinfo/) | Specify other additional contact information |
| [get_Photo](./get_photo/) | Contains contact photo MapiContactPhoto . |
| [get_PhysicalAddresses](./get_physicaladdresses/) | Specify three physical addresses: Home Address, Work Address, and Other Address. One of the addresses can be marked as the Mailing Address |
| [get_PidTagUrlName](./get_pidtagurlname/) | Uses to specify the server URI of the contact WebDav only |
| [get_ProfessionalInfo](./get_professionalinfo/) | Properties are used to store professional details for the person represented by the contact |
| [get_Telephones](./get_telephones/) | Specify telephone numbers for the contact |
| [GetUnderlyingMessage](./getunderlyingmessage/) | Retrieves the underlying MapiMessage object. |
| [Save (6 overloads)](./save/) | Saves this MapiContact into the given stream with vCard format. The supported vCard version is 2.1 |
| [set_ElectronicAddresses](./set_electronicaddresses/) | Specify properties for up to three different e-mail addresses and three different fax addresses |
| [set_Events](./set_events/) | Specify events associated with a contact |
| [set_GoogleId](./set_googleid/) | Uses to specify the server URI of the contact GmailClient only |
| [set_NameInfo](./set_nameinfo/) | The properties are used to specify the name of the person represented by the contact |
| [set_OtherFields](./set_otherfields/) | Specify other fields of conhtact. |
| [set_PersonalInfo](./set_personalinfo/) | Specify other additional contact information |
| [set_Photo](./set_photo/) | Contains contact photo MapiContactPhoto . |
| [set_PhysicalAddresses](./set_physicaladdresses/) | Specify three physical addresses: Home Address, Work Address, and Other Address. One of the addresses can be marked as the Mailing Address |
| [set_PidTagUrlName](./set_pidtagurlname/) | Uses to specify the server URI of the contact WebDav only |
| [set_ProfessionalInfo](./set_professionalinfo/) | Properties are used to store professional details for the person represented by the contact |
| [set_Telephones](./set_telephones/) | Specify telephone numbers for the contact |
| [SetBodyContent](./setbodycontent/) | Sets the content of the body. |
| [ContactClass](./contactclass/) | Represents message class. |

