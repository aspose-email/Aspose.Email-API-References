---
title: ClientCapabilitiesAsync
second_title: Aspose.Email för .NET API-referens
description: Meddelar servern vilka tillägg som stöds av klienten. Observera att denna operation endast fungerar om servern stöder RFC5161 Se mer https//tools.ietf.org/html/rfc5161
type: docs
weight: 60
url: /sv/net/aspose.email.clients.imap/iasyncimapclient/clientcapabilitiesasync/
---
## IAsyncImapClient.ClientCapabilitiesAsync method

Meddelar servern vilka tillägg som stöds av klienten. Observera att denna operation endast fungerar om servern stöder RFC5161 Se mer https://tools.ietf.org/html/rfc5161

```csharp
public Task<IEnumerable<string>> ClientCapabilitiesAsync(IEnumerable<string> capabilityNames, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IEnumerable`1 | Anslutning till en server |
| token | IConnection | Sprider meddelande om att operationer bör avbrytas. |
| capabilityNames | CancellationToken | En rad funktioner som stöds av klienten |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* interface [IAsyncImapClient](../../iasyncimapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->