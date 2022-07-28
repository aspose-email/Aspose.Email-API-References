---
title: SearchResult
second_title: Aspose.Email per riferimento all'API .NET
description: Contenitore per un singolo elemento della cassetta postale corrispondente. Quando larchivio in cui viene eseguita la ricerca è la cassetta postale - Esiste un elemento Risultato per ogni corrispondenza trovata nella cassetta postale. Se non vengono trovate corrispondenze è presente un elemento Result vuoto nellelemento Contenitore Store dellXML di risposta. - Allinterno dellelemento Result lelemento Properties contiene un elenco di proprietà richieste per lelemento della casella di posta. Quando larchivio è la ricerca è nella raccolta documenti - Il primo risultato restituito nella risposta di ricerca sono i metadati per la cartella principale o lelemento a cui punta il valore LinkId. Il client può scegliere di ignorare questa voce se non la richiede. - Se il valore dellelemento documentlibraryLinkId nella richiesta punta a una cartella le proprietà dei metadati della cartella vengono restituite come primo elemento e il contenuto di la cartella viene restituita come risultati successivi. Lintervallo si applica a questi risultati senza alcuna differenza ad esempio lindice 0 sarebbe sempre per lelemento radice a cui punta il collegamento. - Se il valore dellelemento documentlibraryLinkId nella richiesta punta a un elemento viene restituito un solo risultato i metadati per lelemento. - Allinterno dellelemento Risultato lelemento Proprietà contiene un elenco di proprietà richieste per lelemento della casella di posta.
type: docs
weight: 2010
url: /it/net/aspose.email.clients.activesync.transportlayer/searchresult/
---
## SearchResult class

Contenitore per un singolo elemento della cassetta postale corrispondente. Quando l'archivio in cui viene eseguita la ricerca è la cassetta postale: - Esiste un elemento Risultato per ogni corrispondenza trovata nella cassetta postale. Se non vengono trovate corrispondenze, è presente un elemento Result vuoto nell'elemento Contenitore Store dell'XML di risposta. - All'interno dell'elemento Result, l'elemento Properties contiene un elenco di proprietà richieste per l'elemento della casella di posta. Quando l'archivio è la ricerca è nella raccolta documenti: - Il primo risultato restituito nella risposta di ricerca sono i metadati per la cartella principale o l'elemento a cui punta il valore LinkId. Il client può scegliere di ignorare questa voce se non la richiede. - Se il valore dell'elemento documentlibrary:LinkId nella richiesta punta a una cartella, le proprietà dei metadati della cartella vengono restituite come primo elemento e il contenuto di la cartella viene restituita come risultati successivi. L'intervallo si applica a questi risultati senza alcuna differenza; ad esempio, l'indice 0 sarebbe sempre per l'elemento radice a cui punta il collegamento. - Se il valore dell'elemento documentlibrary:LinkId nella richiesta punta a un elemento, viene restituito un solo risultato: i metadati per l'elemento. - All'interno dell'elemento Risultato, l'elemento Proprietà contiene un elenco di proprietà richieste per l'elemento della casella di posta.

```csharp
public class SearchResult
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SearchResult](searchresult)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Class](../../aspose.email.clients.activesync.transportlayer/searchresult/class) { get; set; } | Identifica la classe dell'elemento. |
| [CollectionId](../../aspose.email.clients.activesync.transportlayer/searchresult/collectionid) { get; } | Specifica le cartelle in cui è stato trovato l'elemento. |
| [LongId](../../aspose.email.clients.activesync.transportlayer/searchresult/longid) { get; set; } | Specifica un identificatore univoco assegnato dal server a ogni set di risultati restituito. Il valore di LongId può essere utilizzato come ID lungo specificato nella richiesta del comando ItemOperations, nella richiesta del comando SmartReply, nella richiesta del comando SmartForward o il comando MeetingResponse richiede di fare riferimento al set di risultati. Il client DEVE memorizzare il valore di LongId come una stringa opaca di massimo 256 caratteri. |
| [Properties](../../aspose.email.clients.activesync.transportlayer/searchresult/properties) { get; set; } | La risposta del comando Cerca Proprietà è un contenitore di proprietà che si applicano a una singola voce che corrisponde alla stringa di ricerca dell'elemento Query. Ad esempio, l'elemento Properties contiene un elemento per ogni proprietà GAL con valore di testo non vuota collegata alla voce GAL corrispondente. Vengono restituite solo le proprietà allegate alla voce GAL specifica; pertanto è possibile restituire diversi insiemi di proprietà nell'XML di risposta per diverse voci GAL corrispondenti. Ciascun elemento nel contenitore Proprietà ha come ambito lo spazio dei nomi appropriato specificato nell'elemento Cerca di livello superiore. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
