---
title: PersonalStorage.Load
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Opens a PST file for reading for a storage created with the constructor that takes a TraversalExceptionsCallback
type: docs
weight: 320
url: /net/aspose.email.storage.pst/personalstorage/load/
---
## Load(string) {#load_1}

Opens a PST file for reading, for a storage created with the constructor that takes a `TraversalExceptionsCallback`.

```csharp
public bool Load(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |

### Return Value

`true` if the file has been loaded and can be traversed; otherwise, `false`.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *fileName* is `null` or empty. |

## Remarks

The file is opened for reading only. Problems found while reading are reported to the callback passed to the constructor instead of being thrown.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Opens a PST from a stream for reading, for a storage created with the constructor that takes a `TraversalExceptionsCallback`.

```csharp
public bool Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream with the PST data. |

### Return Value

`true` if the stream has been loaded and can be traversed; otherwise, `false`.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |

## Remarks

Problems found while reading are reported to the callback passed to the constructor instead of being thrown.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


