---
title: ActiveSyncTLClient
second_title: Aspose.Email för .NET API-referens
description: Grundklass för ActiveSync-klientimplementeringar
type: docs
weight: 950
url: /sv/net/aspose.email.clients.activesync.transportlayer/activesynctlclient/
---
## ActiveSyncTLClient class

Grundklass för ActiveSync-klientimplementeringar

```csharp
public class ActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/authenticationtype) { get; set; } | Hämtar eller ställer in typen av autentisering som används av ActiveSync-klienten. |
| virtual [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscoveruri) { get; set; } | Hämtar eller ställer in autodiscover-tjänsten uri |
| virtual [Credentials](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/credentials) { get; } | Användarens autentiseringsuppgifter för Exchange-server |
| virtual [DeviceID](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/deviceid) { get; set; } | En GUID som identifierar enheten. Enhets-ID:t anges av enhets-id-specifikationen ABNF-regeldelen av frågevärdet i vanlig text. Värdet, som representeras av enhets-id ABNF-regeln, är en sträng som anger enheten. Varje enhet MÅSTE ha en unik enhets-ID-sträng. Varje begäran från enheten MÅSTE innehålla samma enhets-ID-sträng. |
| virtual [DeviceType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/devicetype) { get; set; } | Enhetstypen specificeras av ABNF-regeldelen för enhetstypspecifikation av frågevärdet i vanlig text. Värdet, som representeras av ABNF-regeln av enhetstyp, är vilken sträng som helst som anger en enhetstyp. "SP" anger en SmartPhone och "PPC" anger en PocketPC. Andra klientenheter skickar unika strängar för sin specifika enhetstyp. Varje begäran från en klientenhet MÅSTE innehålla samma enhetstypsträng. |
| virtual [PolicyState](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/policystate) { get; set; } | Ett osignerat heltal som indikerar tillståndet för policyinställningar på klientenheten, som specificerats i [MS-ASPROV] avsnitt 2.2.2.41. |
| virtual [Proxy](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/proxy) { get; set; } | Hämtar eller ställer in proxyn. |
| virtual [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedservercommands) { get; } | Hämtar versionerna av ActiveSync-kommandon som stöds |
| virtual [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedserverprotocols) { get; } | Hämtar versionerna av ActiveSync-protokoll som stöds |
| virtual [Timeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/timeout) { get; set; } | Hämtar eller ställer in antalet millisekunder som ska vänta innan åtgärden tar slut. Standardvärdet är 100 000 millisekunder (100 sekunder). |
| virtual [Uri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/uri) { get; } | Hämtar URL:en till ActiveSync-tjänsten |
| virtual [UserAgent](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/useragent) { get; set; } | Fältet User-Agent request-header innehåller information om användaragenten som skapade begäran. Detta är för statistiska ändamål, spårning av protokollöverträdelser och automatiserad igenkänning av användaragenter för att skräddarsy svar för att undvika särskilda användaragentbegränsningar. Användaragenter SKA inkludera detta fält med förfrågningar. Fältet kan innehålla flera produkttokens (avsnitt 3.8) och kommentarer som identifierar agenten och eventuella underprodukter som utgör en betydande del av användaragenten. Enligt konvention listas produktsymbolerna i ordning efter deras betydelse för att identifiera applikationen. Exempel: User-Agent: CERN-LineMode/2.15 libwww/2.17b3 |
| virtual [Version](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/version) { get; } | Hämtar versionen av protokollet som används i ActiveSync-klienten. |
| static [DefaultTimeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/defaulttimeout) { get; set; } | Hämtar eller ställer in standardvärdet för timeout för ActiveSync-klientinstanser Standardvärdet är 100 000 millisekunder (100 sekunder). |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string) | Kommandot Autodiscover underlättar upptäckten av kärnkontokonfigurationsinformation genom att använda användarens SMTP-adress (Simple Mail Transfer Protocol) som primär ingång. |
| [Dispose](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/dispose)() | Utför uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| static [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string, NetworkCredential, string) | Kommandot Autodiscover underlättar upptäckten av kärnkontokonfigurationsinformation genom att använda användarens SMTP-adress (Simple Mail Transfer Protocol) som primär ingång. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance)(string, NetworkCredential) | Hämtar en instans av ActiveSync client Versionen av ActiveSync-protokollet väljs automatiskt enligt serverns svar. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance_1)(string, NetworkCredential, ASProtocolVersions) | Hämtar en instans av ActiveSync-klienten |
| static [GetOptions](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getoptions)(string, NetworkCredential, out string[], out string[]) | Den statiska metoden GetOptions används för att upptäcka vilka protokollversioner som stöds och vilka protokollkommandon som stöds på servern. Klienten använder den statiska metoden GetOptions för att avgöra om servern stöder samma versioner av protokollet som klienten stöder. |

### Se även

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
