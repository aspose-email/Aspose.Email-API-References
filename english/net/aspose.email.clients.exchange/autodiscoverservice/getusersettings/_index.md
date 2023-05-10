---
title: AutodiscoverService.GetUserSettings
second_title: Aspose.Email for .NET API Reference
description: AutodiscoverService method. Retrieves the specified settings for single SMTP address
type: docs
weight: 70
url: /net/aspose.email.clients.exchange/autodiscoverservice/getusersettings/
---
## AutodiscoverService.GetUserSettings method

Retrieves the specified settings for single SMTP address.

```csharp
public GetUserSettingsResponse GetUserSettings(string userSmtpAddress, 
    params UserSettingName[] userSettingNames)
```

| Parameter | Type | Description |
| --- | --- | --- |
| userSmtpAddress | String | The SMTP addresses of the user. |
| userSettingNames | UserSettingName[] | The user setting names. |

### Return Value

A UserResponse object containing the requested settings for the specified user.

## Remarks

This method handles will run the entire Autodiscover "discovery" algorithm and will follow address and URL redirections.

### See Also

* class [GetUserSettingsResponse](../../getusersettingsresponse/)
* enum [UserSettingName](../../usersettingname/)
* class [AutodiscoverService](../)
* namespace [Aspose.Email.Clients.Exchange](../../autodiscoverservice/)
* assembly [Aspose.Email](../../../)


