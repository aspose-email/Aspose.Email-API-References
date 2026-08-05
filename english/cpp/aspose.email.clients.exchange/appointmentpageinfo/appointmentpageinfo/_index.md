---
title: "Aspose::Email::Clients::Exchange::AppointmentPageInfo::AppointmentPageInfo constructor"
linktitle: "AppointmentPageInfo"
articleTitle: "AppointmentPageInfo"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the AppointmentPageInfo class"
type: docs
weight: 10
url: /cpp/aspose.email.clients.exchange/appointmentpageinfo/appointmentpageinfo/
---

## AppointmentPageInfo (1 of 6) {#appointmentpageinfo_1}

Initializes a new instance of the AppointmentPageInfo class

**Returns:** Aspose::Email::Clients::Exchange::

```cpp
AppointmentPageInfo()
```

---

## AppointmentPageInfo (2 of 6) {#appointmentpageinfo_2}

Initializes a new instance of the AppointmentPageInfo class

**Returns:** Aspose::Email::Clients::Exchange::

```cpp
AppointmentPageInfo(int32_t itemsPerPage)
```

| Parameter | Description |
| --- | --- |
| itemsPerPage | A number of items in page |

---

## AppointmentPageInfo (3 of 6) {#appointmentpageinfo_3}

Initializes a new instance of the AppointmentPageInfo class

**Returns:** Aspose::Email::Clients::Exchange::

```cpp
AppointmentPageInfo(int32_t itemsPerPage, int32_t offset)
```

| Parameter | Description |
| --- | --- |
| offset | offset in view of a page |
| itemsPerPage | A number of items in page |

---

## AppointmentPageInfo (4 of 6) {#appointmentpageinfo_4}

Initializes a new instance of the AppointmentPageInfo class

**Returns:** Aspose::Email::Clients::Exchange::

```cpp
AppointmentPageInfo(int32_t totalCount, int32_t itemsPerPage, int32_t offset, bool lastPage)
```

| Parameter | Description |
| --- | --- |
| totalCount | total count of items in view |
| offset | offset in view of a page |
| lastPage | Indicates whether current page is last page in view |
| itemsPerPage | A number of items in page |

---

## AppointmentPageInfo (5 of 6) {#appointmentpageinfo_5}

Initializes a new instance of the AppointmentPageInfo class

**Returns:** Aspose::Email::Clients::Exchange::

```cpp
AppointmentPageInfo(System::SharedPtr < Calendar::AppointmentCollection > items, int32_t itemsPerPage, int32_t offset)
```

| Parameter | Description |
| --- | --- |
| items | A collection of ExchangeMessageInfo objects |
| offset | offset in view of a page |
| itemsPerPage | A number of items in page |

---

## AppointmentPageInfo (6 of 6) {#appointmentpageinfo_6}

Initializes a new instance of the AppointmentPageInfo class

**Returns:** Aspose::Email::Clients::Exchange::

```cpp
AppointmentPageInfo(System::SharedPtr < Calendar::AppointmentCollection > items, int32_t totalCount, int32_t itemsPerPage, int32_t offset, bool lastPage)
```

| Parameter | Description |
| --- | --- |
| items | A collection of ExchangeMessageInfo objects |
| totalCount | Total count of items in view |
| offset | offset in view of a page |
| lastPage | Indicates whether current page is last page in view |
| itemsPerPage | A number of items in page |

