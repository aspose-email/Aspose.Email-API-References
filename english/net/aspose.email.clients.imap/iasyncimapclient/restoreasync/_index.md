---
title: IAsyncImapClient.RestoreAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Begins to restore imap folders from the given personal storage
type: docs
weight: 320
url: /net/aspose.email.clients.imap/iasyncimapclient/restoreasync/
---
## IAsyncImapClient.RestoreAsync method

Begins to restore imap folders from the given personal storage.

```csharp
public Task RestoreAsync(PersonalStorage pst, RestoreSettings settings, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pst | PersonalStorage | A personal storage containing the backuped imap folders. |
| settings | RestoreSettings | The restore settings |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [PersonalStorage](../../../aspose.email.storage.pst/personalstorage/)
* class [RestoreSettings](../../restoresettings/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


