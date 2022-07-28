---
title: ListMessagesAsync
second_title: Aspose.Email för .NET API-referens
description: Hämtar listan över meddelanden i den aktuella mappen.
type: docs
weight: 880
url: /sv/net/aspose.email.clients.imap/imapclient/listmessagesasync/
---
## ListMessagesAsync(int, CancellationToken) {#listmessagesasync_28}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* är negativ. |

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_17}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp för att hämta meddelanden. |
| modificationSequence | Int64 | Modifieringssekvens |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |
| messageExtraFields | IEnumerable`1 | Lista över extra parametrar för ett meddelande som kommer att begäras. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string) {#listmessagesasync_12}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp för att hämta meddelanden. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_6}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long) {#listmessagesasync_10}

Hämtar listan över meddelanden i den aktuella mappen som har en modifieringssekvens som är större än det angivna värdet. Se mer https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| modificationSequence | Int64 | Modifieringssekvens |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool) {#listmessagesasync_15}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp för att hämta meddelanden. |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync()
```

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;) {#listmessagesasync_31}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Lista över extra parametrar för ett meddelande som kommer att begäras. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_25}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(string) {#listmessagesasync_33}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool) {#listmessagesasync_36}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_37}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |
| messageExtraFields | IEnumerable`1 | Lista över extra parametrar för ett meddelande som kommer att begäras. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(long) {#listmessagesasync_29}

Hämtar listan över meddelanden i den aktuella mappen som har en modifieringssekvens som är större än det angivna värdet. Se mer https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| modificationSequence | Int64 | Modifieringssekvens |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int) {#listmessagesasync_13}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Meddelanden plats |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_2}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int) {#listmessagesasync_3}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_21}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int) {#listmessagesasync_34}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Meddelanden plats |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int) {#listmessagesasync_22}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int) {#listmessagesasync_8}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* är negativ. |

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(int) {#listmessagesasync_27}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* är negativ. |

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_18}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp för att hämta meddelanden. |
| modificationSequence | Int64 | Modifieringssekvens |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |
| messageExtraFields | IEnumerable`1 | Lista över extra parametrar för ett meddelande som kommer att begäras. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_20}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, CancellationToken) {#listmessagesasync_19}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp för att hämta meddelanden. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_7}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long, CancellationToken) {#listmessagesasync_11}

Hämtar listan över meddelanden i den aktuella mappen som har en modifieringssekvens som är större än det angivna värdet. Se mer https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| modificationSequence | Int64 | Modifieringssekvens |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool, CancellationToken) {#listmessagesasync_16}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp för att hämta meddelanden. |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_41}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_32}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Lista över extra parametrar för ett meddelande som kommer att begäras. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_26}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(string, CancellationToken) {#listmessagesasync_40}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, CancellationToken) {#listmessagesasync_39}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_38}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |
| messageExtraFields | IEnumerable`1 | Lista över extra parametrar för ett meddelande som kommer att begäras. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(long, CancellationToken) {#listmessagesasync_30}

Hämtar listan över meddelanden i den aktuella mappen som har en modifieringssekvens som är större än det angivna värdet. Se mer https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| modificationSequence | Int64 | Modifieringssekvens |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int, CancellationToken) {#listmessagesasync_14}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Meddelanden plats |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_5}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int, CancellationToken) {#listmessagesasync_4}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_24}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int, CancellationToken) {#listmessagesasync_35}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Meddelanden plats |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int, CancellationToken) {#listmessagesasync_23}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökfrågan. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Samling av ImapMessageInfo-objekt.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int, CancellationToken) {#listmessagesasync_9}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* är negativ. |

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
