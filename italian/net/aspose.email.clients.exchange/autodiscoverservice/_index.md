---
title: AutodiscoverService
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta unassociazione al servizio di individuazione automatica di Exchange.
type: docs
weight: 3090
url: /it/net/aspose.email.clients.exchange/autodiscoverservice/
---
## AutodiscoverService class

Rappresenta un'associazione al servizio di individuazione automatica di Exchange.

```csharp
public sealed class AutodiscoverService : AutodiscoverServiceBase
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [AutodiscoverService](autodiscoverservice#constructor)() | Inizializza una nuova istanza di[`AutodiscoverService`](../autodiscoverservice) classe. |
| [AutodiscoverService](autodiscoverservice#constructor_1)(ExchangeVersion) | Inizializza una nuova istanza di[`AutodiscoverService`](../autodiscoverservice) classe. |
| [AutodiscoverService](autodiscoverservice#constructor_2)(string) | Inizializza una nuova istanza di[`AutodiscoverService`](../autodiscoverservice) classe. |
| [AutodiscoverService](autodiscoverservice#constructor_4)(Uri) | Inizializza una nuova istanza di[`AutodiscoverService`](../autodiscoverservice) classe. |
| [AutodiscoverService](autodiscoverservice#constructor_3)(string, ExchangeVersion) | Inizializza una nuova istanza di[`AutodiscoverService`](../autodiscoverservice) classe. |
| [AutodiscoverService](autodiscoverservice#constructor_5)(Uri, ExchangeVersion) | Inizializza una nuova istanza di[`AutodiscoverService`](../autodiscoverservice) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AcceptGzipEncoding](../../aspose.email.clients.exchange/autodiscoverservicebase/acceptgzipencoding) { get; set; } | Ottiene o imposta un valore che indica se la codifica della compressione GZip deve essere accettata. |
| [ClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/clientrequestid) { get; set; } | Ottiene o imposta l'ID richiesta per la richiesta. |
| [ConnectionGroupName](../../aspose.email.clients.exchange/autodiscoverservicebase/connectiongroupname) { get; set; } | Ottiene o imposta il nome del gruppo di connessione per la richiesta. |
| [CookieContainer](../../aspose.email.clients.exchange/autodiscoverservicebase/cookiecontainer) { get; set; } | Ottiene o imposta il contenitore dei cookie. |
| [Credentials](../../aspose.email.clients.exchange/autodiscoverservicebase/credentials) { get; set; } | Ottiene o imposta le credenziali utilizzate per l'autenticazione con i servizi Web di Exchange. L'impostazione della proprietà Credentials imposta automaticamente UseDefaultCredentials su false. |
| [Domain](../../aspose.email.clients.exchange/autodiscoverservice/domain) { get; set; } | Ottiene o imposta il dominio a cui è associato questo servizio. Quando questa proprietà è impostata, il nome dominio viene utilizzato per determinare automaticamente l'URL del servizio di individuazione automatica. |
| [EnableScpLookup](../../aspose.email.clients.exchange/autodiscoverservice/enablescplookup) { get; set; } | Ottiene o imposta un valore che indica se AutodiscoverService deve eseguire la ricerca di record SCP (ServiceConnectionPoint) durante la determinazione di l'URL del servizio di individuazione automatica. |
| [HttpHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpheaders) { get; } | Ottiene una raccolta di intestazioni HTTP che verranno inviate con ogni richiesta a EWS. |
| [HttpResponseHeaders](../../aspose.email.clients.exchange/autodiscoverservicebase/httpresponseheaders) { get; } | Ottiene una raccolta di intestazioni HTTP dall'ultima risposta. |
| [IsExternal](../../aspose.email.clients.exchange/autodiscoverservice/isexternal) { get; } | Ottiene un valore che indica se il servizio di individuazione automatica a cui punta l'URL è interno (all'interno della rete aziendale) o esterno (esterno alla rete aziendale). |
| [KeepAlive](../../aspose.email.clients.exchange/autodiscoverservicebase/keepalive) { get; set; } | Ottiene o imposta se la richiesta alla risorsa Internet deve contenere un'intestazione HTTP di connessione con il valore Keep-alive |
| [LogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/logfilename) { get; set; } | Ottiene o imposta il nome del file di registro |
| [PreAuthenticate](../../aspose.email.clients.exchange/autodiscoverservicebase/preauthenticate) { get; set; } | Ottiene o imposta un valore che indica se deve essere eseguita la preautenticazione HTTP. |
| [RedirectionUrlValidationCallback](../../aspose.email.clients.exchange/autodiscoverservice/redirectionurlvalidationcallback) { get; set; } | Ottiene o imposta la richiamata di convalida dell'URL di reindirizzamento. |
| [RequestedServerVersion](../../aspose.email.clients.exchange/autodiscoverservicebase/requestedserverversion) { get; } | Ottiene la versione del server richiesta. |
| [ReturnClientRequestId](../../aspose.email.clients.exchange/autodiscoverservicebase/returnclientrequestid) { get; set; } | Ottiene o imposta un flag per indicare se il client richiede che il lato server restituisca l'id della richiesta. |
| [SendClientLatencies](../../aspose.email.clients.exchange/autodiscoverservicebase/sendclientlatencies) { get; set; } | Ottiene o imposta un valore che indica se le informazioni sulla latenza del client vengono inviate al server. |
| [ServerInfo](../../aspose.email.clients.exchange/autodiscoverservicebase/serverinfo) { get; } | Ottiene le informazioni associate al server che ha elaborato l'ultima richiesta. Sarà nullo se nessuna richiesta è stata elaborata. |
| [Timeout](../../aspose.email.clients.exchange/autodiscoverservicebase/timeout) { get; set; } | Ottiene o imposta il timeout utilizzato quando si inviano richieste HTTP e quando si ricevono risposte HTTP, in millisecondi. Il valore predefinito è 100000. |
| [Url](../../aspose.email.clients.exchange/autodiscoverservice/url) { get; set; } | Ottiene o imposta l'URL a cui è associato questo servizio. |
| [UseDateInLogFileName](../../aspose.email.clients.exchange/autodiscoverservicebase/usedateinlogfilename) { get; set; } | Ottiene o imposta un valore che indica se la data deve essere utilizzata nel nome del file di registro. |
| [UseDefaultCredentials](../../aspose.email.clients.exchange/autodiscoverservicebase/usedefaultcredentials) { get; set; } | Ottiene o imposta un valore che indica se le credenziali dell'utente attualmente connesso a Windows devono essere utilizzate per autenticarsi con i servizi Web di Exchange. L'impostazione di UseDefaultCredentials su true imposta automaticamente la proprietà Credentials su null. |
| [UserAgent](../../aspose.email.clients.exchange/autodiscoverservicebase/useragent) { get; set; } | Ottiene o imposta il programma utente. |
| [WebProxy](../../aspose.email.clients.exchange/autodiscoverservicebase/webproxy) { get; set; } | Ottiene o imposta il proxy Web da utilizzare quando si inviano richieste a EWS. Impostare questa proprietà su null per utilizzare il proxy Web predefinito. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetUserSettings](../../aspose.email.clients.exchange/autodiscoverservice/getusersettings)(string, params UserSettingName[]) | Recupera le impostazioni specificate per un singolo indirizzo SMTP. |
| [GetUsersSettings](../../aspose.email.clients.exchange/autodiscoverservice/getuserssettings)(IEnumerable&lt;string&gt;, params UserSettingName[]) | Recupera le impostazioni specificate per un insieme di utenti. |

### Guarda anche

* class [AutodiscoverServiceBase](../autodiscoverservicebase)
* spazio dei nomi [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
