---
title: "Aspose::Email::Clients::Graph::IGraphClient::GetOneNoteOperationStatus method"
linktitle: "GetOneNoteOperationStatus"
articleTitle: "GetOneNoteOperationStatus"
second_title: "Aspose.Email for C++"
description: "Get the status of a long-running OneNote operation."
type: docs
weight: 360
url: /cpp/aspose.email.clients.graph/igraphclient/getonenoteoperationstatus/
---

## GetOneNoteOperationStatus {#getonenoteoperationstatus}

Get the status of a long-running OneNote operation. This applies to operations that return the Operation-Location header in the response, such as CopyNotebook, CopyToNotebook, CopyToSectionGroup, and CopyToSection. You can poll the Operation-Location endpoint until the status property returns completed or failed. If the status is completed, the resourceLocation property contains the resource endpoint URI. If the status is failed, the error and @api.diagnostics properties provide error information.

**Returns:** virtual System::SharedPtr < OnenoteOperation > Aspose::Email::Clients::Graph::

```cpp
GetOneNoteOperationStatus(System::String operationId)
```

| Parameter | Description |
| --- | --- |
| operationId | Operation id |

