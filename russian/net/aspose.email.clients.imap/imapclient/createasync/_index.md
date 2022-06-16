---
title: CreateAsync
second_title: Справочник по Aspose.Email для .NET API
description: Создает новый экземпляр классаImapClientaspose.email.clients.imap/imapclient
type: docs
weight: 1320
url: /ru/net/aspose.email.clients.imap/imapclient/createasync/
---
## ImapClient.CreateAsync method

Создает новый экземпляр класса[`ImapClient`](../../imapclient)

```csharp
public static Task<IAsyncImapClient> CreateAsync(string host, string username, 
    IAsyncTokenProvider asyncTokenProvider, int port = 143, 
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

* interface [IAsyncImapClient](../../iasyncimapclient)
* interface [IAsyncTokenProvider](../../../aspose.email.clients/iasynctokenprovider)
* enum [SecurityOptions](../../../aspose.email.clients/securityoptions)
* class [ImapClient](../../imapclient)
* пространство имен [Aspose.Email.Clients.Imap](../../imapclient)
* сборка [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->