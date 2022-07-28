---
title: DeleteMessages
second_title: Referencia de la API de Aspose.Email para .NET
description: Marca un mensaje con el número de secuencia especificado como eliminado
type: docs
weight: 580
url: /es/net/aspose.email.clients.imap/imapclient/deletemessages/
---
## DeleteMessages(IConnection, IEnumerable&lt;int&gt;) {#deletemessages_6}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;) {#deletemessages_8}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;) {#deletemessages_22}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;) {#deletemessages_24}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(IEnumerable<string> uidSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;int&gt;, long) {#deletemessages_7}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<int> sequenceSet, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long) {#deletemessages_10}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;int&gt;, long) {#deletemessages_23}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(IEnumerable<int> sequenceSet, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| sequenceSet | IEnumerable`1 | El conjunto de números de secuencia para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long) {#deletemessages_26}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, bool) {#deletemessages_25}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, bool) {#deletemessages_9}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;string&gt;, long, bool) {#deletemessages_27}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<string> uidSet, long modificationSequence, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;string&gt;, long, bool) {#deletemessages_11}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<string> uidSet, 
    long modificationSequence, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| uidSet | IEnumerable`1 | El conjunto de UID para mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int) {#deletemessages}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string) {#deletemessages_12}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(int, int) {#deletemessages_16}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(int startSequence, int endSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(string, string) {#deletemessages_28}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(string startUid, string endUid)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, int, int, long) {#deletemessages_1}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(IConnection connection, int startSequence, int endSequence, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long) {#deletemessages_14}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(int, int, long) {#deletemessages_17}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(int startSequence, int endSequence, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startSequence | Int32 | El número de secuencia inicial de una lista de mensajes. |
| endSequence | Int32 | El número de secuencia final de una lista de mensajes. |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long) {#deletemessages_30}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(string, string, bool) {#deletemessages_29}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, bool) {#deletemessages_13}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(string, string, long, bool) {#deletemessages_31}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(string startUid, string endUid, long modificationSequence, 
    bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, string, string, long, bool) {#deletemessages_15}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, string startUid, string endUid, 
    long modificationSequence, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| startUid | String | El UID inicial de una lista de mensajes |
| endUid | String | El UID final de una lista de mensajes |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_2}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;) {#deletemessages_18}

Marca un mensaje con el número de secuencia especificado como eliminado

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_4}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long) {#deletemessages_20}

Marca un mensaje con el identificador único especificado como eliminado

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_19}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, bool) {#deletemessages_3}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_21}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IEnumerable<ImapMessageInfo> messageInfoSet, long modificationSequence, 
    bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

---

## DeleteMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, long, bool) {#deletemessages_5}

Marca un mensaje con el identificador único especificado como eliminado y confirma las eliminaciones si el usuario lo especifica. Este método solo funciona si el servidor admite la extensión UIDPLUS. Lea más https://tools.ietf.org/html/rfc4315

```csharp
public void DeleteMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
    long modificationSequence, bool commitNow)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| connection | IConnection | Conexión a un servidor |
| messageInfoSet | IEnumerable`1 | El conjunto de ImapMessageInfo para su eliminación |
| modificationSequence | Int64 | Secuencia de modificación. Por favor, lea más https://tools.ietf.org/html/rfc7162 |
| commitNow | Boolean | Define si el mensaje debe confirmarse ahora. Lea más https://tools.ietf.org/html/rfc4315 |

### Ver también

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapMessageInfo](../../imapmessageinfo)
* class [ImapClient](../../imapclient)
* espacio de nombres [Aspose.Email.Clients.Imap](../../imapclient)
* asamblea [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
