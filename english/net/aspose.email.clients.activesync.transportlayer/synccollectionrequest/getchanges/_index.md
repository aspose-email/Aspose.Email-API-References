---
title: GetChanges
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 60
url: /net/aspose.email.clients.activesync.transportlayer/synccollectionrequest/getchanges/
---
## SyncCollectionRequest.GetChanges property

Requests that the server include in its response any pending changes to the collection that is specified by the ServerId element (section 2.2.3.151.6). If there have been changes since the last synchronization, the server response includes a Commands element (section 2.2.3.32) that contains additions, deletions, and changes. If the client does not want the server changes returned, the request MUST include the GetChanges element with a value of FALSE. A value of TRUE indicates that the client wants the server changes to be returned. A value of TRUE is assumed when the GetChanges element is empty. When the GetChanges element is not present in the request, the behavior depends on the value of the SyncKey element, as specified in section 2.2.3.166.4. If the SyncKey element has a value of 0, then the request is handled as if the GetChanges element were set to FALSE. If the SyncKey element has a non-zero value, then the request is handled as if the GetChanges element were set to TRUE.

```csharp
public bool? GetChanges { get; set; }
```

### See Also

* class [SyncCollectionRequest](../../synccollectionrequest)
* namespace [Aspose.Email.Clients.ActiveSync.TransportLayer](../../synccollectionrequest)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->