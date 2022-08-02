---
title: MailQuery
second_title: Referencia de la API de Aspose.Email para .NET
description: Inicializa una nueva instancia delMailQueryaspose.email.tools.search/mailquery clase.
type: docs
weight: 10
url: /es/net/aspose.email.tools.search/mailquery/mailquery/
---
## MailQuery(string) {#constructor}

Inicializa una nueva instancia del[`MailQuery`](../../mailquery) clase.

```csharp
public MailQuery(string queryString)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| queryString | String | La cadena de consulta. |

### Observaciones

La cadena de consulta debe tener la siguiente vista.

El ejemplo de una expresión simple:

'&lt;Nombre de campo&gt;' &lt;Operador de comparación&gt; '&lt;Valor de campo&gt;',

donde &lt;Nombre de campo&gt;: el nombre de un campo de mensaje a través del cual se realiza el filtrado, &lt;Operador de comparación&gt;: los operadores de comparación, como su nombre lo indica, permiten comparar el campo de mensaje y el valor especificado, &lt;Valor de campo&gt;: valor para compararse con un campo de mensaje.

El número de expresiones simples puede formar una compuesta, ej.: (&lt;Expresión simple 1&gt; &amp; &lt;Expresión simple 2&gt;) &#x7C; &lt;Expresión simple 3&gt;,

donde "&amp;" - operador lógico AND, "&#x7C;" - operador OR lógico

Actualmente se permiten los siguientes valores como nombre de campo (&lt;Nombre de campo&gt;):

"Para": representa un campo TO del mensaje, "Texto": representa una cadena en el encabezado o el cuerpo del mensaje, "Bcc": representa un campo BCC del mensaje, "Cuerpo": representa una cadena en el cuerpo del mensaje, "Cc": representa un campo CC del mensaje, "De": representa un campo De del mensaje, "Asunto": representa una cadena en el asunto del mensaje, "FechaInterna": representa un fecha del mensaje, "SentDate": representa una fecha de envío del mensaje

Además, los siguientes nombres de campo están permitidos para el protocolo IMAP:

"Respondido": representa un indicador de /Respondido del mensaje "Visto": representa un indicador de /Visto del mensaje "Marcado": representa un indicador de /Marcado del mensaje "Borrador": representa un indicador de /Borrador del mensaje "Eliminado": representa un indicador Eliminado/ de mensaje "Reciente": representa un indicador Eliminado/ de mensaje "Tamaño del mensaje": representa un tamaño (en bytes) de mensaje

Además, los siguientes nombres de campo están permitidos para Exchange:

"IsRead": indica si el mensaje se leyó "HasAttachment": indica si el mensaje tiene archivos adjuntos o no "IsSubmitted": indica si el mensaje se envió a la bandeja de salida "ContentClass": representa una clase de contenido de item

Además, los siguientes nombres de campo están permitidos para archivos pst/ost:

"MessageClass": representa un mensaje class "ContainerClass": representa un contenedor de carpetas class "Importance": representa un mensaje important "MessageSize": representa un tamaño (en bytes) de message "FolderName": representa un nombre de carpeta "ContentsCount" - representa un número total de elementos en la carpeta "UnreadContentsCount" - representa el número de elementos no leídos en la carpeta. "Subcarpetas" - Indica si la carpeta tiene o no subcarpetas "Leído" - el mensaje se marca como leído " HasAttachment": el mensaje tiene al menos un archivo adjunto "Sin enviar": el mensaje aún se está redactando "Sin modificar": el mensaje no se ha modificado desde que se guardó por primera vez (si no se envió) o se entregó (si se envió) "FromMe ": el usuario que recibió el mensaje también fue el usuario que envió el mensaje "Reenviar": el mensaje incluye una solicitud para una operación de reenvío con un informe de no entrega_x000 d_ "NotifyRead": el usuario que envió el mensaje solicitó una notificación cuando un destinatario lo leyó por primera vez "NotifyUnread": el usuario que envió el mensaje solicitó una notificación cuando un destinatario lo eliminó antes de leerlo o el objeto del mensaje caduca "EverRead": el el mensaje ha sido leído al menos una vez

El valor del campo (&lt;Valor del campo&gt;) puede tomar los siguientes valores: Para campos de texto - cualquier cadena, Para campos de tipo fecha - la cadena de formato "d-MMM-yyy", ej. "10-feb-2009", Para marcas (campos de tipo booleano) - "Verdadero" o "Falso"

### Ejemplos

```csharp
MailQuery mailQuery = new MailQuery("(('From' Contains 'test@test.com' | 'Seen' = 'True') & 'SentDate' >= '12-May-2010')");
```

### Ver también

* class [MailQuery](../../mailquery)
* espacio de nombres [Aspose.Email.Tools.Search](../../mailquery)
* asamblea [Aspose.Email](../../../)

---

## MailQuery(string, string) {#constructor_1}

Inicializa una nueva instancia del[`MailQuery`](../../mailquery) clase.

```csharp
public MailQuery(string queryString, string orderByString)
```

### Observaciones

La cadena de consulta de clasificación debe tener la siguiente vista.

El ejemplo de una expresión simple:

'&lt;Nombre de campo&gt;' Ordenar por ['ASC'&#x7C;'DESC'],

where &lt;Field Name&gt; - el nombre de un campo de mensaje a través del cual se realiza la clasificación, ['ASC'&#x7C;'DESC'] - operadores de clasificación, permite clasificar Ascendente o Descendente,

El número de expresiones simples puede formar una compuesta, ej.: (&lt;Expresión simple 1&gt; &amp; &lt;Expresión simple 2&gt;),

### Ejemplos

```csharp
MailQuery mailQuery = new MailQuery("", "(('From' OrderBy 'ASC') & ('SentDate' OrderBy 'DESC'))");
```

### Ver también

* class [MailQuery](../../mailquery)
* espacio de nombres [Aspose.Email.Tools.Search](../../mailquery)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
