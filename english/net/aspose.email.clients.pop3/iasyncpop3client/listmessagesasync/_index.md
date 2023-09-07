---
title: IAsyncPop3Client.ListMessagesAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncPop3Client method. Lists the messages
type: docs
weight: 130
url: /net/aspose.email.clients.pop3/iasyncpop3client/listmessagesasync/
---
## IAsyncPop3Client.ListMessagesAsync method

Lists the messages.

```csharp
public Task<Pop3MessageInfoCollection> ListMessagesAsync(
    Pop3ListFields fields = Pop3ListFields.Main, bool closeTransaction = false, 
    MailQuery query = null, IConnection connection = null, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | Pop3ListFields | Connection to a server |
| fields | Boolean | The fields that we want get |
| closeTransaction | MailQuery | Indicates if current transaction has to be closed, before the list is retrieved. |
| query | IConnection | The [`MailQuery`](../../../aspose.email.tools.search/mailquery/) object. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [Pop3MessageInfoCollection](../../pop3messageinfocollection/)
* enum [Pop3ListFields](../../pop3listfields/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* interface [IAsyncPop3Client](../)
* namespace [Aspose.Email.Clients.Pop3](../../iasyncpop3client/)
* assembly [Aspose.Email](../../../)


