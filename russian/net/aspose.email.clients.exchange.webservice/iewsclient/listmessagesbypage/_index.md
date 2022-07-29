---
title: ListMessagesByPage
second_title: Справочник по Aspose.Email для .NET API
description: Список сообщений в указанной папке.
type: docs
weight: 1150
url: /ru/net/aspose.email.clients.exchange.webservice/iewsclient/listmessagesbypage/
---
## ListMessagesByPage(string, int) {#listmessagesbypage_4}

Список сообщений в указанной папке.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| itemsPerPage | Int32 | Количество элементов на странице |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int) {#listmessagesbypage_2}

Список сообщений в указанной папке.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет критерии поиска. |
| itemsPerPage | Int32 | Количество элементов на странице |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int) {#listmessagesbypage_5}

Список сообщений в указанной папке.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int offset)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| itemsPerPage | Int32 | Количество элементов на странице |
| offset | Int32 | Смещение следующей страницы в поле зрения |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesByPage(string, MailQuery, int, int) {#listmessagesbypage_3}

Список сообщений в указанной папке.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, MailQuery query, int itemsPerPage, 
    int offset)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет критерии поиска. |
| itemsPerPage | Int32 | Количество элементов на странице |
| offset | Int32 | Смещение следующей страницы в поле зрения |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesByPage(string, int, int, ExchangeListMessagesOptions) {#listmessagesbypage_6}

Список сообщений в указанной папке.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, int itemsPerPage, int pageOffset, 
    ExchangeListMessagesOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| itemsPerPage | Int32 | Количество элементов на странице |
| pageOffset | Int32 | Смещение следующего элемента в поле зрения |
| options | ExchangeListMessagesOptions | Задает настройки листинга |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo) {#listmessagesbypage}

Список сообщений в указанной папке.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| pageInfo | PageInfo | Информация о странице |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesByPage(string, PageInfo, ExchangeListMessagesOptions) {#listmessagesbypage_1}

Список сообщений в указанной папке.

```csharp
public ExchangeMessagePageInfo ListMessagesByPage(string folder, PageInfo pageInfo, 
    ExchangeListMessagesOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| pageInfo | PageInfo | Информация о странице |
| options | ExchangeListMessagesOptions | Задает настройки листинга |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessagePageInfo](../../../aspose.email.clients.exchange/exchangemessagepageinfo)
* class [PageInfo](../../../aspose.email.clients/pageinfo)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
