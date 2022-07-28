---
title: DeleteMessages
second_title: Aspose.Email per riferimento all'API .NET
description: Contrassegna un messaggio con il numero di sequenza specificato come eliminato
type: docs
weight: 580
url: /it/net/aspose.email.clients.imap/imapclient/deletemessages/
---
## DeleteMessages(IConnection, IEnumerable&lt;int&gt;) {#deletemessages_6}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;) {#deletemessages_8}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;) {#deletemessages_22}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;) {#deletemessages_24}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(IEnumerable<string> uidSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessages_7}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessages_10}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;, long) {#deletemessages_23}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | L'insieme dei numeri di sequenza per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long) {#deletemessages_26}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, bool) {#deletemessages_25}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessages_9}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long, bool) {#deletemessages_27}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessages_11}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| uidSet | IEnumerable`1 | L'insieme di UID per i messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int) {#deletemessages}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string) {#deletemessages_12}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(int, int) {#deletemessages_16}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(int startSequence, int endSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(string, string) {#deletemessages_28}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(string startUid, string endUid)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int, long) {#deletemessages_1}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long) {#deletemessages_14}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(int, int, long) {#deletemessages_17}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(int startSequence, int endSequence, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startSequence | Int32 | Il numero di sequenza iniziale di un elenco di messaggi |
| endSequence | Int32 | Il numero di sequenza finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long) {#deletemessages_30}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(string, string, bool) {#deletemessages_29}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, bool) {#deletemessages_13}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long, bool) {#deletemessages_31}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long, bool) {#deletemessages_15}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| startUid | String | L'UID iniziale di un elenco di messaggi |
| endUid | String | L'UID finale di un elenco di messaggi |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_2}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_18}

Contrassegna un messaggio con il numero di sequenza specificato come eliminato

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_4}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_20}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_19}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_3}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_21}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, 
    bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_5}

Contrassegna un messaggio con l'identificatore univoco specificato come eliminato e conferma le eliminazioni se l'utente lo specifica. Questo metodo funziona solo se il server supporta l'estensione UIDPLUS. Per favore, leggi di più https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| messageInfoSet | IEnumerable`1 | Il set di ImapMessageInfo per l'eliminazione |
| modificationSequence | Int64 | Sequenza di modifica. Per favore, leggi di più https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Definisce se il messaggio deve essere eseguito ora. Per favore, leggi di più https://tools.ietf.org/html/rfc4315 |

### Guarda anche

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
