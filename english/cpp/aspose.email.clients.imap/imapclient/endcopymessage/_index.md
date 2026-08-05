---
title: "Aspose::Email::Clients::Imap::ImapClient::EndCopyMessage method"
linktitle: "EndCopyMessage"
articleTitle: "EndCopyMessage"
second_title: "Aspose.Email for C++"
description: "Waits for the pending asynchronous operation to complete."
type: docs
weight: 700
url: /cpp/aspose.email.clients.imap/imapclient/endcopymessage/
---

## EndCopyMessage {#endcopymessage}

Waits for the pending asynchronous operation to complete.

**Returns:** If server supports UIDPLUS extension returns unique id of the copied message, otherwise returns null Please, read more https://tools.ietf.org/html/rfc4315

```cpp
EndCopyMessage(System::SharedPtr < System::IAsyncResult > asyncResult)
```

| Parameter | Description |
| --- | --- |
| asyncResult | The reference to the pending asynchronous request to wait for. |

