---
title: AppendMessage
second_title: Справочник по Aspose.Email для .NET API
description: Загружает почтовое сообщение в указанную папку
type: docs
weight: 90
url: /ru/net/aspose.email.clients.exchange.dav/exchangeclient/appendmessage/
---
## AppendMessage(string, MailMessage) {#appendmessage}

Загружает почтовое сообщение в указанную папку

```csharp
public string AppendMessage(string folder, MailMessage message)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | Папка, в которую загружается сообщение |
| message | MailMessage | Сообщение для загрузки |

### Возвращаемое значение

URI созданного сообщения

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | Папка не указана |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *message* является`нулевой` |

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

---

## AppendMessage(string, MailMessage, bool) {#appendmessage_1}

Загружает почтовое сообщение в указанную папку

```csharp
public string AppendMessage(string folder, MailMessage message, bool markAsSent)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| folder | String | URI папки, в которую загружается сообщение |
| message | MailMessage | Сообщение для загрузки |
| markAsSent | Boolean | Значение, указывающее, должно ли сообщение быть добавлено как отправленное сообщение или как черновик. |

### Возвращаемое значение

URI созданного сообщения

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | Папка не указана |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception) | *message* является`нулевой` |

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [ExchangeClient](../../exchangeclient)
* пространство имен [Aspose.Email.Clients.Exchange.Dav](../../exchangeclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
