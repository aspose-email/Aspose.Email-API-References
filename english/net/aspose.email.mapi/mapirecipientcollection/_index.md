---
title: Class MapiRecipientCollection
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Mapi.MapiRecipientCollection class. The recipients of an Outlook item
type: docs
weight: 17470
url: /net/aspose.email.mapi/mapirecipientcollection/
---
## MapiRecipientCollection class

The recipients of an Outlook item.

```csharp
public class MapiRecipientCollection : Collection<MapiRecipient>
```

## Constructors

| Name | Description |
| --- | --- |
| [MapiRecipientCollection](mapirecipientcollection/)() | Initializes a new instance of the `MapiRecipientCollection` class. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.email.mapi/mapirecipientcollection/add/#add_2)(MapiRecipient) | Adds an existing recipient to the end of the collection. |
| [Add](../../aspose.email.mapi/mapirecipientcollection/add/#add)(string, string, MapiRecipientType) | Adds a recipient. |
| [Add](../../aspose.email.mapi/mapirecipientcollection/add/#add_1)(string, string, string, MapiRecipientType) | Adds a recipient with an address of the specified type. |
| [Insert](../../aspose.email.mapi/mapirecipientcollection/insert/#insert)(int, MapiRecipient) | Inserts a recipient at the specified position. |

## Examples

This example adds To, CC and BCC recipients to a message.

[C#]

```csharp
using (var msg = new MapiMessage("from@domain.com", "to@domain.com", "Report", "The report is attached."))
{
    msg.Recipients.Add("cc@domain.com", "Copy Recipient", MapiRecipientType.MAPI_CC);
    msg.Recipients.Add("bcc@domain.com", "Hidden Recipient", MapiRecipientType.MAPI_BCC);

    foreach (MapiRecipient recipient in msg.Recipients)
    {
        Console.WriteLine($"{recipient.RecipientType}: {recipient.DisplayName} <{recipient.EmailAddress}>");
    }

    msg.Save("report.msg");
}
```

[Visual Basic]

```csharp
Using msg = New MapiMessage("from@domain.com", "to@domain.com", "Report", "The report is attached.")
    msg.Recipients.Add("cc@domain.com", "Copy Recipient", MapiRecipientType.MAPI_CC)
    msg.Recipients.Add("bcc@domain.com", "Hidden Recipient", MapiRecipientType.MAPI_BCC)

    For Each recipient As MapiRecipient In msg.Recipients
        Console.WriteLine($"{recipient.RecipientType}: {recipient.DisplayName} <{recipient.EmailAddress}>")
    Next

    msg.Save("report.msg")
End Using
```

### See Also

* class [MapiRecipient](../mapirecipient/)
* namespace [Aspose.Email.Mapi](../../aspose.email.mapi/)
* assembly [Aspose.Email](../../)


