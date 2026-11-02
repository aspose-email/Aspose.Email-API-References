---
title: Class MapiDistributionListSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiDistributionListSaveOptions class. Options for saving a distribution list
type: docs
weight: 17230
url: /net/aspose.email.mapi/mapidistributionlistsaveoptions/
---
## MapiDistributionListSaveOptions class

Options for saving a distribution list.

```csharp
public sealed class MapiDistributionListSaveOptions : ContactSaveOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiDistributionListSaveOptions](mapidistributionlistsaveoptions/)(ContactSaveFormat) | Initializes a new instance of the `MapiDistributionListSaveOptions` class that saves to the specified format. |

## Properties

| Name | Description |
| --- | --- |
| static [Default](../../aspose.email.mapi/mapidistributionlistsaveoptions/default/) { get; } | Gets new options that save to MSG format. |
| [ProductId](../../aspose.email.mapi/contactsaveoptions/productid/) { get; set; } | Gets or sets the identifier of the product that created the vCard, written to its `PRODID` property. |
| [SaveFormat](../../aspose.email.mapi/contactsaveoptions/saveformat/) { get; } | Gets the format this options object saves to. |
| [Version](../../aspose.email.mapi/contactsaveoptions/version/) { get; set; } | Gets or sets the vCard version to write. Used only when the contact is saved to vCard. |

## Remarks

The format is set in the constructor: MSG or vCard. WebDAV is not supported for distribution lists.

### See Also

* class [ContactSaveOptions](../contactsaveoptions/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


