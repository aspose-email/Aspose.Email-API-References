---
title: ExtendedCalendar
second_title: Referencia de la API de Aspose.Email para .NET
description: Inicializa una nueva instancia de la clase ExtendedCalendar.
type: docs
weight: 10
url: /es/net/aspose.email.clients.google/extendedcalendar/extendedcalendar/
---
## ExtendedCalendar() {#constructor}

Inicializa una nueva instancia de la clase ExtendedCalendar.

```csharp
public ExtendedCalendar()
```

### Ver también

* class [ExtendedCalendar](../../extendedcalendar)
* espacio de nombres [Aspose.Email.Clients.Google](../../extendedcalendar)
* asamblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string) {#constructor_1}

Inicializa una nueva instancia de la clase ExtendedCalendar.

```csharp
public ExtendedCalendar(string summary)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| summary | String | Título del calendario. |

### Ver también

* class [ExtendedCalendar](../../extendedcalendar)
* espacio de nombres [Aspose.Email.Clients.Google](../../extendedcalendar)
* asamblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string) {#constructor_2}

Inicializa una nueva instancia de la clase ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| id | String | Identificador del recurso. |
| summary | String | Título del calendario. |

### Ver también

* class [ExtendedCalendar](../../extendedcalendar)
* espacio de nombres [Aspose.Email.Clients.Google](../../extendedcalendar)
* asamblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string) {#constructor_3}

Inicializa una nueva instancia de la clase ExtendedCalendar.

```csharp
public ExtendedCalendar(string summary, string description, string location, string timeZone)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| summary | String | Título del calendario. |
| description | String | Descripción del calendario. |
| location | String | Ubicación geográfica del calendario como texto de formato libre. |
| timeZone | String | La zona horaria del calendario. |

### Ver también

* class [ExtendedCalendar](../../extendedcalendar)
* espacio de nombres [Aspose.Email.Clients.Google](../../extendedcalendar)
* asamblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string) {#constructor_4}

Inicializa una nueva instancia de la clase ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| id | String | Identificador del recurso. |
| summary | String | Título del calendario. |
| description | String | Descripción del calendario. |
| location | String | Ubicación geográfica del calendario como texto de formato libre. |
| timeZone | String | La zona horaria del calendario. |

### Ver también

* class [ExtendedCalendar](../../extendedcalendar)
* espacio de nombres [Aspose.Email.Clients.Google](../../extendedcalendar)
* asamblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_5}

Inicializa una nueva instancia de la clase ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string summary, string description, string location, 
    string timeZone, string summaryOverride, string colorId, string backgroundColor, 
    string foregroundColor, bool hidden, bool selected, AccessRole accessRole, 
    KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| id | String | Identificador del recurso. |
| summary | String | Título del calendario. |
| description | String | Descripción del calendario. |
| location | String | Ubicación geográfica del calendario como texto de formato libre. |
| timeZone | String | La zona horaria del calendario. |
| summaryOverride | String | El resumen que el usuario autenticado ha establecido para este calendario. |
| colorId | String | El color del calendario. Este es un ID que hace referencia a una entrada en la sección "calendario" de la definición de colores (consulte el extremo "colores"). |
| backgroundColor | String | El color principal del calendario en el formato '#0088aa'. Esta propiedad reemplaza la propiedad colorId basada en índice. |
| foregroundColor | String | El color de primer plano del calendario en el formato '#ffffff'. Esta propiedad reemplaza la propiedad colorId basada en índice. |
| hidden | Boolean | Si el calendario se ha ocultado de la lista. El valor predeterminado es falso. |
| selected | Boolean | Si el contenido del calendario aparece en la interfaz de usuario del calendario. El valor predeterminado es falso. |
| accessRole | AccessRole | El rol de acceso efectivo que tiene el usuario autenticado en el calendario. Solo lectura. Los valores posibles son: |
| defaultReminders | KeyValuePair`2[] | Los recordatorios predeterminados que tiene el usuario autenticado para este calendario. |
| primary | Boolean | Si el calendario es el calendario principal del usuario autenticado. Solo lectura. El valor predeterminado es falso. |

### Ver también

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* espacio de nombres [Aspose.Email.Clients.Google](../../extendedcalendar)
* asamblea [Aspose.Email](../../../)

---

## ExtendedCalendar(string, string, string, string, string, string, string, string, string, string, bool, bool, AccessRole, KeyValuePair&lt;ReminderMethods, int&gt;[], bool) {#constructor_6}

Inicializa una nueva instancia de la clase ExtendedCalendar.

```csharp
public ExtendedCalendar(string id, string eTag, string summary, string description, 
    string location, string timeZone, string summaryOverride, string colorId, 
    string backgroundColor, string foregroundColor, bool hidden, bool selected, 
    AccessRole accessRole, KeyValuePair<ReminderMethods, int>[] defaultReminders, bool primary)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| id | String | Identificador del recurso. |
| eTag | String | Una etiqueta de entidad |
| summary | String | Título del calendario. |
| description | String | Descripción del calendario. |
| location | String | Ubicación geográfica del calendario como texto de formato libre. |
| timeZone | String | La zona horaria del calendario. |
| summaryOverride | String | El resumen que el usuario autenticado ha establecido para este calendario. |
| colorId | String | El color del calendario. Este es un ID que hace referencia a una entrada en la sección "calendario" de la definición de colores (consulte el extremo "colores"). |
| backgroundColor | String | El color principal del calendario en el formato '#0088aa'. Esta propiedad reemplaza la propiedad colorId basada en índice. |
| foregroundColor | String | El color de primer plano del calendario en el formato '#ffffff'. Esta propiedad reemplaza la propiedad colorId basada en índice. |
| hidden | Boolean | Si el calendario se ha ocultado de la lista. El valor predeterminado es falso. |
| selected | Boolean | Si el contenido del calendario aparece en la interfaz de usuario del calendario. El valor predeterminado es falso. |
| accessRole | AccessRole | El rol de acceso efectivo que tiene el usuario autenticado en el calendario. Solo lectura. Los valores posibles son: |
| defaultReminders | KeyValuePair`2[] | Los recordatorios predeterminados que tiene el usuario autenticado para este calendario. |
| primary | Boolean | Si el calendario es el calendario principal del usuario autenticado. Solo lectura. El valor predeterminado es falso. |

### Ver también

* enum [AccessRole](../../accessrole)
* enum [ReminderMethods](../../remindermethods)
* class [ExtendedCalendar](../../extendedcalendar)
* espacio de nombres [Aspose.Email.Clients.Google](../../extendedcalendar)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
