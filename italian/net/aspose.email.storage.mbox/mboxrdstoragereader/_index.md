---
title: MboxrdStorageReader
second_title: Aspose.Email per riferimento all'API .NET
description: Rappresenta un lettore di archiviazione in formato mboxrd questo formato è utilizzato da Thunderbird e altri client di posta.
type: docs
weight: 20060
url: /it/net/aspose.email.storage.mbox/mboxrdstoragereader/
---
## MboxrdStorageReader class

Rappresenta un lettore di archiviazione in formato mboxrd, questo formato è utilizzato da Thunderbird e altri client di posta.

```csharp
public sealed class MboxrdStorageReader : MboxStorageReader
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [MboxrdStorageReader](mboxrdstoragereader#constructor)(Stream, MboxLoadOptions) |  |
| [MboxrdStorageReader](mboxrdstoragereader#constructor_2)(string, MboxLoadOptions) | Inizializza una nuova istanza di[`MboxrdStorageReader`](../mboxrdstoragereader) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BaseStream](../../aspose.email.storage.mbox/mboxstoragereader/basestream) { get; } | Ottiene il flusso di base. |
| [CurrentDataSize](../../aspose.email.storage.mbox/mboxstoragereader/currentdatasize) { get; } | Ottiene il numero di byte letti dal metodo ReadNextMessage. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Dispose](../../aspose.email.storage.mbox/mboxstoragereader/dispose)() | Esegue attività definite dall'applicazione associate alla liberazione, al rilascio o al ripristino di risorse non gestite. |
| [EnumerateMessages](../../aspose.email.storage.mbox/mboxstoragereader/enumeratemessages)() | Espone l'enumeratore, che supporta un'iterazione dei messaggi nella memoria. |
| override [GetTotalItemsCount](../../aspose.email.storage.mbox/mboxrdstoragereader/gettotalitemscount)() | Restituisce il numero di messaggi in una memoria. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxrdstoragereader/readnextmessage#readnextmessage)() | Legge il messaggio successivo dal flusso di archiviazione sottostante. |
| override [ReadNextMessage](../../aspose.email.storage.mbox/mboxrdstoragereader/readnextmessage#readnextmessage_1)(out string) | Legge il messaggio successivo dal flusso di archiviazione sottostante. |

### Guarda anche

* class [MboxStorageReader](../mboxstoragereader)
* spazio dei nomi [Aspose.Email.Storage.Mbox](../../aspose.email.storage.mbox)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->