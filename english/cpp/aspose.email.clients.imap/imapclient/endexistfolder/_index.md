---
title: "Aspose::Email::Clients::Imap::ImapClient::EndExistFolder method"
linktitle: "EndExistFolder"
articleTitle: "EndExistFolder"
second_title: "Aspose.Email for C++"
description: "Waits for the pending asynchronous operation to complete."
type: docs
weight: 760
url: /cpp/aspose.email.clients.imap/imapclient/endexistfolder/
---

## EndExistFolder (1 of 2) {#endexistfolder_1}

Waits for the pending asynchronous operation to complete.

**Returns:** Returns true if the folder is existing, otherwise returns false

```cpp
EndExistFolder(System::SharedPtr < System::IAsyncResult > asyncResult)
```

| Parameter | Description |
| --- | --- |
| asyncResult | The reference to the pending asynchronous request to wait for. |

---

## EndExistFolder (2 of 2) {#endexistfolder_2}

Waits for the pending asynchronous operation to complete.

**Returns:** Returns true if the folder is existing, otherwise returns false

```cpp
EndExistFolder(System::SharedPtr < System::IAsyncResult > asyncResult, System::SharedPtr < ImapFolderInfo > & folderInfo)
```

| Parameter | Description |
| --- | --- |
| asyncResult | The reference to the pending asynchronous request to wait for. |
| folderInfo | Folder information |

