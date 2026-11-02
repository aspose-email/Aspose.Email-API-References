---
title: MapiContact.Save
second_title: Aspose.Email for .NET API Reference
description: MapiContact method. Saves the contact to a vCard 2.1 file
type: docs
weight: 160
url: /net/aspose.email.mapi/mapicontact/save/
---
## Save(string) {#save_3}

Saves the contact to a vCard 2.1 file.

```csharp
public void Save(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to write. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## Save(string, ContactSaveFormat) {#save_4}

Saves the contact to a file in the specified format with the default options.

```csharp
public void Save(string filePath, ContactSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to write. |
| saveFormat | ContactSaveFormat | The format: vCard (the default), WebDAV or MSG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |
| NotSupportedException | *saveFormat* is not supported. |

### See Also

* enum [ContactSaveFormat](../../contactsaveformat/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## Save(string, ContactSaveOptions) {#save_5}

Saves the contact to a file with the specified options.

```csharp
public void Save(string filePath, ContactSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | The path of the file to write. |
| saveOptions | ContactSaveOptions | The options; their class selects the format: [`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions/), [`WebDavContactSaveOptions`](../../webdavcontactsaveoptions/) or [`MapiContactSaveOptions`](../../mapicontactsaveoptions/). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or empty. |
| ArgumentNullException | *saveOptions* is `null`. |
| NotSupportedException | The vCard version in *saveOptions* is not supported. |

### See Also

* class [ContactSaveOptions](../../contactsaveoptions/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Saves the contact to a stream in vCard 2.1 format.

```csharp
public void Save(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveFormat) {#save_1}

Saves the contact to a stream in the specified format with the default options.

```csharp
public void Save(Stream stream, ContactSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| saveFormat | ContactSaveFormat | The format: vCard (the default), WebDAV or MSG. |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null`. |
| NotSupportedException | *stream* does not support writing. |
| NotSupportedException | *saveFormat* is not supported. |

### See Also

* enum [ContactSaveFormat](../../contactsaveformat/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveOptions) {#save_2}

Saves the contact to a stream with the specified options.

```csharp
public void Save(Stream stream, ContactSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write to. |
| saveOptions | ContactSaveOptions | The options; their class selects the format: [`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions/), [`WebDavContactSaveOptions`](../../webdavcontactsaveoptions/) or [`MapiContactSaveOptions`](../../mapicontactsaveoptions/). |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* or *saveOptions* is `null`. |
| NotSupportedException | *stream* does not support writing. |
| ArgumentException | The format of *saveOptions* does not match its class. |
| NotSupportedException | The vCard version in *saveOptions* is not supported. |

### See Also

* class [ContactSaveOptions](../../contactsaveoptions/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)


