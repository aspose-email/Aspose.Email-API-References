---
title: CopyMessages
second_title: Справочник по Aspose.Email для .NET API
description: Скопируйте сообщениеeg
type: docs
weight: 500
url: /ru/net/aspose.email.clients.imap/imapclient/copymessages/
---
## CopyMessages(IConnection, int, int, string) {#copymessages}

Скопируйте сообщениеeg

```csharp
public void CopyMessages(IConnection connection, int startSequence, int endSequence, 
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

## CopyMessages(int, int, string) {#copymessages_5}

Копировать сообщения

```csharp
public void CopyMessages(int startSequence, int endSequence, string folderName)
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

## CopyMessages(IConnection, string, string, string) {#copymessages_4}

Копировать сообщения

```csharp
public void CopyMessages(IConnection connection, string startUid, string endUid, string folderName)
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

## CopyMessages(string, string, string) {#copymessages_10}

Копировать сообщения

```csharp
public void CopyMessages(string startUid, string endUid, string folderName)
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

## CopyMessages(IEnumerable&lt;int&gt;, string, bool) {#copymessages_8}

Копировать сообщения

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
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

## CopyMessages(IConnection, IEnumerable&lt;int&gt;, string) {#copymessages_2}

Скопируйте сообщениеeg

```csharp
public void CopyMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
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

## CopyMessages(IEnumerable&lt;int&gt;, string) {#copymessages_7}

Копировать сообщения

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName)
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

## CopyMessages(IConnection, IEnumerable&lt;string&gt;, string) {#copymessages_3}

Копировать сообщения

```csharp
public void CopyMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
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

## CopyMessages(IEnumerable&lt;string&gt;, string) {#copymessages_9}

Копировать сообщения

```csharp
public void CopyMessages(IEnumerable<string> uidSet, string folderName)
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

## CopyMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_1}

Копировать сообщения

```csharp
public void CopyMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## CopyMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_6}

Копировать сообщения

```csharp
public void CopyMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
