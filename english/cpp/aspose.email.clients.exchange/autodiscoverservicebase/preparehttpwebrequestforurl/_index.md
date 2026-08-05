---
title: "Aspose::Email::Clients::Exchange::AutodiscoverServiceBase::PrepareHttpWebRequestForUrl method"
linktitle: "PrepareHttpWebRequestForUrl"
articleTitle: "PrepareHttpWebRequestForUrl"
second_title: "Aspose.Email for C++"
description: "Creates an HttpWebRequest instance and initializes it with the appropriate parameters, based on the configuration of this service object."
type: docs
weight: 290
url: /cpp/aspose.email.clients.exchange/autodiscoverservicebase/preparehttpwebrequestforurl/
---

## PrepareHttpWebRequestForUrl {#preparehttpwebrequestforurl}

Creates an HttpWebRequest instance and initializes it with the appropriate parameters, based on the configuration of this service object.

**Returns:** A initialized instance of HttpWebRequest.

```cpp
PrepareHttpWebRequestForUrl(System::SharedPtr < System::Uri > url, bool acceptGzipEncoding, bool allowAutoRedirect)
```

| Parameter | Description |
| --- | --- |
| url | The URL that the HttpWebRequest should target. |
| acceptGzipEncoding | If true, ask server for GZip compressed content. |
| allowAutoRedirect | If true, redirection responses will be automatically followed. |

