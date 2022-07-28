---
title: ListMessages
second_title: Aspose.Email för .NET API-referens
description: Listar meddelandena. Får en information för sökmeddelande
type: docs
weight: 290
url: /sv/net/aspose.email.clients.pop3/pop3client/listmessages/
---
## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_13}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<string> uniqueIdLst)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uniqueIdLst | IEnumerable`1 | Unik ID-lista för[`Pop3MessageInfo`](../../pop3messageinfo) för att hämta från en server. |

### Returvärde

Pop3MessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;int&gt;) {#listmessages_12}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Pop3MessageInfoCollection ListMessages(IEnumerable<int> sequenceNumberLst)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sequenceNumberLst | IEnumerable`1 | sekvensnummer lista för[`Pop3MessageInfo`](../../pop3messageinfo) för att hämta från en server. |

### Returvärde

Pop3MessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;string&gt;) {#listmessages_7}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<string> uniqueIdLst)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| uniqueIdLst | IEnumerable`1 | Unik ID-lista för[`Pop3MessageInfo`](../../pop3messageinfo) för att hämta från en server. |

### Returvärde

Pop3MessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, IEnumerable&lt;int&gt;) {#listmessages_6}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, 
    IEnumerable<int> sequenceNumberLst)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| sequenceNumberLst | IEnumerable`1 | sekvensnummer lista för[`Pop3MessageInfo`](../../pop3messageinfo) för att hämta från en server. |

### Returvärde

Pop3MessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection) {#listmessages_1}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |

### Returvärde

Pop3MessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, bool) {#listmessages_5}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, bool closeTransaction)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |

### Returvärde

Pop3MessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, MailQuery) {#listmessages_4}

Listar meddelandena.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, MailQuery query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| query | MailQuery | De[`MailQuery`](../../../aspose.email.tools.search/mailquery) objekt. |

### Returvärde

Samling av Pop3MessageInfo-objekt.

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, Pop3ListFields) {#listmessages_2}

Listar meddelandena.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| fields | Pop3ListFields | De fält som vi vill få |

### Returvärde

Pop3MessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IConnection, Pop3ListFields, bool, MailQuery) {#listmessages_3}

Listar meddelandena.

```csharp
public Pop3MessageInfoCollection ListMessages(IConnection connection, Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| fields | Pop3ListFields | De fält som vi vill få |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |
| query | MailQuery | De[`MailQuery`](../../../aspose.email.tools.search/mailquery) objekt. |

### Returvärde

Pop3MessageInfoCollection

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Pop3MessageInfoCollection ListMessages()
```

### Returvärde

Pop3MessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(bool) {#listmessages_11}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Pop3MessageInfoCollection ListMessages(bool closeTransaction)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |

### Returvärde

Pop3MessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(MailQuery) {#listmessages_10}

Listar meddelandena.

```csharp
public Pop3MessageInfoCollection ListMessages(MailQuery query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| query | MailQuery | De[`MailQuery`](../../../aspose.email.tools.search/mailquery) objekt. |

### Returvärde

Samling av Pop3MessageInfo-objekt.

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields) {#listmessages_8}

Listar meddelandena.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fields | Pop3ListFields | De fält som vi vill få |

### Returvärde

Pop3MessageInfoCollection

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(Pop3ListFields, bool, MailQuery) {#listmessages_9}

Listar meddelandena.

```csharp
public Pop3MessageInfoCollection ListMessages(Pop3ListFields fields, bool closeTransaction, 
    MailQuery query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fields | Pop3ListFields | De fält som vi vill få |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |
| query | MailQuery | De[`MailQuery`](../../../aspose.email.tools.search/mailquery) objekt. |

### Returvärde

Pop3MessageInfoCollection

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
