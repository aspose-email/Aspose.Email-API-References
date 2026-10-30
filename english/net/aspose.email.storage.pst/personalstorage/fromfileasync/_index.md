---
title: PersonalStorage.FromFileAsync
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Asynchronously opens a PST or OST file for reading and writing
type: docs
weight: 430
url: /net/aspose.email.storage.pst/personalstorage/fromfileasync/
---
## FromFileAsync(string, CancellationToken) {#fromfileasync_2}

Asynchronously opens a PST or OST file for reading and writing.

```csharp
public static Task<PersonalStorage> FromFileAsync(string fileName, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |
| token | CancellationToken | A token to cancel the operation. |

### Return Value

A task whose result is the opened storage.

## Remarks

Opening for writing needs write access to the file.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromFileAsync(string, bool, CancellationToken) {#fromfileasync_1}

Asynchronously opens a PST or OST file.

```csharp
public static Task<PersonalStorage> FromFileAsync(string fileName, bool writable, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |
| writable | Boolean | `true` to open the file for reading and writing; `false` to open it for reading only. |
| token | CancellationToken | A token to cancel the operation. |

### Return Value

A task whose result is the opened storage.

## Remarks

Opening for writing needs write access to the file. To read a file that is read-only or in use, open it with *writable* set to `false`.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromFileAsync(string, PersonalStorageLoadOptions, CancellationToken) {#fromfileasync}

Asynchronously opens a PST or OST file with the specified options.

```csharp
public static Task<PersonalStorage> FromFileAsync(string fileName, 
    PersonalStorageLoadOptions loadOptions, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |
| loadOptions | PersonalStorageLoadOptions | The options for opening the file. |
| token | CancellationToken | A token to cancel the operation. |

### Return Value

A task whose result is the opened storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | `LeaveStreamOpen` of *loadOptions* is `true`; it must be `false` when opening a file. |

## Remarks

The file is opened for writing only if `PersonalStorageLoadOptions.Writable` is `true`, which is not the default.

### See Also

* class [PersonalStorageLoadOptions](../../personalstorageloadoptions/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


