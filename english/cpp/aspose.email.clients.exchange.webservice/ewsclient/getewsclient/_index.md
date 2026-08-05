---
title: "Aspose::Email::Clients::Exchange::WebService::EWSClient::GetEwsClient method"
linktitle: "GetEwsClient"
articleTitle: "GetEwsClient"
second_title: "Aspose.Email for C++"
description: "GetEwsClient of EWSClient."
type: docs
weight: 40
url: /cpp/aspose.email.clients.exchange.webservice/ewsclient/getewsclient/
---

## GetEwsClient (1 of 2) {#getewsclient_1}

**Returns:** static System::SharedPtr < IEWSClient > Aspose::Email::Clients::Exchange::WebService::

```cpp
GetEwsClient(ExchangeVersion serverVersion, bool formBasedAuthenticationRequired, System::String formBasedAuthenticationLocation, System::String mailboxUri, System::SharedPtr < System::Net::ICredentials > credentials, System::SharedPtr < System::Net::WebProxy > proxy, System::SharedPtr < IHttpWebRequestCreate > httpWebRequestCreate)
```

| Parameter | Description |
| --- | --- |
| serverVersion |  |
| formBasedAuthenticationRequired |  |
| formBasedAuthenticationLocation |  |
| mailboxUri |  |
| credentials |  |
| proxy |  |
| httpWebRequestCreate |  |

---

## GetEwsClient (2 of 2) {#getewsclient_2}

**Returns:** static System::SharedPtr < IEWSClient > Aspose::Email::Clients::Exchange::WebService::

```cpp
GetEwsClient(System::String mailboxUri, System::SharedPtr < System::Net::ICredentials > credentials, System::SharedPtr < System::Net::WebProxy > proxy, System::SharedPtr < IHttpWebRequestCreate > httpWebRequestCreate, System::SharedPtr < ServiceBinding::IExchangeServiceBindingPrepare > exchangeServiceBindingPrepare, System::SharedPtr < System::Collections::Generic::Dictionary< System::String, System::String >> headers)
```

| Parameter | Description |
| --- | --- |
| mailboxUri |  |
| credentials |  |
| proxy |  |
| httpWebRequestCreate |  |
| exchangeServiceBindingPrepare |  |
| headers |  |

