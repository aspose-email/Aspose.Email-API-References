---
title: MapiContact.SaveAsync
second_title: Aspose.Email for .NET API Reference
description: MapiContact method. Saves this MapiContact to the vCard file with a default options asynchronously. The supported vCard version is 2.1
type: docs
weight: 170
url: /net/aspose.email.mapi/mapicontact/saveasync/
---
## SaveAsync(string, CancellationToken) {#saveasync_5}

Saves this [`MapiContact`](../) to the vCard file with a default options asynchronously. The supported vCard version is 2.1

```csharp
public Task SaveAsync(string filePath, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A vCard file name |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(string, ContactSaveFormat, CancellationToken) {#saveasync_3}

Saves this [`MapiContact`](../) to the specified file with a format using the default options asynchronously. The supported save format is vCard.

```csharp
public Task SaveAsync(string filePath, ContactSaveFormat saveFormat, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A vCard file name |
| saveFormat | ContactSaveFormat | A save format |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |
| NotSupportedException | the specified format is not supported |

### See Also

* enum [ContactSaveFormat](../../contactsaveformat/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(string, ContactSaveOptions, CancellationToken) {#saveasync_4}

Saves this [`MapiContact`](../) into file using specified save options asynchronously. The supported save options is [`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions/)

```csharp
public Task SaveAsync(string filePath, ContactSaveOptions saveOptions, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A vCard file name |
| saveOptions | ContactSaveOptions | A save options |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |
| ArgumentNullException | *saveOptions* is `null` |
| NotSupportedException | some save option is not supported |

### See Also

* class [ContactSaveOptions](../../contactsaveoptions/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(Stream, ContactSaveFormat, CancellationToken) {#saveasync}

Saves this [`MapiContact`](../) into the given stream with vCard format asynchronously. The supported vCard version is 2.1

```csharp
public Task SaveAsync(Stream stream, ContactSaveFormat saveFormat, 
    CancellationToken token = default)
```

| Parameter | Description |
| --- | --- |
| stream | A stream to save to |
| token | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support writing |

### See Also

* enum [ContactSaveFormat](../../contactsaveformat/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(Stream, ContactSaveOptions, CancellationToken) {#saveasync_1}

Saves this [`MapiContact`](../) to the given stream using specified save options asynchronously. The supported save options is [`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions/)

```csharp
public Task SaveAsync(Stream stream, ContactSaveOptions saveOptions, 
    CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to |
| saveOptions | ContactSaveOptions | A save options |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* or *saveOptions* is `null` |
| NotSupportedException | *stream* does not support writing |
| ArgumentException | incorrect *saveOptions* |
| NotSupportedException | some save option is not supported |

### See Also

* class [ContactSaveOptions](../../contactsaveoptions/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## SaveAsync(Stream, CancellationToken) {#saveasync_2}

Saves this [`MapiContact`](../) to the given stream asynchronously. The supported save format is vCard.

```csharp
public Task SaveAsync(Stream stream, CancellationToken token = default)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to. |
| token | CancellationToken | Propagates notification that operations should be canceled. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)


