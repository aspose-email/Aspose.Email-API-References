---
title: Enum ContactFieldsSet
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.ContactFieldsSet enum. Defines the groups of contact fields written when a contact is saved to MHTML. The values can be combined
type: docs
weight: 15980
url: /net/aspose.email/contactfieldsset/
---
## ContactFieldsSet enumeration

Defines the groups of contact fields written when a contact is saved to MHTML. The values can be combined.

```csharp
[Flags]
public enum ContactFieldsSet
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| None | `0` | No fields; only the notes of the contact are written. |
| NameInfo | `1` | The name fields. |
| PersonalInfo | `2` | The personal information fields. |
| ProfessionalInfo | `4` | The professional information fields. |
| PhysicalAddresses | `8` | The postal addresses. |
| Telephones | `10` | The telephone numbers. |
| ElectronicAddresses | `20` | The e-mail addresses and fax numbers. |
| Events | `40` | The dates, such as the birthday. |
| OtherFields | `80` | The other fields. |
| AllExisting | `100` | All fields that have a value. |

### See Also

* namespace [Aspose.Email](../../aspose.email/)
* assembly [Aspose.Email](../../)


