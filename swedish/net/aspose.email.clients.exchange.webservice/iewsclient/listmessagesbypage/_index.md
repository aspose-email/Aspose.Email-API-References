---
title: ListMessagesByPage
second_title: Aspose.Email för .NET API-referens
description: Lista meddelandena i den angivna mappen.
type: docs
weight: 1150
url: /sv/net/aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/
---
## ListMessagesByPage(string, int) {#listmessagesbypage_4}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i. |
| itemsPerPage | Int32 | Ett antal artiklar på sidan |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int) {#listmessagesbypage_2}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökkriterier. |
| itemsPerPage | Int32 | Ett antal artiklar på sidan |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int) {#listmessagesbypage_5}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int offset)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i. |
| itemsPerPage | Int32 | Ett antal artiklar på sidan |
| offset | Int32 | En förskjutning av nästa sida i sikte |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int, int) {#listmessagesbypage_3}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage, 
    int offset)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökkriterier. |
| itemsPerPage | Int32 | Ett antal artiklar på sidan |
| offset | Int32 | En förskjutning av nästa sida i sikte |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int, ExchangeListMessagesOptions) {#listmessagesbypage_6}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int pageOffset, 
    ExchangeListMessagesOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i. |
| itemsPerPage | Int32 | Ett antal artiklar på sidan |
| pageOffset | Int32 | En förskjutning av nästa objekt i sikte |
| options | ExchangeListMessagesOptions | Anger inställningarna för listningen |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo) {#listmessagesbypage}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i. |
| pageInfo | PageInfo | En sida info |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo, ExchangeListMessagesOptions) {#listmessagesbypage_1}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo, 
    ExchangeListMessagesOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i. |
| pageInfo | PageInfo | En sida info |
| options | ExchangeListMessagesOptions | Anger inställningarna för listningen |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
