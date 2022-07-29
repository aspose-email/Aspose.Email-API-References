---
title: Insert
second_title: Aspose.Email per riferimento all'API .NET
description: Inserisce un elemento nel fileCollection allindice specificato.
type: docs
weight: 30
url: /it/net/aspose.email.mapi/mapiattachmentcollection/insert/
---
## Insert(int, MapiAttachment) {#insert}

Inserisce un elemento nel fileCollection all'indice specificato.

```csharp
public void Insert(int index, MapiAttachment item)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | L'indice in base zero a cui*item* dovrebbe essere inserito. |
| item | MapiAttachment | L'oggetto da inserire. Il valore può essere null per i tipi di riferimento. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *index* è minore di zero. |

### Guarda anche

* class [MapiAttachment](../../mapiattachment)
* class [MapiAttachmentCollection](../../mapiattachmentcollection)
* spazio dei nomi [Aspose.Email.Mapi](../../mapiattachmentcollection)
* assemblea [Aspose.Email](../../../)

---

## Insert(int, string, MapiMessage) {#insert_2}

Inserisce un messaggio come allegato nel file[`MapiAttachmentCollection`](../../mapiattachmentcollection) all'indice specificato.

```csharp
public void Insert(int index, string name, MapiMessage msg)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | L'indice in base zero in cui deve essere inserito. |
| name | String | Il nome dell'allegato. |
| msg | MapiMessage | Il[`MapiMessage`](../../mapimessage)che rappresenta il messaggio allegato. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | genera se il messaggio è nullo. |

### Guarda anche

* class [MapiMessage](../../mapimessage)
* class [MapiAttachmentCollection](../../mapiattachmentcollection)
* spazio dei nomi [Aspose.Email.Mapi](../../mapiattachmentcollection)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->