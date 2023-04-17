---
title: IEWSClient.DeleteInboxRule
second_title: Aspose.Email for .NET API Reference
description: IEWSClient method. Deletes the specified inbox rule
type: docs
weight: 630
url: /net/aspose.email.clients.exchange.webservice/iewsclient/deleteinboxrule/
---
## DeleteInboxRule(string) {#deleteinboxrule}

Deletes the specified inbox rule

```csharp
public void DeleteInboxRule(string ruleId)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ruleId | String | An id of inbox rule to delete |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | throws when *ruleId* is `null` or `empty` |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)

---

## DeleteInboxRule(string, string) {#deleteinboxrule_1}

Deletes the specified inbox rule

```csharp
public void DeleteInboxRule(string ruleId, string mailbox)
```

| Parameter | Type | Description |
| --- | --- | --- |
| ruleId | String | An id of inbox rule to delete |
| mailbox | String | A mailbox where rule is located. Note: if it is set to `null` or `empty`, the rule will be searched in the default mailbox |

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentException](../../../aspose.email/asposeargumentexception/) | throws when *ruleId* is `null` or `empty` |

### See Also

* interface [IEWSClient](../)
* namespace [Aspose.Email.Clients.Exchange.WebService](../../iewsclient/)
* assembly [Aspose.Email](../../../)


