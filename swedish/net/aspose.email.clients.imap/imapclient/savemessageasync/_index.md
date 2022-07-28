---
title: SaveMessageAsync
second_title: Aspose.Email för .NET API-referens
description: Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en medföljande stream
type: docs
weight: 1100
url: /sv/net/aspose.email.clients.imap/imapclient/savemessageasync/
---
## SaveMessageAsync(IConnection, int, Stream) {#savemessageasync}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en medföljande stream

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| resultStream | Stream | Stream som tar emot meddelandet |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream) {#savemessageasync_4}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en medföljande stream

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Meddelandets unika ID |
| resultStream | Stream | Stream som tar emot meddelandet |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string) {#savemessageasync_6}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en lokal fil

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Meddelandets unika ID |
| fileName | String | Sökvägen till den lokala filen. Detta kan inte vara en katalog |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string) {#savemessageasync_2}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en lokal fil

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| fileName | String | Sökvägen till den lokala filen. Detta kan inte vara en katalog |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream) {#savemessageasync_8}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en medföljande stream

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| resultStream | Stream | Stream som tar emot meddelandet |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream) {#savemessageasync_12}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en medföljande stream

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Meddelandets unika ID |
| resultStream | Stream | Stream som tar emot meddelandet |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string) {#savemessageasync_14}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en lokal fil

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Meddelandets unika ID |
| fileName | String | Sökvägen till den lokala filen. Detta kan inte vara en katalog |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string) {#savemessageasync_10}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en lokal fil

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| fileName | String | Sökvägen till den lokala filen. Detta kan inte vara en katalog |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, Stream, CancellationToken) {#savemessageasync_1}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en medföljande stream

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, Stream resultStream, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| resultStream | Stream | Stream som tar emot meddelandet |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, Stream, CancellationToken) {#savemessageasync_5}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en medföljande stream

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, Stream resultStream, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Meddelandets unika ID |
| resultStream | Stream | Stream som tar emot meddelandet |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, string, string, CancellationToken) {#savemessageasync_7}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en lokal fil

```csharp
public Task SaveMessageAsync(IConnection connection, string uniqueId, string fileName, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Meddelandets unika ID |
| fileName | String | Sökvägen till den lokala filen. Detta kan inte vara en katalog |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(IConnection, int, string, CancellationToken) {#savemessageasync_3}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en lokal fil

```csharp
public Task SaveMessageAsync(IConnection connection, int sequenceNumber, string fileName, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| fileName | String | Sökvägen till den lokala filen. Detta kan inte vara en katalog |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(int, Stream, CancellationToken) {#savemessageasync_9}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en medföljande stream

```csharp
public Task SaveMessageAsync(int sequenceNumber, Stream resultStream, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| resultStream | Stream | Stream som tar emot meddelandet |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(string, Stream, CancellationToken) {#savemessageasync_13}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en medföljande stream

```csharp
public Task SaveMessageAsync(string uniqueId, Stream resultStream, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Meddelandets unika ID |
| resultStream | Stream | Stream som tar emot meddelandet |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(string, string, CancellationToken) {#savemessageasync_15}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en lokal fil

```csharp
public Task SaveMessageAsync(string uniqueId, string fileName, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Meddelandets unika ID |
| fileName | String | Sökvägen till den lokala filen. Detta kan inte vara en katalog |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## SaveMessageAsync(int, string, CancellationToken) {#savemessageasync_11}

Laddar ned meddelandet med det angivna sekvensnumret och skriver dess data till en lokal fil

```csharp
public Task SaveMessageAsync(int sequenceNumber, string fileName, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumber | Int32 | Meddelandets sekvensnummer |
| fileName | String | Sökvägen till den lokala filen. Detta kan inte vara en katalog |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
