---
title: IGraphClientAsync.CreateOrUpdateOverrideAsync
second_title: Aspose.Email for .NET API Reference
description: IGraphClientAsync method. Asynchronously creates or updates a classification override for a sender
type: docs
weight: 110
url: /net/aspose.email.clients.graph/igraphclientasync/createorupdateoverrideasync/
---
## CreateOrUpdateOverrideAsync(MailAddress, ClassificationType, CancellationToken) {#createorupdateoverrideasync_1}

Asynchronously creates or updates a classification override for a sender.

```csharp
public Task<ClassificationOverride> CreateOrUpdateOverrideAsync(MailAddress sender, 
    ClassificationType classifyAs, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sender | MailAddress | The sender's [`MailAddress`](../../../aspose.email/mailaddress/). |
| classifyAs | ClassificationType | The classification type. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created or updated [`ClassificationOverride`](../../classificationoverride/).

### See Also

* class [ClassificationOverride](../../classificationoverride/)
* class [MailAddress](../../../aspose.email/mailaddress/)
* enum [ClassificationType](../../classificationtype/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)

---

## CreateOrUpdateOverrideAsync(ClassificationOverride, CancellationToken) {#createorupdateoverrideasync}

Asynchronously creates or updates a classification override.

```csharp
public Task<ClassificationOverride> CreateOrUpdateOverrideAsync(
    ClassificationOverride classificationOverride, CancellationToken cancellationToken = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classificationOverride | ClassificationOverride | The [`ClassificationOverride`](../../classificationoverride/) to create or update. |
| cancellationToken | CancellationToken | A cancellation token to observe while waiting for the task to complete. |

### Return Value

A task that represents the asynchronous operation. The task result contains the created or updated [`ClassificationOverride`](../../classificationoverride/).

### See Also

* class [ClassificationOverride](../../classificationoverride/)
* interface [IGraphClientAsync](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclientasync/)
* assembly [Aspose.Email](../../../)


