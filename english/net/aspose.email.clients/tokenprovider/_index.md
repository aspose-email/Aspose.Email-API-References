---
title: Class TokenProvider
second_title: Aspose.Email for .NET API Reference
description: Aspose.Email.Clients.TokenProvider class. Class TokenProvider allows to retrieve access token for mail services
type: docs
weight: 15820
url: /net/aspose.email.clients/tokenprovider/
---
## TokenProvider class

Class TokenProvider allows to retrieve access token for mail services.

```csharp
public class TokenProvider : ITokenProvider
```

## Properties

| Name | Description |
| --- | --- |
| virtual [ClientId](../../aspose.email.clients/tokenprovider/clientid/) { get; } | The client ID obtained during application registration. |
| virtual [ClientSecret](../../aspose.email.clients/tokenprovider/clientsecret/) { get; } | The client secret obtained during application registration. |
| virtual [ExtraParameters](../../aspose.email.clients/tokenprovider/extraparameters/) { get; } | Gets extra parameters for request |
| virtual [Login](../../aspose.email.clients/tokenprovider/login/) { get; set; } | Gets or sets login for basic authorization |
| virtual [Password](../../aspose.email.clients/tokenprovider/password/) { get; set; } | Gets or sets password for basic authorization |
| virtual [RefreshToken](../../aspose.email.clients/tokenprovider/refreshtoken/) { get; } | OAuth 2.0 refresh token |
| virtual [RequestUrl](../../aspose.email.clients/tokenprovider/requesturl/) { get; } | The url to obtain access token. |
| virtual [UseBasicAuthorization](../../aspose.email.clients/tokenprovider/usebasicauthorization/) { get; set; } | Gets or sets value which indicates whether basic authorization is used |

## Methods

| Name | Description |
| --- | --- |
| static [GetInstance](../../aspose.email.clients/tokenprovider/getinstance/)(string, string, string, string) | Gets an instance of the OutlookTokenProvider for defined parameters. |
| virtual [Dispose](../../aspose.email.clients/tokenprovider/dispose/)() | Performs releasing resources. |
| virtual [GetAccessToken](../../aspose.email.clients/tokenprovider/getaccesstoken/#getaccesstoken)() | Gets oAuth access token. If token exists and its expiration date is not expired returns current token, otherwise requests new token from a server. |
| virtual [GetAccessToken](../../aspose.email.clients/tokenprovider/getaccesstoken/#getaccesstoken_1)(bool) | Gets oAuth access token. |

## Other Members

| Name | Description |
| --- | --- |
| static class [Google](../../aspose.email.clients/tokenprovider.google) | Provides an instance of the TokenProvider for Google mail server |
| static class [Outlook](../../aspose.email.clients/tokenprovider.outlook) | Provides an instance of the TokenProvider for Outlook mail server |

### See Also

* interface [ITokenProvider](../itokenprovider/)
* namespace [Aspose.Email.Clients](../../aspose.email.clients/)
* assembly [Aspose.Email](../../)


