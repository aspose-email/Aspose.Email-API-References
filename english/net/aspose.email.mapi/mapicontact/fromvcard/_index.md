---
title: MapiContact.FromVCard
second_title: Aspose.Email for .NET API Reference
description: MapiContact method. Loads a contact from a vCard file. vCard versions 2.1 and 3.0 are supported
type: docs
weight: 20
url: /net/aspose.email.mapi/mapicontact/fromvcard/
---
## FromVCard(string) {#fromvcard_3}

Loads a contact from a vCard file. vCard versions 2.1 and 3.0 are supported.

```csharp
public static MapiContact FromVCard(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the vCard file. |

### Return Value

The loaded contact.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## FromVCard(string, VCardLoadOptions) {#fromvcard_4}

Loads a contact from a vCard file. vCard versions 2.1 and 3.0 are supported.

```csharp
public static MapiContact FromVCard(string filePath, VCardLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the vCard file. |
| options | VCardLoadOptions | Options for loading the vCard. |

### Return Value

The loaded contact.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |

### See Also

* class [VCardLoadOptions](../../../aspose.email.personalinfo.vcard/vcardloadoptions/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## FromVCard(Stream) {#fromvcard}

Loads a contact from a stream that contains a vCard. vCard versions 2.1 and 3.0 are supported.

```csharp
public static MapiContact FromVCard(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read. |

### Return Value

The loaded contact.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## FromVCard(Stream, VCardLoadOptions) {#fromvcard_1}

Loads a contact from a stream that contains a vCard. vCard versions 2.1 and 3.0 are supported.

```csharp
public static MapiContact FromVCard(Stream stream, VCardLoadOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to read. |
| options | VCardLoadOptions | Options for loading the vCard. |

### Return Value

The loaded contact.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support reading. |

### See Also

* class [VCardLoadOptions](../../../aspose.email.personalinfo.vcard/vcardloadoptions/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)


