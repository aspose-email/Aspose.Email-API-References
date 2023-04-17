---
title: ImapClient.ClientCapabilities
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Notifies server which extensions are supported by client. Please note this operation works only in case if server supports RFC5161 See more https//tools.ietf.org/html/rfc5161
type: docs
weight: 450
url: /net/aspose.email.clients.imap/imapclient/clientcapabilities/
---
## ClientCapabilities(params string[]) {#clientcapabilities_1}

Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

```csharp
public string[] ClientCapabilities(params string[] capabilityNames)
```

| Parameter | Type | Description |
| --- | --- | --- |
| capabilityNames | String[] | Array of capabilities which are supported by client |

### Return Value

Returns array with capabilities which are supported by a server.

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ClientCapabilities(IConnection, params string[]) {#clientcapabilities}

Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

```csharp
public string[] ClientCapabilities(IConnection connection, params string[] capabilityNames)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| capabilityNames | String[] | Array of capabilities which are supported by client |

### Return Value

Returns array with capabilities which are supported by a server.

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


