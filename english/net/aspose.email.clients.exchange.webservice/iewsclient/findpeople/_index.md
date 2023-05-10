---
title: IEWSClient.FindPeople
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Find contacts located in the global address list GAL on server
type: docs
weight: 860
url: /net/aspose.email.clients.exchange.webservice/iewsclient/findpeople/
---
## FindPeople(string, int) {#findpeople_1}

Find contacts located in the global address list (GAL) on server.

```csharp
public Contact[] FindPeople(string queryString, int maxNumberOfItems)
```

| Parameter | Type | Description |
| --- | --- | --- |
| queryString | String | Represents contact search criteria. |
| maxNumberOfItems | Int32 | Maximum number of items. |

### Return Value

An array of [`Contact`](../../../aspose.email.personalinfo/contact/) that represents contact information

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## FindPeople(string, MailQuery, int) {#findpeople}

Find contacts located in the specified user's personal mailbox on server.

```csharp
public Contact[] FindPeople(string folderUri, MailQuery query, int maxNumberOfItems)
```

| Parameter | Type | Description |
| --- | --- | --- |
| folderUri | String | The URI of folder. |
| query | MailQuery | [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents contact search criteria. |
| maxNumberOfItems | Int32 | Maximum number of items. |

### Return Value

An array of [`Contact`](../../../aspose.email.personalinfo/contact/) that represents contact information

### See Also

* class [Contact](../../../aspose.email.personalinfo/contact/)
* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


