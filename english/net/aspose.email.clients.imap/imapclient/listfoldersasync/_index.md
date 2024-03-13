---
title: ImapClient.ListFoldersAsync
second_title: Aspose.Email for .NET API Reference
description: ImapClient method. Gets the list of folders in the mailbox
type: docs
weight: 850
url: /net/aspose.email.clients.imap/imapclient/listfoldersasync/
---
## ListFoldersAsync(IConnection) {#listfoldersasync_1}

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(IConnection, string) {#listfoldersasync_4}

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, string parentFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| parentFolder | String | Name of the folder |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(IConnection, bool) {#listfoldersasync_2}

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, bool loadFullInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync() {#listfoldersasync}

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync()
```

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(string) {#listfoldersasync_13}

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(bool) {#listfoldersasync_11}

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(bool loadFullInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(string, bool) {#listfoldersasync_14}

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder, bool loadFullInfo)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(IConnection, string, bool) {#listfoldersasync_5}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(string, bool, ListFoldersOptions, ListFoldersReturnOptions) {#listfoldersasync_15}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* enum [ListFoldersOptions](../../listfoldersoptions/)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions) {#listfoldersasync_6}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* enum [ListFoldersOptions](../../listfoldersoptions/)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(IConnection, CancellationToken) {#listfoldersasync_10}

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(IConnection connection, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| connection | IConnection | Connection to a server |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(IConnection, string, CancellationToken) {#listfoldersasync_9}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(IConnection, bool, CancellationToken) {#listfoldersasync_3}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(CancellationToken) {#listfoldersasync_19}

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(string, CancellationToken) {#listfoldersasync_18}

Gets the list of subfolders in the specified folder

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(string parentFolder, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| parentFolder | String | Name of the folder |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(bool, CancellationToken) {#listfoldersasync_12}

Gets the list of folders in the mailbox

```csharp
public Task<ImapFolderInfoCollection> ListFoldersAsync(bool loadFullInfo, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| loadFullInfo | Boolean | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(string, bool, CancellationToken) {#listfoldersasync_17}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(IConnection, string, bool, CancellationToken) {#listfoldersasync_8}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) {#listfoldersasync_16}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* enum [ListFoldersOptions](../../listfoldersoptions/)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)

---

## ListFoldersAsync(IConnection, string, bool, ListFoldersOptions, ListFoldersReturnOptions, CancellationToken) {#listfoldersasync_7}

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

### Return Value

Task object, with delegate for this operation

### See Also

* class [ImapFolderInfoCollection](../../imapfolderinfocollection/)
* interface [IConnection](../../../aspose.email.clients/iconnection/)
* enum [ListFoldersOptions](../../listfoldersoptions/)
* enum [ListFoldersReturnOptions](../../listfoldersreturnoptions/)
* class [ImapClient](../)
* namespace [Aspose.Email.Clients.Imap](../../imapclient/)
* assembly [Aspose.Email](../../../)


