---
title: StartMonitoringAsync
second_title: Aspose.Email for .NET API Referansı
description: Belirtilen klasör için ileti değişikliklerinin izlenmesini başlatır.
type: docs
weight: 370
url: /tr/net/aspose.email.clients.imap/iasyncimapclient/startmonitoringasync/
---
## IAsyncImapClient.StartMonitoringAsync method

Belirtilen klasör için ileti değişikliklerinin izlenmesini başlatır.

```csharp
public Task StartMonitoringAsync(ImapMonitoringEventHandler callback, 
    ImapMonitoringErrorEventHandler errorCallback, string folderName = "Inbox")
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| callback | ImapMonitoringEventHandler | İzleme işlemi için geri arama işlevi. |
| errorCallback | ImapMonitoringErrorEventHandler | Hata işlemeyi izlemek için geri arama işlevi. Bu geri arama çağrıldığında belirtilen klasörün izlenmesi durdurulur. Geri arama ayrıca bir durum tutucu sağlar, böylece klasör izleme kullanılarak devam ettirilebilir [`ResumeMonitoringAsync`](../../imapclient/resumemonitoringasync) yöntem. |
| folderName | String | İzleme işlemi için klasör. |

### Ayrıca bakınız

* delegate [ImapMonitoringEventHandler](../../imapmonitoringeventhandler)
* delegate [ImapMonitoringErrorEventHandler](../../imapmonitoringerroreventhandler)
* interface [IAsyncImapClient](../../iasyncimapclient)
* ad alanı [Aspose.Email.Clients.Imap](../../iasyncimapclient)
* toplantı [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->