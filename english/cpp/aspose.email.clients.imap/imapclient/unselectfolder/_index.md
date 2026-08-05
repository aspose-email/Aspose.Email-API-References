---
title: "Aspose::Email::Clients::Imap::ImapClient::UnselectFolder method"
linktitle: "UnselectFolder"
articleTitle: "UnselectFolder"
second_title: "Aspose.Email for C++"
description: "Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder."
type: docs
weight: 2100
url: /cpp/aspose.email.clients.imap/imapclient/unselectfolder/
---

## UnselectFolder (1 of 4) {#unselectfolder_1}

Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder.

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
UnselectFolder()
```

---

## UnselectFolder (2 of 4) {#unselectfolder_2}

Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
UnselectFolder(bool doNotExpunge)
```

| Parameter | Description |
| --- | --- |
| doNotExpunge | Specifies whether messages marked as deleted should be removed. |

---

## UnselectFolder (3 of 4) {#unselectfolder_3}

Permanently removes all messages marked as deleted for currently selected folder and removes selected-state for this folder.

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
UnselectFolder(System::SharedPtr < IConnection > connection)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |

---

## UnselectFolder (4 of 4) {#unselectfolder_4}

Unselects folder which are currently selected. if doNotExpunge property is true, all messages are marked as deleted are removed, otherwise deletion canceled. Please note, this operation works only in case if server supports RFC3691 See more https://tools.ietf.org/html/rfc3691

**Returns:** void Aspose::Email::Clients::Imap::

```cpp
UnselectFolder(System::SharedPtr < IConnection > connection, bool doNotExpunge)
```

| Parameter | Description |
| --- | --- |
| connection | Connection to a server |
| doNotExpunge | Specifies whether messages marked as deleted should be removed. |

