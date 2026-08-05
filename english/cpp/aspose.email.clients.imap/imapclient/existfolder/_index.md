---
title: "Aspose::Email::Clients::Imap::ImapClient::ExistFolder method"
linktitle: "ExistFolder"
articleTitle: "ExistFolder"
second_title: "Aspose.Email for C++"
description: "Check whether this folder exists"
type: docs
weight: 1100
url: /cpp/aspose.email.clients.imap/imapclient/existfolder/
---

## ExistFolder (1 of 4) {#existfolder_1}

Check whether this folder exists

**Returns:** Returns true if the folder is existing, otherwise returns false

```cpp
ExistFolder(System::SharedPtr < IConnection > connection, System::String folderName)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Name of the folder |

---

## ExistFolder (2 of 4) {#existfolder_2}

Check whether this folder exists, extract folder info if so

**Returns:** Returns true if the folder is existing, otherwise returns false

```cpp
ExistFolder(System::SharedPtr < IConnection > connection, System::String folderName, System::SharedPtr < ImapFolderInfo > & folderInfo)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folderName | Name of the folder |
| folderInfo | Folder information |

---

## ExistFolder (3 of 4) {#existfolder_3}

Check whether this folder exists

**Returns:** Returns true if the folder is existing, otherwise returns false

```cpp
ExistFolder(System::String folderName)
```

| Parameter | Description |
| --- | --- |
| folderName | Name of the folder |

---

## ExistFolder (4 of 4) {#existfolder_4}

Check whether this folder exists, extract folder info if so

**Returns:** Returns true if the folder is existing, otherwise returns false

```cpp
ExistFolder(System::String folderName, System::SharedPtr < ImapFolderInfo > & folderInfo)
```

| Parameter | Description |
| --- | --- |
| folderName | Name of the folder |
| folderInfo | Folder information |

