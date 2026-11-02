---
title: MapiMessage.LoadFromTnef
second_title: Aspose.Email for .NET API Reference
description: MapiMessage method. Loads a message from a stream in TNEF format the content of a winmail.dat attachment
type: docs
weight: 50
url: /net/aspose.email.mapi/mapimessage/loadfromtnef/
---
## LoadFromTnef(Stream) {#loadfromtnef}

Loads a message from a stream in TNEF format (the content of a winmail.dat attachment).

```csharp
public static MapiMessage LoadFromTnef(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read. |

### Return Value

The loaded message.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support reading |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)

---

## LoadFromTnef(string) {#loadfromtnef_1}

Loads a message from a file in TNEF format, such as winmail.dat.

```csharp
public static MapiMessage LoadFromTnef(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The path of the file. |

### Return Value

The loaded message.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *fileName* is `null` or empty. |

### See Also

* class [MapiMessage](../)
* namespace [Aspose.Email.Mapi](../../mapimessage/)
* assembly [Aspose.Email](../../../)


