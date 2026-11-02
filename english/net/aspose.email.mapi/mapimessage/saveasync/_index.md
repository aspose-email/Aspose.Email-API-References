---
title: MapiMessage.SaveAsync
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Saves this MapiMessage to the specified file asynchronously
type: docs
weight: 420
url: /net/aspose.email.mapi/mapimessage/saveasync/
---
## SaveAsync(string, CancellationToken) {#saveasync_3}

Saves this [`MapiMessage`](../) to the specified file asynchronously.

```csharp
public Task SaveAsync(string fileName, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The name of the file to save the message to. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *fileName* is `null` or `empty`. |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(string, SaveOptions, CancellationToken) {#saveasync_2}

Saves this [`MapiMessage`](../) to the specified file with specified options asynchronously.

```csharp
public Task SaveAsync(string fileName, SaveOptions options, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The name of the file to save the message to. |
| options | SaveOptions | Options for saving message. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *fileName* is `null` or `empty`. |
| ArgumentNullException | *options* is `null`. |

### See Also

* class [SaveOptions](../../../aspose.email/saveoptions/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(Stream, CancellationToken) {#saveasync_1}

Saves this [`MapiMessage`](../) to the specified stream asynchronously.

```csharp
public Task SaveAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to save the message to. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(Stream, SaveOptions, CancellationToken) {#saveasync}

Saves this [`MapiMessage`](../) to the specified stream with specified options asynchronously.

```csharp
public Task SaveAsync(Stream stream, SaveOptions options, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to save the message to. |
| options | SaveOptions | Options for saving message. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |
| ArgumentNullException | *options* is `null`. |

### See Also

* class [SaveOptions](../../../aspose.email/saveoptions/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


