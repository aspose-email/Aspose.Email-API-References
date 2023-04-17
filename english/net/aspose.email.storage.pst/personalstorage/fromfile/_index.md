---
title: PersonalStorage.FromFile
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Load PST from file
type: docs
weight: 30
url: /net/aspose.email.storage.pst/personalstorage/fromfile/
---
## FromFile(string) {#fromfile}

Load PST from file.

```csharp
public static PersonalStorage FromFile(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Name of .pst file. |

### Return Value

A PersonalStorage object that represents the current PST.

## Remarks

By default, the pst will support writing.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromFile(string, bool) {#fromfile_3}

Load PST from file.

```csharp
public static PersonalStorage FromFile(string fileName, bool writable)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Name of .pst file. |
| writable | Boolean | if set to `true` then the the pst file will support writing, otherwise it will be opened in read-only mode. |

### Return Value

A PersonalStorage object that represents the current PST.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromFile(string, PersonalStorageLoadOptions) {#fromfile_1}

Load PST from file.

```csharp
public static PersonalStorage FromFile(string fileName, PersonalStorageLoadOptions loadOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Name of .pst file. |
| loadOptions | PersonalStorageLoadOptions | The load options. |

### Return Value

A PersonalStorage object that represents the current PST.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | fileName - File name can not be null or empty |
| ArgumentException | PersonalStorageLoadOptions.LeaveStreamOpen can not be true. |

### See Also

* class [PersonalStorageLoadOptions](../../personalstorageloadoptions/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromFile(string, CancellationToken) {#fromfile_5}

Load PST from file.

```csharp
public static PersonalStorage FromFile(string fileName, CancellationToken token)
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

## FromFile(string, bool, CancellationToken) {#fromfile_4}

```csharp
public static PersonalStorage FromFile(string fileName, bool writable, CancellationToken token)
```

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## FromFile(string, PersonalStorageLoadOptions, CancellationToken) {#fromfile_2}

Load PST from file.

```csharp
public static PersonalStorage FromFile(string fileName, PersonalStorageLoadOptions loadOptions, 
    CancellationToken token)
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


