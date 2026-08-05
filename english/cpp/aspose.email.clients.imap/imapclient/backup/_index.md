---
title: "Aspose::Email::Clients::Imap::ImapClient::Backup method"
linktitle: "Backup"
articleTitle: "Backup"
second_title: "Aspose.Email for C++"
description: "Backups the content of the specified folders"
type: docs
weight: 40
url: /cpp/aspose.email.clients.imap/imapclient/backup/
---

## Backup (1 of 4) {#backup_1}

Backups the content of the specified folders

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
Backup(System::SharedPtr < IConnection > connection, System::SharedPtr < ImapFolderInfoCollection > folders, System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < BackupSettings > options)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folders | A folders to backup |
| stream | A stream to write into |
| options | A backup options |

---

## Backup (2 of 4) {#backup_2}

Backups the content of the specified folders

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
Backup(System::SharedPtr < IConnection > connection, System::SharedPtr < ImapFolderInfoCollection > folders, System::String fileName, System::SharedPtr < BackupSettings > options)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| folders | A folders to backup |
| fileName | A path to the presonal storage file |
| options | A backup options |

---

## Backup (3 of 4) {#backup_3}

Backups the content of the specified folders

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
Backup(System::SharedPtr < ImapFolderInfoCollection > folders, System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < BackupSettings > options)
```

| Parameter | Description |
| --- | --- |
| folders | A folders to backup |
| stream | A stream to write into |
| options | A backup options |

---

## Backup (4 of 4) {#backup_4}

Backups the content of the specified folders

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
Backup(System::SharedPtr < ImapFolderInfoCollection > folders, System::String fileName, System::SharedPtr < BackupSettings > options)
```

| Parameter | Description |
| --- | --- |
| folders | A folders to backup |
| fileName | A path to the presonal storage file |
| options | A backup options |

