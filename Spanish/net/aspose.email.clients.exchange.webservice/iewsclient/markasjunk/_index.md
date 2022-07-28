---
title: MarkAsJunk
second_title: Referencia de la API de Aspose.Email para .NET
description: El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje.
type: docs
weight: 1270
url: /es/net/aspose.email.clients.exchange.webservice/iewsclient/markasjunk/
---
## MarkAsJunk(bool, params string[]) {#markasjunk_3}

El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje.

```csharp
public string[] MarkAsJunk(bool isJunk, params string[] messageUriEn)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| isJunk | Boolean | Indica si los mensajes están marcados como correo no deseado. Si el valor es verdadero, agrega el remitente del mensaje a la lista de bloqueo. Si el valor es falso, se elimina el remitente del mensaje de la lista de bloqueo. |
| messageUriEn | String[] | Matriz de mensaje uri |

### Valor_devuelto

Devuelve la matriz de ID de mensaje que se mueven a la carpeta de correo no deseado.

### Ver también

* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, params string[]) {#markasjunk_1}

El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, params string[] messageUriEn)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| isJunk | Boolean | Indica si los mensajes están marcados como correo no deseado. Si el valor es verdadero, agrega el remitente del mensaje a la lista de bloqueo. Si el valor es falso, se elimina el remitente del mensaje de la lista de bloqueo. |
| moveItem | Boolean | Indica si los mensajes se mueven a la carpeta de correo no deseado. |
| messageUriEn | String[] | Matriz de mensaje uri |

### Valor_devuelto

Devuelve la matriz de ID de mensaje que se mueven a la carpeta de correo no deseado.

### Ver también

* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## MarkAsJunk(bool, IEnumerable&lt;string&gt;) {#markasjunk_2}

El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje.

```csharp
public string[] MarkAsJunk(bool isJunk, IEnumerable<string> messageUriEn)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| isJunk | Boolean | Indica si los mensajes están marcados como correo no deseado. Si el valor es verdadero, agrega el remitente del mensaje a la lista de bloqueo. Si el valor es falso, se elimina el remitente del mensaje de la lista de bloqueo. |
| messageUriEn | IEnumerable`1 | Enumeración del mensaje uri |

### Valor_devuelto

Devuelve el Id. de elemento del mensaje marcado como correo no deseado.

### Ver también

* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;) {#markasjunk}

El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje.

```csharp
public string[] MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| isJunk | Boolean | Indica si los mensajes están marcados como correo no deseado. Si el valor es verdadero, agrega el remitente del mensaje a la lista de bloqueo. Si el valor es falso, se elimina el remitente del mensaje de la lista de bloqueo. |
| moveItem | Boolean | Indica si los mensajes se mueven a la carpeta de correo no deseado. |
| messageUriEn | IEnumerable`1 | Enumeración del mensaje uri |

### Valor_devuelto

Devuelve la matriz de ID de mensaje que se mueven a la carpeta de correo no deseado.

### Ver también

* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

---

## MarkAsJunk(bool, bool, IEnumerable&lt;string&gt;, out string[], out string[], out string[]) {#markasjunk_4}

El método MarkAsJunk mueve los mensajes de correo a la carpeta de correo no deseado y bloquea el remitente del mensaje.

```csharp
public void MarkAsJunk(bool isJunk, bool moveItem, IEnumerable<string> messageUriEn, 
    out string[] movedMessageIds, out string[] failedMessageIds, out string[] errorMessages)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| isJunk | Boolean | Indica si los mensajes están marcados como correo no deseado. Si el valor es verdadero, agrega el remitente del mensaje a la lista de bloqueo. Si el valor es falso, se elimina el remitente del mensaje de la lista de bloqueo. |
| moveItem | Boolean | Indica si los mensajes se mueven a la carpeta de correo no deseado. |
| messageUriEn | IEnumerable`1 | Enumeración del mensaje uri |
| movedMessageIds | String[]& | Devuelve la matriz de ID de mensaje que se mueven a la carpeta de correo no deseado. |
| failedMessageIds | String[]& | Devuelve la matriz de ID de mensajes que no se han movido a la carpeta de correo no deseado. |
| errorMessages | String[]& | Mensajes de error para operaciones fallidas |

### Ver también

* interface [IEWSClient](../../iewsclient)
* espacio de nombres [Aspose.Email.Clients.Exchange.WebService](../../iewsclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
