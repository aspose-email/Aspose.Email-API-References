---
title: ListMessages
second_title: Aspose.Email für .NET-API-Referenz
description: Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab
type: docs
weight: 290
url: /de/net/aspose.email.clients.pop3/pop3client/listmessages/
---
## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_13}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<string> uniqueIdLst)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueIdLst | IEnumerable`1 | UniqueId-Liste für[`Pop3MessageInfo`](../../pop3messageinfo) von einem Server abzurufen. |

### Rückgabewert

Pop3MessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;int&gt;) {#listmessages_12}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<int> sequenceNumberLst)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumberLst | IEnumerable`1 | sequenceNumber Liste für[`Pop3MessageInfo`](../../pop3messageinfo) von einem Server abzurufen. |

### Rückgabewert

Pop3MessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;string&gt;) {#listmessages_7}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<string> uniqueIdLst)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueIdLst | IEnumerable`1 | UniqueId-Liste für[`Pop3MessageInfo`](../../pop3messageinfo) von einem Server abzurufen. |

### Rückgabewert

Pop3MessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;int&gt;) {#listmessages_6}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<int> sequenceNumberLst)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumberLst | IEnumerable`1 | sequenceNumber Liste für[`Pop3MessageInfo`](../../pop3messageinfo) von einem Server abzurufen. |

### Rückgabewert

Pop3MessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |

### Rückgabewert

Pop3MessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_5}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, bool closeTransaction)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |

### Rückgabewert

Pop3MessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_4}

Listet die Nachrichten auf.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, MailQuery query)
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

## ListMessages(IConnection, Pop3ListFields) {#listmessages_2}

Listet die Nachrichten auf.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |

### Rückgabewert

Pop3MessageInfoCollection

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

## ListMessages(IConnection, Pop3ListFields, bool, MailQuery) {#listmessages_3}

Listet die Nachrichten auf.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |
| query | MailQuery | Das[`MailQuery`](../../../aspose.email.tools.search/mailquery) Objekt. |

### Rückgabewert

Pop3MessageInfoCollection

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Pop3MessageInfoCollection ListMessages()
```

### Rückgabewert

Pop3MessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_11}

Listet die Nachrichten auf. Ruft eine Information für jede Nachricht ab

```csharp
public Pop3MessageInfoCollection ListMessages(bool closeTransaction)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |

### Rückgabewert

Pop3MessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_10}

Listet die Nachrichten auf.

```csharp
public Pop3MessageInfoCollection ListMessages(MailQuery query)
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

## ListMessages(Pop3ListFields) {#listmessages_8}

Listet die Nachrichten auf.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |

### Rückgabewert

Pop3MessageInfoCollection

### Bemerkungen

Beachten Sie, dass als gelöscht markierte Nachrichten nicht aufgelistet werden

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields, bool, MailQuery) {#listmessages_9}

Listet die Nachrichten auf.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields, bool closeTransaction, 
    MailQuery query)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fields | Pop3ListFields | Die Felder, die wir wollen, erhalten |
| closeTransaction | Boolean | Gibt an, ob die aktuelle Transaktion geschlossen werden muss, bevor die Liste abgerufen wird. |
| query | MailQuery | Das[`MailQuery`](../../../aspose.email.tools.search/mailquery) Objekt. |

### Rückgabewert

Pop3MessageInfoCollection

### Siehe auch

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
