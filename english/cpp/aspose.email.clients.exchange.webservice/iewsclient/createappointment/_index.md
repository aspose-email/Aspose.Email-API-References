---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::CreateAppointment method"
linktitle: "CreateAppointment"
articleTitle: "CreateAppointment"
second_title: "Aspose.Email for C++"
description: "Creates appointment."
type: docs
weight: 120
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/createappointment/
---

## CreateAppointment (1 of 3) {#createappointment_1}

Creates appointment.

**Returns:** Returns appointment UID

```cpp
CreateAppointment(System::SharedPtr < Calendar::Appointment > appointment)
```

| Parameter | Description |
| --- | --- |
| appointment | Calendar appointment. |

---

## CreateAppointment (2 of 3) {#createappointment_2}

Creates appointment.

**Returns:** Returns appointment UID

```cpp
CreateAppointment(System::SharedPtr < Calendar::Appointment > appointment, System::String folderUri)
```

| Parameter | Description |
| --- | --- |
| appointment | Calendar appointment. |
| folderUri | An uri of appointments parent folder. |

---

## CreateAppointment (3 of 3) {#createappointment_3}

Creates appointment.

**Returns:** Returns PidLidGlobalObjectId as base64 string

```cpp
CreateAppointment(System::SharedPtr < Mapi::MapiCalendar > appointment, System::String folderUri, bool suppressInvitations)
```

| Parameter | Description |
| --- | --- |
| appointment | Calendar appointment. |
| folderUri | An uri of appointments parent folder. |
| suppressInvitations | If true, invitations won't be sent to attendees. |

