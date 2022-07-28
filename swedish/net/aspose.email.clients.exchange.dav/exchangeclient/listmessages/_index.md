---
title: ListMessages
second_title: Aspose.Email för .NET API-referens
description: Listar meddelandena.
type: docs
weight: 280
url: /sv/net/aspose.email.clients.exchange.dav/exchangeclient/listmessages/
---
## ListMessages(string) {#listmessages}

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
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_4}

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
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_7}

Listar meddelandena.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string messageClass, 
    bool recursive)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | Mappen. |
| messageClass | String | Meddelandeklassen. |
| recursive | Boolean | om inställt på`Sann` [rekursiv]. |

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_3}

Lista meddelandena i den angivna mappen

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | Mappen Uri |
| recursive | Boolean | Anger om rekursiv listning eller inte. |

### Returvärde

En samling meddelandeinformation

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, string) {#listmessages_6}

Listar meddelandena.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string query)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | Mappen. |
| query | String | Frågan. |

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_2}

Listar meddelandena.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | Uri för mappen som innehåller meddelanden. |
| query | MailQuery | De[`MailQuery`](../../../aspose.email.tools.search/mailquery) som representerar sökkriterier. |
| recursive | Boolean | Anger om rekursiv listning eller inte. |

### Returvärde

Insamlingen av meddelandeinformation.

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_1}

Listar e-postmeddelandet i den angivna mappen.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | Mappens url |
| options | ExchangeListMessagesOptions | Anger inställningarna för listningen |

### Returvärde

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) samling.

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_5}

Lista meddelandena i den angivna mappen

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| folder | String | Mappen Uri |
| maxNumberOfMessages | Int32 | Maximalt antal meddelanden |
| options | ExchangeListMessagesOptions | Anger inställningarna för listningen |

### Returvärde

En samling meddelandeinformation

### Se även

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* namnutrymme [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
