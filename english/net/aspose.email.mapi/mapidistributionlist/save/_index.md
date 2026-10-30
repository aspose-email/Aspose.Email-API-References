---
title: MapiDistributionList.Save
second_title: Aspose.Email for .NET API Reference
description: MapiDistributionList method. Saves the distribution list to a file in MSG format
type: docs
weight: 70
url: /net/aspose.email.mapi/mapidistributionlist/save/
---
## Save(string) {#save_2}

Saves the distribution list to a file in MSG format.

```csharp
public void Save(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file to write. |

### See Also

* class [MapiDistributionList](../)
* namespace [Aspose.Email.Mapi](../../mapidistributionlist/)
* assembly [Aspose.Email](../../../)

---

## Save(string, MapiDistributionListSaveOptions) {#save_3}

Saves the distribution list to a file with the specified options.

```csharp
public void Save(string fileName, MapiDistributionListSaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file to write. |
| options | MapiDistributionListSaveOptions | The options; [`SaveFormat`](../../contactsaveoptions/saveformat/) selects MSG or vCard. In vCard format every member is written as a separate vCard. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | The format is vCard and the list has no members. |
| NotSupportedException | The format is WebDAV, which a distribution list cannot be saved to. |

### See Also

* class [MapiDistributionListSaveOptions](../../mapidistributionlistsaveoptions/)
* class [MapiDistributionList](../)
* namespace [Aspose.Email.Mapi](../../mapidistributionlist/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Saves the distribution list to a stream in MSG format.

```csharp
public void Save(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |

### See Also

* class [MapiDistributionList](../)
* namespace [Aspose.Email.Mapi](../../mapidistributionlist/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, MapiDistributionListSaveOptions) {#save_1}

Saves the distribution list to a stream with the specified options.

```csharp
public void Save(Stream stream, MapiDistributionListSaveOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| options | MapiDistributionListSaveOptions | The options; [`SaveFormat`](../../contactsaveoptions/saveformat/) selects MSG or vCard. In vCard format every member is written as a separate vCard. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | The format is vCard and the list has no members. |
| NotSupportedException | The format is WebDAV, which a distribution list cannot be saved to. |

### See Also

* class [MapiDistributionListSaveOptions](../../mapidistributionlistsaveoptions/)
* class [MapiDistributionList](../)
* namespace [Aspose.Email.Mapi](../../mapidistributionlist/)
* assembly [Aspose.Email](../../../)


