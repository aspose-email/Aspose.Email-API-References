---
title: AppendMessage
second_title: Справочник по Aspose.Email для .NET API
description: Загружает почтовое сообщение в текущую папку Если текущая папка не указана используется папка по умолчанию.
type: docs
weight: 360
url: /ru/net/aspose.email.clients.imap/imapclient/appendmessage/
---
## AppendMessage(IConnection, MailMessage) {#appendmessage}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public string AppendMessage(IConnection connection, MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| message | MailMessage | Отправить сообщение быть загруженным |

### Возвращаемое значение

Уникальный идентификатор добавленного сообщения

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessage(IConnection, string, MailMessage) {#appendmessage_2}

Загружает почтовое сообщение в указанную папку

```csharp
public string AppendMessage(IConnection connection, string folderName, MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к сервер |
| folderName | String | Папка, которая будет получать почтовое сообщение |
| message | MailMessage | Почтовое сообщение для загрузки |

### Возвращаемое значение

Уникальный идентификатор добавленного сообщения

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessage(IConnection, string) {#appendmessage_1}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public string AppendMessage(IConnection connection, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Соединение с сервером |
| fileName | String | Имя файла ( *.eml) почтового сообщения, которое будет загружено |

### Возвращаемое значение

Уникальный идентификатор добавленного сообщения

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessage(IConnection, string, string) {#appendmessage_3}

Загружает почтовое сообщение в указанную папку

```csharp
public string AppendMessage(IConnection connection, string folderName, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| connection | IConnection | Подключение к сервер |
| имя_папки | String | Папка, которая будет получать почтовое сообщение |
| fileName | String | Имя файла (*. eml) почтового сообщения, которое будет загружено |

### Возвращаемое значение

Уникальный идентификатор добавленного сообщения

### Смотрите также

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessage(MailMessage) {#appendmessage_4}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public string AppendMessage(MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| message | MailMessage | Почтовое сообщение для загрузки |

### Возвращаемое значение

Уникальный идентификатор добавленное сообщение

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessage(string, MailMessage) {#appendmessage_6}

Загружает почтовое сообщение в указанную папку

```csharp
public string AppendMessage(string folderName, MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка, которая получит почтовое сообщение |
| message | MailMessage | Почтовое сообщение для загрузки |

### Возвращаемое значение

Уникальный идентификатор добавленного сообщения

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessage(string) {#appendmessage_5}

Загружает почтовое сообщение в текущую папку Если текущая папка не указана, используется папка по умолчанию.

```csharp
public string AppendMessage(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла (*.eml) почтового сообщения, которое будет загружено |

### Возвращаемое значение

Уникальный идентификатор добавленного сообщения

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessage(string, string) {#appendmessage_7}

Загружает почтовое сообщение в указанную папку

```csharp
public string AppendMessage(string folderName, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folderName | String | Папка, которая получит почтовое сообщение |
| fileName | String | Имя файла (*.eml) почтового сообщения, которое будет загружено |

### Возвращаемое значение

Уникальный идентификатор добавленного сообщения

### Смотрите также

* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
