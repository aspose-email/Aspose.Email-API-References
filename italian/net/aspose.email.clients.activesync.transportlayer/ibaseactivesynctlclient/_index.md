---
title: IBaseActiveSyncTLClient
second_title: Aspose.Email per riferimento all'API .NET
description: Interfaccia client ActiveSync di base
type: docs
weight: 1320
url: /it/net/aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/
---
## IBaseActiveSyncTLClient interface

Interfaccia client ActiveSync di base

```csharp
public interface IBaseActiveSyncTLClient : IDisposable
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/authenticationtype) { get; set; } | Ottiene o imposta il tipo di autenticazione utilizzato dal client ActiveSync. |
| [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/autodiscoveruri) { get; set; } | Ottiene l'individuazione automatica uri |
| [Credentials](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/credentials) { get; } | Credenziali utente per il server Exchange |
| [DeviceID](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/deviceid) { get; set; } | Un GUID che identifica il dispositivo. L'ID dispositivo è specificato dalla parte della regola ABNF specifica ID dispositivo del valore della query in testo normale. Il valore, rappresentato dalla regola ABNF device-id, è una stringa che specifica il dispositivo. Ogni dispositivo DEVE avere una stringa ID dispositivo univoca. Ogni richiesta dal dispositivo DEVE includere la stessa stringa ID dispositivo. |
| [DeviceType](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/devicetype) { get; set; } | Il tipo di dispositivo è specificato dalla parte della regola ABNF specifica per tipo di dispositivo del valore della query di testo normale. Il valore, rappresentato dalla regola ABNF del tipo di dispositivo, è qualsiasi stringa che specifica un tipo di dispositivo. "SP" specifica uno SmartPhone e "PPC" specifica un PocketPC. Altri dispositivi client inviano stringhe univoche per il loro tipo di dispositivo specifico. Ogni richiesta da un dispositivo client DEVE includere la stessa stringa del tipo di dispositivo. |
| [PolicyState](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/policystate) { get; set; } | Un numero intero senza segno che indica lo stato delle impostazioni dei criteri sul dispositivo client, come specificato nella sezione [MS-ASPROV] 2.2.2.41. |
| [Proxy](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/proxy) { get; set; } | Ottiene o imposta il proxy. |
| [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/supportedservercommands) { get; } | Ottiene le versioni dei comandi ActiveSync che sono supportati dal server |
| [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/supportedserverprotocols) { get; } | Ottiene le versioni dei protocolli ActiveSync che sono supportati dal server |
| [Timeout](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/timeout) { get; set; } | Ottiene o imposta il numero di millisecondi di attesa prima del timeout dell'operazione. Il valore predefinito è 100.000 millisecondi (100 secondi). |
| [Uri](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/uri) { get; } | Ottiene il server uri |
| [UserAgent](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/useragent) { get; set; } | Il campo dell'intestazione della richiesta dell'agente utente contiene informazioni sull'agente utente che ha originato la richiesta. Questo è per scopi statistici, il tracciamento delle violazioni del protocollo e il riconoscimento automatico degli user agent per il bene di personalizzare le risposte per evitare particolari limitazioni degli user agent. Gli agenti utente DEVONO includere questo campo con le richieste. Il campo può contenere più token di prodotto (sezione 3.8) e commenti che identificano l'agente e gli eventuali sottoprodotti che costituiscono una parte significativa dell'agente utente. Per convenzione, i token del prodotto sono elencati in ordine di significato per l'identificazione dell'applicazione. Esempio: User-Agent: CERN-LineMode/2.15 libwww/2.17b3 |
| [Version](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/version) { get; } | Ottiene la versione del protocollo utilizzato nel client ActiveSync. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Autodiscover](../../aspose.email.clients.activesync.transportlayer/ibaseactivesynctlclient/autodiscover)(string) | Il comando di individuazione automatica facilita l'individuazione delle informazioni di configurazione dell'account principale utilizzando l'indirizzo SMTP (Simple Mail Transfer Protocol) dell'utente come input principale. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
