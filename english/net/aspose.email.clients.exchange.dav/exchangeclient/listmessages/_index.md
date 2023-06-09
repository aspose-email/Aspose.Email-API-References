---
title: ExchangeClient.ListMessages
second_title: Aspose.Email for .NET API Reference
description: ExchangeClient method. Lists the messages
type: docs
weight: 280
url: /net/aspose.email.clients.exchange.dav/exchangeclient/listmessages/
---
## ListMessages(string) {#listmessages}

Lists the messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder. |

### Return Value

A [`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_4}

Lists the messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder. |
| maxNumberOfMessages | Int32 | Maximum number of messages |

### Return Value

A [`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_7}

Lists the messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string messageClass, 
    bool recursive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder. |
| messageClass | String | The message class. |
| recursive | Boolean | if set to `true` [recursive]. |

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_3}

List the messages in the specified folder

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder Uri |
| recursive | Boolean | Indicates whether recursive listing or not. |

### Return Value

A collection of message info

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, string) {#listmessages_6}

Lists the messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder. |
| query | String | The query. |

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_2}

Lists the messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The Uri of folder that contains messages. |
| query | MailQuery | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search criteria. |
| recursive | Boolean | Indicates whether recursive listing or not. |

### Return Value

The message info collection.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_1}

Lists the mail message in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder url |
| options | ExchangeListMessagesOptions | Specifies the settings of listing |

### Return Value

A [`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/) collection.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_5}

List the messages in the specified folder

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder Uri |
| maxNumberOfMessages | Int32 | Maximum number of messages |
| options | ExchangeListMessagesOptions | Specifies the settings of listing |

### Return Value

A collection of message info

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions/)
* class [ExchangeClient](../)
* namespace [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient/)
* assembly [Aspose.Email](../../../)


