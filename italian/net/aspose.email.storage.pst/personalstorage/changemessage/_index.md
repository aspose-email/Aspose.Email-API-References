---
title: ChangeMessage
second_title: Aspose.Email per riferimento all'API .NET
description: Modifica le proprietà del messaggio.
type: docs
weight: 120
url: /it/net/aspose.email.storage.pst/personalstorage/changemessage/
---
## PersonalStorage.ChangeMessage method

Modifica le proprietà del messaggio.

```csharp
public void ChangeMessage(string entryId, MapiPropertyCollection updatedProperties)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| entryId | String | L'identificatore di voce del messaggio. |
| updatedProperties | MapiPropertyCollection | Le proprietà aggiornate. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| NotImplementedException | La modifica della versione del file ANSI non è implementata. |
| InvalidOperationException | Il PST è aperto per la sola lettura. o L'ID voce non è corretto. |
| ArgumentNullException | entryIdCollection;La raccolta di ID voce non può essere nulla. o updatedProperties;La raccolta di proprietà non può essere nulla. |

### Guarda anche

* class [MapiPropertyCollection](../../../aspose.email.mapi/mapipropertycollection)
* class [PersonalStorage](../../personalstorage)
* spazio dei nomi [Aspose.Email.Storage.Pst](../../personalstorage)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->