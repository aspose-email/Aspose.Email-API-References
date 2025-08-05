---
title: VCardContact.LoadAsync
second_title: Aspose.Email for .NET API Reference
description: VCardContact method. Reads VCardContact from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0
type: docs
weight: 190
url: /net/aspose.email.personalinfo.vcard/vcardcontact/loadasync/
---
## LoadAsync(Stream, CancellationToken) {#loadasync_1}

Reads [`VCardContact`](../) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

```csharp
public static Task<VCardContact> LoadAsync(Stream stream, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to read from |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

A read [`VCardContact`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support reading |

### See Also

* class [VCardContact](../)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact/)
* assembly [Aspose.Email](../../../)

---

## LoadAsync(string, CancellationToken) {#loadasync_3}

Reads [`VCardContact`](../) from the specified vCard file The supported vCard versions are 2.1 and 3.0

```csharp
public static Task<VCardContact> LoadAsync(string filePath, CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name to read from |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

A read [`VCardContact`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |

### See Also

* class [VCardContact](../)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact/)
* assembly [Aspose.Email](../../../)

---

## LoadAsync(Stream, VCardLoadOptions, CancellationToken) {#loadasync}

Reads [`VCardContact`](../) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

```csharp
public static Task<VCardContact> LoadAsync(Stream stream, VCardLoadOptions options, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to read from |
| options | VCardLoadOptions | Additional options when loading a VCardContact list |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Return Value

A read [`VCardContact`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support reading |

### See Also

* class [VCardLoadOptions](../../vcardloadoptions/)
* class [VCardContact](../)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact/)
* assembly [Aspose.Email](../../../)

---

## LoadAsync(string, VCardLoadOptions, CancellationToken) {#loadasync_2}

Reads [`VCardContact`](../) from the specified vCard file The supported vCard versions are 2.1 and 3.0

```csharp
public static Task<VCardContact> LoadAsync(string filePath, VCardLoadOptions options, 
    CancellationToken token)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name to read from |
| token | VCardLoadOptions | Propagates notification that operations should be canceled. |
| options | CancellationToken | Additional options when loading a VCardContact list |

### Return Value

A read [`VCardContact`](../)

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |

### See Also

* class [VCardLoadOptions](../../vcardloadoptions/)
* class [VCardContact](../)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact/)
* assembly [Aspose.Email](../../../)


