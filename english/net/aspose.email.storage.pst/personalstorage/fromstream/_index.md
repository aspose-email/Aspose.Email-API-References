---
title: PersonalStorage.FromStream
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Opens a PST or OST from a stream
type: docs
weight: 40
url: /net/aspose.email.storage.pst/personalstorage/fromstream/
---
## FromStream(Stream, bool) {#fromstream_2}

Opens a PST or OST from a stream.

```csharp
public static PersonalStorage FromStream(Stream stream, bool writable)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream with the PST or OST data. |
| writable | Boolean | `true` to open the PST for reading and writing; `false` for reading only. |

### Return Value

The opened storage.

## Remarks

The stream is closed when the storage is disposed. To keep it open, use the overload with [`PersonalStorageLoadOptions`](../../personalstorageloadoptions/) and set its `LeaveStreamOpen` property.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromStream(Stream, PersonalStorageLoadOptions) {#fromstream_1}

Opens a PST or OST from a stream with the specified options.

```csharp
public static PersonalStorage FromStream(Stream stream, PersonalStorageLoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream with the PST or OST data. |
| loadOptions | PersonalStorageLoadOptions | The options for opening the stream. |

### Return Value

The opened storage.

## Remarks

The PST is opened for writing only if `PersonalStorageLoadOptions.Writable` is `true`, which is not the default.

### See Also

* class [PersonalStorageLoadOptions](../../personalstorageloadoptions/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromStream(Stream) {#fromstream}

Opens a PST or OST from a stream for reading and writing.

```csharp
public static PersonalStorage FromStream(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream with the PST or OST data. |

### Return Value

The opened storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |

## Remarks

The stream is closed when the storage is disposed. To keep it open, use the overload with [`PersonalStorageLoadOptions`](../../personalstorageloadoptions/) and set its `LeaveStreamOpen` property.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


