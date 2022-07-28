---
title: SyncCollectionRequest
second_title: Aspose.Email per riferimento all'API .NET
description: La classe contiene comandi e opzioni che si applicano a una particolare raccolta.
type: docs
weight: 2190
url: /it/net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/
---
## SyncCollectionRequest class

La classe contiene comandi e opzioni che si applicano a una particolare raccolta.

```csharp
public class SyncCollectionRequest
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SyncCollectionRequest](synccollectionrequest)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/collectionid) { get; set; } | Specifica l'ID server della cartella da sincronizzare. |
| [Commands](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/commands) { get; set; } | Contiene le operazioni che si applicano a una raccolta. Le operazioni disponibili sono Aggiungi, Elimina, Modifica, Recupera e Cancellazione graduale. |
| [ConversationMode](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/conversationmode) { get; set; } | Specifica se includere gli elementi inclusi nella modalità di conversazione nei risultati della risposta di sincronizzazione. L'impostazione del valore dell'elemento ConversationMode su TRUE comporta il recupero di tutti i messaggi di posta elettronica che corrispondono alle conversazioni ricevute entro il filtro della data specificato. Tuttavia, sebbene il corpo delle e-mail al di fuori di quel filtro basato sul tempo non verrà recuperato, verranno recuperate le anteprime di testo se le anteprime sono state richieste. L'impostazione del valore dell'elemento ConversationMode su FALSE in una richiesta di sincronizzazione comporta la sincronizzazione di elementi che soddisfano i criteri del valore dell'elemento FilterType (sezione 2.2.3.64). L'impostazione del valore dell'elemento ConversationMode su TRUE espande il set di risultati per includere anche tutti gli elementi con valori email2:ConversationId ([MS-AEMAIL] sezione 2.2.2.14) identici a quelli nel set di risultati FilterType. Il valore dell'elemento ConversationMode non ha alcun impatto sugli elementi al di fuori della raccolta specificata dall'elemento CollectionId (sezione 2.2.3.30.5); il set di risultati è sempre limitato agli elementi nella raccolta specificata. Il valore dell'elemento ConversationMode limita o espande solo i risultati determinati dal valore dell'elemento FilterType. |
| [DeletesAsMoves](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/deletesasmoves) { get; set; } | Richieste che indicano che tutti gli elementi eliminati DOVREBBE essere spostati nella cartella Posta eliminata. Se l'elemento DeletesAsMoves è impostato su false, l'eliminazione è permanente. Se il client desidera eliminare definitivamente gli elementi, la richiesta DEVE includere l'elemento DeletesAsMoves con un valore di FALSE. Un valore TRUE, che è l'impostazione predefinita, indica che tutti gli elementi eliminati vengono spostati nella cartella Posta eliminata. |
| [GetChanges](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/getchanges) { get; set; } | Richiede che il server includa nella sua risposta tutte le modifiche in sospeso alla raccolta specificata dall'elemento ServerId (sezione 2.2.3.151.6). Se sono state apportate modifiche dall'ultima sincronizzazione, la risposta del server include un elemento Commands (sezione 2.2.3.32) che contiene aggiunte, eliminazioni e modifiche. Se il client non desidera che le modifiche al server vengano restituite, la richiesta DEVE includere l'elemento GetChanges con un valore FALSE. Un valore TRUE indica che il client desidera che le modifiche al server vengano restituite. Viene assunto un valore TRUE quando l'elemento GetChanges è vuoto. Quando l'elemento GetChanges non è presente nella richiesta, il comportamento dipende dal valore dell'elemento SyncKey, come specificato nella sezione 2.2.3.166.4. Se l'elemento SyncKey ha un valore pari a 0, la richiesta viene gestita come se l'elemento GetChanges fosse impostato su FALSE. Se l'elemento SyncKey ha un valore diverso da zero, la richiesta viene gestita come se l'elemento GetChanges fosse impostato al VERO. |
| [Options](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/options) { get; } | Specifica le opzioni che controllano determinati aspetti di come viene eseguita la sincronizzazione. Numero consentito 0...2. Le opzioni di sincronizzazione consentono al client di specificare il troncamento e le impostazioni del contenuto. Queste impostazioni sono incapsulate all'interno di un elemento figlio airsyncbase:BodyPreference, come specificato nella sezione [MS-ASAIRS] 2.2.2.7. Poiché le opzioni di sincronizzazione sono specificate su una raccolta, il client può specificare un valore di elemento airsyncbase:BodyPreference univoco per ciascuna raccolta che viene sincronizzata. Per maggiori dettagli sull'elemento airsyncbase:BodyPreference, vedere [MS-ASAIRS] sezione 2.2. 2.7. Il server conserva il blocco Opzioni tra le richieste, utilizzando un concetto denominato "opzioni permanenti". Se il blocco Opzioni non è incluso in una richiesta, viene utilizzato il blocco Opzioni precedente. Ogni volta che il client specifica nuove opzioni includendo un blocco Opzioni nella richiesta, il server DEVE sostituire il blocco Opzioni originale con il nuovo blocco Opzioni. Se due elementi Opzioni sono inclusi in una singola richiesta di comando di sincronizzazione, uno degli elementi Opzioni DEVE specifica le opzioni di sincronizzazione per la classe SMS, mentre l'altro elemento Opzioni specifica le opzioni per la classe predefinita della cartella data. |
| [Supported](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/supported) { get; } | Gli elementi della classe Contact e della classe Calendar che non sono fantasma possono essere inclusi come elementi figlio dell'elemento Supported. Per i dettagli sull'uso delle proprietà fantasma, vedere la sezione 2.2.3.154. |
| [SyncKey](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/synckey) { get; set; } | Il valore SyncKey viene utilizzato dal server per contrassegnare lo stato di sincronizzazione di una raccolta. Una chiave di sincronizzazione di valore 0 (zero) inizializza lo stato di sincronizzazione sul server e provoca una sincronizzazione completa della raccolta. |
| [WindowSize](../../aspose.email.clients.activesync.transportlayer/synccollectionrequest/windowsize) { get; set; } | Specifica un numero massimo di elementi modificati in una raccolta o una richiesta che DOVREBBE essere inclusa nella risposta di sincronizzazione. Se WindowSize non è definito, il server si comporta come se fosse stato inviato un elemento WindowSize con un valore di 100. Il server interpreta il valore 0 (zero) e i valori superiori a 512 come 512. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
