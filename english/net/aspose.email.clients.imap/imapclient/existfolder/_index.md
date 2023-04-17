---
title: ImapClient.ExistFolder
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Check whether this folder exists
type: docs
weight: 620
url: /net/aspose.email.clients.imap/imapclient/existfolder/
---
## ExistFolder(string) {#existfolder_2}

Check whether this folder exists

```csharp
public bool ExistFolder(string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Name of the folder |

### Return Value

Returns true if the folder is existing, otherwise returns false

### See Also

* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ExistFolder(string, out ImapFolderInfo) {#existfolder_3}

Check whether this folder exists, extract folder info if so

```csharp
public bool ExistFolder(string folderName, out ImapFolderInfo folderInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderName | String | Name of the folder |
| folderInfo | ImapFolderInfo& | Folder information |

### Return Value

Returns true if the folder is existing, otherwise returns false

### See Also

* class [ImapFolderInfo](../../imapfolderinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ExistFolder(IConnection, string) {#existfolder}

Check whether this folder exists

```csharp
public bool ExistFolder(IConnection connection, string folderName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Name of the folder |

### Return Value

Returns true if the folder is existing, otherwise returns false

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ExistFolder(IConnection, string, out ImapFolderInfo) {#existfolder_1}

Check whether this folder exists, extract folder info if so

```csharp
public bool ExistFolder(IConnection connection, string folderName, out ImapFolderInfo folderInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| folderName | String | Name of the folder |
| folderInfo | ImapFolderInfo& | Folder information |

### Return Value

Returns true if the folder is existing, otherwise returns false

### See Also

* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapFolderInfo](../../imapfolderinfo/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


