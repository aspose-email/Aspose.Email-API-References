---
title: Save
second_title: Aspose.Email for .NET API Reference
description: 
type: docs
weight: 140
url: /net/aspose.email.personalinfo.vcard/vcardcontact/save/
---
## VCardContact.Save method (1 of 6)

Saves this [`MapiContact`](../../../aspose.email.mapi/mapicontact) to the vCard file with a default options. The supported vCard version is 2.1

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

* class [VCardContact](../../vcardcontact)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assembly [Aspose.Email](../../../)

---

## VCardContact.Save method (2 of 6)

Saves this [`MapiContact`](../../../aspose.email.mapi/mapicontact) to the specified file with a format using the default options. The supported save format is vCard.

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

* enum [ContactSaveFormat](../../../aspose.email.mapi/contactsaveformat)
* class [VCardContact](../../vcardcontact)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assembly [Aspose.Email](../../../)

---

## VCardContact.Save method (3 of 6)

Saves this [`MapiContact`](../../../aspose.email.mapi/mapicontact) into file using specified save options. The supported save options is [`VCardSaveOptions`](../../vcardsaveoptions)

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

* class [ContactSaveOptions](../../../aspose.email.mapi/contactsaveoptions)
* class [VCardContact](../../vcardcontact)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assembly [Aspose.Email](../../../)

---

## VCardContact.Save method (4 of 6)

Saves this [`MapiContact`](../../../aspose.email.mapi/mapicontact) into the given stream with vCard format. The supported vCard version is 2.1

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

* class [VCardContact](../../vcardcontact)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assembly [Aspose.Email](../../../)

---

## VCardContact.Save method (5 of 6)

Saves this [`MapiContact`](../../../aspose.email.mapi/mapicontact) to the given stream with a format using the default options. The supported save format is vCard

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

* enum [ContactSaveFormat](../../../aspose.email.mapi/contactsaveformat)
* class [VCardContact](../../vcardcontact)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assembly [Aspose.Email](../../../)

---

## VCardContact.Save method (6 of 6)

Saves this [`MapiContact`](../../../aspose.email.mapi/mapicontact) to the given stream using specified save options. The supported save options is [`VCardSaveOptions`](../../vcardsaveoptions)

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

* class [ContactSaveOptions](../../../aspose.email.mapi/contactsaveoptions)
* class [VCardContact](../../vcardcontact)
* namespace [Aspose.Email.PersonalInfo.VCard](../../vcardcontact)
* assembly [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->