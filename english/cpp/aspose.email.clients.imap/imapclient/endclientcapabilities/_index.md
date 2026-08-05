---
title: "Aspose::Email::Clients::Imap::ImapClient::EndClientCapabilities method"
linktitle: "EndClientCapabilities"
articleTitle: "EndClientCapabilities"
second_title: "Aspose.Email for C++"
description: "Waits for the pending asynchronous operation to complete."
type: docs
weight: 680
url: /cpp/aspose.email.clients.imap/imapclient/endclientcapabilities/
---

## EndClientCapabilities {#endclientcapabilities}

Waits for the pending asynchronous operation to complete. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

**Returns:** Returns array with capabilities which are supported by a server.

```cpp
EndClientCapabilities(System::SharedPtr < System::IAsyncResult > asyncResult)
```

| Parameter | Description |
| --- | --- |
| asyncResult | The reference to the pending asynchronous request to wait for. |

