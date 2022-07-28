---
title: Save
second_title: Aspose.Email för .NET API-referens
description: Sparar dettaMapiContactaspose.email.mapi/mapicontact till vCard-filen med ett standardalternativ. Den vCard-version som stöds är 2.1
type: docs
weight: 140
url: /sv/net/aspose.email.mapi/mapicontact/save/
---
## Save(string) {#save_3}

Sparar detta[`MapiContact`](../../mapicontact) till vCard-filen med ett standardalternativ. Den vCard-version som stöds är 2.1

```csharp
public void Save(string filePath)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Ett vCard-filnamn |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | *filePath* är`null`eller`tömma` |

### Se även

* class [MapiContact](../../mapicontact)
* namnutrymme [Aspose.Email.Mapi](../../mapicontact)
* hopsättning [Aspose.Email](../../../)

---

## Save(string, ContactSaveFormat) {#save_4}

Sparar detta[`MapiContact`](../../mapicontact)till den angivna filen med ett format som använder standardalternativen. Det sparade formatet som stöds är vCard.

```csharp
public void Save(string filePath, ContactSaveFormat saveFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Ett vCard-filnamn |
| saveFormat | ContactSaveFormat | Ett sparformat |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | *filePath* är`null`eller`tömma` |
| NotSupportedException | det angivna formatet stöds inte |

### Se även

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* namnutrymme [Aspose.Email.Mapi](../../mapicontact)
* hopsättning [Aspose.Email](../../../)

---

## Save(string, ContactSaveOptions) {#save_5}

Sparar detta[`MapiContact`](../../mapicontact) till fil med angivna sparaalternativ. De sparade alternativen som stöds är[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(string filePath, ContactSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | String | Ett vCard-filnamn |
| saveOptions | ContactSaveOptions | Ett spara alternativ |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentException | *filePath* är`null`eller`tömma` |
| ArgumentNullException | *saveOptions* är`null` |
| NotSupportedException | vissa spara alternativ stöds inte |

### Se även

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* namnutrymme [Aspose.Email.Mapi](../../mapicontact)
* hopsättning [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Sparar detta[`MapiContact`](../../mapicontact) in i den givna strömmen med vCard-format. Den vCard-version som stöds är 2.1

```csharp
public void Save(Stream stream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | En stream att spara till |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *stream* är`null` |
| NotSupportedException | *stream* stöder inte skrivande |

### Se även

* class [MapiContact](../../mapicontact)
* namnutrymme [Aspose.Email.Mapi](../../mapicontact)
* hopsättning [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveFormat) {#save_1}

Sparar detta[`MapiContact`](../../mapicontact) till den givna strömmen med ett format som använder standardalternativen. Det sparade formatet som stöds är vCard

```csharp
public void Save(Stream stream, ContactSaveFormat saveFormat)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | En stream att spara till |
| saveFormat | ContactSaveFormat | Ett sparformat |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *stream* är`null` |
| NotSupportedException | *stream* stöder inte skrivande |
| NotSupportedException | Det angivna formatet stöds inte |

### Se även

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* namnutrymme [Aspose.Email.Mapi](../../mapicontact)
* hopsättning [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveOptions) {#save_2}

Sparar detta[`MapiContact`](../../mapicontact) till den givna strömmen med angivna sparalternativ. De sparade alternativen som stöds är[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(Stream stream, ContactSaveOptions saveOptions)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | En stream att spara till |
| saveOptions | ContactSaveOptions | Ett spara alternativ |

### Undantag

| undantag | skick |
| --- | --- |
| ArgumentNullException | *stream*eller*saveOptions* är`null` |
| NotSupportedException | *stream* stöder inte skrivande |
| ArgumentException | felaktig*saveOptions* |
| NotSupportedException | vissa spara alternativ stöds inte |

### Se även

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* namnutrymme [Aspose.Email.Mapi](../../mapicontact)
* hopsättning [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
