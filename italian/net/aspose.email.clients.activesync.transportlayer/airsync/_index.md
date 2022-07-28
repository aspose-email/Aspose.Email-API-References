---
title: AirSync
second_title: Aspose.Email per riferimento all'API .NET
description: Spazio dei nomi AirSync del protocollo ActiveSync
type: docs
weight: 960
url: /it/net/aspose.email.clients.activesync.transportlayer/airsync/
---
## AirSync enumeration

Spazio dei nomi AirSync del protocollo ActiveSync

```csharp
public enum AirSync
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| Sync | `5` | L'elemento Sync è un elemento obbligatorio nelle richieste e risposte dei comandi Sync che identifica il corpo del POST HTTP come contenente un comando Sync (sezione 2.2.2.19). È l'elemento di primo livello nel flusso XML. |
| Responses | `6` | Contiene le risposte alle operazioni elaborate dal server. |
| Add | `7` | Crea un nuovo oggetto in una raccolta sul client o sul server. |
| Change | `8` | Modifica le proprietà di un oggetto esistente sul dispositivo client o sul server. |
| Delete | `9` | Elimina un oggetto sul dispositivo client o sul server. L'oggetto è identificato dal suo elemento ServerId. |
| Fetch | `10` | Utilizzato per richiedere i dati dell'applicazione di un elemento che è stato troncato in una risposta di sincronizzazione dal server. |
| SyncKey | `11` | Contiene un valore utilizzato dal server per contrassegnare lo stato di sincronizzazione di una raccolta. |
| ClientId | `12` | Contiene un identificatore univoco (in genere un numero intero) generato dal client per identificare temporaneamente un nuovo oggetto che viene creato utilizzando l'elemento Add. |
| ServerId | `13` | Rappresenta un identificatore univoco che viene assegnato dal server a ciascun oggetto sincronizzabile. |
| Status | `14` | Indica il motivo del fallimento di una richiesta di comando. |
| Collection | `15` | Contiene comandi e opzioni che si applicano a una particolare raccolta. |
| Class | `16` | Identifica la classe dell'elemento da aggiungere alla raccolta. |
| CollectionId | `18` | Specifica l'ID server della cartella da sincronizzare. |
| GetChanges | `19` | Richiede che il server includa nella sua risposta tutte le modifiche in sospeso alla raccolta specificata dall'elemento ServerId (sezione 2.2.3.151.6). |
| MoreAvailable | `20` | Indica che sono presenti più modifiche rispetto al numero richiesto nell'elemento WindowSize (sezione 2.2.3.183). |
| WindowSize | `21` | Specifica un numero massimo di elementi modificati in una raccolta o una richiesta che DOVREBBE essere inclusa nella risposta di sincronizzazione. |
| Commands | `22` | Contiene le operazioni che si applicano a una raccolta. |
| Options | `23` | Contiene elementi che controllano determinati aspetti di come viene eseguita la sincronizzazione. |
| FilterType | `24` | Specifica una finestra temporale facoltativa per gli oggetti inviati dal server al client. Si applica alle raccolte di e-mail e calendario. |
| Conflict | `27` | Specifica come risolvere il conflitto che si verifica quando un oggetto è stato modificato sia sul client che sul server. |
| Collections | `28` | Funge da contenitore per l'elemento Collection. |
| ApplicationData | `29` | Contiene i dati per un oggetto particolare, come un contatto, un messaggio e-mail, un appuntamento del calendario o un elemento dell'attività. Può essere utilizzato per modificare elementi, aggiungere elementi o recuperare elementi sul dispositivo client o sul server. |
| DeletesAsMoves | `30` | Indica che tutti gli elementi eliminati DEVONO essere spostati nella cartella Posta eliminata. |
| Supported | `32` | Specifica quali elementi di contatto e calendario in una richiesta di sincronizzazione sono gestiti dal client. |
| SoftDelete | `33` | Elimina un oggetto dal client quando non rientra nei risultati FilterType (sezione 2.2.3.64.2) o non è più incluso nelle istruzioni SyncOptions (sezione 2.2.3.115.5). |
| MIMESupport | `34` | Abilita il supporto MIME per gli elementi di posta elettronica inviati dal server al client. |
| MIMETruncation | `35` | Specifica se i dati MIME dell'elemento e-mail DEVONO essere troncati quando viene inviato dal server al client. |
| Wait | `36` | Specifica il numero di minuti che il server DOVREBBE ritardare una risposta se non vengono aggiunti nuovi elementi alle cartelle incluse, come specificato nella sezione 3.1.5.4. |
| Limit | `37` | Specifica il numero massimo di raccolte che possono essere sincronizzate o il valore massimo/minimo consentito per l'intervallo di attesa (sezione 2.2.3.182) o l'intervallo HeartbeatInterval (sezione 2.2.3.79.2). |
| Partial | `38` | Indica al server che il client ha inviato un elenco parziale di raccolte, nel qual caso il server ottiene il resto delle raccolte dalla sua cache. |
| ConversationMode | `39` | Specifica se includere elementi inclusi nella modalità di conversazione nei risultati della risposta di sincronizzazione. |
| MaxItems | `40` | Specifica il numero massimo di destinatari (ovvero i primi N destinatari più utilizzati) da mantenere sincronizzati dalla cache delle informazioni sui destinatari. |
| HeartbeatInterval | `41` | Specifica il numero di secondi in cui il server DOVREBBE ritardare una risposta se non vengono aggiunti nuovi elementi alle cartelle incluse, come specificato nella sezione 3.1.5.4. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
