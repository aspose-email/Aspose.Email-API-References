---
title: ImapClient.UnselectFolder
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Permanently removes all messages marked as deleted for currently selected folder and removes selectedstate for this folder
type: docs
weight: 1260
url: /net/aspose.email.clients.imap/imapclient/unselectfolder/
---
## UnselectFolder(IConnection) {#unselectfolder_1}

Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder.

```csharp
public void UnselectFolder(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## UnselectFolder() {#unselectfolder}

Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder.

```csharp
public void UnselectFolder()
```

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## UnselectFolder(IConnection, bool) {#unselectfolder_2}

Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

```csharp
public void UnselectFolder(IConnection connection, bool doNotExpunge)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| doNotExpunge | Boolean | Specifies whether messages marked as deleted should be removed. |

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## UnselectFolder(bool) {#unselectfolder_3}

Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

```csharp
public void UnselectFolder(bool doNotExpunge)
```

| Parameter | Type | Description |
| --- | --- | --- |
| doNotExpunge | Boolean | Specifies whether messages marked as deleted should be removed. |

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


