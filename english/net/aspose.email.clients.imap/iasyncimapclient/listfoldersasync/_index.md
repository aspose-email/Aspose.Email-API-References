---
title: IAsyncImapClient.ListFoldersAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Gets the list of subfolders in the specified folder
type: docs
weight: 220
url: /net/aspose.email.clients.imap/iasyncimapclient/listfoldersasync/
---
## IAsyncImapClient.ListFoldersAsync method

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder = null, 
    bool loadFullInfo = false, ListFoldersOptions options = ListFoldersOptions.None, 
    ListFoldersReturnOptions returnOptions = ListFoldersReturnOptions.None, 
    IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| options | ListFoldersOptions | Options for operation |
| returnOptions | ListFoldersReturnOptions | Return options for operation |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* enum [ListFoldersOptions](../../listfoldersoptions/)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


