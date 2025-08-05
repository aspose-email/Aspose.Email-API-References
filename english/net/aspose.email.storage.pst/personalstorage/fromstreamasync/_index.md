---
title: PersonalStorage.FromStreamAsync
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Load PST from file
type: docs
weight: 430
url: /net/aspose.email.storage.pst/personalstorage/fromstreamasync/
---
## FromStreamAsync(Stream, CancellationToken) {#fromstreamasync_2}

Load PST from file.

```csharp
public static Task<PersonalStorage> FromStreamAsync(Stream stream, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The System.IO.Stream. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

A PersonalStorage object that represents the current PST.

## Remarks

By default, the pst will support writing.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromStreamAsync(Stream, bool, CancellationToken) {#fromstreamasync_1}

```csharp
public static Task<PersonalStorage> FromStreamAsync(Stream stream, bool writable, 
    CancellationToken token = default)
```

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromStreamAsync(Stream, PersonalStorageLoadOptions, CancellationToken) {#fromstreamasync}

Load PST from file.

```csharp
public static Task<PersonalStorage> FromStreamAsync(Stream stream, 
    PersonalStorageLoadOptions loadOptions, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The System.IO.Stream. |
| loadOptions | PersonalStorageLoadOptions | The load options. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

A PersonalStorage object that represents the current PST.

## Remarks

By default, the pst will support writing.

### See Also

* class [PersonalStorageLoadOptions](../../personalstorageloadoptions/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


