---
title: Class MapiContactElectronicAddress
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiContactElectronicAddress class. An email address or fax number of a contact
type: docs
weight: 17020
url: /net/aspose.email.mapi/mapicontactelectronicaddress/
---
## MapiContactElectronicAddress class

An e-mail address or fax number of a contact.

```csharp
public sealed class MapiContactElectronicAddress : MapiContactAddress
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiContactElectronicAddress](mapicontactelectronicaddress/#constructor)() | Initializes a new instance of the `MapiContactElectronicAddress` class. |
| [MapiContactElectronicAddress](mapicontactelectronicaddress/#constructor_1)(string) | Initializes a new instance of the `MapiContactElectronicAddress` class with an e-mail address. |
| [MapiContactElectronicAddress](mapicontactelectronicaddress/#constructor_2)(string, string) | Initializes a new instance of the `MapiContactElectronicAddress` class with a fax number and an e-mail address. |
| [MapiContactElectronicAddress](mapicontactelectronicaddress/#constructor_3)(string, string, string) | Initializes a new instance of the `MapiContactElectronicAddress` class. |

## Properties

| Name | Description |
| --- | --- |
| [AddressType](../../aspose.email.mapi/mapicontactelectronicaddress/addresstype/) { get; set; } | Gets or sets the type of the address, such as `SMTP` or `EX` (Exchange). |
| [DisplayName](../../aspose.email.mapi/mapicontactelectronicaddress/displayname/) { get; set; } | Gets or sets the name shown for the address. |
| [EmailAddress](../../aspose.email.mapi/mapicontactelectronicaddress/emailaddress/) { get; set; } | Gets or sets the e-mail address. |
| [FaxNumber](../../aspose.email.mapi/mapicontactelectronicaddress/faxnumber/) { get; set; } | Gets or sets the fax number. |
| [IsEmpty](../../aspose.email.mapi/mapicontactelectronicaddress/isempty/) { get; } | Gets a value indicating whether no field of the address is set. |
| [OriginalDisplayName](../../aspose.email.mapi/mapicontactelectronicaddress/originaldisplayname/) { get; set; } | Gets or sets the SMTP form of the address, used when the address itself is of another type. |

## Methods

| Name | Description |
| --- | --- |
| override [Equals](../../aspose.email.mapi/mapicontactelectronicaddress/equals/)(object) | Determines whether the specified object is equal to the current object. |
| override [GetHashCode](../../aspose.email.mapi/mapicontactelectronicaddress/gethashcode/)() | Returns the hash code of the address. |
| override [ToString](../../aspose.email.mapi/mapicontactelectronicaddress/tostring/)() | Returns a string that represents the current object. |
| [implicit operator](../../aspose.email.mapi/mapicontactelectronicaddress/op_implicit/) | Performs an implicit conversion from String to `MapiContactElectronicAddress`. |

## Remarks

A string converts implicitly to this class, so an e-mail address can be assigned directly: `contact.ElectronicAddresses.Email1 = "alice@example.com";`.

### See Also

* class [MapiContactAddress](../mapicontactaddress/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


