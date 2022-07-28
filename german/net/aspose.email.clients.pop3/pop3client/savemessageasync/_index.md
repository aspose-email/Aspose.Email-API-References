---
title: SaveMessageAsync
second_title: Aspose.Email für .NET-API-Referenz
description: Ruft die Nachricht ab und speichert sie als Stream
type: docs
weight: 360
url: /de/net/aspose.email.clients.pop3/pop3client/savemessageasync/
---
## SaveMessageAsync(IConnection, string, Stream) {#savemessageasync_4}

Ruft die Nachricht ab und speichert sie als Stream

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die eindeutige ID der Nachricht |
| outputStream | Stream | Stream, wo die Nachricht gespeichert wird |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string) {#savemessageasync_6}

Ruft die Nachricht ab und speichert sie in einer Datei

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die eindeutige ID der Nachricht |
| fileName | String | Dateiname für Nachricht |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream) {#savemessageasync}

Ruft die Nachricht ab und speichert sie als Stream

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| outputStream | Stream | Stream, wo die Nachricht gespeichert wird |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string) {#savemessageasync_2}

Ruft die Nachricht ab und speichert sie in einer Datei

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| fileName | String | Dateiname für Nachricht |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream) {#savemessageasync_12}

Ruft die Nachricht ab und speichert sie als Stream

```csharp
public Task SaveMessageAsync(string uniqueId, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die eindeutige ID der Nachricht |
| outputStream | Stream | Stream, wo die Nachricht gespeichert wird |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string) {#savemessageasync_14}

Ruft die Nachricht ab und speichert sie in einer Datei

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die eindeutige ID der Nachricht |
| fileName | String | Dateiname für Nachricht |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream) {#savemessageasync_8}

Ruft die Nachricht ab und speichert sie als Stream

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream outputStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| outputStream | Stream | Stream, wo die Nachricht gespeichert wird |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string) {#savemessageasync_10}

Ruft die Nachricht ab und speichert sie in einer Datei

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| fileName | String | Dateiname für Nachricht |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream, CancellationToken) {#savemessageasync_5}

Ruft die Nachricht ab und speichert sie als Stream

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream outputStream, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die eindeutige ID der Nachricht |
| outputStream | Stream | Stream, wo die Nachricht gespeichert wird |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string, CancellationToken) {#savemessageasync_7}

Ruft die Nachricht ab und speichert sie in einer Datei

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| uniqueId | String | Die eindeutige ID der Nachricht |
| fileName | String | Dateiname für Nachricht |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream, CancellationToken) {#savemessageasync_1}

Ruft die Nachricht ab und speichert sie als Stream

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream outputStream, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| outputStream | Stream | Stream, wo die Nachricht gespeichert wird |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string, CancellationToken) {#savemessageasync_3}

Ruft die Nachricht ab und speichert sie in einer Datei

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName, 
    CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| connection | IConnection | Verbindung zu einem Server |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| fileName | String | Dateiname für Nachricht |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream, CancellationToken) {#savemessageasync_13}

Ruft die Nachricht ab und speichert sie als Stream

```csharp
public Task SaveMessageAsync(string uniqueId, Stream outputStream, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die eindeutige ID der Nachricht |
| outputStream | Stream | Stream, wo die Nachricht gespeichert wird |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string, CancellationToken) {#savemessageasync_15}

Ruft die Nachricht ab und speichert sie in einer Datei

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uniqueId | String | Die eindeutige ID der Nachricht |
| fileName | String | Dateiname für Nachricht |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream, CancellationToken) {#savemessageasync_9}

Ruft die Nachricht ab und speichert sie als Stream

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream outputStream, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| outputStream | Stream | Stream, wo die Nachricht gespeichert wird |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string, CancellationToken) {#savemessageasync_11}

Ruft die Nachricht ab und speichert sie in einer Datei

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName, CancellationToken token)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sequenceNumber | Int32 | Die Sequenznummer der Nachricht |
| fileName | String | Dateiname für Nachricht |
| token | CancellationToken | Propagiert die Benachrichtigung, dass Vorgänge abgebrochen werden sollten. |

### Rückgabewert

Task-Objekt mit Delegaten für diesen Vorgang

### Siehe auch

* class [Pop3Client](../../pop3client)
* namensraum [Aspose.Email.Clients.Pop3](../../pop3client)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
