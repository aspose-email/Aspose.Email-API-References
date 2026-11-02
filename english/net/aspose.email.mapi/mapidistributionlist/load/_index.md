---
title: MapiDistributionList.Load
second_title: Aspose.Email for .NET API Reference
description: MapiDistributionList method. Loads a MapiDistributionList from the specified file
type: docs
weight: 30
url: /net/aspose.email.mapi/mapidistributionlist/load/
---
## Load(string) {#load_1}

Loads a [`MapiDistributionList`](../) from the specified file.

```csharp
public static MapiDistributionList Load(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to be loaded. |

### Return Value

Returns a [`MapiDistributionList`](../) instance loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| FileNotFoundException | The specified file does not exist. |
| InvalidOperationException | The file does not contain a distribution list item. |

### See Also

* class [MapiDistributionList](../)
* namespace [Aspose.Email.Mapi](../../mapidistributionlist/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Loads a [`MapiDistributionList`](../) from the specified stream.

```csharp
public static MapiDistributionList Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to be loaded. |

### Return Value

Returns a [`MapiDistributionList`](../) instance loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| InvalidOperationException | The stream does not contain a distribution list item. |

### See Also

* class [MapiDistributionList](../)
* namespace [Aspose.Email.Mapi](../../mapidistributionlist/)
* assembly [Aspose.Email](../../../)


