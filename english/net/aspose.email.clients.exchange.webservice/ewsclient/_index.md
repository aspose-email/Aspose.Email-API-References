---
title: Class EWSClient
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.WebService.EWSClient class. Provides access to MS Exchange Server by using Exchange Web Services EWS
type: docs
weight: 3680
url: /net/aspose.email.clients.exchange.webservice/ewsclient/
---
## EWSClient class

Provides access to MS Exchange Server by using Exchange Web Services (EWS).

```csharp
public abstract class EWSClient : ExchangeClientBase
```

## Properties

| Name | Description |
| --- | --- |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials/) { get; set; } | Gets or sets the credentials |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename/) { get; set; } | Gets or sets log file name |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri/) { get; set; } | Gets or sets the mailbox uri |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy/) { get; set; } | Gets or sets the proxy. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout/) { get; set; } | Gets or sets the number of milliseconds to wait before the operation times out. The default value is 100,000 milliseconds (100 seconds). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename/) { get; set; } | Gets or sets value which indicates if date has to be used in log file name. |

## Methods

| Name | Description |
| --- | --- |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose/)() | Performs application-defined tasks associated with freeing, releasing, or resetting unmanaged resources. |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient/#getewsclient_2)(string, ICredentials) | Initializes a new instance of the `EWSClient` based class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient/#getewsclient_3)(string, ICredentials, WebProxy) | Initializes a new instance of the `EWSClient` based class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient/#getewsclient_4)(string, string, string) | Initializes a new instance of the `EWSClient` based class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient/#getewsclient_1)(ExchangeVersion, string, ICredentials, WebProxy) | Initializes a new instance of the `EWSClient` based class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient/#getewsclient_6)(string, string, string, string) | Initializes a new instance of the `EWSClient` based class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient/#getewsclient_5)(string, string, string, WebProxy) | Initializes a new instance of the `EWSClient` based class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient/#getewsclient_7)(string, string, string, string, WebProxy) | Initializes a new instance of the `EWSClient` based class |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient/#getewsclient)(ExchangeVersion, bool, string, string, ICredentials, WebProxy) | Initializes a new instance of the `EWSClient` based class |
| static [GetEwsClientAsync](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclientasync/)(string, ICredentials, WebProxy, CancellationToken) | Initializes a new instance of the `EWSClient` based class |

### See Also

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase/)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice/)
* assembly [Aspose.Email](../../)


