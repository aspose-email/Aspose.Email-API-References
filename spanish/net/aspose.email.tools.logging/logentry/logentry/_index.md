---
title: LogEntry
second_title: Referencia de la API de Aspose.Email para .NET
description: Inicializar una nueva instancia de unLogEntryaspose.email.tools.logging/logentry clase.
type: docs
weight: 10
url: /es/net/aspose.email.tools.logging/logentry/logentry/
---
## LogEntry() {#constructor}

Inicializar una nueva instancia de un[`LogEntry`](../../logentry) clase.

```csharp
public LogEntry()
```

### Ver también

* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(string) {#constructor_5}

Inicializar una nueva instancia de un[`LogEntry`](../../logentry) clase.

```csharp
public LogEntry(string message)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| message | String | El mensaje. |

### Ver también

* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(string, DateTime) {#constructor_9}

Inicializar una nueva instancia de un[`LogEntry`](../../logentry) clase.

```csharp
public LogEntry(string message, DateTime time)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| message | String | El mensaje. |
| time | DateTime | El tiempo. |

### Ver también

* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(string, Exception) {#constructor_10}

Inicializar una nueva instancia de un[`LogEntry`](../../logentry) clase.

```csharp
public LogEntry(string message, Exception innerException)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| message | String | Cuerpo del mensaje a registrar. Valor del método ToString() del objeto de mensaje. |
| innerException | Exception | La excepción interna para iniciar sesión. |

### Ver también

* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(string, LogLevel) {#constructor_6}

Inicializar una nueva instancia de un[`LogEntry`](../../logentry) clase.

```csharp
public LogEntry(string message, LogLevel severity)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| message | String | Cuerpo del mensaje a registrar. Valor del método ToString() del objeto de mensaje. |
| severity | LogLevel | Registrar la gravedad de la entrada como[`Severity`](../severity) enumeración. (Sin especificar, Información, Advertencia o Error). |

### Ver también

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(string, Exception, LogLevel) {#constructor_11}

Inicializar una nueva instancia de un[`LogEntry`](../../logentry) clase.

```csharp
public LogEntry(string message, Exception innerException, LogLevel severity)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| message | String | Cuerpo del mensaje a registrar. Valor del método ToString() del objeto de mensaje. |
| innerException | Exception | La excepción interna para iniciar sesión. |
| severity | LogLevel | Registrar la gravedad de la entrada como[`Severity`](../severity) enumeración. (Sin especificar, Información, Advertencia o Error). |

### Ver también

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(string, IDictionary&lt;string, string&gt;) {#constructor_8}

Crear una nueva instancia de[`LogEntry`](../../logentry) con un conjunto completo de parámetros de constructor

```csharp
public LogEntry(string message, IDictionary<string, string> properties)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| message | String | Cuerpo del mensaje a registrar. Valor del método ToString() del objeto de mensaje. |
| properties | IDictionary`2 | Diccionario de pares clave/valor a registrar. |

### Ver también

* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(byte[]) {#constructor_1}

Crear una nueva instancia de[`LogEntry`](../../logentry) con un conjunto completo de parámetros de constructor

```csharp
public LogEntry(byte[] binaryDataMessage)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Cuerpo del mensaje binario para registrar. |

### Ver también

* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(byte[], Encoding) {#constructor_3}

Crear una nueva instancia de[`LogEntry`](../../logentry) con un conjunto completo de parámetros de constructor

```csharp
public LogEntry(byte[] binaryDataMessage, Encoding messageEncoding)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Cuerpo del mensaje binario para registrar. |
| messageEncoding | Encoding | Codificación para mensaje binario |

### Ver también

* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(byte[], IDictionary&lt;string, string&gt;) {#constructor_2}

Crear una nueva instancia de[`LogEntry`](../../logentry) con un conjunto completo de parámetros de constructor

```csharp
public LogEntry(byte[] binaryDataMessage, IDictionary<string, string> properties)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Cuerpo del mensaje binario para registrar. |
| properties | IDictionary`2 | Diccionario de pares clave/valor a registrar. |

### Ver también

* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(byte[], Encoding, IDictionary&lt;string, string&gt;) {#constructor_4}

Crear una nueva instancia de[`LogEntry`](../../logentry) con un conjunto completo de parámetros de constructor

```csharp
public LogEntry(byte[] binaryDataMessage, Encoding messageEncoding, 
    IDictionary<string, string> properties)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| binaryDataMessage | Byte[] | Cuerpo del mensaje binario para registrar. |
| messageEncoding | Encoding | Codificación para mensaje binario |
| properties | IDictionary`2 | Diccionario de pares clave/valor a registrar. |

### Ver también

* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(string, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) {#constructor_7}

Crear una nueva instancia de[`LogEntry`](../../logentry) con un conjunto completo de parámetros de constructor

```csharp
public LogEntry(string message, LogLevel severity, string category, int eventId, string title, 
    IDictionary<string, string> properties)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| message | String | Cuerpo del mensaje a registrar. Valor del método ToString() del objeto de mensaje. |
| severity | LogLevel | Registrar la gravedad de la entrada como[`Severity`](../severity) enumeración. (Sin especificar, Información, Advertencia o Error). |
| category | String | Nombre de categoría utilizado para enrutar la entrada de registro a uno o más receptores. |
| eventId | Int32 | Número de evento o identificador. |
| title | String | Descripción adicional del mensaje de entrada de registro. |
| properties | IDictionary`2 | Diccionario de pares clave/valor a registrar. |

### Ver también

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

---

## LogEntry(string, Exception, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) {#constructor_12}

Crear una nueva instancia de[`LogEntry`](../../logentry) con un conjunto completo de parámetros de constructor

```csharp
public LogEntry(string message, Exception innerException, LogLevel severity, string category, 
    int eventId, string title, IDictionary<string, string> properties)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| message | String | Cuerpo del mensaje a registrar. Valor del método ToString() del objeto de mensaje. |
| innerException | Exception | La excepción interna para iniciar sesión. |
| severity | LogLevel | Registrar la gravedad de la entrada como[`Severity`](../severity) enumeración. (Sin especificar, Información, Advertencia o Error). |
| category | String | Nombre de categoría utilizado para enrutar la entrada de registro a uno o más receptores. |
| eventId | Int32 | Número de evento o identificador. |
| title | String | Descripción adicional del mensaje de entrada de registro. |
| properties | IDictionary`2 | Diccionario de pares clave/valor a registrar. |

### Ver también

* class [LogLevel](../../loglevel)
* class [LogEntry](../../logentry)
* espacio de nombres [Aspose.Email.Tools.Logging](../../logentry)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
