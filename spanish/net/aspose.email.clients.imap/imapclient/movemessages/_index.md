---
title: MoveMessages
second_title: Referencia de la API de Aspose.Email para .NET
description: Mueve el mensaje
type: docs
weight: 950
url: /es/net/aspose.email.clients.imap/imapclient/movemessages/
---
## MoveMessages(IConnection, string, string, string) {#movemessages_8}

Mueve el mensaje

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(string, string, string) {#movemessages_18}

Mueve el mensaje

```csharp
public void MoveMessages(string startUid, string endUid, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string, bool) {#movemessages_7}

Mueve el mensaje

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName, 
    bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string, bool) {#movemessages_17}

Mueve el mensaje

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName, bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;string&gt;, string) {#movemessages_6}

Mueve el mensaje

```csharp
public void MoveMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;string&gt;, string) {#movemessages_16}

Mueve el mensaje

```csharp
public void MoveMessages(IEnumerable<string> uidSet, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_3}

Mueve el mensaje

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName, bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string, bool) {#movemessages_13}

Mueve el mensaje

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName, 
    bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_2}

Mueve el mensaje

```csharp
public void MoveMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#movemessages_12}

Mueve el mensaje

```csharp
public void MoveMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string, bool) {#movemessages_1}

Mueve el mensaje

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName, bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(int, int, string, bool) {#movemessages_11}

Mueve el mensaje

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName, 
    bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IConnection, int, int, string) {#movemessages}

Mueve el mensaje

```csharp
public void MoveMessages(IConnection connection, int startSequence, int endSequence, 
    string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(int, int, string) {#movemessages_10}

Mueve el mensaje

```csharp
public void MoveMessages(int startSequence, int endSequence, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string, bool) {#movemessages_5}

Mueve el mensaje

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName, 
    bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string, bool) {#movemessages_15}

Mueve el mensaje

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IConnection, IEnumerable&lt;int&gt;, string) {#movemessages_4}

Mueve el mensaje

```csharp
public void MoveMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IEnumerable&lt;int&gt;, string) {#movemessages_14}

Mueve el mensaje

```csharp
public void MoveMessages(IEnumerable<int> sequenceSet, string folderName)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(IConnection, string, string, string, bool) {#movemessages_9}

Mueve el mensaje

```csharp
public void MoveMessages(IConnection connection, string startUid, string endUid, string folderName, 
    bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## MoveMessages(string, string, string, bool) {#movemessages_19}

Mueve el mensaje

```csharp
public void MoveMessages(string startUid, string endUid, string folderName, bool commitDeletions)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| folderName | String | Nombre de la carpeta donde se va a mover un mensaje |
| commitDeletions | Boolean | Especifica si se deben confirmar las eliminaciones. |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
