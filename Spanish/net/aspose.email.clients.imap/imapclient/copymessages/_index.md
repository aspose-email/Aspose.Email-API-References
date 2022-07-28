---
title: CopyMessages
second_title: Referencia de la API de Aspose.Email para .NET
description: Copie el mensaje
type: docs
weight: 500
url: /es/net/aspose.email.clients.imap/imapclient/copymessages/
---
## CopyMessages(IConnection, int, int, string) {#copymessages}

Copie el mensaje

```csharp
public void CopyMessages(IConnection connection, int startSequence, int endSequence, 
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

## CopyMessages(int, int, string) {#copymessages_5}

Copiar mensajes

```csharp
public void CopyMessages(int startSequence, int endSequence, string folderName)
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

## CopyMessages(IConnection, string, string, string) {#copymessages_4}

Copiar mensajes

```csharp
public void CopyMessages(IConnection connection, string startUid, string endUid, string folderName)
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

## CopyMessages(string, string, string) {#copymessages_10}

Copiar mensajes

```csharp
public void CopyMessages(string startUid, string endUid, string folderName)
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

## CopyMessages(IEnumerable&lt;int&gt;, string, bool) {#copymessages_8}

Copiar mensajes

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName, bool commitDeletions)
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

## CopyMessages(IConnection, IEnumerable&lt;int&gt;, string) {#copymessages_2}

Copie el mensaje

```csharp
public void CopyMessages(IConnection connection, IEnumerable<int> sequenceSet, string folderName)
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

## CopyMessages(IEnumerable&lt;int&gt;, string) {#copymessages_7}

Copiar mensajes

```csharp
public void CopyMessages(IEnumerable<int> sequenceSet, string folderName)
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

## CopyMessages(IConnection, IEnumerable&lt;string&gt;, string) {#copymessages_3}

Copiar mensajes

```csharp
public void CopyMessages(IConnection connection, IEnumerable<string> uidSet, string folderName)
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

## CopyMessages(IEnumerable&lt;string&gt;, string) {#copymessages_9}

Copiar mensajes

```csharp
public void CopyMessages(IEnumerable<string> uidSet, string folderName)
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

## CopyMessages(IConnection, IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_1}

Copiar mensajes

```csharp
public void CopyMessages(IConnection connection, IEnumerable<ImapMessageInfo> messageInfoSet, 
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

## CopyMessages(IEnumerable&lt;ImapMessageInfo&gt;, string) {#copymessages_6}

Copiar mensajes

```csharp
public void CopyMessages(IEnumerable<ImapMessageInfo> messageInfoSet, string folderName)
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

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
