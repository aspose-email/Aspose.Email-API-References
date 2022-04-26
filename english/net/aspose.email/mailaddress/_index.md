---
title: MailAddress
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 15910
url: /net/aspose.email/mailaddress/
---
## MailAddress class

Represents the address of a message.

```csharp
public class MailAddress : IMailAddress
```

## Constructors

| Name | Description |
| --- | --- |
| [MailAddress](mailaddress)(string) | Initializes a new instance of the [`MailAddress`](../mailaddress) class. |
| [MailAddress](mailaddress)(string, bool) | Initializes a new instance of the [`MailAddress`](../mailaddress) class. |
| [MailAddress](mailaddress)(string, string) | Initializes a new instance of the [`MailAddress`](../mailaddress) class. |
| [MailAddress](mailaddress)(string, string, bool) | Initializes a new instance of the [`MailAddress`](../mailaddress) class. |
| [MailAddress](mailaddress)(string, string, Encoding) | Initializes a new instance of the [`MailAddress`](../mailaddress) class. |
| [MailAddress](mailaddress)(string, string, Encoding, bool) | Initializes a new instance of the [`MailAddress`](../mailaddress) class. |

## Properties

| Name | Description |
| --- | --- |
| [Address](address) { get; set; } | Gets or sets the e-mail address. |
| [Count](count) { get; } | Contains count of mail addresses. |
| [DisplayName](displayname) { get; set; } | Gets or sets a display name. |
| [Host](host) { get; } | Gets the host portion of the address. |
| [Id](id) { get; } | Gets object identification information |
| [Item](item) { get; } | Gets the element at the specified index. |
| [OriginalAddressString](originaladdressstring) { get; } | Gets or sets the original e-mail address string. |
| [ParticipationStatus](participationstatus) { get; set; } | Gets or sets the participation status for the calendar user. |
| [User](user) { get; } | Gets the username. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](equals)(object) | Determines whether the specified Object is equal to this instance. |
| override [GetHashCode](gethashcode)() | Returns a hash code for this instance. |
| override [ToString](tostring)() | Returns a String that represents this instance. |
| [implicit operator](op_implicit) | Performs an implicit conversion from String to [`MailAddress`](../mailaddress). (2 operators) |

### See Also

* interface [IMailAddress](../imailaddress)
* namespace [Aspose.Email](../../aspose.email)
* assembly [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->