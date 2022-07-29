---
title: GetOptions
second_title: Aspose.Email för .NET API-referens
description: Den statiska metoden GetOptions används för att upptäcka vilka protokollversioner som stöds och vilka protokollkommandon som stöds på servern. Klienten använder den statiska metoden GetOptions för att avgöra om servern stöder samma versioner av protokollet som klienten stöder.
type: docs
weight: 180
url: /sv/net/aspose.email.clients.activesync.transportlayer/activesynctlclient/getoptions/
---
## ActiveSyncTLClient.GetOptions method

Den statiska metoden GetOptions används för att upptäcka vilka protokollversioner som stöds och vilka protokollkommandon som stöds på servern. Klienten använder den statiska metoden GetOptions för att avgöra om servern stöder samma versioner av protokollet som klienten stöder.

```csharp
public static ASProtocolVersions GetOptions(string uri, NetworkCredential credentials, 
    out string[] supportedServerCommands, out string[] supportedServerProtocols)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uri | String | URL:en för ActiveSync-tjänsten |
| credentials | NetworkCredential | Autentiseringsuppgifter för att ansluta till servern. |
| supportedServerCommands | String[]& | Out-parameter, returnerar protokollkommandon som stöds |
| supportedServerProtocols | String[]& | Out-parameter, returnerar versioner av protokollet som stöds |

### Returvärde

Returnerar den senaste protokollversionen som stöds

### Se även

* enum [ASProtocolVersions](../../asprotocolversions)
* class [ActiveSyncTLClient](../../activesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../activesynctlclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->