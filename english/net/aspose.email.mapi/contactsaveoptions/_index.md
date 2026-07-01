---
title: Class ContactSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.ContactSaveOptions class. Serves as the abstract base class for contact save options when saving contact objects to various formats. This class provides common configuration properties such as save format and vCard version for contact serialization
type: docs
weight: 16570
url: /net/aspose.email.mapi/contactsaveoptions/
---
## ContactSaveOptions class

Serves as the abstract base class for contact save options when saving contact objects to various formats. This class provides common configuration properties such as save format and vCard version for contact serialization.

```csharp
public abstract class ContactSaveOptions
```

## Properties

| Name | Description |
| --- | --- |
| [ProductId](../../aspose.email.mapi/contactsaveoptions/productid/) { get; set; } | Gets or sets the product identifier that created VCard object. |
| [SaveFormat](../../aspose.email.mapi/contactsaveoptions/saveformat/) { get; } | Gets a save format |
| [Version](../../aspose.email.mapi/contactsaveoptions/version/) { get; set; } | Gets or sets a vCard version This property is meaningful if ContactSaveFormat is set to VCard. |

## Remarks

This class is designed to be inherited by concrete format-specific classes like [`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions/). Do not instantiate this class directly. Use the format-specific subclasses to access format-specific saving options. The [`Version`](./version/) property controls the vCard format version when saving to vCard format.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


