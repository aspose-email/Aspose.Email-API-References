---
title: "Aspose::Email::Clients::Google::FreebusyQuery::FreebusyQuery constructor"
linktitle: "FreebusyQuery"
articleTitle: "FreebusyQuery"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the FreebusyQuery class."
type: docs
weight: 10
url: /cpp/aspose.email.clients.google/freebusyquery/freebusyquery/
---

## FreebusyQuery (1 of 7) {#freebusyquery_1}

Initializes a new instance of the FreebusyQuery class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
FreebusyQuery()
```

---

## FreebusyQuery (2 of 7) {#freebusyquery_2}

Initializes a new instance of the FreebusyQuery class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
FreebusyQuery(System::DateTime timeMin, System::DateTime timeMax, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> items)
```

| Parameter | Description |
| --- | --- |
| timeMin | The end of the interval for the query. |
| timeMax | The end of the interval for the query. |
| items | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

---

## FreebusyQuery (3 of 7) {#freebusyquery_3}

Initializes a new instance of the FreebusyQuery class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
FreebusyQuery(System::DateTime timeMin, System::DateTime timeMax, System::String timeZone, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> items)
```

| Parameter | Description |
| --- | --- |
| timeMin | The end of the interval for the query. |
| timeMax | The end of the interval for the query. |
| timeZone | Time zone used in the response. Optional. The default is UTC. |
| items | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

---

## FreebusyQuery (4 of 7) {#freebusyquery_4}

Initializes a new instance of the FreebusyQuery class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
FreebusyQuery(System::DateTime timeMin, System::DateTime timeMax, System::String timeZone, System::Nullable< int32_t > groupExpansionMax, System::Nullable< int32_t > calendarExpansionMax, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> items)
```

| Parameter | Description |
| --- | --- |
| timeMin | The end of the interval for the query. |
| timeMax | The end of the interval for the query. |
| timeZone | Time zone used in the response. Optional. The default is UTC. |
| groupExpansionMax | Maximal number of calendar identifiers to be provided for a single group. Optional. An error will be returned for a group with more members than this value. |
| calendarExpansionMax | Maximal number of calendars for which FreeBusy information is to be provided. Optional. |
| items | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

---

## FreebusyQuery (5 of 7) {#freebusyquery_5}

Initializes a new instance of the FreebusyQuery class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
FreebusyQuery(System::DateTime timeMin, System::DateTime timeMax, const System::ArrayPtr< System::String > & items)
```

| Parameter | Description |
| --- | --- |
| timeMin | The end of the interval for the query. |
| timeMax | The end of the interval for the query. |
| items | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

---

## FreebusyQuery (6 of 7) {#freebusyquery_6}

Initializes a new instance of the FreebusyQuery class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
FreebusyQuery(System::DateTime timeMin, System::DateTime timeMax, System::String timeZone, const System::ArrayPtr< System::String > & items)
```

| Parameter | Description |
| --- | --- |
| timeMin | The end of the interval for the query. |
| timeMax | The end of the interval for the query. |
| timeZone | Time zone used in the response. Optional. The default is UTC. |
| items | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

---

## FreebusyQuery (7 of 7) {#freebusyquery_7}

Initializes a new instance of the FreebusyQuery class.

**Returns:** Aspose::Email::Clients::Google::

```cpp
FreebusyQuery(System::DateTime timeMin, System::DateTime timeMax, System::String timeZone, System::Nullable< int32_t > groupExpansionMax, System::Nullable< int32_t > calendarExpansionMax, const System::ArrayPtr< System::String > & items)
```

| Parameter | Description |
| --- | --- |
| timeMin | The end of the interval for the query. |
| timeMax | The end of the interval for the query. |
| timeZone | Time zone used in the response. Optional. The default is UTC. |
| groupExpansionMax | Maximal number of calendar identifiers to be provided for a single group. Optional. An error will be returned for a group with more members than this value. |
| calendarExpansionMax | Maximal number of calendars for which FreeBusy information is to be provided. Optional. |
| items | List of calendars and/or groups to query. Contains identifiers of a calendar or a group. |

