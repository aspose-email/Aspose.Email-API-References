---
title: "Aspose::Email::Clients::Imap::BackupSettings::BackupSettings constructor"
linktitle: "BackupSettings"
articleTitle: "BackupSettings"
second_title: "Aspose.Email for C++"
description: "Initializes a new instance of the BackupSettings class"
type: docs
weight: 10
url: /cpp/aspose.email.clients.imap/backupsettings/backupsettings/
---

## BackupSettings (1 of 3) {#backupsettings_1}

Initializes a new instance of the BackupSettings class

**Returns:** Aspose::Email::Clients::Imap::

```cpp
BackupSettings()
```

---

## BackupSettings (2 of 3) {#backupsettings_2}

Initializes a new instance of the BackupSettings class

**Returns:** Aspose::Email::Clients::Imap::

```cpp
BackupSettings(Storage::Pst::BackupOptions options)
```

| Parameter | Description |
| --- | --- |
| options | enumerates backup options |

---

## BackupSettings (3 of 3) {#backupsettings_3}

Initializes a new instance of the BackupSettings class

**Returns:** Aspose::Email::Clients::Imap::

```cpp
BackupSettings(bool executeRecursively, bool restoreConnection, int32_t numberOfAttempts, int32_t timeoutBetweenAttempts)
```

| Parameter | Description |
| --- | --- |
| executeRecursively | defines if backup should be executed recursively |
| restoreConnection | defines if connection has to be restored in case if server closes connection forcibly |
| numberOfAttempts | defines number of attempts to repeat failed operation |
| timeoutBetweenAttempts | defines timeout (in milliseconds) between attemptions to execute operation again |

