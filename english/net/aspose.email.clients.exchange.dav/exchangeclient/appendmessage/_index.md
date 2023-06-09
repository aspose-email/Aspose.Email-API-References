---
title: ExchangeClient.AppendMessage
second_title: Aspose.Email for .NET API Reference
description: ExchangeClient method. Uploads the mail message to the specified folder
type: docs
weight: 90
url: /net/aspose.email.clients.exchange.dav/exchangeclient/appendmessage/
---
## AppendMessage(string, MailMessage) {#appendmessage}

Uploads the mail message to the specified folder

```csharp
public string AppendMessage(string folder, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to which message is uploaded |
| message | MailMessage | A message to upload |

### Return Value

An uri of created message

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | A folder is not specified |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *message* is `null` |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessage(string, MailMessage, bool) {#appendmessage_1}

Uploads the mail message to the specified folder

```csharp
public string AppendMessage(string folder, MailMessage message, bool markAsSent)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | An uri of folder to which message is uploaded |
| message | MailMessage | A message to upload |
| markAsSent | Boolean | A value indicating whether the message should be appended as a sent message or a draft. |

### Return Value

An uri of created message

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | A folder is not specified |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *message* is `null` |

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)


