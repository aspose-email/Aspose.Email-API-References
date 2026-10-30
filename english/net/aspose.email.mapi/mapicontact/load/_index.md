---
title: MapiContact.Load
second_title: Aspose.Email for .NET API Reference
description: MapiContact method. Loads a MapiContact from the specified file
type: docs
weight: 30
url: /net/aspose.email.mapi/mapicontact/load/
---
## Load(string) {#load_1}

Loads a [`MapiContact`](../) from the specified file.

```csharp
public static MapiContact Load(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path to the file to be loaded. |

### Return Value

Returns a [`MapiContact`](../) instance loaded from the specified file.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty`. |
| FileNotFoundException | The specified file does not exist. |
| InvalidOperationException | The file holds neither a contact item nor a vCard. |

## Remarks

Accepts both formats [`Save`](../save/) can produce: an Outlook MSG file holding a contact item, and a vCard file (read as [`FromVCard`](../fromvcard/) would). This makes `MapiContact.Load(path)` the inverse of `contact.Save(path)`, which writes vCard by default.

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Loads a [`MapiContact`](../) from the specified stream.

```csharp
public static MapiContact Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to be loaded. |

### Return Value

Returns a [`MapiContact`](../) instance loaded from the specified stream.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |
| InvalidOperationException | The stream holds neither a contact item nor a vCard. |

## Remarks

Accepts both formats [`Save`](../save/) can produce: an Outlook MSG file holding a contact item, and a vCard file (read as [`FromVCard`](../fromvcard/) would). This makes `MapiContact.Load(path)` the inverse of `contact.Save(path)`, which writes vCard by default.

The stream is read from its beginning, whatever its current position.

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)


