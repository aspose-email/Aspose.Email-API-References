---
title: Class EmailAddress
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.PersonalInfo.EmailAddress class. Represents an email address
type: docs
weight: 18230
url: /net/aspose.email.personalinfo/emailaddress/
---
## EmailAddress class

Represents an email address

```csharp
public class EmailAddress : MailAddress, IComparable<EmailAddress>, IEquatable<EmailAddress>
```

## Constructors

| Name | Description |
| --- | --- |
| [EmailAddress](emailaddress/#constructor)() | Initializes a new instance of the `EmailAddress` class. |
| [EmailAddress](emailaddress/#constructor_1)(string) | Initializes a new instance of the `EmailAddress` class. |
| [EmailAddress](emailaddress/#constructor_2)(string, string) | Initializes a new instance of the `EmailAddress` class. |

## Properties

| Name | Description |
| --- | --- |
| [Address](../../aspose.email/mailaddress/address/) { get; set; } | Gets or sets the e-mail address, such as `john@example.com`. |
| [Category](../../aspose.email.personalinfo/emailaddress/category/) { get; set; } | Gets or sets an object category |
| [Count](../../aspose.email/mailaddress/count/) { get; } | Gets the number of addresses, which is always 1. Together with the indexer it lets an address be used where a list is expected. |
| [DisplayName](../../aspose.email/mailaddress/displayname/) { get; set; } | Gets or sets the display name, such as `John Smith`. |
| [Host](../../aspose.email/mailaddress/host/) { get; } | Gets the host part of the address: the part after `@`. |
| [Id](../../aspose.email/mailaddress/id/) { get; } | Gets the identifiers of the address on the server it came from, such as Exchange. |
| [Item](../../aspose.email/mailaddress/item/) { get; } | Gets the address itself; the index is ignored. |
| [OriginalAddressString](../../aspose.email/mailaddress/originaladdressstring/) { get; } | Gets the address exactly as it appeared in the message, before it was parsed. |
| [ParticipationStatus](../../aspose.email/mailaddress/participationstatus/) { get; set; } | Gets or sets the response of the attendee to a meeting request, when the address is a meeting attendee. |
| [Prefered](../../aspose.email.personalinfo/emailaddress/prefered/) { get; set; } | Gets or sets a value which defines whether email address is preferred. |
| [RoutingType](../../aspose.email.personalinfo/emailaddress/routingtype/) { get; set; } | Gets or sets a routing type for an email |
| [User](../../aspose.email/mailaddress/user/) { get; } | Gets the user part of the address: the part before `@`. |
| [X500Address](../../aspose.email/mailaddress/x500address/) { get; } | Gets the Exchange (X.500) form of the address, if the message has one. |

## Methods

| Name | Description |
| --- | --- |
| virtual [CompareTo](../../aspose.email.personalinfo/emailaddress/compareto/)(EmailAddress) | Compares the current instance with another object of the same type and returns an integer that indicates whether the current instance precedes, follows, or occurs in the same position in the sort order as the other object. |
| [Equals](../../aspose.email.personalinfo/emailaddress/equals/#equals)(EmailAddress) | Determines whether the specified Object is equal to the current Object. |
| override [Equals](../../aspose.email.personalinfo/emailaddress/equals/#equals_2)(object) | Determines whether the specified Object is equal to the current Object. |
| [Equals](../../aspose.email.personalinfo/emailaddress/equals/#equals_1)(EmailAddress, EmailAddress) | Determines whether the specified object instances are considered equal. |
| override [GetHashCode](../../aspose.email.personalinfo/emailaddress/gethashcode/#gethashcode)() | GetHashCode returns a hash function for this object. |
| [GetHashCode](../../aspose.email.personalinfo/emailaddress/gethashcode/#gethashcode_1)(EmailAddress) | GetHashCode returns a hash function for specified object. |
| override [ToString](../../aspose.email.personalinfo/emailaddress/tostring/)() | Returns a string that represents the current object. |
| [operator ==](../../aspose.email.personalinfo/emailaddress/op_equality/) | Determines whether the specified objects are equal. |
| [operator !=](../../aspose.email.personalinfo/emailaddress/op_inequality/) | Determines whether the specified objects are not equal. |

### See Also

* class [MailAddress](../../aspose.email/mailaddress/)
* namespace [Aspose.Email.PersonalInfo](../../aspose.email.personalinfo/)
* assembly [Aspose.Email](../../)


