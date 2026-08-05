---
title: "Aspose::Email::Clients::Google::FreebusyResponse::FreebusyResponse constructor"
linktitle: "FreebusyResponse"
articleTitle: "FreebusyResponse"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the FreebusyResponse class."
type: docs
weight: 10
url: /cpp/aspose.email.clients.google/freebusyresponse/freebusyresponse/
---

## FreebusyResponse (1 of 3) {#freebusyresponse_1}

Initializes a new instance of the FreebusyResponse class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
FreebusyResponse()
```

---

## FreebusyResponse (2 of 3) {#freebusyresponse_2}

Initializes a new instance of the FreebusyResponse class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
FreebusyResponse(System::DateTime timeMin, System::DateTime timeMax)
```

| Parameter | Description |
| --- | --- |
| timeMin | The start of the interval for the query. |
| timeMax | The end of the interval for the query. |

---

## FreebusyResponse (3 of 3) {#freebusyresponse_3}

Initializes a new instance of the FreebusyResponse class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
FreebusyResponse(System::DateTime timeMin, System::DateTime timeMax, System::SharedPtr < System::Collections::Generic::Dictionary< System::String, System::SharedPtr < FreebusyGroupInfo >>> groups, System::SharedPtr < System::Collections::Generic::Dictionary< System::String, System::SharedPtr < FreebusyCalendarInfo >>> calendars)
```

| Parameter | Description |
| --- | --- |
| timeMin | The start of the interval for the query. |
| timeMax | The end of the interval for the query. |
| groups | Expansion of groups. |
| calendars | List of free/busy information for calendars. |

