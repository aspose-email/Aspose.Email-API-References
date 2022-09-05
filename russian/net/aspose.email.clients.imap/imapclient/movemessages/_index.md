---
title: MoveMessages
second_title: Справочник по Aspose.Email для .NET API
description: Перемещает сообщение
type: docs
weight: 950
url: /ru/net/aspose.email.clients.imap/imapclient/movemessages/
---
## MoveMessages(IConnection, string, string, string) {#movemessages_8}

Перемещает сообщение

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(string, string, string) {#movemessages_18}

Перемещает сообщение

```csharp
public void MoveMessages(string startUid, string endUid, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string, bool) {#movemessages_7}

Перемещает сообщение

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName, 
    bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string, bool) {#movemessages_17}

Перемещает сообщение

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string) {#movemessages_6}

Перемещает сообщение

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string) {#movemessages_16}

Перемещает сообщение

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор UID для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_3}

Перемещает сообщение

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_13}

Перемещает сообщение

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_2}

Перемещает сообщение

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_12}

Перемещает сообщение

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | Набор ImapMessageInfo |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Смотрите также

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string, bool) {#movemessages_1}

Перемещает сообщениеeg

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(int, int, string, bool) {#movemessages_11}

Перемещает сообщение

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string) {#movemessages}

Перемещает сообщениеeg

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(int, int, string) {#movemessages_10}

Перемещает сообщение

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startSequence | Int32 | Начальный порядковый номер списка сообщений |
| endSequence | Int32 | Конечный порядковый номер списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string, bool) {#movemessages_5}

Перемещает сообщениеeg

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string, bool) {#movemessages_15}

Перемещает сообщение

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string) {#movemessages_4}

Перемещает сообщениеeg

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string) {#movemessages_14}

Перемещает сообщение

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | Набор порядковых номеров для сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(IConnection, string, string, string, bool) {#movemessages_9}

Перемещает сообщение

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## MoveMessages(string, string, string, bool) {#movemessages_19}

Перемещает сообщение

```csharp
public void MoveMessages(string startUid, string endUid, string folderName, bool commitDeletions)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |
| folderName | String | Имя папки, куда нужно переместить сообщение |
| commitDeletions | Boolean | Указывает, должны ли быть зафиксированы удаления. |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
