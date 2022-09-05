---
title: ListMessagesAsync
second_title: Справочник по Aspose.Email для .NET API
description: Список сообщений. Получает информацию для поиска message
type: docs
weight: 300
url: /ru/net/aspose.email.clients.pop3/pop3client/listmessagesasync/
---
## ListMessagesAsync(IConnection) {#listmessagesasync_1}

Список сообщений. Получает информацию для поиска message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool) {#listmessagesasync_8}

Список сообщений. Получает информацию для поиска message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| closeTransaction | Boolean | Указывает, должна ли текущая транзакция быть закрыта перед получением списка. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery) {#listmessagesasync_6}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) объект. |

### Возвращаемое значение

Коллекция объектов Pop3MessageInfo.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields) {#listmessagesasync_2}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| fields | Pop3ListFields | Поля, которые мы хотим получить |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery) {#listmessagesasync_3}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| fields | Pop3ListFields | Поля, которые мы хотим получить |
| closeTransaction | Boolean | Указывает, должна ли текущая транзакция быть закрыта перед получением списка. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) объект. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync() {#listmessagesasync}

Список сообщений. Получает информацию для поиска message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync()
```

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(bool) {#listmessagesasync_17}

Список сообщений. Получает информацию для поиска message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| closeTransaction | Boolean | Указывает, должна ли текущая транзакция быть закрыта перед получением списка. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery) {#listmessagesasync_15}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) объект. |

### Возвращаемое значение

Коллекция объектов Pop3MessageInfo.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields) {#listmessagesasync_11}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fields | Pop3ListFields | Поля, которые мы хотим получить |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery) {#listmessagesasync_12}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fields | Pop3ListFields | Поля, которые мы хотим получить |
| closeTransaction | Boolean | Указывает, должна ли текущая транзакция быть закрыта перед получением списка. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) объект. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, CancellationToken) {#listmessagesasync_10}

Список сообщений. Получает информацию для поиска message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, bool, CancellationToken) {#listmessagesasync_9}

Список сообщений. Получает информацию для поиска message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    bool closeTransaction, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| closeTransaction | Boolean | Указывает, должна ли текущая транзакция быть закрыта перед получением списка. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, MailQuery, CancellationToken) {#listmessagesasync_7}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, MailQuery query, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) объект. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Коллекция объектов Pop3MessageInfo.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, CancellationToken) {#listmessagesasync_5}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| fields | Pop3ListFields | Поля, которые мы хотим получить |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(IConnection, Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_4}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(IConnection connection, 
    Pop3ListFields fields, bool closeTransaction, MailQuery query, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| fields | Pop3ListFields | Поля, которые мы хотим получить |
| closeTransaction | Boolean | Указывает, должна ли текущая транзакция быть закрыта перед получением списка. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) объект. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(CancellationToken) {#listmessagesasync_19}

Список сообщений. Получает информацию для поиска message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(bool, CancellationToken) {#listmessagesasync_18}

Список сообщений. Получает информацию для поиска message

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(bool closeTransaction, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| closeTransaction | Boolean | Указывает, должна ли текущая транзакция быть закрыта перед получением списка. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(MailQuery, CancellationToken) {#listmessagesasync_16}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(MailQuery query, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) объект. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Коллекция объектов Pop3MessageInfo.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, CancellationToken) {#listmessagesasync_14}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fields | Pop3ListFields | Поля, которые мы хотим получить |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Обратите внимание, что сообщения, помеченные как удаленные, не отображаются в списке.

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## ListMessagesAsync(Pop3ListFields, bool, MailQuery, CancellationToken) {#listmessagesasync_13}

Список сообщений.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(Pop3ListFields fields, 
    bool closeTransaction, MailQuery query, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fields | Pop3ListFields | Поля, которые мы хотим получить |
| closeTransaction | Boolean | Указывает, должна ли текущая транзакция быть закрыта перед получением списка. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery) объект. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection)
* enum [Pop3ListFields](../../pop3listfields)
* class [MailQuery](../../../aspose.email.tools.search/mailquery)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
