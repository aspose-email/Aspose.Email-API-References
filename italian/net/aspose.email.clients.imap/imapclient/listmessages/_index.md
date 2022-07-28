---
title: ListMessages
second_title: Aspose.Email per riferimento all'API .NET
description: Elenca i messaggi. Ottiene uninformazione per ogni messaggio
type: docs
weight: 870
url: /it/net/aspose.email.clients.imap/imapclient/listmessages/
---
## ListMessages(string, ImapListFields, int) {#listmessages_21}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, ImapListFields fieldsList, 
    int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |
| fieldsList | ImapListFields | Campi che possono essere recuperati dal server. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

ImapMessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, ImapListFields, int) {#listmessages_8}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    ImapListFields fieldsList, int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |
| fieldsList | ImapListFields | Campi che possono essere recuperati dal server. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

ImapMessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;string&gt;) {#listmessages_26}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<string> uniqueIdLst)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |
| uniqueIdLst | IEnumerable`1 | Elenco di ID univoci per[`ImapMessageInfo`](../../imapmessageinfo) per recuperare da un server. |

### Valore di ritorno

ImapMessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;int&gt;) {#listmessages_25}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<int> sequenceNumberLst)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |
| sequenceNumberLst | IEnumerable`1 | sequenzaNumero elenco per[`ImapMessageInfo`](../../imapmessageinfo) per recuperare da un server. |

### Valore di ritorno

ImapMessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;string&gt;) {#listmessages_13}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<string> uniqueIdLst)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |
| uniqueIdLst | IEnumerable`1 | Elenco di ID univoci per[`ImapMessageInfo`](../../imapmessageinfo) per recuperare da un server. |

### Valore di ritorno

ImapMessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;int&gt;) {#listmessages_12}

Elenca i messaggi. Ottiene un'informazione per ogni messaggio

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<int> sequenceNumberLst)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |
| sequenceNumberLst | IEnumerable`1 | sequenzaNumero elenco per[`ImapMessageInfo`](../../imapmessageinfo) per recuperare da un server. |

### Valore di ritorno

ImapMessageInfoCollection

### Osservazioni

Tieni presente che i messaggi contrassegnati come eliminati non sono elencati

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessages_11}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |
| modificationSequence | Int64 | Sequenza di modifica |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |
| messageExtraFields | IEnumerable`1 | Elenco di parametri extra per un messaggio che verrà richiesto. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string) {#listmessages_7}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_4}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, bool retrieveRecursively)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, long) {#listmessages_6}

Ottiene l'elenco dei messaggi nella cartella corrente che hanno una sequenza di modifica maggiore del valore specificato. Per favore, vedere di più https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| modificationSequence | Int64 | Sequenza di modifica |

### Valore di ritorno

Collezione di[`ImapMessageInfo`](../../imapmessageinfo) che rappresentano le informazioni dei messaggi.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, bool) {#listmessages_10}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Cartella per recuperare i messaggi. |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public ImapMessageInfoCollection ListMessages()
```

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_19}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public ImapMessageInfoCollection ListMessages(IEnumerable<string> messageExtraFields)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Elenco di parametri extra per un messaggio che verrà richiesto. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_16}

Ottiene l'elenco dei messaggi nella cartella corrente

```csharp
public ImapMessageInfoCollection ListMessages(bool retrieveRecursively)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string) {#listmessages_20}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public ImapMessageInfoCollection ListMessages(string folderName)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_23}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, bool, IEnumerable&lt;string&gt;) {#listmessages_24}

Ottiene l'elenco dei messaggi nella cartella specificata

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively, 
    IEnumerable<string> messageExtraFields)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Cartella per recuperare i messaggi. |
| retrieveRecursively | Boolean | Indica se i messaggi devono essere recuperati in modo ricorsivo. |
| messageExtraFields | IEnumerable`1 | Elenco di parametri extra per un messaggio che verrà richiesto. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(long) {#listmessages_18}

Ottiene l'elenco dei messaggi nella cartella corrente che hanno una sequenza di modifica maggiore del valore specificato. Per favore, vedere di più https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(long modificationSequence)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| modificationSequence | Int64 | Sequenza di modifica |

### Valore di ritorno

Collezione di[`ImapMessageInfo`](../../imapmessageinfo) che rappresentano le informazioni dei messaggi.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, MailQuery, int) {#listmessages_9}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| folderName | String | Posizione dei messaggi |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_2}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery, int) {#listmessages_3}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_14}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, int) {#listmessages_22}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| folderName | String | Posizione dei messaggi |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(MailQuery, int) {#listmessages_15}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query, int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) che rappresenta la query di ricerca. |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Raccolta di oggetti ImapMessageInfo.

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(IConnection, int) {#listmessages_5}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| connection | IConnection | Connessione a un server |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Collezione di[`ImapMessageInfo`](../../imapmessageinfo) che rappresentano le informazioni dei messaggi.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* è negativo. |

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

---

## ListMessages(int) {#listmessages_17}

Ottiene l'elenco dei messaggi nella cartella corrente.

```csharp
public ImapMessageInfoCollection ListMessages(int maxNumberOfMessages)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Numero massimo di messaggi. |

### Valore di ritorno

Collezione di[`ImapMessageInfo`](../../imapmessageinfo) che rappresentano le informazioni dei messaggi.

### Eccezioni

| eccezione | condizione |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* è negativo. |

### Guarda anche

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* spazio dei nomi [Aspose.Email.Clients.Imap](../../imapclient)
* assemblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
