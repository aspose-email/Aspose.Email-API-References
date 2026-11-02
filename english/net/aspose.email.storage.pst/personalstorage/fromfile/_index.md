---
title: PersonalStorage.FromFile
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Opens a PST or OST file for reading and writing
type: docs
weight: 30
url: /net/aspose.email.storage.pst/personalstorage/fromfile/
---
## FromFile(string) {#fromfile}

Opens a PST or OST file for reading and writing.

```csharp
public static PersonalStorage FromFile(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |

### Return Value

The opened storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *fileName* is `null` or empty. |

## Remarks

Opening for writing needs write access to the file. To read a file that is read-only or in use, use the overload with writable and pass `false`.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromFile(string, bool) {#fromfile_2}

Opens a PST or OST file.

```csharp
public static PersonalStorage FromFile(string fileName, bool writable)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |
| writable | Boolean | `true` to open the file for reading and writing; `false` to open it for reading only. |

### Return Value

The opened storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *fileName* is `null` or empty. |

## Remarks

Opening for writing needs write access to the file. To read a file that is read-only or in use, open it with *writable* set to `false`.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromFile(string, PersonalStorageLoadOptions) {#fromfile_1}

Opens a PST or OST file with the specified options.

```csharp
public static PersonalStorage FromFile(string fileName, PersonalStorageLoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |
| loadOptions | PersonalStorageLoadOptions | The options for opening the file. |

### Return Value

The opened storage.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *fileName* is `null` or empty. |
| ArgumentException | `LeaveStreamOpen` of *loadOptions* is `true`; it must be `false` when opening a file. |

## Remarks

The file is opened for writing only if `PersonalStorageLoadOptions.Writable` is `true`, which is not the default.

### See Also

* class [PersonalStorageLoadOptions](../../personalstorageloadoptions/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


