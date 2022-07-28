---
title: CommitDeletesAsync
second_title: Aspose.Email för .NET API-referens
description: Begå raderingarna
type: docs
weight: 470
url: /sv/net/aspose.email.clients.imap/imapclient/commitdeletesasync/
---
## CommitDeletesAsync(IConnection) {#commitdeletesasync_1}

Begå raderingarna

```csharp
public Task CommitDeletesAsync(IConnection connection)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int) {#commitdeletesasync_2}

Begå raderingarna

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sleep | Int32 | Väntetid slutför operationen i millisekunder |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync() {#commitdeletesasync}

Begå raderingarna

```csharp
public Task CommitDeletesAsync()
```

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(int) {#commitdeletesasync_11}

Begå raderingarna

```csharp
public Task CommitDeletesAsync(int sleep)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sleep | Int32 | Väntetid slutför operationen i millisekunder |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;) {#commitdeletesasync_13}

Commit the deletions Den här metoden fungerar bara om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättning av unika identifierare för meddelanden |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(string) {#commitdeletesasync_15}

Commit the deletions Den här metoden fungerar bara om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för ett meddelande |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, string) {#commitdeletesasync_16}

Commit the deletions Den här metoden fungerar bara om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;) {#commitdeletesasync_4}

Commit the deletions Den här metoden fungerar bara om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättning av unika identifierare för meddelanden |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string) {#commitdeletesasync_6}

Begå raderingarna

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för ett meddelande |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, string) {#commitdeletesasync_7}

Commit the deletions Den här metoden fungerar bara om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, CancellationToken) {#commitdeletesasync_10}

Begå raderingarna

```csharp
public Task CommitDeletesAsync(IConnection connection, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, int, CancellationToken) {#commitdeletesasync_3}

Begå raderingarna

```csharp
public Task CommitDeletesAsync(IConnection connection, int sleep, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sleep | Int32 | Väntetid slutför operationen i millisekunder |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(CancellationToken) {#commitdeletesasync_19}

Begå raderingarna

```csharp
public Task CommitDeletesAsync(CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(int, CancellationToken) {#commitdeletesasync_12}

Begå raderingarna

```csharp
public Task CommitDeletesAsync(int sleep, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sleep | Int32 | Väntetid slutför operationen i millisekunder |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_14}

Commit the deletions Den här metoden fungerar bara om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IEnumerable<string> uidSet, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Uppsättning av unika identifierare för meddelanden |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, CancellationToken) {#commitdeletesasync_18}

Commit the deletions Den här metoden fungerar bara om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string uniqueId, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueId | String | Uid för ett meddelande |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(string, string, CancellationToken) {#commitdeletesasync_17}

Commit the deletions Den här metoden fungerar bara om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(string startUid, string endUid, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, IEnumerable&lt;string&gt;, CancellationToken) {#commitdeletesasync_5}

Commit the deletions Den här metoden fungerar bara om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, IEnumerable<string> uidSet, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uidSet | IEnumerable`1 | Uppsättning av unika identifierare för meddelanden |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, CancellationToken) {#commitdeletesasync_9}

Begå raderingarna

```csharp
public Task CommitDeletesAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueId | String | Uid för ett meddelande |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## CommitDeletesAsync(IConnection, string, string, CancellationToken) {#commitdeletesasync_8}

Commit the deletions Den här metoden fungerar bara om servern stöder UIDPLUS-tillägget. Vänligen läs mer https://tools.ietf.org/html/rfc4315

```csharp
public Task CommitDeletesAsync(IConnection connection, string startUid, string endUid, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| startUid | String | Start-UID för en meddelandelista |
| endUid | String | Slut-UID för en meddelandelista |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
