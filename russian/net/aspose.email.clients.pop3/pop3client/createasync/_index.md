---
title: CreateAsync
second_title: Справочник по Aspose.Email для .NET API
description: Создает новый экземплярPop3Clientaspose.email.clients.pop3/pop3client класс
type: docs
weight: 410
url: /ru/net/aspose.email.clients.pop3/pop3client/createasync/
---
## Pop3Client.CreateAsync method

Создает новый экземпляр[`Pop3Client`](../../pop3client) класс

```csharp
public static Task<IAsyncPop3Client> CreateAsync(string host, string username, 
    IAsyncTokenProvider asyncTokenProvider, int port = 110, 
    SecurityOptions securityOptions = SecurityOptions.Auto, 
    CancellationToken cancellationToken = default)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| host | String | Имя хоста |
| port | String | Номер порта |
| username | IAsyncTokenProvider | Имя пользователя |
| asyncTokenProvider | Int32 | Поставщик маркера доступа. |
| securityOptions | SecurityOptions | Режим безопасности для почтового клиента |
| cancellationToken | CancellationToken | Токен отмены. |

### Смотрите также

* interface [IAsyncPop3Client](../../iasyncpop3client)
* interface [IAsyncTokenProvider](../../../aspose.email.clients/iasynctokenprovider)
* enum [SecurityOptions](../../../aspose.email.clients/securityoptions)
* class [Pop3Client](../../pop3client)
* пространство имен [Aspose.Email.Clients.Pop3](../../pop3client)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
