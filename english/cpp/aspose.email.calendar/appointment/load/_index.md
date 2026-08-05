---
title: "Aspose::Email::Calendar::Appointment::Load method"
linktitle: "Load"
articleTitle: "Load"
second_title: "Aspose.Email for C++"
description: "Loads Appointment from the stream"
type: docs
weight: 390
url: /cpp/aspose.email.calendar/appointment/load/
---

## Load (1 of 5) {#load_1}

Loads Appointment from the stream

**Returns:** A read Appointment

```cpp
Load(System::SharedPtr < System::IO::Stream > stream)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to load from |

---

## Load (2 of 5) {#load_2}

Loads Appointment from the stream

**Returns:** A read Appointment

```cpp
Load(System::SharedPtr < System::IO::Stream > stream, bool applyLocalTimeZone)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to load from |
| applyLocalTimeZone | Convert time to local timezone |

---

## Load (3 of 5) {#load_3}

Loads Appointment from the stream

**Returns:** A read Appointment

```cpp
Load(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < AppointmentLoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to load from |
| options | Represents appointment load options |

---

## Load (4 of 5) {#load_4}

Loads Appointment from the file. Supported file formats: iCalendar

**Returns:** A read Appointment

```cpp
Load(System::String filePath)
```

| Parameter | Description |
| --- | --- |
| filePath | A file path |

---

## Load (5 of 5) {#load_5}

Loads Appointment from the file. Supported file formats: iCalendar

**Returns:** A read Appointment .

```cpp
Load(System::String filePath, System::SharedPtr < AppointmentLoadOptions > options)
```

| Parameter | Description |
| --- | --- |
| filePath | A file path. |
| options | Represents appointment load options AppointmentLoadOptions . |

