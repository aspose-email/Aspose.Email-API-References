---
title: "Aspose::Email::Attachment class"
linktitle: "Attachment"
articleTitle: "Attachment"
second_title: "Aspose.Email for C++"
description: "Represents an e-mail attachment."
type: docs
weight: 10
url: /cpp/aspose.email/attachment/
---

## Attachment class

**Inherits:** Aspose::Email::AttachmentBase, Aspose::Email::IPreferredTextEncodingProvider

Represents an e-mail attachment.

The following example shows how to add and remove an Attachment from MailMessage .

```csharp
// Create an instance of MailMessage class
var eml = new MailMessage {From = "sender@sender.com", To = "receiver@gmail.com"};
 
// Load an attachment
var attachment = new Attachment("1.txt");
eml.Attachments.Add(attachment);
 
// Remove attachment from your MailMessage
eml.Attachments.Remove(attachment);
```

```vb
' Create an instance of MailMessage class
Dim eml = New MailMessage With {
  .From = "sender@sender.com",
            .[To] = "receiver@gmail.com"
        }
 
' Load an attachment
Dim attachment = New Attachment("1.txt")
eml.Attachments.Add(attachment)
 
' Remove attachment from your MailMessage
eml.Attachments.Remove(attachment)
```

## Constructors

| Name | Description |
| --- | --- |
| [Attachment (9 overloads)](./attachment/) | Initializes a new instance of the Attachment class. |

## Methods

| Name | Description |
| --- | --- |
| [Clone](./clone/) |  |
| [ConvertToMapiAttachment](./converttomapiattachment/) | Implements Aspose::Email::AttachmentBase . |
| [CreateAttachmentFromString (3 overloads)](./createattachmentfromstring/) | Creates the attachment from string. |
| [CreateName](./createname/) |  |
| [get_ContentDisposition](./get_contentdisposition/) | Gets Content-Disposition header |
| [get_CreatedName](./get_createdname/) | Created name from subject in case when attacment is message/rfc822 |
| [get_Id](./get_id/) | Object identifier |
| [get_IsEmbeddedMessage](./get_isembeddedmessage/) | Gets a value indicating whether the attachment is an embedded message. |
| [get_IsTnef](./get_istnef/) | Gets a value indicating whether the attachment is TNEF formatted message. |
| [get_IsUri](./get_isuri/) | Gets a value indicating whether attachment is URI-attachment. |
| [get_Name](./get_name/) | Gets an attachment name |
| [get_NameEncoding](./get_nameencoding/) | Gets an encoding of attachment name |
| [get_PreferredTextEncoding](./get_preferredtextencoding/) | Gets a preferred text encoding |
| [get_UniqueId](./get_uniqueid/) | Gets a unique identifier for the attachment that will be constant for each application run. |
| [set_CreatedName](./set_createdname/) | Created name from subject in case when attacment is message/rfc822 |
| [set_Name](./set_name/) | Sets an attachment name |
| [set_NameEncoding](./set_nameencoding/) | Sets an encoding of attachment name |
| [set_PreferredTextEncoding](./set_preferredtextencoding/) | Sets a preferred text encoding |
| [ToCalendarAttachmentProperty](./tocalendarattachmentproperty/) |  |
| [CollectionNum](./collectionnum/) |  |
| [isUri](./isuri/) |  |

