---
title: GmailClient
second_title: Справочник по Aspose.Email для .NET API
description: Базовый класс для клиента Gmail
type: docs
weight: 15760
url: /ru/net/aspose.email.clients.google/gmailclient/
---
## GmailClient class

Базовый класс для клиента Gmail

```csharp
public abstract class GmailClient : IBaseGmailClient
```

## Характеристики

| Имя | Описание |
| --- | --- |
| virtual [AccessToken](../../aspose.email.clients.google/gmailclient/accesstoken) { get; set; } | Получает или устанавливает токен доступа OAuth 2.0 В случае, если установлен токен обновления, токен доступа генерируется автоматически. |
| virtual [DefaultEmail](../../aspose.email.clients.google/gmailclient/defaultemail) { get; } | Получает или устанавливает адрес электронной почты по умолчанию |
| virtual [Proxy](../../aspose.email.clients.google/gmailclient/proxy) { get; set; } | Получает или задает прокси. |
| virtual [Timeout](../../aspose.email.clients.google/gmailclient/timeout) { get; set; } | Получает или задает количество миллисекунд ожидания до истечения времени ожидания операции. Значение по умолчанию — 100 000 миллисекунд (100 секунд). |
| static [DefaultTimeout](../../aspose.email.clients.google/gmailclient/defaulttimeout) { get; set; } | Получает или задает значение времени ожидания по умолчанию для экземпляров клиента ActiveSync Значение по умолчанию — 100 000 миллисекунд (100 секунд). |

## Методы

| Имя | Описание |
| --- | --- |
| virtual [Dispose](../../aspose.email.clients.google/gmailclient/dispose)() | Выполняет определяемые приложением задачи, связанные с освобождением, высвобождением или сбросом неуправляемых ресурсов. |
| virtual [RefreshToken](../../aspose.email.clients.google/gmailclient/refreshtoken)() | Обновить токен доступа |
| static [GetInstance](../../aspose.email.clients.google/gmailclient/getinstance#getinstance_1)(string, string) | Получает экземпляр клиента Gmail |
| static [GetInstance](../../aspose.email.clients.google/gmailclient/getinstance#getinstance)(string, IWebProxy, string) | Получает экземпляр клиента Gmail |
| static [GetInstance](../../aspose.email.clients.google/gmailclient/getinstance#getinstance_3)(string, string, string, string) | Получает экземпляр клиента Gmail |
| static [GetInstance](../../aspose.email.clients.google/gmailclient/getinstance#getinstance_2)(string, string, string, IWebProxy, string) | Получает экземпляр клиента Gmail |

### Смотрите также

* interface [IBaseGmailClient](../ibasegmailclient)
* пространство имен [Aspose.Email.Clients.Google](../../aspose.email.clients.google)
* сборка [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
