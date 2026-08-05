---
title: "Aspose::Email::Clients::Exchange::AutodiscoverService::GetUserSettings method"
linktitle: "GetUserSettings"
articleTitle: "GetUserSettings"
second_title: "Aspose.Email for C++"
description: "Gets the user settings using Autodiscover SOAP service."
type: docs
weight: 170
url: /cpp/aspose.email.clients.exchange/autodiscoverservice/getusersettings/
---

## GetUserSettings (1 of 2) {#getusersettings_1}

Gets the user settings using Autodiscover SOAP service.

**Returns:** System::SharedPtr < GetUserSettingsResponseCollection > Aspose::Email::Clients::Exchange::

```cpp
GetUserSettings(System::SharedPtr < System::Collections::Generic::ListExt< System::String >> smtpAddresses, System::SharedPtr < System::Collections::Generic::ListExt< UserSettingName >> settings)
```

| Parameter | Description |
| --- | --- |
| smtpAddresses | The SMTP addresses of the users. |
| settings | The settings. |

---

## GetUserSettings (2 of 2) {#getusersettings_2}

Retrieves the specified settings for single SMTP address.

**Returns:** A UserResponse object containing the requested settings for the specified user.

```cpp
GetUserSettings(System::String userSmtpAddress, const System::ArrayPtr< UserSettingName > & userSettingNames)
```

| Parameter | Description |
| --- | --- |
| userSmtpAddress | The SMTP addresses of the user. |
| userSettingNames | The user setting names. |

