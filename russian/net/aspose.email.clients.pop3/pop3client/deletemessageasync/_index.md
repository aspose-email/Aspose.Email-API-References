---
title: DeleteMessageAsync
second_title: Справочник по Aspose.Email для .NET API
description: Удаляет сообщение
type: docs
weight: 80
url: /ru/net/aspose.email.clients.pop3/pop3client/deletemessageasync/
---
## DeleteMessageAsync(IConnection, int) {#deletemessageasync}

Удаляет сообщение

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Сервер POP3 помечает сообщение как удаленное. Сервер POP3 фактически не удаляет сообщение, пока сеанс POP3 не перейдет в состояние UPDATE.

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string) {#deletemessageasync_2}

Удаляет сообщение

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | Уникальный идентификатор сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Сервер POP3 помечает сообщение как удаленное. Сервер POP3 фактически не удаляет сообщение, пока сеанс POP3 не перейдет в состояние UPDATE.

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(int) {#deletemessageasync_4}

Удаляет сообщение

```csharp
public Task DeleteMessageAsync(int sequenceNumber)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Сервер POP3 помечает сообщение как удаленное. Сервер POP3 фактически не удаляет сообщение, пока сеанс POP3 не перейдет в состояние UPDATE.

### Смотрите также

* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(string) {#deletemessageasync_6}

Удаляет сообщение

```csharp
public Task DeleteMessageAsync(string uniqueId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор сообщения |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Сервер POP3 помечает сообщение как удаленное. Сервер POP3 фактически не удаляет сообщение, пока сеанс POP3 не перейдет в состояние UPDATE.

### Смотрите также

* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, int, CancellationToken) {#deletemessageasync_1}

Удаляет сообщение

```csharp
public Task DeleteMessageAsync(IConnection connection, int sequenceNumber, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Сервер POP3 помечает сообщение как удаленное. Сервер POP3 фактически не удаляет сообщение, пока сеанс POP3 не перейдет в состояние UPDATE.

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(IConnection, string, CancellationToken) {#deletemessageasync_3}

Удаляет сообщение

```csharp
public Task DeleteMessageAsync(IConnection connection, string uniqueId, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | Уникальный идентификатор сообщения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Сервер POP3 помечает сообщение как удаленное. Сервер POP3 фактически не удаляет сообщение, пока сеанс POP3 не перейдет в состояние UPDATE.

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(int, CancellationToken) {#deletemessageasync_5}

Удаляет сообщение

```csharp
public Task DeleteMessageAsync(int sequenceNumber, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Сервер POP3 помечает сообщение как удаленное. Сервер POP3 фактически не удаляет сообщение, пока сеанс POP3 не перейдет в состояние UPDATE.

### Смотрите также

* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

---

## DeleteMessageAsync(string, CancellationToken) {#deletemessageasync_7}

Удаляет сообщение

```csharp
public Task DeleteMessageAsync(string uniqueId, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | Уникальный идентификатор сообщения |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Примечания

Сервер POP3 помечает сообщение как удаленное. Сервер POP3 фактически не удаляет сообщение, пока сеанс POP3 не перейдет в состояние UPDATE.

### Смотрите также

* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
