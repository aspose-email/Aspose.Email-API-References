---
title: ListMessagesAsync
second_title: Справочник по Aspose.Email для .NET API
description: Получает список сообщений в текущей папке.
type: docs
weight: 880
url: /ru/net/aspose.email.clients.imap/imapclient/listmessagesasync/
---
## ListMessagesAsync(int, CancellationToken) {#listmessagesasync_28}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* отрицательно. |

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_17}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка для получения сообщений. |
| modificationSequence | Int64 | Последовательность модификации |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |
| messageExtraFields | IEnumerable`1 | Список дополнительных параметров для сообщения, которое будет запрошено. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Получает список сообщений в текущей папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string) {#listmessagesasync_12}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка для получения сообщений. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_6}

Получает список сообщений в текущей папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long) {#listmessagesasync_10}

Получает список сообщений в текущей папке, у которых последовательность модификации больше указанного значения. Подробнее см. https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| modificationSequence | Int64 | Последовательность модификации |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool) {#listmessagesasync_15}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка для получения сообщений. |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Получает список сообщений в текущей папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync()
```

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;) {#listmessagesasync_31}

Получает список сообщений в текущей папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Список дополнительных параметров для сообщения, которое будет запрошено. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_25}

Получает список сообщений в текущей папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(string) {#listmessagesasync_33}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool) {#listmessagesasync_36}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;) {#listmessagesasync_37}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |
| messageExtraFields | IEnumerable`1 | Список дополнительных параметров для сообщения, которое будет запрошено. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(long) {#listmessagesasync_29}

Получает список сообщений в текущей папке, у которых последовательность модификации больше указанного значения. Подробнее см. https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| modificationSequence | Int64 | Последовательность модификации |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int) {#listmessagesasync_13}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Расположение сообщений |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_2}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int) {#listmessagesasync_3}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_21}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int) {#listmessagesasync_34}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Расположение сообщений |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int) {#listmessagesasync_22}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int) {#listmessagesasync_8}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* отрицательно. |

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(int) {#listmessagesasync_27}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(int maxNumberOfMessages)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* отрицательно. |

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, long, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_18}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    long modificationSequence, bool retrieveRecursively, IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка для получения сообщений. |
| modificationSequence | Int64 | Последовательность модификации |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |
| messageExtraFields | IEnumerable`1 | Список дополнительных параметров для сообщения, которое будет запрошено. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_20}

Получает список сообщений в текущей папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, CancellationToken) {#listmessagesasync_19}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка для получения сообщений. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_7}

Получает список сообщений в текущей папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool retrieveRecursively, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, long, CancellationToken) {#listmessagesasync_11}

Получает список сообщений в текущей папке, у которых последовательность модификации больше указанного значения. Подробнее см. https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| modificationSequence | Int64 | Последовательность модификации |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, bool, CancellationToken) {#listmessagesasync_16}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Папка для получения сообщений. |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_41}

Получает список сообщений в текущей папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_32}

Получает список сообщений в текущей папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IEnumerable<string> messageExtraFields, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageExtraFields | IEnumerable`1 | Список дополнительных параметров для сообщения, которое будет запрошено. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_26}

Получает список сообщений в текущей папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(bool retrieveRecursively, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(string, CancellationToken) {#listmessagesasync_40}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, CancellationToken) {#listmessagesasync_39}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(string, bool, IEnumerable&lt;string&gt;, CancellationToken) {#listmessagesasync_38}

Получает список сообщений в указанной папке

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, 
    bool retrieveRecursively, IEnumerable<string> messageExtraFields, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка для получения сообщений. |
| retrieveRecursively | Boolean | Указывает, должны ли сообщения извлекаться рекурсивно. |
| messageExtraFields | IEnumerable`1 | Список дополнительных параметров для сообщения, которое будет запрошено. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(long, CancellationToken) {#listmessagesasync_30}

Получает список сообщений в текущей папке, у которых последовательность модификации больше указанного значения. Подробнее см. https://tools.ietf.org/html/rfc7162

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(long modificationSequence, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| modificationSequence | Int64 | Последовательность модификации |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, string, MailQuery, int, CancellationToken) {#listmessagesasync_14}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, string folderName, 
    MailQuery query, int maxNumberOfMessages, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| folderName | String | Расположение сообщений |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_5}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, int, CancellationToken) {#listmessagesasync_4}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_24}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(string, MailQuery, int, CancellationToken) {#listmessagesasync_35}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(string folderName, MailQuery query, 
    int maxNumberOfMessages, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Расположение сообщений |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, int, CancellationToken) {#listmessagesasync_23}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(MailQuery query, int maxNumberOfMessages, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) который представляет поисковый запрос. |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Коллекция объектов ImapMessageInfo.

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, int, CancellationToken) {#listmessagesasync_9}

Получает список сообщений в текущей папке.

```csharp
public Task<ImapMessageInfoCollection> ListMessagesAsync(IConnection connection, 
    int maxNumberOfMessages, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| maxNumberOfMessages | Int32 | Максимальное количество сообщений. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Исключения

| исключение | условие |
| --- | --- |
| ArgumentOutOfRangeException | *maxNumberOfMessages* отрицательно. |

### Смотрите также

* class [ImapMessageInfoCollection](../../imapmessageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
