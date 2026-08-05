---
title: "Aspose::Email::Clients::Exchange::Dav::ExchangeClient::Restore method"
linktitle: "Restore"
articleTitle: "Restore"
second_title: "Aspose.Email for C++"
description: "Restores exchange folders from the given personal storage."
type: docs
weight: 400
url: /cpp/aspose.email.clients.exchange.dav/exchangeclient/restore/
---

## Restore (1 of 6) {#restore_1}

Restores exchange folders from the given personal storage.

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
Restore(System::SharedPtr < Storage::Pst::PersonalStorage > pst, Storage::Pst::RestoreOptions options)
```

| Parameter | Description |
| --- | --- |
| pst | A personal storage containing the backuped imap folders. |
| options | Restore options. |

---

## Restore (2 of 6) {#restore_2}

Restores the specified exchange folders from the given personal storage.

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
Restore(System::SharedPtr < Storage::Pst::PersonalStorage > pst, System::SharedPtr < ExchangeFolderInfoCollection > folders, Storage::Pst::RestoreOptions options)
```

| Parameter | Description |
| --- | --- |
| pst | A personal storage containing the backuped exchange folders. |
| folders | A folders to be restored. |
| options | Restore options. |

---

## Restore (3 of 6) {#restore_3}

Restores exchange folders from the given personal storage.

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
Restore(System::SharedPtr < System::IO::Stream > stream, Storage::Pst::RestoreOptions options)
```

| Parameter | Description |
| --- | --- |
| stream | A stream containing personal storage. |
| options | Restore options. |

---

## Restore (4 of 6) {#restore_4}

Restores the specified exchange folders from the given personal storage.

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
Restore(System::SharedPtr < System::IO::Stream > stream, System::SharedPtr < ExchangeFolderInfoCollection > folders, Storage::Pst::RestoreOptions options)
```

| Parameter | Description |
| --- | --- |
| stream | A stream containing personal storage. |
| folders | A folders to be restored. |
| options | Restore options. |

---

## Restore (5 of 6) {#restore_5}

Restores exchange folders from the specified personal storage file.

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
Restore(System::String fileName, Storage::Pst::RestoreOptions options)
```

| Parameter | Description |
| --- | --- |
| fileName | A path to personal storage file. |
| options | Restore options. |

---

## Restore (6 of 6) {#restore_6}

Restores the specified exchange folders from the specified personal storage file.

**Returns:** void Aspose::Email::Clients::Exchange::Dav::

```cpp
Restore(System::String fileName, System::SharedPtr < ExchangeFolderInfoCollection > folders, Storage::Pst::RestoreOptions options)
```

| Parameter | Description |
| --- | --- |
| fileName | A path to personal storage file. |
| folders | A folders to be restored. |
| options | Restore options. |

