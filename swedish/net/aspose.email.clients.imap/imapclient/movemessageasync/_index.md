---
title: MoveMessageAsync
second_title: Aspose.Email för .NET API-referens
description: Flyttar meddelandet
type: docs
weight: 940
url: /sv/net/aspose.email.clients.imap/imapclient/movemessageasync/
---
## MoveMessageAsync(int, string, bool) {#movemessageasync_9}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool) {#movemessageasync_13}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string) {#movemessageasync}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string) {#movemessageasync_4}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string) {#movemessageasync_8}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string) {#movemessageasync_12}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool, CancellationToken) {#movemessageasync_2}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool, CancellationToken) {#movemessageasync_6}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, bool, CancellationToken) {#movemessageasync_10}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, bool, CancellationToken) {#movemessageasync_14}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, CancellationToken) {#movemessageasync_3}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, CancellationToken) {#movemessageasync_7}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(int, string, CancellationToken) {#movemessageasync_11}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(int sequenceNumber, string folderName, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(string, string, CancellationToken) {#movemessageasync_15}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(string uniqueId, string folderName, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för meddelandet |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, int, string, bool) {#movemessageasync_1}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(IConnection connection, int sequenceNumber, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## MoveMessageAsync(IConnection, string, string, bool) {#movemessageasync_5}

Flyttar meddelandet

```csharp
public Task<string> MoveMessageAsync(IConnection connection, string uniqueId, string folderName, 
    bool commitDeletions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för meddelandet |
| folderName | String | Mappnamn dit ett meddelande ska flyttas |
| commitDeletions | Boolean | Anger om borttagningar ska begås. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
