---
title: MapiMessage.LoadAsync
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Loads a MapiMessage from the specified file asynchronously
type: docs
weight: 480
url: /net/aspose.email.mapi/mapimessage/loadasync/
---
## LoadAsync(string, CancellationToken) {#loadasync_3}

Loads a [`MapiMessage`](../) from the specified file asynchronously.

```csharp
public static Task<MapiMessage> LoadAsync(string fileName, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The name of the file to load the message from. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiMessage`](../) instance loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *fileName* is `null` or `empty`. |
| FileNotFoundException | The specified file does not exist. |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## LoadAsync(Stream, CancellationToken) {#loadasync_1}

Loads a [`MapiMessage`](../) from the specified stream asynchronously.

```csharp
public static Task<MapiMessage> LoadAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load the message from. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiMessage`](../) instance loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## LoadAsync(string, LoadOptions, CancellationToken) {#loadasync_2}

Loads a [`MapiMessage`](../) from the specified file with specified options asynchronously.

```csharp
public static Task<MapiMessage> LoadAsync(string fileName, LoadOptions options, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The name of the file to load the message from. |
| options | LoadOptions | Options for loading message. If `null`, the format is detected from the data: an MSG is loaded with [`MsgLoadOptions`](../../../aspose.email/msgloadoptions/), anything else with [`EmlLoadOptions`](../../../aspose.email/emlloadoptions/). |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiMessage`](../) instance loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *fileName* is `null` or `empty`. |
| FileNotFoundException | The specified file does not exist. |

### See Also

* class [LoadOptions](../../../aspose.email/loadoptions/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## LoadAsync(Stream, LoadOptions, CancellationToken) {#loadasync}

Loads a [`MapiMessage`](../) from the specified stream with specified options asynchronously.

```csharp
public static Task<MapiMessage> LoadAsync(Stream stream, LoadOptions options, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to load the message from. |
| options | LoadOptions | Options for loading message. If `null`, the format is detected from the data: an MSG is loaded with [`MsgLoadOptions`](../../../aspose.email/msgloadoptions/), anything else with [`EmlLoadOptions`](../../../aspose.email/emlloadoptions/). |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

Returns a [`MapiMessage`](../) instance loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |

### See Also

* class [LoadOptions](../../../aspose.email/loadoptions/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


