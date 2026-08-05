---
title: "Aspose::Email::Clients::Imap::ImapClient::ListFolders method"
linktitle: "ListFolders"
articleTitle: "ListFolders"
second_title: "Aspose.Email for C++"
description: "Gets the list of folders in the mailbox"
type: docs
weight: 1570
url: /cpp/aspose.email.clients.imap/imapclient/listfolders/
---

## ListFolders (1 of 10) {#listfolders_1}

Gets the list of folders in the mailbox

**Returns:** Collection of ImapFolderInfo objects

```cpp
ListFolders()
```

---

## ListFolders (2 of 10) {#listfolders_2}

Gets the list of folders in the mailbox

**Returns:** Collection of ImapFolderInfo objects

```cpp
ListFolders(bool loadFullInfo)
```

| Parameter | Description |
| --- | --- |
| loadFullInfo | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

---

## ListFolders (3 of 10) {#listfolders_3}

Gets the list of folders in the mailbox

**Returns:** Collection of ImapFolderInfo objects

```cpp
ListFolders(System::SharedPtr < IConnection > connection)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |

---

## ListFolders (4 of 10) {#listfolders_4}

Gets the list of folders in the mailbox

**Returns:** Collection of ImapFolderInfo objects

```cpp
ListFolders(System::SharedPtr < IConnection > connection, bool loadFullInfo)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| loadFullInfo | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

---

## ListFolders (5 of 10) {#listfolders_5}

Gets the list of subfolders in the specified folder

**Returns:** Collection of ImapFolderInfo objects

```cpp
ListFolders(System::SharedPtr < IConnection > connection, System::String parentFolder)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| parentFolder | Name of the folder |

---

## ListFolders (6 of 10) {#listfolders_6}

Gets the list of subfolders in the specified folder

**Returns:** Collection of ImapFolderInfo objects

```cpp
ListFolders(System::SharedPtr < IConnection > connection, System::String parentFolder, bool loadFullInfo)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| parentFolder | Name of the folder |
| loadFullInfo | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

---

## ListFolders (7 of 10) {#listfolders_7}

Gets the list of subfolders in the specified folder

**Returns:** Collection of ImapFolderInfo objects

```cpp
ListFolders(System::SharedPtr < IConnection > connection, System::String parentFolder, bool loadFullInfo, ListFoldersOptions options, ListFoldersReturnOptions returnOptions)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| parentFolder | Name of the folder |
| loadFullInfo | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| options | Options for operation |
| returnOptions | Return options for operation |

---

## ListFolders (8 of 10) {#listfolders_8}

Gets the list of subfolders in the specified folder

**Returns:** Collection of ImapFolderInfo objects

```cpp
ListFolders(System::String parentFolder)
```

| Parameter | Description |
| --- | --- |
| parentFolder | Name of the folder |

---

## ListFolders (9 of 10) {#listfolders_9}

Gets the list of subfolders in the specified folder

**Returns:** Collection of ImapFolderInfo objects

```cpp
ListFolders(System::String parentFolder, bool loadFullInfo)
```

| Parameter | Description |
| --- | --- |
| parentFolder | Name of the folder |
| loadFullInfo | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |

---

## ListFolders (10 of 10) {#listfolders_10}

Gets the list of subfolders in the specified folder

**Returns:** Collection of ImapFolderInfo objects

```cpp
ListFolders(System::String parentFolder, bool loadFullInfo, ListFoldersOptions options, ListFoldersReturnOptions returnOptions)
```

| Parameter | Description |
| --- | --- |
| parentFolder | Name of the folder |
| loadFullInfo | If true indicates that folder information should be retrieved from a server completely, otherwise only folder names are retrieved. |
| options | Options for operation |
| returnOptions | Return options for operation |

