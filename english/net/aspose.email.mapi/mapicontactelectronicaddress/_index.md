---
title: Class MapiContactElectronicAddress
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiContactElectronicAddress class. Represents a group of properties that define an electronic address email or fax for a contact. This class provides functionality for managing contact email addresses and fax numbers through properties such as display name address type email address and fax number
type: docs
weight: 17020
url: /net/aspose.email.mapi/mapicontactelectronicaddress/
---
## MapiContactElectronicAddress class

Represents a group of properties that define an electronic address (email or fax) for a contact. This class provides functionality for managing contact email addresses and fax numbers through properties such as display name, address type, email address, and fax number.

```csharp
public sealed class MapiContactElectronicAddress : MapiContactAddress
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiContactElectronicAddress](mapicontactelectronicaddress/#constructor)() | Initializes a new instance of the `MapiContactElectronicAddress` class. |
| [MapiContactElectronicAddress](mapicontactelectronicaddress/#constructor_1)(string) | Initializes a new instance of the `MapiContactElectronicAddress` class. |
| [MapiContactElectronicAddress](mapicontactelectronicaddress/#constructor_2)(string, string) | Initializes a new instance of the `MapiContactElectronicAddress` class. |
| [MapiContactElectronicAddress](mapicontactelectronicaddress/#constructor_3)(string, string, string) | Initializes a new instance of the `MapiContactElectronicAddress` class. |

## Properties

| Name | Description |
| --- | --- |
| [AddressType](../../aspose.email.mapi/mapicontactelectronicaddress/addresstype/) { get; set; } | Gets or sets the address type of an electronic address |
| [DisplayName](../../aspose.email.mapi/mapicontactelectronicaddress/displayname/) { get; set; } | Gets or sets the user-readable display name for the e-mail address |
| [EmailAddress](../../aspose.email.mapi/mapicontactelectronicaddress/emailaddress/) { get; set; } | Gets or sets the e-mail address of the contact |
| [FaxNumber](../../aspose.email.mapi/mapicontactelectronicaddress/faxnumber/) { get; set; } | Gets or sets the telephone number of the mail user's primary fax machine |
| [IsEmpty](../../aspose.email.mapi/mapicontactelectronicaddress/isempty/) { get; } | Shows if MapiContactElectronicAddress is empty |
| [OriginalDisplayName](../../aspose.email.mapi/mapicontactelectronicaddress/originaldisplayname/) { get; set; } | Gets or sets the SMTP e-mail address that corresponds to the e-mail address for the Contact object. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.email.mapi/mapicontactelectronicaddress/equals/)(object) | Determines whether the specified object is equal to the current object. |
| override [GetHashCode](../../aspose.email.mapi/mapicontactelectronicaddress/gethashcode/)() |  |
| override [ToString](../../aspose.email.mapi/mapicontactelectronicaddress/tostring/)() | Returns a string that represents the current object. |
| [implicit operator](../../aspose.email.mapi/mapicontactelectronicaddress/op_implicit/) | Performs an implicit conversion from String to `MapiContactElectronicAddress`. |

## Remarks

Use this class to manage electronic addresses in [`MapiContact`](../mapicontact/) items. The class supports both email addresses and fax numbers, with properties like [`DisplayName`](./displayname/), [`AddressType`](./addresstype/), [`EmailAddress`](./emailaddress/), and [`FaxNumber`](./faxnumber/). It also supports implicit conversion from string for convenient email address assignment.

### See Also

* class [MapiContactAddress](../mapicontactaddress/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


