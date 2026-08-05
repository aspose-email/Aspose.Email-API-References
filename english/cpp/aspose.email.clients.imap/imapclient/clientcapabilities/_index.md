---
title: "Aspose::Email::Clients::Imap::ImapClient::ClientCapabilities method"
linktitle: "ClientCapabilities"
articleTitle: "ClientCapabilities"
second_title: "Aspose.Email for C++"
description: "Notifies server which extensions are supported by client."
type: docs
weight: 530
url: /cpp/aspose.email.clients.imap/imapclient/clientcapabilities/
---

## ClientCapabilities (1 of 2) {#clientcapabilities_1}

Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

**Returns:** Returns array with capabilities which are supported by a server.

```cpp
ClientCapabilities(const System::ArrayPtr< System::String > & capabilityNames)
```

| Parameter | Description |
| --- | --- |
| capabilityNames | Array of capabilities which are supported by client |

---

## ClientCapabilities (2 of 2) {#clientcapabilities_2}

Notifies server which extensions are supported by client. Please note, this operation works only in case if server supports RFC5161 See more https://tools.ietf.org/html/rfc5161

**Returns:** Returns array with capabilities which are supported by a server.

```cpp
ClientCapabilities(System::SharedPtr < IConnection > connection, const System::ArrayPtr< System::String > & capabilityNames)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| capabilityNames | Array of capabilities which are supported by client |

