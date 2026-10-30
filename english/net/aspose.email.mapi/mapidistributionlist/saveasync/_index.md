---
title: MapiDistributionList.SaveAsync
second_title: Aspose.Email for .NET API Reference
description: MapiDistributionList method. Saves the specified file name asynchronously
type: docs
weight: 80
url: /net/aspose.email.mapi/mapidistributionlist/saveasync/
---
## SaveAsync(string, MapiDistributionListSaveOptions, CancellationToken) {#saveasync_2}

Saves the specified file name asynchronously.

```csharp
public Task SaveAsync(string fileName, MapiDistributionListSaveOptions options, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Name of the file. |
| options | MapiDistributionListSaveOptions | Additional options for saving DistributionList. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown if DistributionList is empty. |
| NotSupportedException | Thrown if the DistributionList is saved in WebDav |

### See Also

* class [MapiDistributionListSaveOptions](../../mapidistributionlistsaveoptions/)
* class [MapiDistributionList](../)
* namespace [Aspose.Email.Mapi](../../mapidistributionlist/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(Stream, MapiDistributionListSaveOptions, CancellationToken) {#saveasync}

Saves the specified stream asynchronously.

```csharp
public Task SaveAsync(Stream stream, MapiDistributionListSaveOptions options, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| options | MapiDistributionListSaveOptions | Additional options for saving DistributionList. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | Thrown if DistributionList is empty. |
| NotSupportedException | Thrown if the DistributionList is saved in WebDav |

### See Also

* class [MapiDistributionListSaveOptions](../../mapidistributionlistsaveoptions/)
* class [MapiDistributionList](../)
* namespace [Aspose.Email.Mapi](../../mapidistributionlist/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_3}

Saves the specified file name asynchronously.

```csharp
public Task SaveAsync(string fileName, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Name of the file. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### See Also

* class [MapiDistributionList](../)
* namespace [Aspose.Email.Mapi](../../mapidistributionlist/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(Stream, CancellationToken) {#saveasync_1}

Saves the specified stream asynchronously.

```csharp
public Task SaveAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### See Also

* class [MapiDistributionList](../)
* namespace [Aspose.Email.Mapi](../../mapidistributionlist/)
* assembly [Aspose.Email](../../../)


