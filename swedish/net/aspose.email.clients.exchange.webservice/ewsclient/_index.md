---
title: EWSClient
second_title: Aspose.Email för .NET API-referens
description: Ger åtkomst till MS Exchange Server genom att använda Exchange Web Services EWS.
type: docs
weight: 3680
url: /sv/net/aspose.email.clients.exchange.webservice/ewsclient/
---
## EWSClient class

Ger åtkomst till MS Exchange Server genom att använda Exchange Web Services (EWS).

```csharp
public abstract class EWSClient : ExchangeClientBase
```

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Hämtar eller ställer in autentiseringsuppgifterna |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Hämtar eller ställer in loggfilens namn |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | Hämtar eller ställer in postlådan uri |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Hämtar eller ställer in proxyn. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | Hämtar eller ställer in antalet millisekunder som ska vänta innan åtgärden tar slut. Standardvärdet är 100 000 millisekunder (100 sekunder). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Hämtar eller ställer in värde som indikerar om datum måste användas i loggfilens namn. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Utför programdefinierade uppgifter associerade med att frigöra, frigöra eller återställa ohanterade resurser. |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_2)(string, ICredentials) | Initierar en ny instans av[`EWSClient`](../ewsclient) baserad klass |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_3)(string, ICredentials, WebProxy) | Initierar en ny instans av[`EWSClient`](../ewsclient) baserad klass |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_4)(string, string, string) | Initierar en ny instans av[`EWSClient`](../ewsclient) baserad klass |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_1)(ExchangeVersion, string, ICredentials, WebProxy) | Initierar en ny instans av[`EWSClient`](../ewsclient) baserad klass |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_6)(string, string, string, string) | Initierar en ny instans av[`EWSClient`](../ewsclient) baserad klass |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_5)(string, string, string, WebProxy) | Initierar en ny instans av[`EWSClient`](../ewsclient) baserad klass |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_7)(string, string, string, string, WebProxy) | Initierar en ny instans av[`EWSClient`](../ewsclient) baserad klass |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient)(ExchangeVersion, bool, string, string, ICredentials, WebProxy) | Initierar en ny instans av[`EWSClient`](../ewsclient) baserad klass |
| static [GetEwsClientAsync](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclientasync)(string, ICredentials, WebProxy, CancellationToken) | Initierar en ny instans av[`EWSClient`](../ewsclient) baserad klass |

### Se även

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->