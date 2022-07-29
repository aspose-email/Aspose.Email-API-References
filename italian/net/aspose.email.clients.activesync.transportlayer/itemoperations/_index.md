---
title: ItemOperations
second_title: Aspose.Email per riferimento all'API .NET
description: Spazio dei nomi ItemOperations del protocollo ActiveSync
type: docs
weight: 1390
url: /it/net/aspose.email.clients.activesync.transportlayer/itemoperations/
---
## ItemOperations enumeration

Spazio dei nomi ItemOperations del protocollo ActiveSync

```csharp
public enum ItemOperations
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| ItemOperations | `5` | L'elemento ItemOperations è un elemento obbligatorio nelle richieste di comando ItemOperations e nelle risposte ai comandi ItemOperations che identifica il corpo del POST HTTP come contenente un comando ItemOperations (sezione 2.2.2.8). |
| Fetch | `6` | Recupera un elemento dal server. |
| Store | `7` | Specifica il nome del negozio a cui si applica l'operazione padre. |
| Options | `8` | Contiene le opzioni per l'operazione EmptyFolderContents, l'operazione di recupero o l'operazione di spostamento. |
| Range | `9` | Specifica l'intervallo di byte che il client può ricevere in risposta all'operazione Recupero (sezione 2.2.3.63.1) per un elemento della raccolta documenti. |
| Total | `10` | Indica la dimensione totale di un elemento sul server, in byte. |
| Properties | `11` | Contiene le proprietà restituite per gli elementi nella risposta. |
| Data | `12` | Contiene il contenuto dell'elemento per le risposte del contenuto in linea. |
| Status | `13` | Indica il risultato di un'operazione. |
| Response | `14` | Contiene le risposte all'operazione. |
| Version | `15` | Indica l'ora in cui un elemento del documento è stato modificato l'ultima volta. |
| Schema | `16` | Specifica lo schema dell'elemento da recuperare. |
| Part | `17` | Specifica un indice intero nei metadati della risposta in più parti. |
| EmptyFolderContents | `18` | Identifica il corpo della richiesta o risposta come contenente l'operazione che elimina il contenuto di una cartella. |
| DeleteSubFolders | `19` | Indica se eliminare le sottocartelle della cartella specificata. |
| UserName | `20` | Specifica il nome utente dell'account utilizzato per recuperare l'elemento desiderato. |
| Password | `21` | Specifica la password per il nome utente specificato (sezione 2.2.3.177.1). |
| Move | `22` | Identifica il corpo della richiesta o risposta come contenente l'operazione che sposta una determinata conversazione. |
| DstFldId | `23` | Specifica l'ID server della cartella di destinazione (ovvero la cartella in cui vengono spostati gli elementi). |
| ConversationId | `24` | Specifica la conversazione da spostare. |
| MoveAlways | `25` | Indica se spostare sempre la conversazione specificata, incluse tutte le email future nella conversazione, nella cartella specificata dal valore dell'elemento DstFldId (sezione 2.2.3.49.1). |

### Guarda anche

* spazio dei nomi [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* assemblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->