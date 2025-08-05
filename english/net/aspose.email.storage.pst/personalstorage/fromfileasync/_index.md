---
title: PersonalStorage.FromFileAsync
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Load PST from file
type: docs
weight: 420
url: /net/aspose.email.storage.pst/personalstorage/fromfileasync/
---
## FromFileAsync(string, CancellationToken) {#fromfileasync_2}

Load PST from file.

```csharp
public static Task<PersonalStorage> FromFileAsync(string fileName, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Name of .pst file. |
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

## FromFileAsync(string, bool, CancellationToken) {#fromfileasync_1}

```csharp
public static Task<PersonalStorage> FromFileAsync(string fileName, bool writable, 
    CancellationToken token = default)
```

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromFileAsync(string, PersonalStorageLoadOptions, CancellationToken) {#fromfileasync}

Load PST from file.

```csharp
public static Task<PersonalStorage> FromFileAsync(string fileName, 
    PersonalStorageLoadOptions loadOptions, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Name of .pst file. |
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


