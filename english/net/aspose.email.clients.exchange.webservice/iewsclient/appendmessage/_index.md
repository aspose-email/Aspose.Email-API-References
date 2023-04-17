---
title: IEWSClient.AppendMessage
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Uploads the mail message to the specified folder
type: docs
weight: 370
url: /net/aspose.email.clients.exchange.webservice/iewsclient/appendmessage/
---
## AppendMessage(MapiMessage) {#appendmessage_1}

Uploads the mail message to the specified folder

```csharp
public string AppendMessage(MapiMessage mapiMessage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mapiMessage | MapiMessage | A message to upload |

### Return Value

An uri of created message

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessage(MapiMessage, bool) {#appendmessage_2}

Uploads the mail message to the specified folder

```csharp
public string AppendMessage(MapiMessage mapiMessage, bool markAsSent)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mapiMessage | MapiMessage | A message to upload |
| markAsSent | Boolean | A value indicating whether the message should be appended as a sent message or a draft. |

### Return Value

An uri of created message

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessage(string, MapiMessage, bool) {#appendmessage_5}

Uploads the mail message to the specified folder

```csharp
public string AppendMessage(string folderUri, MapiMessage mapiMessage, bool markAsSent)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | String | A folder URI to which message is uploaded. |
| mapiMessage | MapiMessage | A message to upload |
| markAsSent | Boolean | A value indicating whether the message should be appended as a sent message or a draft. |

### Return Value

An uri of created message

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | A folder is not specified |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | *mapiMessage* is `null` |

### See Also

* class [MapiMessage](../../../aspose.email.mapi/mapimessage/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessage(MailMessage) {#appendmessage}

Uploads the mail message to the Inbox folder

```csharp
public string AppendMessage(MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| message | MailMessage | A message to upload |

### Return Value

An uri of created message

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## AppendMessage(string, MailMessage) {#appendmessage_3}

Uploads the mail message to the specified folder

```csharp
public string AppendMessage(string folderUri, MailMessage message)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | String | A folder URI to which message is uploaded. |
| message | MailMessage | A message to upload |

### Return Value

An uri of created message

### See Also

* class [MailMessage](../../../aspose.email/mailmessage/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


