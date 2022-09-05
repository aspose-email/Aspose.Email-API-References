---
title: ChangeMessageFlagsAsync
second_title: Справочник по Aspose.Email для .NET API
description: Изменяет флаги сообщения
type: docs
weight: 430
url: /ru/net/aspose.email.clients.imap/imapclient/changemessageflagsasync/
---
## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#changemessageflagsasync_41}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#changemessageflagsasync_17}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long) {#changemessageflagsasync_13}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#changemessageflagsasync_36}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags) {#changemessageflagsasync_8}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#changemessageflagsasync_37}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long) {#changemessageflagsasync_9}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_51}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_31}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_23}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_3}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_50}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_30}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_22}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_2}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_55}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_35}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_27}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_7}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_54}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_34}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_26}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_6}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_47}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_43}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_19}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_15}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_46}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_42}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags, 
    long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_18}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_14}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_39}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, CancellationToken) {#changemessageflagsasync_11}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_38}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<ImapMessageInfo> messageInfoSet, 
    ImapMessageFlags flags, long modificationSequence, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, ImapMessageFlags, long, CancellationToken) {#changemessageflagsasync_10}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, 
    IEnumerable<ImapMessageInfo> messageInfoSet, ImapMessageFlags flags, long modificationSequence, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags) {#changemessageflagsasync_48}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags) {#changemessageflagsasync_28}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags) {#changemessageflagsasync_20}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags) {#changemessageflagsasync}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, ImapMessageFlags, long) {#changemessageflagsasync_49}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(string uniqueId, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, ImapMessageFlags, long) {#changemessageflagsasync_29}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(int sequenceNumber, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, ImapMessageFlags, long) {#changemessageflagsasync_21}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string uniqueId, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, ImapMessageFlags, long) {#changemessageflagsasync_1}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int sequenceNumber, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceNumber | Int32 | Порядковый номер сообщения |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags) {#changemessageflagsasync_52}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags) {#changemessageflagsasync_32}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags) {#changemessageflagsasync_24}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags) {#changemessageflagsasync_4}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(string, string, ImapMessageFlags, long) {#changemessageflagsasync_53}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(string startUid, string endUid, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(int, int, ImapMessageFlags, long) {#changemessageflagsasync_33}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(int startSequence, int endSequence, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, string, string, ImapMessageFlags, long) {#changemessageflagsasync_25}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, string startUid, string endUid, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, int, int, ImapMessageFlags, long) {#changemessageflagsasync_5}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, int startSequence, int endSequence, 
    ImapMessageFlags flags, long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags) {#changemessageflagsasync_44}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;int&gt;, ImapMessageFlags) {#changemessageflagsasync_40}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<int> sequenceSet, ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;string&gt;, ImapMessageFlags) {#changemessageflagsasync_16}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<string> uidSet, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IConnection, IEnumerable&lt;int&gt;, ImapMessageFlags) {#changemessageflagsasync_12}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    ImapMessageFlags flags)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно убрать |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## ChangeMessageFlagsAsync(IEnumerable&lt;string&gt;, ImapMessageFlags, long) {#changemessageflagsasync_45}

Изменяет флаги сообщения

```csharp
public Task ChangeMessageFlagsAsync(IEnumerable<string> uidSet, ImapMessageFlags flags, 
    long modificationSequence)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| flags | ImapMessageFlags | Флаги, которые нужно изменить |
| modificationSequence | Int64 | Последовательность модификаций. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc7162 |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageFlags](../../imapmessageflags)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
