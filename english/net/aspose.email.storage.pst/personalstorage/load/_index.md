---
title: PersonalStorage.Load
second_title: Aspose.Email for .NET API Reference
description: PersonalStorage method. Load PST from file. This method is used when a PersonalStorage object is created using the constructor
type: docs
weight: 300
url: /net/aspose.email.storage.pst/personalstorage/load/
---
## Load(string) {#load_1}

Load PST from file. This method is used when a PersonalStorage object is created using the constructor.

```csharp
public bool Load(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The name of .pst file. |

### Return Value

'true' if the file has been loaded successfully and further traversal is possible; otherwise, false.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | fileName - File name can not be null or empty |

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Load PST from stream. This method is used when a PersonalStorage object is created using the constructor.

```csharp
public bool Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The System.IO.Stream. |

### Return Value

'true' if the file has been loaded successfully and further traversal is possible; otherwise, false.

### See Also

* class [PersonalStorage](../)
* namespace [Aspose.Email.Storage.Pst](../../personalstorage/)
* assembly [Aspose.Email](../../../)


