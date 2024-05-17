---
title: IGraphClient.CreateOrUpdateOverride
second_title: Aspose.Email for .NET API Reference
description: IGraphClient method. Create an override for a sender identified by an SMTP address. Future messages from that SMTP address will be consistently classified as specified in the override. Note  If an override already exists with the same SMTP address then the classifyAs and name fields of that override are updated with the provided values.  The maximum number of overrides supported for a mailbox is 1000 based on unique sender SMTP addresses. Permissions Delegatedwork or school account Mail.ReadWrite Delegatedpersonal Microsoft account Mail.ReadWrite Application Mail.ReadWrite
type: docs
weight: 180
url: /net/aspose.email.clients.graph/igraphclient/createorupdateoverride/
---
## CreateOrUpdateOverride(MailAddress, ClassificationType) {#createorupdateoverride_1}

Create an override for a sender identified by an SMTP address. Future messages from that SMTP address will be consistently classified as specified in the override. Note: - If an override already exists with the same SMTP address, then the classifyAs and name fields of that override are updated with the provided values. - The maximum number of overrides supported for a mailbox is 1000, based on unique sender SMTP addresses. Permissions: Delegated(work or school account) Mail.ReadWrite Delegated(personal Microsoft account) Mail.ReadWrite Application Mail.ReadWrite

```csharp
public ClassificationOverride CreateOrUpdateOverride(MailAddress sender, 
    ClassificationType classifyAs)
```

| Parameter | Type | Description |
| --- | --- | --- |
| sender | MailAddress | Email address information of the sender for whom the override is created. |
| classifyAs | ClassificationType | Value which specifies how incoming messages from a specific sender should always be classified as. |

### See Also

* class [ClassificationOverride](../../classificationoverride/)
* class [MailAddress](../../../aspose.email/mailaddress/)
* enum [ClassificationType](../../classificationtype/)
* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)

---

## CreateOrUpdateOverride(ClassificationOverride) {#createorupdateoverride}

Create an override for a sender identified by an SMTP address. Future messages from that SMTP address will be consistently classified as specified in the override. Note: - If an override already exists with the same SMTP address, then the classifyAs and name fields of that override are updated with the provided values. - The maximum number of overrides supported for a mailbox is 1000, based on unique sender SMTP addresses. Permissions: Delegated(work or school account) Mail.ReadWrite Delegated(personal Microsoft account) Mail.ReadWrite Application Mail.ReadWrite

```csharp
public ClassificationOverride CreateOrUpdateOverride(ClassificationOverride classificationOverride)
```

| Parameter | Type | Description |
| --- | --- | --- |
| classificationOverride | ClassificationOverride |  |

### See Also

* class [ClassificationOverride](../../classificationoverride/)
* interface [IGraphClient](../)
* namespace [Aspose.Email.Clients.Graph](../../igraphclient/)
* assembly [Aspose.Email](../../../)


