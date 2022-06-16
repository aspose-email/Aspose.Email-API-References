---
title: ListMessages
second_title: Справочник по Aspose.Email для .NET API
description: Список сообщений.
type: docs
weight: 280
url: /ru/net/aspose.email.clients.exchange.dav/exchangeclient/listmessages/
---
## ListMessages(string) {#listmessages}

Список сообщений.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка. |

### Возвращаемое значение

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_4}

Список сообщений.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений |

### Возвращаемое значение

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_7}

Список сообщений.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string messageClass, 
    bool recursive)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка. |
| messageClass | String | Класс сообщения. |
| recursive | Boolean | , если установлено значение` true` [рекурсивный]. |

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_3}

Список сообщений в указанной папке

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка Uri |
| recursive | Boolean | Указывает, рекурсивный листинг или нет. |

### Возвращаемое значение

Коллекция информации о сообщениях

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, string) {#listmessages_6}

Список сообщений.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, string query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка. |
| query | String | Запрос. |

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_2}

Список сообщений.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Uri папки, содержащей сообщения. |
| query | MailQuery | Объект[`MailQuery`](../../../aspose.email.tools.search/mailquery), представляющий критерии поиска. |
| recursive | Boolean | Указывает, рекурсивный листинг или нет. |

### Возвращаемое значение

Коллекция информации о сообщениях.

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_1}

Список сообщений электронной почты в указанной папке.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | URL-адрес папки |
| options | ExchangeListMessagesOptions | Задает настройки листинг |

### Возвращаемое значение

A[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)коллекция.

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_5}

Список сообщений в указанной папке

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка Uri |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений |
| options | ExchangeListMessagesOptions | Задает настройки листинга |

### Возвращаемое значение

Коллекция информации о сообщениях

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
