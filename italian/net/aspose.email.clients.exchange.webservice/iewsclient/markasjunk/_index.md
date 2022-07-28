---
title: MarkAsJunk
second_title: Aspose.Email per riferimento all'API .NET
description: Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio.
type: docs
weight: 1270
url: /it/net/aspose.email.clients.exchange.webservice/iewsclient/markasjunk/
---
## MarkAsJunk(bool, params string[]) {#markasjunk_3}

Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio.

```csharp
public string[] MarkAsJunk(bool isJunk, params string[] messageUriEn)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isJunk | Boolean | Indica se i messaggi sono contrassegnati come posta indesiderata. Se il valore di true aggiunge il mittente del messaggio all'elenco di blocco. Se il valore di false rimuove il mittente del messaggio dall'elenco di blocco. |
| messageUriEn | String[] | Matrice di messaggi uri |

### Valore di ritorno

Restituisce l'array dell'ID messaggio che viene spostato nella cartella della posta indesiderata.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, params string[]) {#markasjunk_1}

Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, params string[] messageUriEn)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isJunk | Boolean | Indica se i messaggi sono contrassegnati come posta indesiderata. Se il valore di true aggiunge il mittente del messaggio all'elenco di blocco. Se il valore di false rimuove il mittente del messaggio dall'elenco di blocco. |
| moveItem | Boolean | Indica se i messaggi vengono spostati nella cartella della posta indesiderata. |
| messageUriEn | String[] | Matrice di messaggi uri |

### Valore di ritorno

Restituisce l'array dell'ID messaggio che viene spostato nella cartella della posta indesiderata.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## MarkAsJunk(bool, IEnumerable&lt;string&gt;) {#markasjunk_2}

Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio.

```csharp
public string[] MarkAsJunk(bool isJunk, IEnumerable<string> messageUriEn)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isJunk | Boolean | Indica se i messaggi sono contrassegnati come posta indesiderata. Se il valore di true aggiunge il mittente del messaggio all'elenco di blocco. Se il valore di false rimuove il mittente del messaggio dall'elenco di blocco. |
| messageUriEn | IEnumerable`1 | Enumerazione del messaggio uri |

### Valore di ritorno

Restituisce l'ID articolo del messaggio contrassegnato come posta indesiderata.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;) {#markasjunk}

Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isJunk | Boolean | Indica se i messaggi sono contrassegnati come posta indesiderata. Se il valore di true aggiunge il mittente del messaggio all'elenco di blocco. Se il valore di false rimuove il mittente del messaggio dall'elenco di blocco. |
| moveItem | Boolean | Indica se i messaggi vengono spostati nella cartella della posta indesiderata. |
| messageUriEn | IEnumerable`1 | Enumerazione del messaggio uri |

### Valore di ritorno

Restituisce l'array dell'ID messaggio che viene spostato nella cartella della posta indesiderata.

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) {#markasjunk_4}

Il metodo MarkAsJunk sposta i messaggi di posta nella cartella della posta indesiderata e blocca il mittente del messaggio.

```csharp
public void MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn, 
    out string[] movedMessageIds, out string[] failedMessageIds, out string[] errorMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| isJunk | Boolean | Indica se i messaggi sono contrassegnati come posta indesiderata. Se il valore di true aggiunge il mittente del messaggio all'elenco di blocco. Se il valore di false rimuove il mittente del messaggio dall'elenco di blocco. |
| moveItem | Boolean | Indica se i messaggi vengono spostati nella cartella della posta indesiderata. |
| messageUriEn | IEnumerable`1 | Enumerazione del messaggio uri |
| movedMessageIds | String[]& | Restituisce l'array dell'ID messaggio che viene spostato nella cartella della posta indesiderata. |
| failedMessageIds | String[]& | Restituisce l'array dell'ID messaggio che non è stato spostato nella cartella della posta indesiderata. |
| errorMessages | String[]& | Messaggi di errore per operazioni non riuscite |

### Guarda anche

* interface [IEWSClient](../../iewsclient)
* spazio dei nomi [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
