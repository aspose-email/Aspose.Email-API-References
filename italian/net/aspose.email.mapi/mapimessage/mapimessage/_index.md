---
title: MapiMessage
second_title: Aspose.Email per riferimento all'API .NET
description: Inizializza una nuova istanza diMapiMessageaspose.email.mapi/mapimessage classe.
type: docs
weight: 10
url: /it/net/aspose.email.mapi/mapimessage/mapimessage/
---
## MapiMessage() {#constructor}

Inizializza una nuova istanza di[`MapiMessage`](../../mapimessage) classe.

```csharp
public MapiMessage()
```

### Guarda anche

* class [MapiMessage](../../mapimessage)
* spazio dei nomi [Aspose.Email.Mapi](../../mapimessage)
* assemblea [Aspose.Email](../../../)

---

## MapiMessage(OutlookMessageFormat) {#constructor_1}

Inizializza una nuova istanza di[`MapiMessage`](../../mapimessage) classe.

```csharp
public MapiMessage(OutlookMessageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | OutlookMessageFormat | Definisce se utilizzare la codifica Unicode o ASCII per questo messaggio. |

### Guarda anche

* enum [OutlookMessageFormat](../../outlookmessageformat)
* class [MapiMessage](../../mapimessage)
* spazio dei nomi [Aspose.Email.Mapi](../../mapimessage)
* assemblea [Aspose.Email](../../../)

---

## MapiMessage(string, string, string, string, OutlookMessageFormat) {#constructor_3}

Inizializza una nuova istanza di[`MapiMessage`](../../mapimessage) classe.

```csharp
public MapiMessage(string from, string to, string subject, string body, OutlookMessageFormat format)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| from | String | L'indirizzo Da. |
| to | String | Gli indirizzi dei destinatari. Si noti che gli indirizzi sono separati da punto e virgola. |
| subject | String | L'oggetto del messaggio. |
| body | String | Il corpo del messaggio. |
| format | OutlookMessageFormat | Definisce se utilizzare la codifica Unicode o ASCII per questo messaggio. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | Viene generato se l'indirizzo del destinatario è nullo o vuoto. |
| ArgumentException | Viene generato se l'indirizzo del mittente o del destinatario non è in un formato riconosciuto. |
| InvalidEnumArgumentException | Viene lanciato se*format*parametro non è un membro di enumerazione valido. |

### Guarda anche

* enum [OutlookMessageFormat](../../outlookmessageformat)
* class [MapiMessage](../../mapimessage)
* spazio dei nomi [Aspose.Email.Mapi](../../mapimessage)
* assemblea [Aspose.Email](../../../)

---

## MapiMessage(string, string, string, string) {#constructor_2}

Inizializza una nuova istanza di[`MapiMessage`](../../mapimessage) classe.

```csharp
public MapiMessage(string from, string to, string subject, string body)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| from | String | L'indirizzo Da. |
| to | String | Gli indirizzi dei destinatari. Si noti che gli indirizzi sono separati da punto e virgola. |
| subject | String | L'oggetto del messaggio. |
| body | String | Il corpo del messaggio. |

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentNullException | genera se l'indirizzo del destinatario è nullo o vuoto. |
| ArgumentException | genera se l'indirizzo del mittente o del destinatario non è in un formato riconosciuto. |

### Guarda anche

* class [MapiMessage](../../mapimessage)
* spazio dei nomi [Aspose.Email.Mapi](../../mapimessage)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->