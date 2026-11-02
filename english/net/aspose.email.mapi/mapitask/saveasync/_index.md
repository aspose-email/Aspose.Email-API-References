---
title: MapiTask.SaveAsync
second_title: Aspose.Email for .NET API Reference
description: MapiTask method. Saves this MapiTask to the given stream using specified format asynchronously. The supported save format is MSG
type: docs
weight: 260
url: /net/aspose.email.mapi/mapitask/saveasync/
---
## SaveAsync(Stream, TaskSaveFormat, CancellationToken) {#saveasync}

Saves this [`MapiTask`](../) to the given stream using specified format asynchronously. The supported save format is MSG.

```csharp
public Task SaveAsync(Stream stream, TaskSaveFormat saveFormat, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to. |
| saveFormat | TaskSaveFormat | A save format. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |
| NotSupportedException | The specified format is not supported. |

### See Also

* enum [TaskSaveFormat](../../tasksaveformat/)
* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(string, TaskSaveFormat, CancellationToken) {#saveasync_2}

Saves this [`MapiTask`](../) into file using specified format asynchronously. The supported save format is MSG.

```csharp
public Task SaveAsync(string filePath, TaskSaveFormat saveFormat, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name. |
| saveFormat | TaskSaveFormat | A save format. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| NotSupportedException | some save option is not supported |

### See Also

* enum [TaskSaveFormat](../../tasksaveformat/)
* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(Stream, CancellationToken) {#saveasync_1}

Saves this [`MapiTask`](../) to the given stream asynchronously. The supported save format is MSG.

```csharp
public Task SaveAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |

### See Also

* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(string, CancellationToken) {#saveasync_3}

Saves this [`MapiTask`](../) into file asynchronously. The supported save format is MSG.

```csharp
public Task SaveAsync(string filePath, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |

### See Also

* class [MapiTask](../)
* namespace [Aspose.Email.Mapi](../../mapitask/)
* assembly [Aspose.Email](../../../)


