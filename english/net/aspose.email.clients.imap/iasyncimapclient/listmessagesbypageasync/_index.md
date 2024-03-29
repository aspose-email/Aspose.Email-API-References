---
title: IAsyncImapClient.ListMessagesByPageAsync
second_title: Aspose.Email for .NET API Reference
description: IAsyncImapClient method. Gets the list of messages
type: docs
weight: 250
url: /net/aspose.email.clients.imap/iasyncimapclient/listmessagesbypageasync/
---
## ListMessagesByPageAsync(int, int, PageSettings, CancellationToken) {#listmessagesbypageasync_1}

Gets the list of messages

```csharp
public Task<ImapPageInfo> ListMessagesByPageAsync(int itemsPerPage, int pageOffset, 
    PageSettings settings, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| itemsPerPage | Int32 | A number of items in page |
| pageOffset | Int32 | An offset of next page in view |
| settings | PageSettings | The settings. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapPageInfo](../../imappageinfo/)
* class [PageSettings](../../pagesettings/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)

---

## ListMessagesByPageAsync(MailQuery, PageInfo, PageSettings, CancellationToken) {#listmessagesbypageasync}

Gets the list of messages

```csharp
public Task<ImapPageInfo> ListMessagesByPageAsync(MailQuery query, PageInfo pageInfo, 
    PageSettings settings, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents search query. |
| pageInfo | PageInfo | The next page to retrieve. |
| settings | PageSettings | The settings. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapPageInfo](../../imappageinfo/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [PageInfo](../../../aspose.email.clients/pageinfo/)
* class [PageSettings](../../pagesettings/)
* interface [IAsyncImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../iasyncimapclient/)
* assembly [Aspose.Email](../../../)


