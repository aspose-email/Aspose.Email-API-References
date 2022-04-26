---
title: ListFolders
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 830
url: /net/aspose.email.clients.imap/imapclient/listfolders/
---
## ImapClient.ListFolders method (1 of 10)

Gets the list of folders in the mailbox

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

## Return Value

Collection of ImapFolderInfo objects

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFolders method (2 of 10)

Gets the list of subfolders in the specified folder

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, string parentFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| parentFolder | String | Name of the folder |

## Return Value

Collection of ImapFolderInfo objects

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFolders method (3 of 10)

Gets the list of folders in the mailbox

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, bool loadFullInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

## Return Value

Collection of ImapFolderInfo objects

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFolders method (4 of 10)

Gets the list of folders in the mailbox

```csharp
public ImapFolderInfoCollection ListFolders()
```

## Return Value

Collection of ImapFolderInfo objects

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFolders method (5 of 10)

Gets the list of subfolders in the specified folder

```csharp
public ImapFolderInfoCollection ListFolders(string parentFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |

## Return Value

Collection of ImapFolderInfo objects

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFolders method (6 of 10)

Gets the list of folders in the mailbox

```csharp
public ImapFolderInfoCollection ListFolders(bool loadFullInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

## Return Value

Collection of ImapFolderInfo objects

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFolders method (7 of 10)

Gets the list of subfolders in the specified folder

```csharp
public ImapFolderInfoCollection ListFolders(string parentFolder, bool loadFullInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

## Return Value

Collection of ImapFolderInfo objects

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFolders method (8 of 10)

Gets the list of subfolders in the specified folder

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, string parentFolder, 
    bool loadFullInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

## Return Value

Collection of ImapFolderInfo objects

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFolders method (9 of 10)

Gets the list of subfolders in the specified folder

```csharp
public ImapFolderInfoCollection ListFolders(string parentFolder, bool loadFullInfo, 
    ListFoldersOptions options, ListFoldersReturnOptions returnOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| options | ListFoldersOptions | Options for operation |
| returnOptions | ListFoldersReturnOptions | Return options for operation |

## Return Value

Collection of ImapFolderInfo objects

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFolders method (10 of 10)

Gets the list of subfolders in the specified folder

```csharp
public ImapFolderInfoCollection ListFolders(IConnection connection, string parentFolder, 
    bool loadFullInfo, ListFoldersOptions options, ListFoldersReturnOptions returnOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| options | ListFoldersOptions | Options for operation |
| returnOptions | ListFoldersReturnOptions | Return options for operation |

## Return Value

Collection of ImapFolderInfo objects

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->