---
title: Create
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 20
url: /net/aspose.email.storage.pst/personalstorage/create/
---
## PersonalStorage.Create method (1 of 6)

Creates the new PST file with the specified file name.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The full name of the file. |
| version | FileFormatVersion | The PST file version. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

A PersonalStorage object that represents the new PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws if ANSI file version is created |
| ArgumentNullException | throws if file name is null or empty |

### Remarks

Note, only Unicode file version creation is supported now.

### See Also

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage)
* assembly [Aspose.Email](../../../)

---

## PersonalStorage.Create method (2 of 6)

Creates the PST in a stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream in which PST is created. |
| version | FileFormatVersion | The PST file version. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

A PersonalStorage object that represents the new PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws if ANSI file version is created |
| ArgumentNullException | throws if file name is null or empty |

### Remarks

Note, only Unicode file version creation is supported now.

### See Also

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage)
* assembly [Aspose.Email](../../../)

---

## PersonalStorage.Create method (3 of 6)

Creates the PST in a stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, 
    bool leaveStreamOpen, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream in which PST is created. |
| version | FileFormatVersion | The PST file version. |
| leaveStreamOpen | Boolean | Leave stream open when PersonalStorage is disposed. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

## Return Value

A PersonalStorage object that represents the new PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws if ANSI file version is created |
| ArgumentNullException | throws if file name is null or empty |

### Remarks

Note, only Unicode file version creation is supported now.

### See Also

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage)
* assembly [Aspose.Email](../../../)

---

## PersonalStorage.Create method (4 of 6)

Creates the new PST file with the specified file name.

```csharp
public static PersonalStorage Create(string fileName, FileFormatVersion version)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The full name of the file. |
| version | FileFormatVersion | The PST file version. |

## Return Value

A PersonalStorage object that represents the new PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws if ANSI file version is created |
| ArgumentNullException | throws if file name is null or empty |

### Remarks

Note, only Unicode file version creation is supported now.

### See Also

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage)
* assembly [Aspose.Email](../../../)

---

## PersonalStorage.Create method (5 of 6)

Creates the PST in a stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream in which PST is created. |
| version | FileFormatVersion | The PST file version. |

## Return Value

A PersonalStorage object that represents the new PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws if ANSI file version is created |
| ArgumentNullException | throws if stream is null |

### Remarks

Note, only Unicode file version creation is supported now.

### See Also

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage)
* assembly [Aspose.Email](../../../)

---

## PersonalStorage.Create method (6 of 6)

Creates the PST in a stream.

```csharp
public static PersonalStorage Create(Stream stream, FileFormatVersion version, bool leaveStreamOpen)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream in which PST is created. |
| version | FileFormatVersion | The PST file version. |
| leaveStreamOpen | Boolean | Leave stream open when PersonalStorage is disposed. |

## Return Value

A PersonalStorage object that represents the new PST.

### Exceptions

| exception | condition |
| --- | --- |
| NotImplementedException | throws if ANSI file version is created |
| ArgumentNullException | throws if stream is null |

### Remarks

Note, only Unicode file version creation is supported now.

### See Also

* enum [FileFormatVersion](../../fileformatversion)
* class [PersonalStorage](../../personalstorage)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
