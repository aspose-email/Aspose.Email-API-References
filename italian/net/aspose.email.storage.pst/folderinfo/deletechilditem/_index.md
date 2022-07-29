---
title: DeleteChildItem
second_title: Aspose.Email per riferimento all'API .NET
description: Elimina lelemento cartella o messaggio in base al suo entryId.
type: docs
weight: 210
url: /it/net/aspose.email.storage.pst/folderinfo/deletechilditem/
---
## FolderInfo.DeleteChildItem method

Elimina l'elemento (cartella o messaggio) in base al suo entryId.

```csharp
public void DeleteChildItem(byte[] entryId)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entryId | Byte[] | L'ID voce. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | genera, se entryId è null. |
| InvalidOperationException | genera, se l'elemento non appartiene alla cartella o l'elemento non può essere eliminato o entryID ha il valore errato. |
| InvalidOperationException | getta, se un PST è aperto per la sola lettura. |

### Osservazioni

L'elemento deve essere contenuto in una cartella.

### Guarda anche

* class [FolderInfo](../../folderinfo)
* spazio dei nomi [Aspose.Email.Storage.Pst](../../folderinfo)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->