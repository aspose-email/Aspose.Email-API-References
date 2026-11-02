---
title: Class MapiRecipient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiRecipient class. A recipient of an Outlook message or of another item such as a meeting
type: docs
weight: 17460
url: /net/aspose.email.mapi/mapirecipient/
---
## MapiRecipient class

A recipient of an Outlook message, or of another item such as a meeting.

```csharp
public class MapiRecipient : MapiPropertyContainer
```

## Properties

| Name | Description |
| --- | --- |
| [AddressType](../../aspose.email.mapi/mapirecipient/addresstype/) { get; } | Gets the type of the address of the recipient, such as `SMTP` or `EX` (Exchange). |
| virtual [CodePage](../../aspose.email.mapi/mapipropertycontainer/codepage/) { get; } | Gets the code page of the ANSI strings of the object. |
| [Content](../../aspose.email.mapi/mapirecipient/content/) { get; } | Gets the content of the recipient. |
| [DisplayName](../../aspose.email.mapi/mapirecipient/displayname/) { get; set; } | Gets or sets the display name of the recipient. |
| [EmailAddress](../../aspose.email.mapi/mapirecipient/emailaddress/) { get; set; } | Gets or sets the e-mail address of the recipient, in SMTP form. |
| [NamedProperties](../../aspose.email.mapi/mapirecipient/namedproperties/) { get; } | Gets the named properties of the recipient. |
| [OrganizationEmailAddress](../../aspose.email.mapi/mapirecipient/organizationemailaddress/) { get; } | Gets the e-mail address of the recipient within the organization (`PR_ORG_EMAIL_ADDR`). |
| virtual [Properties](../../aspose.email.mapi/mapipropertycontainer/properties/) { get; } | Gets all properties of the object. |
| [PropertyStream](../../aspose.email.mapi/mapirecipient/propertystream/) { get; } | Gets the property stream of the recipient. |
| [RecipientClass](../../aspose.email.mapi/mapirecipient/recipientclass/) { get; } | Gets the type of the MAPI object of the recipient, such as a mail user or a distribution list. |
| [RecipientTrackStatus](../../aspose.email.mapi/mapirecipient/recipienttrackstatus/) { get; set; } | Gets or sets the response of the recipient to a meeting request. |
| [RecipientType](../../aspose.email.mapi/mapirecipient/recipienttype/) { get; } | Gets the type of the recipient: To, CC or BCC. |
| [SubStorages](../../aspose.email.mapi/mapirecipient/substorages/) { get; } | Gets the sub-storages of the recipient. |

## Methods

| Name | Description |
| --- | --- |
| virtual [GetProperty](../../aspose.email.mapi/mapipropertycontainer/getproperty/)(PropertyDescriptor) | Gets a MAPI property by its descriptor. |
| [GetPropertyBoolean](../../aspose.email.mapi/mapipropertycontainer/getpropertyboolean/)(long) | Gets the value of a property as a Boolean. |
| [GetPropertyBytes](../../aspose.email.mapi/mapipropertycontainer/getpropertybytes/)(long) | Gets the value of a property as bytes. |
| [GetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/getpropertydatetime/)(long) | Gets the value of a property as a date and time. |
| [GetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/getpropertyint32/)(long) | Gets the value of a property as a 32-bit integer. |
| [GetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/getpropertylong/)(long) | Gets the value of a property as a 64-bit integer. |
| [GetPropertyShort](../../aspose.email.mapi/mapipropertycontainer/getpropertyshort/)(long) | Gets the value of a property as a 16-bit integer. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long) | Gets the value of a property as a string. |
| [GetPropertyString](../../aspose.email.mapi/mapipropertycontainer/getpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [IsStoreUnicodeOk](../../aspose.email.mapi/mapipropertycontainer/isstoreunicodeok/)() | Determines whether the string properties of the object are stored in Unicode. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(MapiProperty) | Adds the property, or replaces the property with the same tag. |
| virtual [SetProperty](../../aspose.email.mapi/mapipropertycontainer/setproperty/)(PropertyDescriptor, object) | Sets the value of a MAPI property, creating the property if needed. |
| [TryGetPropertyData](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydata/)(long) | Gets the value of a property as bytes. |
| [TryGetPropertyDateTime](../../aspose.email.mapi/mapipropertycontainer/trygetpropertydatetime/)(long, ref DateTime) | Gets the value of a property as a date and time, if the property exists. |
| [TryGetPropertyInt32](../../aspose.email.mapi/mapipropertycontainer/trygetpropertyint32/)(long, ref int) | Gets the value of a property as a 32-bit integer, if the property exists. |
| [TryGetPropertyLong](../../aspose.email.mapi/mapipropertycontainer/trygetpropertylong/)(long, ref long) | Gets the value of a property as a 64-bit integer, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long) | Gets the value of a property as a string. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, int) | Gets the value of a property as a string, decoding an ANSI string with the specified code page. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string) | Gets the value of a property as a string, if the property exists. |
| [TryGetPropertyString](../../aspose.email.mapi/mapipropertycontainer/trygetpropertystring/)(long, ref string, int) | Gets the value of a property as a string, if the property exists, decoding an ANSI string with the specified code page. |

### See Also

* class [MapiPropertyContainer](../mapipropertycontainer/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


