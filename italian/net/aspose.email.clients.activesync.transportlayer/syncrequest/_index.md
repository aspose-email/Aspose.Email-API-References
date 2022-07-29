---
title: SyncRequest
second_title: Aspose.Email per riferimento all'API .NET
description: Contiene i parametri della richiesta di sincronizzazione
type: docs
weight: 2280
url: /it/net/aspose.email.clients.activesync.transportlayer/syncrequest/
---
## SyncRequest class

Contiene i parametri della richiesta di sincronizzazione

```csharp
public class SyncRequest
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SyncRequest](syncrequest)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Collections](../../aspose.email.clients.activesync.transportlayer/syncrequest/collections) { get; } | Contiene un elenco di oggetti con comandi e opzioni che si applicano a una particolare raccolta. |
| [HeartbeatInterval](../../aspose.email.clients.activesync.transportlayer/syncrequest/heartbeatinterval) { get; set; } | Specifica il numero di secondi che il server DOVREBBE ritardare una risposta se non vengono aggiunti nuovi elementi alle cartelle incluse. I valori validi per HeartbeatInterval sono compresi tra 60 e 3540 secondi (59 minuti). Quando il client richiede un intervallo che non rientra nell'intervallo accettabile, il server invierà una risposta che include un valore Status di 14 e un elemento Limit. In una richiesta di comando di sincronizzazione possono essere inclusi HeartbeatInterval o Wait, ma non Entrambi. Se sono inclusi entrambi gli elementi, la risposta del server conterrà un valore di stato di 4. |
| [Partial](../../aspose.email.clients.activesync.transportlayer/syncrequest/partial) { get; set; } | Indica al server che il client ha inviato un elenco parziale di raccolte, nel qual caso il server ottiene il resto delle raccolte dalla sua cache. |
| [Wait](../../aspose.email.clients.activesync.transportlayer/syncrequest/wait) { get; set; } | Specifica il numero di minuti in cui il server DOVREBBE ritardare una risposta se non vengono aggiunti nuovi elementi alle cartelle incluse. I valori validi per Wait sono compresi tra 1 e 59. Quando il client richiede un intervallo di attesa che non rientra nell'intervallo accettabile, il server invierà una risposta che include un valore Status di 14 e un Limit. In una richiesta di comando di sincronizzazione possono essere inclusi Wait o HeartbeatInterval, ma non entrambi. Se sono inclusi entrambi, la risposta del server conterrà un valore di stato di 4. |
| [WindowSize](../../aspose.email.clients.activesync.transportlayer/syncrequest/windowsize) { get; set; } | Specifica un numero massimo di elementi modificati in una raccolta o in una richiesta che DOVREBBE essere inclusa nella risposta di sincronizzazione. Il valore massimo per WindowSize è 512. Tuttavia, se WindowSize è impostato su 512, il server può inviare messaggi di risposta di sincronizzazione che contengono meno di 512 aggiornamenti. Se il server non invia tutti gli aggiornamenti in un unico messaggio, il messaggio di risposta Sync contiene MoreAvailable, che indica che sono presenti aggiornamenti aggiuntivi sul server da scaricare sul client. WindowSize compare solo nelle richieste inviate al server dal client. Se WindowSize viene omesso, il server si comporta come se fosse inviato un elemento WindowSize con un valore di 100. Il server interpreta il valore 0 (zero) e i valori superiori a 512 come 512. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->