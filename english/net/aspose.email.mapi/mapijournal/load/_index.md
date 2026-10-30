---
title: MapiJournal.Load
second_title: Aspose.Email for .NET API Reference
description: MapiJournal method. Loads a MapiJournal from the specified file
type: docs
weight: 20
url: /net/aspose.email.mapi/mapijournal/load/
---
## Load(string) {#load_1}

Loads a [`MapiJournal`](../) from the specified file.

```csharp
public static MapiJournal Load(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to be loaded. |

### Return Value

Returns a [`MapiJournal`](../) instance loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| FileNotFoundException | The specified file does not exist. |
| InvalidOperationException | The file does not contain a journal item. |

### See Also

* class [MapiJournal](../)
* namespace [Aspose.Email.Mapi](../../mapijournal/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Loads a [`MapiJournal`](../) from the specified stream.

```csharp
public static MapiJournal Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to be loaded. |

### Return Value

Returns a [`MapiJournal`](../) instance loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| InvalidOperationException | The stream does not contain a journal item. |

### See Also

* class [MapiJournal](../)
* namespace [Aspose.Email.Mapi](../../mapijournal/)
* assembly [Aspose.Email](../../../)


