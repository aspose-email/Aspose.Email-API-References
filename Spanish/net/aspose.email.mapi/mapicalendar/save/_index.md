---
title: Save
second_title: Referencia de la API de Aspose.Email para .NET
description: Guarda el objeto de calendario en el archivo con el formato especificado utilizando las opciones de guardado predeterminadas
type: docs
weight: 220
url: /es/net/aspose.email.mapi/mapicalendar/save/
---
## Save(string, MapiCalendarSaveOptions) {#save_5}

Guarda el objeto de calendario en el archivo con el formato especificado utilizando las opciones de guardado predeterminadas

```csharp
public void Save(string filePath, MapiCalendarSaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Una ruta de archivo |
| saveOptions | MapiCalendarSaveOptions | Unas opciones de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | *filePath* es`nulo`o`vacío` |
| NotSupportedException | las opciones de guardado especificadas no son compatibles |

### Ver también

* class [MapiCalendarSaveOptions](../../mapicalendarsaveoptions)
* class [MapiCalendar](../../mapicalendar)
* espacio de nombres [Aspose.Email.Mapi](../../mapicalendar)
* asamblea [Aspose.Email](../../../)

---

## Save(Stream, MapiCalendarSaveOptions) {#save_2}

Guarda el calendario en la secuencia con las opciones de guardado especificadas

```csharp
public void Save(Stream stream, MapiCalendarSaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo para guardar |
| saveOptions | MapiCalendarSaveOptions | Unas opciones de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *saveOptions*o*stream* es`nulo` |
| NotSupportedException | las opciones de guardado especificadas no son compatibles |
| NotSupportedException | stream no admite escritura |

### Ver también

* class [MapiCalendarSaveOptions](../../mapicalendarsaveoptions)
* class [MapiCalendar](../../mapicalendar)
* espacio de nombres [Aspose.Email.Mapi](../../mapicalendar)
* asamblea [Aspose.Email](../../../)

---

## Save(string) {#save_3}

Guarda el objeto de calendario en el archivo con formato iCalendar utilizando las opciones de guardado predeterminadas

```csharp
public void Save(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Una ruta de archivo |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | *filePath* es`nulo`o`vacío` |

### Ver también

* class [MapiCalendar](../../mapicalendar)
* espacio de nombres [Aspose.Email.Mapi](../../mapicalendar)
* asamblea [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveFormat) {#save_4}

Guarda el objeto de calendario en el archivo con el formato especificado utilizando las opciones de guardado predeterminadas

```csharp
public void Save(string filePath, AppointmentSaveFormat saveFormat)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Una ruta de archivo |
| saveFormat | AppointmentSaveFormat | Un formato de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentException | *filePath* es`nulo`o`vacío` |
| NotSupportedException | El especificado*saveFormat* no es apoyado |

### Ver también

* enum [AppointmentSaveFormat](../../../aspose.email.calendar/appointmentsaveformat)
* class [MapiCalendar](../../mapicalendar)
* espacio de nombres [Aspose.Email.Mapi](../../mapicalendar)
* asamblea [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Guarda el objeto de calendario en el archivo con formato iCalendar utilizando las opciones de guardado predeterminadas

```csharp
public void Save(Stream stream)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo para guardar |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *stream* es`nulo` |
| NotSupportedException | stream no admite escritura |

### Ver también

* class [MapiCalendar](../../mapicalendar)
* espacio de nombres [Aspose.Email.Mapi](../../mapicalendar)
* asamblea [Aspose.Email](../../../)

---

## Save(Stream, AppointmentSaveFormat) {#save_1}

Guarda el objeto de calendario en la secuencia con el formato especificado utilizando las opciones de guardado predeterminadas

```csharp
public void Save(Stream stream, AppointmentSaveFormat saveFormat)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo para guardar |
| saveFormat | AppointmentSaveFormat | Un formato de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *stream* es`nulo` |
| NotSupportedException | El especificado*saveFormat* no es apoyado |
| NotSupportedException | stream no admite escritura |

### Ver también

* enum [AppointmentSaveFormat](../../../aspose.email.calendar/appointmentsaveformat)
* class [MapiCalendar](../../mapicalendar)
* espacio de nombres [Aspose.Email.Mapi](../../mapicalendar)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
