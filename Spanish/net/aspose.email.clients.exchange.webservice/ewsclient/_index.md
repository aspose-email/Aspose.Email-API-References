---
title: EWSClient
second_title: Referencia de la API de Aspose.Email para .NET
description: Proporciona acceso a MS Exchange Server mediante Exchange Web Services EWS.
type: docs
weight: 3680
url: /es/net/aspose.email.clients.exchange.webservice/ewsclient/
---
## EWSClient class

Proporciona acceso a MS Exchange Server mediante Exchange Web Services (EWS).

```csharp
public abstract class EWSClient : ExchangeClientBase
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| virtual [Credentials](../../aspose.email.clients.exchange/exchangeclientbase/credentials) { get; set; } | Obtiene o establece las credenciales |
| [LogFileName](../../aspose.email.clients.exchange/exchangeclientbase/logfilename) { get; set; } | Obtiene o establece el nombre del archivo de registro |
| virtual [MailboxUri](../../aspose.email.clients.exchange/exchangeclientbase/mailboxuri) { get; set; } | Obtiene o establece el buzón uri |
| virtual [Proxy](../../aspose.email.clients.exchange/exchangeclientbase/proxy) { get; set; } | Obtiene o establece el proxy. |
| virtual [Timeout](../../aspose.email.clients.exchange/exchangeclientbase/timeout) { get; set; } | Obtiene o establece el número de milisegundos de espera antes de que se agote el tiempo de espera de la operación. El valor predeterminado es 100 000 milisegundos (100 segundos). |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/exchangeclientbase/usedateinlogfilename) { get; set; } | Obtiene o establece el valor que indica si se debe usar la fecha en el nombre del archivo de registro. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Dispose](../../aspose.email.clients.exchange/exchangeclientbase/dispose)() | Realiza tareas definidas por la aplicación asociadas con liberar, liberar o restablecer recursos no administrados. |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_2)(string, ICredentials) | Inicializa una nueva instancia del[`EWSClient`](../ewsclient) clase basada |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_3)(string, ICredentials, WebProxy) | Inicializa una nueva instancia del[`EWSClient`](../ewsclient) clase basada |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_4)(string, string, string) | Inicializa una nueva instancia del[`EWSClient`](../ewsclient) clase basada |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_1)(ExchangeVersion, string, ICredentials, WebProxy) | Inicializa una nueva instancia del[`EWSClient`](../ewsclient) clase basada |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_6)(string, string, string, string) | Inicializa una nueva instancia del[`EWSClient`](../ewsclient) clase basada |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_5)(string, string, string, WebProxy) | Inicializa una nueva instancia del[`EWSClient`](../ewsclient) clase basada |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient_7)(string, string, string, string, WebProxy) | Inicializa una nueva instancia del[`EWSClient`](../ewsclient) clase basada |
| static [GetEWSClient](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclient#getewsclient)(ExchangeVersion, bool, string, string, ICredentials, WebProxy) | Inicializa una nueva instancia del[`EWSClient`](../ewsclient) clase basada |
| static [GetEwsClientAsync](../../aspose.email.clients.exchange.webservice/ewsclient/getewsclientasync)(string, ICredentials, WebProxy, CancellationToken) | Inicializa una nueva instancia del[`EWSClient`](../ewsclient) clase basada |

### Ver también

* class [ExchangeClientBase](../../aspose.email.clients.exchange/exchangeclientbase)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../aspose.email.clients.exchange.webservice)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->