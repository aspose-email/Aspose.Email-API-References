---
title: ListMessagesAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab
type: docs
weight: 300
url: /de/net/aspose.email.clients.pop3/pop3client/listmessagesasync/
---
## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_8}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_6}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| query | MailQuery | Das[`MailQuery`](../../../aspose.email.tools.search/mailquery) Objekt. |

### Rückgabewert

Sammlung von Pop3MessageInfo-Objekten.

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields) {#listmessagesasync_2}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery) {#listmessagesasync_3}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |
| query | MailQuery | Das[`MailQuery`](../../../aspose.email.tools.search/mailquery) Objekt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync()
```

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_17}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_15}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| query | MailQuery | Das[`MailQuery`](../../../aspose.email.tools.search/mailquery) Objekt. |

### Rückgabewert

Sammlung von Pop3MessageInfo-Objekten.

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields) {#listmessagesasync_11}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery) {#listmessagesasync_12}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |
| query | MailQuery | Das[`MailQuery`](../../../aspose.email.tools.search/mailquery) Objekt. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_10}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_9}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_7}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| query | MailQuery | Das[`MailQuery`](../../../aspose.email.tools.search/mailquery) Objekt. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Sammlung von Pop3MessageInfo-Objekten.

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, CancellationToken) {#listmessagesasync_5}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_4}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |
| query | MailQuery | Das[`MailQuery`](../../../aspose.email.tools.search/mailquery) Objekt. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_19}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_18}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_16}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| query | MailQuery | Das[`MailQuery`](../../../aspose.email.tools.search/mailquery) Objekt. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Sammlung von Pop3MessageInfo-Objekten.

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, CancellationToken) {#listmessagesasync_14}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_13}

Listet die Nachrichten auf.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |
| query | MailQuery | Das[`MailQuery`](../../../aspose.email.tools.search/mailquery) Objekt. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
