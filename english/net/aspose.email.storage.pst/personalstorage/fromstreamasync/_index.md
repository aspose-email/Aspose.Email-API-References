---
title: PersonalStorage.FromStreamAsync
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Asynchronously opens a PST or OST from a stream for reading and writing
type: docs
weight: 440
url: /net/aspose.email.storage.pst/personalstorage/fromstreamasync/
---
## FromStreamAsync(Stream, CancellationToken) {#fromstreamasync_2}

Asynchronously opens a PST or OST from a stream for reading and writing.

```csharp
public static Task<PersonalStorage> FromStreamAsync(Stream stream, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream with the PST or OST data. |
| token | CancellationToken | A token to cancel the operation. |

### Return Value

A task whose result is the opened storage.

## Remarks

The stream is closed when the storage is disposed. To keep it open, use the overload with [`PersonalStorageLoadOptions`](../../personalstorageloadoptions/) and set its `LeaveStreamOpen` property.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromStreamAsync(Stream, bool, CancellationToken) {#fromstreamasync_1}

Asynchronously opens a PST or OST from a stream.

```csharp
public static Task<PersonalStorage> FromStreamAsync(Stream stream, bool writable, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream with the PST or OST data. |
| writable | Boolean | `true` to open the PST for reading and writing; `false` for reading only. |
| token | CancellationToken | A token to cancel the operation. |

### Return Value

A task whose result is the opened storage.

## Remarks

The stream is closed when the storage is disposed. To keep it open, use the overload with [`PersonalStorageLoadOptions`](../../personalstorageloadoptions/) and set its `LeaveStreamOpen` property.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromStreamAsync(Stream, PersonalStorageLoadOptions, CancellationToken) {#fromstreamasync}

Asynchronously opens a PST or OST from a stream with the specified options.

```csharp
public static Task<PersonalStorage> FromStreamAsync(Stream stream, 
    PersonalStorageLoadOptions loadOptions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream with the PST or OST data. |
| loadOptions | PersonalStorageLoadOptions | The options for opening the stream. |
| token | CancellationToken | A token to cancel the operation. |

### Return Value

A task whose result is the opened storage.

## Remarks

The PST is opened for writing only if `PersonalStorageLoadOptions.Writable` is `true`, which is not the default.

### See Also

* class [PersonalStorageLoadOptions](../../personalstorageloadoptions/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


