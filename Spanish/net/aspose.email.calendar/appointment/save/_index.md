---
title: Save
second_title: Referencia de la API de Aspose.Email para .NET
description: Guarda la cita en la secuencia con las opciones de guardado especificadas
type: docs
weight: 350
url: /es/net/aspose.email.calendar/appointment/save/
---
## Save(Stream, AppointmentSaveOptions) {#save_2}

Guarda la cita en la secuencia con las opciones de guardado especificadas

```csharp
public void Save(Stream stream, AppointmentSaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| stream | Stream | Un flujo para guardar |
| saveOptions | AppointmentSaveOptions | Unas opciones de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *saveOptions*o*stream* es`nulo` |
| NotSupportedException | las opciones de guardado especificadas no son compatibles |
| NotSupportedException | stream no admite escritura |

### Ver también

* class [AppointmentSaveOptions](../../appointmentsaveoptions)
* class [Appointment](../../appointment)
* espacio de nombres [Aspose.Email.Calendar](../../appointment)
* asamblea [Aspose.Email](../../../)

---

## Save(string) {#save_3}

Guarda la cita en el archivo con formato iCalendar utilizando las opciones de guardado predeterminadas

```csharp
public void Save(string filePath)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Una ruta de archivo |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *filePath* es`nulo`o`vacío` |

### Ver también

* class [Appointment](../../appointment)
* espacio de nombres [Aspose.Email.Calendar](../../appointment)
* asamblea [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveFormat) {#save_4}

Guarda la cita en el archivo con el formato especificado utilizando las opciones de guardado predeterminadas

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
| ArgumentOutOfRangeException | *filePath* es`nulo`o`vacío` |
| NotSupportedException | Las opciones de guardado especificadas no son compatibles |

### Ver también

* enum [AppointmentSaveFormat](../../appointmentsaveformat)
* class [Appointment](../../appointment)
* espacio de nombres [Aspose.Email.Calendar](../../appointment)
* asamblea [Aspose.Email](../../../)

---

## Save(string, AppointmentSaveOptions) {#save_5}

Guarda la cita en el archivo con las opciones de guardado especificadas

```csharp
public void Save(string filePath, AppointmentSaveOptions saveOptions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| filePath | String | Una ruta de archivo |
| saveOptions | AppointmentSaveOptions | Unas opciones de guardado |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentOutOfRangeException | *filePath* es`nulo`o`vacío` |
| ArgumentNullException | *saveOptions* es`nulo` |
| NotSupportedException | Las opciones de guardado especificadas no son compatibles |

### Ver también

* class [AppointmentSaveOptions](../../appointmentsaveoptions)
* class [Appointment](../../appointment)
* espacio de nombres [Aspose.Email.Calendar](../../appointment)
* asamblea [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Guarda la cita en el archivo con formato iCalendar utilizando las opciones de guardado predeterminadas

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

* class [Appointment](../../appointment)
* espacio de nombres [Aspose.Email.Calendar](../../appointment)
* asamblea [Aspose.Email](../../../)

---

## Save(Stream, AppointmentSaveFormat) {#save_1}

Guarda la cita en la secuencia con el formato especificado utilizando las opciones de guardado predeterminadas

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
| NotSupportedException | Las opciones de guardado especificadas no son compatibles |
| NotSupportedException | stream no admite escritura |

### Ver también

* enum [AppointmentSaveFormat](../../appointmentsaveformat)
* class [Appointment](../../appointment)
* espacio de nombres [Aspose.Email.Calendar](../../appointment)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->