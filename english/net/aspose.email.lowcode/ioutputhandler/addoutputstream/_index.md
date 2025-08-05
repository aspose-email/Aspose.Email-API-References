---
title: IOutputHandler.AddOutputStream
second_title: Aspose.Email for .NET API Reference
description: IOutputHandler method. Adds a named output stream using an asynchronous write action
type: docs
weight: 10
url: /net/aspose.email.lowcode/ioutputhandler/addoutputstream/
---
## AddOutputStream(string, Func&lt;Stream, Task&gt;) {#addoutputstream}

Adds a named output stream using an asynchronous write action.

```csharp
public Task AddOutputStream(string name, Func<Stream, Task> writeAction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the output stream (e.g. file name). |
| writeAction | Func`2 | An asynchronous function that writes to the provided stream. |

### Return Value

A task representing the asynchronous operation.

### See Also

* interface [IOutputHandler](../)
* namespace [Aspose.Email.LowCode](../../ioutputhandler/)
* assembly [Aspose.Email](../../../)

---

## AddOutputStream(string, Action&lt;Stream&gt;) {#addoutputstream_1}

Adds a named output stream using a synchronous write action.

```csharp
public void AddOutputStream(string name, Action<Stream> writeAction)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | The name of the output stream (e.g. file name). |
| writeAction | Action`1 | A synchronous action that writes to the provided stream. |

### See Also

* interface [IOutputHandler](../)
* namespace [Aspose.Email.LowCode](../../ioutputhandler/)
* assembly [Aspose.Email](../../../)


