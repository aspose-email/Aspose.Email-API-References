---
title: UnselectFolderAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 1260
url: /net/aspose.email.clients.imap/imapclient/unselectfolderasync/
---
## ImapClient.UnselectFolderAsync method (1 of 8)

Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder.

```csharp
public Task UnselectFolderAsync(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.UnselectFolderAsync method (2 of 8)

Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder.

```csharp
public Task UnselectFolderAsync()
```

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.UnselectFolderAsync method (3 of 8)

Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(IConnection connection, bool doNotExpunge)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| doNotExpunge | Boolean | Specifies whether messages marked as deleted should be removed. |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.UnselectFolderAsync method (4 of 8)

Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge)
```

| Parameter | Type | Description |
| --- | --- | --- |
| doNotExpunge | Boolean | Specifies whether messages marked as deleted should be removed. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.UnselectFolderAsync method (5 of 8)

Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder.

```csharp
public Task UnselectFolderAsync(IConnection connection, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.UnselectFolderAsync method (6 of 8)

Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder.

```csharp
public Task UnselectFolderAsync(CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.UnselectFolderAsync method (7 of 8)

Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(IConnection connection, bool doNotExpunge, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| doNotExpunge | Boolean | Specifies whether messages marked as deleted should be removed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.UnselectFolderAsync method (8 of 8)

Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

```csharp
public Task UnselectFolderAsync(bool doNotExpunge, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| doNotExpunge | Boolean | Specifies whether messages marked as deleted should be removed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
