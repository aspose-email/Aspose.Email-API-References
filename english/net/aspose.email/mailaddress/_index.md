---
title: Class MailAddress
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.MailAddress class. Represents an email address with support for display names encoding and address parsing. This class provides functionality for working with email addresses in email messages including properties for the display name user name host and raw address. It supports proper encoding of international characters in display names and validates email addresses against SMTP standards
type: docs
weight: 16460
url: /net/aspose.email/mailaddress/
---
## MailAddress class

Represents an email address with support for display names, encoding, and address parsing. This class provides functionality for working with email addresses in email messages, including properties for the display name, user name, host, and raw address. It supports proper encoding of international characters in display names and validates email addresses against SMTP standards.

```csharp
public class MailAddress : IMailAddress
```

## Constructors

| Name | Description |
| --- | --- |
| [MailAddress](mailaddress/#constructor)(string) | Initializes a new instance of the `MailAddress` class. |
| [MailAddress](mailaddress/#constructor_1)(string, bool) | Initializes a new instance of the `MailAddress` class. |
| [MailAddress](mailaddress/#constructor_2)(string, string) | Initializes a new instance of the `MailAddress` class. |
| [MailAddress](mailaddress/#constructor_3)(string, string, bool) | Initializes a new instance of the `MailAddress` class. |
| [MailAddress](mailaddress/#constructor_4)(string, string, Encoding) | Initializes a new instance of the `MailAddress` class. |
| [MailAddress](mailaddress/#constructor_5)(string, string, Encoding, bool) | Initializes a new instance of the `MailAddress` class. |

## Properties

| Name | Description |
| --- | --- |
| [Address](../../aspose.email/mailaddress/address/) { get; set; } | Gets or sets the e-mail address, such as `john@example.com`. |
| [Count](../../aspose.email/mailaddress/count/) { get; } | Gets the number of addresses, which is always 1. Together with the indexer it lets an address be used where a list is expected. |
| [DisplayName](../../aspose.email/mailaddress/displayname/) { get; set; } | Gets or sets the display name, such as `John Smith`. |
| [Host](../../aspose.email/mailaddress/host/) { get; } | Gets the host part of the address: the part after `@`. |
| [Id](../../aspose.email/mailaddress/id/) { get; } | Gets the identifiers of the address on the server it came from, such as Exchange. |
| [Item](../../aspose.email/mailaddress/item/) { get; } | Gets the address itself; the index is ignored. |
| [OriginalAddressString](../../aspose.email/mailaddress/originaladdressstring/) { get; } | Gets the address exactly as it appeared in the message, before it was parsed. |
| [ParticipationStatus](../../aspose.email/mailaddress/participationstatus/) { get; set; } | Gets or sets the response of the attendee to a meeting request, when the address is a meeting attendee. |
| [User](../../aspose.email/mailaddress/user/) { get; } | Gets the user part of the address: the part before `@`. |
| [X500Address](../../aspose.email/mailaddress/x500address/) { get; } | Gets the Exchange (X.500) form of the address, if the message has one. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.email/mailaddress/equals/)(object) | Determines whether the specified object is the same e-mail address. |
| override [GetHashCode](../../aspose.email/mailaddress/gethashcode/)() | Returns a hash code for this instance. |
| override [ToString](../../aspose.email/mailaddress/tostring/)() | Returns the address with its display name, as written in a header. |
| [implicit operator](../../aspose.email/mailaddress/op_implicit/#op_implicit_1) | Performs an implicit conversion from String to `MailAddress`. (2 operators) |

## Remarks

The `MailAddress` class can represent both simple email addresses (e.g., "user@example.com") and addresses with display names (e.g., "John Elias &lt;john@example.com&gt;"). It automatically handles encoding of non-ASCII characters in display names and validates addresses to ensure they comply with SMTP standards.

## Examples

The following example shows how to create mail addresses with and without display names.

[C#]

```csharp
// Create a simple email address
var address1 = new MailAddress("user@example.com");

// Create an address with display name
var address2 = new MailAddress("john@example.com", "John Doe");

// Create an address with encoded display name (international characters)
var encoding = Encoding.UTF8;
var address3 = new MailAddress("user@example.com", "Андрей Иванов", encoding);

// Access address properties
Console.WriteLine("Address: " + address1.Address);
Console.WriteLine("Display Name: " + address2.DisplayName);
Console.WriteLine("User: " + address2.User);
Console.WriteLine("Host: " + address2.Host);
```

[Visual Basic]

```csharp
' Create a simple email address
Dim address1 As New MailAddress("user@example.com")

' Create an address with display name
Dim address2 As New MailAddress("john@example.com", "John Doe")

' Create an address with encoded display name (international characters)
Dim encoding As Encoding = Encoding.UTF8
Dim address3 As New MailAddress("user@example.com", "Андрей Иванов", encoding)

' Access address properties
Console.WriteLine("Address: " + address1.Address)
Console.WriteLine("Display Name: " + address2.DisplayName)
Console.WriteLine("User: " + address2.User)
Console.WriteLine("Host: " + address2.Host)
```

### See Also

* interface [IMailAddress](../imailaddress/)
* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


