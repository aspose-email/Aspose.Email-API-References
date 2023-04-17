---
title: IAsyncImapClient.SelectFolderAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Selects the specified folder
type: docs
weight: 340
url: /net/aspose.email.clients.imap/iasyncimapclient/selectfolderasync/
---
## IAsyncImapClient.SelectFolderAsync method

Selects the specified folder

```csharp
public Task SelectFolderAsync(string folderName, bool? readOnly = false, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | String | Connection to a server |
| folderName | Nullable`1 | Folder to be selected |
| readOnly | IConnection | Specifies whether the folder is to be selected as read-only |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


