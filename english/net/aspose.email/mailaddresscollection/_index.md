---
title: Class MailAddressCollection
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.MailAddressCollection class. A list of email addresses such as the recipients of a message
type: docs
weight: 16470
url: /net/aspose.email/mailaddresscollection/
---
## MailAddressCollection class

A list of e-mail addresses, such as the recipients of a message.

```csharp
public class MailAddressCollection : Collection<MailAddress>
```

## Constructors

| Name | Description |
| --- | --- |
| [MailAddressCollection](mailaddresscollection/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.email/mailaddresscollection/add/#add)(MailAddress) | Adds an address to the collection. |
| [Add](../../aspose.email/mailaddresscollection/add/#add_2)(string) | Adds one or more addresses to the collection. |
| [AddRange](../../aspose.email/mailaddresscollection/addrange/#addrange_1)(IEnumerable&lt;MailAddress&gt;) | Adds a sequence of addresses. |
| [AddRange](../../aspose.email/mailaddresscollection/addrange/#addrange)(MailAddressCollection) | Adds the addresses of another collection. |
| [Copy](../../aspose.email/mailaddresscollection/copy/)() | Creates a copy of the collection. |
| override [ToString](../../aspose.email/mailaddresscollection/tostring/)() | Returns the addresses as a comma-separated list, as written in a header. |
| [implicit operator](../../aspose.email/mailaddresscollection/op_implicit/#op_implicit) | Performs an implicit conversion from [`MailAddress`](../mailaddress/) to `MailAddressCollection`. (2 operators) |

## Remarks

A string converts to this class implicitly, so `msg.To = "a@example.com, b@example.com";` works.

## Examples

This example adds recipients to a message in several ways.

[C#]

```csharp
var msg = new MailMessage();
msg.From = new MailAddress("sender@example.com", "Sender");

// a comma-separated list
msg.To.Add("alice@example.com, bob@example.com");

// one address with a display name
msg.CC.Add(new MailAddress("carol@example.com", "Carol"));

// implicit conversion from a string
msg.Bcc = "audit@example.com";

foreach (MailAddress address in msg.To)
{
    Console.WriteLine(address.Address);
}
```

[Visual Basic]

```csharp
Dim msg = New MailMessage()
msg.From = New MailAddress("sender@example.com", "Sender")

' a comma-separated list
msg.To.Add("alice@example.com, bob@example.com")

' one address with a display name
msg.CC.Add(New MailAddress("carol@example.com", "Carol"))

' implicit conversion from a string
msg.Bcc = "audit@example.com"

For Each address As MailAddress In msg.To
    Console.WriteLine(address.Address)
Next
```

### See Also

* class [MailAddress](../mailaddress/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


