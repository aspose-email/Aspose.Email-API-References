---
title: UnselectFolderAsync
second_title: Справочник по Aspose.Email для .NET API
description: Безвозвратно удаляет все сообщения помеченные как удаленные для текущей выбранной папки и удаляет выбранное состояние для этой папки.
type: docs
weight: 1260
url: /ru/net/aspose.email.clients.imap/imapclient/unselectfolderasync/
---
## UnselectFolderAsync(IConnection) {#unselectfolderasync_1}

Безвозвратно удаляет все сообщения, помеченные как удаленные для текущей выбранной папки, и удаляет выбранное состояние для этой папки.

```csharp
public Task UnselectFolderAsync(IConnection connection)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## UnselectFolderAsync() {#unselectfolderasync}

Безвозвратно удаляет все сообщения, помеченные как удаленные для текущей выбранной папки, и удаляет выбранное состояние для этой папки.

```csharp
public Task UnselectFolderAsync()
```

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, bool) {#unselectfolderasync_2}

Отменяет выбор папки, которая выбрана в данный момент. если свойство doNotExpunge равно true, все сообщения, помеченные как удаленные, удаляются, иначе удаление отменяется. Обратите внимание, эта операция работает только в том случае, если сервер поддерживает RFC3691 Подробнее https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(IConnection connection, bool doNotExpunge)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| doNotExpunge | Boolean | Указывает, следует ли удалять сообщения, помеченные как удаленные. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## UnselectFolderAsync(bool) {#unselectfolderasync_5}

Отменяет выбор папки, которая выбрана в данный момент. если свойство doNotExpunge равно true, все сообщения, помеченные как удаленные, удаляются, иначе удаление отменяется. Обратите внимание, эта операция работает только в том случае, если сервер поддерживает RFC3691 Подробнее https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| doNotExpunge | Boolean | Указывает, следует ли удалять сообщения, помеченные как удаленные. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, CancellationToken) {#unselectfolderasync_4}

Безвозвратно удаляет все сообщения, помеченные как удаленные для текущей выбранной папки, и удаляет выбранное состояние для этой папки.

```csharp
public Task UnselectFolderAsync(IConnection connection, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## UnselectFolderAsync(CancellationToken) {#unselectfolderasync_7}

Безвозвратно удаляет все сообщения, помеченные как удаленные для текущей выбранной папки, и удаляет выбранное состояние для этой папки.

```csharp
public Task UnselectFolderAsync(CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, bool, CancellationToken) {#unselectfolderasync_3}

Отменяет выбор папки, которая выбрана в данный момент. если свойство doNotExpunge равно true, все сообщения, помеченные как удаленные, удаляются, иначе удаление отменяется. Обратите внимание, эта операция работает только в том случае, если сервер поддерживает RFC3691 Подробнее https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(IConnection connection, bool doNotExpunge, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| doNotExpunge | Boolean | Указывает, следует ли удалять сообщения, помеченные как удаленные. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## UnselectFolderAsync(bool, CancellationToken) {#unselectfolderasync_6}

Отменяет выбор папки, которая выбрана в данный момент. если свойство doNotExpunge равно true, все сообщения, помеченные как удаленные, удаляются, иначе удаление отменяется. Обратите внимание, эта операция работает только в том случае, если сервер поддерживает RFC3691 Подробнее https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| doNotExpunge | Boolean | Указывает, следует ли удалять сообщения, помеченные как удаленные. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
