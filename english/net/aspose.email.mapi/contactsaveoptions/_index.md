---
title: Class ContactSaveOptions
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.ContactSaveOptions class. The base class for the options that control how a contact is saved. The derived classes select the format VCardSaveOptions for vCard WebDavContactSaveOptions for WebDAV and MapiContactSaveOptions for MSG
type: docs
weight: 16570
url: /net/aspose.email.mapi/contactsaveoptions/
---
## ContactSaveOptions class

The base class for the options that control how a contact is saved. The derived classes select the format: [`VCardSaveOptions`](../../aspose.email.personalinfo.vcard/vcardsaveoptions/) for vCard, [`WebDavContactSaveOptions`](../webdavcontactsaveoptions/) for WebDAV and [`MapiContactSaveOptions`](../mapicontactsaveoptions/) for MSG.

```csharp
public abstract class ContactSaveOptions
```

## Properties

| Name | Description |
| --- | --- |
| [ProductId](../../aspose.email.mapi/contactsaveoptions/productid/) { get; set; } | Gets or sets the identifier of the product that created the vCard, written to its `PRODID` property. |
| [SaveFormat](../../aspose.email.mapi/contactsaveoptions/saveformat/) { get; } | Gets the format this options object saves to. |
| [Version](../../aspose.email.mapi/contactsaveoptions/version/) { get; set; } | Gets or sets the vCard version to write. Used only when the contact is saved to vCard. |

## Remarks

Pass an instance to [`Save`](../mapicontact/save/). [`Version`](./version/) applies only to vCard output; the other formats ignore it.

### See Also

* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


