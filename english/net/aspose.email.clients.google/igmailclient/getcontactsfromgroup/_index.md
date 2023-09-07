---
title: IGmailClient.GetContactsFromGroup
second_title: Aspose.Email for .NET API Reference
description: IGmailClient method. Fetches contacts belonging to the group specified
type: docs
weight: 190
url: /net/aspose.email.clients.google/igmailclient/getcontactsfromgroup/
---
## IGmailClient.GetContactsFromGroup method

Fetches contacts belonging to the group specified.

```csharp
public Contact[] GetContactsFromGroup(string groupId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| groupId | String | string that represents group id for a contact |

### Return Value

Contacts array

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *groupId* is `null` or `empty`. |
| WebException | when operation fails |

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* interface [IGmailClient](../)
* namespace [Aspose.Email.Clients.Google](../../igmailclient/)
* assembly [Aspose.Email](../../../)


