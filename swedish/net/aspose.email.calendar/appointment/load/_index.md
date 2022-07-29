---
title: Load
second_title: Aspose.Email för .NET API-referens
description: LaddarAppointmentaspose.email.calendar/appointment från filen. Filformat som stöds iCalendar
type: docs
weight: 20
url: /sv/net/aspose.email.calendar/appointment/load/
---
## Load(string) {#load_3}

Laddar[`Appointment`](../../appointment) från filen. Filformat som stöds: iCalendar

```csharp
public static Appointment Load(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | En filsökväg |

### Returvärde

En läsning[`Appointment`](../../appointment)

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | *filePath* är`null`eller`tömma` |

### Se även

* class [Appointment](../../appointment)
* namnutrymme [Aspose.Email.Calendar](../../appointment)
* hopsättning [Aspose.Email](../../../)

---

## Load(string, AppointmentLoadOptions) {#load_4}

Laddar[`Appointment`](../../appointment) från filen. Filformat som stöds: iCalendar En filsökväg.Representerar laddningsalternativ för möten[`AppointmentLoadOptions`](../../appointmentloadoptions). En läsning[`Appointment`](../../appointment).

```csharp
public static Appointment Load(string filePath, AppointmentLoadOptions options)
```

### Se även

* class [AppointmentLoadOptions](../../appointmentloadoptions)
* class [Appointment](../../appointment)
* namnutrymme [Aspose.Email.Calendar](../../appointment)
* hopsättning [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Laddar[`Appointment`](../../appointment) från stream

```csharp
public static Appointment Load(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | En ström att ladda från |

### Returvärde

En läsning[`Appointment`](../../appointment)

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *stream* är`null` |
| NotSupportedException | *stream* stöder inte läsning |

### Se även

* class [Appointment](../../appointment)
* namnutrymme [Aspose.Email.Calendar](../../appointment)
* hopsättning [Aspose.Email](../../../)

---

## Load(Stream, bool) {#load_2}

Laddar[`Appointment`](../../appointment) från stream

```csharp
public static Appointment Load(Stream stream, bool applyLocalTimeZone)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | En ström att ladda från |
| applyLocalTimeZone | Boolean | Konvertera tid till lokal tidszon |

### Returvärde

En läsning[`Appointment`](../../appointment)

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *stream* är`null` |
| NotSupportedException | *stream* stöder inte läsning |

### Se även

* class [Appointment](../../appointment)
* namnutrymme [Aspose.Email.Calendar](../../appointment)
* hopsättning [Aspose.Email](../../../)

---

## Load(Stream, AppointmentLoadOptions) {#load_1}

Laddar[`Appointment`](../../appointment) från stream

```csharp
public static Appointment Load(Stream stream, AppointmentLoadOptions options)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | En ström att ladda från |
| options | AppointmentLoadOptions | Representerar laddningsalternativ för möten |

### Returvärde

En läsning[`Appointment`](../../appointment)

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *stream* är`null` |
| NotSupportedException | *stream* stöder inte läsning |

### Se även

* class [AppointmentLoadOptions](../../appointmentloadoptions)
* class [Appointment](../../appointment)
* namnutrymme [Aspose.Email.Calendar](../../appointment)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->