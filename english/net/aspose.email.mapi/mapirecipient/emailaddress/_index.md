---
title: EmailAddress
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 40
url: /net/aspose.email.mapi/mapirecipient/emailaddress/
---
## MapiRecipient.EmailAddress property

Gets or sets the email address of the message recipient or sender.

```csharp
public string EmailAddress { get; set; }
```

## Property Value

The email address.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | throws if recipient address is null or empty. |
| ArgumentException | throws if recipient address is not in a recognized format. |

### Remarks

Note, this property displays an address in SMTP format. It means that if MapiRecipient.AddressType == "EX" and MapiPropertyTag.PR_EMAIL_ADDRESS contain an address in Exchange-style, the value for mapiRecipient.EmailAddress property filling is picked from PR_SMTP_ADDRESS. When setting a value, the values of PR_SEARCH_KEY and PR_ENTRYID properties are updated as well.

### See Also

* class [MapiRecipient](../../mapirecipient)
* namespace [Aspose.Email.Mapi](../../mapirecipient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->