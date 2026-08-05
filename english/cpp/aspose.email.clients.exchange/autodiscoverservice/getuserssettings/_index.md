---
title: "Aspose::Email::Clients::Exchange::AutodiscoverService::GetUsersSettings method"
linktitle: "GetUsersSettings"
articleTitle: "GetUsersSettings"
second_title: "Aspose.Email for C++"
description: "Retrieves the specified settings for a set of users."
type: docs
weight: 180
url: /cpp/aspose.email.clients.exchange/autodiscoverservice/getuserssettings/
---

## GetUsersSettings {#getuserssettings}

Retrieves the specified settings for a set of users.

**Returns:** A GetUserSettingsResponseCollection object containing the responses for each individual user.

```cpp
GetUsersSettings(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> userSmtpAddresses, const System::ArrayPtr< UserSettingName > & userSettingNames)
```

| Parameter | Description |
| --- | --- |
| userSmtpAddresses | The SMTP addresses of the users. |
| userSettingNames | The user setting names. |

