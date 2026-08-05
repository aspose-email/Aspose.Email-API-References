---
title: "Aspose::Email::Clients::Graph::IGraphClient::UpdateOverride method"
linktitle: "UpdateOverride"
articleTitle: "UpdateOverride"
second_title: "Aspose.Email for C++"
description: "Change the classifyAs field of an override as specified."
type: docs
weight: 690
url: /cpp/aspose.email.clients.graph/igraphclient/updateoverride/
---

## UpdateOverride {#updateoverride}

Change the classifyAs field of an override as specified. You cannot use this method to change any other fields in an ClassificationOverride instance. If an override exists for a sender and the sender changes his/her display name, you can use CreateOrUpdateOverride to force an update to the name field in the existing override. If an override exists for a sender and the sender changes his/her SMTP address, deleting the existing override and creating a new one with the new SMTP address is the only way to "update" the override for this sender. Permissions: One of the following permissions is required to call this API.To learn more, including how to choose permissions, see Permissions. Delegated (work or school account) Mail.ReadWrite Delegated (personal Microsoft account) Mail.ReadWrite Application Mail.ReadWrite

**Returns:** virtual System::SharedPtr < ClassificationOverride > Aspose::Email::Clients::Graph::

```cpp
UpdateOverride(System::SharedPtr < ClassificationOverride > classificationOverride)
```

| Parameter | Description |
| --- | --- |
| classificationOverride | Classification override to update |

