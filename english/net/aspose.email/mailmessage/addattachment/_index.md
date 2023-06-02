---
title: MailMessage.AddAttachment
second_title: Aspose.Email for .NET API Reference
description: MailMessage method. Add an attachment to message
type: docs
weight: 390
url: /net/aspose.email/mailmessage/addattachment/
---
## MailMessage.AddAttachment method

Add an attachment to message

```csharp
public virtual void AddAttachment(Attachment attachment)
```

| Parameter | Type | Description |
| --- | --- | --- |
| attachment | Attachment | Attachment for adding |

## Examples

The following example shows how to add Attachments to MailMessage.

[C#]

```csharp
// Create an instance of MailMessage class
var eml = new MailMessage
{
	From = "sender@from.com",
	To = "receiver@to.com",
	Subject = "This is message",
	Body = "This is body"
};

// Load an attachment
var attachment = new Attachment("1.txt");

// Add Multiple Attachment in instance of MailMessage class and Save message to disk
eml.Attachments.Add(attachment);

eml.AddAttachment(new Attachment("1.jpg"));
eml.AddAttachment(new Attachment("1.doc"));
eml.AddAttachment(new Attachment("1.rar"));
eml.AddAttachment(new Attachment("1.pdf"));
eml.Save("AddAttachments.eml");
```

[Visual Basic]

```csharp
' Create an instance of MailMessage class
Dim eml = New MailMessage With {
  .From = "sender@from.com",
	.[To] = "receiver@to.com",
	.Subject = "This is message",
	.Body = "This is body"
		}

' Load an attachment
Dim attachment = New Attachment("1.txt")

' Add Multiple Attachment in instance of MailMessage class and Save message to disk
eml.Attachments.Add(attachment)

eml.AddAttachment(New Attachment("1.jpg"))
eml.AddAttachment(New Attachment("1.doc"))
eml.AddAttachment(New Attachment("1.rar"))
eml.AddAttachment(New Attachment("1.pdf"))
eml.Save("AddAttachments.eml")
```

### See Also

* class [Attachment](../../attachment/)
* class [MailMessage](../)
* namespace [Aspose.Email](../../mailmessage/)
* assembly [Aspose.Email](../../../)


