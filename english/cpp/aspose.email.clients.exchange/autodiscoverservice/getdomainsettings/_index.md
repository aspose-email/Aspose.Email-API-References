---
title: "Aspose::Email::Clients::Exchange::AutodiscoverService::GetDomainSettings method"
linktitle: "GetDomainSettings"
articleTitle: "GetDomainSettings"
second_title: "Aspose.Email for C++"
description: "Retrieves the specified settings for a set of domains."
type: docs
weight: 140
url: /cpp/aspose.email.clients.exchange/autodiscoverservice/getdomainsettings/
---

## GetDomainSettings (1 of 3) {#getdomainsettings_1}

Retrieves the specified settings for a set of domains.

**Returns:** A GetDomainSettingsResponseCollection object containing the responses for each individual domain.

```cpp
GetDomainSettings(System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> domains, System::Nullable< WebService::ExchangeVersion > requestedVersion, const System::ArrayPtr< DomainSettingName > & domainSettingNames)
```

| Parameter | Description |
| --- | --- |
| domains | The SMTP addresses of the domains. |
| requestedVersion | Requested version of the Exchange service. |
| domainSettingNames | The domain setting names. |

---

## GetDomainSettings (2 of 3) {#getdomainsettings_2}

Gets the domain settings using Autodiscover SOAP service.

**Returns:** GetDomainSettingsResponse collection.

```cpp
GetDomainSettings(System::SharedPtr < System::Collections::Generic::ListExt< System::String >> domains, System::SharedPtr < System::Collections::Generic::ListExt< DomainSettingName >> settings, System::Nullable< WebService::ExchangeVersion > requestedVersion)
```

| Parameter | Description |
| --- | --- |
| domains | The domains. |
| settings | The settings. |
| requestedVersion | Requested version of the Exchange service. |

---

## GetDomainSettings (3 of 3) {#getdomainsettings_3}

Retrieves the specified settings for a domain.

**Returns:** A DomainResponse object containing the requested settings for the specified domain.

```cpp
GetDomainSettings(System::String domain, System::Nullable< WebService::ExchangeVersion > requestedVersion, const System::ArrayPtr< DomainSettingName > & domainSettingNames)
```

| Parameter | Description |
| --- | --- |
| domain | The domain. |
| requestedVersion | Requested version of the Exchange service. |
| domainSettingNames | The domain setting names. |

