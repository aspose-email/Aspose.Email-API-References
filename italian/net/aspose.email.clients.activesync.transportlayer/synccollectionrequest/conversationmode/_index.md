---
title: ConversationMode
second_title: Aspose.Email per riferimento all'API .NET
description: Specifica se includere gli elementi inclusi nella modalità di conversazione nei risultati della risposta di sincronizzazione. Limpostazione del valore dellelemento ConversationMode su TRUE comporta il recupero di tutti i messaggi di posta elettronica che corrispondono alle conversazioni ricevute entro il filtro della data specificato. Tuttavia sebbene il corpo delle e-mail al di fuori di quel filtro basato sul tempo non verrà recuperato verranno recuperate le anteprime di testo se le anteprime sono state richieste. Limpostazione del valore dellelemento ConversationMode su FALSE in una richiesta di sincronizzazione comporta la sincronizzazione di elementi che soddisfano i criteri del valore dellelemento FilterType sezione 2.2.3.64. Limpostazione del valore dellelemento ConversationMode su TRUE espande il set di risultati per includere anche tutti gli elementi con valori email2ConversationId MS-AEMAIL sezione 2.2.2.14 identici a quelli nel set di risultati FilterType. Il valore dellelemento ConversationMode non ha alcun impatto sugli elementi al di fuori della raccolta specificata dallelemento CollectionId sezione 2.2.3.30.5 il set di risultati è sempre limitato agli elementi nella raccolta specificata. Il valore dellelemento ConversationMode limita o espande solo i risultati determinati dal valore dellelemento FilterType.
type: docs
weight: 40
url: /it/net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/conversationmode/
---
## SyncCollectionRequest.ConversationMode property

Specifica se includere gli elementi inclusi nella modalità di conversazione nei risultati della risposta di sincronizzazione. L'impostazione del valore dell'elemento ConversationMode su TRUE comporta il recupero di tutti i messaggi di posta elettronica che corrispondono alle conversazioni ricevute entro il filtro della data specificato. Tuttavia, sebbene il corpo delle e-mail al di fuori di quel filtro basato sul tempo non verrà recuperato, verranno recuperate le anteprime di testo se le anteprime sono state richieste. L'impostazione del valore dell'elemento ConversationMode su FALSE in una richiesta di sincronizzazione comporta la sincronizzazione di elementi che soddisfano i criteri del valore dell'elemento FilterType (sezione 2.2.3.64). L'impostazione del valore dell'elemento ConversationMode su TRUE espande il set di risultati per includere anche tutti gli elementi con valori email2:ConversationId ([MS-AEMAIL] sezione 2.2.2.14) identici a quelli nel set di risultati FilterType. Il valore dell'elemento ConversationMode non ha alcun impatto sugli elementi al di fuori della raccolta specificata dall'elemento CollectionId (sezione 2.2.3.30.5); il set di risultati è sempre limitato agli elementi nella raccolta specificata. Il valore dell'elemento ConversationMode limita o espande solo i risultati determinati dal valore dell'elemento FilterType.

```csharp
public bool? ConversationMode { get; set; }
```

### Guarda anche

* class [SyncCollectionRequest](../../synccollectionrequest)
* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../synccollectionrequest)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->