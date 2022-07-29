---
title: SearchOptions
second_title: Aspose.Email per riferimento all'API .NET
description: Contiene le opzioni di ricerca. UserName e Password possono essere inviati nella richiesta solo dopo aver ricevuto un valore di Stato pari a 14. Il server richiede queste credenziali per accedere alle risorse richieste. Il client DEVE inviare questi solo su una connessione sicura o affidabile e solo in risposta a un valore di stato di 14. Le opzioni supportate variano a seconda del negozio che viene cercato. La tabella seguente elenca le opzioni valide per ciascun negozio. GAL Intervallo Nome utente Password Immagine Cassetta postale Intervallo DeepTraversal RebuildResults BodyPreference BodyPartPreference RightsManagementSupport DocumentLibrary Range UserName Password La BodyPartPreference è valida solo nella ricerca richieste di comando che includono un ConversationId.
type: docs
weight: 1950
url: /it/net/aspose.email.clients.activesync.transportlayer/searchoptions/
---
## SearchOptions class

Contiene le opzioni di ricerca. UserName e Password possono essere inviati nella richiesta solo dopo aver ricevuto un valore di Stato pari a 14. Il server richiede queste credenziali per accedere alle risorse richieste. Il client DEVE inviare questi solo su una connessione sicura o affidabile e solo in risposta a un valore di stato di 14. Le opzioni supportate variano a seconda del negozio che viene cercato. La tabella seguente elenca le opzioni valide per ciascun negozio. GAL: Intervallo, Nome utente, Password, Immagine Cassetta postale: Intervallo, DeepTraversal, RebuildResults, BodyPreference, BodyPartPreference, RightsManagementSupport DocumentLibrary: Range, UserName, Password La BodyPartPreference è valida solo nella ricerca richieste di comando che includono un ConversationId.

