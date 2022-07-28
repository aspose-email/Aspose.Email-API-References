---
title: UnselectFolderAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Entfernt dauerhaft alle als gelöscht markierten Nachrichten für den aktuell ausgewählten Ordner und entfernt den ausgewählten Status für diesen Ordner.
type: docs
weight: 1260
url: /de/net/aspose.email.clients.imap/imapclient/unselectfolderasync/
---
## UnselectFolderAsync(IConnection) {#unselectfolderasync_1}

Entfernt dauerhaft alle als gelöscht markierten Nachrichten für den aktuell ausgewählten Ordner und entfernt den ausgewählten Status für diesen Ordner.

```csharp
public Task UnselectFolderAsync(IConnection connection)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## UnselectFolderAsync() {#unselectfolderasync}

Entfernt dauerhaft alle als gelöscht markierten Nachrichten für den aktuell ausgewählten Ordner und entfernt den ausgewählten Status für diesen Ordner.

```csharp
public Task UnselectFolderAsync()
```

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, bool) {#unselectfolderasync_2}

Hebt die Auswahl der aktuell ausgewählten Ordner auf. Wenn die Eigenschaft doNotExpunge wahr ist, werden alle Nachrichten als gelöscht markiert und entfernt, andernfalls wird das Löschen abgebrochen. Bitte beachten Sie, dass dieser Vorgang nur funktioniert, wenn der Server RFC3691 unterstützt Weitere Informationen finden Sie unter https://tools. ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(IConnection connection, bool doNotExpunge)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| doNotExpunge | Boolean | Gibt an, ob als gelöscht markierte Nachrichten entfernt werden sollen. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## UnselectFolderAsync(bool) {#unselectfolderasync_5}

Hebt die Auswahl der aktuell ausgewählten Ordner auf. Wenn die Eigenschaft doNotExpunge wahr ist, werden alle Nachrichten als gelöscht markiert und entfernt, andernfalls wird das Löschen abgebrochen. Bitte beachten Sie, dass dieser Vorgang nur funktioniert, wenn der Server RFC3691 unterstützt Weitere Informationen finden Sie unter https://tools. ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| doNotExpunge | Boolean | Gibt an, ob als gelöscht markierte Nachrichten entfernt werden sollen. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, CancellationToken) {#unselectfolderasync_4}

Entfernt dauerhaft alle als gelöscht markierten Nachrichten für den aktuell ausgewählten Ordner und entfernt den ausgewählten Status für diesen Ordner.

```csharp
public Task UnselectFolderAsync(IConnection connection, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## UnselectFolderAsync(CancellationToken) {#unselectfolderasync_7}

Entfernt dauerhaft alle als gelöscht markierten Nachrichten für den aktuell ausgewählten Ordner und entfernt den ausgewählten Status für diesen Ordner.

```csharp
public Task UnselectFolderAsync(CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, bool, CancellationToken) {#unselectfolderasync_3}

Hebt die Auswahl der aktuell ausgewählten Ordner auf. Wenn die Eigenschaft doNotExpunge wahr ist, werden alle Nachrichten als gelöscht markiert und entfernt, andernfalls wird das Löschen abgebrochen. Bitte beachten Sie, dass dieser Vorgang nur funktioniert, wenn der Server RFC3691 unterstützt Weitere Informationen finden Sie unter https://tools. ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(IConnection connection, bool doNotExpunge, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| doNotExpunge | Boolean | Gibt an, ob als gelöscht markierte Nachrichten entfernt werden sollen. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

---

## UnselectFolderAsync(bool, CancellationToken) {#unselectfolderasync_6}

Hebt die Auswahl der aktuell ausgewählten Ordner auf. Wenn die Eigenschaft doNotExpunge wahr ist, werden alle Nachrichten als gelöscht markiert und entfernt, andernfalls wird das Löschen abgebrochen. Bitte beachten Sie, dass dieser Vorgang nur funktioniert, wenn der Server RFC3691 unterstützt Weitere Informationen finden Sie unter https://tools. ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| doNotExpunge | Boolean | Gibt an, ob als gelöscht markierte Nachrichten entfernt werden sollen. |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [ImapClient](../../imapclient)
* namensraum [Aspose.Email.Clients.Imap](../../imapclient)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
