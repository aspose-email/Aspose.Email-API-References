---
title: IGraphClient.GetOneNoteOperationStatus
second_title: Aspose.Email for .NET API Reference
description: IGraphClient method. Get the status of a longrunning OneNote operation. This applies to operations that return the OperationLocation header in the response such as CopyNotebook CopyToNotebook CopyToSectionGroup and CopyToSection. You can poll the OperationLocation endpoint until the status property returns completed or failed. If the status is completed the resourceLocation property contains the resource endpoint URI. If the status is failed the error and api.diagnostics properties provide error information
type: docs
weight: 360
url: /net/aspose.email.clients.graph/igraphclient/getonenoteoperationstatus/
---
## IGraphClient.GetOneNoteOperationStatus method

Get the status of a long-running OneNote operation. This applies to operations that return the Operation-Location header in the response, such as CopyNotebook, CopyToNotebook, CopyToSectionGroup, and CopyToSection. You can poll the Operation-Location endpoint until the status property returns completed or failed. If the status is completed, the resourceLocation property contains the resource endpoint URI. If the status is failed, the error and @api.diagnostics properties provide error information.

```csharp
public OnenoteOperation GetOneNoteOperationStatus(string operationId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| operationId | String | Operation id |

### See Also

* class [OnenoteOperation](../../onenoteoperation/)
* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)


