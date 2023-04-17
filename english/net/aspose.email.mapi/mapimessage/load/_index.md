---
title: MapiMessage.Load
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Loads message from file
type: docs
weight: 40
url: /net/aspose.email.mapi/mapimessage/load/
---
## Load(string) {#load_2}

Loads message from file.

```csharp
public static MapiMessage Load(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Source file pathString. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | File name should not be null or empty. |
| NotSupportedException | Stream does not support reading. |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception/) | Passed message format is not supported. |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Loads message from stream.

```csharp
public static MapiMessage Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Source streamStream. |

### Exceptions

| exception | condition |
| --- | --- |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception/) | Passed message format is not supported. |
| ArgumentNullException | Stream should not be null or empty. |
| NotSupportedException | Stream does not support reading. |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Loads message from stream with additional options.

```csharp
public static MapiMessage Load(Stream stream, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | Source streamStream. |
| options | LoadOptions | Additional options [`LoadOptions`](../../../aspose.email/loadoptions/). |

### Exceptions

| exception | condition |
| --- | --- |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception/) | Passed message format is not supported. |
| ArgumentNullException | Stream should not be null or empty. |
| NotSupportedException | Stream does not support reading. |

### See Also

* class [LoadOptions](../../../aspose.email/loadoptions/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## Load(string, LoadOptions) {#load_3}

Loads message from file with additional options.

```csharp
public static MapiMessage Load(string fileName, LoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | Source file pathString. |
| options | LoadOptions | Additional options [`LoadOptions`](../../../aspose.email/loadoptions/). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | File name should not be null or empty. |
| NotSupportedException | Stream does not support reading. |
| [FormatNotSupportedException](../../../aspose.email/formatnotsupportedexception/) | Passed message format is not supported. |

### See Also

* class [LoadOptions](../../../aspose.email/loadoptions/)
* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


