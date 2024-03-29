---
title: IAsyncImapClient.ClientCapabilitiesAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Notifies server which extensions are supported by client. Please note this operation works only in case if server supports RFC5161 See more https//tools.ietf.org/html/rfc5161
type: docs
weight: 60
url: /net/aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync/
---
## IAsyncImapClient.ClientCapabilitiesAsync method

Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

```csharp
public Task<IEnumerable<string>> ClientCapabilitiesAsync(IEnumerable<string> capabilityNames, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IEnumerable`1 | Connection to a server |
| token | IConnection | Propagates notification that operations should be canceled. |
| capabilityNames | CancellationToken | Array of capabilities which are supported by client |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


