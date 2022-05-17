---
title: ListFoldersAsync
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 840
url: /net/aspose.email.clients.imap/imapclient/listfoldersasync/
---
## ImapClient.ListFoldersAsync method (1 of 20)

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (2 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, string parentFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| parentFolder | String | Name of the folder |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (3 of 20)

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, bool loadFullInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (4 of 20)

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync()
```

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (5 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (6 of 20)

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(bool loadFullInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (7 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder, bool loadFullInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (8 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, string parentFolder, 
    bool loadFullInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (9 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder, bool loadFullInfo, 
    ListFoldersOptions options, ListFoldersReturnOptions returnOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| options | ListFoldersOptions | Options for operation |
| returnOptions | ListFoldersReturnOptions | Return options for operation |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (10 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, string parentFolder, 
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

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (11 of 20)

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (12 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, string parentFolder, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| parentFolder | String | Name of the folder |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (13 of 20)

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, bool loadFullInfo, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (14 of 20)

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (15 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (16 of 20)

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(bool loadFullInfo, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (17 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder, bool loadFullInfo, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (18 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, string parentFolder, 
    bool loadFullInfo, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (19 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder, bool loadFullInfo, 
    ListFoldersOptions options, ListFoldersReturnOptions returnOptions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| options | ListFoldersOptions | Options for operation |
| returnOptions | ListFoldersReturnOptions | Return options for operation |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

---

## ImapClient.ListFoldersAsync method (20 of 20)

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, string parentFolder, 
    bool loadFullInfo, ListFoldersOptions options, ListFoldersReturnOptions returnOptions, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| options | ListFoldersOptions | Options for operation |
| returnOptions | ListFoldersReturnOptions | Return options for operation |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection)
* interface [IConnection](../../../aspose.email.clients/iconnection)
* enum [ListFoldersOptions](../../listfoldersoptions)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions)
* class [ImapClient](../../imapclient)
* namespace [Aspose.Email.Clients.Imap](../../imapclient)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
