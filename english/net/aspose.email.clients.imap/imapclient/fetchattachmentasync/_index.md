---
title: ImapClient.FetchAttachmentAsync
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Fetches the specified attachment
type: docs
weight: 650
url: /net/aspose.email.clients.imap/imapclient/fetchattachmentasync/
---
## FetchAttachmentAsync(IConnection, int, string) {#fetchattachmentasync}

Fetches the specified attachment

```csharp
public Task<Attachment> FetchAttachmentAsync(IConnection connection, int sequenceNumber, 
    string attachmentName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of a message |
| attachmentName | String | A name of attachment |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Attachment](../../../aspose.email/attachment/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## FetchAttachmentAsync(int, string) {#fetchattachmentasync_2}

Fetches the specified attachment

```csharp
public Task<Attachment> FetchAttachmentAsync(int sequenceNumber, string attachmentName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of a message |
| attachmentName | String | A name of attachment |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Attachment](../../../aspose.email/attachment/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## FetchAttachmentAsync(IConnection, int, string, CancellationToken) {#fetchattachmentasync_1}

Fetches the specified attachment

```csharp
public Task<Attachment> FetchAttachmentAsync(IConnection connection, int sequenceNumber, 
    string attachmentName, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of a message |
| attachmentName | String | A name of attachment |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Attachment](../../../aspose.email/attachment/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## FetchAttachmentAsync(int, string, CancellationToken) {#fetchattachmentasync_3}

Fetches the specified attachment

```csharp
public Task<Attachment> FetchAttachmentAsync(int sequenceNumber, string attachmentName, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of a message |
| attachmentName | String | A name of attachment |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Attachment](../../../aspose.email/attachment/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


