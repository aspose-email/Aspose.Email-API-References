---
title: CommitDeletes
second_title: Справочник по Aspose.Email для .NET API
description: Подтвердить удаление
type: docs
weight: 460
url: /ru/net/aspose.email.clients.imap/imapclient/commitdeletes/
---
## CommitDeletes() {#commitdeletes}

Подтвердить удаление

```csharp
public void CommitDeletes()
```

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletes(int) {#commitdeletes_6}

Подтвердить удаление

```csharp
public void CommitDeletes(int sleep)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| sleep | Int32 | Время ожидания завершения операции в миллисекундах |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletes(IEnumerable&lt;string&gt;) {#commitdeletes_7}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IEnumerable<string> uidSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uidSet | IEnumerable`1 | Набор уникальных идентификаторов для сообщений |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletes(string) {#commitdeletes_8}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(string uniqueId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| uniqueId | String | UID сообщения |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletes(string, string) {#commitdeletes_9}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(string startUid, string endUid)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, IEnumerable&lt;string&gt;) {#commitdeletes_3}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IConnection connection, IEnumerable<string> uidSet)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uidSet | IEnumerable`1 | Набор уникальных идентификаторов для сообщений |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, string) {#commitdeletes_4}

Подтвердить удаление

```csharp
public void CommitDeletes(IConnection connection, string uniqueId)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| uniqueId | String | UID сообщения |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, string, string) {#commitdeletes_5}

Зафиксировать удаление Этот метод работает, только если сервер поддерживает расширение UIDPLUS. Пожалуйста, прочитайте больше https://tools.ietf.org/html/rfc4315

```csharp
public void CommitDeletes(IConnection connection, string startUid, string endUid)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| startUid | String | Начальный UID списка сообщений |
| endUid | String | Конечный UID списка сообщений |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletes(IConnection) {#commitdeletes_1}

Подтвердить удаление

```csharp
public void CommitDeletes(IConnection connection)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## CommitDeletes(IConnection, int) {#commitdeletes_2}

Подтвердить удаление

```csharp
public void CommitDeletes(IConnection connection, int sleep)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к серверу |
| sleep | Int32 | Время ожидания завершения операции в миллисекундах |

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
