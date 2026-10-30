---
title: MapiCalendar.LoadAsync
second_title: Aspose.Email for .NET API Reference
description: MapiCalendar method. Loads a MapiCalendar from the specified file asynchronously
type: docs
weight: 300
url: /net/aspose.email.mapi/mapicalendar/loadasync/
---
## LoadAsync(string, CancellationToken) {#loadasync_1}

Loads a [`MapiCalendar`](../) from the specified file asynchronously.

```csharp
public static Task<MapiCalendar> LoadAsync(string filePath, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to be loaded. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiCalendar`](../) instance loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| FileNotFoundException | The specified file does not exist. |

### See Also

* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)

---

## LoadAsync(Stream, CancellationToken) {#loadasync}

Loads a [`MapiCalendar`](../) from the specified stream asynchronously.

```csharp
public static Task<MapiCalendar> LoadAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to be loaded. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiCalendar`](../) instance loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| InvalidOperationException | The stream does not contain a calendar item. |

### See Also

* class [MapiCalendar](../)
* namespace [Aspose.Email.Mapi](../../mapicalendar/)
* assembly [Aspose.Email](../../../)


