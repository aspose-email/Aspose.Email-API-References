---
title: IGraphClient.UpdateOverride
second_title: Aspose.Email for .NET API Reference
description: IGraphClient method. Change the classifyAs field of an override as specified. You cannot use this method to change any other fields in an ClassificationOverride instance. If an override exists for a sender and the sender changes his/her display name you can use CreateOrUpdateOverride to force an update to the name field in the existing override. If an override exists for a sender and the sender changes his/her SMTP address deleting the existing override and creating a new one with the new SMTP address is the only way to update the override for this sender. Permissions One of the following permissions is required to call this API.To learn more including how to choose permissions see Permissions. Delegated work or school account Mail.ReadWrite Delegated personal Microsoft account Mail.ReadWrite Application Mail.ReadWrite
type: docs
weight: 420
url: /net/aspose.email.clients.graph/igraphclient/updateoverride/
---
## IGraphClient.UpdateOverride method

Change the classifyAs field of an override as specified. You cannot use this method to change any other fields in an ClassificationOverride instance. If an override exists for a sender and the sender changes his/her display name, you can use CreateOrUpdateOverride to force an update to the name field in the existing override. If an override exists for a sender and the sender changes his/her SMTP address, deleting the existing override and creating a new one with the new SMTP address is the only way to "update" the override for this sender. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) Mail.ReadWrite Delegated (personal Microsoft account) Mail.ReadWrite Application Mail.ReadWrite

```csharp
public ClassificationOverride UpdateOverride(ClassificationOverride classificationOverride)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classificationOverride | ClassificationOverride | Classification override to update |

### See Also

* class [ClassificationOverride](../../classificationoverride/)
* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)


