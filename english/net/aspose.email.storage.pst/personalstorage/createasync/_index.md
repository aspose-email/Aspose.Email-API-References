---
title: PersonalStorage.CreateAsync
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Asynchronously creates a new PST file
type: docs
weight: 420
url: /net/aspose.email.storage.pst/personalstorage/createasync/
---
## CreateAsync(string, FileFormatVersion, CancellationToken) {#createasync_2}

Asynchronously creates a new PST file.

```csharp
public static Task<PersonalStorage> CreateAsync(string fileName, FileFormatVersion version, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file to create. The file must not exist. |
| version | FileFormatVersion | The version of the PST. Only `FileFormatVersion.Unicode` is supported. |
| token | CancellationToken | A token to cancel the operation. |

### Return Value

A task whose result is the new PST, open for writing.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | *version* is `FileFormatVersion.ANSI`. |
| ArgumentNullException | *fileName* is `null` or empty. |
| IOException | A file named *fileName* already exists. |

## Remarks

Only Unicode PST files can be created.

### See Also

* enum [FileFormatVersion](../../fileformatversion/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## CreateAsync(Stream, FileFormatVersion, CancellationToken) {#createasync_1}

Asynchronously creates a new PST in a stream.

```csharp
public static Task<PersonalStorage> CreateAsync(Stream stream, FileFormatVersion version, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write the PST to. |
| version | FileFormatVersion | The version of the PST. Only `FileFormatVersion.Unicode` is supported. |
| token | CancellationToken | A token to cancel the operation. |

### Return Value

A task whose result is the new PST, open for writing.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | *version* is `FileFormatVersion.ANSI`. |
| ArgumentNullException | *stream* is `null`. |

## Remarks

Only Unicode PST files can be created. The stream is closed when the storage is disposed. Use the overload with leaveStreamOpen to keep it open.

### See Also

* enum [FileFormatVersion](../../fileformatversion/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## CreateAsync(Stream, FileFormatVersion, bool, CancellationToken) {#createasync}

Asynchronously creates a new PST in a stream.

```csharp
public static Task<PersonalStorage> CreateAsync(Stream stream, FileFormatVersion version, 
    bool leaveStreamOpen, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write the PST to. |
| version | FileFormatVersion | The version of the PST. Only `FileFormatVersion.Unicode` is supported. |
| leaveStreamOpen | Boolean | `true` to leave *stream* open when the storage is disposed. |
| token | CancellationToken | A token to cancel the operation. |

### Return Value

A task whose result is the new PST, open for writing.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | *version* is `FileFormatVersion.ANSI`. |
| ArgumentNullException | *stream* is `null`. |

## Remarks

Only Unicode PST files can be created.

### See Also

* enum [FileFormatVersion](../../fileformatversion/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


