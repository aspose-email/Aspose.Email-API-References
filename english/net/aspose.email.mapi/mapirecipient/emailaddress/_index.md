---
title: MapiRecipient.EmailAddress
second_title: Aspose.Email for .NET API Reference
description: MapiRecipient property. Gets or sets the email address of the recipient in SMTP form
type: docs
weight: 40
url: /net/aspose.email.mapi/mapirecipient/emailaddress/
---
## MapiRecipient.EmailAddress property

Gets or sets the e-mail address of the recipient, in SMTP form.

```csharp
public string EmailAddress { get; set; }
```

### Property Value

The e-mail address.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | The value is `null` or empty. |
| ArgumentException | The address is not valid. |

## Remarks

For an Exchange (`EX`) recipient the SMTP address is returned, taken from `PR_SMTP_ADDRESS`. Setting the address also updates the search key and the EntryID of the recipient.

### See Also

* class [MapiRecipient](../)
* namespace [Aspose.Email.Mapi](../../mapirecipient/)
* assembly [Aspose.Email](../../../)


