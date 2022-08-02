---
title: DeleteMessage
second_title: Referencia de la API de Aspose.Email para .NET
description: Marca un mensaje con el número de secuencia especificado como eliminado
type: docs
weight: 560
url: /es/net/aspose.email.clients.imap/imapclient/deletemessage/
---
## DeleteMessage(IConnection, int) {#deletemessage}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string) {#deletemessage_2}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessage(IConnection connection, string uniqueId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessage(int) {#deletemessage_6}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessage(int sequenceNumber)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessage(string) {#deletemessage_8}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessage(string uniqueId)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, int, long) {#deletemessage_1}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessage(IConnection connection, int sequenceNumber, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long) {#deletemessage_4}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessage(int, long) {#deletemessage_7}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessage(int sequenceNumber, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceNumber | Int32 | Número de secuencia de un mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessage(string, long) {#deletemessage_10}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessage(string, bool) {#deletemessage_9}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, bool) {#deletemessage_3}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessage(string, long, bool) {#deletemessage_11}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(string uniqueId, long modificationSequence, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessage(IConnection, string, long, bool) {#deletemessage_5}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessage(IConnection connection, string uniqueId, long modificationSequence, 
    bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uniqueId | String | El uid del mensaje |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
