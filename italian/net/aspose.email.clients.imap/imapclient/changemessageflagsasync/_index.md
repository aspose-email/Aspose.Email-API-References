---
title: ChangeMessageFlagsAsync
second_title: Aspose.Email per riferimento all'API .NET
description: Modifica i flag del messaggio
type: docs
weight: 430
url: /it/net/aspose.email.clients.imap/imapclient/changemessageflagsasync/
---
## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#changemessageflagsasync_41}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#changemessageflagsasync_17}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#changemessageflagsasync_13}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#changemessageflagsasync_36}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'insieme di ImapMessageInfo |
| flags | ImapMessageFlags | Le bandiere da cambiare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#changemessageflagsasync_8}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | L'insieme di ImapMessageInfo |
| flags | ImapMessageFlags | Le bandiere da cambiare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#changemessageflagsasync_37}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'insieme di ImapMessageInfo |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#changemessageflagsasync_9}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | L'insieme di ImapMessageInfo |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_51}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_31}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_23}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_3}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_50}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_30}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_22}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_2}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_55}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_35}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_27}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_7}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_54}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_34}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_26}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_6}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_47}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_43}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_19}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_15}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_46}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_42}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_18}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_14}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_39}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'insieme di ImapMessageInfo |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_11}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | L'insieme di ImapMessageInfo |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_38}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | L'insieme di ImapMessageInfo |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_10}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence, 
    CancellationToken token)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | L'insieme di ImapMessageInfo |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Propaga la notifica che le operazioni devono essere annullate. |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags) {#changemessageflagsasync_48}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| flags | ImapMessageFlags | Le bandiere da cambiare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags) {#changemessageflagsasync_28}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| flags | ImapMessageFlags | Le bandiere da rimuovere |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#changemessageflagsasync_20}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
| flags | ImapMessageFlags | Le bandiere da cambiare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#changemessageflagsasync}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| flags | ImapMessageFlags | Le bandiere da rimuovere |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, long) {#changemessageflagsasync_49}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uniqueId | String | Il fluido del messaggio |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, long) {#changemessageflagsasync_29}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#changemessageflagsasync_21}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uniqueId | String | Il fluido del messaggio |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#changemessageflagsasync_1}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceNumber | Int32 | Il numero di sequenza del messaggio |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags) {#changemessageflagsasync_52}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags) {#changemessageflagsasync_32}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#changemessageflagsasync_24}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#changemessageflagsasync_4}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, long) {#changemessageflagsasync_53}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, long) {#changemessageflagsasync_33}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#changemessageflagsasync_25}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#changemessageflagsasync_5}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#changemessageflagsasync_44}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#changemessageflagsasync_40}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#changemessageflagsasync_16}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#changemessageflagsasync_12}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| flags | ImapMessageFlags | Le bandiere da rimuovere |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#changemessageflagsasync_45}

Modifica i flag del messaggio

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| flags | ImapMessageFlags | Le bandiere da cambiare |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Valore di ritorno

Oggetto attività, con delegato per questa operazione

### Guarda anche

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
