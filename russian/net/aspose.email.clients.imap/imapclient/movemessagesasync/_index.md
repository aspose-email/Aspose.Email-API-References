---
title: MoveMessagesAsync
second_title: Справочник по Aspose.Email для .NET API
description: Перемещает сообщениеeg
type: docs
weight: 960
url: /ru/net/aspose.email.clients.imap/imapclient/movemessagesasync/
---
## MoveMessagesAsync(IConnection, int, int, string, bool) {#movemessagesasync_1}

Перемещает сообщениеeg

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, bool) {#movemessagesasync_21}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string) {#movemessagesasync}

Перемещает сообщениеeg

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string) {#movemessagesasync_20}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, bool) {#movemessagesasync_9}

Перемещает сообщениеeg

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, bool) {#movemessagesasync_29}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string) {#movemessagesasync_8}

Перемещает сообщениеeg

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string) {#movemessagesasync_28}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, bool) {#movemessagesasync_17}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, bool) {#movemessagesasync_37}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string) {#movemessagesasync_16}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string) {#movemessagesasync_36}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, bool) {#movemessagesasync_13}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, bool) {#movemessagesasync_33}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string) {#movemessagesasync_12}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string) {#movemessagesasync_32}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessagesasync_5}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessagesasync_25}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessagesasync_4}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessagesasync_24}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string, bool, CancellationToken) {#movemessagesasync_2}

Перемещает сообщениеeg

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, bool, CancellationToken) {#movemessagesasync_22}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, int, int, string, CancellationToken) {#movemessagesasync_3}

Перемещает сообщениеeg

```csharp
public Task MoveMessagesAsync(IConnection connection, int startSequence, int endSequence, 
    string folderName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(int, int, string, CancellationToken) {#movemessagesasync_23}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(int startSequence, int endSequence, string folderName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, bool, CancellationToken) {#movemessagesasync_10}

Перемещает сообщениеeg

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, bool, CancellationToken) {#movemessagesasync_30}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;int&gt;, string, CancellationToken) {#movemessagesasync_11}

Перемещает сообщениеeg

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<int> sequenceSet, 
    string folderName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;int&gt;, string, CancellationToken) {#movemessagesasync_31}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<int> sequenceSet, string folderName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, bool, CancellationToken) {#movemessagesasync_18}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, bool, CancellationToken) {#movemessagesasync_38}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, string, string, string, CancellationToken) {#movemessagesasync_19}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, string startUid, string endUid, 
    string folderName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(string, string, string, CancellationToken) {#movemessagesasync_39}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(string startUid, string endUid, string folderName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, bool, CancellationToken) {#movemessagesasync_14}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, bool, CancellationToken) {#movemessagesasync_34}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, bool commitDeletions, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;string&gt;, string, CancellationToken) {#movemessagesasync_15}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<string> uidSet, 
    string folderName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;string&gt;, string, CancellationToken) {#movemessagesasync_35}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<string> uidSet, string folderName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) {#movemessagesasync_6}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, bool, CancellationToken) {#movemessagesasync_26}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#movemessagesasync_7}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessagesAsync(IEnumerable&lt;ImapMessageInfo&gt;, string, CancellationToken) {#movemessagesasync_27}

Перемещает сообщение

```csharp
public Task MoveMessagesAsync(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    CancellationToken token)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| token | CancellationToken | Распространяет уведомление о том, что операции должны быть отменены. |

### Возвращаемое значение

Объект задачи с делегатом для этой операции

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
