---
title: "Aspose::Email::Clients::Graph::IGraphClient::CopyNotebook method"
linktitle: "CopyNotebook"
articleTitle: "CopyNotebook"
second_title: "Aspose.Email for C++"
description: "Copies a notebook to the Notebooks folder in the destination Documents library."
type: docs
weight: 30
url: /cpp/aspose.email.clients.graph/igraphclient/copynotebook/
---

## CopyNotebook {#copynotebook}

Copies a notebook to the Notebooks folder in the destination Documents library. The folder is created if it doesn't exist. For Copy operations, you follow an asynchronous calling pattern: First call the Copy action, and then poll the operation endpoint for the result. Permissions One of the following permissions is required to call this API. Delegated(work or school account) Notes.Create, Notes.ReadWrite, Notes.ReadWrite.All Delegated(personal Microsoft account) Notes.Create, Notes.ReadWrite Application Notes.ReadWrite.All

**Returns:** If successful, this method returns an Operation-Location string. You may use this value to get the status of the operation.

```cpp
CopyNotebook(System::String itemId, System::String groupId, System::String renameAs)
```

| Parameter | Description |
| --- | --- |
| itemId | Item id to be copied |
| groupId | The id of the group to copy to. Use only when copying to an Office 365 group. |
| renameAs | The name of the copy. Defaults to the name of the existing item. |

