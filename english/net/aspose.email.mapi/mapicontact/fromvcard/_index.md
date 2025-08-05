---
title: MapiContact.FromVCard
second_title: Aspose.Email for .NET API Reference
description: MapiContact method. Reads MapiContact from the specified vCard file The supported vCard versions are 2.1 and 3.0
type: docs
weight: 20
url: /net/aspose.email.mapi/mapicontact/fromvcard/
---
## FromVCard(string) {#fromvcard_3}

Reads [`MapiContact`](../) from the specified vCard file The supported vCard versions are 2.1 and 3.0

```csharp
public static MapiContact FromVCard(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name to read from |

### Return Value

A read [`MapiContact`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## FromVCard(string, VCardLoadOptions) {#fromvcard_4}

Reads [`MapiContact`](../) from the specified vCard file The supported vCard versions are 2.1 and 3.0

```csharp
public static MapiContact FromVCard(string filePath, VCardLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name to read from |
| options | VCardLoadOptions | Additional options when loading a VCardContact |

### Return Value

A read [`MapiContact`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |

### See Also

* class [VCardLoadOptions](../../../aspose.email.personalinfo.vcard/vcardloadoptions/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## FromVCard(Stream) {#fromvcard}

Reads [`MapiContact`](../) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

```csharp
public static MapiContact FromVCard(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to read from |

### Return Value

A read [`MapiContact`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support reading |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## FromVCard(Stream, VCardLoadOptions) {#fromvcard_1}

Reads [`MapiContact`](../) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

```csharp
public static MapiContact FromVCard(Stream stream, VCardLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to read from |
| options | VCardLoadOptions | Additional options when loading a VCardContact |

### Return Value

A read [`MapiContact`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support reading |

### See Also

* class [VCardLoadOptions](../../../aspose.email.personalinfo.vcard/vcardloadoptions/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)


