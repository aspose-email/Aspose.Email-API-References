---
title: ListMessages
second_title: Aspose.Email för .NET API-referens
description: Listar meddelandena. Får en information för sökmeddelande
type: docs
weight: 870
url: /sv/net/aspose.email.clients.imap/imapclient/listmessages/
---
## ListMessages(string, ImapListFields, int) {#listmessages_21}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, ImapListFields fieldsList, 
    int maxNumberOfMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |
| fieldsList | ImapListFields | Fält som kan hämtas från servern. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |

### Returvärde

ImapMessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, ImapListFields, int) {#listmessages_8}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    ImapListFields fieldsList, int maxNumberOfMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp för att hämta meddelanden. |
| fieldsList | ImapListFields | Fält som kan hämtas från servern. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |

### Returvärde

ImapMessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ImapListFields](../../imaplistfields)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;string&gt;) {#listmessages_26}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<string> uniqueIdLst)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |
| uniqueIdLst | IEnumerable`1 | Unik ID-lista för[`ImapMessageInfo`](../../imapmessageinfo) för att hämta från en server. |

### Returvärde

ImapMessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, IEnumerable&lt;int&gt;) {#listmessages_25}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, IEnumerable<int> sequenceNumberLst)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |
| sequenceNumberLst | IEnumerable`1 | sekvensnummer lista för[`ImapMessageInfo`](../../imapmessageinfo) för att hämta från en server. |

### Returvärde

ImapMessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;string&gt;) {#listmessages_13}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<string> uniqueIdLst)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp för att hämta meddelanden. |
| uniqueIdLst | IEnumerable`1 | Unik ID-lista för[`ImapMessageInfo`](../../imapmessageinfo) för att hämta från en server. |

### Returvärde

ImapMessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, IEnumerable&lt;int&gt;) {#listmessages_12}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    IEnumerable<int> sequenceNumberLst)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp för att hämta meddelanden. |
| sequenceNumberLst | IEnumerable`1 | sekvensnummer lista för[`ImapMessageInfo`](../../imapmessageinfo) för att hämta från en server. |

### Returvärde

ImapMessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessages_11}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
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

Samling av ImapMessageInfo-objekt

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |

### Returvärde

Samling av ImapMessageInfo-objekt

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, string) {#listmessages_7}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp för att hämta meddelanden. |

### Returvärde

Samling av ImapMessageInfo-objekt

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_4}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, bool retrieveRecursively)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |

### Returvärde

Samling av ImapMessageInfo-objekt

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, long) {#listmessages_6}

Hämtar listan över meddelanden i den aktuella mappen som har en modifieringssekvens som är större än det angivna värdet. Se mer https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| modificationSequence | Int64 | Modifieringssekvens |

### Returvärde

Samling av[`ImapMessageInfo`](../../imapmessageinfo) representerar meddelandeinformationen.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, bool) {#listmessages_10}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| folderName | String | Mapp för att hämta meddelanden. |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |

### Returvärde

Samling av ImapMessageInfo-objekt

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public ImapMessageInfoCollection ListMessages()
```

### Returvärde

Samling av ImapMessageInfo-objekt

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_19}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public ImapMessageInfoCollection ListMessages(IEnumerable<string> messageExtraFields)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Lista över extra parametrar för ett meddelande som kommer att begäras. |

### Returvärde

Samling av ImapMessageInfo-objekt

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_16}

Hämtar listan över meddelanden i den aktuella mappen

```csharp
public ImapMessageInfoCollection ListMessages(bool retrieveRecursively)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |

### Returvärde

Samling av ImapMessageInfo-objekt

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string) {#listmessages_20}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public ImapMessageInfoCollection ListMessages(string folderName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |

### Returvärde

Samling av ImapMessageInfo-objekt

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_23}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |

### Returvärde

Samling av ImapMessageInfo-objekt

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, bool, IEnumerable&lt;string&gt;) {#listmessages_24}

Hämtar listan över meddelanden i den angivna mappen

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, bool retrieveRecursively, 
    IEnumerable<string> messageExtraFields)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folderName | String | Mapp för att hämta meddelanden. |
| retrieveRecursively | Boolean | Indikerar om meddelanden måste hämtas rekursivt. |
| messageExtraFields | IEnumerable`1 | Lista över extra parametrar för ett meddelande som kommer att begäras. |

### Returvärde

Samling av ImapMessageInfo-objekt

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(long) {#listmessages_18}

Hämtar listan över meddelanden i den aktuella mappen som har en modifieringssekvens som är större än det angivna värdet. Se mer https://tools.ietf.org/html/rfc7162

```csharp
public ImapMessageInfoCollection ListMessages(long modificationSequence)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| modificationSequence | Int64 | Modifieringssekvens |

### Returvärde

Samling av[`ImapMessageInfo`](../../imapmessageinfo) representerar meddelandeinformationen.

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, string, MailQuery, int) {#listmessages_9}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, string folderName, 
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

## ListMessages(IConnection, MailQuery) {#listmessages_2}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query)
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

## ListMessages(IConnection, MailQuery, int) {#listmessages_3}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, MailQuery query, 
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

## ListMessages(MailQuery) {#listmessages_14}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query)
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

## ListMessages(string, MailQuery, int) {#listmessages_22}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public ImapMessageInfoCollection ListMessages(string folderName, MailQuery query, 
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

## ListMessages(MailQuery, int) {#listmessages_15}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public ImapMessageInfoCollection ListMessages(MailQuery query, int maxNumberOfMessages)
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

## ListMessages(IConnection, int) {#listmessages_5}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public ImapMessageInfoCollection ListMessages(IConnection connection, int maxNumberOfMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |

### Returvärde

Samling av[`ImapMessageInfo`](../../imapmessageinfo) representerar meddelandeinformationen.

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

## ListMessages(int) {#listmessages_17}

Hämtar listan över meddelanden i den aktuella mappen.

```csharp
public ImapMessageInfoCollection ListMessages(int maxNumberOfMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |

### Returvärde

Samling av[`ImapMessageInfo`](../../imapmessageinfo) representerar meddelandeinformationen.

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* är negativ. |

### Se även

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* namnutrymme [Aspose.Email.Clients.Imap](../../imapclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
