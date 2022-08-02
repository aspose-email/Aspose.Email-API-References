---
title: UnselectFolderAsync
second_title: Referencia de la API de Aspose.Email para .NET
description: Elimina permanentemente todos los mensajes marcados como eliminados para la carpeta seleccionada actualmente y elimina el estado seleccionado para esta carpeta.
type: docs
weight: 1260
url: /es/net/aspose.email.clients.imap/imapclient/unselectfolderasync/
---
## UnselectFolderAsync(IConnection) {#unselectfolderasync_1}

Elimina permanentemente todos los mensajes marcados como eliminados para la carpeta seleccionada actualmente y elimina el estado seleccionado para esta carpeta.

```csharp
public Task UnselectFolderAsync(IConnection connection)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## UnselectFolderAsync() {#unselectfolderasync}

Elimina permanentemente todos los mensajes marcados como eliminados para la carpeta seleccionada actualmente y elimina el estado seleccionado para esta carpeta.

```csharp
public Task UnselectFolderAsync()
```

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, bool) {#unselectfolderasync_2}

Anula la selección de la carpeta que está actualmente seleccionada. si la propiedad doNotExpunge es verdadera, se eliminan todos los mensajes marcados como eliminados; de lo contrario, se cancela la eliminación. Tenga en cuenta que esta operación solo funciona en caso de que el servidor admita RFC3691 Ver más https://tools. ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(IConnection connection, bool doNotExpunge)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| doNotExpunge | Boolean | Especifica si se deben eliminar los mensajes marcados como eliminados. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## UnselectFolderAsync(bool) {#unselectfolderasync_5}

Anula la selección de la carpeta que está actualmente seleccionada. si la propiedad doNotExpunge es verdadera, se eliminan todos los mensajes marcados como eliminados; de lo contrario, se cancela la eliminación. Tenga en cuenta que esta operación solo funciona en caso de que el servidor admita RFC3691 Ver más https://tools. ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| doNotExpunge | Boolean | Especifica si se deben eliminar los mensajes marcados como eliminados. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, CancellationToken) {#unselectfolderasync_4}

Elimina permanentemente todos los mensajes marcados como eliminados para la carpeta seleccionada actualmente y elimina el estado seleccionado para esta carpeta.

```csharp
public Task UnselectFolderAsync(IConnection connection, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## UnselectFolderAsync(CancellationToken) {#unselectfolderasync_7}

Elimina permanentemente todos los mensajes marcados como eliminados para la carpeta seleccionada actualmente y elimina el estado seleccionado para esta carpeta.

```csharp
public Task UnselectFolderAsync(CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## UnselectFolderAsync(IConnection, bool, CancellationToken) {#unselectfolderasync_3}

Anula la selección de la carpeta que está actualmente seleccionada. si la propiedad doNotExpunge es verdadera, se eliminan todos los mensajes marcados como eliminados; de lo contrario, se cancela la eliminación. Tenga en cuenta que esta operación solo funciona en caso de que el servidor admita RFC3691 Ver más https://tools. ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(IConnection connection, bool doNotExpunge, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| doNotExpunge | Boolean | Especifica si se deben eliminar los mensajes marcados como eliminados. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## UnselectFolderAsync(bool, CancellationToken) {#unselectfolderasync_6}

Anula la selección de la carpeta que está actualmente seleccionada. si la propiedad doNotExpunge es verdadera, se eliminan todos los mensajes marcados como eliminados; de lo contrario, se cancela la eliminación. Tenga en cuenta que esta operación solo funciona en caso de que el servidor admita RFC3691 Ver más https://tools. ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge, CancellationToken token)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| doNotExpunge | Boolean | Especifica si se deben eliminar los mensajes marcados como eliminados. |
| token | CancellationToken | Propaga la notificación de que las operaciones deben cancelarse. |

### Valor_devuelto

Objeto de tarea, con delegado para esta operación.

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
