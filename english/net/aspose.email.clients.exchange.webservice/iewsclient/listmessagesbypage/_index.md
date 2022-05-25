---
title: ListMessagesByPage
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 1150
url: /net/aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/
---
## IEWSClient.ListMessagesByPage method (1 of 7)

List the messages in the specified folder.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| itemsPerPage | Int32 | A number of items in page |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessagesByPage method (2 of 7)

List the messages in the specified folder.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search criteria. |
| itemsPerPage | Int32 | A number of items in page |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessagesByPage method (3 of 7)

List the messages in the specified folder.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int offset)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| itemsPerPage | Int32 | A number of items in page |
| offset | Int32 | An offset of next page in view |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessagesByPage method (4 of 7)

List the messages in the specified folder.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage, 
    int offset)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) that represents search criteria. |
| itemsPerPage | Int32 | A number of items in page |
| offset | Int32 | An offset of next page in view |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessagesByPage method (5 of 7)

List the messages in the specified folder.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int pageOffset, 
    ExchangeListMessagesOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| itemsPerPage | Int32 | A number of items in page |
| pageOffset | Int32 | An offset of next item in view |
| options | ExchangeListMessagesOptions | Specifies the settings of listing |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessagesByPage method (6 of 7)

List the messages in the specified folder.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| pageInfo | PageInfo | A page info |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

---

## IEWSClient.ListMessagesByPage method (7 of 7)

List the messages in the specified folder.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo, 
    ExchangeListMessagesOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folder | String | A folder to search messages in. |
| pageInfo | PageInfo | A page info |
| options | ExchangeListMessagesOptions | Specifies the settings of listing |

### Return Value

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) that contains messages from the specified folder.

### See Also

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
