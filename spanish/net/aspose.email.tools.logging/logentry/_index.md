---
title: LogEntry
second_title: Referencia de la API de Aspose.Email para .NET
description: Representa un mensaje de registro. Contiene las propiedades comunes que se requieren para todos los mensajes de registro.
type: docs
weight: 20520
url: /es/net/aspose.email.tools.logging/logentry/
---
## LogEntry class

Representa un mensaje de registro. Contiene las propiedades comunes que se requieren para todos los mensajes de registro.

```csharp
public class LogEntry
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LogEntry](logentry#constructor)() | Inicializar una nueva instancia de un[`LogEntry`](../logentry) clase. |
| [LogEntry](logentry#constructor_1)(byte[]) | Crear una nueva instancia de[`LogEntry`](../logentry) con un conjunto completo de parámetros de constructor |
| [LogEntry](logentry#constructor_5)(string) | Inicializar una nueva instancia de un[`LogEntry`](../logentry) clase. |
| [LogEntry](logentry#constructor_3)(byte[], Encoding) | Crear una nueva instancia de[`LogEntry`](../logentry) con un conjunto completo de parámetros de constructor |
| [LogEntry](logentry#constructor_2)(byte[], IDictionary&lt;string, string&gt;) | Crear una nueva instancia de[`LogEntry`](../logentry) con un conjunto completo de parámetros de constructor |
| [LogEntry](logentry#constructor_9)(string, DateTime) | Inicializar una nueva instancia de un[`LogEntry`](../logentry) clase. |
| [LogEntry](logentry#constructor_10)(string, Exception) | Inicializar una nueva instancia de un[`LogEntry`](../logentry) clase. |
| [LogEntry](logentry#constructor_8)(string, IDictionary&lt;string, string&gt;) | Crear una nueva instancia de[`LogEntry`](../logentry) con un conjunto completo de parámetros de constructor |
| [LogEntry](logentry#constructor_6)(string, LogLevel) | Inicializar una nueva instancia de un[`LogEntry`](../logentry) clase. |
| [LogEntry](logentry#constructor_4)(byte[], Encoding, IDictionary&lt;string, string&gt;) | Crear una nueva instancia de[`LogEntry`](../logentry) con un conjunto completo de parámetros de constructor |
| [LogEntry](logentry#constructor_11)(string, Exception, LogLevel) | Inicializar una nueva instancia de un[`LogEntry`](../logentry) clase. |
| [LogEntry](logentry#constructor_7)(string, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Crear una nueva instancia de[`LogEntry`](../logentry) con un conjunto completo de parámetros de constructor |
| [LogEntry](logentry#constructor_12)(string, Exception, LogLevel, string, int, string, IDictionary&lt;string, string&gt;) | Crear una nueva instancia de[`LogEntry`](../logentry) con un conjunto completo de parámetros de constructor |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AppDomainName](../../aspose.email.tools.logging/logentry/appdomainname) { get; set; } | El AppDomain en el que estamos ejecutando |
| [BinaryDataMessage](../../aspose.email.tools.logging/logentry/binarydatamessage) { get; set; } | Cuerpo del mensaje binario para registrar. |
| [Category](../../aspose.email.tools.logging/logentry/category) { get; set; } | Nombre de categoría utilizado para enrutar la entrada de registro a uno o más receptores. |
| [ContextualProperties](../../aspose.email.tools.logging/logentry/contextualproperties) { get; set; } | Diccionario de pares clave/valor a registrar. |
| [ErrorMessages](../../aspose.email.tools.logging/logentry/errormessages) { get; } | Obtiene el mensaje de error con el[`LogEntry`](../logentry) |
| [EventId](../../aspose.email.tools.logging/logentry/eventid) { get; set; } | Número de evento o identificador. |
| [InnerException](../../aspose.email.tools.logging/logentry/innerexception) { get; set; } | Obtiene o establece el objeto de excepción interno. |
| [MachineName](../../aspose.email.tools.logging/logentry/machinename) { get; set; } | Nombre del equipo. |
| [Message](../../aspose.email.tools.logging/logentry/message) { get; set; } | Cuerpo del mensaje para registrar. Valor del método ToString() del objeto de mensaje. |
| [MessageEncoding](../../aspose.email.tools.logging/logentry/messageencoding) { get; set; } | Codificación para cuerpo de mensaje binario |
| [SequenceId](../../aspose.email.tools.logging/logentry/sequenceid) { get; } | El identificador único del evento de registro que se genera automáticamente y aumenta monótonamente. |
| [Severity](../../aspose.email.tools.logging/logentry/severity) { get; set; } | Gravedad de entrada de registro como[`Severity`](./severity) enumeración. (Sin especificar, Información, Advertencia o Error). |
| [ThreadName](../../aspose.email.tools.logging/logentry/threadname) { get; set; } | El nombre del subproceso .NET. |
| [TimeStamp](../../aspose.email.tools.logging/logentry/timestamp) { get; set; } | Fecha y hora del mensaje de entrada de registro. |
| [Title](../../aspose.email.tools.logging/logentry/title) { get; set; } | Descripción adicional del mensaje de entrada de registro. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [AddErrorMessage](../../aspose.email.tools.logging/logentry/adderrormessage)(string) | Agrega un mensaje de error o advertencia al inicio del generador de cadenas de mensajes. Usado por el distribuidor para registrar problemas. |
| [Clone](../../aspose.email.tools.logging/logentry/clone)() | Crea un nuevo[`LogEntry`](../logentry) esa es una copia de la instancia actual. |
| override [ToString](../../aspose.email.tools.logging/logentry/tostring)() |  |

### Ver también

* espacio de nombres [Aspose.Email.Tools.Logging](../../aspose.email.tools.logging)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
