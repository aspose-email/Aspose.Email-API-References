---
title: IEWSClient.MarkAllItems
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Marks all items in specified folders
type: docs
weight: 1240
url: /net/aspose.email.clients.exchange.webservice/iewsclient/markallitems/
---
## MarkAllItems(bool, params string[]) {#markallitems_2}

Marks all items in specified folders.

```csharp
public void MarkAllItems(bool read, params string[] folderIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| read | Boolean | Sets the read/unread state to messages in specified folder. True to mark messages in the folder as read. False to mark messages as unread. |
| folderIds | String[] | List of folder uri for processing. |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## MarkAllItems(bool, bool, params string[]) {#markallitems_1}

Marks all items in specified folders.

```csharp
public void MarkAllItems(bool read, bool suppressReadReceipts, params string[] folderIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| read | Boolean | Sets the read/unread state to messages in specified folder. True to mark messages in the folder as read. False to mark messages as unread. |
| suppressReadReceipts | Boolean | True to suppress sending read receipts for messages; otherwise, false. |
| folderIds | String[] | List of folder uri for processing. |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## MarkAllItems(bool, bool, IEnumerable&lt;string&gt;) {#markallitems}

Marks all items in specified folders.

```csharp
public void MarkAllItems(bool read, bool suppressReadReceipts, IEnumerable<string> folderIds)
```

| Parameter | Type | Description |
| --- | --- | --- |
| read | Boolean | Sets the read/unread state to messages in specified folder. True to mark messages in the folder as read. False to mark messages as unread. |
| suppressReadReceipts | Boolean | True to suppress sending read receipts for messages; otherwise, false. |
| folderIds | IEnumerable`1 | List of folder uri for processing. |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


