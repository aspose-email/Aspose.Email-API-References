---
title: Save
second_title: Aspose.Email für .NET-API-Referenz
description: Speichert diesMapiContactaspose.email.mapi/mapicontact in die vCard-Datei mit Standardoptionen. Die unterstützte vCard-Version ist 2.1
type: docs
weight: 140
url: /de/net/aspose.email.mapi/mapicontact/save/
---
## Save(string) {#save_3}

Speichert dies[`MapiContact`](../../mapicontact) in die vCard-Datei mit Standardoptionen. Die unterstützte vCard-Version ist 2.1

```csharp
public void Save(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Ein vCard-Dateiname |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | *filePath* ist`Null`oder`leer` |

### Siehe auch

* class [MapiContact](../../mapicontact)
* namensraum [Aspose.Email.Mapi](../../mapicontact)
* Montage [Aspose.Email](../../../)

---

## Save(string, ContactSaveFormat) {#save_4}

Speichert dies[`MapiContact`](../../mapicontact)in die angegebene Datei mit einem Format unter Verwendung der Standardoptionen. Das unterstützte Speicherformat ist vCard.

```csharp
public void Save(string filePath, ContactSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Ein vCard-Dateiname |
| saveFormat | ContactSaveFormat | Ein sicheres Format |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | *filePath* ist`Null`oder`leer` |
| NotSupportedException | das angegebene Format wird nicht unterstützt |

### Siehe auch

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* namensraum [Aspose.Email.Mapi](../../mapicontact)
* Montage [Aspose.Email](../../../)

---

## Save(string, ContactSaveOptions) {#save_5}

Speichert dies[`MapiContact`](../../mapicontact) in Datei mit angegebenen Speicheroptionen. Die unterstützten Speicheroptionen sind[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(string filePath, ContactSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Ein vCard-Dateiname |
| saveOptions | ContactSaveOptions | Eine Speicheroption |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentException | *filePath* ist`Null`oder`leer` |
| ArgumentNullException | *saveOptions* ist`Null` |
| NotSupportedException | Einige Speicheroptionen werden nicht unterstützt |

### Siehe auch

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* namensraum [Aspose.Email.Mapi](../../mapicontact)
* Montage [Aspose.Email](../../../)

---

## Save(Stream) {#save}

Speichert dies[`MapiContact`](../../mapicontact) in den angegebenen Stream mit vCard-Format. Die unterstützte vCard-Version ist 2.1

```csharp
public void Save(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream zum Speichern |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *stream* ist`Null` |
| NotSupportedException | *stream* unterstützt das Schreiben nicht |

### Siehe auch

* class [MapiContact](../../mapicontact)
* namensraum [Aspose.Email.Mapi](../../mapicontact)
* Montage [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveFormat) {#save_1}

Speichert dies[`MapiContact`](../../mapicontact) zum gegebenen Stream mit einem Format, das die Standardoptionen verwendet. Das unterstützte Speicherformat ist vCard

```csharp
public void Save(Stream stream, ContactSaveFormat saveFormat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream zum Speichern |
| saveFormat | ContactSaveFormat | Ein sicheres Format |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *stream* ist`Null` |
| NotSupportedException | *stream* unterstützt das Schreiben nicht |
| NotSupportedException | Das angegebene Format wird nicht unterstützt |

### Siehe auch

* enum [ContactSaveFormat](../../contactsaveformat)
* class [MapiContact](../../mapicontact)
* namensraum [Aspose.Email.Mapi](../../mapicontact)
* Montage [Aspose.Email](../../../)

---

## Save(Stream, ContactSaveOptions) {#save_2}

Speichert dies[`MapiContact`](../../mapicontact) zum gegebenen Stream mit spezifizierten Speicheroptionen. Die unterstützten Speicheroptionen sind[`VCardSaveOptions`](../../../aspose.email.personalinfo.vcard/vcardsaveoptions)

```csharp
public void Save(Stream stream, ContactSaveOptions saveOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream zum Speichern |
| saveOptions | ContactSaveOptions | Eine Speicheroption |

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| ArgumentNullException | *stream*oder*saveOptions* ist`Null` |
| NotSupportedException | *stream* unterstützt das Schreiben nicht |
| ArgumentException | falsch*saveOptions* |
| NotSupportedException | Einige Speicheroptionen werden nicht unterstützt |

### Siehe auch

* class [ContactSaveOptions](../../contactsaveoptions)
* class [MapiContact](../../mapicontact)
* namensraum [Aspose.Email.Mapi](../../mapicontact)
* Montage [Aspose.Email](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
