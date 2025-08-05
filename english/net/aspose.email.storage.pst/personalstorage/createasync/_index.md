---
title: PersonalStorage.CreateAsync
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Creates the new PST file with the specified file name
type: docs
weight: 410
url: /net/aspose.email.storage.pst/personalstorage/createasync/
---
## CreateAsync(string, FileFormatVersion, CancellationToken) {#createasync_2}

Creates the new PST file with the specified file name.

```csharp
public static Task<PersonalStorage> CreateAsync(string fileName, FileFormatVersion version, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The full name of the file. |
| version | FileFormatVersion | The PST file version. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

A PersonalStorage object that represents the new PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws if ANSI file version is created |
| ArgumentNullException | throws if file name is null or empty |

## Remarks

Note, only Unicode file version creation is supported now.

### See Also

* enum [FileFormatVersion](../../fileformatversion/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## CreateAsync(Stream, FileFormatVersion, CancellationToken) {#createasync_1}

Creates the PST in a stream.

```csharp
public static Task<PersonalStorage> CreateAsync(Stream stream, FileFormatVersion version, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream in which PST is created. |
| version | FileFormatVersion | The PST file version. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

A PersonalStorage object that represents the new PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws if ANSI file version is created |
| ArgumentNullException | throws if file name is null or empty |

## Remarks

Note, only Unicode file version creation is supported now.

### See Also

* enum [FileFormatVersion](../../fileformatversion/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## CreateAsync(Stream, FileFormatVersion, bool, CancellationToken) {#createasync}

Creates the PST in a stream.

```csharp
public static Task<PersonalStorage> CreateAsync(Stream stream, FileFormatVersion version, 
    bool leaveStreamOpen, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream in which PST is created. |
| version | FileFormatVersion | The PST file version. |
| leaveStreamOpen | Boolean | Leave stream open when PersonalStorage is disposed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

A PersonalStorage object that represents the new PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws if ANSI file version is created |
| ArgumentNullException | throws if file name is null or empty |

## Remarks

Note, only Unicode file version creation is supported now.

### See Also

* enum [FileFormatVersion](../../fileformatversion/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


