---
title: PersonalStorage.Create
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Creates the new PST file with the specified file name
type: docs
weight: 20
url: /net/aspose.email.storage.pst/personalstorage/create/
---
## Create(string, FileFormatVersion) {#create_2}

Creates the new PST file with the specified file name.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The full name of the file. |
| version | FileFormatVersion | The PST file version. |

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

## Create(Stream, FileFormatVersion) {#create}

Creates the PST in a stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream in which PST is created. |
| version | FileFormatVersion | The PST file version. |

### Return Value

A PersonalStorage object that represents the new PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws if ANSI file version is created |
| ArgumentNullException | throws if stream is null |

## Remarks

Note, only Unicode file version creation is supported now.

### See Also

* enum [FileFormatVersion](../../fileformatversion/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## Create(Stream, FileFormatVersion, bool) {#create_1}

Creates the PST in a stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, bool leaveStreamOpen)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream in which PST is created. |
| version | FileFormatVersion | The PST file version. |
| leaveStreamOpen | Boolean | Leave stream open when PersonalStorage is disposed. |

### Return Value

A PersonalStorage object that represents the new PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws if ANSI file version is created |
| ArgumentNullException | throws if stream is null |

## Remarks

Note, only Unicode file version creation is supported now.

### See Also

* enum [FileFormatVersion](../../fileformatversion/)
* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


