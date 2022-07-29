---
title: SyncAddServerOperation
second_title: Aspose.Email per riferimento all'API .NET
description: Crea un nuovo oggetto in una raccolta sul server.
type: docs
weight: 2150
url: /it/net/aspose.email.clients.activesync.transportlayer/syncaddserveroperation/
---
## SyncAddServerOperation class

Crea un nuovo oggetto in una raccolta sul server.

```csharp
public class SyncAddServerOperation
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [SyncAddServerOperation](syncaddserveroperation)() | Default_Costruttore |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ApplicationData](../../aspose.email.clients.activesync.transportlayer/syncaddserveroperation/applicationdata) { get; } | ApplicationData contiene dati per un oggetto particolare, come un contatto, un messaggio di posta elettronica, un appuntamento del calendario o un elemento dell'attività. |
| [Class](../../aspose.email.clients.activesync.transportlayer/syncaddserveroperation/class) { get; set; } | Identifica la classe dell'elemento da aggiungere alla raccolta. |
| [ClientId](../../aspose.email.clients.activesync.transportlayer/syncaddserveroperation/clientid) { get; set; } | Contiene un identificatore univoco che viene generato dal client per identificare temporaneamente un nuovo oggetto che viene creato utilizzando l'elemento Aggiungi. Il client include l'elemento ClientId nella richiesta Aggiungi elemento che invia al server. La risposta del server contiene un elemento Add che contiene l'ID client originale e un nuovo ID server assegnato per l'oggetto, che sostituisce l'ID client come identificatore di oggetto permanente. L'elemento ClientId è un identificatore univoco composto da un massimo di 64 cifre e lettere. Il client genera questo ID. Il valore deve essere univoco per il dispositivo solo durante la durata della richiesta di sincronizzazione che aggiunge l'oggetto al server. Il client memorizza gli ID client fino al completamento della sessione di sincronizzazione, per semplificare il ripristino se il processo di sincronizzazione non riesce. |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->