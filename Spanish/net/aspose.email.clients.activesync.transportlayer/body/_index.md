---
title: Body
second_title: Referencia de la API de Aspose.Email para .NET
description: Especifica un campo de datos de longitud variable y formato libre asociado con un elemento almacenado en el servidor.
type: docs
weight: 1030
url: /es/net/aspose.email.clients.activesync.transportlayer/body/
---
## Body class

Especifica un campo de datos de longitud variable y formato libre asociado con un elemento almacenado en el servidor.

```csharp
public class Body
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Body](body)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Data](../../aspose.email.clients.activesync.transportlayer/body/data) { get; set; } | El contenido del elemento de datos es una cadena en el formato especificado por la propiedad Tipo. Si el valor del Tipo es RTF, el valor del elemento Datos se codifica utilizando la codificación base64. Si la propiedad Truncado se establece en verdadero, los datos del elemento Datos se truncan. La propiedad EstimatedDataSize proporciona una estimación aproximada del tamaño real del contenido completo de la cadena de datos. |
| [EstimatedDataSize](../../aspose.email.clients.activesync.transportlayer/body/estimateddatasize) { get; set; } | Especifica una estimación informativa del tamaño de los datos asociados con el elemento principal. El elemento de tamaño de datos estimado DEBE presentarse siempre que el elemento truncado se establezca en TRUE |
| [Part](../../aspose.email.clients.activesync.transportlayer/body/part) { get; set; } | Contiene un índice entero en los metadatos de la respuesta de varias partes. Esta propiedad DEBE estar presente en las respuestas de varias partes. Esta propiedad NO DEBE estar presente en solicitudes o respuestas que no sean de varias partes. |
| [Preview](../../aspose.email.clients.activesync.transportlayer/body/preview) { get; set; } | Contiene el mensaje de texto sin formato Unicode o la vista previa parcial del mensaje devuelta al cliente. |
| [Truncated](../../aspose.email.clients.activesync.transportlayer/body/truncated) { get; set; } | Especifica si el cuerpo del elemento se ha truncado de acuerdo con el elemento BodyPreference indicado por el cliente. Si el valor es TRUE, entonces el cuerpo del elemento se ha truncado. Si el valor es FALSO o la propiedad Truncado no está configurada, entonces el cuerpo del elemento no se ha truncado. |
| [Type](../../aspose.email.clients.activesync.transportlayer/body/type) { get; set; } | Especifica el tipo de formato del contenido del cuerpo del elemento. |

### Ver también

* espacio de nombres [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* asamblea [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->