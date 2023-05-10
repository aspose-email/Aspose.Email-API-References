---
title: IEWSClient.ListMessages
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Lists the messages
type: docs
weight: 1140
url: /net/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---
## ListMessages(string) {#listmessages_2}

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
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_3}

Lists the messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder. |
| options | ExchangeListMessagesOptions | Specifies the settings of listing |

### Return Value

A [`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_8}

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
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_9}

Lists the messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder. |
| maxNumberOfMessages | Int32 | Maximum number of messages |
| options | ExchangeListMessagesOptions | Specifies the settings of listing |

### Return Value

A [`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_13}

List the messages in the specified folder

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, bool recursive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | String | The mailbox that is used to initialize the folder id class. |
| folder | String | A folder to search messages in |
| recursive | Boolean | Indicates whether recursive listing or not |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/) that contains messages from the specified folder

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, string, MailQuery) {#listmessages_12}

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | String | The mailbox that is used to initialize the folder id class. |
| folder | String | A folder to search messages in. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents message search criteria. |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/) that contains messages from the specified folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_7}

List the messages in the specified folder

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in |
| recursive | Boolean | Indicates whether recursive listing or not |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/) that contains messages from the specified folder

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) {#listmessages_4}

List the messages in the specified folder

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options, IEnumerable<PropertyDescriptor> extendedProperties)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in |
| options | ExchangeListMessagesOptions | Specifies the settings of listing |
| extendedProperties | IEnumerable`1 | Extended properties of retrieved messages |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/) that contains messages from the specified folder

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions/)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery) {#listmessages_5}

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents message search criteria. |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/) that contains messages from the specified folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_6}

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents message search criteria. |
| recursive | Boolean | Indicates whether recursive listing or not. |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/) that contains messages from the specified folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery, bool) {#listmessages_11}

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query, bool recursive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents message search criteria. |
| recursive | Boolean | Indicates whether recursive listing or not. |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/) that contains messages from the specified folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_1}

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(IEnumerable<string> iDs)
```

| Parameter | Type | Description |
| --- | --- | --- |
| iDs | IEnumerable`1 | Enumeration of message ids |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/) that contains messages with.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

List the messages in the inbox folder.

```csharp
public ExchangeMessageInfoCollection ListMessages()
```

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/) from inbox folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery) {#listmessages_10}

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents message search criteria. |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection/) that contains messages from the specified folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


