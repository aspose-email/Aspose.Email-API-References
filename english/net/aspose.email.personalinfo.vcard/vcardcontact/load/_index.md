---
title: VCardContact.Load
second_title: Aspose.Email for .NET API Reference
description: VCardContact method. Reads VCardContact from the specified vCard file The supported vCard versions are 2.1 and 3.0
type: docs
weight: 20
url: /net/aspose.email.personalinfo.vcard/vcardcontact/load/
---
## Load(string) {#load_3}

Reads [`VCardContact`](../) from the specified vCard file The supported vCard versions are 2.1 and 3.0

```csharp
public static VCardContact Load(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A file name to read from |

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

## Load(string, VCardLoadOptions) {#load_4}

Reads [`VCardContact`](../) from the specified vCard file The supported vCard versions are 2.1 and 3.0

```csharp
public static VCardContact Load(string filePath, VCardLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | Source file |
| options | VCardLoadOptions | Additional options when loading a VCardContact |

### Return Value

List of contacts

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Throws if filePath is null or empty |

### See Also

* class [VCardLoadOptions](../../vcardloadoptions/)
* class [VCardContact](../)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact/)
* assembly [Aspose.Email](../../../)

---

## Load(Stream) {#load}

Reads [`VCardContact`](../) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

```csharp
public static VCardContact Load(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to read from |

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

## Load(Stream, VCardLoadOptions) {#load_1}

Reads [`VCardContact`](../) from the specified stream containing vCard. The supported vCard versions are 2.1 and 3.0

```csharp
public static VCardContact Load(Stream stream, VCardLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to read from |
| options | VCardLoadOptions | Additional options when loading a VCardContact |

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


