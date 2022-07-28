---
title: ListMessagesAsync
second_title: Aspose.Email för .NET API-referens
description: Listar meddelandena. Får en information för sökmeddelande
type: docs
weight: 300
url: /sv/net/aspose.email.clients.pop3/pop3client/listmessagesasync/
---
## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_8}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_6}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
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

## ListMessagesAsync(IConnection, Pop3ListFields) {#listmessagesasync_2}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| fields | Pop3ListFields | De fält som vi vill få |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

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

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery) {#listmessagesasync_3}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| fields | Pop3ListFields | De fält som vi vill få |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |
| query | MailQuery | De[`MailQuery`](../../../aspose.email.tools.search/mailquery) objekt. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync()
```

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_17}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_15}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query)
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

## ListMessagesAsync(Pop3ListFields) {#listmessagesasync_11}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fields | Pop3ListFields | De fält som vi vill få |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery) {#listmessagesasync_12}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fields | Pop3ListFields | De fält som vi vill få |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |
| query | MailQuery | De[`MailQuery`](../../../aspose.email.tools.search/mailquery) objekt. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_10}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_9}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_7}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| query | MailQuery | De[`MailQuery`](../../../aspose.email.tools.search/mailquery) objekt. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

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

## ListMessagesAsync(IConnection, Pop3ListFields, CancellationToken) {#listmessagesasync_5}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| fields | Pop3ListFields | De fält som vi vill få |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

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

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_4}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| connection | IConnection | Anslutning till en server |
| fields | Pop3ListFields | De fält som vi vill få |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |
| query | MailQuery | De[`MailQuery`](../../../aspose.email.tools.search/mailquery) objekt. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_19}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_18}

Listar meddelandena. Får en information för sökmeddelande

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_16}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| query | MailQuery | De[`MailQuery`](../../../aspose.email.tools.search/mailquery) objekt. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Samling av Pop3MessageInfo-objekt.

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, CancellationToken) {#listmessagesasync_14}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fields | Pop3ListFields | De fält som vi vill få |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Anmärkningar

Observera att meddelanden som är markerade som raderade inte listas

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_13}

Listar meddelandena.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query, CancellationToken token)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fields | Pop3ListFields | De fält som vi vill få |
| closeTransaction | Boolean | Indikerar om aktuell transaktion måste avslutas innan listan hämtas. |
| query | MailQuery | De[`MailQuery`](../../../aspose.email.tools.search/mailquery) objekt. |
| token | CancellationToken | Sprider meddelande om att operationer bör avbrytas. |

### Returvärde

Uppgiftsobjekt, med ombud för denna operation

### Se även

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* namnutrymme [Aspose.Email.Clients.Pop3](../../pop3client)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
