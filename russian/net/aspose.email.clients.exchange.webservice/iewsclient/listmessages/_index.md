---
title: ListMessages
second_title: Справочник по Aspose.Email для .NET API
description: Список сообщений.
type: docs
weight: 1140
url: /ru/net/aspose.email.clients.exchange.webservice/iewsclient/listmessages/
---
## ListMessages(string) {#listmessages_2}

Список сообщений.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка. |

### Возвращаемое значение

А[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions) {#listmessages_3}

Список сообщений.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка. |
| options | ExchangeListMessagesOptions | Задает настройки листинга |

### Возвращаемое значение

А[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, int) {#listmessages_8}

Список сообщений.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений |

### Возвращаемое значение

А[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, int, ExchangeListMessagesOptions) {#listmessages_9}

Список сообщений.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    ExchangeListMessagesOptions options)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений |
| options | ExchangeListMessagesOptions | Задает настройки листинга |

### Возвращаемое значение

А[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, string, bool) {#listmessages_13}

Список сообщений в указанной папке

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, bool recursive)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mailbox | String | Почтовый ящик, который используется для инициализации класса идентификатора папки. |
| folder | String | Папка для поиска сообщений |
| recursive | Boolean | Указывает, рекурсивный листинг или нет |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) который содержит сообщения из указанной папки

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, string, MailQuery) {#listmessages_12}

Список сообщений в указанной папке.

```csharp
public ExchangeMessageInfoCollection ListMessages(string mailbox, string folder, MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| mailbox | String | Почтовый ящик, который используется для инициализации класса идентификатора папки. |
| folder | String | Папка для поиска сообщений. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет критерии поиска сообщения. |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, bool) {#listmessages_7}

Список сообщений в указанной папке

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, bool recursive)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений |
| recursive | Boolean | Указывает, рекурсивный листинг или нет |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) который содержит сообщения из указанной папки

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, ExchangeListMessagesOptions, IEnumerable&lt;PropertyDescriptor&gt;) {#listmessages_4}

Список сообщений в указанной папке

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, 
    ExchangeListMessagesOptions options, IEnumerable<PropertyDescriptor> extendedProperties)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений |
| options | ExchangeListMessagesOptions | Задает настройки листинга |
| extendedProperties | IEnumerable`1 | Расширенные свойства полученных сообщений |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) который содержит сообщения из указанной папки

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* enum [ExchangeListMessagesOptions](../../../aspose.email.clients.exchange/exchangelistmessagesoptions)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery) {#listmessages_5}

Список сообщений в указанной папке.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет критерии поиска сообщений. |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) содержащий сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, MailQuery, bool) {#listmessages_6}

Список сообщений в указанной папке.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, MailQuery query, bool recursive)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет критерии поиска сообщений. |
| recursive | Boolean | Указывает, рекурсивный листинг или нет. |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) содержащий сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery, bool) {#listmessages_11}

Список сообщений в указанной папке.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query, bool recursive)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет критерии поиска сообщения. |
| recursive | Boolean | Указывает, рекурсивный листинг или нет. |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(IEnumerable&lt;string&gt;) {#listmessages_1}

Список сообщений в указанной папке.

```csharp
public ExchangeMessageInfoCollection ListMessages(IEnumerable<string> iDs)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| iDs | IEnumerable`1 | Перечисление идентификаторов сообщений |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) который содержит сообщения с.

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages() {#listmessages}

Список сообщений в папке "Входящие".

```csharp
public ExchangeMessageInfoCollection ListMessages()
```

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection) из папки входящие.

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## ListMessages(string, int, MailQuery) {#listmessages_10}

Список сообщений в указанной папке.

```csharp
public ExchangeMessageInfoCollection ListMessages(string folder, int maxNumberOfMessages, 
    MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка для поиска сообщений. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет критерии поиска сообщения. |

### Возвращаемое значение

[`ExchangeMessageInfoCollection`](../../../aspose.email.clients.exchange/exchangemessageinfocollection)который содержит сообщения из указанной папки.

### Смотрите также

* class [ExchangeMessageInfoCollection](../../../aspose.email.clients.exchange/exchangemessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
