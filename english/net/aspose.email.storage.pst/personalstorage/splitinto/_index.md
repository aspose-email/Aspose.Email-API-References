---
title: PersonalStorage.SplitInto
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Splits the pst storage into less sized parts
type: docs
weight: 350
url: /net/aspose.email.storage.pst/personalstorage/splitinto/
---
## SplitInto(long, string) {#splitinto}

Splits the pst storage into less sized parts.

```csharp
public void SplitInto(long chunkSize, string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | Int64 | The approximate size of a chunk in bytes. |
| path | String | The folder path where chunks will be created. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Throws when the path parameter is null or empty. |
| ArgumentException | Throws when the chunk size is less then the minimum size of pst file. |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## SplitInto(IList&lt;MailQuery&gt;, string) {#splitinto_2}

Splits the pst storage based on criteria.

```csharp
public void SplitInto(IList<MailQuery> criteria, string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| criteria | IList`1 | The collection of [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents criteria of pst splitting. |
| path | String | The folder path where chunks will be created. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Throws when the path parameter is null or empty. |

### See Also

* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## SplitInto(long, string, string) {#splitinto_1}

Splits the pst storage into less sized parts.

```csharp
public void SplitInto(long chunkSize, string partFileNamePrefix, string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| chunkSize | Int64 | The approximate size of a chunk in bytes. |
| path | String | The folder path where chunks will be created. |
| partFileNamePrefix | String | The prefix to be added to the filename of each part of pst. If provided, the prefix will be added to the beginning of each file name. If not provided (null or empty), the pst parts will be created without a prefix. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Throws when the path parameter is null or empty. |
| ArgumentException | Throws when the chunk size is less then the minimum size of pst file. |

## Remarks

The pst file names are produced using the following template: {prefix}_part{number}.pst - {prefix}: The filename prefix provided by the partFileNamePrefix parameter. If not provided, this part will be omitted. - {number}: The number of the chunk file.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## SplitInto(IList&lt;MailQuery&gt;, string, string) {#splitinto_3}

Splits the pst storage based on criteria.

```csharp
public void SplitInto(IList<MailQuery> criteria, string partFileNamePrefix, string path)
```

| Parameter | Type | Description |
| --- | --- | --- |
| criteria | IList`1 | The collection of [`MailQuery`](../../../aspose.email.tools.search/mailquery/) that represents criteria of pst splitting. |
| path | String | The folder path where chunks will be created. |
| partFileNamePrefix | String | The prefix to be added to the filename of each part of pst. If provided, the prefix will be added to the beginning of each file name. If not provided (null or empty), the pst parts will be created without a prefix. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Throws when the path parameter is null or empty. |

## Remarks

The pst file names are produced using the following template: {prefix}_part{number}.pst - {prefix}: The filename prefix provided by the partFileNamePrefix parameter. If not provided, this part will be omitted. - {number}: The number of the chunk file.

### See Also

* class [MailQuery](../../../aspose.email.tools.search/mailquery/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


