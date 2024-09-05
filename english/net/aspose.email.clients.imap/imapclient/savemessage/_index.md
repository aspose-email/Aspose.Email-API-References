---
title: ImapClient.SaveMessage
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Downloads the message with the specified sequence number and writes its data into a supplied stream
type: docs
weight: 1100
url: /net/aspose.email.clients.imap/imapclient/savemessage/
---
## SaveMessage(int, Stream) {#savemessage_4}

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public void SaveMessage(int sequenceNumber, Stream resultStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| resultStream | Stream | Stream that will receive the message |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## SaveMessage(string, Stream) {#savemessage_6}

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public void SaveMessage(string uniqueId, Stream resultStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| resultStream | Stream | Stream that will receive the message |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## SaveMessage(string, string) {#savemessage_7}

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public void SaveMessage(string uniqueId, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| uniqueId | String | The unique Id of the message |
| fileName | String | The path of the local file. This cannot be a directory |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## SaveMessage(int, string) {#savemessage_5}

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public void SaveMessage(int sequenceNumber, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sequenceNumber | Int32 | The sequence number of the message |
| fileName | String | The path of the local file. This cannot be a directory |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## SaveMessage(IConnection, int, Stream) {#savemessage}

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public void SaveMessage(IConnection connection, int sequenceNumber, Stream resultStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| resultStream | Stream | Stream that will receive the message |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## SaveMessage(IConnection, string, Stream) {#savemessage_2}

Downloads the message with the specified sequence number and writes its data into a supplied stream

```csharp
public void SaveMessage(IConnection connection, string uniqueId, Stream resultStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| resultStream | Stream | Stream that will receive the message |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## SaveMessage(IConnection, string, string) {#savemessage_3}

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public void SaveMessage(IConnection connection, string uniqueId, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| uniqueId | String | The unique Id of the message |
| fileName | String | The path of the local file. This cannot be a directory |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## SaveMessage(IConnection, int, string) {#savemessage_1}

Downloads the message with the specified sequence number and writes its data into a local file

```csharp
public void SaveMessage(IConnection connection, int sequenceNumber, string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| sequenceNumber | Int32 | The sequence number of the message |
| fileName | String | The path of the local file. This cannot be a directory |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


