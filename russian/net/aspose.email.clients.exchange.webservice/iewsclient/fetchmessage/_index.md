---
title: FetchMessage
second_title: Справочник по Aspose.Email для .NET API
description: Извлекает сообщение.
type: docs
weight: 810
url: /ru/net/aspose.email.clients.exchange.webservice/iewsclient/fetchmessage/
---
## FetchMessage(string) {#fetchmessage}

Извлекает сообщение.

```csharp
public MailMessage FetchMessage(string messageUri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageUri | String | URI сообщения. |

### Возвращаемое значение

Возвращает сообщение

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

---

## FetchMessage(string, IEnumerable&lt;PropertyDescriptor&gt;) {#fetchmessage_1}

Получает сообщение с server

```csharp
public MailMessage FetchMessage(string messageUri, 
    IEnumerable<PropertyDescriptor> extendedProperties)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| messageUri | String | URI сообщения |
| extendedProperties | IEnumerable`1 | Перечень расширенных свойств |

### Возвращаемое значение

[`MailMessage`](../../../aspose.email/mailmessage) который представляет сообщение электронной почты, если пользовательские свойства были найдены и установлены, вы можете получить к ним доступ, используя[`Headers`](../../../aspose.email/mailmessage/headers) коллекция.

### Исключения

| исключение | условие |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception) | *messageUri* является`нулевой`или же`пустой` |
| [ExchangeException](../../../aspose.email/exchangeexception) | Сообщение не может быть получено |

### Смотрите также

* class [MailMessage](../../../aspose.email/mailmessage)
* class [PropertyDescriptor](../../../aspose.email.mapi/propertydescriptor)
* interface [IEWSClient](../../iewsclient)
* пространство имен [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
