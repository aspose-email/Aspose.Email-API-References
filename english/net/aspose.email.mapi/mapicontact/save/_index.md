---
title: MapiContact.Save
second_title: Aspose.Email for .NET API Reference
description: MapiContact method. Saves this MapiContact to the vCard file with a default options. The supported vCard version is 2.1
type: docs
weight: 140
url: /net/aspose.email.mapi/mapicontact/save/
---
## Save(string) {#save_3}

Saves this [`MapiContact`](../) to the vCard file with a default options. The supported vCard version is 2.1

```csharp
public void Save(string filePath)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A vCard file name |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | *filePath* is `null` or `empty` |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## Save(string, ContactSaveFormat) {#save_4}

Saves this [`MapiContact`](../) to the specified file with a format using the default options. The supported save format is vCard.

```csharp
public void Save(string filePath, ContactSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A vCard file name |
| saveFormat | ContactSaveFormat | A save format |

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

## Save(string, ContactSaveOptions) {#save_5}

Saves this [`MapiContact`](../) into file using specified save options. The supported save options is [`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions/)

```csharp
public void Save(string filePath, ContactSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| filePath | String | A vCard file name |
| saveOptions | ContactSaveOptions | A save options |

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

## Save(Stream) {#save}

Saves this [`MapiContact`](../) into the given stream with vCard format. The supported vCard version is 2.1

```csharp
public void Save(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support writing |

### See Also

* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveFormat) {#save_1}

Saves this [`MapiContact`](../) to the given stream with a format using the default options. The supported save format is vCard

```csharp
public void Save(Stream stream, ContactSaveFormat saveFormat)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to |
| saveFormat | ContactSaveFormat | A save format |

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | *stream* is `null` |
| NotSupportedException | *stream* does not support writing |
| NotSupportedException | The specified format is not supported |

### See Also

* enum [ContactSaveFormat](../../contactsaveformat/)
* class [MapiContact](../)
* namespace [Aspose.Email.Mapi](../../mapicontact/)
* assembly [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveOptions) {#save_2}

Saves this [`MapiContact`](../) to the given stream using specified save options. The supported save options is [`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions/)

```csharp
public void Save(Stream stream, ContactSaveOptions saveOptions)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | A stream to save to |
| saveOptions | ContactSaveOptions | A save options |

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


