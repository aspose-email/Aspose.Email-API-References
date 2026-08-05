---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::SyncFolder method"
linktitle: "SyncFolder"
articleTitle: "SyncFolder"
second_title: "Aspose.Email for C++"
description: "Retrieves changes of the items in a specified folder."
type: docs
weight: 1490
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/syncfolder/
---

## SyncFolder (1 of 5) {#syncfolder_1}

Retrieves changes of the items in a specified folder.

**Returns:** Returns result of SyncFolder operation.

```cpp
SyncFolder(System::SharedPtr < SyncState > syncState)
```

| Parameter | Description |
| --- | --- |
| syncState | The synchronization state. |

---

## SyncFolder (2 of 5) {#syncfolder_2}

Retrieves changes of the items and subfolders in a specified folder.

**Returns:** Returns result of SyncFolder operation.

```cpp
SyncFolder(System::String folderUri)
```

| Parameter | Description |
| --- | --- |
| folderUri | The folder uri |

---

## SyncFolder (3 of 5) {#syncfolder_3}

Retrieves changes of the items and subfolders in a specified folder.

**Returns:** Returns result of SyncFolder operation.

```cpp
SyncFolder(System::String folderUri, SyncFolderType syncType)
```

| Parameter | Description |
| --- | --- |
| folderUri | The folder uri |
| syncType | Folder synchronization type |

---

## SyncFolder (4 of 5) {#syncfolder_4}

Retrieves changes of the items in a specified folder.

**Returns:** Returns result of SyncFolder operation.

```cpp
SyncFolder(System::String folderUri, System::String syncState)
```

| Parameter | Description |
| --- | --- |
| folderUri | The folder uri |
| syncState | The optional synchronization state. Must be null for first synchronization. |

---

## SyncFolder (5 of 5) {#syncfolder_5}

Retrieves changes of the items in a specified folder.

**Returns:** Returns result of SyncFolder operation.

```cpp
SyncFolder(System::String folderUri, System::String syncState, System::SharedPtr < System::Collections::Generic::IEnumerable< System::String >> ignoreList)
```

| Parameter | Description |
| --- | --- |
| folderUri | The folder uri |
| syncState | The optional synchronization state. Must be null for first synchronization. |
| ignoreList | The optional list of item uris that should be ignored. |