```csharp
public class SearchOptions
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SearchOptions](searchoptions)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BodyPartPreference](../../aspose.email.clients.activesync.transportlayer/searchoptions/bodypartpreference) { get; } | Contiene informazioni sulle preferenze relative al tipo e alla dimensione delle informazioni restituite dalla ricerca, sincronizzazione o recupero di una parte del messaggio. |
| [BodyPreference](../../aspose.email.clients.activesync.transportlayer/searchoptions/bodypreference) { get; } | Contiene informazioni sulle preferenze relative al tipo e alla dimensione delle informazioni restituite dalla ricerca, sincronizzazione o recupero. |
| [DeepTraversal](../../aspose.email.clients.activesync.transportlayer/searchoptions/deeptraversal) { get; set; } | Indica che il client desidera che il server cerchi in tutte le sottocartelle le cartelle specificate nella query. |
| [MIMESupport](../../aspose.email.clients.activesync.transportlayer/searchoptions/mimesupport) { get; set; } | Abilita il supporto MIME per gli elementi e-mail che vengono inviati dal server al client. Se l'elemento airsync:MIMESupport è impostato su 'SendForSecureMIMEonly' (1) o 'SendForAll' (2) nella richiesta di ricerca: - La proprietà di l'airsyncbase:BodyPreference, il Tipo, DOVREBBE essere incluso nella richiesta di ricerca, contenente un valore di 'MIME' (4) per informare il server che il dispositivo può leggere il MIME BLOB. - La risposta dal server DEVE includere il airsyncbase:Body, che è un figlio di Properties. Il airsyncbase:Body DEVE contenere le seguenti proprietà in una risposta di ricerca S/MIME: - Il airsyncbase:Type con un valore di 'MIME' (4) per informare il dispositivo che i dati sono un MIME BLOB. - Il airsyncbase :EstimatedDataSize per specificare la dimensione totale approssimativa dei dati. - Airsyncbase:troncato per indicare se il MIME BLOB è troncato. - Airsyncbase:Data che contiene il MIME BLOB completo. |
| [Password](../../aspose.email.clients.activesync.transportlayer/searchoptions/password) { get; set; } | Specifica la password per il nome utente specificato. Il valore della Password ha una lunghezza massima di 100 caratteri. |
| [Picture](../../aspose.email.clients.activesync.transportlayer/searchoptions/picture) { get; set; } | Contiene i dati relativi alla richiesta di foto. L'immagine non è supportata quando la versione del protocollo è 12.1 o 14.0. |
| [Range](../../aspose.email.clients.activesync.transportlayer/searchoptions/range) { get; set; } | Specifica il numero massimo di voci corrispondenti da restituire. Il formato del valore dell'elemento Intervallo è sotto forma di identificatore di indice in base zero, formato con uno zero, un trattino e un altro valore numerico: "mn". La m indica l'indice più basso di un array in base zero che conterrebbe gli elementi. Il n indica l'indice più alto di una matrice in base zero che conterrebbe gli elementi. Ad esempio, un valore dell'elemento Intervallo di 0–9 indica 10 elementi e 0–10 indica 11 elementi. Un valore dell'elemento Intervallo di 0–0 indica 1 elemento. Se Intervallo è nullo, viene utilizzato il valore Intervallo predefinito per ogni tipo di negozio. La tabella seguente identifica i valori di intervallo predefiniti e i risultati massimi restituiti per ogni tipo di archivio: Cassetta postale - Valore intervallo predefinito: 0-99 - Risultati massimi restituiti: 100 DocumentLibrary - Valore intervallo predefinito: 0-999 - Risultati massimi : 1000 GAL - Valore dell'intervallo predefinito: 0-99 - Risultati massimi restituiti: 100 Se il valore dell'intervallo specificato nella richiesta supera il valore dell'intervallo predefinito, viene restituito un valore di stato pari a 12 per indicare che l'intervallo massimo è stato superato. Nella risposta al comando di ricerca, la proprietà Totale indica una stima del numero totale di voci che corrispondono al valore della query. I risultati della ricerca vengono archiviati in una cartella di ricerca sul server. In questo modo, quando un client torna con la stessa query ma un nuovo intervallo di righe, le righe vengono estratte dal set di risultati attualmente archiviato nella cartella di ricerca. Non è necessario ricostruire l'intero set di risultati. |
| [RebuildResults](../../aspose.email.clients.activesync.transportlayer/searchoptions/rebuildresults) { get; set; } | Forza il server a ricostruire la cartella di ricerca (2) che corrisponde a una determinata query. I risultati della ricerca (ovvero il set di risultati) sono archiviati in una cartella di ricerca sul server. In questo modo, quando un client torna con la stessa query ma un nuovo intervallo di righe, le righe vengono estratte dal set di risultati attualmente archiviato nella cartella di ricerca. Non è necessario ricostruire l'intero set di risultati. La cartella di ricerca rimane invariata finché il client non esegue una delle seguenti operazioni per aggiornare il set di risultati: - Invia una richiesta di ricerca, specificando una nuova query. In questo caso, la cartella di ricerca viene ricostruita automaticamente. Il nodo RebuildResults non deve essere incluso. - Invia una richiesta di ricerca che include il nodo RebuildResults. In questo caso, il server è costretto a ricostruire la cartella di ricerca. Se viene aggiunto un nuovo elemento, l'elemento non viene visualizzato nel set di risultati fino a quando il set di risultati non viene aggiornato. Se un elemento viene eliminato, il server filtrerà l'elemento eliminato dal set di risultati. Il client DOVREBBE inviare una nuova richiesta di ricerca con la query data e includere l'opzione RebuildResults ogni pochi giorni per garantire risultati accurati per quella query. |
| [RightsManagementSupport](../../aspose.email.clients.activesync.transportlayer/searchoptions/rightsmanagementsupport) { get; set; } | Specifica come il server restituisce al client i messaggi di posta elettronica con gestione dei diritti. Se il valore è TRUE, il server decomprime e decrittografa i messaggi di posta elettronica con gestione dei diritti prima di inviarli al client. Se il valore è FALSE, il server non decomprimerà né decrittograferà i messaggi di posta elettronica con gestione dei diritti prima di inviarli al client. Se l'elemento RightsManagementSupport non è incluso in un messaggio di richiesta, viene assunto un valore predefinito FALSE. |
| [UserName](../../aspose.email.clients.activesync.transportlayer/searchoptions/username) { get; set; } | Specifica l'account utente utilizzato per cercare il documento dalla raccolta documenti. Il valore UserName può avere una lunghezza massima di 100 caratteri. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->