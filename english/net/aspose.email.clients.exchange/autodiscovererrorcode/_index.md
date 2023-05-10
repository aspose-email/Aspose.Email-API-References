---
title: Enum AutodiscoverErrorCode
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.Exchange.AutodiscoverErrorCode enum. Defines the error codes that can be returned by the Autodiscover service
type: docs
weight: 3050
url: /net/aspose.email.clients.exchange/autodiscovererrorcode/
---
## AutodiscoverErrorCode enumeration

Defines the error codes that can be returned by the Autodiscover service.

```csharp
public enum AutodiscoverErrorCode
```

### Values

| Name | Value | Description |
| --- | --- | --- |
| NoError | `0` | There was no Error. |
| RedirectAddress | `1` | The caller must follow the e-mail address redirection that was returned by Autodiscover. |
| RedirectUrl | `2` | The caller must follow the URL redirection that was returned by Autodiscover. |
| InvalidUser | `3` | The user that was passed in the request is invalid. |
| InvalidRequest | `4` | The request is invalid. |
| InvalidSetting | `5` | A specified setting is invalid. |
| SettingIsNotAvailable | `6` | A specified setting is not available. |
| ServerBusy | `7` | The server is too busy to process the request. |
| InvalidDomain | `8` | The requested domain is not valid. |
| NotFederated | `9` | The organization is not federated. |
| InternalServerError | `10` | Internal server error. |

### See Also

* namespace [Aspose.Email.Clients.Exchange](../../aspose.email.clients.exchange/)
* assembly [Aspose.Email](../../)


