---
title: MapiContact.FromVCardAsync
second_title: Aspose.Email for .NET API Reference
description: MapiContact method. Reads MapiContact from the specified vCard file asynchronously. The supported vCard versions are 2.1 and 3.0
type: docs
weight: 190
url: /net/aspose.email.mapi/mapicontact/fromvcardasync/
---
## FromVCardAsync(string, CancellationToken) {#fromvcardasync_5}

Reads [`MapiContact`](../) from the specified vCard file asynchronously. The supported vCard versions are 2.1 and 3.0

```csharp
public static Task<MapiContact> FromVCardAsync(string filePath, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name to read from |
| token | CancellationToken | Propagates notification that operations should be canceled. |

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

## FromVCardAsync(string, VCardLoadOptions, CancellationToken) {#fromvcardasync_3}

Reads [`MapiContact`](../) from the specified vCard file asynchronously. The supported vCard versions are 2.1 and 3.0

```csharp
public static Task<MapiContact> FromVCardAsync(string filePath, VCardLoadOptions options, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name to read from |
| options | VCardLoadOptions | Additional options when loading a VCardContact |
| token | CancellationToken | Propagates notification that operations should be canceled. |

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

## FromVCardAsync(Stream, CancellationToken) {#fromvcardasync_2}

Reads [`MapiContact`](../) from the specified stream containing vCard asynchronously. The supported vCard versions are 2.1 and 3.0

```csharp
public static Task<MapiContact> FromVCardAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to read from |
| token | CancellationToken | Propagates notification that operations should be canceled. |

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

## FromVCardAsync(Stream, VCardLoadOptions, CancellationToken) {#fromvcardasync}

Reads [`MapiContact`](../) from the specified stream containing vCard asynchronously. The supported vCard versions are 2.1 and 3.0

```csharp
public static Task<MapiContact> FromVCardAsync(Stream stream, VCardLoadOptions options, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to read from |
| options | VCardLoadOptions | Additional options when loading a VCardContact |
| token | CancellationToken | Propagates notification that operations should be canceled. |

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


