---
title: ListMessages
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 1140
url: /net/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---
## IEWSClient.ListMessages method (1 of 14)

Lists the messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder. |

## Return Value

A [`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (2 of 14)

Lists the messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder. |
| options | ExchangeListMessagesOptions | Specifies the settings of listing |

## Return Value

A [`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (3 of 14)

Lists the messages.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | The folder. |
| maxNumberOfMessages | Int32 | Maximum number of messages |

## Return Value

A [`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (4 of 14)

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

## Return Value

A [`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (5 of 14)

List the messages in the specified folder

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, bool recursive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | String | The mailbox that is used to initialize the folder id class. |
| folder | String | A folder to search messages in |
| recursive | Boolean | Indicates whether recursive listing or not |

## Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (6 of 14)

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| mailbox | String | The mailbox that is used to initialize the folder id class. |
| folder | String | A folder to search messages in. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents message search criteria. |

## Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (7 of 14)

List the messages in the specified folder

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in |
| recursive | Boolean | Indicates whether recursive listing or not |

## Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (8 of 14)

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

## Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (9 of 14)

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents message search criteria. |

## Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (10 of 14)

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents message search criteria. |
| recursive | Boolean | Indicates whether recursive listing or not. |

## Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (11 of 14)

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query, bool recursive)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents message search criteria. |
| recursive | Boolean | Indicates whether recursive listing or not. |

## Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (12 of 14)

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(IEnumerable<string> iDs)
```

| Parameter | Type | Description |
| --- | --- | --- |
| iDs | IEnumerable`1 | Enumeration of message ids |

## Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages with.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (13 of 14)

List the messages in the inbox folder.

```csharp
public ExchangeMessageInfoCollection ListMessages()
```

## Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) from inbox folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessages method (14 of 14)

List the messages in the specified folder.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| maxNumberOfMessages | Int32 | Maximum number of messages. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents message search criteria. |

## Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
