---
title: MapiMessage
second_title: Referencia de la API de Aspose.Email para .NET
description: Inicializa una nueva instancia delMapiMessageaspose.email.mapi/mapimessage clase.
type: docs
weight: 10
url: /es/net/aspose.email.mapi/mapimessage/mapimessage/
---
## MapiMessage() {#constructor}

Inicializa una nueva instancia del[`MapiMessage`](../../mapimessage) clase.

```csharp
public MapiMessage()
```

### Ver también

* class [MapiMessage](../../mapimessage)
* espacio de nombres [Aspose.Email.Mapi](../../mapimessage)
* asamblea [Aspose.Email](../../../)

---

## MapiMessage(OutlookMessageFormat) {#constructor_1}

Inicializa una nueva instancia del[`MapiMessage`](../../mapimessage) clase.

```csharp
public MapiMessage(OutlookMessageFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| format | OutlookMessageFormat | Define si usar la codificación Unicode o ASCII para este mensaje. |

### Ver también

* enum [OutlookMessageFormat](../../outlookmessageformat)
* class [MapiMessage](../../mapimessage)
* espacio de nombres [Aspose.Email.Mapi](../../mapimessage)
* asamblea [Aspose.Email](../../../)

---

## MapiMessage(string, string, string, string, OutlookMessageFormat) {#constructor_3}

Inicializa una nueva instancia del[`MapiMessage`](../../mapimessage) clase.

```csharp
public MapiMessage(string from, string to, string subject, string body, OutlookMessageFormat format)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| from | String | La dirección de origen. |
| to | String | Las direcciones de los destinatarios. Tenga en cuenta que las direcciones están separadas por punto y coma. |
| subject | String | El asunto del mensaje. |
| body | String | El cuerpo del mensaje. |
| format | OutlookMessageFormat | Define si usar la codificación Unicode o ASCII para este mensaje. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | Se lanza si la dirección del destinatario es nula o está vacía. |
| ArgumentException | Se lanza si la dirección del remitente o del destinatario no está en un formato reconocido. |
| InvalidEnumArgumentException | se tira si*format*El parámetro no es un miembro de enumeración válido. |

### Ver también

* enum [OutlookMessageFormat](../../outlookmessageformat)
* class [MapiMessage](../../mapimessage)
* espacio de nombres [Aspose.Email.Mapi](../../mapimessage)
* asamblea [Aspose.Email](../../../)

---

## MapiMessage(string, string, string, string) {#constructor_2}

Inicializa una nueva instancia del[`MapiMessage`](../../mapimessage) clase.

```csharp
public MapiMessage(string from, string to, string subject, string body)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| from | String | La dirección de origen. |
| to | String | Las direcciones de los destinatarios. Tenga en cuenta que las direcciones están separadas por punto y coma. |
| subject | String | El asunto del mensaje. |
| body | String | El cuerpo del mensaje. |

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | se lanza si la dirección del destinatario es nula o está vacía. |
| ArgumentException | se lanza si la dirección del remitente o del destinatario no está en un formato reconocido. |

### Ver también

* class [MapiMessage](../../mapimessage)
* espacio de nombres [Aspose.Email.Mapi](../../mapimessage)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->