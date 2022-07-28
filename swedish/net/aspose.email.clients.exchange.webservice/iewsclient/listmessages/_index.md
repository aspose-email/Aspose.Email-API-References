---
title: ListMessages
second_title: Aspose.Email för .NET API-referens
description: Listar meddelandena.
type: docs
weight: 1140
url: /sv/net/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---
## ListMessages(string) {#listmessages_2}

Listar meddelandena.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | Mappen. |

### Returvärde

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_3}

Listar meddelandena.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | Mappen. |
| options | ExchangeListMessagesOptions | Anger inställningarna för listningen |

### Returvärde

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_8}

Listar meddelandena.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | Mappen. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden |

### Returvärde

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_9}

Listar meddelandena.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | Mappen. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden |
| options | ExchangeListMessagesOptions | Anger inställningarna för listningen |

### Returvärde

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_13}

Lista meddelandena i den angivna mappen

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, bool recursive)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mailbox | String | Brevlådan som används för att initiera mapp-id-klassen. |
| folder | String | En mapp att söka efter meddelanden i |
| recursive | Boolean | Anger om rekursiv listning eller inte |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) som innehåller meddelanden från den angivna mappen

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, string, MailQuery) {#listmessages_12}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, MailQuery query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mailbox | String | Brevlådan som används för att initiera mapp-id-klassen. |
| folder | String | En mapp att söka efter meddelanden i. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökkriterier för meddelanden. |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_7}

Lista meddelandena i den angivna mappen

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i |
| recursive | Boolean | Anger om rekursiv listning eller inte |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) som innehåller meddelanden från den angivna mappen

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) {#listmessages_4}

Lista meddelandena i den angivna mappen

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options, IEnumerable<PropertyDescriptor> extendedProperties)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i |
| options | ExchangeListMessagesOptions | Anger inställningarna för listningen |
| extendedProperties | IEnumerable`1 | Utökade egenskaper för hämtade meddelanden |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) som innehåller meddelanden från den angivna mappen

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery) {#listmessages_5}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökkriterier för meddelanden. |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_6}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökkriterier för meddelanden. |
| recursive | Boolean | Indikerar om rekursiv listning eller inte. |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery, bool) {#listmessages_11}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query, bool recursive)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökkriterier för meddelanden. |
| recursive | Boolean | Anger om rekursiv listning eller inte. |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_1}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessageInfoCollection ListMessages(IEnumerable<string> iDs)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| iDs | IEnumerable`1 | Uppräkning av meddelande-id |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) som innehåller meddelanden med.

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Lista meddelandena i inkorgen.

```csharp
public ExchangeMessageInfoCollection ListMessages()
```

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) från inkorgen.

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery) {#listmessages_10}

Lista meddelandena i den angivna mappen.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | En mapp att söka efter meddelanden i. |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökkriterier för meddelanden. |

### Returvärde

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)som innehåller meddelanden från den angivna mappen.

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namnutrymme [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
