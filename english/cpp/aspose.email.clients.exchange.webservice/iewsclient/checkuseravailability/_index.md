---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::CheckUserAvailability method"
linktitle: "CheckUserAvailability"
articleTitle: "CheckUserAvailability"
second_title: "Aspose.Email for C++"
description: "Checks users availability within the specified time window."
type: docs
weight: 80
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/checkuseravailability/
---

## CheckUserAvailability (1 of 2) {#checkuseravailability_1}

Checks users availability within the specified time window.

**Returns:** ExchangeUserAvailabilityCollection containing the users availability informaiton.

```cpp
CheckUserAvailability(System::SharedPtr < System::Collections::Specialized::StringCollection > users, System::SharedPtr < DateRange > timeWindow)
```

| Parameter | Description |
| --- | --- |
| users | An users smtp addresses. |
| timeWindow | A time span for the queried user's availability. |

---

## CheckUserAvailability (2 of 2) {#checkuseravailability_2}

Checks user availability within the specified time window.

**Returns:** ExchangeUserAvailability containing user availability information.

```cpp
CheckUserAvailability(System::String user, System::SharedPtr < DateRange > timeWindow)
```

| Parameter | Description |
| --- | --- |
| user | An user smtp address. |
| timeWindow | A time span for the queried user's availability. |

