---
title: StringComparisonField.Contains
second_title: Aspose.Email for .NET API Reference
description: StringComparisonField method. Indicates that field in message must contain the specified value
type: docs
weight: 10
url: /net/aspose.email.tools.search/stringcomparisonfield/contains/
---
## Contains(string) {#contains}

Indicates that field in message must contain the specified value.

```csharp
public MailQuery Contains(string value)
```

| Parameter | Type | Description |
| --- | --- | --- |
| value | String | The value. |

### Return Value

[`MailQuery`](../../mailquery/) that represents search query (one searching criterion).

### See Also

* class [MailQuery](../../mailquery/)
* class [StringComparisonField](../)
* namespace [Aspose.Email.Tools.Search](../../stringcomparisonfield/)
* assembly [Aspose.Email](../../../)

---

## Contains(string, bool) {#contains_1}

Indicates that field in message must contain the specified value.

```csharp
public MailQuery Contains(string value, bool ignoreCase)
```

| Parameter | Type | Description |
| --- | --- | --- |
| value | String | The value. |
| ignoreCase | Boolean | true to ignore case during the comparison; otherwise, false. |

### Return Value

[`MailQuery`](../../mailquery/) that represents search query (one searching criterion).

### Exceptions

| exception | condition |
| --- | --- |
| [AsposeArgumentNullException](../../../aspose.email/asposeargumentnullexception/) | value;Field value should not be null or empty |

### See Also

* class [MailQuery](../../mailquery/)
* class [StringComparisonField](../)
* namespace [Aspose.Email.Tools.Search](../../stringcomparisonfield/)
* assembly [Aspose.Email](../../../)


