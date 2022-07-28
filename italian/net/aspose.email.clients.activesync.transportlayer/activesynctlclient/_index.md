---
title: ActiveSyncTLClient
second_title: Aspose.Email per riferimento all'API .NET
description: Classe di base per implementazioni client ActiveSync
type: docs
weight: 950
url: /it/net/aspose.email.clients.activesync.transportlayer/activesynctlclient/
---
## ActiveSyncTLClient class

Classe di base per implementazioni client ActiveSync

```csharp
public class ActiveSyncTLClient : IBaseActiveSyncTLClient
```

## Proprietà

| Nome | Descrizione |
| --- | --- |
| virtual [AuthenticationType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/authenticationtype) { get; set; } | Ottiene o imposta il tipo di autenticazione utilizzato dal client ActiveSync. |
| virtual [AutodiscoverUri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscoveruri) { get; set; } | Ottiene o imposta il servizio di individuazione automatica uri |
| virtual [Credentials](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/credentials) { get; } | Credenziali utente per il server Exchange |
| virtual [DeviceID](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/deviceid) { get; set; } | Un GUID che identifica il dispositivo. L'ID dispositivo è specificato dalla parte della regola ABNF specifica ID dispositivo del valore della query in testo normale. Il valore, rappresentato dalla regola ABNF device-id, è una stringa che specifica il dispositivo. Ogni dispositivo DEVE avere una stringa ID dispositivo univoca. Ogni richiesta dal dispositivo DEVE includere la stessa stringa ID dispositivo. |
| virtual [DeviceType](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/devicetype) { get; set; } | Il tipo di dispositivo è specificato dalla parte della regola ABNF specifica per tipo di dispositivo del valore della query di testo normale. Il valore, rappresentato dalla regola ABNF del tipo di dispositivo, è qualsiasi stringa che specifica un tipo di dispositivo. "SP" specifica uno SmartPhone e "PPC" specifica un PocketPC. Altri dispositivi client inviano stringhe univoche per il loro tipo di dispositivo specifico. Ogni richiesta da un dispositivo client DEVE includere la stessa stringa del tipo di dispositivo. |
| virtual [PolicyState](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/policystate) { get; set; } | Un numero intero senza segno che indica lo stato delle impostazioni dei criteri sul dispositivo client, come specificato nella sezione [MS-ASPROV] 2.2.2.41. |
| virtual [Proxy](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/proxy) { get; set; } | Ottiene o imposta il proxy. |
| virtual [SupportedServerCommands](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedservercommands) { get; } | Ottiene le versioni dei comandi ActiveSync supportati |
| virtual [SupportedServerProtocols](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/supportedserverprotocols) { get; } | Ottiene le versioni dei protocolli ActiveSync supportati |
| virtual [Timeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/timeout) { get; set; } | Ottiene o imposta il numero di millisecondi di attesa prima del timeout dell'operazione. Il valore predefinito è 100.000 millisecondi (100 secondi). |
| virtual [Uri](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/uri) { get; } | Ottiene l'URL del servizio ActiveSync |
| virtual [UserAgent](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/useragent) { get; set; } | Il campo dell'intestazione della richiesta dell'agente utente contiene informazioni sull'agente utente che ha originato la richiesta. Questo è per scopi statistici, il tracciamento delle violazioni del protocollo e il riconoscimento automatico degli user agent per il bene di personalizzare le risposte per evitare particolari limitazioni degli user agent. Gli agenti utente DEVONO includere questo campo con le richieste. Il campo può contenere più token di prodotto (sezione 3.8) e commenti che identificano l'agente e gli eventuali sottoprodotti che costituiscono una parte significativa dell'agente utente. Per convenzione, i token del prodotto sono elencati in ordine di significato per l'identificazione dell'applicazione. Esempio: User-Agent: CERN-LineMode/2.15 libwww/2.17b3 |
| virtual [Version](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/version) { get; } | Ottiene la versione del protocollo utilizzato nel client ActiveSync. |
| static [DefaultTimeout](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/defaulttimeout) { get; set; } | Ottiene o imposta il valore di timeout predefinito per le istanze client ActiveSync Il valore predefinito è 100.000 millisecondi (100 secondi). |

## Metodi

| Nome | Descrizione |
| --- | --- |
| virtual [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string) | Il comando di individuazione automatica facilita l'individuazione delle informazioni di configurazione dell'account principale utilizzando l'indirizzo SMTP (Simple Mail Transfer Protocol) dell'utente come input principale. |
| [Dispose](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/dispose)() | Esegue attività associate alla liberazione, al rilascio o al ripristino di risorse non gestite. |
| static [Autodiscover](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/autodiscover)(string, NetworkCredential, string) | Il comando di individuazione automatica facilita l'individuazione delle informazioni di configurazione dell'account principale utilizzando l'indirizzo SMTP (Simple Mail Transfer Protocol) dell'utente come input principale. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance)(string, NetworkCredential) | Ottiene un'istanza del client ActiveSync La versione del protocollo ActiveSync viene selezionata automaticamente in base alla risposta del server. |
| static [GetInstance](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getinstance#getinstance_1)(string, NetworkCredential, ASProtocolVersions) | Ottiene un'istanza del client ActiveSync |
| static [GetOptions](../../aspose.email.clients.activesync.transportlayer/activesynctlclient/getoptions)(string, NetworkCredential, out string[], out string[]) | Il metodo statico GetOptions viene utilizzato per scoprire quali versioni di protocollo sono supportate e quali comandi di protocollo sono supportati sul server. Il client utilizza il metodo statico GetOptions per determinare se il server supporta le stesse versioni del protocollo supportate dal client. |

### Guarda anche

* interface [IBaseActiveSyncTLClient](../ibaseactivesynctlclient)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
