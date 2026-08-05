---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::ListAppointmentsByPage method"
linktitle: "ListAppointmentsByPage"
articleTitle: "ListAppointmentsByPage"
second_title: "Aspose.Email for C++"
description: "Retrieves page with appointments for calendar folder"
type: docs
weight: 950
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/listappointmentsbypage/
---

## ListAppointmentsByPage (1 of 8) {#listappointmentsbypage_1}

Retrieves page with appointments for calendar folder

**Returns:** Returns page with appointments

```cpp
ListAppointmentsByPage(int32_t itemsPerPage)
```

| Parameter | Description |
| --- | --- |
| itemsPerPage | A number of items in page |

---

## ListAppointmentsByPage (2 of 8) {#listappointmentsbypage_2}

Retrieves page with appointments for calendar folder

**Returns:** Returns page with appointments

```cpp
ListAppointmentsByPage(int32_t itemsPerPage, int32_t itemOffset)
```

| Parameter | Description |
| --- | --- |
| itemsPerPage | A number of items in page |
| itemOffset | An offset of next item in view |

---

## ListAppointmentsByPage (3 of 8) {#listappointmentsbypage_3}

Retrieves page with appointments for calendar folder

**Returns:** Returns page with appointments

```cpp
ListAppointmentsByPage(System::SharedPtr < Tools::Search::MailQuery > query, int32_t itemsPerPage)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents appointments search criteria. |
| itemsPerPage | A number of items in page |

---

## ListAppointmentsByPage (4 of 8) {#listappointmentsbypage_4}

Retrieves page with appointments for calendar folder

**Returns:** Returns page with appointments

```cpp
ListAppointmentsByPage(System::SharedPtr < Tools::Search::MailQuery > query, int32_t itemsPerPage, int32_t itemOffset)
```

| Parameter | Description |
| --- | --- |
| query | MailQuery that represents appointments search criteria. |
| itemsPerPage | A number of items in page |
| itemOffset | An offset of next item in view |

---

## ListAppointmentsByPage (5 of 8) {#listappointmentsbypage_5}

Retrieves page with appointments for specified calendar folder

**Returns:** Returns collection of appointments

```cpp
ListAppointmentsByPage(System::String folderUri, int32_t itemsPerPage)
```

| Parameter | Description |
| --- | --- |
| folderUri | A folder to search appointments in. |
| itemsPerPage | A number of items in page |

---

## ListAppointmentsByPage (6 of 8) {#listappointmentsbypage_6}

Retrieves page with appointments for specified calendar folder

**Returns:** Returns page with appointments

```cpp
ListAppointmentsByPage(System::String folderUri, int32_t itemsPerPage, int32_t itemOffset)
```

| Parameter | Description |
| --- | --- |
| folderUri | A folder to search appointments in. |
| itemsPerPage | A number of items in page |
| itemOffset | An offset of next item in view |

---

## ListAppointmentsByPage (7 of 8) {#listappointmentsbypage_7}

Retrieves page with appointments for specified calendar folder

**Returns:** Returns page with appointments

```cpp
ListAppointmentsByPage(System::String folderUri, System::SharedPtr < Tools::Search::MailQuery > query, int32_t itemsPerPage)
```

| Parameter | Description |
| --- | --- |
| folderUri | A folder to search appointments in. |
| query | MailQuery that represents appointments search criteria. |
| itemsPerPage | A number of items in page |

---

## ListAppointmentsByPage (8 of 8) {#listappointmentsbypage_8}

Retrieves page with appointments for specified calendar folder

**Returns:** Returns page with appointments

```cpp
ListAppointmentsByPage(System::String folderUri, System::SharedPtr < Tools::Search::MailQuery > query, int32_t itemsPerPage, int32_t itemOffset)
```

| Parameter | Description |
| --- | --- |
| folderUri | A folder to search appointments in. |
| query | MailQuery that represents appointments search criteria. |
| itemsPerPage | A number of items in page |
| itemOffset | An offset of next item in view |

