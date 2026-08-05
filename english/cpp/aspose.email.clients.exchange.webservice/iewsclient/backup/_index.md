---
title: "Aspose::Email::Clients::Exchange::WebService::IEWSClient::Backup method"
linktitle: "Backup"
articleTitle: "Backup"
second_title: "Aspose.Email for C++"
description: "Backups the content of the specified folders"
type: docs
weight: 60
url: /cpp/aspose.email.clients.exchange.webservice/iewsclient/backup/
---

## Backup (1 of 2) {#backup_1}

Backups the content of the specified folders

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
Backup(System::SharedPtr < ExchangeFolderInfoCollection > folders, System::SharedPtr < System::IO::Stream > stream, Storage::Pst::BackupOptions options)
```

| Parameter | Description |
| --- | --- |
| folders | A folders to backup |
| stream | A stream to write into |
| options | A backup options |

---

## Backup (2 of 2) {#backup_2}

Backups the content of the specified folders

**Returns:** virtual void Aspose::Email::Clients::Exchange::WebService::

```cpp
Backup(System::SharedPtr < ExchangeFolderInfoCollection > folders, System::String fileName, Storage::Pst::BackupOptions options)
```

| Parameter | Description |
| --- | --- |
| folders | A folders to backup |
| fileName | A path to the presonal storage file |
| options | A backup options |

