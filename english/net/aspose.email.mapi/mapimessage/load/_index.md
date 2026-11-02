---
title: MapiMessage.Load
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Loads a message from a file
type: docs
weight: 40
url: /net/aspose.email.mapi/mapimessage/load/
---
## Load(string) {#load_2}

Loads a message from a file.

```csharp
public static MapiMessage Load(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *fileName* is `null` or empty. |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception/) | The data is not in a supported message format. |
| NotSupportedException | The stream does not support reading. |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Loads a message from a stream.

```csharp
public static MapiMessage Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception/) | The data is not in a supported message format. |
| NotSupportedException | The stream does not support reading. |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Loads a message from a stream with the specified options.

```csharp
public static MapiMessage Load(Stream stream, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read. |
| options | LoadOptions | The options of loading. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception/) | The data is not in a supported message format. |
| NotSupportedException | The stream does not support reading. |

### See Also

* class [LoadOptions](../../../aspose.email/loadoptions/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## Load(string, LoadOptions) {#load_3}

Loads a message from a file with the specified options.

```csharp
public static MapiMessage Load(string fileName, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |
| options | LoadOptions | The options of loading. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *fileName* is `null` or empty. |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception/) | The data is not in a supported message format. |
| NotSupportedException | The stream does not support reading. |

### See Also

* class [LoadOptions](../../../aspose.email/loadoptions/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


